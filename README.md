# Bank DAPP

A simple Dapp to store and withdraw ETH. Connect through metemask wallet with Rinkeby network to test the functionality.

## [Live Preview:](https://Bank-Dapp.janus9.repl.co)

<p align="center">
<img src="https://user-images.githubusercontent.com/62827213/179518260-f14726b8-a6d9-40e5-ae55-b1451ea815f0.PNG" width=60% height=30%>
</p>
<p align="center">
    <em>Dapp Landing Page</em>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/62827213/179518611-3277db4b-c8c8-4ebe-9f17-a04e398da473.PNG" width=60% height=30%>
</p>
<p align="center">
    <em>After Connecting Wallet</em>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/62827213/179518690-6282a4ae-8922-429d-b1c4-cf77717f4819.PNG" width=60% height=30%>
</p>
<p align="center">
    <em>After Setting Bank Name</em>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/62827213/179518804-c3be9e58-2d8a-4009-b954-c2de785ab179.PNG" width=60% height=30%>
</p>
<p align="center">
    <em>After Deposited ETH</em>
</p>

## Project Setup
```
npm init -y
npm install --save-dev hardhat
npm hardhat
```
### HardHat Environment
Compiling Smart Contract
```
npx hardhat compile
```
Deploying to your local Hardhat Blockchain
1. Start a Hardhat Node
   ```
   npx hardhat node
   ```
2. Deploy Smart Contract in `localhost` or `rinkeby` network
    ```
    npx hardhat run --network localhost scripts/deploy.js
    ```
    ```
    npx hardhat run --network rinkeby scripts/deploy.js
    ```

