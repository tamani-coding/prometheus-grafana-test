# prometheus-grafana-test
prometheus-grafana-test

A simple example for a Prometheus and Grafana Monitoring setup with an example spring boot backend exposing metrics.

`./docker/docker-compose.yml`
	- starts prometheus and grafana

`./docker/data/`
	- contains data for grafana and prometheus
	
See `docker/data/prometheus/config/prometheus.yml` for the prometheus configuration and change the target to your IP address to enable scraping metrics for your locally running service.

References:

- https://grafana.com/grafana/dashboards/893
- https://github.com/prometheus/prometheus
- https://www.mokkapps.de/blog/monitoring-spring-boot-application-with-micrometer-prometheus-and-grafana-using-custom-metrics/

