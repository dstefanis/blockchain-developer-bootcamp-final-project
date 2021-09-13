# blockchain-developer-bootcamp-final-project

Concept is an NFT to track your on-chain reputation

1. User mints their personal NFT
2. User will only be able to mint 1 NFT per ETH address
3. The NFT will have a set of default attributes
4. A "NFT Updater" contract exists that has the sole ability to update individual NFT's attributes
5. A DAO (or specific third party) is the only one in control of the "NFT Updater" contract
6. The DAO can interact with the "NFT Updater" contract to specify the attributes that should be updated on a specific NFT
7. A user will be granted or denied access a Discord channel based on if they hold the NFT and if the NFT contains certain attributes