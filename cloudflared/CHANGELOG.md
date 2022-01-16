## v0.2.1
- Fixed config parameter name

## v0.2.1
- Bump Cloudflared to 2022.1.2

## v0.2.0
- Added possibility to configure additional hosts to forward to

## v0.1.9

- Bump Cloudflared to 2022.1.0
- Disabled Auto-Update of Cloudflared
- Automatically detect HA port, removed config option

## v0.1.8

- Bump Cloudflared to 2021.12.0
- Force DNS creation if there is an existing entry

## v0.1.7

- Changed startup config to default "Application" to avoid race-condition with Nginxproxymanager

## v0.1.6

- Added tunnel connection to Nginxproxymanager

## v0.1.5

- Optimised reset

## v0.1.4

- Changed folder of Cloudflared files to /data/ for persistent storage
- Included a reset option in the config to delete all existing cloudflared files
- Optimised logging
- Made config parameter to reset cloudflared file optional
- Optimised documentation