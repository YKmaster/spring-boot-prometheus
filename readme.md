# Spring Boot REST application with Prometheus support

This is a template application for Spring Boot REST application instrumented to
expose Prometheus metrics.

## Endpoints used by Kubernetes

# new change
# change v1
# change v2
# change test
# change 1

This quickstart exposes the following endpoints important for Kubernetes deployments:
- `/actuator/health` - Spring Boot endpoint indicating health. Used by Kubernetes as readiness probe.
- `/actuator/metrics` - Prometheus metrics. Invoked periodically and collected by Prometheus Kubernetes scraper.
