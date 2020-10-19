# Using the authpower network

## Initial configurations to setup network:
![Configuration](Screenshots/puppeth_configuration.PNG?raw=true)

## Making nodes, password: hunter
![Nodes](Screenshots/making_nodes.PNG?raw=true)

## Initializing nodes to network
![Init](Screenshots/initializing_nodes_to_network.PNG?raw=true)

## Pre-funded amount:
![Pre_Fund](Screenshots/prefund.PNG?raw=true)

## Running Nodes

* Using the following command for the first node:
```
    *./geth --datadir node1 --unlock "6Dc530431f3e4b4378795ad5d1A921886664C23c" --mine --rpc --allow-insecure-unlock
```
* In a separate terminal use the following command to run the second node, Password: 'hunter':
```
    *./geth --datadir node2 --unlock "A1c710CeCD2902F7F35c8cCF47a7a07916642eED" --mine --port 30304 --bootnodes "enode://c5ba47423a6482e2df13a46251dbb02be0ba72e059ee24bcae1019a263e67dcd21c77b6776c2d4ba2b236f47d1476ce45fc9b615d1c2a644658ace4bd66bfc29@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock
```
## Create custom node
![Custom_node](Screenshots/custom_node.PNG?raw=true)

## After creating the custom network use node1 keystore file to login and do a transaction, use password hunter
![wallet](Screenshots/wallet.PNG?raw=true)
![keystore](Screenshots/keystore.PNG?raw=true)

## Transaction went through!
![transaction](Screenshots/transaction_info.PNG?raw=true)
![transaction](Screenshots/transaction_geth.PNG?raw=true)