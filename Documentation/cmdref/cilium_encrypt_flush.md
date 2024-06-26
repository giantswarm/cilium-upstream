<!-- This file was autogenerated via cilium cmdref, do not edit manually-->

## cilium encrypt flush

Flushes the current IPsec state

### Synopsis

Will cause a short connectivity disruption

```
cilium encrypt flush [flags]
```

### Options

```
  -f, --force            Skip confirmation
  -h, --help             help for flush
      --node-id string   Only delete states and policies with this node ID. Decimal or hexadecimal (0x) format. If multiple filters are used, they all apply
  -o, --output string    json| yaml| jsonpath='{}'
      --spi uint8        Only delete states and policies with this SPI. If multiple filters are used, they all apply
```

### Options inherited from parent commands

```
      --config string   Config file (default is $HOME/.cilium.yaml)
  -D, --debug           Enable debug messages
  -H, --host string     URI to server-side API
```

### SEE ALSO

* [cilium encrypt](cilium_encrypt.md)	 - Manage transparent encryption

