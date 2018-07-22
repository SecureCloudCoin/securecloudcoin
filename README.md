
[![Build Status](https://travis-ci.org/securecloudcoin-project/securecloudcoin.svg?branch=master)](https://travis-ci.org/securecloudcoin-project/securecloudcoin) 
# SecureCloudCoin Core integration/staging repository

### SecureCloudCoin is a fork of [RUPX](https://github.com/rupaya-project/rupaya) that forked [PIVX](https://github.com/PIVX-Project/PIVX) that forked [Dash](https://github.com/dashpay/dash) that forked [Bitcoin](https://github.com/bitcoin/bitcoinp)

### Compiling with boost other than 1.54 will create a malfunctioning wallet. This is the default version on Ubuntu 16.04 LTS, but newer versions will come with newer boost versions.


SecureCloudCoin is a new generation cryptocurrency, with many features not available in most other cryptocurrencies.
It is one of the top players in technological vanguard in the market of cryptocurrencies.
- Anonymized transactions using zerocoin technology.
- Fast transactions featuring guaranteed zero confirmation transactions, PIVX named it _SwiftX_.
- Decentralized blockchain voting providing for consensus based advancement of the current Masternode
  technology used to secure the network and provide the above features, each Masternode is secured
  with a collateral of 12345 SC2.
  
  
This is not just another masternode coin, it aims to attack the market making available to buy cloud virtual machine directly from our platform and permits payments with SC2 currency.

The biggest problem of masternode cryptocurrencies is the inflaction. SC2 inflaction plan will will grant solid rewards to investor and at the same time will control the inflaction with a studied strategy, and a studied reward plan that will leave high the supply demand offer.

More information at [securecloudcoin.com](https://www.securecloudcoin.com) Visit our ANN thread at [BitcoinTalk](https://bitcointalk.org/index.php?topic=4597563.msg41497230#msg41497230)


### Coin Specs
<table>
<tr><td>Algo</td><td>Xevan</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoS Phase)</td><td>25,000,000 SC2</td></tr>
<tr><td>Premine</td><td>1,200,000 SC2</td></tr>
<tr><td>RPC Port</td><td>7654</td></tr>
<tr><td>P2P Port</td><td>42523</td></tr>
</table>


### Reward Distribution

<table>
<th colspan=4>PoW Phase</th>
<tr><th>Block Height</th><th>Reward Amount</th><th>Notes</th><th>Duration (Days)</th></tr>
<tr><td>1</td><td>1,200,000 SC2</td><td>Initial Premine for Coin Swap</td><td>0 Days</td></tr>
<tr><th colspan=4>PoS Phase</th></tr>
<td colspan=3>Masternodes: 75%</td><td>Stakers: 25%</td></tr>
</table>

Governance proposals (Budget) will be usable starting from _superblock_ **100,000** in cycles of 30 days. Anyone will be able to create proposals and MasterNode owners will vote them.

### PoS Rewards 

<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Masternodes</th><th>Stakers</th><th>Governance Max</th>
<tr><td>Phase 1</td><td>0 ->  18000</td><td>14 SC2</td><td>10,5 SC2</td><td>3,5 SC2</td><td>0 SC2</td></tr>
<tr><td>Phase 2</td><td>18001 ->  23000</td><td>140 SC2</td><td>105 SC2</td><td>35 SC2</td><td>0 SC2</td></tr>
<tr><td>Phase 3</td><td>23001 ->  30000</td><td>90 SC2</td><td>67,5 SC2</td><td>22,5 SC2</td><td>0 SC2</td></tr>
<tr><td>Phase 4</td><td> 30001 ->  50000</td><td>95 SC2</td><td>71,25 SC2</td><td>23,75 SC2</td><td>0 SC2</td></tr>
<tr><td>Phase 5</td><td> 50001 ->  100000</td><td>120 SC2</td><td>90 SC2</td><td>30 SC2</td><td>0 SC2</td></tr>
<tr><td>Phase 6</td><td>100001 ->  200000</td><td>88 SC2</td><td>66 SC2</td><td>22 SC2</td><td>22 SC2</td></tr>
<tr><td>Phase 7</td><td>200001 ->  300000</td><td>80 SC2</td><td>60 SC2</td><td>20 SC2</td><td>20 SC2</td></tr>
<tr><td>Phase 8</td><td>300001 ->  400000</td><td>72 SC2</td><td>54 SC2</td><td>18 SC2</td><td>18 SC2</td></tr>
<tr><td>Phase 9</td><td>400001 ->  500000</td><td>64 SC2</td><td>48 SC2</td><td>16 SC2</td><td>16 SC2</td></tr>
<tr><td>Phase 10</td><td>500001 ->  600000</td><td>56 SC2</td><td>42 SC2</td><td>14 SC2</td><td>14 SC2</td></tr>
<tr><td>Phase 11</td><td>600001 ->  700000</td><td>48 SC2</td><td>36 SC2</td><td>12 SC2</td><td>12 SC2</td></tr>
<tr><td>Phase 12</td><td>700001 ->  800000</td><td>40 SC2</td><td>30 SC2</td><td>10 SC2</td><td>10 SC2</td></tr>
<tr><td>Phase 13</td><td>800001 ->  900000</td><td>32 SC2</td><td>24 SC2</td><td>8 SC2</td><td>8 SC2</td></tr>
<tr><td>Phase 14</td><td>900001 -> 1000000</td><td>24 SC2</td><td>18 SC2</td><td>6 SC2</td><td>6 SC2</td></tr>
<tr><td>Phase 15</td><td>1000001 -> 1100000</td><td>16 SC2</td><td>12 SC2</td><td>4 SC2</td><td>4 SC2</td></tr>
<tr><td>Phase 16</td><td>1100001 -> 1200000</td><td>8 SC2</td><td>6 SC2</td><td>2 SC2</td><td>2 SC2</td></tr>
<tr><td>Phase 17</td><td>1200001 -> INFINITE</td><td>0.001 SC2</td><td>0.00075 SC2</td><td>0.00025 SC2</td><td>0.00025 SC2</td></tr>
</table>

The Governance percentage is only added into circulation if there are proposals voted by the MasterNodes every month.

The information can be retrived into the code [here](https://github.com/SecureCloudCoin/securecloudcoin/blob/master/src/main.cpp#L2133-L2166). 

