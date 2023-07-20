slacccCoin TOKEN CONTRACT

THIS IS A SIMPLE TOKEN CONTRACT WRITTEN IN SOLIDITY

## Description

THE slacccCoin CONTRACT CAN BE DEPLOYED USING REMIX
ONCE DEPLOYED EVERY ADDRESS ON THE BLOCKCHAIN HAS A TOKEN BALANCE
TOKEN BALANCE OF ANY ADDRESS IS INITIALIZED TO 0
TOTAL SUPPLY IS ALSO INITIALIZED TO 0
THE BALANCE OF ANY ADDRESS CAN BE INCREASED USING THE MINT FUNCTION
THE BALANCE OF ANY ADDRESS CAN BE DECREASED USING THE BURN FUNCTION
TOKENS CANNOT BE TRANSFERRED

## Getting Started

CREATE A FILE NAMED slacccCoin.sol IN THE REMIX IDE
COPY AND PASTE THE CODE IN slacccCoin.sol INTO THE FILE IN THE REMIX IDE
COMPILE THE CONTRACT slacccCoin IN  slacccCoin.sol

### Installing

* YOU CAN DEPLOY THE CODE TO ANY BLOCKCHAIN
* YOU CAN ALSO DEPLOY TO THE REMIX VM
* DEPLOY WITHIN THE REMIX IDE
* THE REMIX IDE WILL PROVIDE AN INTERFACE FOR INTERACTING WITH THE CONTRACT

### Executing program

WITHIN THE REMIX IDE AFTER DEPLOYING ARE SIX FUNCTIONS
HERE IS AN OVERVIEW OF HOW TO USE THOSE FUNCTIONS

| FUNCTION | INPUTS | OUTPUTS | EFFECTS|
|----------|--------|---------|--------|
| balances | address | token balance for the given address| none|
|tokenName| none | 'slacccCoin' | none |
|tokenAbrrv| none | 'SC'| none |
| total Supply | none | total number of slacccCoins in existence at any moment | none
|mint| address, amount| none | creates new tokens into the provided address, the amount created is specified as input|
|burn| address, amount| string (indicating success for failure)| destroys tokens belonging to the provided address given that it has the amount specified|




## Help

PROBLEMS WITH THE CONTRACT

    IT DOESN'T FIT THE ERC20 TOKEN STANDARD
    ANYONE CAN CREATE TOKENS
    ANYONE CAN DESTROY ANYONE ELSE'S TOKENS
    TOKENS CANNOT BE TRANSFERRED

## Authors
THIS CODE WAS WRITTEN BY SPACHITO (DISCORD- spachito)

## License

This project is licensed under the MIT License