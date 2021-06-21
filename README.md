# Vexchange VET

Vexchange VET is a fork of VVET that ensures Vexchange LPs receive their fair share of VTHO. The contracts have a `recoverToken` method that allows the `owner` to move non-VET VIP-180 tokens out of the contract. This will enable the distribution of VTHO to LPs that otherwise might have been stuck, or stolen by frontrunners via the `skim` method. Initially, the Vexchange team will be entrusted to distribute the `VTHO`, however, `owner` can always be changed to a trustless claim manager contract (more dev work than a centralized solution).

## Deployed contract addresses
 - Mainnet: Coming Soon
 - Testnet: Coming Soon
