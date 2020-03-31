# WiFi Web Server

 A simple web server that lets you blink an LED via the web.  
 This sketch will print the IP address of your board (once connected) to the Serial monitor.  
 From there, you can open that address in a web browser.  
 to turn on and off the LED on pin 9.  

 If the IP address of your shield is yourAddress:  
 - `http://yourAddress/H` turns the LED on  
 - `http://yourAddress/L` turns it off  

 This example is written for a network using WPA encryption.  
 For WEP or WPA, change the `Wifi.begin()` call accordingly.  

 Circuit:
 * Arduino Primo or Uno WiFi Developer Edition (with WiFi Link firmware running)
 * LED attached to pin 9

## my run and Result

you can see the test clip on my youtube channel:
https://www.youtube.com/watch?v=K0I9b7xwXck
