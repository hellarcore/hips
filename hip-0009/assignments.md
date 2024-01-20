## Registered Features

Here is a table of current feature paths and any associated HIP. Future HIPs may introduce more types.


| Feature Index * | Feature | HIP Number and Name | Note |
| ------------------ | ------------ | ------------------- | ---- |
| `3'` | Masternode Keys | [HIP 0003: Deterministic Masternode List](https://github.com/hellarcore/hips/blob/master/hip-0003.md) | The masternode related keys are located in the following sub-paths:  <br>`0'/*` - _Reserved_<br>`1'/*` - Voting Key<br>`2'/*` - Owner Key<br>`3'/*` - Operator Key<br>`4'/*` - [Platform P2P Key](../hip-0028.md#calculating-the-platform-node-id) (ED25519)<br><br>For example, the first voting key for Hellar would be at `m/9'/5'/3'/1'/0` |
| `5'` | Identity Keys | [HIP 0013: Identities in Hierarchical Deterministic wallets](../hip-0013.md) | The related keys are located in the following sub-paths: <br>`0'/key type'/identity index'/key index'/*` - Identity Authentication ([details](../hip-0013.md#identity-authentication-keys))<br>`1'/*` - Identity Registration Funding ([details](../hip-0013.md#identity-registration-funding-keys))<br>`2'/*` - Identity Topup Funding ([details](../hip-0013.md#identity-top-up-funding-keys))<br><br>For example, the first Identity Registration Funding key for Hellar would be at `m/9'/5'/5'/1'/0` |
| `15'` | HellarPay - Incoming Funds | [HIP 0015: HellarPay](../hip-0015.md#hellarcore-incoming-funds-derivation-path) | The related keys are located in the following sub-paths: `/0'/account'/*`<br><br>For example, incoming funds for the first identity would be at `m/9'/5'/15'/0'/*` |
| `16'` | HellarPay - Auto Accept Proof | [HIP 0015: HellarPay](../hip-0015.md#auto-accept-proof-autoacceptproof) | The related keys are located in the following sub-paths: `16'/expiration timestamp'`<br><br>For example, the key for a proof expiring at a Unix epoch time of `1605927033` would be at `m/9'/5'/16'/1605927033'` |

Note: all HIP 0009 paths are of the format: `m / 9' / coin_type' / feature' / *`

\* Where applicable, the feature index matches the number of the HIP that defines the feature(s)
