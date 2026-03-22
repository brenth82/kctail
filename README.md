# Keycloak on Koyeb (Optimized Build)

This repo deploys Keycloak 26.5.6 on Koyeb using an optimized container image built with `kc.sh build`.

It is intended for:
- Koyeb
- Neon Postgres
- later use with a custom domain for OIDC (for example Tailscale custom OIDC)

## Why this image exists

The standard `quay.io/keycloak/keycloak:26.5.6` image with:

```bash
kc.sh start