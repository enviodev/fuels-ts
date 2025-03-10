# @fuel-ts/errors

## 0.89.0

### Patch Changes

- Updated dependencies [67afa32]
- Updated dependencies [a96c1fe]
  - @fuel-ts/versions@0.89.0

## 0.88.1

### Patch Changes

- @fuel-ts/versions@0.88.1

## 0.88.0

### Patch Changes

- @fuel-ts/versions@0.88.0

## 0.87.0

### Patch Changes

- @fuel-ts/versions@0.87.0

## 0.86.0

### Patch Changes

- 316c757: fix: internalize `ethers` functionality and remove dependency
- Updated dependencies [64e9659]
  - @fuel-ts/versions@0.86.0

## 0.85.0

### Patch Changes

- f7eacb4: chore: warn on fuel client version incompatibility
  - @fuel-ts/versions@0.85.0

## 0.84.0

### Patch Changes

- Updated dependencies [2990edb]
  - @fuel-ts/versions@0.84.0

## 0.83.0

### Minor Changes

- 9c3c094: chore!: upgrade `fuel-core` to `0.24.3`

### Patch Changes

- Updated dependencies [29f46ef]
- Updated dependencies [9c3c094]
- Updated dependencies [0d75266]
  - @fuel-ts/versions@0.83.0

## 0.82.0

### Patch Changes

- @fuel-ts/versions@0.82.0

## 0.81.0

### Patch Changes

- 37743e8: chore: add initial `depcheck` using knip
- Updated dependencies [1d92ce7]
  - @fuel-ts/versions@0.81.0

## 0.80.0

### Minor Changes

- 29d5303: chore: remove redundant error codes

### Patch Changes

- @fuel-ts/versions@0.80.0

## 0.79.0

### Patch Changes

- Updated dependencies [dc1b0925]
  - @fuel-ts/versions@0.79.0

## 0.78.0

### Patch Changes

- Updated dependencies [9df48991]
  - @fuel-ts/versions@0.78.0

## 0.77.0

### Patch Changes

