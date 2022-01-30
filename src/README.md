---
label: About Kigzag
icon: info
---

# [Kigzag Protocol](https://main.xeldorado.live/)

![Samrt Contract Flow Diagram](./assets/social_token_development1.png)

A general purpose Social Token Protocol to build Creator Economy using 2 types of tokens:
  
#### 1. Loyalty Tokens (Launching soon)
  These are **non-tradable** fixed price tickets to get exclusive services/products from creator. 

<!-- ![Samrt Contract Flow Diagram](./assets/tickets.svg) -->
<img src="./assets/tickets.png" width="400" height="250" />
<br/>

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

## Documentation

White paper & Docs for Kigzag Protocol is currently under development.

## Tests

For tests please refer to [`README`](https://github.com/Xeldorado/XeldoradoContractsV1/blob/main/test/README.md) from test folder.

## Licensing

The primary license for Kigzag Contracts V1 is the Business Source License 1.1 (`BUSL-1.1`), see [`LICENSE`](https://github.com/Xeldorado/XeldoradoContractsV1/blob/main/LICENSE). 

<h3>
    
```diff
!!! Overall this repository is not available for production use !!!
```

</h3>

### Exceptions

- All files in `contracts/interfaces/` are licensed under `GPL-2.0-or-later` (as indicated in their SPDX headers), see [`contracts/interfaces/LICENSE`](https://github.com/Xeldorado/XeldoradoContractsV1/blob/main/contracts/interfaces/LICENSE)
- Several files in `contracts/libraries/` are licensed under `GPL-2.0-or-later` (as indicated in their SPDX headers), see [`contracts/libraries/LICENSE`](https://github.com/Xeldorado/XeldoradoContractsV1/blob/main/contracts/libraries/LICENSE)
- All files in `contracts/test` remain unlicensed.

## Community

<a href="https://discord.gg/ExMb82zpnB" target="_blank"><img src="https://main.xeldorado.live/images/discord.png" width="80" height="80"/></a>&emsp;&emsp;&emsp;
<a href="https://t.me/Kigzag" target="_blank"><img src="https://main.xeldorado.live/images/telegram.png" width="80" height="80"/></a>&emsp;&emsp;&emsp;
<a href="https://twitter.com/Kigzag" target="_blank"><img src="https://main.xeldorado.live/images/twitter.png" width="80" height="80"/></a>&emsp;&emsp;&emsp;
<a href="https://www.reddit.com/r/Kigzag/" target="_blank"><img src="https://main.xeldorado.live/images/reddit.png" width="80" height="80"/></a>

## Responsible disclosure

At Kigzag, we consider the security of our systems a top priority. But even putting top priority status and maximum effort, there is still possibility that vulnerabilities can exist. 

In case you discover a vulnerability, we would like to know about it immediately so we can take steps to address it as quickly as possible.  

If you discover a vulnerability, please do the following: 

    E-mail your findings to kigzagofficial@gmail.com; 

    Do not take advantage of the vulnerability or problem you have discovered; 

    Do not reveal the problem to others until it has been resolved; 

    Do not use attacks on physical security, social engineering, distributed denial of service, spam or applications of third parties; and 

    Do provide sufficient information to reproduce the problem, so we will be able to resolve it as quickly as possible. Complex vulnerabilities may require further explanation so we might ask you for additional information. 

We will promise the following: 

    We will respond to your report within 3 business days with our evaluation of the report and an expected resolution date; 

    If you have followed the instructions above, we will not take any legal action against you in regard to the report; 

    We will handle your report with strict confidentiality, and not pass on your personal details to third parties without your permission; 

    If you so wish we will keep you informed of the progress towards resolving the problem; 

    In the public information concerning the problem reported, we will give your name as the discoverer of the problem (unless you desire otherwise); and 

    As a token of our gratitude for your assistance, we offer a reward for every report of a security problem that was not yet known to us. The amount of the reward will be determined based on the severity of the leak, the quality of the report and any additional assistance you provide.  

## Remarks

- Currently,
    - we won't be having any exchange token but the core contract has support for discounted fees based on the number of exchange tokens owned. This is done to ensure smooth future integration of exchange token next year after our protocol gains some traction.
  
    - we haven't implemented the logic for creator's bank contract. There must be some buffer between Creator Token launch and starting of Bank to mitigate risk and establish real valuations for NFTs as well as Creator Tokens which is much needed for using them as collateral for lending borrowing. However The intigration will require only deploying of Bank contract by creator and updating creatorBank value in XeldoraroCreatorFactory contract.


