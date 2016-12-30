# app edit

```
Usage: cscli app edit <appId>

Edit an application configuration running on a ContainerShip Cluster.

--engine, -x        Engine used to start the application
--image, -i         Docker image used for the application
--env-var, -e       Default environment variable to set in the application
--network-mode, -n  Application network mode (bridged or host)
--container-port, -p    Port that the application listens on
--command, -s           Custom command to run the application with
--volume, -b            Volume to mount from the host machine into the application container
--tag, -t               Tags to add to an application
--cpus, -c              CPUs allocated to an application
--memory, -m            Memory (mb) allocated to the application
--privileged            Run the application containers in privileged mode
--respawn               Respawn application containers when they die
```

Edits an application with the specified `appId` on your configured cluster. You can specify various properties to edit through command options.

## Examples

```
cscli app edit redis -p 7000

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



