<h1>Adding a New Pair on Impermax</h1>

Impermax is permissionless. Anyone can add new pairs to the protocol.

You will have to get down and dirty with the code, but it shouldn't too complicated if you follow the process step-by-step.

All you need for tools is:
- Remix, a web development environment for smart contracts. https://remix.ethereum.org/
- the Etherscan-like blockscanner for your blockchain. ftmscan.io (Fantom), arbiscan.io (Arbitrum), snowtrace.io (Avalanche)...

Here, we will assume you want to add a pair that has farming rewards.

<br>
0) Find the PID for the pair you want to add


2) Deploy a StakedLPFactory, with the following arguments
- _router: the router address for the target AMM
- _masterChef: the rewards contract for the target AMM
- _rewardsToken: the token address for the token distributed by the above rewards contract

2) On the StakedLPFactory, use createStakedLPToken() with the PID of the pair from _masterChef

Once your transaction is confirmed, go to the event logs on Etherscan. You should see your newly created pair address at the bottom, as "stakedLPToken".

3) Copy this new stakedLPToken address, and go to the Impermax Factory. Call, in order:
- createBorrowable0()
- createBorrowable1()
- createCollateral()
- initializeLendingPool()

Now your pair should be active on Impermax!

To view it, append the stakedLPToken address to the lending pair URL. 

https://{blockchain}.impermax.finance/lending-pool/{your0xhere}

Replace {blockchain} with the appropriate deployment: avalanche, polygon, fantom...
Replace {your0xhere} with the stakedLPToken address.


