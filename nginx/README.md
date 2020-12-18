# NGINX - Web Server

This recipe deploy several resources that includes a deployment, service, and IngressRoute. You need to create one folder to persist your data.

```
$ mkdir -p /mnt/data/nginx-data
```

Once folder was created, you need to modify the IngressRoute with your address, after that, you're ready to deploy your NGINX Web Server:

```
$ kubectl apply -f nginx.yml
```
