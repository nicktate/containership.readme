# cloud cluster list

```
Usage: cscli cluster list

List all clusters that belong in the current activeOrganization.
```

Will list all clusters that belong to the `activeOrganization` that you have access to \(see `[cloud org use](/client/cloud-org-use.md)` for more information\).

## Examples

```
cscli cluster list
ID                                   NAME              PROVIDER_NAME       CREATED_AT
11111111-1111-1111-1111-111111111111 sample-cluster1   Packet              2016-12-20T11:53:43.335Z
11111111-1111-1111-1111-111111111112 sample-cluster2   Amazon Web Services 2016-12-25T16:52:44.125Z
11111111-1111-1111-1111-111111111113 sample-cluster3   Digital Ocean       2016-12-27T17:57:38.003Z
```

You can use one of the listed IDs in the \`[cloud cluster use](/client/cloud-cluster-use.md)\` command in order to set that as your active cluster. You may also find out more details about the cluster by running \`[cloud cluster show &lt;clusterId&gt;](/client/cloud-cluster-show.md)\`.

## 



