FROM grafana/tempo:2.8.2
COPY tempo/config.yaml /etc/tempo/config.yaml
ENTRYPOINT ["/tempo"]
CMD ["-config.file=/etc/tempo/config.yaml"]
