# cloud login

```
Usage: containership cloud login <scm>

Login with an `scm` that you have registered through ContainerShip Cloud.
```

The `containership configure use [cluster]` command will update the configuration configuration object by setting the \`activeCluster\` key to the provided cluster name. If that \`cluster\` configuration has not been created, \`configure use\` will throw an error.

## Examples

```
containership configure use mycluster
```

This will update your client configuration file at `~/.containership/cli-config-v2.json` to include the `activeCluster` attribute set to the provided cluster.

```
{
  ...
  "activeCluster": "mycluster",
  ... 
}
```

## 



