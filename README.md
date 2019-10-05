# Generating Cloud Init ISO File

This repo files used to generate `cloud-init.iso` file, to be used on many case related to cloud image initialization.

Usage:

```
genisoimage  -output cloud-init.iso -volid cidata -joliet -rock user-data meta-data
```

> One `cloud-init.iso` can be used for many cloud image

Some images can be downloaded from:

- [Debian](https://cdimage.debian.org/cdimage/cloud/)
- [Ubuntu](https://cloud-images.ubuntu.com/releases)
- [CentOS](https://cloud.centos.org/centos/7/images/)

This is minimal init config used by me, more detailed can be found at [Read The Docs](https://cloudinit.readthedocs.io/en/latest/topics/examples.html)
