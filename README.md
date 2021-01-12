# docker-env

Set docker env with databases containers with prometheus monitoring and stress test services

Environment:
 - 3 nodes cassandra cluster
 - prometheus (gathering metrics)
 - grafana (visualize metrics) *not set yet

To set the environment:
 - grafana dashboard and promethues config from  - https://grafana.com/grafana/dashboards/5408
 - build a custom image for cassandra - "$docker build -t <image_name> ./configs/cass" to install the prometheus/jmx-reporter
 - run $docker-compose up -d