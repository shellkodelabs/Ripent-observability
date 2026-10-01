FROM grafana/alloy:v1.11.0
COPY observability/alloy/config.alloy /etc/alloy/config.alloy
ENTRYPOINT ["alloy"]
CMD ["run", "/etc/alloy/config.alloy"]
