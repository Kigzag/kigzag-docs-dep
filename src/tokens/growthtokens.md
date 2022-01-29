---
label: Growth Tokens
icon: git-branch
icon: rocket
---

## Growth Tokens
- [x] <b>Creator Vault</b>
  - [x] Creator Add/Mint NFTs to vault contract
  - [x] Launch Creator Token, make it available for community to buy. Liquidity is bought not rented. Since CreatorTokens offer NFT, DAO, Banking related utilities they do have value since day one of launch especially to access Vault NFTs.
  - [x] Price of NFTs is pegged to certain number of tokens at the time of launch and stays same forever so scope of rise in NFT prise is only from rise in token price of CreatorToken
  - [x] Same number of tokens are minted every time an NFT is added to vault, these tokens are transferred to DAO contract and can be used for Airdrop, FLO, Grants for community [batch supported]
  - [x] Holder of CreatorTokens can redeem NFT and tokens worth NFT price will be burnt from his wallet [batch supported]
  - [x] Holder of CreatorTokens can return his redeemed NFT and tokens worth NFT price will be minted to his wallet [batch supported]
  - [x] 2 NFTs of a creator can be swapped for no fees [batch supported]
  - [x] Creator/Community can add Further Liquidity to Pair Contract by sale of CreatorTokens from DAO contract. Vault Contract hosts this sale.
  - [x] Vault can own millions of NFTs. There are no arrays storing Vault's NFT data about redeemed NFTs. Instead a simple mapping of vaultId to NFT Contract and vaultId to TokenId is used and to know whether an NFT is redeemed a simple ownerOf() function call for a given vaultId will help determine. This is done to avoid For Loops over large arrays which will run out of gas after few thousand NFTs. Hence avoiding scaling bottleneck.

- [x] <b>Creator Pair</b>
  - [x] Constant Product based AMM for CreatorToken - BaseToken pair
  - [x] Swap between tokens

- [x] <b>Creator Vesting Vault</b>
  - [x] Tokens allocated to creator at the start are vested over a period of time, 2 years by default with 3 months of cliff period during which the vested token count will be increasing just that creator cannot redeem them due to cliff.

- [x] <b>Creator DAO</b>
  - [x] Token holders can make proposals 
  - [x] Creator can choose managers and those managers will be given allowances. Using these allowances they can pay folks/employees, they hire, for specific task either on Pay Per Task basis or monthly salaries. Managers can transfer from their allowances to the employee's allowance value. 
  - [x] 4 types of proposals 
    - [x] Airdrops, before CreatorToken launch as it is, after launch with voting and approval 
    - [x] Further LIquidity Offering (FLO) proposals to increase size of market to ensure greater liquidity in Pair contract
    - [x] Allowances Proposals to decide amount allocated per manager. Single proposal can handle multiple managers' allowances.
    - [x] General Proposal will contain link to their DAO Forum's proposal page where detailed discussions can take place. Results of these proposals will be acted upon by community members in good faith.
  - [x] Token holders can vote for each of the proposal
  - [x] Result of voting is based on number of CreatorTokens held by the voter. For first 3 cases only 2 choices, no or yes. For General Proposal any number of choices are allowed. 

- [x] <b>Migration to V2</b> 
  - [x] Pair, DAO, Vault and Bank contracts contains Token and NFT assets which is transfered via Migration Contract to V2 version of Pair, DAO, Vault and Bank contracts
  - [x] Before migration of a Creator Community's assets, community members must vote for or against mirgration and migration contract will be made public much in advance. Voting is implemented in CreatorToken contract. This is done to ensure security of assets and decentralisation of decision making. This is important since in Xeldorado Protocol liquidity isn't rented its owned.
  - [x] If voted no, then assets will stay in V1, current version, of Xeldorado Protocol
  - [x] There can be 2 types of migration, partial and complete. In partial migration only one or two parts maybe updated like only Vault contract updated and hence needs asset transfer only for Vault's V2 version. In full migration all 4 contracts will be updated and maybe entire Factory and CreatorFactory may also be updated. 
  - [x] Migration function in Pair, DAO, Vault and Bank are implemented with check on voting status passed and only after that migration contract, that has been voted, is allowed to transfer asset by deploying V2 version of the contract.
  - [x] Migration function also updates all dependent contracts with new address of V2 contract. For e.g. if Vault contract gets migrated to V2,then its dependent contract CreatorToken, CreatorNFT, CreatorDAO and CreatorFactory will get updated with V2 address of vault variable.

- [ ] <b>Creator Bank (Not needed on day one, can be integrated after launch)</b>
  - [ ] Bank contract needs price data from CreatorToken to decide upon interest rates. Hence, Each creator can have different interest rates
  - [ ] Community members, holders of CreatorToken can stake their CreatorTokens for some yield
  - [ ] NFT Loans: Holder of NFTs from Creator Vault can use it as collateral for borrowing CreatorTokens, since we have price data of CreatorTokens and also price of single NFT is fixed w.r.t. to CreatorToken we can estimate realistic valuation of NFTs
  - [ ] Flash Loans on Creator Tokens 

- [ ] <b>External Contract Functions</b>
  - [ ] 2 NFTs of different creator with same BaseTokens can be swapped with small fees 
  - [ ] If someone owns an NFT, you can buy it for premium by placing a bid (Auction smart contract will be placed separately) 
  - [ ] Base Token Pairs: Use a Curve kind of multi token pairs for BaseTokens for swap. This will help NFTs of creator that don't have same base token. Liquidity will be added by us using a small fraction of profit being earnt in BaseTokens. Swap in these pools will have no fees.
