# 1
![Screenshot from 2021-09-01 23-15-30](https://user-images.githubusercontent.com/89813113/131740521-fbeb4381-67fc-4cc9-99f3-a5321c62e04b.png)
![Screenshot from 2021-09-01 23-15-43](https://user-images.githubusercontent.com/89813113/131740524-398a220b-5eeb-4129-8c70-492862b2ad87.png)
![Screenshot from 2021-09-01 23-16-02](https://user-images.githubusercontent.com/89813113/131740528-13541e52-d003-4ab0-80a3-61919752deb6.png)
![Screenshot from 2021-09-01 23-16-42](https://user-images.githubusercontent.com/89813113/131740533-67f66404-de1e-471d-8df8-c4f343d7ffbe.png)
![Screenshot from 2021-09-01 23-16-54](https://user-images.githubusercontent.com/89813113/131740535-09538b49-8156-4509-9409-c48145c96921.png)
![Screenshot from 2021-09-01 23-17-14](https://user-images.githubusercontent.com/89813113/131740538-88c79725-c7c2-41a0-a034-8cbfe4592287.png)
![Screenshot from 2021-09-01 23-17-29](https://user-images.githubusercontent.com/89813113/131740541-9ff5bec5-7b2b-4c4e-816f-d029ed8f778a.png)
# 2
Project Link: https://github.com/leonngen/SupplyChain-Nervos
# 3
Tx hash: 0x77881daf24ef316efe4475ab9d0b3b4cdfe05fd483d14f79a2b59937203ad420

Deployed Contract: 0xFe0be4765FaafF67F07ca87c4D059A7EEBF25744
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
          "internalType": "enum SupplyChain.shippingProcess",
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
              "internalType": "enum SupplyChain.shippingProcess",
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

