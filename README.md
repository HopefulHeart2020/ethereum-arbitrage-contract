# Flashloan Trading Smart Contract

## Usage

1. Rename `.env.example` file to `.env` inside the contracts directory
 
2. Config `.env` file. 

    Here, you need three things. 
    * Insert your INFURA Project ID. You can create a infura Project ID [here](https://infura.io). 
    * Insert your MetaMask (Kovan Testnet) 32byte wallet private key.
    * Insert your [etherscan](https://etherscan.io) account's API KEY.

3. Install yarn modules. Open terminal window and run:

```
npm install
npm i @truffle/hdwallet-provider@next
yarn install
```

4. Run Smart Contract function defintions defined in flashswap.js
```
yarn post
```

```
yarn migrate-kovan
```

```
yarn verify UniswapFlash1Inch --network  kovan
```



## Modifying UniswapFlash1Inch.sol


## Integrating 1Inch V4 Router 
## Kovan Testnet Past Examples
* Ensure to have your .env configuration setup with your etherscan API key, and your INFURA API keys as well. 

* Successful profiting $1,249 DAI 
Smart Contract Transaction: https://kovan.etherscan.io/tx/0x848afb676324d035ee6c58528bce0e2abe43c62a80ff4564aa4e4cd06fec262d



# Developer Instruction Manual (ETH MAINNET): 

## COMING SOON (THINGS REQUIRED)
* AAVE, EQUALIZER, DODO Flashloan contracts activated for Mainnet
* bot.js needs to be modified to lookup mainnet opportunities
* flashswap needs to change to mainnet from kovan testenet config 