# Changelog

## 0.30.0-openclaw.1

- Synced with upstream v0.30.0 and the subsequent comment fix (16dc791).
- Updated Tailscale to v1.102.4 and the app base image to v21.0.5.
- Migrated the legacy log_level option to log_suppression.
- Migrated local_subnets route entries to explicit subnet addresses.
- Moved the OpenClaw service registration to the new S6 user bundle location.

## 0.29.1-openclaw.1

- Synced the app with upstream Tailscale v0.29.0.
- Preserved the OpenClaw sharing integration.
- Updated Home Assistant app configuration mappings to their current names.
