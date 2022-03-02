FROM fluent/fluentd:v1.12.2-1.0
USER root
RUN gem install fluent-plugin-docker_metadata_elastic_filter
RUN gem install fluent-plugin-grafana-loki
RUN gem install fluent-plugin-record-modifier --no-document
USER fluent
