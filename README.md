INNOVATIVE and DECENTRALIZED crypto currency that have the bases (fast, secure and anonymous transactions, low fees) to become the best digital payment asset for buying/selling goods and service around the world. XerumCash will also be the starting point around which we will create a complex system of tools and services for ecommerce, trading and crypto world.

Anonymized transactions using coin mixing technology. 1-Second-Transactions. Network stability with masternodes, each is secured with a collateral of 1.000 XerumCash.

For further information visit us at [http://www.XerumCash.com/#](http://www.XerumCash.com/#)

# Coin Specs

• PoW Algorithm: NeoScrypt  
• Premine: 1,366,000 XerumCash 
• Type: POW + Masternode
• Block Time: 45 Seconds  
• PoW Max Coin Output/Supply: 30,450,000 
• Masternode Requirements: 1,000 XerumCash  
• Maturity: 101 Confirmations

# Block Reward Distribution

<table class="reward_table"width="100%">
<tr>
<th rowspan=2>Blocks</th>
<th rowspan=2>Reward</th>						
<th colspan=2>Reward Distribution</th>
</tr>
<tr>
<th>Minner</th>
<th>Masternode</th>
</tr>
<tr>
<td>2 - 64800</td>
<td>4 XerumCash</td>
<td>25%</td>
<td>75%</td>
</tr>
<tr>
<td>64801 - 129600</td>
<td>3.9 XerumCash</td>
<td>27%</td>
<td>73%</td>
</table>				
*) Starting with block 525601 the reward will decrease by 10% every year



License
-------

XerumCash Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/XerumCashpay/XerumCash/tags) are created to indicate new official,
stable release versions of Vivo Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](/doc/unit-tests.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows
and Linux, OS X, and that unit and sanity tests are automatically run.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward

