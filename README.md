## XMRig

### What is it?

XMRig is the console miner provided by [XMRig](https://github.com/xmrig/xmrig).

XMRig supports Cryptonight, Cryptonight-heavy and Cryptonight-lite.

### Example usages

Replace `ARCH` for your system architecture. Available option(s): `x86_64`

- To run the container in background:

```console
$ docker run -d --name YOUR_CONTAINER_NAME yorick/xmrig:ARCH -a YOUR_ALGO -o YOUR_POOL_ADDRESS -u YOUR_USERNAME.YOUR_WORKER_NAME -p YOUR_WORKER_PASSWORD
```

- Get `xmrig` options:

```console
$ docker run --rm yorick/xmrig:ARCH
```

- To fetch logs of a container:

```console
$ docker logs YOUR_CONTAINER_NAME
```
