# Lab 10
## Overview
This lab demonstrates the usages of the blockchain and how to mine a virtual coin

The first task was to run hash_value.py twice and compare the results.
![hash](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab10/Lab10%20Images/hash_value.png)

I then ran python snakecoin.py, which began adding snakecoins to the blockchain.
![snakecoin](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab10/Lab10%20Images/snakecoin1.png)
![snakecoin2](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab10/Lab10%20Images/snakecoin2.png)

I proceeded to run the SnakeCoin server at http://127.0.0.1:5000/ and used python3 snakecoin-server-full-code.py to connect my terminal.
![server](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab10/Lab10%20Images/snakecoin%20terminal%201.png)

On a separate terminal, I created a transaction and mine a new block at http://127.0.0.1:5000/mine
![curl](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab10/Lab10%20Images/snakecoin%20terminal%202.png)

After cloning https://github.com/satwikkansal/python_blockchain_app.git into my lesson10 direction and uncommenting the last line of node_server.py,
I connected to the server on one terminal and ran the app on another.
![node](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab10/Lab10%20Images/nodeserver.png)

## Conclusion
The purpose of this lab was to learn the usage of connecting to a node server and operating on the blockchain.
