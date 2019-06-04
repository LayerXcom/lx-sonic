# Sonic proving system
This library is an implementation of Sonic.

- [Sonic: Zero-Knowledge SNARKs from Linear-Size Universal and
Updatable Structured Reference Strings](https://eprint.iacr.org/2019/099.pdf)
  - Mary Maller, [Sean Bowe](https://github.com/ebfull), Markulf Kohlweiss, Sarah Meiklejohn

Unhelpder mode is not fully implemented yet.

## Setup
```
git clone git@github.com:LayerXcom/lx-sonic.git
cd lx-sonic
cargo build --release
```

## Test
```
cargo test --release
```

## Acknowledgements
Original implementation for paper is in [sonic crate](https://github.com/ebfull/sonic), developed by [Sean Bowe](https://github.com/ebfull). This implementation have been adapted from it.
