# docker-env

Set docker env with databases containers with prometheus monitoring and stress test services

Environment:
 - 3 nodes cassandra cluster
 - prometheus (gathering metrics)
 - grafana (visualize metrics) *not set yet

To set the environment:
 - build a custom image for cassandra - "$docker build -t ./configs/cass" to install the prometheus/jmx-reporter
 - run $docker-compose up -d