# Web3 Functions Use Cases and PoCs.

Github repo listing the existing Relay use-cases and PoCs.

### Quick Links Use Cases
- [Relay Unit Testing with Hardhat](https://github.com/gelatodigital/rel-example-unit-tests) 
- [Swap Fee Token](https://github.com/gelatodigital/rel-swap-fee-token) 
- [Hash Based ERC2771](https://github.com/gelatodigital/relay-hash-based-ERC2771) 
- [ Gelato Deployer](https://github.com/gelatodigital/relay-gasless-contract-deploy) 


&nbsp;  

---

### Relay Unit Testing with Hardhat
This project demonstrates unit testing with Relay.
It comes with sample counter contracts and unit tests for each.
Fee payment in ETH (native), as well as ERC20 tokens, is demonstrated where applicable.&nbsp;  

**Status**&nbsp;  
🟢 Ready to use&nbsp;  
🟢 Version: 4.0

Repo: [https://github.com/gelatodigital/rel-example-unit-tests](https://github.com/gelatodigital/rel-example-unit-tests)


---


### Swap Fee Token
This project demonstrates synchronous fee payment (callWithSyncFee/callWithSyncFeeERC2771) using an unsupported fee token. Rather than using _transferRelayFee, it introduces _swapAndTransferRelayFee which swaps the unsupported token to a supported fee token using any Uniswap-based router and transfers it to the fee collector.&nbsp; 


**Status**&nbsp;  
🟢 Ready to use&nbsp;  
🟢 Version: 4.0

Repo: [https://github.com/gelatodigital/rel-swap-fee-token](https://github.com/gelatodigital/rel-swap-fee-token)

---

### Hash Based ERC2771
This projects showcases how to run paralell Relay calls using hash based ERC2771 &nbsp; 

**Status**&nbsp;  
🟢 Ready to use&nbsp;  
🟢 Version: 4.0

Repo: [https://github.com/gelatodigital/relay-hash-based-ERC2771](https://github.com/gelatodigital/relay-hash-based-ERC2771)
 
---

### Gasless Contract Deployment aka Gelato Deployer
This project demonstrates network-agnostic contract deployment using Relay and 1Balance by introducing the deploy-sdk. Contracts are deployed at the same precomputed address on every network using Create2. This eliminates the need for dedicated deployer wallets and native tokens on every network providing a seamless developer experience. &nbsp; 

**Status**&nbsp;  
🟢 Ready to use&nbsp;  
🟢 Version: 4.0

Repo: [https://github.com/gelatodigital/relay-gasless-contract-deploy](https://github.com/gelatodigital/relay-gasless-contract-deploy)
