## Downloads

### Eclipse plug-ins

If you need a new Eclipse:

* download the entire
[GNU MCU Eclipse IDE for C/C++ Developers](https://github.com/gnu-mcu-eclipse/org.eclipse.epp.packages/releases)
(it includes the latest Eclipse CDT and the latest plug-ins).

To update an existing Eclipse:

* use Eclipse Marketplace:
  * go to the _Eclipse_ menu → **Help** → **Eclipse Marketplace...**
  * search **GNU MCU** 
  * install
  
* use the update site:
  * go to the _Eclipse_ menu → **Help** → **Install New Software**
  * **Add...** → **Location:** `http://gnu-mcu-eclipse.netlify.com/v4-neon-updates/`

To install older versions:

* download an archive from
[GNU MCU Eclipse plug-ins](https://github.com/gnu-mcu-eclipse/eclipse-plugins/releases)
* install from the archive
  * go to the _Eclipse_ menu → **Help** → **Install New Software**
  * **Add...** → **Archive...**

### Workspace preferences

Don't forget to set the
[workspace preferences](https://gnu-mcu-eclipse.github.io/eclipse/workspace/preferences/),
the defaults are not always right.

### Binary tools

The most convenient way to install the binary tools is via the portable
[`xpm`](https://www.npmjs.com/package/xpm) tool.

```console
$ xpm install --global @gnu-mcu-eclipse/arm-none-eabi-gcc
$ xpm install --global @gnu-mcu-eclipse/windows-build-tools
$ xpm install --global @gnu-mcu-eclipse/openocd
$ xpm install --global @gnu-mcu-eclipse/riscv-none-gcc
```

If you prefer the manual way, download the archives from:

* [GNU MCU Eclipse ARM Embedded GCC ](https://github.com/gnu-mcu-eclipse/arm-none-eabi-gcc/releases)
* [GNU MCU Eclipse Windows Build Tools](https://github.com/gnu-mcu-eclipse/windows-build-tools/releases)
* [GNU MCU Eclipse OpenOCD](https://github.com/gnu-mcu-eclipse/openocd/releases)
* [GNU MCU Eclipse RISC-V Embedded GCC ](https://github.com/gnu-mcu-eclipse/riscv-none-gcc/releases)
* [GNU ARM Eclipse QEMU](https://github.com/gnu-mcu-eclipse/qemu/releases)

Unpack the archives in:

* `%HOMEPATH%\AppData\Roaming\GNU MCU Eclipse` (on Windows)
* `$HOME/opt/gnu-mcu-eclipse` (on macOS and GNU/Linux)

> Note: although perfectly possible to install the binaries anywhere, it is
highly recommended to use this location, since by default the plug-ins search
for the executables in this location.

## Tutorials

* [Create a Blinky ARM test project](https://gnu-mcu-eclipse.github.io/tutorials/blinky-arm/)

## Issues

* [eclipse-plugins.git](https://github.com/gnu-mcu-eclipse/eclipse-plugins/)
[![GitHub issues](https://img.shields.io/github/issues/gnu-mcu-eclipse/eclipse-plugins.svg)](https://github.com/gnu-mcu-eclipse/eclipse-plugins/issues/)
[![GitHub pulls](https://img.shields.io/github/issues-pr/gnu-mcu-eclipse/eclipse-plugins.svg)](https://github.com/gnu-mcu-eclipse/eclipse-plugins/pulls/)
[![Build Status](https://travis-ci.org/gnu-mcu-eclipse/eclipse-plugins.svg?branch=develop)](https://travis-ci.org/gnu-mcu-eclipse/eclipse-plugins/) 
* [gnu-mcu-eclipse.github.io-source.git](https://github.com/gnu-mcu-eclipse/gnu-mcu-eclipse.github.io-source/)
[![GitHub issues](https://img.shields.io/github/issues/gnu-mcu-eclipse/gnu-mcu-eclipse.github.io-source.svg)](https://github.com/gnu-mcu-eclipse/gnu-mcu-eclipse.github.io-source/issues/)
[![GitHub pull](https://img.shields.io/github/issues-pr/gnu-mcu-eclipse/gnu-mcu-eclipse.github.io-source.svg)](https://github.com/gnu-mcu-eclipse/gnu-mcu-eclipse.github.io-source/pulls/)
[![Build Status](https://travis-ci.org/gnu-mcu-eclipse/eclipse-plugins.svg?branch=develop)](https://github.com/gnu-mcu-eclipse/gnu-mcu-eclipse.github.io-source/issues/) 
* [arm-none-eabi-gcc-build.git](https://github.com/gnu-mcu-eclipse/arm-none-eabi-gcc-build/)
[![GitHub issues](https://img.shields.io/github/issues/gnu-mcu-eclipse/arm-none-eabi-gcc-build.svg)](https://github.com/gnu-mcu-eclipse/rarm-none-eabi-gcc-build/issues/)
[![GitHub pulls](https://img.shields.io/github/issues-pr/gnu-mcu-eclipse/arm-none-eabi-gcc-build.svg)](https://github.com/gnu-mcu-eclipse/arm-none-eabi-gcc-build/pulls/)
* [openocd.git](https://github.com/gnu-mcu-eclipse/openocd/)
[![GitHub issues](https://img.shields.io/github/issues/gnu-mcu-eclipse/openocd.svg)](https://github.com/gnu-mcu-eclipse/openocd/issues/)
[![GitHub pulls](https://img.shields.io/github/issues-pr/gnu-mcu-eclipse/openocd.svg)](https://github.com/gnu-mcu-eclipse/openocd/pulls/)
* [openocd-build.git](https://github.com/gnu-mcu-eclipse/openocd-build/)
[![GitHub issues](https://img.shields.io/github/issues/gnu-mcu-eclipse/openocd-build.svg)](https://github.com/gnu-mcu-eclipse/openocd-build/issues/)
[![GitHub pulls](https://img.shields.io/github/issues-pr/gnu-mcu-eclipse/openocd-build.svg)](https://github.com/gnu-mcu-eclipse/openocd-build/pulls/)
* [qemu.git](https://github.com/gnu-mcu-eclipse/qemu/)
[![GitHub issues](https://img.shields.io/github/issues/gnu-mcu-eclipse/qemu.svg)](https://github.com/gnu-mcu-eclipse/qemu/issues/)
[![GitHub pulls](https://img.shields.io/github/issues-pr/gnu-mcu-eclipse/qemu.svg)](https://github.com/gnu-mcu-eclipse/qemu/pulls/)
* [qemu-build.git](https://github.com/gnu-mcu-eclipse/qemu-build/)
[![GitHub issues](https://img.shields.io/github/issues/gnu-mcu-eclipse/qemu-build.svg)](https://github.com/gnu-mcu-eclipse/qemu-build/issues/)
[![GitHub pulls](https://img.shields.io/github/issues-pr/gnu-mcu-eclipse/qemu-build.svg)](https://github.com/gnu-mcu-eclipse/qemu-build/pulls/)
* [windows-build-tools.git](https://github.com/gnu-mcu-eclipse/windows-build-tools/)
[![GitHub issues](https://img.shields.io/github/issues/gnu-mcu-eclipse/windows-build-tools.svg)](https://github.com/gnu-mcu-eclipse/windows-build-tools/issues/)
[![GitHub pulls](https://img.shields.io/github/issues-pr/gnu-mcu-eclipse/windows-build-tools.svg)](https://github.com/gnu-mcu-eclipse/windows-build-tools/pulls/)
* [riscv-none-gcc-build.git](https://github.com/gnu-mcu-eclipse/riscv-none-gcc-build/)
[![GitHub issues](https://img.shields.io/github/issues/gnu-mcu-eclipse/riscv-none-gcc-build.svg)](https://github.com/gnu-mcu-eclipse/riscv-none-gcc-build/issues/)
[![GitHub pulls](https://img.shields.io/github/issues-pr/gnu-mcu-eclipse/riscv-none-gcc-build.svg)](https://github.com/gnu-mcu-eclipse/riscv-none-gcc-build/pulls/)

(Badges from [shields.io](http://shields.io))

## Analytics

* [eclipse-plugins.git](https://github.com/gnu-mcu-eclipse/eclipse-plugins/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/eclipse-plugins/latest/total.svg)](https://github.com/gnu-mcu-eclipse/eclipse-plugins/releases/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/eclipse-plugins/total.svg)](https://github.com/gnu-mcu-eclipse/eclipse-plugins/releases/) [![Eclipse Marketplace](https://img.shields.io/eclipse-marketplace/dt/gnu-mcu-eclipse.svg?label=marketplace)](https://github.com/gnu-mcu-eclipse/eclipse-plugins/)
* [org.eclipse.epp.packages.git](https://github.com/gnu-mcu-eclipse/org.eclipse.epp.packages/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/org.eclipse.epp.packages/latest/total.svg)](https://github.com/gnu-mcu-eclipse/org.eclipse.epp.packages/releases/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/org.eclipse.epp.packages/total.svg)](https://github.com/gnu-mcu-eclipse/org.eclipse.epp.packages/releases/)
* [arm-none-eabi-gcc.git](https://github.com/gnu-mcu-eclipse/arm-none-eabi-gcc/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/arm-none-eabi-gcc/latest/total.svg)](https://github.com/gnu-mcu-eclipse/arm-none-eabi-gcc/releases/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/arm-none-eabi-gcc/total.svg)](https://github.com/gnu-mcu-eclipse/arm-none-eabi-gcc/releases/)
* [openocd.git](https://github.com/gnu-mcu-eclipse/openocd/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/openocd/latest/total.svg)](https://github.com/gnu-mcu-eclipse/openocd/releases/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/openocd/total.svg)](https://github.com/gnu-mcu-eclipse/openocd/releases/)
* [qemu.git](https://github.com/gnu-mcu-eclipse/qemu/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/qemu/latest/total.svg)](https://github.com/gnu-mcu-eclipse/qemu/releases/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/qemu/total.svg)](https://github.com/gnu-mcu-eclipse/qemu/releases/)
* [windows-build-tools.git](https://github.com/gnu-mcu-eclipse/windows-build-tools/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/windows-build-tools/latest/total.svg)](https://github.com/gnu-mcu-eclipse/windows-build-tools/releases/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/windows-build-tools/total.svg)](https://github.com/gnu-mcu-eclipse/windows-build-tools/releases/)
* [riscv-none-gcc.git](https://github.com/gnu-mcu-eclipse/riscv-none-gcc/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/riscv-none-gcc/latest/total.svg)](https://github.com/gnu-mcu-eclipse/riscv-none-gcc/releases/)
[![Github All Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/riscv-none-gcc/total.svg)](https://github.com/gnu-mcu-eclipse/riscv-none-gcc/releases/)

## xPacks

GNU MCU Eclipse

* [@gnu-mcu-eclipse/arm-none-eabi-gcc](https://github.com/gnu-mcu-eclipse/arm-none-eabi-gcc-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@gnu-mcu-eclipse/arm-none-eabi-gcc.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/arm-none-eabi-gcc/)
[![npm](https://img.shields.io/npm/dw/@gnu-mcu-eclipse/arm-none-eabi-gcc.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/arm-none-eabi-gcc/)
[![npm](https://img.shields.io/npm/dt/@gnu-mcu-eclipse/arm-none-eabi-gcc.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/arm-none-eabi-gcc/)
* [@gnu-mcu-eclipse/windows-build-tools](https://github.com/gnu-mcu-eclipse/windows-build-tools-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@gnu-mcu-eclipse/windows-build-tools.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/windows-build-tools/)
[![npm](https://img.shields.io/npm/dw/@gnu-mcu-eclipse/windows-build-tools.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/windows-build-tools/)
[![npm](https://img.shields.io/npm/dt/@gnu-mcu-eclipse/windows-build-tools.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/windows-build-tools/)
* [@gnu-mcu-eclipse/openocd](https://github.com/gnu-mcu-eclipse/openocd-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@gnu-mcu-eclipse/openocd.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/openocd/)
[![npm](https://img.shields.io/npm/dw/@gnu-mcu-eclipse/openocd.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/openocd/)
[![npm](https://img.shields.io/npm/dt/@gnu-mcu-eclipse/openocd.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/openocd/)
* [@gnu-mcu-eclipse/riscv-none-gcc](https://github.com/gnu-mcu-eclipse/riscv-none-gcc-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@gnu-mcu-eclipse/riscv-none-gcc.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/riscv-none-gcc/)
[![npm](https://img.shields.io/npm/dw/@gnu-mcu-eclipse/riscv-none-gcc.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/riscv-none-gcc/)
[![npm](https://img.shields.io/npm/dt/@gnu-mcu-eclipse/riscv-none-gcc.svg)](https://www.npmjs.com/package/@gnu-mcu-eclipse/riscv-none-gcc/)

µOS++

* [@micro-os-plus/startup](https://github.com/micro-os-plus/startup-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/startup.svg)](https://www.npmjs.com/package/@micro-os-plus/startup/)
[![npm](https://img.shields.io/npm/dw/@micro-os-plus/startup.svg)](https://www.npmjs.com/package/@micro-os-plus/startup/)
[![npm](https://img.shields.io/npm/dt/@micro-os-plus/startup.svg)](https://www.npmjs.com/package/@micro-os-plus/startup/)
* [@micro-os-plus/c-libs](https://github.com/micro-os-plus/c-libs-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/c-libs.svg)](https://www.npmjs.com/package/@micro-os-plus/c-libs/)
[![npm](https://img.shields.io/npm/dw/@micro-os-plus/c-libs.svg)](https://www.npmjs.com/package/@micro-os-plus/c-libs/)
[![npm](https://img.shields.io/npm/dt/@micro-os-plus/c-libs.svg)](https://www.npmjs.com/package/@micro-os-plus/c-libs/)
* [@micro-os-plus/cpp-libs](https://github.com/micro-os-plus/cpp-libs-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/cpp-libs.svg)](https://www.npmjs.com/package/@micro-os-plus/cpp-libs/)
[![npm](https://img.shields.io/npm/dw/@micro-os-plus/cpp-libs.svg)](https://www.npmjs.com/package/@micro-os-plus/cpp-libs/)
[![npm](https://img.shields.io/npm/dt/@micro-os-plus/cpp-libs.svg)](https://www.npmjs.com/package/@micro-os-plus/cpp-libs/)
* [@micro-os-plus/diag-trace](https://github.com/micro-os-plus/diag-trace-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/diag-trace.svg)](https://www.npmjs.com/package/@micro-os-plus/diag-trace/)
[![npm](https://img.shields.io/npm/dw/@micro-os-plus/diag-trace.svg)](https://www.npmjs.com/package/@micro-os-plus/diag-trace/)
[![npm](https://img.shields.io/npm/dt/@micro-os-plus/diag-trace.svg)](https://www.npmjs.com/package/@micro-os-plus/diag-trace/)
* [@micro-os-plus/riscv-arch](https://github.com/micro-os-plus/riscv-arch-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/riscv-arch.svg)](https://www.npmjs.com/package/@micro-os-plus/riscv-arch/)
[![npm](https://img.shields.io/npm/dw/@micro-os-plus/riscv-arch.svg)](https://www.npmjs.com/package/@micro-os-plus/riscv-arch/)
[![npm](https://img.shields.io/npm/dt/@micro-os-plus/riscv-arch.svg)](https://www.npmjs.com/package/@micro-os-plus/riscv-arch/)

SiFive

* [@sifive/templates](https://github.com/micro-os-plus/sifive-templates-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@sifive/templates.svg)](https://www.npmjs.com/package/@sifive/templates/)
[![npm](https://img.shields.io/npm/dw/@sifive/templates.svg)](https://www.npmjs.com/package/@sifive/templates/)
[![npm](https://img.shields.io/npm/dt/@sifive/templates.svg)](https://www.npmjs.com/package/@sifive/templates/)
* [@sifive/devices](https://github.com/micro-os-plus/sifive-devices-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@sifive/devices.svg)](https://www.npmjs.com/package/@sifive/devices/)
[![npm](https://img.shields.io/npm/dw/@sifive/devices.svg)](https://www.npmjs.com/package/@sifive/devices/)
[![npm](https://img.shields.io/npm/dt/@sifive/devices.svg)](https://www.npmjs.com/package/@sifive/devices/)
* [@sifive/hifive1-board](https://github.com/micro-os-plus/sifive-hifive1-board-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@sifive/hifive1-board.svg)](https://www.npmjs.com/package/@sifive/hifive1-board/)
[![npm](https://img.shields.io/npm/dw/@sifive/hifive1-board.svg)](https://www.npmjs.com/package/@sifive/hifive1-board/)
[![npm](https://img.shields.io/npm/dt/@sifive/hifive1-board.svg)](https://www.npmjs.com/package/@sifive/hifive1-board/)
* [@sifive/arty-boards](https://github.com/micro-os-plus/sifive-arty-boards-xpack/)
[![npm (scoped)](https://img.shields.io/npm/v/@sifive/arty-boards.svg)](https://www.npmjs.com/package/@sifive/arty-boards/)
[![npm](https://img.shields.io/npm/dw/@sifive/arty-boards.svg)](https://www.npmjs.com/package/@sifive/arty-boards/)
[![npm](https://img.shields.io/npm/dt/@sifive/arty-boards.svg)](https://www.npmjs.com/package/@sifive/arty-boards/)

## NPM modules

* [xpm](https://github.com/xpack/xpm-js/)
[![npm](https://img.shields.io/npm/v/xpm.svg)](https://www.npmjs.com/package/xpm/)
[![npm](https://img.shields.io/npm/dw/xpm.svg)](https://www.npmjs.com/package/xpm/)
[![npm](https://img.shields.io/npm/dt/xpm.svg)](https://www.npmjs.com/package/xpm/)
* [xmake](https://github.com/xpack/xmake-js/)
[![npm](https://img.shields.io/npm/v/xmake.svg)](https://www.npmjs.com/package/xmake/)
[![npm](https://img.shields.io/npm/dw/xmake.svg)](https://www.npmjs.com/package/xmake/)
[![npm](https://img.shields.io/npm/dt/xmake.svg)](https://www.npmjs.com/package/xmake/)
