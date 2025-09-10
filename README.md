# chromium-hid-netbsd

HID support for Chromium on NetBSD. Based on OpenBSD’s *fido* and the FreeBSD backends, and uses [libudev-bsd](https://github.com/kikadf/libudev-bsd).

## Usage

1. Copy the files into Chromium’s `services/device/hid` directory.  
2. Add `use_udev=true` to your `GN_ARGS`.  