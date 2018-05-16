# wfcminer
a full wfcminer build and run environment docker image.


### usage
1. copy `Dockerfile` to `./`
2. run `docker docker build ./ -t wfcminer:pre-release`
3. run `docker run -d --rm --name wfcminer wfcminer:pre-release minerd -o http://192.168.1.123:9665 -u test -p admin  --no-getwork -a sha256d --coinbase-addr=wiijXST1RShBC4eAo56PqXoipX1RKFQ49o -t 2`


# public image

```
docker run -d --rm --name wfcminer registry.cn-hangzhou.aliyuncs.com/wificoin-project/wfcminer:pre-release minerd -o http://192.168.1.123:9665 -u test -p admin  --no-getwork -a sha256d --coinbase-addr=wiijXST1RShBC4eAo56PqXoipX1RKFQ49o -t 2
```
