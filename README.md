# Wrapped VET

Wrapped VET is a fork of VVET that will have the benefit of ensuring Vexchange LPs receive their fair share of VTHO generated. The contracts have a `recoverToken` method that allows the `owner` to move any VIP-180 tokens out of the contract. This ability does not compramise the security of the underlying VET. The ability to move VIP-180s will enable the distribution of VTHO to LPs that otherwise might have been stuck, or stolen by frontrunners via the `skim` method. Initially, the Vexchange team will be entrusted to distribute the `VTHO`, however, `owner` can always be changed to a trustless claim manager contract (more dev work than a centralized solution).

## Deployed contract addresses
| Network | Address                                                                                                                               |
| ---     | ---                                                                                                                                   |
| Mainnet | [0xd8ccdd85abdbf68dfec95f06c973e87b1b5a9997](https://explore.vechain.org/accounts/0xd8ccdd85abdbf68dfec95f06c973e87b1b5a9997)         |
| Testnet | [0x93e5fa8011612fab061ef58cbab9262d2e76407b](https://explore-testnet.vechain.org/accounts/0x93e5fa8011612fab061ef58cbab9262d2e76407b) |
