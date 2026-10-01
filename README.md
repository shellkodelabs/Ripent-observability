# Ripent Observability

Dedicated source repository for Ripent's open-source observability images:
Alloy, ClickHouse, Grafana, Loki, Mimir, Tempo, and Langfuse.

Each directory contains the pinned upstream-based Dockerfile and the runtime
configuration copied into the image. AWS CodePipeline builds each component
independently and publishes an immutable commit-tagged image to Ripent ECR.
