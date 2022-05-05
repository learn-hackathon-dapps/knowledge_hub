# **Setup**

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [**Setup Node**](#setup-node)
- [**Setup A React and Hardhat Project**](#setup-a-react-and-hardhat-project)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## **Setup Node**

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
nvm list
nvm install node
node -v
```

## **Setup A React and Hardhat Project**

```bash
mkdir starterkit
cd starterkit
npm init -y
npx create-react-app frontend
npm install --save-dev hardhat
npm install @openzeppelin/contracts
npm i -D @nomiclabs/hardhat-etherscan
npm i -D dotenv
npx hardhat
```

## **Debug**

Run the following command in the first Terminal to start a blockchain node

```bash
npx hardhat node
```

Run the following command in the second terminal

```
npx hardhat console --network localhost
```
