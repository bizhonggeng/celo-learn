Datahub Link: https://datahub.figment.io/services/celo

* git clone https://github.com/ericet/celo-learn.git
* cd celo-learn
* npm install
* Replace < API KEY > in .env file with your API KEY

#1
* node connect.js

#2
* node create_account.js
* Copy address and private key from output of connect.js into .env

#3
* node query.js
(Hint: If you can't pass this, do #4)

#4
* Get free testnet tokens: https://celo.org/developers/faucet
* node transfer.js
* node exchange.js

#5
* npm install -g truffle
* cd celo_contract
* truffle compile
* truffle migrate --network alfajores
* cd ..
* node interactions.js
