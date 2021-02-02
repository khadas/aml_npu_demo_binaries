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
$ ./detect_demo_xx_usb -d /dev/videoX -m 0
```

* YoloV2 demo

```
$ ./detect_demo_xx_usb -d /dev/videoX -m 1
```

* YoloV3 demo

```
$ ./detect_demo_xx_usb -d /dev/videoX -m 2
```

* YoloTiny demo

```
$ ./detect_demo_xx_usb -d /dev/videoX -m 3
```

* YoloV4 demo

```
$ ./detect_demo_xx_usb -d /dev/videoX -m 4
```
*Note: Replace /dev/videoX to the correct node.*

### Uninstall the libraries

```
$ sudo ./UNINSTALL
```

