<div align="center">

<img src="./assets/zahls-logo.svg" alt="zahls.ch" width="220" />

**Swiss payments for the web — TWINT, cards & PostFinance.**

[Website](https://www.zahls.ch) · [Developer docs](https://www.zahls.ch/entwickler) · [API reference](https://www.zahls.ch/entwickler/api) · [Sign up](https://signup.zahls.ch)

<br />

[![Switzerland](https://img.shields.io/badge/Made%20in-Switzerland-FF0000?style=flat-square&logo=swiss&logoColor=white)](https://www.zahls.ch)
[![Website](https://img.shields.io/badge/www.zahls.ch-3f245c?style=flat-square)](https://www.zahls.ch)
[![Support](https://img.shields.io/badge/support@zahls.ch-575756?style=flat-square)](mailto:support@zahls.ch)

</div>

---

## What we build

zahls.ch is a Swiss payment platform for shops, websites, and apps. Accept **TWINT**, **credit & debit cards**, **PostFinance**, Apple Pay, Google Pay, and more — without setup fees.

| Product | What it does |
| --- | --- |
| **Payment Gateway** | Embed checkout in your shop or app via plugins or REST API |
| **Payment links** | Get paid with a single link — no website required |
| **Payment pages** | Mini shop / landing page to sell products, tickets, or services |
| **Invoices** | Digital invoices with PDF and payment status |
| **Donations** | Donation forms for clubs, foundations, and projects |

---

## Open source

We publish integrations and tools that help developers accept Swiss payments.

| Platform | Repository | Install |
| --- | --- | --- |
| **Medusa** | [zahls-plugin-medusa](https://github.com/zahls/zahls-plugin-medusa) | `npm install @zahls/medusa-plugin` |
| **Shopware 6** | [zahls-plugin-shopware6](https://github.com/zahls/zahls-plugin-shopware6) | [Latest release](https://github.com/zahls/zahls-plugin-shopware6/releases/latest) |
| **Magento 2** | [zahls-plugin-magento](https://github.com/zahls/zahls-plugin-magento) | [Latest release](https://github.com/zahls/zahls-plugin-magento/releases/latest) |
| **PrestaShop** | [zahls-plugin-prestashop](https://github.com/zahls/zahls-plugin-prestashop) | [Latest release](https://github.com/zahls/zahls-plugin-prestashop/releases/latest) |
| **PHP SDK** | [zahls-php](https://github.com/zahls/zahls-php) | Composer |

WooCommerce lives on WordPress.org: [zahls-ch-payment-gateway](https://de-ch.wordpress.org/plugins/zahls-ch-payment-gateway/).

More integrations on [zahls.ch → Integrations](https://www.zahls.ch/integrationen).

---

## For developers

```bash
# Create a gateway, get paid, get notified
curl -X POST "https://api.zahls.ch/v1.0/Gateway/" \
  -H "Authorization: YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"amount":1000,"currency":"CHF","successRedirectUrl":"https://example.com/ok"}'
```

- [REST API & OpenAPI](https://www.zahls.ch/entwickler/api)
- [Webhooks](https://www.zahls.ch/entwickler/webhook)
- [Embedding / modal checkout](https://www.zahls.ch/entwickler/embedding)
- [Help center](https://www.zahls.ch/hilfe)

Instance API keys live under **API & Integrations** in your [zahls.ch dashboard](https://login.zahls.ch).

---

## Quick links

| | |
| --- | --- |
| Product | [zahls.ch](https://www.zahls.ch) |
| Create account | [signup.zahls.ch](https://signup.zahls.ch) |
| Dashboard | [login.zahls.ch](https://login.zahls.ch) |
| Pricing | [zahls.ch/preise](https://www.zahls.ch/preise) |
| Contact | [zahls.ch/kontakt](https://www.zahls.ch/kontakt) · [support@zahls.ch](mailto:support@zahls.ch) |

---

<div align="center">

<sub>Built in Switzerland · <a href="https://www.zahls.ch">zahls.ch</a></sub>

</div>