- Add try/catch block when parsing GraphQL stream data response, by [@Torres-ssf](https://github.com/Torres-ssf) (See [#1839](https://github.com/FuelLabs/fuels-ts/pull/1839))
- Migrate implementations of `sha256`, `keccak` and `scrypt` to `@noble/hashes`, by [@danielbate](https://github.com/danielbate) (See [#1786](https://github.com/FuelLabs/fuels-ts/pull/1786))
- 🐞 fix: disallow transferring <= 0 amounts, by [@Dhaiwat10](https://github.com/Dhaiwat10) (See [#1827](https://github.com/FuelLabs/fuels-ts/pull/1827))
- - Handling `SqueezedOut` status update when calling `submitAndAwait` subscription at `Provider.sendTransaction`
  - Handling `SqueezedOut` status update when calling statusChange subscrition at `TransactionResponse.waitForResult`, by [@Torres-ssf](https://github.com/Torres-ssf) (See [#1829](https://github.com/FuelLabs/fuels-ts/pull/1829))

## 0.76.0

## 0.75.0

### Minor Changes

- Introduce the v1 encoding scheme and use correct file naming conventions for `@fuel-ts/abi-coder`, by [@danielbate](https://github.com/danielbate) (See [#1780](https://github.com/FuelLabs/fuels-ts/pull/1780))

### Patch Changes

- exports InvocationCallResult, by [@Torres-ssf](https://github.com/Torres-ssf) (See [#1765](https://github.com/FuelLabs/fuels-ts/pull/1765))
- Use interal utilities for arrayify, hexlify, concat and BytesLike, by [@danielbate](https://github.com/danielbate) (See [#1775](https://github.com/FuelLabs/fuels-ts/pull/1775))

## 0.74.0

### Minor Changes

- restructure Account related packages, by [@Torres-ssf](https://github.com/Torres-ssf) (See [#1675](https://github.com/FuelLabs/fuels-ts/pull/1675))

## 0.73.0

## 0.72.0

### Patch Changes

- Implemented GraphQL subscriptions, by [@arboleya](https://github.com/arboleya) (See [#1495](https://github.com/FuelLabs/fuels-ts/pull/1495))

## 0.71.1

## 0.71.0

### Minor Changes

- Add `pnpm create fuels` CLI tool, by [@arboleya](https://github.com/arboleya) (See [#1624](https://github.com/FuelLabs/fuels-ts/pull/1624))
- add support for TX policies, by [@arboleya](https://github.com/arboleya) (See [#1624](https://github.com/FuelLabs/fuels-ts/pull/1624))

## 0.70.1

## 0.70.0

### Minor Changes

- Add `pnpm create fuels` CLI tool, by [@Dhaiwat10](https://github.com/Dhaiwat10) (See [#1565](https://github.com/FuelLabs/fuels-ts/pull/1565))
- add support for TX policies, by [@Torres-ssf](https://github.com/Torres-ssf) (See [#1437](https://github.com/FuelLabs/fuels-ts/pull/1437))

## 0.69.1

## 0.69.0

## 0.68.0

### Patch Changes

- Improves inputs validation and adds pretty error messages, by [@arboleya](https://github.com/arboleya) (See [#1433](https://github.com/FuelLabs/fuels-ts/pull/1433))
- Remove hexlify logic on values that are not hex, by [@camsjams](https://github.com/camsjams) (See [#1454](https://github.com/FuelLabs/fuels-ts/pull/1454))

## 0.67.0

## 0.66.1

### Patch Changes

- Adjusting package manager configs, by [@arboleya](https://github.com/arboleya) (See [#1415](https://github.com/FuelLabs/fuels-ts/pull/1415))

## 0.66.0

## 0.65.0

## 0.64.1

## 0.64.0

## 0.63.0

## 0.62.0

### Minor Changes

- Reverted GraphQL subscriptions, thus removing `Provider.operations.statusChange`, by [@nedsalk](https://github.com/nedsalk) (See [#1333](https://github.com/FuelLabs/fuels-ts/pull/1333))

## 0.61.0

### Minor Changes

- Check mismatch of fuel client version and supported version: throw on major/minor mismatch, warn on patch mismatch, by [@nedsalk](https://github.com/nedsalk) (See [#1287](https://github.com/FuelLabs/fuels-ts/pull/1287))
- Improve developer experience of `fromEvmAddress` address helper function, by [@danielbate](https://github.com/danielbate) (See [#1309](https://github.com/FuelLabs/fuels-ts/pull/1309))

## 0.60.0

### Minor Changes

- purging constant MAX_GAS_PER_TX, by [@Torres-ssf](https://github.com/Torres-ssf) (See [#1272](https://github.com/FuelLabs/fuels-ts/pull/1272))

## 0.59.0

### Minor Changes

- using `FuelError` instead of `@ethersproject/logger`, by [@Torres-ssf](https://github.com/Torres-ssf) (See [#1278](https://github.com/FuelLabs/fuels-ts/pull/1278))

## 0.58.0

### Minor Changes

- Remove `chainId` from the `Predicate` constructor. You don't need to pass in `chainId` anymore since you are passing in a `provider` already, by [@Dhaiwat10](https://github.com/Dhaiwat10) (See [#1181](https://github.com/FuelLabs/fuels-ts/pull/1181))
- using FuelError across all packages, by [@Torres-ssf](https://github.com/Torres-ssf) (See [#1230](https://github.com/FuelLabs/fuels-ts/pull/1230))

## 0.57.0

## 0.56.1

### Patch Changes

- Simplyfing errors package and its test utility, by [@arboleya](https://github.com/arboleya) (See [#1228](https://github.com/FuelLabs/fuels-ts/pull/1228))

## 0.56.0

### Minor Changes

- forbid multicall for more than one function that returns heap types, by [@Torres-ssf](https://github.com/Torres-ssf) (See [#1217](https://github.com/FuelLabs/fuels-ts/pull/1217))

## 0.55.0

## 0.54.1

## 0.54.0

## 0.53.0
