# blockchain
## Server Usage
cd into src
Run Server: python3 -m block run

## Client Usage
Mine a Coin/verify transaction: curl "localhost:5000/mine"

Send a Transaction: curl "localhost:5000/txion" -H "Content-Type: application/json" -d '{"from": "test", "to":"rqasd", "amount": 10}'

View Blocks: curl "localhost:5000/blocks"
