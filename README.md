# ESP32-blinking-code
this code is for checking if the esp32 is running or not .

## First : dawnload Arduino IDE :
1- Download and install Arduino IDE on your computer.

2- After installing Arduino IDE, run the program.

3- Connect the ESP32 device to the computer.

4- Make sure that the port number on Arduino IDE is correct and the ESP32 device name is also correct.

## Second : blinking code :

1- Write this code on Arduino IDE.

```
Void setup(){
pinMode(LED_BUILLTIN,OUTPUT);

}

Void loop(){
digitalwrite( LED_BUILTIN, HIGH);
delay(1000);
digitalwrite( LED_BUILTIN, LOW);
delay(1000);

}
```
2- After writing this code verify and save the code.

3- Make sure that there is no error in the code.

4- Click upload to upload this code to the ESP32 device.

5- You will see the built-in LED blinking.
