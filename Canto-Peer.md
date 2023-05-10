<h1 align="center"> State-Sync Peer for Canto. </h1>
To synchronize, you can use our peer by adding it to the config.toml file.

```
9f9ddc760ffeb70bfa241d7688a083f603954117@188.172.228.225:26676
```
To add the peer, you can use the following instructions:
```
PEERS=9f9ddc760ffeb70bfa241d7688a083f603954117@188.172.228.225:26676
sed -i.bak -e "s/^persistent_peers =./persistent_peers = "$PEERS"/" $HOME/.cantod/config/config.toml
```

Alternatively, you can add it manually.
Open the config.toml file with the nano editor.
```
nano .cantod/config/config.toml
```
Add the peer YTWOFUND to the "persistent_peers" line.
