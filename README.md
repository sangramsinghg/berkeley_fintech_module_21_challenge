# Berkeley Fintech Module 21 Challenge

Setup a new fungible ERC-20 compliant cryptocurrency KaseiCoin in solidity.
Mint the fungible token using a timed and capped crowdsale to sell the tokens.

## Evaluation Evidence 
### Solidity Compiler - Compiled KaseiCoin
![Compiled KaseiCoin](Images/kasei_coin_evaluation_evidence.png)
### Solidity Compiler - Compiled KaseiCoinCrowdsale
![Compiled KaseiCoinCrowdsale](Images/kasei_coin_crowdsale_evaluation_evidence.png)
### Solidity Compiler - Compiled KaseiCoinCrowdsaleDeployer
![Compiled KaseiCoinCrowdsaleDeployer](Images/kasei_coin_crowdsale_deployer_evaluation_evidence.png)

## Use the KaseiCoinCrowdsaleDeployer to deploy the KaseiCoin Crowdsale
![Setup the KaseiCoinCrowdsaleDeployer](Images/kasei_coin_crowdsale_deployer_deployment_1_2.png)
## Deployed the Kasei Coin Crowdsale Deployer
![Deployed Kasei Coin Crowdsale Deployer ](Images/kasei_coin_crowdsale_deployer_deployment_2_2.png)
## Deploy the Kasei Coin Crowdsale 
![Deploy Kasei Coin Crowdsale](Images/kasei_coin_crowdsale_deployer_deployment_3_2.png)
## Deployed Kasei Coin Crowdsale
![Deployed Kasei  Kasei Coin](Images/kasei_coin_crowdsale_deployer_deployment_4_2.png)

## Buy 54321 tokens
![Buy 54321 Tokens](Images/kasei_coin_crowdsale_deployer_deployment_5_2.png)
![Buy 54321 Tokens Metmask](Images/kasei_coin_crowdsale_deployer_deployment_6_2.png)

## Verify in Remix Crowdsale that the 54321 wei/tokens have been raised 
![Verify the 54321 Tokens in Remix](Images/kasei_coin_crowdsale_deployer_deployment_7_2.png)
## Verify in Ganache that the 54321 wei/tokens have been raised 
![Verify the 54321 Tokens in Ganache](Images/kasei_coin_crowdsale_deployer_deployment_8_2.png)
## Verify in Remix console that the 54321 wei/tokens have been raised 
![Verify the 54321 Tokens in Remix Console](Images/kasei_coin_crowdsale_deployer_deployment_9_2.png)
## Verify in Remix Kasei Token that the 54321 wei/tokens have been supplied
![Verify the 54321 Tokens in Remix Kasei Token](Images/kasei_coin_crowdsale_deployer_deployment_10_2.png)
## Verify in Remix Kasei Token that the 54321 wei/tokens have been supplied using the balanceOf
![Verify the 54321 Tokens in Remix Kasei Token balanceOf](Images/kasei_coin_crowdsale_deployer_deployment_11_2.png)

## Verify in Metmask that the 54321 wei/tokens have been supplied to Account 4
![Verify the 54321 Tokens in Metamask Account 4](Images/kasei_coin_crowdsale_metamask_1.png)
## Verify in Metmask that the 54321 wei/tokens have been supplied to Account 4 in Swap Section
![Verify the 54321 Tokens in Metamask Account 4 Swap](Images/kasei_coin_crowdsale_metamask_2.png)

## Optional: Timed and Capped Crowdsale
### Use the KaseiCoinCrowdsaleDeployer to deploy the KaseiCoin Crowdsale
![Setup the KaseiCoinCrowdsaleDeployer](Images/kasei_coin_crowdsale_optional_deployer_1.png)
### Deployed the Kasei Coin Crowdsale Deployer
![Deployed Kasei Coin Crowdsale Deployer ](Images/kasei_coin_crowdsale_optional_deployer_2.png)
### Deploy the Kasei Coin Crowdsale and Coin Token
![Deploy Kasei Coin Crowdsale and Coin Token](Images/kasei_coin_crowdsale_optional_deployer_3.png)

### Buy 1000 tokens
![Buy 1000 Tokens](Images/Images/kasei_coin_crowdsale_optional_deployer_4.png)
### Buy 4000 tokens
![Buy 4000 Tokens](Images/Images/kasei_coin_crowdsale_optional_deployer_5.png)

### Verify that the goal of 5000 is reached and weiRaised is 5000
![Goal Reached](Images/Images/kasei_coin_crowdsale_optional_deployer_6.png)
### Verify that the cap of 5000 is reached and hasClosed is false
![Cap Reached](Images/Images/kasei_coin_crowdsale_optional_deployer_7.png)
### Verify in Ganache that the 5000 wei/tokens have been raised 
![Verify the 5000 Tokens in Ganache](Images/kasei_coin_crowdsale_optional_deployer_8.png)
### Verify in Ganache that the eth in 0xA92 and 0x481 accounts have decreased 
![Verify the eth in 0xA92 and 0x481 in Ganache](Images/kasei_coin_crowdsale_optional_deployer_12.png)

### Verify in Metmask that the 5000 wei/tokens have been supplied to Account 4
![Verify the 5000 Tokens in Metamask](Images/kasei_coin_crowdsale_optional_deployer_9.png)
### Verify in Metmask that the 5000 wei/tokens have been supplied to Account 4 in Swap Section
![Verify the 5000 Tokens in Metamask Swap](Images/kasei_coin_crowdsale_optional_deployer_10.png)
_
### Finalize before the closing time - fails
![Verify that the finalize before closing fails](Images/kasei_coin_crowdsale_optional_deployer_11.png)
### Finalize after the closing time (30 mins from crowdsale deployment) - passes
![Verify that the finalize after closing - passes](Images/kasei_coin_crowdsale_optional_deployer_13.png)
### Verify the finalized crowdsale - finalized is true and hasClosed is true and isOpen is false
![Verify that the finalized crowdsale](Images/kasei_coin_crowdsale_optional_deployer_14.png)

---

## Technologies

This project uses the following packages:

* [Remix](https://remix.ethereum.org/) - Remix is a browser-based compiler and IDE that enables users to build Ethereum contracts with Solidity language and to debug transactions.

* [Solidity](https://docs.soliditylang.org/) - Solidity is an object-oriented, high-level language for implementing smart contracts. Smart contracts are programs which govern the behaviour of accounts within the Ethereum state.

* [MetaMask](https://metamask.io/) - A crypto wallet & gateway to blockchain apps.

* [Ganache](https://www.trufflesuite.com/ganache) - Quickly fire up a personal Ethereum blockchain which you can use to run tests, execute commands, and inspect state while controlling how the chain operates..

---

## Installation Guide

This project can be run online. There is no need to install any packages locally.

---

## Usage

Please download the project or clone the project using git clone

Please launch remix by typing the following on the browser:

```python
https://remix.ethereum.org/
```

---

## Contributors

Sangram Singh (sangramsinghg@yahoo.com)

---

## License

MIT