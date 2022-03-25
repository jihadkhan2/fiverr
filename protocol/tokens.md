# Tokens

### MARIO - bomb.money Token

![bomb.money (MARIO)](<../.gitbook/assets/bomb-256 (1).png>)

Contract: [0x522348779DCb2911539e76A1042aA922F9C47Ee3](https://bscscan.com/address/0x522348779dcb2911539e76a1042aa922f9c47ee3)

The MARIO token is designed to be used as a medium of exchange. The built-in stability mechanisms within the protocol aim to maintain MARIO's peg of 10,000 MARIO = 1 Bitcoin (BTC) in the long run.&#x20;

{% hint style="warning" %}
Note that MARIO **actively pegs via an algorithm**, but that **does not mean** it will be valued at 10,000 MARIO to 1 BTC at all times as **it is not collateralized**. **MARIO is not to be confused for a crypto or fiat-backed stablecoin.**
{% endhint %}

### [xMARIO - MARIO Protocol Governance Token](xbomb-bomb-staking.md)

![xMARIO](../.gitbook/assets/xbomb-logo.png)

Contract: [0xAf16cB45B8149DA403AF41C63AbFEBFbcd16264b](https://bscscan.com/address/0xaf16cb45b8149da403af41c63abfebfbcd16264b)

xMARIO is the governance token of MARIO Protocol.  It can be obtained by staking MARIO.

Learn more about xMARIO on the [xMARIO - MARIO Staking page](xbomb-bomb-staking.md).

### BSHARES - MARIO Shares

![BSHARE](<../.gitbook/assets/bshare-256 (1).png>)

Contract: [0x531780FAcE85306877D7e1F05d713D1B50a37F7A](https://bscscan.com/address/0x531780face85306877d7e1f05d713d1b50a37f7a)

MARIO Shares (BSHARE) are one of the ways to measure the value of the Mario Finance Protocol and shareholder trust in its ability to consistently maintain MARIO close to peg. During epoch expansions the protocol mints MARIO and distributes it proportionally to all BSHARE holders who have staked their tokens in the [**Boardroom**](boardroom.md).

BSHARE has a **maximum total supply of 70,001** tokens distributed as follows:

1. _Treasury/DAO Allocation: 5,500_ BSHARE vested linearly 12 months\*
2. _Team Allocation: 5,000_ BSHARE vested linearly over 12 months
3. _Rewards: 59,500_ BSHARE are allocated for incentivizing liquidity providers in two farming pools for 12 months
4. Initial mint: 1 BSHARE minted upon contract creation for the initial pool

{% hint style="success" %}
The Mario Finance team will use the treasury funds in any way that they feel is best for the long-term success of the protocol.&#x20;
{% endhint %}

### [BBOND - MARIO Bonds](bonds-mechanism.md)

![BBOND](<../.gitbook/assets/bbond-256 (1).png>)

Contract: [0xDA1d9C79240003195d0a67f202efcCCC3F78b994](https://bscscan.com/address/0xda1d9c79240003195d0a67f202efcccc3f78b994)

The main purpose of MARIO Bonds (BBOND) is to help incentivize fluctuations in the MARIO supply during epoch contraction periods. When the TWAP (time-weighted average price) of MARIO falls below 10,000 to 1 BTC, BBONDs are issued and can be bought with MARIO at the current price. Exchanging MARIO for BBOND burns MARIO tokens, taking them out of circulation (deflation) and helps to get the price back up to peg. These BBOND can be redeemed for MARIO when the price is above peg in the future, plus a premium based on how high above peg we currently are. This conversely creates inflation and subsequent sell pressure for MARIO when it is above peg, helping to push it back toward 10,000 MARIO to 1 BTC ratio.

{% hint style="info" %}
Unlike early algorithmic protocols, BBONDs do not have expiration dates.
{% endhint %}

All BBOND holders will be able to redeem their BBOND for MARIO tokens as long as the treasury has a positive MARIO balance, which typically happens when the protocol is in epoch expansion periods.
