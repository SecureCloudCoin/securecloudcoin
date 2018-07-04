
[![Build Status](https://travis-ci.org/securecloudcoin-project/securecloudcoin.svg?branch=master)](https://travis-ci.org/securecloudcoin-project/securecloudcoin) 


### SecureCloudCoin is a fork of [PIVX](https://github.com/PIVX-Project/PIVX) that forked [Dash](https://github.com/dashpay/dash) that forked [Bitcoin](https://github.com/bitcoin/bitcoinp)

# SecureCloudCoin Core integration/staging repository


SecureCloudCoin is a cutting edge cryptocurrency, with many features not available in most other cryptocurrencies.
- Anonymized transactions using zerocoin technology.
- Fast transactions featuring guaranteed zero confirmation transactions, PIVX named it _SwiftX_.
- Decentralized blockchain voting providing for consensus based advancement of the current Masternode
  technology used to secure the network and provide the above features, each Masternode is secured
  with a collateral of 12345 SC2.

More information at [securecloudcoin.com](https://securecloudcoin.com) Visit our ANN thread at [BitcoinTalk](http://www.bitcointalk.org/index.php)


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

The information can be retrived into the code [here](https://github.com/securecloudcoin-project/securecloudcoin/blob/master/src/main.cpp#L2131-L2158). 

