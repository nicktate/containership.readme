# app create

```
Usage: cscli app create <appId>

Create an application on the configured ContainerShip Cluster.

--engine, -x   
```

Creates an application with the specified `appId` on your configured cluster. You can specify various properties for the application during creation through command options.

## Examples

```
cscli app create redis --image="library/redis:3.0.3" --memory=64 --cpus=0.25 --command="redis-server --appendonly yes" -p 6379

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



