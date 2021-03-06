# Uniswap Frontend
This an an open source interface for Uniswap - a protocol for decentralized exchange of Ethereum tokens.

* Website: [uniswap.io/](https://uniswap.io/)
* Docs: [docs.uniswap.io/](https://docs.uniswap.io/)
* Twitter: [@UniswapExchange](https://twitter.com/UniswapExchange)
* Reddit: [/r/Uniswap/](https://www.reddit.com/r/UniSwap/)
* Email: [contact@uniswap.io](mailto:contact@uniswap.io)
* Slack: [uni-swap.slack.com/](https://join.slack.com/t/uni-swap/shared_invite/enQtNDYwMjg1ODc5ODA4LWEyYmU0OGU1ZGQ3NjE4YzhmNzcxMDAyM2ExNzNkZjZjZjcxYTkwNzU0MGE3M2JkNzMxOTA2MzE2ZWM0YWQwNjU)
* Whitepaper: [Link](https://hackmd.io/C-DvwDSfSxuh-Gd4WKE_ig)

# About this fork

This fork is intended for people who want to deploy and play with
Uniswap locally on their own instance. It provides all the necessary
scripts to run local instance of Uniswap.

### To Start Development

###### Installing dependency
```bash
yarn
```

###### Running locally on Rinkeby
```bash
yarn start:rinkeby
```

###### Running locally on Ganache

First, you need to modify src/ducks/addresses.js

```bash
yarn start:ganache
```



###### Running locally on other testnet
```bash
REACT_APP_NETWORK_ID=2 REACT_APP_NETWORK='Ropsten Test Network' react-scripts start
```

### Contributions
Please open all pull requests against `dev` branch.
