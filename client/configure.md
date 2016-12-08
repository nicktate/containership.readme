# configure

```
Usage: containership configure [OPTIONS]

Create a new container

          --api-url                       Cluster API Url to connect to
          --api-version                   Version of the core API the cluster is running
          --plugin-location               Base plugin install directory
          --strict-ssl                    Enforece strict ssl checking
```

The `containership configure` command configures your client for communication with your Containership cluster. Running configure without any arguments will start an interactive setup or you can pass one or more arguments manually.

## Examples

```
containership configure --api-url="http://localhost:8080"
```

This will update your `~/.containership/cli-config.json` file to have the following:

```
{
  "api-url": "http://localhost:8080"
}
```