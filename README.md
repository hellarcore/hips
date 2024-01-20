# Hellar Improvement Proposals (HIPs)

HIP stands for Hellar Improvement Proposal. Similar to Bitcoin's [BIPs](https://github.com/bitcoin/bips/), a HIP is a design document providing information to the Hellar community, or describing a new feature for Hellar or its processes or environment. The HIP should provide a concise technical specification of the feature and a rationale for the feature.

Because Hellar is forked from the Bitcoin codebase, many of the BIPs can be applied to Hellar as well (a list of the BIPs updated to include Hellar-specific details can be found [here](https://github.com/hellarcore/bips)). The purpose of the HIPs is not to duplicate those which exist as BIPs, but to introduce protocol upgrades or feature specifications which are unique to Hellar.

## Contributions

We use the same general guidelines for introducing a new HIP as specified in [BIP 2](https://github.com/bitcoin/bips/blob/master/bip-0002.mediawiki), with a few differences. Specifically:

* Instead of the BIP editor, initiate contact with the Hellar Core development team and your request should be routed to the HIP editor(s). The HIP workflow mimics the BIP workflow.
* Recommended licenses include the MIT license
* Markdown format is the preferred format for HIPs
* Following a discussion, the proposal should be submitted to the HIPs git repository as a pull request. This draft must be written in BIP/HIP style as described in [BIP 2](https://github.com/bitcoin/bips/blob/master/bip-0002.mediawiki), and named with an alias such as "hip-johndoe-infinitehellar" until the editor has assigned it a HIP number (authors MUST NOT self-assign HIP numbers).

## Hellar Improvement Proposal Summary

Number | Layer | Title | Type | Status
--- | --- | --- | --- | --- | ---
[1](hip-0001.md) | Consensus | Initial Scaling of the Network | Standard | Final
[2](hip-0002.md) | Consensus | Special Transactions |  Standard | Final
[3](hip-0003.md) | Consensus | Deterministic Masternode Lists |  Standard | Final
[4](hip-0004.md) | Consensus | Simplified Verification of Deterministic Masternode Lists | Standard | Final
[5](hip-0005.md) | Consensus | Blockchain Users | Standard | Withdrawn
[6](hip-0006.md) | Consensus | Long-Living Masternode Quorums | Standard | Final
[7](hip-0007.md) | Consensus | LLMQ Signing Requests / Sessions |  Standard | Final
[8](hip-0008.md) | Consensus | ChainLocks | Alexander Block | Standard | Final
[9](hip-0009.md) | Applications | Feature Derivation Paths |  Informational | Proposed
[10](hip-0010.md) | Consensus | LLMQ InstantSend |  Standard | Final
[11](hip-0011.md) | Consensus | Identities | Standard | Proposed
[12](hip-0012.md) | Consensus | Hellar Platform Name Service | Standard | Proposed
[13](hip-0013.md) | Applications | Identities in Hierarchical Deterministic Wallets | Informational | Proposed
[14](hip-0014.md) | Applications | Extended Key Derivation using 256-Bit Unsigned Integers |  Informational | Proposed
[15](hip-0015.md) | Applications | HellarPay |  Standard | Proposed
[16](hip-0016.md) | Applications | Headers First Synchronization on Simple Payment Verification Wallets | Informational | Proposed
[20](hip-0020.md) | Consensus | Hellar Opcode Updates | Standard | Final
[21](hip-0021.md) | Consensus | LLMQ DKG Data Sharing | Standard | Final
[22](hip-0022.md) | Consensus | Making InstantSend Deterministic using Quorum Cycles | Standard | Final
[23](hip-0023.md) | Consensus | Enhanced Hard Fork Mechanism |  Standard | Proposed
[24](hip-0024.md) | Consensus | Long-Living Masternode Quorum Distribution and Rotation |  Standard | Final
[25](hip-0025.md) | Peer Services | Compressed Block Headers |  Standard | Proposed
[26](hip-0026.md) | Consensus | Multi-Party Payout | Standard | Proposed
27 |  |  |  |  | Reserved
[28](hip-0028.md) | Consensus | Progress Masternodes | Standard | Final
[29](hip-0029.md) | Consensus | Randomness Beacon For LLMQ Selection |  | Standard | Proposed

## License

Unless otherwise specified, Hellar Improvement Proposals (HIPs) are released under the terms of the MIT license. See [LICENSE](LICENSE) for more information or see the [MIT License](https://opensource.org/licenses/MIT).
