<h1 align="center"> State-Sync Peer for Quicksilver. </h1>
To synchronize, you can use our peer by adding it to the config.toml file.

```
415fd7164d58c248feded4a81f4ad5f67d2981ea@94.16.123.116:16696
```
To add the peer, you can use the following instructions:
```
PEERS=415fd7164d58c248feded4a81f4ad5f67d2981ea@94.16.123.116:16696
sed -i.bak -e "s/^persistent_peers =./persistent_peers = "$PEERS"/" $HOME/.quicksilverd/config/config.toml
```

Alternatively, you can add it manually.
Open the config.toml file with the nano editor.
```
nano .quicksilverd/config/config.toml
```
Add the peer YTWOFUND to the "quicksilver_peers" line.
