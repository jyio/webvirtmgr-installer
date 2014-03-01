# WebVirtMgr installer for Debian

A Debian package to install **[WebVirtMgr]**

## What this does

- Installs the latest **WebVirtMgr** to `/opt/webvirtmgr/bin`
- Creates a `webvirtmgr` user to manage `libvirt` services
- Allows `webvirtmgr` to SSH to its own account

## How to use

```Shell
dpkg-deb -b ./package
dpkg -i ./package.deb
apt-get -f install
```

## How to update

```Shell
webvirtmgr-install
```

[WebVirtMgr]: http://retspen.github.io/
