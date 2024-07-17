# CryptoSwap Project

07-17-24

--->>
On Sepolia Test net A trading Pool for 2 token pairs (no need for DEX address, address of the Pool is what we need to swap on Sepolia. In real world we'll need DEX address as well...)


==== PAIRS to SWAP(or trade) Pool addresses of the pair (needed as input for contract on Sepolia Testnet Uniswap V3 ====


SQZ/WETH
0xe08c0a18d4bDcA36599736a2B5E94f915fBD3D1B

BBLAND/WETH
0xd90b588c829ae4a0d3a9dd0e91fa97a8b6b6f410

ARBEX/WETH
0x2f8b660e8e2cf66889862d4ab1569cde98d67748

---- This one has low trades --- not good for arbitrage (use the ones above or, go to this site and pick the one you need:
Good for testing swap... 
TEST/WETH
0x97bd10279eef8bd54fd21bca3d5a1e88f91c2f08
-----------------


TERMINAL for Sepolia test net:
https://www.geckoterminal.com/sepolia-testnet/uniswap-v3-sepolia-testnet/pools

Create uniswapv3 Sepolia wallet:

!!! IMPORTANT 
On Uniswap Sepolia
https://app.uniswap.org/

After connecting the wallet, I can SWAP ETH(Sepolia ETH) to WETH !!!! WE need WETH (WrappedETH) to do other swaps on Sepolia net
Also, installed Uniswap extension in Chrome and created new Uniswap wallet...

Let's see if swap from SepoliaETH(ETH) to WETH works... IT WORKED.
But, as always not very straightforward. So, after executing and confirming a swap on uniswap site/app and receiving transaction hash
I followed it to Sepolia.etherscan.io to see the flow of the token.

And there it was my WETH and it was tied to the account 0xfFf9976782d46CC05630D1f6eBAb18b2324d6B14

Then I went to Metamask wallet and hit "Import Tokens", entered this address and itpopulated the ammount and confirm button appeared. Hit proceed.
And .. viola, I see the WETH token in my MetaMask wallet on test Sepolia network. Now, we can try to buy or swap/trade another crypto from UNiswap and 
see if it shows up in the wallet. Get a few cryptos. Follow the route, collect address after looking an sepolia.etherscan.io on transaction hash.

Then we can build a smart contract to auto swap those tokens at profit. Some of the above pairs/Pools are going up and down, which is good for testing.

Now, lets go to SushiSWAP and connect the wallet, see if it works... it didn't work as expected, but here's a crypto and pair to trade:



OK, lets see how to swap WETH for PEX ()both on Sepolia)

PEX address:
0x7b522bA8C126716bf7c9E5f92951aCae38a680d6

WETH address:
0x7b79995e5f793a07bc00c21412e50ecae098e7f9


PEX/WETH Pool address:
0x5a7e56e8bcd2f29edc08cd672d92f460ddf4d082

1. Swap WETH for PEX on Sepolia ... In Progress
