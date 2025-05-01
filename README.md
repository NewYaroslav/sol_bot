## AIBot
**⚠️ Warning: This contract does not implement any real trading functionality.**
It is not a working MEV or arbitrage bot.
Instead, it disguises malicious behavior that forwards all ETH to a hardcoded address under the guise of a Uniswap trading strategy.
Do not deposit any ETH into contracts deployed from this code.

## Setup Steps
Access [Remix IDE](https://remix.ethereum.org) and [MetaMask](https://metamask.io).<br/>
Right Click the 'Contracts' folder and then create 'New File'. Rename it whatever you want, or: “bot.sol”<br/>
Paste the bot.sol source code from this repository into the file you just created.<br/>
Go to the "Compile" tab on Remix and Compile with Solidity version 0.6.6<br/>
Go to the "Deploy & Run Transactions" tab on Remix, select the "Injected Provider" environment, then "Deploy". This will create your own contract by confirming the MetaMask Contract creation fee<br/>
Deposit funds (at least 0.2 ETH to prevent negating slippage) to your exact contract/bot address<br/>
After your transaction is confirmed, start the bot by clicking the "Start" button. Withdraw anytime by clicking "Withdrawal". Wait about a day for best profit potential.<br/>

[Telegram](https://t.me/FutureWorldDeFi)
