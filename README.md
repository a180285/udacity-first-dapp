### Specify the Truffle version and OpenZeppelin version used in the project.

```bash
$ truffle version
Truffle v5.1.0 (core: 5.1.0)
Solidity v0.5.12 (solc-js)
Node v10.10.0
Web3.js v1.2.2
```

openzeppelin version from package-lock.json:
```json
    "openzeppelin-solidity": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/openzeppelin-solidity/-/openzeppelin-solidity-2.1.2.tgz",
      "integrity": "sha512-1ggh+AZFpMAgGfgnVMQ8dwYawjD2QN4xuWkQS4FUbeUz1fnCKJpguUl2cyadyfDYjBq1XJ6MA6VkzYpTZtJMqw=="
    }
```


### Your ERC-721 Token Name and Symbol

```solidity
    string private _name_ = "HuangWei First Token";
    string private _symbol_ = "HWFT";
```

### Your “Token Address” on the Rinkeby Network

I used **ropsten** test network

Token address `0x6fa0f37f65311d28d0e32907e5a71f0127575835`

Etherscan Link: https://ropsten.etherscan.io/token/0x6fa0f37f65311d28d0e32907e5a71f0127575835
