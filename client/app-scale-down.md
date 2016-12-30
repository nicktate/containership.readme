# app scale-down

```
Usage: cscli app scale-down <appId>

--count, -c        number of containers to scale by

Scales down the number of containers running for the provided application.
```

Scales down the application with the specified `appId` on your configured cluster. If `--count, -c` is provided, scales by the provided amount, otherwise it defaults to 1.

## Examples

```
cscli app scale-down redis --count 2

Successfully scaled application redis!
```

## 



