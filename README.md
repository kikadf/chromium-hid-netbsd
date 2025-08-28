# chromium-hid-netbsd
Chromium HID support for NetBSD. Based on OpenBSD's fido and the FreeBSD backends, used libudev-bsd.

To use chromium-hid-netbsd deploy the files to the chromium source's services/device/hid folder and add use_udev=true to GN_ARGS.
