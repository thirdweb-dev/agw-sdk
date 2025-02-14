# @abstract-foundation/agw-client

## 1.0.1

### Patch Changes

- 1480d43: Fixes prepareTransaction action so it does not override a manual gas value passed in

## 1.0.0

### Major Changes

- a674404: Finalize contract deployment addresses and adjust session types

## 0.1.8

### Patch Changes

- d64523c: Use gas estimation from zks_estimateFee instead of making a separate call for eth_estimateGas
- 46fd96b: Fix getSmartAccountAddressFromInitialSigner to throw if initial signer is undefined

## 0.1.7

### Patch Changes

- f3db70c: Fixed an issue that would occur in session key actions when creating an Abstract Client using the account and provider from another client as the signer

## 0.1.6

### Patch Changes

- 599ecf4: Fix EIP-5792 return type on wallet_getCallsStatus

## 0.1.5

### Patch Changes

- 5e15f01: Add new valid chain id

## 0.1.4

### Patch Changes

- f72546d: Update useCreateSession to add module if not installed

## 0.1.3

### Patch Changes

- cdecfd6: Fix incorrect package import from sessions

## 0.1.2

### Patch Changes

- 70bd5be: Add hook for createSession
- 1859431: Allow passing through additional transaction parameters for sendTransactionBatch

## 0.1.1

### Patch Changes

- 6ece839: Update message signing and typed signing to check codesize and only serialize as ERC-6942 signature if AGW is not deployed
- 7445977: Add getChainId to abstract wallet client
