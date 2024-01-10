# evm-tools

To install the required modules for running the script, you can use the Node Package Manager (npm) by running the following command in your terminal:

- npm install ethers fs moment chalk readline axios

As for the files used in the script:

- address.txt: This file is used to store the generated wallet addresses in the "Generate Wallets" script (Script 1). Each generated address is appended to this file.

- key.txt: This file is used to store the corresponding private keys of the generated wallets in the "Generate Wallets" script (Script 1). Each private key is appended to this file.

- key-utama.txt: This file contains the private key of the primary address used for transferring tokens in the "Transfer Tokens" script (Script 2). It is read to retrieve the private key for signing the transactions.

- sisa-saldo-{network}.txt: This file is created in the "Check Balance" script (Script 3) for each selected network. It stores the address, balance, and balance in USD for each checked address. The {network} placeholder is replaced with the network name in lowercase with spaces replaced by hyphens.
