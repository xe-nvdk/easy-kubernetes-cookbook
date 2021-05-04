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
| [Calibre Web](calibre-web) | Calibre-Web is a web app for browsing, reading and downloading eBooks using an existing Calibre database | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Ghost](ghost) | The world's most popular modern publishing platform for creating a new media platform. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Grafana](grafana) | The world's most popular technology used to compose observability dashboards. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [InfluxDB OSS](influxdb-oss-v2.0.3) | InfluxDB OSS is an open source time series database designed to handle high write and query loads | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
