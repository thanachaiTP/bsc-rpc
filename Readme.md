# Binance Smart Chain node RPC Docker image
## Install docker and docker-compose
```
# curl https://get.docker.com | sh
# curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
# chmod +x /usr/local/bin/docker-compose
```

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

> https://docs.docker.com/compose/install/
