# Proveable Random Raffle Contracts

## About

This code is to create a proveable random smart contract lottery.

## What will it do?

1. Userc can enter by paying for a ticket
   1. The ticket fees are going to go to the winner during the draw.
2. After X period of time, the lottery will automatically draw a winner.
   1. This will be done programmatically.
3. Using Chainlink VRF & Chainlink automation
   1. Chainlink VRF -> Randomness
   2. Chainlink Automation -> Time based trigger

## Tests!

1. Write some deploy scripts
2. Write our tests
   1. Work on a locak chain.
   2. Forked Testnet
   3. Forked Mainnet