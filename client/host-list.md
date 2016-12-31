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
eae24991-68ac-41e8-bcee-314832e0c8f1 eae24991-68ac-41e8-bcee-314832e0c8f1 1482684983421 follower 5
f1fb23ce-9b3d-4f60-8fbd-4c0393d66275 f1fb23ce-9b3d-4f60-8fbd-4c0393d66275 1482685053663 leader * 0
ID                              IMAGE                                            COMMAND                       CPUS MEMORY CONTAINERS
ntpd                            containership/ntp:latest                                                       0.1  16     1/1
containership-logs              containership/docker-cs-logs:latest                                            0.1  64     1/1
containership-prometheus        containership/docker-cs-prometheus-server:latest                               0.1  320    1/1
containership-prometheus-agents containership/docker-cs-prometheus-agents:latest                               0.1  64     1/1
service-discovery               containership/service-discovery:latest                                         0.1  64     1/1
nicksapp                        containership/engine                                                           0.1  129    0/0
redis                           library/redis:3.0.3                              redis-server --appendonly yes 0.25 64     1/1
```

To find out more details about an individual application, you can run \`[cscli app show &lt;appId&gt;](/client/app-show.md)\`.

## 



