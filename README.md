# Decentraland Analytics

## Decentraland
Decentraland is one of the most popular decentralized virtual reality (VR) platforms, powered by the Ethereum blockchain. Within the platform, users can create, experience, and monetize their content and applications. Specificially, the finite, traversable, 3D virtual space is called LAND, a non-fungible digital asset maintained in an Ethereum smart contract. The 16m x 16m smallest unit of LAND is named a _parcel_, identified by cartesian coordinates (x,y). At the time of writing, LAND consists of 90,601 different parcel. On each parcel, users can build a _scene_ by using design tools like the [Builder](https://builder.decentraland.org/) or the Decentaland SDK, offering parcel-specific virtual experience to other users. Users can also create an _Estate_ by grouping two or more directly adjacent parcels to manage larger holdings or build larger scenes. Conversely, users can dissolve an Estate into separate parcles as well.

It is possible to trade both parcles and Estates on the [official marketplace](https://market.decentraland.org/) using MANA or on third-party NFT marketplaces like OpenSea using ETH, USDC, DAI, or other cryptocurrencies.

Below is a list of main characteristics distinguishing each LAND parcel:
- Distance to District
- Distnace to Plaza
- Distance to Road
- Neighborhood
- ...

[Here](https://docs.decentraland.org/decentraland/introduction/) is the official documentation of Decentraland.
[Here](https://nonfungible.com/blog/discovery-of-decentraland?utm_campaign=Weekly%20Newsletter&utm_medium=email&_hsmi=200553779&_hsenc=p2ANqtz-9qmLYq4OxVvb74c0vTQKXxIjKNx6QmgrTu_jEWgcpxIeCXBQG6twHvi2Wpc_xMnX6zVpHL9ORDqQ8u_FPl_OrF6pTq-g&utm_content=200553779&utm_source=hs_email) is a good summary of the history and evolution of Decentraland by NonFungible.com (2021).


## Retrieving LAND Transactions from OpenSea
[OpenSea API](https://docs.opensea.io/reference/api-overview) is used to retrieve all the historical events (e.g., auctions, sales, transfers) of LANDs from 2018 to 2020. The retrieval is in progress; 75,560 transactions of 30,000 parcels have been collected so far.
