# rungeth

## 开发者模式启动
```
geth --datadir ./devdata --networkid 18 --port 30303 --rpc --rpcaddr 0.0.0.0 --rpcvhosts "*"  --rpcport 8545 --rpcapi 'db,net,eth,web3,personal' --rpccorsdomain '*'  --dev --dev.period 1 console 2> 1.log
```
