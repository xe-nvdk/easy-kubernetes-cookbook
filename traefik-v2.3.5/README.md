# Traefik v2.3.5

This recipe deploy an ingress and several custom resource definition, Traefik V2.3.5 and an Hello World to test the SSL configuration. 

You can run this recipe cloning this folder, changing the email for Let's Encrypt configuration in the deployment.yml file and "mydomain.com" in the file hello.yml, and running the following:

```
$ kubectl apply -f crd.yml
```

```
$ kubectl apply -f deployment.yml
```

```
$ kubectl apply -f hello.yml
```
![traefik](https://doc.traefik.io/traefik/assets/img/webui-dashboard.png)
