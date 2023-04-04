# Mint Your Own NFT and View it in Metamask

This project demonstrates how to mint your own NFT (Non-Fungible Token) using the OpenZeppelin ERC721 contract and how to view it in your Metamask wallet. By following the instructions below, you'll be able to create your own NFT and see it in your Metamask wallet.

## Getting Started

To get started with this project, follow these steps:

1. Install the required dependencies by running the following command:

`npm install`

2. Configure the `truffle-config.js` file to connect to your local or remote Ethereum network. You can configure your development network settings in the file. 

3. Create a new NFT by running the following command:

`npm start`

This will start the web application, and you should see a button labeled "Mint NFT" on the page.

5. Click the "Mint NFT" button to create a new NFT. You'll be prompted to connect to your Metamask wallet and pay the gas fees required to mint the NFT.

6. After you've minted the NFT, you should see it on the page along with its unique token ID.

7. To view the NFT in your Metamask wallet, open your wallet and add a new custom token with the following details:

* Token Contract Address: the address of the ERC721 smart contract that you deployed in step 3
* Token Symbol: the symbol that you specified in the ERC721 contract
* Decimals: 0

Once you've added the custom token, you should see your NFT in your wallet along with its name and symbol.

## Contributing

If you would like to contribute to this project, please open a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).
