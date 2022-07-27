# MidTBot ESP32

![](https://github.com/bdring/midTbot_esp32/blob/master/Docs/images/20190721_092227.jpg)

The MidTBot is a small and simple little pen plotter. All of the custom parts are 3D printed. The rest of the parts are low cost and easy to get.

The controller uses an ESP32 running Grbl_ESP32 firmware. It can be controlled via USB, Bluetooth or Wifi. You can simply upload gcode files to the unboard SD card and print.


The machine is controlled by a unique H-bot configuration, that uses a single belt. Two small stepper motors drive that belt in a special way to move in the X/Y plane. The pen is lifted by a hobby servo using a very simple and accurate mechanism.

