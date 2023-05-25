<h1 align="center"> State-Sync Peer for Quicksilver. </h1>
To synchronize, you can use our peer by adding it to the config.toml file.

```
2f31e1c4cfcecc04d6f3f4b3c9b8ac63158a3bac@188.172.228.225:26646
```
To add the peer, you can use the following instructions:
```
PEERS=2f31e1c4cfcecc04d6f3f4b3c9b8ac63158a3bac@188.172.228.225:26646
sed -i.bak -e "s/^persistent_peers =./persistent_peers = "$PEERS"/" $HOME/.quicksilverd/config/config.toml
```

Alternatively, you can add it manually.
Open the config.toml file with the nano editor.
```
nano .quicksilverd/config/config.toml
```
Add the peer YTWOFUND to the "quicksilver_peers" line.
