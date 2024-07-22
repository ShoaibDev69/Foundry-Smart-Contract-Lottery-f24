# Proveably Random Raffle Contracts

# About 

Thi code is to create a proveably random smart contract lottery.

# What we want it to do ?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to go to the winner during the dra
2. After X period of time, the lottery will automatically draw a winner
   1. And this will be done programmatically
3. Using Chainlink VRF & Chainlink Automation
   1. Chainlink VRF - > Randomness
   2. Chainlink Automation - > Time Based Trigger

# Tests 

1. Write deploy script
   1. This will not work on zkSync
2. Write tests 
   1. Local Chain
   2. Forked Testnet 
   3. Forked Mainnet