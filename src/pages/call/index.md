---
title: Call
version: 0.8.26
description: In Solidity call is a low level function to interact with other contracts
keywords: [contract, contracts, call, function, functions]
cyfrinLink: https://www.cyfrin.io/glossary/call-solidity-code-example
---

`call` is a low level function to interact with other contracts.

This is the recommended method to use when you're just sending Ether via calling the `fallback` function.

However it is not the recommended way to call existing functions.

### Few reasons why low-level call is not recommended

- Reverts are not bubbled up
- Type checks are bypassed
- Function existence checks are omitted

```solidity
{{{Call}}}
```
