# cloud org list

    Usage: containership org list

    List all organizations that you have access to on ContainerShip Cloud.

The supported \`scm\` arguments are currently \`github\` and \`bitbucket\`.

## Examples

```
containership cloud login github
Please enter your github credentials to login:
Your username or email: developer@containership.io
Your password: ******
```

This will update your client configuration file at `~/.containership/cli-config-v2.json` to include the \`cloud\` key set with a ContainerShip authentication token. This will be used in any authentication calls that interact with the cloud api.

```
"cloud": {
    "token": "****************"
}
```

## 



