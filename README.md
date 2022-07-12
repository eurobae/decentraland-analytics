# Decentraland Analytics

## Decentraland
Decentraland is a virtual reality (VR) platform powered by the Ethereum blockchain. Within the platform, users can create, experience, and monetize their content and applications. Specificially, the finite, traversable, 3D virtual space is called LAND, a non-fungible digital asset maintained in an Ethereum smart contract. The 16m x 16m smallest unit of LAND is named a _parcel_, identified by cartesian coordinates (x,y). At the time of writing, LAND consists of 92,598 different parcels. On each parcel, users can build a _scene_ by using design tools like the [Builder](https://builder.decentraland.org/) or the Decentaland SDK, offering parcel-specific virtual experience to other users. Users can also create an _Estate_ by grouping two or more directly adjacent parcels to manage larger holdings or build larger scenes. Conversely, users can dissolve an Estate into separate parcles as well.

It is possible to trade both parcles and Estates on the [official marketplace](https://market.decentraland.org/) using MANA or on third-party NFT marketplaces like OpenSea using ETH, USDC, DAI, or other cryptocurrencies.

Below is a list of main characteristics distinguishing each LAND parcel:
- Distance to District
- Distance to Plaza
- Distance to Road
- Neighborhood
- ...

[Here](https://docs.decentraland.org/decentraland/introduction/) is the official documentation of Decentraland.
[Here](https://nonfungible.com/blog/discovery-of-decentraland?utm_campaign=Weekly%20Newsletter&utm_medium=email&_hsmi=200553779&_hsenc=p2ANqtz-9qmLYq4OxVvb74c0vTQKXxIjKNx6QmgrTu_jEWgcpxIeCXBQG6twHvi2Wpc_xMnX6zVpHL9ORDqQ8u_FPl_OrF6pTq-g&utm_content=200553779&utm_source=hs_email) is a good summary of the history and evolution of Decentraland by NonFungible.com (2021).


## Timeline
- 2017-Aug-18: ICO
- 2017-Dec-15 - 2018-Jan-??: [First public LAND auction](https://medium.com/decentraland/the-terraform-event-is-around-the-corner-bdda6a2d4367)
- 2018-Mar-??: Decentraland Marketplace launch
- 2018-Dec-10 - 2018-Dec-23: [Second public LAND auction](https://decentraland.org/blog/announcements/the-decentraland-land-auction-has-started/)
- 2020-Feb-20: [Decentraland public launch](https://decentraland.org/blog/announcements/decentraland-announces-publich-launch/)


## 
| Location | Size | Start | End | Organization | Link |
| -- | -- | -- | -- | -- | -- |
| (-138,-116) | 1 | 2021-03-12 | 2021-03-13 | Domino's Pizza | https://events.decentraland.org/event/?id=9ad1f34a-4565-498d-bac5-835e9c6b6047 |
| (52-56,82-85) | 20 | 2021-06-04 | | Sotheby's | https://decentraland.org/blog/announcements/sotheby-s-opens-a-virtual-gallery-in-decentraland/ |
| (100-107,76-82)<br />except (100,76),(105,82),(107,76),(107,80-82)| 50 | 2022-01-06 | | Samsung 837X | https://news.samsung.com/us/samsung-837x-metaverse-customization-youmake-create-world-you-want/ |
| (18-19,142-143) | 4 | 2022-01-07 | | Prager Metis | https://pragermetis.com/news/prager-metis-opens-first-ever-cpa-firm-metaverse/ |
| (94,23) | 1 | 2022-02-15 | | J.P.Morgan | https://www.jpmorgan.com/content/dam/jpm/treasury-services/documents/opportunities-in-the-metaverse.pdf |
| (51-55,74-77) | 20 | 2022-02-23 | | VICE Media Group | https://dappradar.com/blog/vice-media-group-unveils-hq-in-decentraland |


## Retrieving LAND Transactions from OpenSea
[OpenSea API](https://docs.opensea.io/reference/api-overview) is used to retrieve all the historical events (e.g., auctions, sales, transfers) of LANDs. Between 2018 and 2020, 244,695 transactions of 92,598 parcels are retrieved (i.e., 2.64 tx/parcel). Retrieving trransactions in 2021 is in progress.

Note that the retrieved transactions were occurred not only on OpenSea but also on other NFT marketplaces, such as LooksRare and X2Y2.


## References
- Decentraland. (2018). "Introudcing LAND Estates," Decentraland Blog, https://decentraland.org/blog/announcements/introducing-land-estates/.
- Decentraland. (2019). "Decentraland's LAND Parcel Size," Decentraland Blog, https://decentraland.org/blog/platform/land-parcel-size/.
- Waldorf T. (2018). "Designing Genesis City: Roads and Urban Planning," Decentraland Blog, https://decentraland.org/blog/platform/designing-genesis-city-roads-urban-planning/.
