## 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![](1.png)
## 2. The transaction hash from the console output (in text format).
0xb1396168ef302174648806aa8fa1a1c2a7816682124a547bf27ab091fe9a4212
## 3. The contract address that you called (in text format).
0xa6bD7db63b5842F488AC5E5250DCafa33C7d5923
## 4. The ABI for contract you made a call on (in text format).
```json
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```