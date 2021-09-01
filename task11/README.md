# Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

## 1) A screenshot of the accounts you created (account list) in ckb-cli.
![](https://raw.githubusercontent.com/ysongh/Nervos-Hackathon-Submission/master/task11/screenshot1.png)

## 2) A link to the Layer 1 address you funded on the Testnet Explorer.
https://explorer.nervos.org/aggron/address/ckt1qyq02zgw5z3j6ph68x3rsmu23qcqg2l3adusturc3v

## 3) A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2.
![](https://raw.githubusercontent.com/ysongh/Nervos-Hackathon-Submission/master/task11/screenshot2.png)

## 4) A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2.
![](https://raw.githubusercontent.com/ysongh/Nervos-Hackathon-Submission/master/task11/screenshot3.png)

## 5) The transaction hash of the "Contract call" from the console output (in text format).
0xe55e0cef0421eda1f6a8cea236aa2e4f89e7db30be3d35333bc9e7a850acb1a5

## 6) The contract address that you called (in text format).
0xE2A30E50C9D437227654bAb92Af1b66F0601Dc54

## 7) The ABI for contract you made a call on (in text format).
```
[[
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "string",
          "name": "cid",
          "type": "string"
        },
        {
          "indexed": false,
          "internalType": "string",
          "name": "name",
          "type": "string"
        },
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "date",
          "type": "uint256"
        },
        {
          "indexed": false,
          "internalType": "address",
          "name": "from",
          "type": "address"
        }
      ],
      "name": "ImageAdded",
      "type": "event"
    },
    {
      "inputs": [],
      "name": "imageCount",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "images",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "cid",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        },
        {
          "internalType": "uint256",
          "name": "date",
          "type": "uint256"
        },
        {
          "internalType": "address",
          "name": "from",
          "type": "address"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_cid",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "_name",
          "type": "string"
        }
      ],
      "name": "addImages",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
]
```
## 8) Your Tron address (in text format).
TQTcDZGmrocEB8caMBL3gDZ57ficGCEKUs