# Galax-Blockchain-Explorer
Block explorer for Galax CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon galaxd. It should be accessible from the Internet. Run galaxd with open port as follows:
```bash
./galaxd --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
