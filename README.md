# Mercadolibre Scraper — examples

Runnable examples for the **[MercadoLibre Scraper - Products, Prices & Sellers | $3/1K](https://apify.com/bovi/mercadolibre-scraper)** on Apify.

Scrape MercadoLibre product listings across all Latin-American sites (MLA Argentina, MLB Brazil, MLM Mexico, MLC Chile, MCO Colombia & more). Returns title, price, original price, currency, condition, seller, free shipping, category, attributes, location, permalink & images per item. No API key.

## What you get per record
`attributes` · `available_quantity` · `category_id` · `condition` · `country` · `currency_id` · `discount_pct` · `free_shipping` · `installments` · `item_id` · `listing_type` · `location_city` · `location_state` · `original_price` · `parse_confidence` · `permalink` · `pictures` · `price` · `rating` · `reviews_count` · `scraped_at` · `seller_id` · `seller_nickname` · `seller_reputation` · `site` · `sold_quantity` · `thumbnail` · `title` · `warnings`

## Who uses this
- **Price intelligence** — track competitor pricing across Argentina/Mexico/Brazil marketplaces.
- **Arbitrage / reselling** — surface underpriced listings and demand by category.
- **Market research** — assortment, seller concentration and price bands per category.

## Quickstart
1. Get your Apify token: <https://console.apify.com/account/integrations>
2. Run a language example below. Both call the actor and print the results.

| Example | File |
|---|---|
| Python (`apify-client`) | [`examples/python/run.py`](examples/python/run.py) |
| JavaScript (`apify-client`) | [`examples/javascript/run.js`](examples/javascript/run.js) |
| Sample output (real records) | [`examples/sample_output.json`](examples/sample_output.json) |

## Example input
```json
{
  "site": "MLM",
  "query": "iphone",
  "maxResults": 50,
  "proxyConfiguration": {
    "useApifyProxy": true,
    "apifyProxyGroups": [
      "RESIDENTIAL"
    ]
  }
}
```

## Links
- **Actor on Apify Store:** <https://apify.com/bovi/mercadolibre-scraper>
- **Apify client docs:** [Python](https://docs.apify.com/api/client/python/) · [JavaScript](https://docs.apify.com/api/client/js/)

---
_MIT-licensed examples. The actor runs on the caller's Apify account (you pay platform compute + per-result)._
