### Install the libraries

```
$ sudo ./INSTALL
```

### Choose demo for MIPI camera or UVC

x11:

* MIPI: `detect_demo_x11_mipi`
* USB: `detect_demo_x11_usb`

framebuffer:

* MIPI: `detect_demo_mipi_fb`
* UVC: `detect_demo_uvc_fb`


E.g For UVC:

* Yoloface demo

```
$ ./detect_demo_uvc_xx -d /dev/videoX -m 0
```

* YoloV2 demo

```
$ ./detect_demo_uvc_xx -d /dev/videoX -m 1
```

* YoloV3 demo

```
$ ./detect_demo_uvc_xx -d /dev/videoX -m 2
```

* YoloTiny demo

```
$ ./detect_demo_uvc_xx -d /dev/videoX -m 3
```

* YoloV4 demo

```
$ ./detect_demo_uvc_xx /dev/videoX 4
```
*Note: Replace /dev/videoX to the correct node.*

### Uninstall the libraries

```
$ sudo ./UNINSTALL
```

### Source Code

`detect_demo_x11`: https://gitlab.com/numbqq/aml_npu_app/tree/master/detect_library/yolo_demo_x11


`detect_demo_uvc_fb`: https://gitlab.com/numbqq/aml_npu_app/tree/master/detect_library/yolo_demo_gst_uvc_fb

`detect_demo_mipi_fb`: https://gitlab.com/numbqq/aml_npu_app/tree/master/detect_library/yolo_demo_mipi_fb
