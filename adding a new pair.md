<h1>Adding a New Pair on Impermax</h1>


1) Deploy a StakedLPFactory, with the following arguments
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

https://{blockchain}.impermax.finance/lending-pool/ <- paste the "0x..." right here


