## empowerd query staking validators

Query for all validators

### Synopsis

Query details about all validators on a network.

Example:
```bash
$ empowerd query staking validators
```

```
empowerd query staking validators [flags]
```

### Options

```
      --count-total        count total number of records in validators to query for
      --grpc-addr string   the gRPC endpoint to use for this chain
      --grpc-insecure      allow gRPC over insecure channels, if not TLS the server must use TLS
      --height int         Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help               help for validators
      --limit uint         pagination limit of validators to query for (default 100)
      --node string        \<host\>:\<port\> to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
      --offset uint        pagination offset of validators to query for
  -o, --output string      Output format (text|json) (default "text")
      --page uint          pagination page of validators to query for. This sets offset to a multiple of limit (default 1)
      --page-key string    pagination page-key of validators to query for
      --reverse            results are sorted in descending order
```

### SEE ALSO

* [empowerd query staking](empowerd_query_staking.md)	 - Querying commands for the staking module
