### Install the libraries

```
$ sudo ./INSTALL
```

### Choose demo for MIPI camera or UVC

* MIPI: `detect_demo_mipi`
* UVC: `detect_demo_uvc`


E.g For UVC:

* Yoloface demo

```
$ ./detect_demo_uvc /dev/videoX 0
```

* YoloV2 demo

```
$ ./detect_demo_uvc /dev/videoX 1
```

* YoloV3 demo

```
$ ./detect_demo_uvc /dev/videoX 2
```

*Note: Replace /dev/videoX to the correct node.*

### Uninstall the libraries

```
$ sudo ./UNINSTALL
```

### Source Code

`detect_demo_uvc`: https://gitlab.com/numbqq/aml_npu_app/tree/master/detect_library/yolo_demo_gst_uvc

`detect_demo_mipi`: https://gitlab.com/numbqq/aml_npu_app/tree/master/detect_library/yolo_demo_mipi
