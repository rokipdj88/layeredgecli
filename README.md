copy and paste
```
wget https://github.com/rokipdj88/layeredgecli/raw/main/auto.sh -O auto.sh && chmod +x auto.sh && ./auto.sh
```

```
cd $HOME/light-node/
screen -S lightnode
```

```
nano .env
```

```
GRPC_URL=34.31.74.109:9090
CONTRACT_ADDR=cosmos1ufs3tlq4umljk0qfe8k5ya0x6hpavn897u2cnf9k0en9jr7qarqqt56709
ZK_PROVER_URL=http://127.0.0.1:3001
API_REQUEST_TIMEOUT=100
POINTS_API=http://127.0.0.1:8080
PRIVATE_KEY='your-cli-node-private-key'
```

save it

```
go build
./light-node
```
