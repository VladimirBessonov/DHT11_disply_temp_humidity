# DHT11_disply_temp_humidity

Simple command line programm to disply temp and humidity measured with DHT11 from freenove ultimate starter kit for raspberry pi 4 b
rename I2CLCD1602.c to I2CLCD1602.cpp

gcc I2CLCD1602.cpp DHT.cpp DHT.hpp -o I2CLCD1602 -lwiringPi -lwiringPiDev
