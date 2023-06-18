**Our Dorahack buidl**: https://dorahacks.io/buidl/6488

**Our Pitch + Testing demo video**: https://youtu.be/eFapH3GMcXQ


Stochastic DAO specializes in the creation of fair and unmanipulated on-chain randomness, leveraging the security, decentralization, and transparency for the Nautilus dapps ecosystem.


## For developers using Stochastic DAO's random number generator

Sample contracts are available here: https://github.com/stochasticdao/stochasticdao/tree/main/examples


## For developers who are interested in the protocol

### Dependencies

* npm
* node.js

### Setup

1. Clone this repository.

2. Install the required packages:
```
npm install
```

3. Edit your private key and make necessary configurations in `hardhat.config.js`.

### Compile

```
npx hardhat compile
```

### Deploy

Locally:

```
npx hardhat run --network localhost scripts/deploy.js
```

On Triton testnet:

```
npx hardhat run --network triton scripts/deploy.js
```

### Test

```
npx hardhat test
```


## For DAO participants

You can run a bot to participate automatically (addressed here: https://github.com/stochasticdao/stochasticdao/blob/main/auto-participate.md).


## Contract Addresses

### Triton Testnet

* `Token`: 0x1dd8c26e83C851b0A40dEFAe2e3dF879Bf00cD1d
* `Rice` (the main RNG): 0xD69A36a2629F10678c369E2c8B10688774B96BFb
