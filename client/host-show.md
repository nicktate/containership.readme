# host show

```
Usage: cscli host show <hostId>

Show details about the host running on your configured cluster.
```

List details about the provided host running on your ContainerShip Cluster.

## Examples

```
cscli app show 11111111-1111-1111-1111-111111111111

KEY              VALUE
host_name        11111111-1111-1111-1111-111111111111
start_time       1482684983421
mode             follower
port             2777
public_ip        111.111.111.111
private_ip       10.136.111.111
tags             custom_tag => value1, custom_tag2 => value2
available_cpus   0.5
used_cpus        0.5
available_memory 255.01230430603027
used_memory      688
```

## 



