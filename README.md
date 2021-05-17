<p align="center">
  <img src="https://cambiodigital-ol.com/wp-content/uploads/2019/02/Kubernetes_New.png" />
</p>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B34N5TU)

# Easy Kubernetes Cookbook
I'm leaving Docker Swarm and Docker standalone to run all my workloads in Kubernetes, so I'm building a few recipes with what I need, and I posting here to share with others.

## Assumptions

All these recipes are created using Traefik as Ingress. So, in the services that require access from outside, I'm setting an IngressRoute with TLS. Also, as I used a single node of Kubernetes, I set HostPath volumes to persist the containers' data.

## Contribute

If you see that something can be better, go ahead a contribute with this Cookbook.

## Recipes

| Applications         | Description | Author |
|----------------------|-------------|:------:|
| [Calibre Web](calibre-web) | Calibre-Web is a web app for browsing, reading and downloading eBooks using an existing Calibre database. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Ghost](ghost) | The world's most popular modern publishing platform for creating a new media platform. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Grafana](grafana) | The world's most popular technology used to compose observability dashboards. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [InfluxDB OSS](influxdb-oss-v2.0.3) | InfluxDB OSS is an open source time series database designed to handle high write and query loads. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [MariaDB](mariadb) | MariaDB Server is one of the most popular open source relational databases. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Matomo](matomo) | Google Analytics alternative that protects your data and your customers' privacy. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Nginx](nginx) | nginx [engine x] is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Portainer Business]([portainer-business-v2.0) | Solution to manage Kubernetes and Docker Swarm clusters from a GUI. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Telegraf](telegraf) | Telegraf is a plugin-driven server agent for collecting and sending metrics and events from diverse systems. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Traefik](traefik-v2.3.5) | Traefik is an open-source Edge Router that makes publishing your services a fun and easy experience. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
| [Wordpress](wordpress) | WordPress is open source software you can use to create a beautiful website, blog, or app. | [Ignacio Van Droogenbroeck](github.com/xe-nvdk) |
