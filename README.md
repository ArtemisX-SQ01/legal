# H-VNCareer app legal pages

Public Privacy Policies and Terms of Service. This repository contains only legal website content; no Android source, VPN profiles, credentials, or ad configuration.

## AnoBrowser

- Privacy: https://artemisx-sq01.github.io/legal/anobrowser/privacy.html
- Terms: https://artemisx-sq01.github.io/legal/anobrowser/terms.html

## NijPath Browser

- Privacy: https://artemisx-sq01.github.io/legal/nijpath/privacy.html
- Terms: https://artemisx-sq01.github.io/legal/nijpath/terms.html
- Package: `com.tt.browser.tw` (Premium edition: `com.tt.browser.tw.premium`)

These URLs match the links already configured in NijPath Browser. The NijPath policy describes the user's own WireGuard server and does not reuse AnoBrowser's operator no-logs claim. Review the final advertising, Firebase, and data-safety configuration before publishing.

Operator: H-VNCareer. Contact: long123v123@gmail.com. AnoBrowser effective date: 26 September 2026. The operator has confirmed that its AnoBrowser VPN servers do not store logs; this statement does not cover a server supplied by a NijPath user.

## Adding another app

Create a separate directory named after the app, containing its own privacy.html and terms.html. Add links to the root index.html. Write disclosures for that app's actual data processing and SDKs rather than copying another app's claims unchanged. Keep published URL paths stable.

## GitHub Pages

Publish from Settings → Pages → Deploy from a branch → main → / (root). The .nojekyll file disables Jekyll. Link each app's policies within the app and in its store listing. Check disclosures whenever features or SDKs change.
