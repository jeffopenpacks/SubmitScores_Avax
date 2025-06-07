# SubmitScores_Avax
A simple smart contract that stores the scores of a browser pong game on-chain


This repo consists of 2 files
1) pongscore.sol (Smart contract)
2) contract.ts (Frontend)

Note that this code is extracted from a larger web-browser game project and will not work on its own. The smart contract is live on fuji test-net.

The smart contract contains 2 simple functions: 1 to submit scores, and 1 to retrieve. The frontend provides the required struct and calls on the submitScores function. Similarly, when it calls getScores, it then takes the returned values and present it in a human-readable format.
