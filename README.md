# Keccak Circuit implementation in Halo2

We port Konstantin Panarin's [sparse representation](https://hackmd.io/xfgP5_uMTZyaEJJG4EJoRQ) idea and implementation from [matter-labs/franklin-crypto](https://github.com/matter-labs/franklin-crypto/blob/dev/src/plonk/circuit/hashes_with_tables/keccak/gadgets.rs) to Halo2.

The circuit is optimized to minize columns. It is suitable for when verification cost is high and not much hashes to perform.
