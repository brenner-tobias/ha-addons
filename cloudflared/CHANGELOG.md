## What’s changed
## 🚨 Breaking change 🚨

It is now mandatory to add the option `warp_routes` if `warp_enable` is set to `true`, 
otherwise the add on will not start.

You can safely ignore this if you don't use the Cloudflare Warp functionality. 

- Remove Manager API calls @elcajon (#72)

## 🚀 Enhancements

- Add image signing - CAS Codenotary @elcajon (#69)

## ⬆️ Dependency updates

- Bump docker/build-push-action from 2.9.0 to 2.10.0 @dependabot (#70)
