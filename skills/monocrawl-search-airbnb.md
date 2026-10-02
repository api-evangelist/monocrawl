---
name: search-airbnb
description: Search Airbnb listings via Monocrawl API
api: https://www.monocrawl.com/openapi.json
operations:
  - airbnb_search_stays
---

## Steps
1. Call the `airbnb_search_stays` operation with required query parameters.
2. Handle pagination using the `cursor` parameter as documented.
