## Auto-participate

To automatically participate in Stochastic DAO's campaign, you can use `auto-participate.js`.

### Installation

First, download/clone this repository, make sure you also installed `Node.js` and `npm`.

Then, open your terminal/command prompt, install the necessary packages:

```
npm install
```

Next, be sure to insert your private key in `hardhat.config.js`.

### Configure

Go to `config.js` and change the contract address to the contract address that you want. It is currently set to the address of the contract that we have deployed on the Triton testnet. If you are deploying locally, replace the `riceAddress` value with the locally deployed contract address, if you are using a different network, provide the contract address there.

### Running

Simply type in and run:

```
npx hardhat run scripts/auto-participate.js --network triton
```

Or if you using local hardhat node, run:

```
npx hardhat run scripts/auto-participate.js --network localhost
```

**Remember to deploy the contracts to your local hardhat node and configure the contract address first!**
