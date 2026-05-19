# Brother_HL2260_armhf
The driver for brother hl2260 on debian/ubuntu(arm32), learned from [alexivkin/brother-in-arms](https://github.com/alexivkin/brother-in-arms).
This repositorie includes cupswrapper and lpr, tested successfully on Ubuntu 20.04 at Hi3798MV100 device.

setup by following steps:
```bash
dpkg -i hl2260cupswrapper-3.2.0-1.armhf.deb
dpkg -i hl2260lpr-3.2.0-1.armhf.deb
```
After installation, you can use the printer as usual. If you encounter any issues, please check the printer settings and ensure that the correct driver is selected.
you will find the printer in cups pages at http://localhost:631/.
