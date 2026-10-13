# EMPIREX Tech

**SC EMPIRE GLOBAL SOLUTIONS SRL** · Bucharest  
Software architecture for commerce, invoicing, and catalog systems.

[empirex.tech](https://empirex.tech) · [engineering](https://empirex.tech/engineering) · PHP · Laravel · WooCommerce · OpenCart · PrestaShop · Cloud · AI

Fourteen years of shipped PHP: checkout and shipping engines, merchant feeds, marketplace connectors, invoicing, and the queues that keep those systems honest.

The repositories below are original EMPIREX engineering. They are not client stores and they do not contain credentials or customer data. Practice page: [empirex.tech/engineering](https://empirex.tech/engineering).

## Practice

| Domain | Work |
| --- | --- |
| Commerce platforms | WooCommerce, OpenCart, PrestaShop, Shopify, WordPress |
| Application backends | Laravel, Symfony, Node.js, REST APIs |
| Money & documents | Integer ledgers, VAT, e-invoice adapters, plan limits |
| Catalog | Feed ingest, GTIN identity, incremental merchant push |
| Checkout | City/postcode rules, delivery windows, payment hooks |
| Operations | Locks, batch budgets, circuit breakers, signed webhooks |

## Engineering

**[php-commerce-engine](https://github.com/empirextech/php-commerce-engine)**  
Typed money, shipping qualification, catalog mapping, batch sync, circuit breaker.

**[woocommerce-checkout-architect](https://github.com/empirextech/woocommerce-checkout-architect)**  
WooCommerce shipping method from JSON rules, checkout fields, invoice gateway, HPOS.

**[woocommerce-merchant-sync](https://github.com/empirextech/woocommerce-merchant-sync)**  
Incremental Merchant Center-style push: watermark, exclusive lock, product mapper.

**[opencart-prestashop-extensions](https://github.com/empirextech/opencart-prestashop-extensions)**  
OpenCart city shipping and phone identity. PrestaShop combination feed.

**[php-feed-pipeline](https://github.com/empirextech/php-feed-pipeline)**  
Advertiser feed ingest: normalize, GTIN/brand/title identity, taxonomy.

**[php-invoice-ledger](https://github.com/empirextech/php-invoice-ledger)**  
VAT invoice arithmetic, series numbering, SaaS limits, e-invoice XML port.

**[php-posting-kernel](https://github.com/empirextech/php-posting-kernel)**  
Transactional posting: unique series, Idempotency-Key, mixed VAT, storno, outbox.

**[laravel-catalog-gateway](https://github.com/empirextech/laravel-catalog-gateway)**  
Sanctum API, unique sync jobs, HMAC webhooks, schema-checked AI enrichment.

## Method

Domain first. Platform adapters second. Money never as float. Remote APIs behind locks and breakers. Secrets in the environment.

## Contact

[empirex.tech](https://empirex.tech) · [github.com/empirextech](https://github.com/empirextech)
