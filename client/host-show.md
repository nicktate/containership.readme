# host show

```
Usage: cscli host show <hostId>

Show details about the host running on your configured cluster.
```

List details about the provided host running on your ContainerShip Cluster.

## Examples

```
cscli app show 11111111-1111-1111-1111-111111111111

KEY            VALUE
engine         docker
image          library/redis:3.0.3
command        redis-server --appendonly yes
cpus           0.25
memory         64
network_mode   bridge
discovery_port 10813
container_port 6379
```

## 



