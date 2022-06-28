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


## Retrieving LAND Transactions from OpenSea
[OpenSea API](https://docs.opensea.io/reference/api-overview) is used to retrieve all the historical events (e.g., auctions, sales, transfers) of LANDs. Between 2018 and 2020, 244,695 transactions of 92,598 parcels are retrieved (i.e., 2.64 tx/parcel). Retrieving trransactions in 2021 is in progress.

Note that the retrieved transactions were occurred not only on OpenSea but also on other NFT marketplaces, such as LooksRare and X2Y2.


## References
- Decentraland. (2018). "Introudcing LAND Estates," Decentraland Blog, https://decentraland.org/blog/announcements/introducing-land-estates/.
- Decentraland. (2019). "Decentraland's LAND Parcel Size," Decentraland Blog, https://decentraland.org/blog/platform/land-parcel-size/.
- Waldorf T. (2018). "Designing Genesis City: Roads and Urban Planning," Decentraland Blog, https://decentraland.org/blog/platform/designing-genesis-city-roads-urban-planning/.
