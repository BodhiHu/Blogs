# Tech Issues

> Grow 🌳🌳🌳 Grow **BodhiCitta**

#### proxy.golang.org timeout
```
$ go env -w GOPROXY=https://goproxy.cn
```

## Docker

#### \[Windows WSL2\] Ports are not available: unable to list exposed ports: Get "http://unix/forwards/list"

```
netsh winsock reset
# then restart Windows
```
