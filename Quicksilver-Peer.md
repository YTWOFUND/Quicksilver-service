<h1 align="center"> State-Sync Peer for Quicksilver. </h1>
To synchronize, you can use our peer by adding it to the config.toml file.

```
835744be6c33a878118f7356426ac1c56f23f16f@94.16.123.116:26656
```
To add the peer, you can use the following instructions:
```
PEERS=835744be6c33a878118f7356426ac1c56f23f16f@94.16.123.116:26656
sed -i.bak -e "s/^persistent_peers =./persistent_peers = "$PEERS"/" $HOME/.quicksilverd/config/config.toml
```

Alternatively, you can add it manually.
Open the config.toml file with the nano editor.
```
nano .quicksilverd/config/config.toml
```
Add the peer YTWOFUND to the "quicksilver_peers" line.
