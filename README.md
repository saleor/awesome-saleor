# Awesome Saleor [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An opinionated list of awesome Saleor tools, libraries, and resources. Inspired by awesome-python.

Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome Saleor](#awesome-saleor)
  - [Apps](#apps)
    - [Free](#free)
    - [Non-free](#non-free)
    - [Templates](#templates)
    - [SDKs](#sdks)
  - [Migration tools](#migration-tools)
- [Resources](#resources)
- [Contributing](#contributing)

---

Legend:

- ᴺ - **N**ot feature complete
- ᴸ - **L**egacy - deprecated / archived / No longer maintained
- ˢ - developed by **S**aleor

## Apps

Current list of apps maintained by Saleor can be found at the [App Store](https://apps.saleor.io/).

### Free

- [Avataxˢ](https://github.com/saleor/apps/tree/canary/apps/avatax) - Calculates dynamic taxes via AvaTax API
- [CMSˢ](https://github.com/saleor/apps/tree/canary/apps/cms-v2) - Allows one-direction synchronization of Saleor products into supported CMS platforms (Contentful, Strapi, DatoCMS, Builder.io, Payload)
- [Klaviyoˢ](https://github.com/saleor/apps/tree/canary/apps/klaviyo) - Send Saleor events to Klaviyo, where you can notify the customers
- [Products-feedˢ](https://github.com/saleor/apps/tree/canary/apps/products-feed) - Allows generating an XML file with products and their details. The file can be used as a feed source for Google Merchant Center.
- [Searchˢ](https://github.com/saleor/apps/tree/canary/apps/search) - Provides integration with the Algolia search engine. It allows you to index your products and search them using Algolia's API.
- [SMTPˢ](https://github.com/saleor/apps/tree/canary/apps/smtp) - Email communication with customers using Handlebars templating
- [Stripeᴸᴺˢ](https://github.com/saleor/saleor-app-payment-stripe) - Payment app for Stripe integration
- [SendGridᴸᴺˢ](https://github.com/saleor/example-app-sendgrid) - SendGrid email marketing integration
- [TaxJarᴸᴺˢ](https://github.com/saleor/example-app-taxjar) - TaxJar: "Sales Tax Compliance for Modern Commerce"
- [Invoicesᴸˢ](https://github.com/saleor/example-app-invoices) - Creates simple PDF invoices
- [CRMᴸˢ](https://github.com/saleor/example-app-crm) - **C**ustomer **R**elations **M**anagement with Mailchimp
- [Segmentᴸᴺˢ](https://github.com/saleor/example-app-segment) - Customer data for real-time insights using Twillio Segment
- [Emails and Messagesᴸˢ](https://github.com/saleor/apps/tree/saleor-app-emails-and-messages%401.10.4/apps/emails-and-messages) - Predecessor of SMTP, uses Handlebars templating, is missing `handlebars-helpers`
- [Data Importerᴸᴺˢ](https://github.com/saleor/apps/tree/data-importer%401.12.9/apps/data-importer) - Data Importer uses [Nuvo](https://www.getnuvo.com/) to batch import customers data to Saleor from sources like CSV or Excel
- [Slackᴸˢ](https://github.com/saleor/apps/tree/slack%401.12.4/apps/slack) - Connection between Saleor and Slack. For example `order_created` webhook triggers Slack bot to send message
- [Abandoned Checkoutsᴸᴺˢ](https://github.com/saleor/saleor-app-abandoned-checkouts) - Adds a menu in the Dashboard that shows IDs of Abandoned checkouts
- [Klarnaᴸᴺˢ](https://github.com/saleor/saleor-app-payment-klarna) - This app integrates Saleor with Klarna payment gateway
- [Authorize.netᴸᴺˢ](https://github.com/saleor/saleor-app-payment-authorize.net) - This app integrates Saleor with the Authorize.net payment gateway
- [Hyperswitch](https://github.com/juspay/hyperswitch-saleor-payment-app) - Payments switch that provides access to Stripe, Paypal, Worldpay and Braintree all in one stop
- [Dummy Payment Serverᴸᴺ](https://github.com/witoszekdev/dummy-payment-server) - Simple payment app created with deno

### Non-free

- [Sitemap Generator](https://github.com/djkato/saleor-apps-rs) - `sitemap.txt` generator with simple templating
- [Simple Payment Gateway](https://github.com/djkato/saleor-apps-rs) - Payment gateway for methods that don't require validation (Cash, COD, bank transfer...)

### Templates

- [Saleor App Templateˢ](https://github.com/saleor/saleor-app-template) - Uses NextJS, and Saleors Typescript SDK
- [App Payment Templateˢᴸ](https://github.com/saleor/saleor-app-payment-template) - Template Saleor payments apps were built from
- [Rust App Template](https://github.com/djkato/saleor-apps-rs) - Uses Axum and the Rust SDK, meant for apps that don't need dashboard integration
- [Rust App Template UIᴺ](https://github.com/djkato/saleor-apps-rs) - Uses Axum, Leptos and the Rust SDK, allows Dashboard integration thanks to WASM

### SDKs

- [Typescript / NextJS SDK (Official)](https://github.com/saleor/app-sdk)
- [Rust SDK](https://github.com/djkato/saleor-apps-rs)

## Migration tools

Tools helpful when you are migrating data to a Saleor instance.

- [theseus](https://github.com/p-febis/theseus) - The admin panel your servers deserve.

# Resources

Where to discover learning resources or additional details.

- [Saleor Discord](https://discord.gg/H52JTZAtSH)
- [Saleor Docs](https://docs.saleor.io/)

# Miscellaneous

Links to useful stuff that's hard to categorize, like app builds, .

- [Unofficial Docker builds of apps developed by Saleor](https://github.com/djkato/saleor-dockerize-all-apps)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/saleor/awesome-saleor/blob/master/CONTRIBUTING.md) first.

---

If you have any question about this opinionated list, do not hesitate to contact us on our [Discord](https://discord.gg/H52JTZAtSH) or open an issue on GitHub.
