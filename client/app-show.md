# app show

```
Usage: cscli app show <appId>

Show details about the application running on your configured cluster.
```

List details about the provided application running on your ContainerShip Cluster.

## Examples

```
cscli app show redis

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



