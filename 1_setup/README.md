# **Setup**

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [**Node**](#node)
- [**Setup React and Hardhat**](#setup-react-and-hardhat)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## **Node**

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
npx hardhat
```
