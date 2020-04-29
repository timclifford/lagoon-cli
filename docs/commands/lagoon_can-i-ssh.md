## lagoon can-i-ssh

Can I SSH will return the environment if you can access it

### Synopsis

Can I SSH will return the environment if you can access it.
This is useful if you want to quickly check if you can SSH to an environment in lagoon.

```
lagoon can-i-ssh [flags]
```

### Options

```
  -h, --help   help for can-i-ssh
```

### Options inherited from parent commands

```
      --config-file string   Path to the config file to use (must be *.yml or *.yaml)
      --debug                Enable debugging output (if supported)
  -e, --environment string   Specify an environment to use
      --force                Force yes on prompts (if supported)
  -l, --lagoon string        The Lagoon instance to interact with
      --no-header            No header on table (if supported)
      --output-csv           Output as CSV (if supported)
      --output-json          Output as JSON (if supported)
      --pretty               Make JSON pretty (if supported)
  -p, --project string       Specify a project to use
      --skip-update-check    Skip checking for updates
  -i, --ssh-key string       Specify path to a specific SSH key to use for lagoon authentication
```

### SEE ALSO

* [lagoon](lagoon.md)	 - Command line integration for Lagoon
