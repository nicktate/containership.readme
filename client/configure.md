# configure

```
Usage: containership configure

View the current client configuration.
```

The `containership configure` command displays your current client configuration as well as any configured ContainerShip clusters.

## Examples

```
containership configure set mycluster --api-url="http://localhost:8080"
```

This will update your `~/.containership/cli-config-v2.json` file to have the following cluster configuration:

```
{
  "clusters": {
    "mycluster": {
      "api-url": "http://localhost:8080"
    }
  } 
}
```



