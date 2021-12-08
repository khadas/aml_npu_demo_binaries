### Install the libraries

```
$ sudo ./INSTALL
```

### Choose demo for MIPI camera or UVC

x11:

* MIPI: `detect_demo_x11_mipi`
* USB: `detect_demo_x11_usb`

framebuffer:

* MIPI: `detect_demo_fb_mipi`
* UVC: `detect_demo_fb_usb`


E.g For UVC:

* Yoloface demo

```
$ ./detect_demo_xx_usb -d /dev/videoX -m 0 -w 1920 -h 1080
```

* YoloV2 demo

```
$ ./detect_demo_xx_usb -d /dev/videoX -m 1 -w 1920 -h 1080
```

* YoloV3 demo

```
$ ./detect_demo_xx_usb -d /dev/videoX -m 2 -w 1920 -h 1080
```

* YoloTiny demo

```
$ ./detect_demo_xx_usb -d /dev/videoX -m 3 -w 1920 -h 1080
```

* YoloV4 demo

```
$ ./detect_demo_xx_usb -d /dev/videoX -m 4 -w 1920 -h 1080
```

default width is `1920`, default height is `1080`.
*Note: Replace /dev/videoX to the correct node.*

### Uninstall the libraries

```
$ sudo ./UNINSTALL
```

