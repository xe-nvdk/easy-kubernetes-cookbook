# Easy Kubernetes Cookbook
I'm leaving Docker Swarm and Docker standalone to run all my workloads in Kubernetes, so, I'm building a few recipes with what I need and I posted here to share with others.

## Assumptions

All this recipes are created using Traefik as Ingress. So, in the services that require accesed from outside I´m setting an IngressRoute with TLS. Also, as I used a single node of Kubernetes, I set HostPath volumes to persist the data of the containers. 

## Contribute

If you see that something can be improved, go ahead a contribute with this Cookbook.
