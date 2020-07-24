this is tribunnews truffle ethereum testing environment

1. change the sourcePath and absolutePath to your current project location build/contracts parent path
2. make sure you have working environment of node version 11.6.x and npm 6.5.x
3. to run the services of truffle and ganache concurrently : npm run start
4. directory contracts : /build/contracts/Migration.json
5. address : 0xcDd8abE6E300829F9f6922E981D579108CE849De
6. transaction Hash : 0xb0ea453df174002cce6463cb4b986e04855bfa7fec6250d46b8f79338f89d21c
7. sample curl request : 
   curl -X POST --data '{"jsonrpc":"2.0","method":"eth_getTransactionByHash","params":["0xb0ea453df174002cce6463cb4b986e04855bfa7fec6250d46b8f79338f89d21c"],"id":1}' localhost:8545
8. sample curl request ether price :
   curl -X POST --data '{"jsonrpc":"2.0","method":"eth_gasPrice","params":[],"id":73}' localhost:8545
9. other sample curl request : https://eth.wiki/json-rpc/API
