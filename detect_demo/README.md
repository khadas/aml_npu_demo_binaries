### Install the libraries

```
$ sudo ./INSTALL
```

### Choose demo for MIPI camera or UVC

x11:

* MIPI: `detect_demo_mipi_x11`
* UVC: `detect_demo_uvc_x11`

framebuffer:

* MIPI: `detect_demo_mipi_fb`
* UVC: `detect_demo_uvc_fb`


E.g For UVC:

* Yoloface demo

```
$ ./detect_demo_uvc_xx /dev/videoX 0
```

* YoloV2 demo

```
$ ./detect_demo_uvc_xx /dev/videoX 1
```

* YoloV3 demo

```
$ ./detect_demo_uvc_xx /dev/videoX 2
```

*Note: Replace /dev/videoX to the correct node.*

### Uninstall the libraries

```
$ sudo ./UNINSTALL
```

### Source Code

`detect_demo_uvc_x11`: https://gitlab.com/numbqq/aml_npu_app/tree/master/detect_library/yolo_demo_gst_uvc_x11

`detect_demo_mipi_x11`: https://gitlab.com/numbqq/aml_npu_app/tree/master/detect_library/yolo_demo_mipi_x11

`detect_demo_uvc_fb`: https://gitlab.com/numbqq/aml_npu_app/tree/master/detect_library/yolo_demo_gst_uvc_fb

`detect_demo_mipi_fb`: https://gitlab.com/numbqq/aml_npu_app/tree/master/detect_library/yolo_demo_mipi_fb
