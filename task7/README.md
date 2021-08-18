# Gitcoin: 7) Port An Existing Ethereum DApp To Polyjuice

## 1) Screenshots or video of your application running on Godwoken.
![](https://raw.githubusercontent.com/ysongh/Nervos-Hackathon-Submission/master/task7/screenshot1.png)

![](https://raw.githubusercontent.com/ysongh/Nervos-Hackathon-Submission/master/task7/screenshot2.png)

![](https://raw.githubusercontent.com/ysongh/Nervos-Hackathon-Submission/master/task7/screenshot3.png)

![](https://raw.githubusercontent.com/ysongh/Nervos-Hackathon-Submission/master/task7/screenshot4.png)

## 2) Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.
https://github.com/ysongh/Image-Storage-On-Polyjuice

## 3) If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)
- transaction hash = `0xd6ef5d6fa7afce8a7315605f167e5ea18653c5f0a97efb8629aba74026e347f8`
- deployed contract address = `0xd6B5BD3ED292DAF7D2DA9a0c9F18183BC4f7AfD5`
- ABI of the deployed smart contract
```
 "abi": [
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
],
```