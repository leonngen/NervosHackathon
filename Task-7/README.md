# 1
![Screenshot from 2021-09-02 00-07-14](https://user-images.githubusercontent.com/89813113/131745500-5265feda-14d2-4561-8285-023a0cb1bccf.png)
![Screenshot from 2021-09-02 00-07-29](https://user-images.githubusercontent.com/89813113/131745501-185a141d-70ec-40c1-b152-cdfb11dda46f.png)
![Screenshot from 2021-09-02 00-07-46](https://user-images.githubusercontent.com/89813113/131745504-568ff640-78ea-4269-8ab1-76509228f827.png)
![Screenshot from 2021-09-02 00-07-58](https://user-images.githubusercontent.com/89813113/131745507-5a656e79-67b6-4d63-9a6a-600512140030.png)
![Screenshot from 2021-09-02 00-08-06](https://user-images.githubusercontent.com/89813113/131745509-07ae2baf-247f-49ea-8758-3c00980a519c.png)
![Screenshot from 2021-09-02 00-08-27](https://user-images.githubusercontent.com/89813113/131745512-fb86ec28-067e-48a1-826a-bafce6de9110.png)
![Screenshot from 2021-09-02 00-08-40](https://user-images.githubusercontent.com/89813113/131745516-9070bc54-f555-4f2c-b8fd-a6ec1ad97585.png)

# 2
Project Link: https://github.com/leonngen/SupplyChain-Nervos
# 3
Tx hash: 0x624f6c7ee4c39cac56d7d07e12500257323a6a71cc50912e2e880996ef7eb65e

Deployed Contract: 0x3ba29c385214dDB5f987BA4C1B7210133Ddc2751

ABI:

~~~
[
    {
      "inputs": [],
      "name": "index",
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
      "name": "productInfo",
      "outputs": [
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "category",
          "type": "string"
        },
        {
          "internalType": "enum SupplyChain.supplyProcess",
          "name": "proc",
          "type": "uint8"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "category",
          "type": "string"
        }
      ],
      "name": "setProduct",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "productId",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "trackInfo",
          "type": "string"
        }
      ],
      "name": "addProcess",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        }
      ],
      "name": "getProduct",
      "outputs": [
        {
          "components": [
            {
              "internalType": "string",
              "name": "name",
              "type": "string"
            },
            {
              "internalType": "string",
              "name": "category",
              "type": "string"
            },
            {
              "internalType": "enum SupplyChain.supplyProcess",
              "name": "proc",
              "type": "uint8"
            }
          ],
          "internalType": "struct SupplyChain.product",
          "name": "",
          "type": "tuple"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
~~~

