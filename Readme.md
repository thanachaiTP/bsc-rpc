# Binance Smart Chain node RPC Docker image
## QuickStart
```
# mkdir -p /data/
# cd /data/
# git clone https://github.com/thanachaiTP/bsc-rpc.git bsc
# cd bsc
# docker-compose up -d
```

## Check sync status
```
# docker exec binance-smart-chain-node-rpc bsc attach --exec eth.syncing

# docker logs -f --tail=30 binance-smart-chain-node
```

# Reference
> https://github.com/vlddm/binance-smart-chain-node

> https://github.com/binance-chain/bsc
