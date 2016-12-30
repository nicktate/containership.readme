# configure set

```
Usage: containership configure set [cluster]

Set the cli configuration and individual cluster configurations.

--plugin-location    Local path to directory containing containership plugins for use in the CLI
--api-url            URL of the ContainerShip leader api used to interact with the cluster
--api-version        API version that the ContainerShip cluster is running
--strict-ssl         Whether or not to force ssl on requests to the cluster
```

The `containership configure set [cluster]` command will create a configuration object 

## Examples

```
containership configure set mycluster --api-url http://localhost:8080 --plugin-location ~/.containership/plugins
```

This will update your client configuration file at `~/.containership/cli-config-v2.json` to include the following:

```
{
  "plugin-location": "~/.containership/plugins",
  "activeCluster": "mycluster",
  "clusters": {
    "mycluster": {
      "api-url": "http://localhost:8080",
      "api-version": "v1"
    }
  } 
}
```

## 



