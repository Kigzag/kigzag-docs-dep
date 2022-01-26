---
label: About
icon: info
---
# [Xeldorado Protocol](https://main.xeldorado.live/)

![Samrt Contract Flow Diagram](./assets/social_token_development1.png)

### Xeldorado - A general purpose Social Token Protocol to build Creator Economy using 2 types of tokens:
  
#### 1. Loyalty Tokens (Launching soon)
  These are **non-tradable** fixed price tickets to get exclusive services/products from creator. 

<!-- ![Samrt Contract Flow Diagram](./assets/tickets.svg) -->
<img src="./assets/tickets.png" width="400" height="250" />
  
##### Products/Rewards can be but not limited to:
  
  - gated community on discord, telegram
  
  - exclusive video content, one-on-one intereaction (online/offline), shoutouts on social media
  
  - merchandise
  
  - real world use cases like access to front row seats of Creator's show (if creator is a musician or comedian). 
  
  - Businesses can also be a creator and reward their loyal customers (token holders) with exclusive products and discounts. This will make their business **Network Effect** driven by creating **sticky customers**.

![Samrt Contract Flow Diagram](./assets/premium.svg)

##### Key Offerings:

   - <b>Creator Tokens</b> : fans and followers can buy creator tokens at price fixed by creator or community. These tokens should be treated as vouchers or tickets which can be bought but one cannot sell them back directly. A creator can choose to create subscription by deducting some tokens from holder on regular basis.

   - <b>NFT Sale against Creator Token</b> : Creator or community can decide upon price of NFT in creator tokens and list it for sale. 

   - <b>DAO</b> : token holders can take part in creator community governance. Handles creator treasury. 
   
   - <b>Accepted Payments & Allowances</b> : 3 tokens are accepted for buying of Creator Tokens as well as receiving allowances. These are wrapped network's token (like **WETH** for ethereum. **WMATIC** for polygon, **WAVAX** for Avalanche, etc.), **USDC**, **DAI**. In case user doesn't own wrapped ERC20 version, we will integrate the function calls to wrap the token.

##### Benefits:
  - Same Creator Token can gives access across a range of products both online and offline.
  
  - Fans/Followers can take part in creator's decision making which takes participation in creator's journey to another level

  - Global nature of blockchain makes cross border ticketting easier.


#### 2. Growth Tokens (Need regulatory approval before launch)
  Creator/Community are **Tradable** Social Tokens that offer potential increase in price as Creator/Community grows. Growth Tokens are superior version of Loyalty Tokens. They are traded with in-house AMM and offers:
   - <b>Liquidity Pair of CreatorToken-BaseToken</b> : Gateway between Creator Economy and External World. Creator can choose from a list of options to select best suited BaseToken. For e.g. USDC, DAI, WETH, WBTC, BUSD, etc. 

   - <b>NFTs that are pegged to CreatorToken</b> : Price of 1 NFT will be constant w.r.t. CreatorToken and every time a new NFT is added to the vault same number of CreatorTokens will be minted to ensure the peg. Price of NFT soars when Creator Tokens soars w.r.t. Base Tokens. Secondary Market for NFT allows price to soar further but the floor price of NFTs stay constant w.r.t. Creator Tokens. At this price NFT holder can sell to the vault.

   - <b>Bank</b> : for NFT backed lending borrowing of Creator Tokens

   - <b>DAO</b> : for Creator community governance. Handles community treasury.

Creator/Community can decide to opt for anyone of them.

# About Sakura Casino

!!!warning

SakuraCasino roulette is in beta. Our contract hasn't been audited yet. Please be sure to know the risks before betting or pooling.

!!!

[SakuraCasino](https://sakura.casino) is a decentralized online casino based on the [Polygon (Matic)](https://polygon.technology/) network.
The casino consists of a roulette contract deployed in the *Matic mainnet* with an UI that interacts with that contract.

---

### Randomness beacon

SakuraCasino uses [Chainlink VRF](https://chain.link/solutions/chainlink-vrf), which is a verifiable random function for smart contracts provided by Chainlink's oracle network.

![](assets/chainlink_vrf_graphic.svg)

This is the first [**provably-fair**](https://en.wikipedia.org/wiki/Provably_fair_algorithm) crypto roulette with true random number generation.

!!!secondary

Most Solidity-based DApps use other sources for randomness, like the *blockhash*, but those have been proven to be [vulnerable and biasable](https://betterprogramming.pub/how-to-generate-truly-random-numbers-in-solidity-and-blockchain-9ced6472dbdf).

!!!

---

### Low fees and DAI betting

The roulette is deployed in the *Matic network* because of its low fees to operate. Making a bet cost less than a cent and you can use the [DAI Stablecoin](https://makerdao.com/).

Pooling and earning interest on the Roulette earnings is open to everyone. 

---

### Non-KYC and censorship resistance

The Roulette contract is deployed in the blockchain. It cannot be modified or tampered with. Anyone with a *Matic wallet* and *DAI tokens* can bet or provide liquidity by simply interacting with the contract.

There's a nice user interface deployed at [app.sakura.casino](https://app.sakura.casino/) for interacting with the contract. You can also clone our open source [Github repository](https://github.com/sakuracasino/roulette-ui) and run the DApp locally.

!!! Why DAI?

We use *DAI* because it's the only stablecoin that can't have blacklisted address (unlike [USDT](https://www.theblockcrypto.com/linked/80249/tether-blacklist-addresses-ethereum) or [USDC](https://www.theblockcrypto.com/linked/102761/centre-consortium-blacklisted-seven-usdc-addresses-wednesday)). Another benefit is that *DAI* is not dependant on any goverment or entity to [secure its collaterals](https://makerdao.com/en/whitepaper/#collateral-assets).

!!!

---

## Support

Our software it's still in an early stage and we have a lot of ideas for future functionality. Be sure to join us in our [Discord server](https://discord.gg/DHux5uEvrJ) and get involved with the project.