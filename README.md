# Cutefish Video Player

An open source video player built with Qt/QML and libmpv.

### Third Party Code

[haruna](https://github.com/g-fb/haruna)

## OpenMandriva Dependencies

```shell
sudo dnf in task-devel
sudo dnf install extra-cmake-modules (qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev) lib64mpv-devel
```

## Ubuntu Dependencies

```shell
sudo apt install extra-cmake-modules qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev libmpv-dev
```

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## Uninstall

```shell
rm /usr/bin/cutefish-videoplayer
rm /usr/share/applications/cutefish-videoplayer.desktop
```

# License

This project has been licensed by GPLv3.
