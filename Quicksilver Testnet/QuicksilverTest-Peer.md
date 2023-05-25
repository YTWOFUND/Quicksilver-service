<h1 align="center"> State-Sync Peer for Quicksilver. </h1>
To synchronize, you can use our peer by adding it to the config.toml file.

```
97b305b91092202eb8ee143f93ae2a0fb7c5d2c8@188.172.228.225:26696
```
To add the peer, you can use the following instructions:
```
PEERS=97b305b91092202eb8ee143f93ae2a0fb7c5d2c8@188.172.228.225:26696
sed -i.bak -e "s/^persistent_peers =./persistent_peers = "$PEERS"/" $HOME/.quicksilverd/config/config.toml
```

Alternatively, you can add it manually.
Open the config.toml file with the nano editor.
```
nano .quicksilverd/config/config.toml
```
Add the peer YTWOFUND to the "quicksilver_peers" line.
