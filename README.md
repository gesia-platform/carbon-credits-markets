# VoucherMarket Smart Contract

## 📖 Overview

The VoucherMarket Smart Contract is an advanced blockchain-based marketplace for trading voucher tokens. Deployed on the Gesia network, it allows users to buy and sell vouchers in a decentralized and secure environment. This contract integrates with multiple external interfaces and utilities like Chainlink and OpenZeppelin libraries.

## ✨ Features

Place and Unplace Tokens (Public): Users can place their voucher tokens for sale or remove them from the marketplace.

Purchase Tokens with USDT (Public): Enables buying voucher tokens using USDT.

Operator and Whitelist Management: Only verified operators can manage voucher contracts, ensuring security and integrity.

```
Functions include:

- place()
- unPlace()
- purchaseInUSDT()
- verifyVoucherContract()
- unVerifyVoucherContract()
```

## 🚀 Smart Contract Deployment Information

VoucherMarket has been deployed on Gesia network. Here are the deployment details:

Contract Address: [0xd22C96D762B22721f22c0489aB56083C894f46b8](https://explorer.gesia.io/address/0xd22C96D762B22721f22c0489aB56083C894f46b8)

Transaction Hash: [0xa7625c462b576cd08b466ac7d50f87d053f4da86ca317a4a208afa98572ed6ec](https://explorer.gesia.io/tx/0xa7625c462b576cd08b466ac7d50f87d053f4da86ca317a4a208afa98572ed6ec)

You can verify the deployment by checking the contract address and transaction hash on [Gesiascan](https://explorer.gesia.io/)

## 📝 How it Works?

Placing Tokens: Users place their voucher tokens on the marketplace, setting the price per token.

Unplacing Tokens: Users can remove their tokens from the sale.

Purchasing Tokens: Buyers can purchase tokens using USDT. The contract handles fee deduction and transfer of tokens.

## 🛠️ Integrations

OpenZeppelin Libraries: SafeMath, SafeERC20, Counters, ERC1155Holder, etc.

Chainlink Client: For external data feeds.

Interfaces: IOperator, IWhitelist, IFeeManager, IPrice.

# DerivativeTokenMarket Smart Contract

## 📖 Overview

The DerivativeTokenMarket Smart Contract is a sophisticated blockchain-based platform for trading Derivative Tokens. Deployed on the Gesia network, this contract facilitates the buying and selling of Derivative Tokens in a secure and decentralized environment. It integrates with external interfaces and uses libraries such as OpenZeppelin for robust contract functionalities.

## ✨ Features

Place and Unplace Tokens (Public): Users can list their Derivative Tokens for sale or remove them from the market.

Purchase Tokens with USDT (Public): Facilitates the purchase of Derivative Tokens using USDT.

Operator and Whitelist Management: Ensures that only verified operators can manage Derivative Token contracts, enhancing security and integrity.

```
Core Functions:
- place()
- unPlace()
- purchaseInUSDT()
- verifyDerivativeTokenContract()
- unVerifyDerivativeTokenContract()
```

## 🚀 Smart Contract Deployment Information

DerivativeTokenMarket has been successfully deployed on the Gesia network. The deployment details are as follows:

Contract Address: [0xFEC2E8307E580FC77e3dF5D4a40816Ff11B05E30](https://explorer.gesia.io/address/0xFEC2E8307E580FC77e3dF5D4a40816Ff11B05E30)

Transaction Hash: [0x1bf700b13aeccf6c78b7fe1df3be9aedf91253ad6c312939023b737dbd407e8d](https://explorer.gesia.io/tx/0x1bf700b13aeccf6c78b7fe1df3be9aedf91253ad6c312939023b737dbd407e8d)

Verify the deployment by checking the contract address and transaction hash on [Gesiascan](https://explorer.gesia.io/)

## 📝 How It Works?

Placing Tokens: Sellers list their DerivativeTokens on the market, specifying the price for each token.

Unplacing Tokens: Sellers can withdraw their DerivativeTokens from the market.

Purchasing Tokens: Buyers can acquire DerivativeTokens using USDT. The contract manages fee calculations and token transfers.

## 🛠️ Integrations

OpenZeppelin Libraries: For secure smart contract development.

Chainlink Client: Utilized for reliable external data feeds.

Interfaces Used: IOperator, IWhitelist, IFeeManager, IPrice.

# MMarket Smart Contract

## 📖 Overview

The MMarket Smart Contract is a blockchain-based marketplace for trading voucher DerivativeTokens. Deployed on the Gesia network, it enables users to buy and sell voucher DerivativeTokens in a secure and decentralized environment. The contract incorporates several external interfaces and uses OpenZeppelin libraries to ensure robust functionalities.

## ✨ Features

Token Placement and Removal (Public): Users can list their voucher DerivativeTokens for sale or remove them from the marketplace.

Transfer By Operator (Operator Only): This function allows operators to transfer tokens under specific conditions, ensuring controlled and secure transactions.

Voucher DerivativeToken Contract Verification: Ensures that only verified voucher DerivativeToken contracts are tradable, enhancing the marketplace's integrity.

```
Key Functions:
- place()
- unPlace()
- transferByOperator()
- verifyVoucherDerivativeTokenContract()
- unVerifyVoucherDerivativeTokenContract()
```

## 🚀 Smart Contract Deployment Information

MMarket has been deployed on the Gesia network. The deployment details are as follows:

Contract Address: [0xBB4E347aA8B9c2Ef9101e10F0340e60E14232415](https://explorer.gesia.io/address/0xBB4E347aA8B9c2Ef9101e10F0340e60E14232415)

Transaction Hash: [0x2d0fc1b124381eff0747d362438b34cfa5baa5ad83c6c6c0927840668e169972](https://explorer.gesia.io/tx/0x2d0fc1b124381eff0747d362438b34cfa5baa5ad83c6c6c0927840668e169972)

Verify the deployment by checking the contract address and transaction hash on [Gesiascan](https://explorer.gesia.io/)

## 📝 How It Works?

Placing Tokens: Sellers list their voucher DerivativeTokens on the market, setting a price.

Unplacing Tokens: Sellers can remove their DerivativeTokens from the sale.

Operator Transfers: Operators can transfer tokens to a specified receiver based on verified conditions.

## 🛠️ Integrations

OpenZeppelin Libraries: For secure and efficient smart contract development.

Interfaces Used: IOperator, IFeeManager.

## 📄 License

This project is unlicensed. It's free for use and modification without any restrictions.
