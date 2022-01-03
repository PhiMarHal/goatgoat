<h1>Frequently Asked Questions</h1>

This is a list of common questions about Impermax, and answers.

If you wonder about anything else you'd like to see here, feel free to ping me on the Impermax Discord: @PhiMarHal#9107 

<br>
<h3>Where can I use Impermax?</h3>

Impermax is available on Ethereum, Polygon, Arbitrum, Avalanche and Moonriver.

<br>
<h3>Where should I get the latest info on Impermax?</h3>

The Discord server is fairly active, and the #resources channel in particular will have most of the links you might need.

<br>
<h3>Where can I trade IMX?</h3>

You can trade IMX on decentralized exchanges.

Uniswap pair (Ethereum): https://v2.info.uniswap.org/pair/0xa00d47b4b304792eb07b09233467b690db847c91
QuickSwap pair (Polygon): https://info.quickswap.exchange/#/pair/0x5f819f510ca9b1469e6a3ffe4ecd7f0c1126f8f5
SushiSwap pair (Arbitrum): https://analytics-arbitrum.sushi.com/pairs/0xb7e5e74b52b9ada1042594cfd8abbdee506cc6c5
Swapr pair (Arbitrum): https://dxstats.eth.link/#/pair/0x9da6ce1f3e25843e7a3fbd262fd8082b8f562923
Pangolin pair (Avalanche): https://info.pangolin.exchange/#/pair/0xa34862a7de51a0e1aee6d3912c3767594390586d
Solarbeam pair (Moonriver): https://analytics.solarbeam.io/pairs/0x6ed3bc66dfcc5ac05daec840a75836da935fac97

<br>
<h3>What is the recommended wallet for Impermax?</h3>

Currently, Metamask on desktop has the best support.

<br>
<h3>How long has Impermax been around?</h3>

The ancient scrolls claim it has been around for longer than mankind itself. Etherscan says March 2021.

<br>
<h3>How safe is Impermax?</h3>

The protocol has secured more than $40M of TVL for 9 months on 5 chains with no bugs or hacks.

Additionally, a large bug bounty program (or "unofficial fork") has been running on the Fantom blockchain since August.

<br>
<h3>How do I lend?</h3>

Open any pair using the asset you want to lend, and click on the "Lending" tab.

<br>
<h3>What rewards do I get if I lend?</h3>

You get rewards in the same token you lend. These rewards are added to your supplied balance (they autocompound).

<br>
<h3>How often do I get rewards for lending?</h3>

Interest adds up with every block. However, your balance won't update dynamically. A refresh every few minutes should show you your increased balance.

<br>
<h3>Can I see my lending gains anywhere?</h3>

Not directly through the website yet.

Instead, you can track your original deposit from a block explorer, then subtract it to your current supplied balance.

<br>
<h3>Can I lose funds by lending?</h3>

Only in the rare scenario bots would not liquidate an undercollateralized loan in time. This has never happened in the entire history of Impermax.

<br>
<h3>[Mobile Wallet] I can't withdraw, the wheel keeps spinning and nothing happens</h3>

This is a known bug with some mobile wallets. Your best bet is to import your mobile wallet seed in Metamask.

<br>
<h3>My wallet is connected, but I can't see my funds anymore!</h3>

Make sure you're connected with the right wallet, if you use several ones.

Try a hard refresh: CTRL-F5.

If nothing shows up, it may be an issue with the subgraph. Check in on Discord to see if others have the same problem.

<br>
<h3>What is the Bounty?</h3>

The Bounty reinvests external rewards into more of the underlying LPs. It compounds collateral for all LPs deposited on Impermax.

Whoever calls the Bounty gets 2% of those farming rewards for their work. In practice, bots tend to claim the Bounty as soon as it's economically viable. You can ignore the Bounty and treat it as an autocompounder.

<br>
<h3>How can I get involved with IMX staking?</h3>

The staking contract is on Ethereum mainnet. It lets you deposit IMX and get xIMX in return.

If Ethereum fees are too high, you can buy xIMX on Polygon through the Uniswap v3 pair: https://info.uniswap.org/#/polygon/pools/0xcc64b5d5eecd61a237d74e70dbf26e2cb1667d76

<br>
<h3>What's the point of the IMX token?</h3>

IMX can be staked for a share of protocol profits (currently, 100% of protocol profits are sent to stakers).

All holders of IMX also passively benefit from protocol buybacks.

In the future, IMX will serve as a governance token for the protocol.

Holders could vote on new pools and allocations, and be rewarded for their votes, similar to Curve and "Liquidity Direction Rights": https://tokenomicsexplained.com/evolutions-in-liquidity-sourcing


<br>
<h3>How do buybacks work?</h3>

A share of protocol profits is used to buy back IMX on the open market. Buybacks are done manually by the dev team. They happen roughly on a weekly basis.

<br>
<h3>How does staking work?</h3>

