ImageLookup
===========

## Goals ##

1. Serve as a subscription service for eCommerce and mobile shopping platforms to leverage across retail oriented verticals such as apparel and shoes. The idea is to pay for at least the cost of hosting and bandwidth to keep the service alive and thriving.
2. High quality images should be request-able in any dimension or format.
3. Lookups may be based on just one field like just a `UPC` or multiple criteria `upc AND sku AND description` etc.
4. The subscription should not be used to serve the end-users of an eCommerce or mobile platform! Instead it is meant for those platforms to fill in any gaps they have in their own databases/edge-caches from which they serve their respective users. For example, a retail store with 20,000 SKUs and only 500 or so images would subscribe to the service in order to fill in rest of the 19,500 gap.
5. Photographers should be able to upload product images and select a license that clearly indicates that they are OK with its distribution. They should also indicate that its their own work and does not belong to someone else.
6. Catalog owners should be able to bulk upload their data.
7. Crawlers or connectors should be added by the community over time to collect trending apparel images from services like Pinterest or FashionSnoops or MyFdb while respecting any copyright or infringement clauses that may be put forth by such entities.
