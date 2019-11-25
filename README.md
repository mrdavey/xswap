# XSwap

### Rinkby

```
0xc8434758Bf78F0d5632E4E965C3889677C43Fa25
```

### Abi

```
[ { "constant": true, "inputs": [], "name": "usdx", "outputs": [ { "name": "", "type": "address" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "isOpen", "outputs": [ { "name": "", "type": "bool" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": false, "inputs": [], "name": "acceptOwnership", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "authority_", "type": "address" } ], "name": "setAuthority", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": true, "inputs": [], "name": "owner", "outputs": [ { "name": "", "type": "address" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": false, "inputs": [], "name": "disableOwnership", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": true, "inputs": [ { "name": "", "type": "address" } ], "name": "buyRate", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [ { "name": "", "type": "address" } ], "name": "price", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [ { "name": "", "type": "address" } ], "name": "sellRate", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "authority", "outputs": [ { "name": "", "type": "address" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "newOwner", "outputs": [ { "name": "", "type": "address" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": false, "inputs": [ { "name": "newOwner_", "type": "address" } ], "name": "transferOwnership", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "inputs": [ { "name": "_usdx", "type": "address" } ], "payable": false, "stateMutability": "nonpayable", "type": "constructor" }, { "anonymous": false, "inputs": [ { "indexed": true, "name": "authority", "type": "address" } ], "name": "LogSetAuthority", "type": "event" }, { "anonymous": false, "inputs": [ { "indexed": true, "name": "owner", "type": "address" } ], "name": "LogSetOwner", "type": "event" }, { "anonymous": false, "inputs": [ { "indexed": true, "name": "owner", "type": "address" }, { "indexed": true, "name": "newOwner", "type": "address" } ], "name": "OwnerUpdate", "type": "event" }, { "constant": false, "inputs": [ { "name": "_tokenAmount", "type": "uint256" }, { "name": "_tokenAddr", "type": "address" }, { "name": "_receiver", "type": "address" } ], "name": "sellToken", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_tokenAmount", "type": "uint256" }, { "name": "_tokenAddr", "type": "address" } ], "name": "sellToken", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_usdxAmount", "type": "uint256" }, { "name": "_tokenAddr", "type": "address" }, { "name": "_receiver", "type": "address" } ], "name": "buyToken", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_tokenAmount", "type": "uint256" }, { "name": "_tokenAddr", "type": "address" } ], "name": "buyToken", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_tokenAddr", "type": "address" }, { "name": "_price", "type": "uint256" }, { "name": "_sellRate", "type": "uint256" }, { "name": "_buyRate", "type": "uint256" } ], "name": "updatePair", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_tokenAddr", "type": "address" }, { "name": "_price", "type": "uint256" } ], "name": "updatePrice", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_tokenAddr", "type": "address" }, { "name": "_sellRate", "type": "uint256" } ], "name": "updateSellRate", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_tokenAddr", "type": "address" }, { "name": "_buyRate", "type": "uint256" } ], "name": "updateBuyRate", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_open", "type": "bool" } ], "name": "emergencyStop", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_tokenAddr", "type": "address" }, { "name": "_receiver", "type": "address" }, { "name": "_amount", "type": "uint256" } ], "name": "transferOut", "outputs": [ { "name": "", "type": "bool" } ], "payable": false, "stateMutability": "nonpayable", "type": "function" } ]
```

### run test

```
npm install
truffle test
```