Buyback proceeds are sent to the staking distributor. The staking distributor then sends IMX to the staking contract, over a period of 30 days.

As the staking contract receives IMX, it naturally increases the value of xIMX compared to IMX. 

This also means your xIMX tokens on any other chain benefit from staking rewards on Ethereum mainnet.

<br>
<h3>Once I leverage my LP tokens, in what form do I get the rewards?</h3>

You will get a mix of: Trading Fees, External Rewards, and IMX Farming.

Trading Fees and External Rewards autocompound to your LP equity.

IMX Farming accrues in your "Farming" tab.

<br>
<h3>When leveraging, do IMX rewards compound?</h3>

IMX rewards are claimed manually at your convenience. They don't compound.

<br>
<h3>[Moonriver] Do MOVR rewards compound?</h3>

MOVR rewards can be claimed manually just like IMX rewards.

MOVR rewards are also claimed automatically with any action tied to your LP (leverage, deleverage, withdraw, deposit).

<br>
<h3>[Polygon] I'm trying to withdraw, but my transactions won't go through. I have several queued transactions</h3>

The network is likely congested.

On blockchains, transactions work in order.

This means you must find the first transaction that got stuck, then speed it up.

Use a tool like Owlracle to choose your gas price: https://owlracle.info/poly

<br>
<h3>[Polygon] I'm having issues with getting Polygon to load correctly. Other networks are fine.</h3>

Changing the default RPC may help. polygon-rpc.com is a good one.

To change your RPC, go to Metamask -> Settings -> Networks. Pick Matic.

Then, replace "New RPC URL" with https://polygon-rpc.com

<br>
<h3>Are there any fees on deposits?</h3>

There are no fees on deposits or withdrawals.

<br>
<h3>Are there any fees on leveraging?</h3>

On Ethereum, Polygon and Arbitrum, there is a 0.1% upfront fee on leveraging.

This fee is applied per degree of leverage.

If you enter a position with 4x leverage, you will pay 0.1% * (4 - 1) = 0.3% of your capital upfront.

Avalanche and Moonriver have no upfront fee on leveraging.

There are no fees on deleveraging anywhere.

<br>
<h3>Can I use Impermax for my LPs without leveraging?</h3>

Yes! If you deposit LPs without leveraging, Impermax acts as an autocompounder.

<br>
<h3>Why is my LP equity going down, even though the APR is positive?</h3>

There are several factors at play.

It may be that your APR is mostly in IMX rewards. As IMX rewards must be manually claimed, they don't compound to your equity.

It may be that you're suffering from impermanent loss, if the two assets of your pair are moving from each other. Leverage multiplies impermanent loss.

<br>
<h3>What does it mean when the APR is negative?</h3>

When the APR is negative, people who are currently in the pair at that level of leverage are losing money.

<br>
<h3>*Why* is the APR negative?</h3>

Rates are driven by supply and demand. Too many borrowers, too few lenders may result in negative APR.

The price variation between assets can also play a role. If a pair has high farming rewards, but the market value of these rewards lowers, so will APR.

<br>
<h3>Should I deleverage immediately when the APR is negative?</h3>

It depends of your strategy and market outlook. 

You could decide to wait for other borrowers to deleverage before you.

If Supply APR is high, it may attract lenders. Restoring your own leverage APR.

<br>
<h3>I'm trying to deleverage, but only one of my assets was fully deleveraged. What should I do?</h3>

It's likely your debt has become unbalanced due to impermanent loss. You need to repay manually the debt for that asset (assetA), in order to be able to withdraw your LP in full.
 
To do that, you could borrow the other asset (assetB). Then swap assetB for assetA on a decentralized exchange. And repay the assetA debt.

<br>
<h3>I deleveraged, but I'm not seeing my LP anymore!</h3>

If you deleverage in full, Impermax breaks your LP into their original tokens. You should see them in your wallet.

<br>
<h3>If I get liquidated, can my account go negative?</h3>

Liquidation takes 4% per degree of leverage on volatile pairs. 1% on stable/stable pairs.

For example, if you were leveraged 6x at the moment of liquidation, you would lose 4% * (6 - 1) = 20% of your capital.

Note that as liquidation generally happens because your debt grows and your liquidation increases, your leverage at the moment of liquidation is likely to be higher than your initial leverage.

<br>
<h3>I withdrew my assets, but there's still something left.</h3>

This is a known issue: the protocol leaves dust behind. The amount should be too small to matter (but it's admittedly annoying!).

<br>
<h3>Can I transfer my supplied positions to another address?</h3>

Yes. Supplied positions are ERC20 tokens.

You might be able to find your supplied positions by looking at your address in a block explorer. Supplied positions are all named "imxB". 

If you have several positions, clicking on the token, then on the contract address, then on the "tokens" for that contract address, might let you know which imxB corresponds to your position.

<br>
<h3>Can I transfer my leveraged positions to another address?</h3>

Unfortunately, no. Leveraged positions are bound to the address that opened them.
