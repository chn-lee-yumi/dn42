# Software as a Service (offline)

## Introduction

**This service only can be accessed in the DN42 network.**

Now our SaaS only has one type: Prometheus + Grafana.

## Usage

Open control panel: http://saas.gcc.dn42

The username is `dn42`, the password is `dn42`.

Create a new instance, wait about 5 seconds, you will see your instance is UP and have a DN42 IP.

Open this IP in the web browser to access Grafana. You should configure Prometheus in Grafana first if you want to use it.

The Prometheus data source URL is `http://localhost:9090` ( in Grafana).
