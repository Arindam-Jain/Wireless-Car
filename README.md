# Wireless-Car
Car is controlled using Arduino and Bluetooth module

1) Load Arduino.ino File in Arduino 
2) Before running rc_control_test.py file check Serial port in Arduino in Tools-> Port      
self.ser = serial.Serial("/dev/cu.HC05_SLAVE-DevB", 115200, timeout=1)
                                     |
                               This Value        
                                 
