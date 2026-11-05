# Google

Sign in to PeltyCMS with Google

Official single sign-on for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Teams that want one-click login with an identity provider customers already use.

## Features

- Client and staff sign-in with **Google**
- OAuth / OIDC redirect + session handled by Pelty
- Account linking for existing customers
- Sandboxed WASM SSO provider

## How it works

1. Install **Google** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/sso-google) inside Pelty Admin → Addons.
2. Open Pelty Admin → Authentication, create a Google app, paste client id/secret, and enable the SSO button.
3. Customers hit checkout / login / order flow as usual — Google runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working Google credentials
- Outbound HTTPS from your panel

## Get it

**[Google on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/sso-google)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
