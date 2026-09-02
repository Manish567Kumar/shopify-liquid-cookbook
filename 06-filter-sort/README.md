# 06 - Filter & Sort Sidebar

Sidebar UI to expose `collection.filters` and `collection.sort_options` to customers. The snippet progressively enhances a basic HTML form and preserves selections in the URL.

Usage
- Copy `snippet.liquid` where your sidebar would render on collection pages and include `styles.css`.

Customization
- Filter param encoding used by this snippet: `filter_{name}=value1,value2` — set `FILTER_PARAM_FORMAT` in the top comment if your theme expects a different format.

Notes / Assumptions
- Shopify themes and Storefront filtering variations differ. This snippet serializes repeated checkbox selections into comma-separated lists; you may need to adapt the query param format to your theme's filter handler.

Demo
- demo.gif placeholder pending — please record and add `demo.gif` in this folder.
