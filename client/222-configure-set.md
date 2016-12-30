# configure set

```
Usage: containership configure set [cluster]

Set the cli configuration and individual cluster configurations.

--plugin-location    Local path to directory containing containership plugins for use in the CLI
--api-url            URL of the ContainerShip leader api used to interact with the cluster
--api-version        API version that the ContainerShip cluster is running
--strict-ssl         Whether or not to force ssl on requests to the cluster
```

The `containership configure` command displays your current client configuration as well as any configured ContainerShip clusters.

## Examples

```
containership configure
```

This will display your `~/.containership/cli-config-v2.json` file::

```
{
  "plugin-location": "~/.containership/plugins",
  "activeCluster": "mycluster",
  "clusters": {
    "mycluster": {
      "api-url": "http://localhost:8080"
    }
  } 
}
```

## 



