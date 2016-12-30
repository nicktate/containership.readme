# cloud org use

```
Usage: cscli cluster use <clusterId>

Set the provided cluster as the active client cluster.
```

The `containership cloud cluster use [clusterId]`command will update the configuration object by setting the \`activeCluster\` key to the provided clusterId. If that \`cluster\` does not exist or if you do not have permissions to view that cluster, it will throw an error.

### Examples

```
cscli cluster use 11111111-1111-1111-1111-111111111111

KEY           VALUE
id            11111111-1111-1111-1111-111111111111
name          sample-cluster1
provider_name Digital Ocean
created_at    2016-12-25T16:52:44.125Z
```

The \`~/.containership/cli-config-v2.json\` file will now be updated with the following:

```
{
   "clusters": {
      "api-url": "11.111.111.11:8080",
      "api-version": "v1",
      "use-cloud": true
   }
}
```

## 



