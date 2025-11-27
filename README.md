# Unison OS Base Image

Defines the base container image for all Unison services.
Goals:
- Stable Ubuntu LTS base.
- Minimal packages.
- Non-root runtime user.

## Status
Supporting infra (active) — base layer for service Dockerfiles.

## Build/Test
```bash
docker build -t unison-os:dev .
```
