# apps/workspace-console (A1)

Drop the extracted workspace/dashboard source here from `/opt/riven/spa-frontend/src-backup-*.tar.gz`.
Gate: G-REC-1. Do not commit secrets. Do not modify build pipeline yet — capture first, refactor later.

## Current routing status

`console.rivenai.io` is temporarily routed to the existing `riven-spa-frontend:9090` container
(`infra/traefik/dynamic/console-rivenai-io.yaml`). Once this directory contains a standalone
console build, update the Traefik route to point to the new `workspace-console` container.
