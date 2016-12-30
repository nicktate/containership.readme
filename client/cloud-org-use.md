# cloud org use

```
Usage: cscli org use <orgId>

Show details about the provided organization.
```

The `containership cloud org use [orgId]`command will update the configuration  object by setting the \`cloud.activeOrganization\` key to the provided orgId. If that \`organization\` does not exist or if you do not have permissions to vie that organization, it will throw an error.

### Examples

```
cscli org use 11111111-1111-1111-1111-111111111111

KEY        VALUE
id         11111111-1111-1111-1111-111111111111
name       sample-org1
tier       standard
locked     false
created_at 2016-08-01T15:23:50.807Z
```

The \`~/.containership/cli-config-v2.json\` file will now be updated with the following:

```
{
    "cloud": {
        ...
        "activeOrganization": "11111111-1111-1111-1111-111111111111"
    },
    ...
}
```

## 

