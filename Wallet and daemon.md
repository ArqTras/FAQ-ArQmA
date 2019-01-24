# **Copyright 2018-2019 The ArQma Project**

## The ArQmA Project - Secured Digital Currency

#### Basic options
1. arqmad
2. arqma-wallet-cli
3. arqma-wallet-rpc

#####  1. ArQmA windows Daemon options
Arqma Devils Gate (v0.2-Tagged_Release::cd4f554)

Usage: arqmad [options|settings] [daemon_command...]

Options:
`  --help Produce help message`
`--version Output version information`
`--os-version OS for which this executable was compiled`
`--config-file arg (=Patch to your config file arqma.conf)`

Specify configuration file
` --install-service                     Install Windows service`
`--uninstall-service                   Uninstall Windows service`
`--start-service                       Start Windows service`
`--stop-service                        Stop Windows service`

Settings:
`--log-file arg (=C:\Users\Your_Username\AppData\Roaming\arqma\arqma.log, C:\Users\Your_Username\AppData\Roaming\arqma\testnet\arqma.log if testnet, C:\Users\Your_Username\AppData\Roaming\arqma\stagenet\arqma.log if stagenet)`

Specify log file
` --log-level arg`
`--max-log-file-size arg (=104850000)  Specify maximum log file size [B]`
`--max-concurrency arg (=0) Max number of threads to use for a parallel job`
`--zmq-rpc-bind-ip arg (=127.0.0.1)    IP for ZMQ RPC server to listen on`
`--zmq-rpc-bind-port arg (=19995, 29995 if testnet, 39995 if stagenet) Port for ZMQ RPC server to listen on`
 `--data-dir arg (=C:\ProgramData\arqma, C:\ProgramData\arqma\testnet if testnet, C:\ProgramData\arqma\stagenet if stagenet)`

Specify data directory
`--test-drop-download For net tests: in download, discard ALL blocks instead checking/saving them (very fast)`
`--test-drop-download-height arg (=0)  Like test-drop-download but discards only after around certain height`
`--testnet Run on testnet. The wallet must be launched with --testnet flag.`
`--stagenet Run on stagenet. The wallet must be launched with --stagenet flag.`
`--regtest Run in a regression testing mode.`
`--fixed-difficulty arg (=0) Fixed difficulty used for testing.`
`--enforce-dns-checkpointing checkpoints from DNS server will be enforced - Obsolete. ON by Default`
`--prep-blocks-threads arg (=4) Max number of threads to use when preparing block hashes in groups.`
`--fast-block-sync arg (=1) Sync up most of the way by using embedded, known block hashes.`
`--show-time-stats arg (=0) Show time-stats when processing blocks/txs and disk synchronization.`
`--block-sync-size arg (=0) How many blocks to sync at once during chain synchronization (0 = adaptive).`
`--check-updates arg (=notify) Check for new versions of arqma:[disabled|notify|download|update]`
`--fluffy-blocks Relay blocks as fluffy blocks (obsolete, now default)`
`--no-fluffy-blocks Relay blocks as normal blocks`
`--test-dbg-lock-sleep arg (=0) Sleep time in ms, defaults to 0 (off), used to debug before/after locking mutex. Values 100 to 1000 are good for tests.`
`--offline Do not listen for peers, nor connect to any`
`--disable-dns-checkpoints Do not retrieve checkpoints from DNS`
`--max-txpool-size arg (=648000000) Set maximum txpool size in bytes.`
`--block-notify arg Run a program for each new block, '%s' will be replaced by the block hash`
`--extra-messages-file arg Specify file for extra messages to include into coinbase transactions`
`--start-mining arg Specify wallet address to mining for`
`--mining-threads arg Specify mining threads count`
`--bg-mining-enable enable/disable background mining`
`--bg-mining-ignore-battery if true, assumes plugged in when unable to query system power status`
`--bg-mining-min-idle-interval arg Specify min lookback interval in seconds for determining idle state`
`--bg-mining-idle-threshold arg Specify minimum avg idle percentage over lookback interval`
`--bg-mining-miner-target arg Specify maximum percentage cpu use by miner(s)`
`--db-type arg (=lmdb) Specify database type, available: lmdb`
`--db-sync-mode arg (=fast:async:250000000bytes) Specify sync option, using format [safe|fast|fastest]:[sync|async]:[<nblocks_per_sync>[blocks]|<nbytes_per_sync> [bytes]].`
`--db-salvage Try to salvage a blockchain database if it seems corrupted`
`--p2p-bind-ip arg (=0.0.0.0) Interface for p2p network protocol`
`--p2p-bind-port arg (=19993, 29993 if 'testnet', 39993 if 'stagenet') Port for p2p network protocol`
`--p2p-external-port arg (=0) External port for p2p network protocol (if port forwarding used with NAT)`
`--allow-local-ip Allow local ip add to peer list, mostly in debug purposes`
`--add-peer arg Manually add peer to local peerlist`
`--add-priority-node arg Specify list of peers to connect to and attempt to keep the connection open`
`--add-exclusive-node arg Specify list of peers to connect to only. If this option is given the options add-priority-node and seed-node are ignored`
`--seed-node arg Connect to a node to retrieve peer addresses, and disconnect`
`--hide-my-port  Do not announce yourself as peerlist candidate`
`--no-igd Disable UPnP port mapping`
`--out-peers arg (=48) set max number of out peers`
`--in-peers arg (=24) set max number of in peers`
`--tos-flag arg (=-1) set TOS flag`
`--limit-rate-up arg (=6144) set limit-rate-up [Kbps]`
`--limit-rate-down arg (=24576) set limit-rate-down [Kbps]`
`--limit-rate arg (=-1) set limit-rate [kbps]`
`--save-graph Save data for dr Arqma`
`--rpc-bind-port arg (=19994, 29994 if 'testnet', 39994 if 'stagenet') Port for RPC server`
`--rpc-restricted-bind-port arg        Port for restricted RPC server`
`--restricted-rpc                      Restrict RPC to view only commands and do not return privacy sensitive data in RPC calls`
`--bootstrap-daemon-address arg        URL of a 'bootstrap' remote daemon that the connected wallets can use while this daemon is still not fully synced`
`--bootstrap-daemon-login arg          Specify username:password for the bootstrap daemon login`
`--rpc-bind-ip arg (=127.0.0.1)        Specify IP to bind RPC server`
`--rpc-login arg                       Specify username[:password] required RPC server`
`--confirm-external-bind               Confirm rpc-bind-ip value is NOT a loopback (local) IP`
`--rpc-access-control-origins arg      Specify a comma separated list of origins to allow cross origin resource sharing`
