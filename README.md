<img alt="nullLinux" src="media/logo.png" width="300">

**Simple linux distribution based on musl, busybox and quickInit**

**Introduction**
------------
nullLinux is a simple linux distribution based on musl, busybox and quickInit which you can build on your computer using provided scripts. 

**Features**
--------
    * own musl based toolchain
    * BusyBox utilities
    * quickInit

nullLinux is in constant development. There will be more features as long as I will have enough free time.

**Building**
-------------
If you want to build nullLinux x86_64 image:

1. Build x86_64 toolchain

```
cd toolchain
./build_toolchain x86_64_config
```

```x86_64_config``` is the file from ```toolchain/config``` directory.

2. Build nullLinux

```
cd ..
./make_img build
```

3. Run nullLinux

```
./run_qemu_x86_64
```

Default login is ```root``` without password.



[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)