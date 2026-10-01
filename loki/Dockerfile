FROM grafana/loki:3.5.5
COPY loki/config.yaml /etc/loki/config.yaml
ENTRYPOINT ["/usr/bin/loki"]
CMD ["-config.file=/etc/loki/config.yaml"]
