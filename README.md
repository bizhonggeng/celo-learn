* git clone 
* cd celo-learn
* npm install
* Replace <API KEY> in .env file with your API KEY

#1
* node connect.js
#2
* node create_account.js
* Copy address and private key from output of connect.js into .env
#3
* node query.js
#4
* Get free testnet tokens: https://celo.org/developers/faucet
* node transfer.js
* node exchange.js
#5
* npm install -g truffle
* truffle compile
* truffle migrate --network alfajores
* cd ..
* node interactions.js