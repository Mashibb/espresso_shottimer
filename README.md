shottimer for any machine with solenoid valve. 

hardware required:


https://spotpear.com/shop/ESP32-C3-desktop-trinket-Mini-TV-Portable-Pendant-LVGL-1.44inch-LCD-ST7735.html
+
D-z73 reed sensor (connect to pin21 and GND of esp32)

the 2 button is for adjust pre-infusion. if no pre-infusion. please set it to 0.

the counter color change during 25-30 secs.

the installation same as Luminaire Shot Timer. all you need to tie the reed sensor in solenoid valve.


this is the command to load it to the esp32
arduino-cli upload -i shot_timer.ino.bin -p COMx -b esp32:esp32:esp32c3
