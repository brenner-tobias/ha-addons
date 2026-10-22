### 🔒 Security

- Fixes trust in compromised eMudhra intermediate CA certificates by updating cloudflared to v2026.10.3 (fix introduced in v2026.10.2). Weak private keys of eight eMudhra intermediates allowed forged certificates for arbitrary domains, enabling interception or modification of TLS traffic. All users of v7.0.18 and earlier are advised to update immediately. See the [Cloudflare advisory](https://blog.cloudflare.com/emudhra-certificate-compromise) for details. (#1106, #1105)


### ⬆️ Dependency updates


- Update yq to 4.53.3-r2 @elcajon ([#1104](https://github.com/homeassistant-apps/app-cloudflared/pull/1104))
- ⬆️ Update cloudflared to v2026.10.2 @[renovate[bot]](https://github.com/apps/renovate) ([#1103](https://github.com/homeassistant-apps/app-cloudflared/pull/1103))
- ⬆️ Update cloudflared to v2026.10.3 @[renovate[bot]](https://github.com/apps/renovate) ([#1105](https://github.com/homeassistant-apps/app-cloudflared/pull/1105))
