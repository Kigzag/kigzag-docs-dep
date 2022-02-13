---
label: License
icon: info
---

The primary license for Kigzag Contracts V1 is the Business Source License 1.1 (`BUSL-1.1`), see [`LICENSE`](https://github.com/Kigzag/KigzagContractsV1/blob/main/LICENSE). 
    
Overall this repository is **not** available for production use !!!


## Exceptions

- All files in `contracts/interfaces/` are licensed under `GPL-2.0-or-later` (as indicated in their SPDX headers), see [`contracts/interfaces/LICENSE`](https://github.com/Kigzag/KigzagContractsV1/blob/main/contracts/interfaces/LICENSE)
- Several files in `contracts/libraries/` are licensed under `GPL-2.0-or-later` (as indicated in their SPDX headers), see [`contracts/libraries/LICENSE`](https://github.com/Kigzag/KigzagContractsV1/blob/main/contracts/libraries/LICENSE)
- All files in `contracts/test` remain unlicensed.

## Remarks

- Currently,
    - we won't be having any exchange token but the core contract has support for discounted fees based on the number of exchange tokens owned. This is done to ensure smooth future integration of exchange token next year after our protocol gains some traction.
  
    - we haven't implemented the logic for creator's bank contract. There must be some buffer between Creator Token launch and starting of Bank to mitigate risk and establish real valuations for NFTs as well as Creator Tokens which is much needed for using them as collateral for lending borrowing. However The intigration will require only deploying of Bank contract by creator and updating creatorBank value in XeldoraroCreatorFactory contract.



## Community

<a href="https://discord.gg/ExMb82zpnB" target="_blank"><img src="https://kigzag.com/images/discord.png" width="80" height="80"/></a>&emsp;&emsp;&emsp;
<a href="https://t.me/Kigzag" target="_blank"><img src="https://kigzag.com/images/telegram.png" width="80" height="80"/></a>&emsp;&emsp;&emsp;
<a href="https://twitter.com/Kigzag" target="_blank"><img src="https://kigzag.com/images/twitter.png" width="80" height="80"/></a>&emsp;&emsp;&emsp;
<a href="https://www.reddit.com/r/Kigzag/" target="_blank"><img src="https://kigzag.com/images/reddit.png" width="80" height="80"/></a>
