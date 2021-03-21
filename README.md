# network

ref:
- https://github.com/tindy2013/subconverter/blob/master/README-cn.md
- https://github.com/lzdnico/subconverteriniexample

test:

```
CONFIG=https://raw.githubusercontent.com/zhengcan/network/clash/custom.ini

curl -G \
  --data-urlencode "target=clash" \
  --data-urlencode "url=${URL}" \
  --data-urlencode "config=${CONFIG}" \
  http://192.168.2.1:25500/sub
```

