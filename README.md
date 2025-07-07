ZFS real time cache activity monitor
====================================

Python script for monitoring ZFS caches efficiency


Installation
-------------

Clone the repo and run `python -m build`. Then install the package with `pip`.

```shell
git clone https://github.com/mbottini/zfs-mon.git
cd zfs-mon
python -m build
python -m pip install ./dist/zfs_mon-1.0-py3-none-any.whl
```

Another alternative is to build the Debian package, which can be done by running

```shell
dpkg-buildpackage -us -uc
```

inside the `zfs-mon` repository and then installing the resulting `.deb` package with APT.

After installation you may run command - `zfs-mon` and watch for ZFS cache activity.

```shell
zfs-mon
```
