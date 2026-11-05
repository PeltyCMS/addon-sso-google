# Google

Sign in to PeltyCMS with Google

Official **single sign-on** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `sso-google`.

## Why this addon

Teams that want one-click login with an identity provider customers already use.

## Features

- Client and staff sign-in with **Google**
- OAuth / OIDC redirect + session handled by Pelty
- Account linking for existing customers
- Sandboxed WASM SSO provider

## How it works

1. Install **Google** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/sso-google) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your Google credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use Google automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid Google API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to Google

## Get it

[Google on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/sso-google)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/sso-google
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab
