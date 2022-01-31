# Adalo custom component Near-View-NFT for Near Protocol
This is an example of Adalo custom component that allows you to call view method to contract and get collection using the Near blockchain in the Adalo platform.

## Simple demo

[Example NFT](https://previewer.adalo.com/99c92caa-08b9-48a8-a742-d1ee558ce09c)

## Install

1. Code instructions
  - clone repo
  - set your own name and version of Component in package.json
  - install dependencies
    - `yarn`
  - login to Adalo cli
    - `npx adalo login`
  - run dev or prod mod
    - `npx adalo dev` or `npx adalo publish`

2. Adalo instructions
- Enable the developer mode in your Adalo profile
- Refresh page
- Find and add your Component library in Profile/Developers/Libraries
- Enjoy

## Usage

### If you have never before use Near blockchain you can learn it here [Near Education](https://near.org/ru/education/)

1. Create a smart contract using Rust or AssemblyScript or get an example contract from [Near Examples](https://examples.near.org/)
2. Build & deploy it with your own account.
3. You need to connect Adalo to contract - you can use my base component [Near Connection](https://github.com/Ellweb3/near-button).
4. Now you can set view method.
5. Fill free to customize it for your contract

## Addition components
1. [Near Connection](https://github.com/Ellweb3/near-button)
2. [Near submit button](https://github.com/Ellweb3/near-submit-button)
3. [Near status](https://github.com/Ellweb3/near-status)
