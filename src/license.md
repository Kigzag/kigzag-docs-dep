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

## Responsible disclosure

At Kigzag, we consider the security of our systems a top priority. But even putting top priority status and maximum effort, there is still possibility that vulnerabilities can exist. 

!!! In case you discover a vulnerability, we would like to know about it immediately so we can take steps to address it as quickly as possible.  

If you discover a vulnerability, please do the following: 

E-mail your findings to kigzagofficial@gmail.com. 

Do not take advantage of the vulnerability or problem you have discovered. 

Do not reveal the problem to others until it has been resolved. 

Do not use attacks on physical security, social engineering, distributed denial of service, spam or applications of third parties. and 

Do provide sufficient information to reproduce the problem, so we will be able to resolve it as quickly as possible. Complex vulnerabilities may require further explanation so we might ask you for additional information. 
!!!

!!! We will promise the following: 

We will respond to your report within 3 business days with our evaluation of the report and an expected resolution date. 

If you have followed the instructions above, we will not take any legal action against you in regard to the report. 

We will handle your report with strict confidentiality, and not pass on your personal details to third parties without your permission. 

If you so wish we will keep you informed of the progress towards resolving the problem. 

In the public information concerning the problem reported, we will give your name as the discoverer of the problem (unless you desire otherwise).

As a token of our gratitude for your assistance, we offer a reward for every report of a security problem that was not yet known to us. The amount of the reward will be determined based on the severity of the leak, the quality of the report and any additional assistance you provide.  
!!! 
## Remarks

- Currently,
    - we won't be having any exchange token but the core contract has support for discounted fees based on the number of exchange tokens owned. This is done to ensure smooth future integration of exchange token next year after our protocol gains some traction.
  
    - we haven't implemented the logic for creator's bank contract. There must be some buffer between Creator Token launch and starting of Bank to mitigate risk and establish real valuations for NFTs as well as Creator Tokens which is much needed for using them as collateral for lending borrowing. However The intigration will require only deploying of Bank contract by creator and updating creatorBank value in XeldoraroCreatorFactory contract.



## Community

<a href="https://discord.gg/ExMb82zpnB" target="_blank"><img src="https://kigzag.com/images/discord.png" width="80" height="80"/></a>&emsp;&emsp;&emsp;
<a href="https://t.me/Kigzag" target="_blank"><img src="https://kigzag.com/images/telegram.png" width="80" height="80"/></a>&emsp;&emsp;&emsp;
<a href="https://twitter.com/Kigzag" target="_blank"><img src="https://kigzag.com/images/twitter.png" width="80" height="80"/></a>&emsp;&emsp;&emsp;
<a href="https://www.reddit.com/r/Kigzag/" target="_blank"><img src="https://kigzag.com/images/reddit.png" width="80" height="80"/></a>
