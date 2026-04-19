# David Stone

**Worked at @automattic on  @woocommerce . Now I revive the awesome open source project Ultimate Multisite.**

![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![CSS](https://img.shields.io/badge/-CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![CoffeeScript](https://img.shields.io/badge/-CoffeeScript-555555?style=flat-square)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 9.3h | 78.2h | 78.2h | ~4,022h* |
| User AI session hours | 5.3h | 22.7h | 22.7h | 22.7h |
| AI worker hours | 9.9h | 37.4h | 37.4h | 37.4h |
| AI concurrency hours | 24.3h | 91.9h | 91.9h | 91.9h |
| Interactive sessions | 45 | 107 | 107 | 107 |
| Worker sessions | 42 | 121 | 121 | 121 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 22,873 | 135.7M | 9.2M | 2,811.2M | $9,558.75 | $37,952.34 | $0.00 |
| claude-sonnet-4-6 | 101,331 | 5.2M | 32.8M | 8,528.6M | $3,906.66 | $23,027.40 | $12,266.21 |
| claude-opus-4-7 | 634 | 770 | 289K | 59.3M | $155.27 | $801.09 | $0.00 |
| hf:moonshotai/Kimi-K2.5 | 749 | 6.8M | 230K | 44.8M | $37.37 | $121.08 | $149.47 |
| claude-opus-4-5 | 161 | 176 | 26K | 10.5M | $23.88 | $141.78 | $0.00 |
| hf:zai-org/GLM-5.1 | 441 | 2.7M | 134K | 34.2M | $20.52 | $92.60 | $82.08 |
| claude-opus-4 | 114 | 105 | 35K | 7.7M | $17.96 | $104.54 | $0.00 |
| big-pickle | 224 | 2.2M | 55K | 12.8M | $13.69 | $0.00 | $57.42 |
| hf:zai-org/GLM-4.7-Flash | 383 | 692K | 51K | 24.3M | $10.15 | $65.63 | $40.59 |
| claude-sonnet-4-5 | 243 | 455 | 103K | 19.0M | $9.80 | $51.45 | $29.10 |
| deepseek-reasoner | 119 | 904K | 15K | 6.0M | $5.08 | $16.32 | $19.03 |
| claude-haiku-4-5 | 480 | 1K | 88K | 21.3M | $2.76 | $15.40 | $36.65 |
| mimo-v2-pro-free | 69 | 123K | 16K | 5.2M | $2.25 | $14.11 | $8.75 |
| gemma4:e4b | 9 | 206K | 3K | 0 | $0.67 | $0.00 | $2.69 |
| claude-haiku-4-5 | 13 | 45K | 4K | 324K | $0.23 | $0.23 | $1.44 |
| claude-sonnet-4 | 2 | 4 | 16 | 24K | $0.10 | $0.07 | $0.03 |
| **Total** | **127,845** | **154.7M** | **43.1M** | **11,585.9M** | **$13,765.14** | **$62,404.06** | **$12,693.44** |

_12,152.0M total tokens processed. 95.3% cache hit rate._

_$75,097.50 total saved ($62,404.06 caching + $12,693.44 model routing vs all-Opus)._

_Model savings are modest because ~95.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,612 | 4K | 1.4M | 463.5M | $801.88 | $6,258.06 | $0.00 |
| claude-sonnet-4-6 | 11,044 | 11K | 4.6M | 1,096.5M | $398.98 | $2,960.60 | $1,596.00 |
| claude-opus-4-7 | 630 | 770 | 289K | 59.3M | $110.70 | $801.09 | $0.00 |
| **Total** | **15,286** | **16K** | **6.3M** | **1,619.4M** | **$1,311.56** | **$10,019.76** | **$1,596.00** |

_1,678.1M total tokens processed. 97% cache hit rate._

_$11,615.75 total saved ($10,019.76 caching + $1,596.00 model routing vs all-Opus)._

_Model savings are modest because ~97% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[wp-update-server-plugin](https://github.com/superdav42/wp-update-server-plugin)** -- Enable automatic updates for WordPress plugins sold as Woocommerce downloadable products
- **[meeting-manager](https://github.com/superdav42/meeting-manager)** -- WordPress block for managing virtual meetings with Jitsi/JaaS integration, scheduling, and notifications
- **[glotpress-rest-api](https://github.com/superdav42/glotpress-rest-api)** -- Adds REST API endpoints for GlotPress project management
- **[magento-image-usage-calculator](https://github.com/superdav42/magento-image-usage-calculator)** -- Usage calculator to make it possible to purchase images or artwork at various resolutions.
- **[do-test](https://github.com/superdav42/do-test)** -- No description
- **[magento-image-products](https://github.com/superdav42/magento-image-products)** -- New product type for Magento 2 which makes it easy to sell images, photographs and artwork.
- **[magento-image-quality](https://github.com/superdav42/magento-image-quality)** -- Improve image quality of product images in Magento 2
- **[kalidokit-react](https://github.com/superdav42/kalidokit-react)** -- Kalidokit example using react and three js fiber
- **[gutenberg-standalone](https://github.com/superdav42/gutenberg-standalone)** -- Gutenberg without WordPress
- **[perf-html-editor](https://github.com/superdav42/perf-html-editor)** -- Created with CodeSandbox
- **[php-pm-wordpress](https://github.com/superdav42/php-pm-wordpress)** -- Experimental way to run WordPress with the PHP Process Manager
- **[psp](https://github.com/superdav42/psp)** -- Sample wordpress install with bedrock and moodle
- **[gp-reject-feedback](https://github.com/superdav42/gp-reject-feedback)** -- Plugin for GlotPress which allow reviewers to provide feedback for translators
- **[TwigOptimizations](https://github.com/superdav42/TwigOptimizations)** -- Twig extensions which enable some experimental optimizations on compiled code
- **[datauri-pages](https://github.com/superdav42/datauri-pages)** -- pages
## Contributions

- **[docket-cache](https://github.com/nawawi/docket-cache)** -- A persistent object cache stored as a plain PHP code, accelerates caching with OPcache backend.
- **[jetpack](https://github.com/Automattic/jetpack)** -- Security, performance, marketing, and design tools — Jetpack is made by WordPress experts to make WP sites safer and faster, and help you grow your traffic.
- **[GlotPress-WP](https://github.com/GlotPress/GlotPress)** -- :earth_africa: :earth_americas: :earth_asia: GlotPress, a WordPress Plugin
- **[datatable-translatable](https://github.com/unfoldingWord/datatable-translatable)** -- A Component Library for Translating DataTables using React and MaterialUI.
- **[wp-sqlite-db](https://github.com/aaemnnosttv/wp-sqlite-db)** -- A single file drop-in for using a SQLite database with WordPress. Based on the original SQLite Integration plugin.
- **[claude-max-api-proxy](https://github.com/atalovesyou/claude-max-api-proxy)** -- Use your Claude Max/Pro subscription with any OpenAI-compatible client. Saves $1000s compared to API keys.
- **[WPTranslationFiller](https://github.com/vibgyj/WPTranslationFiller)** -- No description
- **[wbwwb](https://github.com/ncase/wbwwb)** -- We Become What We Behold – a minigame about the news!
- **[action-scheduler](https://github.com/woocommerce/action-scheduler)** -- A scalable, traceable job queue for background processing large queues of tasks in WordPress. Specifically designed for distribution in WordPress plugins and themes - no server access required.
- **[potrans](https://github.com/OzzyCzech/potrans)** -- Command line tool for translate Gettext with Google Translator API or DeepL API
- **[multisite-ultimate-1](https://github.com/Ultimate-Multisite/ultimate-multisite)** -- Website as a service plugin for WordPress Multisite
- **[elasticsuite](https://github.com/Smile-SA/elasticsuite)** -- Smile ElasticSuite - Magento 2 merchandising and search engine built on ElasticSearch
- **[woocommerce](https://github.com/woocommerce/woocommerce)** -- A customizable, open-source ecommerce platform built on WordPress. Build any commerce solution you can imagine.
- **[magento2-sentry](https://github.com/justbetter/magento2-sentry)** -- Magento 2 module to log to Sentry
- **[module-address-autocomplete](https://github.com/shipperhq/module-address-autocomplete)** -- ShipperHQ Address Autocomplete for Magento 2
- **[magento2-matomo](https://github.com/fnogatz/magento2-matomo)** -- Matomo Analytics Module for Magento 2
- **[microsoft-translator](https://github.com/matthiasnoback/microsoft-translator)** -- PHP library for making calls to the Microsoft Translator V2 API
- **[magento2-deepl](https://github.com/aromicon/magento2-deepl)** -- Magento 2 Module for Automatic Translation with DeepL 
- **[module-notorama](https://github.com/robaimes/module-notorama)** -- Say no to Fotorama in Magento 2.3 with Notorama.
- **[magento2-replace-tools](https://github.com/yireo/magento2-replace-tools)** -- No description
- **[magento2-customer-password](https://github.com/kiwicommerce/magento2-customer-password)** -- Magento 2 - Customer Password by KiwiCommerce
- **[wp-webauthn](https://github.com/yrccondor/wp-webauthn)** -- 🔒 WP-WebAuthn allows you to safely login to your WordPress site without password.
- **[wordpress-core](https://github.com/johnpbloch/wordpress-core)** -- Fork to support running WordPress with Swoole
- **[binpackingjs](https://github.com/olragon/binpackingjs)** -- 2D, 3D, 4D Bin Packing JS Library
- **[multilingual-press](https://github.com/inpsyde/multilingual-press)** -- The multisite-based free open source plugin for your multilingual WordPress websites. Supports PHP8.1
- **[v-tooltip](https://github.com/Akryum/floating-vue)** -- Easy tooltips for Vue 2.x
- **[magento2-campaignmonitor](https://github.com/vincent2090311/magento2-campaignmonitor)** -- Campaign Monitor connector for the Magento 2.x
- **[proskomma-js](https://github.com/mvahowe/proskomma-js)** -- A JS Implementation of the Proskomma Scripture Processing Model
- **[xelah](https://github.com/xelahjs/xelah)** -- No description
- **[epitelete](https://github.com/Proskomma/epitelete)** -- PERF Middleware for Editors in the Proskomma Ecosystem
- **[Sign-Language-Recognition--MediaPipe-DTW](https://github.com/gabguerin/Sign-Language-Recognition--MediaPipe-DTW)** -- No description
- **[psalm-plugin-wordpress](https://github.com/psalm/psalm-plugin-wordpress)** -- WordPress stubs and plugin for Psalm
- **[wordpress](https://github.com/johnpbloch/wordpress)** -- A fork of WordPress with Composer support added. Branches, tags, and trunk synced from upstream every 15 minutes.
- **[Imagine](https://github.com/php-imagine/Imagine)** -- PHP 5.3 Object Oriented image manipulation library
- **[campaignmonitor-php](https://github.com/99designs/campaignmonitor-php)** -- Campaign Monitor PHP API wrapper
- **[hapi-i18n](https://github.com/funktionswerk/hapi-i18n)** -- Translation module for hapi based on mashpie's i18n module
- **[magento2-s3](https://github.com/brenofabio/magento2-s3)** -- Use Amazon S3 as the file storage solution for your Magento 2 application
- **[lx-utils](https://github.com/eyroot/lx-utils)** -- A collection of various PHP utils
- **[php-rrule](https://github.com/rlanvin/php-rrule)** -- Lightweight and fast recurring dates library for PHP RFC 5545
- **[wordpress-opcache](https://github.com/elcobvg/wordpress-opcache)** -- OPcache Object Cache plugin for WordPress. Faster than Redis, Memcache or APC.
- **[module-authorizenetcim](https://github.com/pmclain/module-authorizenetcim)** -- Magento 2 Authorize.net CIM
- **[magento2](https://github.com/magento/magento2)** -- All Submissions you make to Magento Inc. “Magento" through GitHub are subject to the following terms and conditions: 1 You grant Magento a perpetual, worldwide, non-exclusive, no charge, royalty free, irrevocable license under your applicable copyrights and patents to reproduce, prepare derivative works of, display, publically perform, sublicense and distribute any feedback, ideas, code, or other information “Submission" you submit through GitHub. 2 Your Submission is an original work of authorship and you are the owner or are legally entitled to grant the license stated above. 3 You agree to the Contributor License Agreement found here:  https://github.com/magento/magento2/blob/master/CONTRIBUTOR_LICENSE_AGREEMENT.html
- **[valet-linux](https://github.com/cpriego/valet-linux)** -- A fork of Laravel Valet to work in Linux.
- **[prototype](https://github.com/prototypejs/prototype)** -- Prototype JavaScript framework
- **[apple-news](https://github.com/alleyinteractive/apple-news)** -- No description
- **[quickbooks-php](https://github.com/consolibyte/quickbooks-php)** -- QuickBooks Integration for PHP
- **[prophecy](https://github.com/phpspec/prophecy)** -- Highly opinionated mocking framework for PHP 5.3+
- **[libvmod-headerproxy](https://github.com/SteveEasley/libvmod-headerproxy)** -- Varnish Header Proxy VMOD
- **[doctrine2](https://github.com/doctrine/orm)** -- Doctrine 2 Object Relational Mapper ORM
- **[Twig](https://github.com/twigphp/Twig)** -- Twig, the flexible, fast, and secure template language for PHP
- **[dokuwiki](https://github.com/dokuwiki/dokuwiki)** -- The DokuWiki Open Source Wiki Engine
- **[plugin-tag](https://github.com/dokufreaks/plugin-tag)** -- Fork to add option for seaching through multiple namespaces
- **[symfony](https://github.com/symfony/symfony)** -- The Symfony PHP framework
- **[Yaml](https://github.com/symfony/yaml)** -- READ-ONLY Subtree split of the Symfony YAML Component -- clone into Symfony/Component/ master at symfony/symfony
- **[dokuwiki-plugin-graphviz](https://github.com/ascendro/dokuwiki-plugin-graphviz)** -- Create Graphviz graphs from within DokuWiki
- **[Door43](https://github.com/unfoldingWord-dev/Door43)** -- Repo to hold issues related to Door43
- **[hubot](https://github.com/unfoldingWord-dev/hubot)** -- Bot for messaging
- **[dokuwiki-enhancedindexer](https://github.com/unfoldingWord-dev/dokuwiki-enhancedindexer)** -- Better, faster cli indexer for dokuwiki
- **[pagequery](https://github.com/MrBertie/pagequery)** -- An all-in-one, multi-column page listing plugin for Dokuwiki
- **[ckgedit](https://github.com/turnermm/ckgedit)** -- CKEditor integrated into fckgLite
- **[knp-components](https://github.com/KnpLabs/knp-components)** -- Various component pack, includes paginator
- **[server-configs-nginx](https://github.com/h5bp/server-configs-nginx)** -- Nginx HTTP server boilerplate configs
- **[LeezyPheanstalkBundle](https://github.com/armetiz/LeezyPheanstalkBundle)** -- Bundle for Pheanstalk - A PHP client for beanstalkd queue
- **[dbal](https://github.com/doctrine/dbal)** -- Doctrine Database Abstraction Layer
- **[MidgardAppServerBundle](https://github.com/bergie/MidgardAppServerBundle)** -- Run Symfony2 applications on the AppServer-in-PHP
- **[twentytwenty](https://github.com/zurb/twentytwenty)** -- jQuery Plugin to Compare Images
- **[raven-php](https://github.com/getsentry/sentry-php)** -- PHP client for sentry

## Connect

[![Website](https://img.shields.io/badge/-ultimatemultisite.com-FF5722?style=flat-square&logo=hugo&logoColor=white)](https://ultimatemultisite.com)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/superdav42)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-19 07:31 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
