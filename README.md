# homelab-nfs

This is a mirco-services repo for deploying
[nfs](https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner)
into [my homelab](https://github.com/charlesthomas/homelab).

## install nfs-common on the nodes

```bash
sudo apt-get install nfs-common -y
```

---
This repo is templated via
[homelab-template](https://github.com/charlesthomas/homelab-template)
and automatically updated via
[🤖 Templatron](https://github.com/charlesthomas/templatron).
