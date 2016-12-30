# app list

```
Usage: cscli app list

List all applications currently running on the configured cluster.
```

Will list all the applications that are running on the configured cluster with some additional metadata about each application.

## Examples

```
cscli app list
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



