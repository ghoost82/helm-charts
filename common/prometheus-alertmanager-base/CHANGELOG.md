## 1.3.0

* Allow disabling default notification templates.

## 1.2.3

* Disable vice-president in ingress by default

## 1.2.2

* Set Chart `apiVersion: v2`.
* Added annotation triggering certificate automation: `kubernetes.io/tls-acme: "true"`. 

## 1.0.2

* Adds alert for cluster status.
* Adds Grafana dashboard.

## 1.0.1

* Adds [Prometheus alerts](./templates/alerts) for common Alertmanager errors.  
  **NOTE**: Only useful if Alertmanager is part of an HA cluster and the Prometheus evaluating the alerts sends alerts to all members of that cluster. 

## 1.0.0

* Init Helm chart that shall serve as a base for Prometheus Alertmanager instances.
