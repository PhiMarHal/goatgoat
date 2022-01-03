<h1>Frequently Asked Questions</h1>

This is a list of common questions about Impermax, and answers.

If you have any other question you'd like to see here, feel free to ping me on the Impermax Discord: @PhiMarHal#9107 

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

