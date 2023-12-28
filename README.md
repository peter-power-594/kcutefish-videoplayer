# Cutefish Video Player

An open source video player built with Qt/QML and libmpv.

### Third Party Code

[haruna](https://github.com/g-fb/haruna)

## OpenMandriva Dependencies

```shell
sudo dnf in task-devel
sudo dnf install extra-cmake-modules (qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev) lib64mpv-devel
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

# License

This project has been licensed by GPLv3.
