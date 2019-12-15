# nvm-repro

### How to test?

Run the folling command
```console
> npm run test
```

### What happens?

The error below is thrown.

```console
nvm is not compatible with the "npm_config_prefix" environment variable: currently set to "/Users/[username]/.nvm/versions/node/[active_node_version_on_shell]"
Run `unset npm_config_prefix` to unset it.
```

### What is expected?

NVM is sourced, installed & set succesfully, after which the string `it worked` is echoed to the console.