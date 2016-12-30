# app scale-up

```
Usage: cscli app scale-up <appId>

--count, -c        number of containers to scale by

Scales up the number of containers running for the provided application.
```

Scales up the application with the specified `appId` on your configured cluster. If `--count, -c` is provided, scales by the provided amount, otherwise it defaults to 1.

## Examples

```
cscli app scale-up redis --count 2

Successfully scaled application redis!
```

## 



