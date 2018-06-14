# Catalyst Blockchain Explorer
Block explorer for Catalyst CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon catalystd. It should be accessible from the Internet. Run catalystd with open port as follows:
```bash
./catalystd --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=18230
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
