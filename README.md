# redbearLearn

## Flashing Redbear with the latest Firmware

1. Install dfu-util (link: https://github.com/redbear/Duo/blob/master/docs/dfu-util_installation_guide.md) 

2. When listing the Duo devices fails, reboot your computer. 
```
$ dfu-util -l
```

2. Follow the instructions on Duo: Firmware Deployment Guide (link: https://github.com/redbear/Duo/blob/master/docs/firmware_deployment_guide.md#duo-firmware-deployment-guide), 

*Update System Firmware

*Update Factory Reset Application (FAC)

*Update Wi-Fi Firmware

3. Once it's all done, unplug and plug in the USB cable of Redbear to notice the difference. 
