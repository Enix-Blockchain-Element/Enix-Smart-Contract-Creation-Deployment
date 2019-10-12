# SmartContract
An Overview Guide on Creating/Deploying Smart Contracts on the ENIX Blockchain

The Enix Blockchain itself focuses on distributed computational processing and/or large data transactions, however its core makeup allows the use and easy creation/deployment of smart contracts utilising either Solidity or Vyper which were created for the Ethereum blockchain for familiarity and cross chain requirements.

It is recommended to use the latest version of SOLC to ensure compatibility.

## Solidity Guide
https://solidity.readthedocs.io/en/v0.4.24/introduction-to-smart-contracts.html

In the above url, you can obtain an introduction to smart contracts within the Solidity Framework.

- Also checkout: https://www.baeldung.com/smart-contracts-ethereum-solidity

## Vyper Guide
https://vyper.readthedocs.io/en/v0.1.0-beta.13/

In the above url, you can obtain an introduction to smart contracts within the Solidity Framework.

## Deploy Smart Contract on wallet.enix.ai

Wallet.enix.ai is a re-engineered version of the famous MEW specific to Enix and for familiarity, if you have experience with MEW and deploying smart contracts for ETH, then you should certainly have no issues deploying smart contracts there.

However if you do not have experience this guide will help you.

Deploying an Enix smart contract is an easy task thanks to Wallet’s Deploy Contract interface. All you need to have is the following:

- Byte Code
- ABI/JSON Interface
- Contract Name

![alt text](https://github.com/Enix-Blockchain-Element/SmartContract/blob/master/photo_2562-10-12%2022.03.49.jpeg)
Compiling https://etherscan.io/address/0x167cb3f2446f829eb327344b66e271d1a7efec9a#code as an example for ENIX Blockchain, Gandhiji is a smart contract dapp for ETH https://gandhiji.io

NOTE IMPORTANT: Language components would need to be composed as ethereum/Ethereum, however vars, consts, lets will need to be ENIX or other sub tokenized element.

Once you have those three ready, the first two of which you can get once your smart contract is compiled, you can head over to Wallet https://wallet.enix.ai/#contracts and deploy:

![alt text](https://github.com/Enix-Blockchain-Element/SmartContract/blob/master/photo_2562-10-12%2022.05.36.jpeg)

Resulting in: https://explorer.enix.ai/tx/0x0d24d2ea8272de0182aab3d833f24fcd0a5c927ddc120fb4d70e4ce22d9312fb/internal_transactions

![alt text](https://github.com/Enix-Blockchain-Element/SmartContract/blob/master/Screen%20Shot%202562-10-12%20at%2022.22.14.png) 

A deployed Smart Contract on the Enix Blockchain.

![alt text](https://github.com/Enix-Blockchain-Element/SmartContract/blob/master/Screen%20Shot%202562-10-12%20at%2022.22.41.png)

Interacting with the created contract is seamless.

![alt text](https://github.com/Enix-Blockchain-Element/SmartContract/blob/master/Screen%20Shot%202562-10-12%20at%2022.28.21.png)

![alt text](https://github.com/Enix-Blockchain-Element/SmartContract/blob/master/Screen%20Shot%202562-10-12%20at%2022.30.25.png)

## Other potential tools.

- Ethfiddle.com

Check compiled / security issues.

![alt text](https://github.com/Enix-Blockchain-Element/SmartContract/blob/master/Screen%20Shot%202562-10-12%20at%2022.18.34.png)
