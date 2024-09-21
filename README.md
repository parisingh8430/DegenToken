# Project Title

This project is part of ETH+AVAX Proof Intermediate course by Metacrafters

In this project we had to build a custom token using Solidity and deploy it to Avalanche Fuji Testnet using Hardhat.

## Description

Make sure you have a Web3 wallet such as Metamask. Visit a Avalanche Fuji Testnet faucet to recieve tokens in your wallet, which will be used to pay the transaction fee

## Getting Started

### Installing
Install all the required packages npm i
Create a .env file and store your credentials inside WALLET_PRIVATE_KEY="YOUR PRIVATE KEY" SNOWTRACE_API_KEY="YOUR API KEY"
Make changes in the hardhat.config.js file FORK_FUJI = true // if you wish to fork the testnet, else false FORK_MAINNET = true // if you wish to fork the mainnet, else false
Deploy the token // Replace "SELECTED_NETWORK" with either fuji or mainnet
npx hardhat run --network "SELECTED_NETWORK" scripts/deploy.js Verification After the script executes successfully, the contract will be deployed on the selected net, and the address of the token would be printed.

You can verify the Token creation on Snowtrace by pasting its address.

To interact with the token, we'll be using Remix IDE

### Executing program
Open Remix IDE on a browser Upload the same contract and press Ctrl+S to save and compile it In the deploy tab, set the environment to Injected Provider Approve the connection to your Web3 wallet, and the IDE will be connected to the net, and account will be loaded automatically. Paste your token address and click At Address. This will load up the contract, and you will be able to interact with it.
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)


## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
