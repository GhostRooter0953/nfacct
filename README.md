# nfacct

The role installs and configures nfacct

## Usage (examples)

### Minimal

```yaml
    - role: nfacct
```

### With some lists

```yaml
    - role: nfacct
      nfacct_lists:
        - http-v4
        - http-v6
```

## Available parameters

### Main

| Param | Default | Description |
| -------- | -------- | -------- |
| `nfacct_setup` | `full` | Setup mode |
| `nfacct_lists` | `[]` | Lists to add |

## Useful links

- [Official Docs](https://www.netfilter.org/projects/nfacct/index.html)

## TODO

- ...
