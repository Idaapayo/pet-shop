## INSTRUCTIONS ON HOW TO RUN

### Prerequisites

`npm install -g truffle`
 
* Download ganache 

### How to run
* Open terminal in root directory
* `truffle compile`
* `truffle migrate`
* open ganache - you should see several created accounts in the accounts section

### Testing the smart contract
* `truffle test`

### Interacting with dapp in the browser
* install MetaMask as an extention in chrome
* Import an account using the mnemonic that appears on ganache
* In the networks section on metamask, create a new network with network url as http://127.0.0.1:7545 and 1337 as the chainID
* Close the settings page and return to accounts page. You should have about 99 eth

### Starting local web server
* `npm run dev`
* a page will launch with the various pets to adopt
* allow metamask to connect to your dapp
* click on the pet that you want to adopt and click submit to approve transaction on metamask
* the adopt button will change to success
* In metamask the transaction will be listed in the history section