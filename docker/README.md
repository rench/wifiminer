# wfcminer
a full wfcminer build and run environment docker image.


### usage
1. copy `Dockerfile` to `./`
2. run `docker docker build ./ -t wfcminer:latest`
3. run `docker run -d --rm --name wfcminer wfcminer:latest minerd -o http://x.x.x.x:9665 -u test -p admin  --no-getwork -a sha256d --coinbase-addr=wiijXST1RShBC4eAo56PqXoipX1RKFQ49o -t 2`


# public image

```
docker run -d --rm --name wfcminer registry.cn-hangzhou.aliyuncs.com/wificoin-project/wfcminer:latest minerd -o http://x.x.x.x:9665 -u test -p admin  --no-getwork -a sha256d --coinbase-addr=wiijXST1RShBC4eAo56PqXoipX1RKFQ49o -t 2
```
`x.x.x.x` General fill in your local LAN IP address.

`--coinbase-addr` The following address must be replaced with your own wfc address.