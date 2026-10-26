# Awesome Zid [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources, tools, libraries and learning material for building on [Zid](https://zid.sa/), the e-commerce platform for merchants in Saudi Arabia and the Gulf.

قائمة منتقاة من الموارد والأدوات والمكتبات والمحتوى التعليمي للتطوير على منصة زد.

Maintained by [Grovlix](https://grovlix.com), a Saudi company that builds apps and themes for Salla and Zid. This list is not affiliated with or endorsed by Zid. Zid's official GitHub organization is at [zidsa](https://github.com/zidsa).

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) first.

## Contents | المحتويات

- [Official Resources | الموارد الرسمية](#official-resources--الموارد-الرسمية)
- [SDKs & Libraries | المكتبات وأدوات التطوير](#sdks--libraries--المكتبات-وأدوات-التطوير)
- [Themes & Theme Development | القوالب وتطوير القوالب](#themes--theme-development--القوالب-وتطوير-القوالب)
- [CLI & Tooling | سطر الأوامر والأدوات](#cli--tooling--سطر-الأوامر-والأدوات)
- [Webhooks | الويب هوك](#webhooks--الويب-هوك)
- [Starter Templates & Example Apps | قوالب البداية والتطبيقات التجريبية](#starter-templates--example-apps--قوالب-البداية-والتطبيقات-التجريبية)
- [Payment & Shipping Integrations | تكامل الدفع والشحن](#payment--shipping-integrations--تكامل-الدفع-والشحن)
- [AI & Automation | الذكاء الاصطناعي والأتمتة](#ai--automation--الذكاء-الاصطناعي-والأتمتة)
- [Learning | التعلم](#learning--التعلم)
- [Community | المجتمع](#community--المجتمع)

## Official Resources | الموارد الرسمية

- [Authorization](https://docs.zid.sa/authorization) - Official guide to OAuth for Zid apps.
- [Rate Limiting](https://docs.zid.sa/rate-limiting-644369m0) - Official explanation of Zid API request limits.
- [Start Here](https://docs.zid.sa/start-here) - Official onboarding guide for new Zid partners building apps and themes.
- [Zid Developer Docs](https://docs.zid.sa/) - Official documentation for the Zid Merchant API, apps, themes and webhooks.
- [Zid on GitHub](https://github.com/zidsa) - Official GitHub organization with Vitrin tooling, themes, SDKs and samples.
- [Zid Partner Changelog](https://changelog.partner.zid.sa/) - Release notes for the partner platform and APIs.
- [Zid Partner Help Center](https://help-partner.zid.sa/en/) - Help articles for Zid partners.
- [Zid Partner Portal](https://partner.zid.sa/) - Portal for creating and publishing Zid apps and themes.
- [Zid Partners Developers Page](https://zid.sa/ar/partners/developers/) - Official entry point for developers and partners, with links to community channels.
- [Zid Status](https://status.zid.sa/) - Real-time and historical status of Zid services.

## SDKs & Libraries | المكتبات وأدوات التطوير

- [Embedded Apps](https://docs.zid.sa/embedded-apps-2168216m0) - Official guide to running an app inside the Zid merchant dashboard.
- [sdk-python](https://github.com/zidsa/sdk-python) - Official Python client for the Zid API, published on PyPI as zid-client.
- [Storefront Events](https://docs.zid.sa/storefront-events-649611m0) - Official reference for events emitted by Zid storefronts.
- [ZATCA](https://github.com/zidsa/zatca) - PHP package published by Zid for ZATCA e-invoicing integration, described as unofficial.
- [Zid MUI](https://github.com/zidsa/zidmui) - Official React component library for building UIs consistent with Zid products.
- [Zid SDKs](https://docs.zid.sa/zid-sdks-2008123m0) - Official overview of available and planned Zid SDKs.

## Themes & Theme Development | القوالب وتطوير القوالب

- [growth-theme](https://github.com/zidsa/growth-theme) - Zid's default Vitrin theme built with Jinja2, Tailwind CSS and Vite.
- [Jinja Basics](https://docs.zid.sa/jinja-basics-1379353m0) - Official introduction to Jinja templating for Vitrin themes.
- [Legacy Theme Migration](https://docs.zid.sa/legacy-theme-migration-4638089f0) - Official guide to moving legacy themes to Vitrin.
- [Theme Development](https://docs.zid.sa/theme-development) - Official getting-started guide for Zid theme development.
- [Twig to Jinja](https://docs.zid.sa/twig-to-jinja-1379319m0) - Official mapping from legacy Twig syntax to Vitrin Jinja.
- [Vitrin Changelog](https://docs.zid.sa/vitrin-changelog-1769483m0) - Release notes for the Vitrin theme platform.
- [Vitrin Jinja Extensions](https://docs.zid.sa/vitrins-jinja-extensions-1379354m0) - Official reference for Jinja filters, tags and globals added by Vitrin.

## CLI & Tooling | سطر الأوامر والأدوات

- [Arabic SEO Toolkit](https://github.com/Grovlix/arabic-seo-toolkit) - Arabic-first SEO audit web app and CLI for Salla and Zid merchants, maintained by Grovlix.
- [Vitrin CLI](https://github.com/zidsa/vitrin-cli) - Official command line tool and terminal UI for creating, previewing and deploying Vitrin themes.
- [Vitrin CLI Commands](https://docs.zid.sa/cli-commands-1390556m0) - Official command reference for the Vitrin CLI.
- [Zid Bridge Tool](https://docs.zid.sa/zid-bridge) - Official hosted tool that completes the Zid OAuth flow to get test tokens, not for public apps.

## Webhooks | الويب هوك

- [Webhook Health Tracking](https://docs.zid.sa/webhook-health-tracking-2197281m0) - Official guide to monitoring webhook delivery health.
- [Webhook Reference (Salla & Zid)](https://github.com/Grovlix/salla-webhook-reference) - Bilingual (English and Arabic) reference for Salla and Zid webhook events, maintained by Grovlix (work in progress).
- [Zid Webhooks](https://docs.zid.sa/webhooks) - Official overview of webhook events and subscriptions.

## Starter Templates & Example Apps | قوالب البداية والتطبيقات التجريبية

- [demo-app-python](https://github.com/zidsa/demo-app-python) - Official minimal FastAPI app that uses the Zid Python SDK.
- [express-sample-app](https://github.com/zidsa/express-sample-app) - Official Express.js sample covering Zid OAuth and API calls.
- [laravel-sample-app](https://github.com/zidsa/laravel-sample-app) - Official Laravel sample covering Zid OAuth and API calls.

## Payment & Shipping Integrations | تكامل الدفع والشحن

- [Embedded Payment](https://docs.zid.sa/embedded-payment-1030692m0) - Official guide to integrating payment methods with Zid checkout.
- [Plans and Billing](https://docs.zid.sa/plans-and-billing) - Official guide to pricing plans, usage-based billing and subscription events for apps.
- [Shipping API](https://docs.zid.sa/shipping-1810986f0) - Official reference for Zid shipping endpoints.

## AI & Automation | الذكاء الاصطناعي والأتمتة

- [Zid AI Agent Skill](https://github.com/zidsa/zid-agent-skill) - Official skill that grounds coding agents in Zid OAuth and Merchant API patterns.
- [Zid MCP Server](https://docs.zid.sa/our-custom-mcp-server-1363315m0) - Official MCP server for querying the Zid API documentation from AI-powered IDEs.

## Learning | التعلم

- [Create Your First App](https://docs.zid.sa/create-first-app) - Official step-by-step tutorial for your first Zid app.
- [Test Your App](https://docs.zid.sa/test-your-app) - Official checklist for testing an app before submission.
- [Zid Academy](https://academy.zid.sa/ar) - Official Arabic learning platform for Zid merchants.
- [Zid on YouTube](https://www.youtube.com/channel/UCcPU3vP1sTR4f1zupXGYa8Q) - Official Arabic channel with practical videos for running a Zid store.

## Community | المجتمع

- [Zid Community](https://community.zid.sa/) - Arabic community forum for Zid merchants.
- [Zid Developers Community on Telegram](https://t.me/zidpartnersthemes) - Official Telegram community for Zid developers, linked from the Zid partners page.

## License | الرخصة

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
