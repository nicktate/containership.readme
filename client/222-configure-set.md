# configure set

```
Usage: containership configure set [cluster]

Set the cli configuration and individual cluster configurations.

--plugin-location Location 
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