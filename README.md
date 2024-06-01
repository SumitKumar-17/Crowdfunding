# Crowdfunding

With connected to the blockchain, metamask pairing, interaction with smart contracts, sending Ethereum through the blockchain network, and writing solidity code.

The client directory contains the frontend code .

The web3 directory has the Smart Contract code. It is deployed using the thirdweb frmaework.


For working with the repository,

1. Clone the repository

```python
git clone https://github.com/SumitKumar-17/Crowdfunding.git
```

2. Go to the web3 directory and run the command 

    Rename the .env.example file to .env and add the following variables

    ```python
    PRIVATE_KEY=<your_private_key_metamask>
    ```


3. Go to the web3 directory and run the command 


```python
npm install
```

```python
npm run deploy
```

A thirdweb server will be started and the contract will be deployed. Copy the contract address and paste it in the client/src/context/index.jsx file.

4. Go to the client directory and run the command

```python
npm install
```

```python
npm start
```

