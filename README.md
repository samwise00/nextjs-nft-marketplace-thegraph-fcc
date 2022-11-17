1. Instead of reading events from Moralis, we will
    1. Index them with The Graph
    2. Read from The Graph

However, we will still use Moralis for wallet connection and interaction with the contract functions.

The Graph implementation is in another repo https://github.com/samwise00/thegraph-nft-marketplace-fcc

Access it simply by setting query url `NEXT_PUBLIC_SUBGRAPH_URL=https://api.studio.thegraph.com/query/{id}/nft-marketplace/v0.0.2` in `.env`

Then create subgraph queries [like here](./constants/subgraphQueries)

Then consume the data object in the front end.

We are now utilizing decentralized data structures 👏
