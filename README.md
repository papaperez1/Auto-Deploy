# Auto-Deploy
```
git clone https://github.com/Svz1404/Nexus-DeployNTE.git
cd Nexus-DeployNTE
```
```
npm install dotenv ethers solc chalk ora cfonts readline-sync
```
```
nano .env
```
Update below vaiables as per your chain

RPC_URL=https://testnet-rpc.monad.xyz/
PRIVATE_KEY=<>
CHAIN_ID=10143
EXPLORER_URL=https://testnet.monadexplorer.com
CURRENCY_SYMBOL=MON
NETWORK_NAME=MONAD

```
node index.js
```
