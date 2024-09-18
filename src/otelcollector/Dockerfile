FROM ubuntu:latest

COPY _build/otelcol /otelcol

COPY otelcol-config.yml /etc/otelcol-config.yml
COPY otelcol-config-extras.yml /etc/otelcol-config-extras.yml
#CMD ["/otelcol", "--config", "/etc/otelcol-config.yml", "--config", "/etc/otelcol-config-extras.yml"]