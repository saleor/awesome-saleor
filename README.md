# Awesome Saleor [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An opinionated list of awesome tools, libraries, and resources for Saleor. Inspired by the [awesome-python](https://github.com/vinta/awesome-python) repository.

---

## Table of Contents

- [Awesome Saleor](#awesome-saleor-)
  - [Table of Contents](#table-of-contents)
  - [Apps](#apps)
  - [Tooling](#tooling)
    - [JavaScript](#javascript)
    - [Rust](#rust)
    - [Python](#python)
    - [Miscellaneous](#miscellaneous)
  - [Resources](#resources)
  - [Contributing](#contributing)

---

## Apps

> [!NOTE]  
> Saleor hosts some apps through the [Saleor App Store](https://docs.saleor.io/developer/app-store/overview#saleor-app-store) on [Saleor Cloud](https://cloud.saleor.io/).

Here is the list of both official and community-built Saleor apps:

- **[AvaTax](https://github.com/saleor/apps/tree/main/apps/avatax)**  
  Integrates with the AvaTax API to calculate dynamic taxes.
  
- **[CMS](https://github.com/saleor/apps/tree/main/apps/cms)**  
  Enables one-way synchronization of Saleor products into supported CMS platforms such as Contentful, Strapi, DatoCMS, Builder.io, and Payload.
  
- **[Klaviyo](https://github.com/saleor/apps/tree/main/apps/klaviyo)**  
  Sends Saleor events to Klaviyo for customer notifications.
  
- **[Product Feed](https://github.com/saleor/apps/tree/main/apps/products-feed)**  
  Generates an XML feed of products and their details, compatible with Google Merchant Center.
  
- **[Search](https://github.com/saleor/apps/tree/main/apps/search)**  
  Integrates Saleor with Algolia search for indexing and searching products.
  
- **[SMTP](https://github.com/saleor/apps/tree/main/apps/smtp)**  
  Provides email communication with customers using Handlebars templating.
  
- **[Stripe](https://github.com/saleor/saleor-app-payment-stripe)**  
  Integrates Stripe payment gateway with Saleor.
  
- **[SendGrid](https://github.com/saleor/example-app-sendgrid)**  
  Email marketing integration with SendGrid.
  
- **[TaxJar](https://github.com/saleor/example-app-taxjar)**  
  Sales tax compliance service for modern commerce.
  
- **[Invoices](https://github.com/saleor/example-app-invoices)**  
  Generates simple PDF invoices.
  
- **[CRM](https://github.com/saleor/example-app-crm)**  
  Syncs customers from Saleor to Mailchimp.
  
- **[Segment](https://github.com/saleor/example-app-segment)**  
  Provides real-time customer insights using Twilio Segment.
  
- **[Slack](https://github.com/saleor/example-slack-app)**  
  Connects Saleor with Slack, triggering bot messages (e.g., `order_created` webhook).
  
- **[Abandoned Checkouts](https://github.com/saleor/saleor-app-abandoned-checkouts)**  
  Adds a dashboard menu to display abandoned checkout IDs.
  
- **[Klarna](https://github.com/saleor/saleor-app-payment-klarna)**  
  Integrates Saleor with Klarna payment gateway.
  
- **[Authorize.net](https://github.com/saleor/saleor-app-payment-authorize.net)**  
  Connects Saleor with the Authorize.net payment gateway.
  
- **[Hyperswitch](https://github.com/juspay/hyperswitch-saleor-payment-app)**  
  A payment switch providing access to Stripe, PayPal, Worldpay, and Braintree in one platform.
  
- **[Dummy Payment App](https://github.com/saleor/dummy-payment-app)**  
  Generates payments without integrating with a payment provider.
  
- **[Sitemap Generator](https://github.com/djkato/saleor-apps-rs)**  
  Creates a `sitemap.txt` file using simple templating.
  
- **[Simple Payment Gateway](https://github.com/djkato/saleor-apps-rs/tree/master/simple-payment-gateway)**  
  A payment gateway for methods that don't require validation (e.g., cash, COD, bank transfer).

## Tooling

The following tools can help you work with Saleor more effectively:

### JavaScript

- **[Saleor App Template](https://github.com/saleor/saleor-app-template)**  
  A Next.js-based template using the Saleor App SDK.
  
- **[Saleor App SDK](https://github.com/saleor/app-sdk)**  
  Official SDK for building apps with Next.js and TypeScript.
  
- **[Saleor Storefront](https://github.com/saleor/storefront)**  
  A sample storefront built with Next.js and Tailwind CSS.

- **[Hono + Cloudflare Pages App template](https://github.com/witoszekdev/saleor-app-hono-cf-pages-template)**
  Bolierplate for Saleor apps deployed for Cloudflare Pages using Hono app framework.

- **[Hono + Deno App template](https://github.com/witoszekdev/saleor-app-hono-deno-template)**
  Boilerplate for building Saleor apps in Deno runtime using Hono app framework.

- **[AWS Lambda App Template](https://github.com/mirumee/serverless-saleor-app-example)**
  Example implementation of Saleor app using AWS Lambda

### Rust

- **[Rust SDK](https://github.com/djkato/saleor-apps-rs)**  
  A community SDK for building Saleor apps with Rust.
  
- **[Rust App Template](https://github.com/djkato/saleor-apps-rs)**  
  A Rust-based app template using Axum and the Rust SDK, ideal for apps that don't require dashboard integration.

- **[Rust App Template with HTMX](https://github.com/cozyGalvinism/saleor-app-rust-axum)**
  A Rust-based app template using Axum and HTMX, includes dashboard integration.

- **[Rust App Template UI](https://github.com/djkato/saleor-apps-rs)**  
  Uses Axum, Leptos, and the Rust SDK, enabling dashboard integration via WASM.

### Python

- **[Python App Template](https://github.com/mirumee/saleor-app-framework-python)**
  Boilterplate for building Saleor apps in Python.

### Miscellaneous

- **[Theseus](https://github.com/p-febis/theseus)**  
  An importer written specifically for Saleor.
  
- **[Unofficial Docker Builds of Saleor Apps](https://github.com/djkato/saleor-dockerize-all-apps)**  
  Provides Docker images for Saleor apps.

- **[Example migration from SQL DB to Saleor with Rust](https://github.com/djkato/old-sql-shop-to-saleor-migration)**
  A collection of Rust and Typescript based tools used to migrate an Elias based e-commerce to Saleor.
  Includes:
    - example tool for sql category tree generator, help making product type to category relations used during product upload (for stores comming from backends with no concept of product types)
    - example tool for wiping all products, categories and product types
    - example tool for querying MariaDB for products, categories, media, prices etc., then transforming them for and uploading to Saleor

---

## Resources

Discover more about Saleor and access additional learning materials:

- **[Saleor Discord](https://discord.gg/H52JTZAtSH)**  
  Join the Saleor community on Discord.
  
- **[Saleor Docs](https://docs.saleor.io/)**  
  Official Saleor documentation.
  
- **[Saleor YouTube Channel](https://www.youtube.com/@saleor)**  
  Tutorials, demos, and community events on YouTube.

---

## Contributing

We welcome your contributions! Please refer to our [contribution guidelines](https://github.com/saleor/awesome-saleor/blob/master/CONTRIBUTING.md) before submitting.

---

If you have any questions or suggestions regarding this list, feel free to reach out to us on [Discord](https://discord.gg/H52JTZAtSH) or open an issue on GitHub.
