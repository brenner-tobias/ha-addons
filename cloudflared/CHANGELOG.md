## What’s changed
## 🚨 Breaking changes

- Remove built-in NGINX (workaround for live logs issues) @felipecrs (#913)

> If you are using the previously included NGINX proxy with Port 8321 (`http://localhost:8321/`), you have to switch to Port 8123 (`http://homeassistant:8123/`) in your Cloudflared Configuration

## ⬆️ Dependency updates

- ⬆️ Update cloudflared to v2025.9.1 @[renovate[bot]](https://github.com/apps/renovate) (#907)
- ⬆️ Update ghcr.io/hassio-addons/base Docker tag to v18.1.3 @[renovate[bot]](https://github.com/apps/renovate) (#910)
- ⬆️ Update docker/login-action action to v3.6.0 @[renovate[bot]](https://github.com/apps/renovate) (#912)
- ⬆️ Update peter-evans/repository-dispatch action to v4 @[renovate[bot]](https://github.com/apps/renovate) (#916)
- ⬆️ Update ghcr.io/hassio-addons/base Docker tag to v18.1.4 @[renovate[bot]](https://github.com/apps/renovate) (#917)
