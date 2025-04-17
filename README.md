# Onchain Agent

An AI-powered blockchain agent that can interact with the Abstract Testnet blockchain. Built with OpenAI's Assistant API and viem.

## Features

- Powered by openai Api
- interaction with blockchain with [Viem](https://viem.sh/)
- Support for:
  - ERC20 token deployments and interactions
  - Contract reading and writing
  - Balance checking
  - Transaction management
  - Uniswap V3 pool creation

## Prerequisites
- An OpenAI API key
- A wallet private key for the agent

## Getting Started

1. clone the repository

2. Install dependencies:

```bash
npm install
```

3. Create the `.env` file and add your OpenAI API key and wallet private key:

```bash
OPENAI_API_KEY=your_openai_api_key
PRIVATE_KEY=your_wallet_private_key
```

4. Run the agent:

```bash
npm start
```
