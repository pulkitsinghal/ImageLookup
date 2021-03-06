ImageLookup
===========

## Goals ##

1. Serve as a subscription service for eCommerce and mobile shopping platforms to leverage across retail oriented verticals such as apparel and shoes. The idea is to pay for at least the cost of hosting and bandwidth to keep the service alive and thriving.
2. High quality images should be request-able in any dimension or format.
3. Lookups may be based on just one field like just a `UPC` or multiple criteria `upc AND sku AND description` etc.
4. The subscription should not be used to serve the end-users of an eCommerce or mobile platform! Instead it is meant for those platforms to fill in any gaps they have in their own databases/edge-caches from which they serve their respective users. For example, a retail store with 20,000 SKUs and only 500 or so images would subscribe to the service in order to fill in rest of the 19,500 gap.
5. Photographers should be able to upload product images and select a license that clearly indicates that they are OK with its distribution. They should also indicate that its their own work and does not belong to someone else.
6. Catalog owners should be able to bulk upload their data.
7. Crawlers or connectors should be added by the community over time to collect trending apparel images from services like [Pinterest](http://pinterest.com) or [FashionSnoops](http://www.fashionsnoops.com/) or [MyFdb](https://www.myfdb.com/) while respecting any copyright or infringement clauses that may be put forth by such entities.
8. Leverage machine learning for picking pitures and matching codes out of PDF catalogs when they aren't arranged one image at a time. For example: http://www.image-apparel-solutions.com/assets/1/Page/2012%20Image%20Apparel%20Solutions%20Catalog%20Final%20LR.pdf
9. If end-users of an eCommerce or mobile platform want to contribute with the amatuer pitures they might take from their cameras then in addition to an API for that, there should also be some sort of vote up/down community curation system.
