# Add Liquidity

Adding liquidity allows the contributor to earn 0.2% swapping fees from the pairs they've provided. Your liquidity can earn even more rewards (PNEs) if they're staked at farms!

When you've provided liquidity, you will receive psLP tokens (PennySwap Liquidity Provider tokens) as proof of contribution. For example, if a user deposited $PNE and $SYS into a pool they would receive PNE-SYS spLP tokens. These tokens represent a proportional share of the pooled assets.

These psLP tokens can be staked at farms to earn PNE.

---

## How a pool accrues value from fees

If at the time of a trade, there are 100 psLP tokens representing 100 PNE and 100 SYS, each psLP token would be worth 1 PNE and 1 SYS. 

If one user trades 10 SYS for 10 PNE, and another traded 10 PNE for 10 SYS, then there would now be 100.02 PNE and 100.025 SYS in the pool.

This means each LP token would be worth 1.00025 SYS and 1.00025 PNE when it is withdrawn.


**Adding liquidity to an existing pool**

You need to provide tokens in a 1:1 value ratio to the liquidity pool. This means that if you are adding to, say, a PNE-SYS pool, and wish to provide 2000 SYS worth of liquidity, you would need to convert approx 1000 SYS to an equal value of PNE tokens first via our Swap.

**Adding liquidity to a new pool**

If the pool you wish to provide liquidity to does not exist, you can create it of course! Just provide the tokens and off you go. As the first liquidity provider, you set the initial exchange ratio (price) if one of the tokens in the pair does not exist yet on PennySwap. This often quickly corrects itself through arbitrage and by more liquidity providers adding to the pool.

---

## How to add liquidity

By adding liquidity, you are putting equal USD value of 2 ingredients to make LP tokens. 
Here's how to do it:

**Requirements**

* MetaMask wallet
* Some (less than 1 cent) SYS for gas 

**Steps**

1. Connect your wallet, make sure that it is on Syscoin Mainnet.
2. Go to Liquidity - Add
3. Next, click "Select" to choose which tokens you'd like to add. 
4. Choose a token from the list. If it is not on the list, you can search for its address and add it to the list
5. Select the second token
6. Enter the amount you'd like, you can also click on "MAX" to max out. The other ingredient amount will automatically adjust to the same value in USD.
7. When you're happy with the amount, click "Supply" and your wallet will ask you to confirm. 

    If this is your first time making LP tokens with the ingredients, click "Approve" for both tokens. This may take a few minutes to update from your wallet. Click "Confirm" after it becomes enabled.
8. When your "Confirm" request has been sent to Sysscan, popup message will show up. You can check the link to Sysscan for its progress but this usually takes few minutes. 

9. You can check that your liquidity has been absolutely made by going to "Remove" and manage them.  Though staked tokens will not display here at the moment.


Voilà! You have made your liquidity and are on your way to earning fees!


Want to earn more with your liquidity? See the next section, Yield Farming for how to stake those psLP tokens to earn PNEs!

---

## Impermanent Loss

Impermanent Loss (aka IL) is one of the risks you take on for being a liquidity provider and is a result of how AMMs function. Here are two articles to better explain it:

https://pintail.medium.com/understanding-uniswap-returns-cc593f3499ef

https://blog.bancor.network/beginners-guide-to-getting-rekt-by-impermanent-loss-7c9510cb2f22 

They will give you an idea of what IL is and how you are affected by it. Stay tuned for more info!

TL;DR: Large swings in the relative price difference of the two tokens in the pool could result in a loss compared to holding the tokens themselves if you withdraw at that precise moment (hence the term impermanent). The loss is only "permanent" if you withdraw your liquidity completely, however that does not mean the IL will necessarily go away over time. Generally speaking, the trading fees received for being a liquidity provider and the yield from the farm can offset IL risk, but nothing is guaranteed.


