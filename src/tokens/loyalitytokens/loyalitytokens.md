---
label: Loyalty Tokens
icon: git-branch
icon: token 
---
 
  These are **non-tradable** fixed price tickets to get exclusive services/products from creator. 

<!-- ![Samrt Contract Flow Diagram](./assets/tickets.svg) -->
<img src="./assets/tickets.png" width="400" height="250" />
  
##### Seervice, Rewards & much more...
  
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


##### Creator Token:
  - [x] Buy Creator Tokens at a price fixed by Creator/Community using network wrapped token like WETH/WMATIC/WAVAX or stablecoins like USDC, DAI. These base tokens/payment tokens received are send to DAO contract which handles treasury.

##### Creator DAO:
  - [x] Token holders can make proposals 
  - [x] Creator/Community can airdrop Creator Tokens to any account since these tokens cannot be sold and only be used to access premium stuff, creator can airdrop into wallet giving a fan free access to creator's products.
  - [x] Creator/Community can add managers and those managers will be given allowances in base tokens / payment tokens received by the DAO contract on Creator Token sale. Using these allowances they can pay folks/employees, they hire, for specific task either on Pay Per Task basis or monthly salaries. Managers can transfer from their allowances to the employee's allowance value. 
  - [x] If creator is a person/business then creator can redeem any amount of base tokens/payment tokens from DAO since it his/her earning. However, it is advisable to keep leave some amount for allowances. 
  - [x] In case creator is a community with no central entity then direct/unapproved redeem is not available and every token redeemed goes through allowances voting process.
  - [x] 2 types of proposals 
    - [x] Allowances Proposals to decide amount allocated per manager. Single proposal can handle multiple managers' allowances.
    - [x] General Proposal will contain link to their DAO Forum's proposal page where detailed discussions can take place. Results of these proposals will be acted upon by community members in good faith.
  - [x] Token holders can vote for each of the proposal
  - [x] Result of voting is based on number of CreatorTokens held by the voter. For first case only 2 choices, no or yes. For General Proposal any number of choices are allowed. 
  
##### Creator Vault:
  - [x] Creator/Community can add NFTs to vault. Further list it for Sale at before mentioned price.
  - [x] NFTs are sold for Creator Tokens which are burnt since they are only a form of voucher/tickets.