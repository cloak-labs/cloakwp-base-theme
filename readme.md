# CloakWP Theme
This is a super barebones theme for headless WordPress projects (or more specifically [CloakWP](https://github.com/cloak-labs/cloakwp) projects). It is built primarily just to meet the WordPress requirement of having an active theme; it doesn't actually provide any headless functionality -- for that, check out the [CloakWP Plugin](https://github.com/cloak-labs/cloakwp/tree/main/plugins/cloakwp-plugin).

## Features:
- All non-admin routes redirect to wp-admin (essentially turning off the traditional WordPress front-end)

## Installation
If you're not using [CloakWP Bedrock](https://github.com/cloak-labs/cloakwp-bedrock), which pre-installs the CloakWP Base Theme for you, you can install the theme via Composer by running:
```bash
composer require cloak-labs/cloakwp-base-theme
```

Not using Composer? First, strongly consider using Composer. Otherwise, download the theme's GitHub repo and upload it to WordPress as a .zip