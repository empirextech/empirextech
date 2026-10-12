# EMPIREX Tech

**Software Architect & Senior Full-Stack Developer**  
PHP · AI · Cloud

Fourteen years of professional work on PHP commerce systems: custom modules, checkout and shipping engines, catalog synchronization, API platforms, and the operational layer that keeps those systems running.

The public repositories below are original demonstration implementations. They reconstruct engineering patterns from production work without publishing client stores, credentials, or proprietary code.

## Focus

| Area | What I actually build |
| --- | --- |
| eCommerce platforms | WooCommerce, OpenCart, PrestaShop, Shopify, WordPress |
| Application backends | Laravel, Symfony, Node.js APIs |
| Catalog & channels | Merchant feeds, marketplace sync, incremental push, circuit breakers |
| Checkout | City/postcode shipping rules, delivery windows, payment gateway hooks |
| Operations | Queue jobs, locks, logging, server-side hardening |
| AI | Structured providers, schema validation, no unconstrained prompt-to-page |

PHP, MySQL, JavaScript, React, Vue.js, WooCommerce, OpenCart, PrestaShop, Shopify, REST integrations.

## Repositories

**[php-commerce-engine](https://github.com/empirextech/php-commerce-engine)**  
PHP 8.3 library for typed money, shipping qualification, catalog mapping, batch sync, and circuit breaking. The domain layer the platform modules sit on.

**[woocommerce-checkout-architect](https://github.com/empirextech/woocommerce-checkout-architect)**  
WooCommerce shipping method driven by JSON rules, checkout fields (delivery window, access number), and a correctly implemented invoice gateway. HPOS compatible.

**[opencart-prestashop-extensions](https://github.com/empirextech/opencart-prestashop-extensions)**  
OpenCart 3 city/postcode shipping plus phone-or-email identity, and a PrestaShop 8 incremental combination feed. Shared core covered by PHPUnit.

**[laravel-catalog-gateway](https://github.com/empirextech/laravel-catalog-gateway)**  
Laravel 11 API: Sanctum, product upserts, unique sync jobs, HMAC webhooks, and schema-checked AI enrichment.

## How I work

Architecture first, then the platform adapter. Rules and money live in testable PHP. WordPress, OpenCart, and PrestaShop remain integration shells. Remote APIs are bounded with locks, batches, and circuit breakers. Secrets stay in the environment.

## Contact

GitHub: [empirextech](https://github.com/empirextech)
