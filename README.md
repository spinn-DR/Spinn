# Spinn Core integration/staging repository
=====================================

## What is Spinn?

Spinn is an open source community-driven cryptocurrency forked from bitcoin that focuses on three main aspects:

(1) Privacy: Through the use of mixers built-in with each node allowing privacy that is also resistant to inflation bugs.

(2) Decentralization: Proof of Work SHA256 (was going to go SHA3 but there's more SHA256 miners)

(3) Node Incentives: Aside from typical mining incentives, node runners also have an incentive to spin (mix), and every user the incentive to remain anonymous without having to enroll in any mixing service as it's automatically included in the protocol.

## Pre-mine Disclosure
There will be 1 million pre-mined coins prior to launch.
10% will be held as a developer fund;
the other 90% will be available for the Airdrop.

Visit our [Spinn-Airdrop](https://github.com/spinn-DR/spinn-airdrop) repository for more details on how to claim the airdrop.

A pre-mine is necessary in order for the built-in spinning to work properly. We need users who already have coins prior to launch in order to provide liquidity needed for spinning.

## Road Map
- GitHub release for Open-Source review (coming soon!)
- Finish Website 
- Bitcoin UTXO Snapshot 03 October 2022
- Launch 05 December 2022!



## Experimental Risks
If there is an insufficient amount of node operators and liquidity at launch, users attempting to spend may be unable to spend as the network is unable find a spin partner to broadcast their transaction for them. To mitigate this risk we have introduced an airdop so that they can enable spinning that is built-in with the node that can be operated without any mining hardware and earn rewards. This incentivizes users to run a node so they can earn funds just by running a node and by keeping a balance on their node wallet. The incentive should keep users running nodes, and thereby keeping the chain alive. Fortunately if users left and liquidity were to completely evaporate the chain can still be revived later if sufficient liquidity returns.  If the amount of spinners ever goes to zero, it incentivizes someone to reactivate the chain on their own by adding liquidity as they would be the only spinner and thereby collecting 100% of mining fees of pending transactions. It should go without saying this will be an experiment.
 
## License
Spinn Core is released under the terms of the MIT license. See https://opensource.org/licenses/MIT.

## Development Process

The master branch is regularly built (see doc/build-*.md for instructions) and tested, but it is not guaranteed to be completely stable. [Tags](https://github.com/spinn-DR/Spinn/tags) are created regularly from release branches to indicate new official, stable release versions of Spinn Core.


## Testing

Testing and code review is the bottleneck for development. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people a lot of money.

## Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to submit new unit tests for old code.

## Donations

Creating new software takes time and is expensive. Please consider donating BTC: 3FU4GQ8ruxWFTydEgzookE2mbgtEzJN9Xh

