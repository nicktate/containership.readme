# configure

```
Usage: containership configure

View the current client configuration.
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



 

