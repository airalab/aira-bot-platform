# AiraEthBot Documentation

## Getting the Bot

Go to the link [@AiraEthBot](http://www.telegram.me/airaethbot). Click "Send message" and allow browser to open link in Telegram. 

## Commands

* `/start` - creates your personal ID and Ethereum account. Sends 1 Air to your new account. Second and next calls show your ID
* `/help` - output the list of all commands with a brief description
* `/me` - returns a link to your Ethereum account
* `/id` - returns your ID
* `/send` - sends ether from your account to another one. You should enter a recipient address and amount of ether
* `/transfer` - transfers ether, air or erc20 tokens to Ethereum or Telegram account
* `/newtoken` - creates new ERC20 token, ERC20 token with emission or vault contract
* `/balance` - returns your ETH, Air or ERC20 balance
* `/watch` - subscribes you to account transactions
* `/unwatch` - unsubscribes from account transactions
* `/cancel` - cancels command execution

## How to create a new ERC20 token

AiraEthBot is capable of create ERC20 tokens, ERC20 tokens with emission and vault contract to store ether.
To create a ERC20 token follow these steps:

1. Call `/newtoken`
2. Pick `ERC20 token` or `ERC20 token with emission`
3. Enter a name for token (e.g. Ethereum)
4. Enter a symbol for token, usually 2-3 letters (e.g. ETH)
5. Enter amount of digitals after a decimal point (0 for integer)
6. Enter amount of tokens to be created

If there're no errors and your balance allows to make transactions, the bot returns an address of your new ERC20 token.

> Notice. For example you'd like to create 1000 tokens with 2 decimal places. In this case you should enter 2 at 5th step and 100000 at 6th
