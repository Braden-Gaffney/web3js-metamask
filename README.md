This document imports Web3.js, creates several placeholders that will be used to display network information, and defines a script that checks for an injected provider. 
If an injected provider is found, it's used to construct a new Web3 instance and connect to the Ethereum network.
A check is performed to ensure that the injected provider is coming from MetaMask and the result of this check is displayed to the user. 
Once connected through the injected provider, the script updates the placeholders with the chain ID and latest block number, and creates an event subscription to update the block number as new blocks are created. 
If no injected provider is found, the user is instructed to install MetaMask
