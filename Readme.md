# Project Details

This project was made by Stiff Roy for his Udacity Blockchain Developer ND program.

## Package versions:
Truffle v5.1.19 (core: 5.1.19)

OpenZeppelin v2.1.2

Solidity v0.5.16 (solc-js)

Node v10.19.0

Web3.js v1.2.1

## ERC-721 details:
**Token Name**: CryptoStar Token

**Token Symbol**: STR

**Token Address**: [0x6754dEb3D7bF3C8503159BF85608d13000A06e38](https://rinkeby.etherscan.io/address/0x6754deb3d7bf3c8503159bf85608d13000a06e38)

## GitHub details:

Github project URL: [https://github.com/stiffroy/crypto-star-daap](https://github.com/stiffroy/crypto-star-daap)

_Note_: Builds are not a part of the git files, so you have to re-compile and migrate the contracts .

## How to run

To run the project effectively, one should do the following
1. Clone the repository to his local machine
2. Check node is installed by typing ```node -v``` in the terminal. (Please note, to run the truffle tests properly, you need to have node version < 11)
3. Check that truffle is installed by typing ```truffle -v ``` otherwise install it with ```npm install -g truffle``` in the terminal
4. Check into the cloned directory by typing ```cd crypto-star-daap``` in the terminal
5. Compile and migrate the contracts: 
⋅⋅⋅ either by executing ```truffle compile && truffle migrate --reset```
... or by going into the truffle console by typing ```truffle develop``` and then executing ```compile``` and ```migrate --reset```
6. Now on another terminal, go to the app directory inside the project directory as ```cd app``` and execute ```npm run dev```.
7. Keep this terminal open and go to the url provided by the previous command (it should be mostly [http://localhost:8080](http://localhost:8080)) to check the Daap