# host list

```
Usage: cscli host list

List all hosts currently running on the configured cluster.
```

Will list all the hosts that are running on the configured cluster with some additional metadata about each host.

## Examples

```
cscli host list

ID                                   NAME                                 START_TIME    MODE     CONTAINERS
11111111-1111-1111-1111-111111111111 11111111-1111-1111-1111-111111111111 1482684983421 follower 5
11111111-1111-1111-1111-111111111112 11111111-1111-1111-1111-111111111112 1482685053663 leader * 0
```

To find out more details about an individual application, you can run \`[cscli host show &lt;hostId&gt;](/client/host-show.md)\`.

## 



