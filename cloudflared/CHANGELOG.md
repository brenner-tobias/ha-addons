## What's Changed

### BREAKING CHANGES

The add-on reads your `configuration.yaml` to detect your Home Assistant port and if SSL is used. **If you have changed the default port or
enabled SSL in the HTTP integration**, you must keep the entire `http:` block directly in `configuration.yaml`. Do **not** move it to a
`!include` file or a `!include_dir_*` directory, as the add-on does not follow additional YAML files.

### Bug Fixes

* Fix add-on not properly detecting when HA is using HTTPS by @felipecrs in https://github.com/brenner-tobias/addon-cloudflared/pull/898

**Full Changelog**: https://github.com/brenner-tobias/addon-cloudflared/compare/v5.3.7...v5.3.8