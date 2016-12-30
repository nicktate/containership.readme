# cloud cluster list

```
Usage: cscli cluster list

List all clusters that belong in the current activeOrganization.
```

Will list all clusters that belong to the `activeOrganization` that you have access to \(see `[cloud org use](/client/cloud-org-use.md)` for more information\).

## Examples

```
cscli cluster list
ID                                   NAME      PROVIDER_NAME       CREATED_AT
1c1f35e2-100d-45a4-bc01-a23d5056f827           Amazon Web Services
78d3afda-aaa7-412c-842d-16ca2edb1b2d CliV2Test Digital Ocean       2016-12-25T16:52:44.125Z
bfe1d564-261b-42dc-ab76-48a125130bae testing   Digital Ocean       2016-12-27T17:57:38.003Z
```

You can use one of the listed IDs in the \`[cloud org use](/client/cloud-org-use.md)\` command in order to set that as your active organization. You may also find out more details about the organization by running \`[cloud org show &lt;orgId&gt;](/client/cloud-org-show.md)\`.

## 



