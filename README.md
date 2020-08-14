# prometheus-dockercompose
Docker compose to run prometheus and grafana


## Connection to prometheus

localhost:9090 
No targets beyond prometheus are in the config.
Add your targets in prometheus/prometheus.yml

## Connection to Grafana

localhost:3000

Grafana will be bootstraped with datasource to prometheus.


