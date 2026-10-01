FROM grafana/mimir:2.17.0
COPY observability/mimir/config.yaml /etc/mimir/config.yaml
ENTRYPOINT ["/bin/mimir"]
CMD ["-config.file=/etc/mimir/config.yaml"]
