# host edit

```
Usage: cscli host edit <hostId>

Edit an host configuration running on a ContainerShip Cluster.

--tag, -t       Add a tag to a host.

```

Edits an host with the specified `hostId` on your configured cluster. You can specify various properties to edit through command options.

## Examples

```
cscli host edit redis -p 7000

KEY            VALUE
engine         docker
image          library/redis:3.0.3
command        redis-server --appendonly yes
cpus           0.25
memory         64
network_mode   bridge
discovery_port 10813
container_port 7000
```

## 



