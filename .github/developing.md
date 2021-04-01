### Development

#### Building the snap package

* Install [snapcraft](https://snapcraft.io/snapcraft) tools (onetime)
* :bulb: We will be using [lxd](https://snapcraft.io/docs/build-on-lxd) instead of `multipass`

```bash
sudo snap install snapcraft --classic
sudo snap install lxd
sudo snap install review-tools
sudo /snap/bin/lxd init --auto
```

* Build snap package
* :bulb: snap package takes deb package as source; so we need to build deb package too.

```bash
yarn run build
yarn run build:deb
yarn run build:snap
```

* Login to snapcraft (onetime)

```bash
snapcraft login
```

* Publish to store

```bash
yarn run build:snap-repack
snapcraft upload --release=stable ./*.snap
```

* Remove build artifacts

```bash
rm -rf ./dist
rm -f ./*.snap
```
