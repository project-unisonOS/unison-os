# Unison OS Base Image

## Role in UnisonOS
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

## Docs

Full docs at https://project-unisonos.github.io
- Repo roles: `unison-docs/dev/unison-repo-roles.md`
- Platform roadmap: `unison-docs/roadmap/deployment-platform-roadmap.md`
