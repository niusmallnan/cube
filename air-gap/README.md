# CUBE-AIR-GAP-PROXY

This image is used for air-gap network. This image will proxy cube console `index.yml` and cube console service yml.

## How to build

```
$ cd <cube root directory>
$ make air-gap-proxy
```

## How to run
```
$ docker run -itd -p <PORT>:80 rancher/cube-air-gap-proxy:<tag>
```

Set RancherOS Repository:
```
$ ros config set rancher.repositories.cube.url http://192.168.1.153:<PORT>
```
