# ESCAPE HATCHES

Impermax is a decentralized protocol. Your funds are always in your control.

What happens if the website is down? 
The protocol keeps working. 
You can always access everything, through the smart contracts.

Following is a guide to get tokens back from lending, if the UI is down. 
This example uses Polygon, but the same steps will work on any Impermax deployment.
The official Discord (https://discord.gg/XN739EgG4X) has all the appropriate contract addresses in its resources channel.

**How to Redeem tokens supplied on Impermax**

### STEP 1: get the lending pool address

Open your address in Polygonscan. 
In the "Token" dropdown menu, search for "imxB"
Click on the imxB token. This will open a link with its contract address, as well as your imxB balance.

### STEP 2: give the Impermax Router an approval for your imxB token

On the imxB Polygonscan page you just opened, go to the "Contract" tab, then the "Write Contract" tab.
Scroll down to "8. approve".

Input the following arguments:

spender       = address of the Impermax Router: 0x7c79a1c2152665273ebd50e9e88d92a887a83ba0
value         = a very large number (24+ figures recommended). For example: 999999999999999999999999999999

Click on Write, and send the transaction through your wallet.

### STEP 3: withdraw your tokens from the router

Go to the Polygonscan page for the Impermax Router: https://polygonscan.com/address/0x7c79a1c2152665273ebd50e9e88d92a887a83ba0#writeContract
In the "Write Contract" tab, scroll down to "12. redeem"

Input the following arguments:

poolToken       = address of your lending pool / imxB token 
tokens          = your balance of imxB tokens, minus the decimal point (if you have a balance of 1.969173950467165445 imxB, input 1969173950467165445)
to              = your own address 
deadline        = any large number above 2000000000 should work (unix time)
permit          = 0x

Click on Write, and send the transaction through your wallet.

You're done! Your original tokens should be back in your wallet, with accrued interest, as soon as the transaction confirms.
