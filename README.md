# ESP32 working example
this repo aims to configure and test a fully operational esp32 dev kit board.

## Precheck
Download and install Arduino IDE.  
Add your user to **dialog** and **uucp** group, mandatory to write on usb dev.
```
$ sudo usermod -a -G dialog $USER
$ sudo usermod -a -G uucp $USER
```
## Configurations
Download resources as shown in the image:  
![download-boards-manager.png](https://github.com/7eXx/DoIt-ESP32-dev-kit-example/blob/master/download-boards-manager.png?raw=true)  

Configure the usb device:  
![configure-serial.png](https://github.com/7eXx/DoIt-ESP32-dev-kit-example/blob/master/configure-serial.png?raw=true)  

# Start
Verify the scretch and upload it.  
Test if the led on board blink.  

**Warning**: make sure that upload serial speed is 115200 otherwise it give errors on upload.

