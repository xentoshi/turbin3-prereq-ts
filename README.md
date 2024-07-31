# turbin3-prereq-rs

This repository contains simple Solana program for the [Turbin3](https://turbin3.com/)  bootcamp in Typescript.

**Network:** Solana Devnet.

## Getting Started

These instructions will give you a copy of the project up and running on
your local machine for development and testing purposes. 

### Prerequisites

Requirements for the software and other tools to build, test and push 
- [NodeJS](https://nodejs.org/en/download/package-manager)
- [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable)

### Installing

A step by step series of examples that tell you how to get a development
environment running

Clone the repository:

    git clone https://github.com/xentoshi/turbin3-prereq-ts.git

Install dependencies:

    yarn install

 or
 
    npm install

Generate a keypair: 

    solana-keygen new

Run: 

    yarn <file name>

✅ Make sure you have keypair stored in the `dev-wallet.json` file in byte array format after generating a new keypair. There are tests available in `lib.rs` for you to safely convert from base58 to byte array if needed. 

## Running the tests

Tests are located in `lib.rs`.You can run the tests by clicking on "Run Tests" above the `tests` module in your editor. 

Available tests are:
- Convert from base58 to byte array,
- Convert from byte array to base58,
- Create a new keypair,
- Airdrop,
- Transfer SOL,
- Empty wallet,
- Register for WBA Cohort (This test will fail).

## Authors

  - [Turbin3](https://turbin3.com/) 

Contributions welcome, for anything related to this repo, contact [xentoshi](https://x.com/xentoshi)
