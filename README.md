
# Awesome Plutus [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of amazingly awesome Plutus libraries, resources and shiny things.

Plutus is the new smart contract language for the Cardano blockchain.

This is intended to give the first waves of Plutus developers the best and most comprehensive information and tools for using plutus as fast as possible.

## FAQ

Q: Where can I find haskell libraries I can use with plutus.
A: We recommend https://hoogle.haskell.org - which allows you to search for functions by type.
   Please keep in mind that Plutus on-chain code will only support a subset of haskell.
   You might also want to take a look at [awesome-haskell](https://github.com/krispo/awesome-haskell#readme)

## Official
- [Plutus Monorepo](https://github.com/input-output-hk/plutus)
- [The Plutus Playground](https://playground.plutus.iohkdev.io)  - allows a plutus script to be compiled and evaluated online

## Videos
- Plutus Pioneer program
  - [Lecture #1](https://www.youtube.com/watch?v=igV7kMXcdpw)
  - [Lecture #2](https://www.youtube.com/watch?v=E5KRk5y9KjQ)
  - [Lecture #3](https://www.youtube.com/watch?v=Lk1eIVm_ZTQ)
  - [Lecture #4](https://www.youtube.com/watch?v=6Reuh0xZDjY)
  - [Lecture #5](https://www.youtube.com/watch?v=6VbhY162GQA)
  - [Lecture #6](https://www.youtube.com/watch?v=wY7R-PJn66g&t=2832s)
- 
## Code Examples
- [Plutus Use Cases](https://github.com/input-output-hk/plutus/tree/master/plutus-use-cases)

## Testing
 the plutus monorepo currently provides two libraries that can be used to write effective tests for your plutus contract:
 
- [Wallet Emulator](https://github.com/input-output-hk/plutus/tree/master/plutus-contract/src/Wallet/Emulator)
- [PAB Simulator](https://github.com/input-output-hk/plutus/blob/master/plutus-pab/src/Plutus/PAB/Simulator.hs)

## Formal Specification Documents
- [The EUTXO Spec](https://github.com/hydra-supplementary-material/eutxo-spec/blob/master/extended-utxo-specification.pdf)
- [The Plutus Platform Technical Report (DRAFT)](https://hydra.iohk.io/build/5735420/download/1/plutus.pdf)
- [Plutus Core Formal Specification](https://hydra.iohk.io/build/5988492/download/1/plutus-core-specification.pdf)
