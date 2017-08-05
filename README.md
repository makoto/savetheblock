# SaveTheBlock

An evidence based Initial Coin Offering insurance to make crowdsale more protectable against hacking.

## Overview

### What problem are you tackling?

- The recent crowdsale started raising unreasonable amount of money with little transparency of technical governance.
- With more cryptocurrencies sent to and kept on smart contracts, the incident of theft and scam are increasing.
- If the number of incidents increase, it will harm the overall reputation of Ethereum blockchain ecosystem as a whole.

### How do you solve the problem?

- Provide cyber insurance policy for crowdsale investors and/or crowdsale companies that lost their cryptocurrencies during the crowdsale period due to malicious hack caused by bugs in the smart contract.
- Premium is calculated based on manual/automatic assessment of the risks of each crowdsale smart contract.
- Payout occurs when bug was found during bug bounty period to cover the reward to security researchers as well as contract bug is bleached during the crowdsale period.

### Out of scope

- The rationality of the crowdsale project
- Whether the crowdsale terms are ethical or not.

### Inspiration behind the idea.

The original idea was formed when Makoto and other team members created a project called BountyMax which is a marketplace for automatic bug bounty programs among security researchers. It was developed as part of Thomson Reuters HackEthon and won the runner up prize.

During the [interview with CryptoCoinsnews](https://www.cryptocoinsnews.com/blockchain-based-sports-game-wins-thomson-reuters-hackethon/), Makoto stated the possibility of the concept expanded into insurance product as follows.

```
“At our PoC, each contract owner puts rewards for their own contract violation. The amount will be small unless you have big pockets. We can group the contracts together and have compound bounties so that a researcher who breaks one of the contracts can get a payout of the entire bounties combined.

Once we get enough data about the probability of contract violations, insurers can (potentially) underwrite policies so that we can have higher bounties than total rewards (aka premium) combined.”
```

This project is to reimagine the original concept tailored to meet the need of the current crowdsale smart contract codes.

## Research topics


### How do you major the risk of crowdsale?

Majoring security risks can be done by the followings.

- a. Verify that the known crowdsale has gone through recommended software release management procedures (either manually or by utilising source code repository API such as Github).
- b. Categorise complexity and risk of the smart contract (assessed by security auditor)
- c. Run automated analytics against smart contract to analyse risk level.
- d. Go through security bounty program.

### How do you market your product & services?

- Partnership with existing crowdsale marketplaces.
- Partnership with group of smart contract security auditors.

## Resources

### A: List of known best practices

- [Ethereum Contract Security Techniques and Tips](https://github.com/ConsenSys/smart-contract-best-practices)
- [Software Token Sale Best Practices](https://github.com/DavidJohnstonCEO/CrowdsaleBestPractices)

### B: Example of security code audits

- [Compiled list](https://docs.google.com/spreadsheets/d/1xZnUTUGPW72ln0_WHvjNaZ-9TM2BMMxB1oK4OyGfmiI/edit?usp=sharing&lipi=urn%3Ali%3Apage%3Ad_flagship3_messaging%3BlSyiQNncRma%2B0GbmrQ4vaw%3D%3D)

### C: Known Smart contract analysis tool

- [An Analysis Tool for Smart Contracts](https://github.com/melonproject/oyente)
- [Decompiler for Blockchain-based Ethereum Smart-Contracts](https://github.com/comaeio/porosity)
- [Code coverage for Solidity testing](https://www.npmjs.com/package/solidity-coverage)
- [Visualize Solidity control flow for smart contract security analysis](https://github.com/raineorshine/solgraph)

### D. Bug bounty as a smart contract

- [WeiFund bug bounty live honeypot](https://weifund.surge.sh/)
- [Bug bounty smart contract](https://github.com/OpenZeppelin/zeppelin-solidity/blob/master/contracts/Bounty.sol)

### Market: Current list of Crowdsale platform

- https://coinlist.co
- https://tokenmarket.net/ico-professional-services
- https://coralfundraiser.com
- http://weifund.io/

### Market: ICO market size

- https://www.coindesk.com/ico-investments-pass-vc-funding-in-blockchain-market-first/

### Market: ICO related bugs and thefts

-[THEDAO](http://www.coindesk.com/understanding-dao-hack-journalists/)
-[InsureX](https://www.reddit.com/r/ethtrader/comments/6mjw57/insurex_twitter_and_slack_have_been_hacked_do_not/)
-[CoinDash](https://hothardware.com/news/coindash-ico-hacked-ethereum-price-plummets
https://www.ethnews.com/ethereum-name-service-launch-delayed-by-bugs)
-[TokenCard](https://www.ethnews.com/tokencard-ico-bug-disproportionately-distributes-tokens)
-[Parity Multisig](https://news.bitcoin.com/ethereums-parity-client-users-lose-millions-multi-sig-hack/)
