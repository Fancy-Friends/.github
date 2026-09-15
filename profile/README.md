# Fancy Friends

**The connectors for [Fancy UI](https://ui.particle.academy)'s workflow engine, fancy-flow.** One
repository per third-party service — payments, email, CRMs, spreadsheets, social — each shipping
the same connector as four packages, one per runtime.

## Why they live here

The Fancy kit itself lives in [Particle Academy](https://github.com/Particle-Academy). A connector
for every service means hundreds of repositories, so they have an organisation of their own: the
Particle Academy repo list stays readable, and the connectors, which all share one shape, stay
together.

## Every connector, four ways

| Runtime | Package |
|---|---|
| The editor, on every host | `@particle-academy/<service>-ui` |
| Node | `@particle-academy/<service>-js` |
| PHP 8.4+ | `particle-academy/<service>-php` |
| Python 3.11+ | `fancy-<service>` |

Every connector runs its nodes in **fake mode** with no credentials at all, so a workflow can be
built before an account exists. The npm packages are published through npm Trusted Publishing and
carry a provenance attestation naming the repository and workflow that built them.

## The connectors — 23 live

| Connector | Domain | npm | Packagist | PyPI |
|---|---|---|---|---|
| [Amazon SES](https://github.com/Fancy-Friends/amazon-ses) | email | [amazon-ses-ui](https://www.npmjs.com/package/@particle-academy/amazon-ses-ui) · [amazon-ses-js](https://www.npmjs.com/package/@particle-academy/amazon-ses-js) | [amazon-ses-php](https://packagist.org/packages/particle-academy/amazon-ses-php) | [fancy-amazon-ses](https://pypi.org/project/fancy-amazon-ses/) |
| [Buffer](https://github.com/Fancy-Friends/buffer) | marketing | [buffer-ui](https://www.npmjs.com/package/@particle-academy/buffer-ui) · [buffer-js](https://www.npmjs.com/package/@particle-academy/buffer-js) | [buffer-php](https://packagist.org/packages/particle-academy/buffer-php) | [fancy-buffer](https://pypi.org/project/fancy-buffer/) |
| [Discord](https://github.com/Fancy-Friends/discord) | messaging | [discord-ui](https://www.npmjs.com/package/@particle-academy/discord-ui) · [discord-js](https://www.npmjs.com/package/@particle-academy/discord-js) | [discord-php](https://packagist.org/packages/particle-academy/discord-php) | [fancy-discord](https://pypi.org/project/fancy-discord/) |
| [Facebook Lead Ads](https://github.com/Fancy-Friends/facebook-lead-ads) | marketing | [facebook-lead-ads-ui](https://www.npmjs.com/package/@particle-academy/facebook-lead-ads-ui) · [facebook-lead-ads-js](https://www.npmjs.com/package/@particle-academy/facebook-lead-ads-js) | [facebook-lead-ads-php](https://packagist.org/packages/particle-academy/facebook-lead-ads-php) | [fancy-facebook-lead-ads](https://pypi.org/project/fancy-facebook-lead-ads/) |
| [Facebook Pages](https://github.com/Fancy-Friends/facebook-pages) | marketing | [facebook-pages-ui](https://www.npmjs.com/package/@particle-academy/facebook-pages-ui) · [facebook-pages-js](https://www.npmjs.com/package/@particle-academy/facebook-pages-js) | [facebook-pages-php](https://packagist.org/packages/particle-academy/facebook-pages-php) | [fancy-facebook-pages](https://pypi.org/project/fancy-facebook-pages/) |
| [Gmail](https://github.com/Fancy-Friends/gmail) | email | [gmail-ui](https://www.npmjs.com/package/@particle-academy/gmail-ui) · [gmail-js](https://www.npmjs.com/package/@particle-academy/gmail-js) | [gmail-php](https://packagist.org/packages/particle-academy/gmail-php) | [fancy-gmail](https://pypi.org/project/fancy-gmail/) |
| [Google Ads](https://github.com/Fancy-Friends/google-ads) | marketing | [google-ads-ui](https://www.npmjs.com/package/@particle-academy/google-ads-ui) · [google-ads-js](https://www.npmjs.com/package/@particle-academy/google-ads-js) | [google-ads-php](https://packagist.org/packages/particle-academy/google-ads-php) | [fancy-google-ads](https://pypi.org/project/fancy-google-ads/) |
| [Google Analytics](https://github.com/Fancy-Friends/google-analytics) | analytics | [google-analytics-ui](https://www.npmjs.com/package/@particle-academy/google-analytics-ui) · [google-analytics-js](https://www.npmjs.com/package/@particle-academy/google-analytics-js) | [google-analytics-php](https://packagist.org/packages/particle-academy/google-analytics-php) | [fancy-google-analytics](https://pypi.org/project/fancy-google-analytics/) |
| [Google Docs](https://github.com/Fancy-Friends/google-docs) | productivity | [google-docs-ui](https://www.npmjs.com/package/@particle-academy/google-docs-ui) · [google-docs-js](https://www.npmjs.com/package/@particle-academy/google-docs-js) | [google-docs-php](https://packagist.org/packages/particle-academy/google-docs-php) | [fancy-google-docs](https://pypi.org/project/fancy-google-docs/) |
| [Google Drive](https://github.com/Fancy-Friends/google-drive) | productivity | [google-drive-ui](https://www.npmjs.com/package/@particle-academy/google-drive-ui) · [google-drive-js](https://www.npmjs.com/package/@particle-academy/google-drive-js) | [google-drive-php](https://packagist.org/packages/particle-academy/google-drive-php) | [fancy-google-drive](https://pypi.org/project/fancy-google-drive/) |
| [Google Sheets](https://github.com/Fancy-Friends/google-sheets) | productivity | [google-sheets-ui](https://www.npmjs.com/package/@particle-academy/google-sheets-ui) · [google-sheets-js](https://www.npmjs.com/package/@particle-academy/google-sheets-js) | [google-sheets-php](https://packagist.org/packages/particle-academy/google-sheets-php) | [fancy-google-sheets](https://pypi.org/project/fancy-google-sheets/) |
| [Google Slides](https://github.com/Fancy-Friends/google-slides) | productivity | [google-slides-ui](https://www.npmjs.com/package/@particle-academy/google-slides-ui) · [google-slides-js](https://www.npmjs.com/package/@particle-academy/google-slides-js) | [google-slides-php](https://packagist.org/packages/particle-academy/google-slides-php) | [fancy-google-slides](https://pypi.org/project/fancy-google-slides/) |
| [HubSpot](https://github.com/Fancy-Friends/hubspot) | crm | [hubspot-ui](https://www.npmjs.com/package/@particle-academy/hubspot-ui) · [hubspot-js](https://www.npmjs.com/package/@particle-academy/hubspot-js) | [hubspot-php](https://packagist.org/packages/particle-academy/hubspot-php) | [fancy-hubspot](https://pypi.org/project/fancy-hubspot/) |
| [Instagram for Business](https://github.com/Fancy-Friends/instagram-business) | marketing | [instagram-business-ui](https://www.npmjs.com/package/@particle-academy/instagram-business-ui) · [instagram-business-js](https://www.npmjs.com/package/@particle-academy/instagram-business-js) | [instagram-business-php](https://packagist.org/packages/particle-academy/instagram-business-php) | [fancy-instagram-business](https://pypi.org/project/fancy-instagram-business/) |
| [LinkedIn Ads](https://github.com/Fancy-Friends/linkedin-ads) | marketing | [linkedin-ads-ui](https://www.npmjs.com/package/@particle-academy/linkedin-ads-ui) · [linkedin-ads-js](https://www.npmjs.com/package/@particle-academy/linkedin-ads-js) | [linkedin-ads-php](https://packagist.org/packages/particle-academy/linkedin-ads-php) | [fancy-linkedin-ads](https://pypi.org/project/fancy-linkedin-ads/) |
| [monday.com](https://github.com/Fancy-Friends/monday) | productivity | [monday-ui](https://www.npmjs.com/package/@particle-academy/monday-ui) · [monday-js](https://www.npmjs.com/package/@particle-academy/monday-js) | [monday-php](https://packagist.org/packages/particle-academy/monday-php) | [fancy-monday](https://pypi.org/project/fancy-monday/) |
| [Notion](https://github.com/Fancy-Friends/notion) | productivity | [notion-ui](https://www.npmjs.com/package/@particle-academy/notion-ui) · [notion-js](https://www.npmjs.com/package/@particle-academy/notion-js) | [notion-php](https://packagist.org/packages/particle-academy/notion-php) | [fancy-notion](https://pypi.org/project/fancy-notion/) |
| [Resend](https://github.com/Fancy-Friends/resend) | email | [resend-ui](https://www.npmjs.com/package/@particle-academy/resend-ui) · [resend-js](https://www.npmjs.com/package/@particle-academy/resend-js) | [resend-php](https://packagist.org/packages/particle-academy/resend-php) | [fancy-resend](https://pypi.org/project/fancy-resend/) |
| [Slack](https://github.com/Fancy-Friends/slack) | messaging | [slack-ui](https://www.npmjs.com/package/@particle-academy/slack-ui) · [slack-js](https://www.npmjs.com/package/@particle-academy/slack-js) | [slack-php](https://packagist.org/packages/particle-academy/slack-php) | [fancy-slack](https://pypi.org/project/fancy-slack/) |
| [Square](https://github.com/Fancy-Friends/square) | payments | [square-ui](https://www.npmjs.com/package/@particle-academy/square-ui) · [square-js](https://www.npmjs.com/package/@particle-academy/square-js) | [square-php](https://packagist.org/packages/particle-academy/square-php) | [fancy-square](https://pypi.org/project/fancy-square/) |
| [Stripe](https://github.com/Fancy-Friends/stripe) | payments | [stripe-ui](https://www.npmjs.com/package/@particle-academy/stripe-ui) · [stripe-js](https://www.npmjs.com/package/@particle-academy/stripe-js) | [stripe-php](https://packagist.org/packages/particle-academy/stripe-php) | [fancy-stripe](https://pypi.org/project/fancy-stripe/) |
| [Telegram](https://github.com/Fancy-Friends/telegram) | messaging | [telegram-ui](https://www.npmjs.com/package/@particle-academy/telegram-ui) · [telegram-js](https://www.npmjs.com/package/@particle-academy/telegram-js) | [telegram-php](https://packagist.org/packages/particle-academy/telegram-php) | [fancy-telegram](https://pypi.org/project/fancy-telegram/) |
| [YouTube](https://github.com/Fancy-Friends/youtube) | marketing | [youtube-ui](https://www.npmjs.com/package/@particle-academy/youtube-ui) · [youtube-js](https://www.npmjs.com/package/@particle-academy/youtube-js) | [youtube-php](https://packagist.org/packages/particle-academy/youtube-php) | [fancy-youtube](https://pypi.org/project/fancy-youtube/) |

95 more are planned. A connector appears here once its repository and packages exist.

## Using one

```bash
npm install @particle-academy/stripe-ui      # the node kinds, for the editor
composer require particle-academy/stripe-php # run them on a PHP host
pip install fancy-stripe                     # or in Python
```

Each repository's README says how to set the connector up: the credentials it needs, where to get
them, whether the provider has a test estate, and every operation it can perform.

## Contributing

Every repository here is **generated** from a single provider definition, so a pull request that
edits `packages/` is overwritten by the next sync. Open an issue on the connector's repository
instead — a wrong field, a changed API, a missing operation — and it is fixed at the source for
all four packages at once.

<!-- Generated. Edits here are overwritten; open an issue instead. -->
