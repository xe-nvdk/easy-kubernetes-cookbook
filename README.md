![kubernetes](https://cambiodigital-ol.com/wp-content/uploads/2019/02/Kubernetes_New.png)

# Easy Kubernetes Cookbook
I'm leaving Docker Swarm and Docker standalone to run all my workloads in Kubernetes, so I'm building a few recipes with what I need, and I posting here to share with others.

## Assumptions

All these recipes are created using Traefik as Ingress. So, in the services that require access from outside, I'm setting an IngressRoute with TLS. Also, as I used a single node of Kubernetes, I set HostPath volumes to persist the containers' data.

## Contribute

If you see that something can be better, go ahead a contribute with this Cookbook.

## Recipes

| Applications         | Description | Author |
|----------------------|-------------|:------:|
| Calibre Web | Calibre-Web is a web app for browsing, reading and downloading eBooks using an existing Calibre database | [Ignacio Van Droogenbroeck(xe-nvdk) |
