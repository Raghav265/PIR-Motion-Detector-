This is a project that is used to detect motion in a room. The components of project are: Arduino, PIR sensor, 2 resistors, jump wires and 2 LED (1 blue and  1 yellow). The connections are made as per shown in the Circuit design. 

Working: 
When the PIR sensor detects motion then LED1(blue) starts to glow till 5 seconds and the serial monitor in Arduino IDE displays a text "Motion Detected". It will keep glowing if it detects continuous motion. 
When the sensor doesn't detect any kind of motion in its atmosphere then LED1(blue) stops to glow and LED2 (yellow) starts to glow till the time there is no motion and serial monitor in Arduino IDE firstly displays "Motion Ended" followed by "Extented time HIGH ended!" in a loop.
