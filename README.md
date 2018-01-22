# kickstart
NOTE: You need a `.env` file in your repo, which isn't in this repo because I .gitignored it.

Instructions to run:
- Create a API URL from https://infura.io/ (it's free)
- Download MetaMask https://metamask.io/
  - Create an account(testing purposes)
  - Save your account mneomic
  - Set network to Rinkeby
  - Get free ETH for test network at https://faucet.rinkeby.io/
- Create a `.env` file
  - ACCOUNT_MNEMONIC=your account mneomic from metamask
  - INFURA_LINK=your api infura link
- Command Prompt
  - npm install
  - node ethereum/compile.js
  - node ethereum/deploy.js
    - save address (console log from terminal)
    - add in .env ADDRESS=saved address
  - npm run dev (http://localhost:3000)
  
Simple full stack app for Ethereum using tools, such as, Solidity, web3, ganache-cli, React, Node, Nextjs, MetaMask, etc

Project is based on the website Kickstarter and some of the underlying issues it has.  The main problem with Kickstarter is the funding goes straight to the user who starts the campaign.  With blockchain all of the funding is transparent, and with smart contracts we can add some safe measures to the project.

The smart contract here can create requests for ethereum and users can vote whether the funds can be released or not(At the moment I set it to 1 otherwise if people wanted to test the app end-to-end they'd need more accounts to play with, otherwise would be 50% or higher)

### Screenshots
![screenshot from 2018-01-19 17-43-24](https://user-images.githubusercontent.com/13317855/35180668-87e1bb3a-fd69-11e7-8e13-b164373f7d5d.png)
![screenshot from 2018-01-19 17-43-45](https://user-images.githubusercontent.com/13317855/35180669-8b24e7d6-fd69-11e7-96cd-8c76e4115bce.png)
![screenshot from 2018-01-19 17-44-14](https://user-images.githubusercontent.com/13317855/35180670-8ce6ae06-fd69-11e7-9954-9e37b09fa5b9.png)
![screenshot from 2018-01-19 17-44-37](https://user-images.githubusercontent.com/13317855/35180671-8e647cc2-fd69-11e7-98dd-537325b59b11.png)
![screenshot from 2018-01-19 17-45-00](https://user-images.githubusercontent.com/13317855/35180672-8fb8b61a-fd69-11e7-9409-2099badb368f.png)
![screenshot from 2018-01-19 17-45-42](https://user-images.githubusercontent.com/13317855/35180674-91a62ade-fd69-11e7-8249-3ae86091e647.png)
![screenshot from 2018-01-19 17-46-00](https://user-images.githubusercontent.com/13317855/35180675-9327b9a4-fd69-11e7-8d37-52230ae1b29c.png)
![screenshot from 2018-01-19 17-46-18](https://user-images.githubusercontent.com/13317855/35180676-9548b346-fd69-11e7-9e1a-47213be71ff2.png)
![screenshot from 2018-01-19 17-46-59](https://user-images.githubusercontent.com/13317855/35180677-96bb6a20-fd69-11e7-84e2-0743999038fa.png)
![screenshot from 2018-01-19 17-47-13](https://user-images.githubusercontent.com/13317855/35180678-98358c00-fd69-11e7-9e8b-94d7276f57a7.png)
![screenshot from 2018-01-19 17-48-09](https://user-images.githubusercontent.com/13317855/35180680-9a3e2282-fd69-11e7-90be-f57db5166d1d.png)
![screenshot from 2018-01-19 17-48-22](https://user-images.githubusercontent.com/13317855/35180682-9b9656ea-fd69-11e7-967b-e42aa82a9d66.png)
![screenshot from 2018-01-19 17-51-56](https://user-images.githubusercontent.com/13317855/35180683-9cf9885e-fd69-11e7-9fba-0a57e43b8529.png)
![screenshot from 2018-01-19 17-53-39](https://user-images.githubusercontent.com/13317855/35180684-9eee90f0-fd69-11e7-9363-8e9262fa4371.png)
![screenshot from 2018-01-19 17-54-38](https://user-images.githubusercontent.com/13317855/35180685-a139d0c2-fd69-11e7-811e-4f6c8ffbeb6a.png)
![screenshot from 2018-01-19 17-55-55](https://user-images.githubusercontent.com/13317855/35180686-a35d87c2-fd69-11e7-9cdb-c8e9449c9736.png)
