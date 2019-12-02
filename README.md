Board: 
nodeMCU V3

Sensors:
//hum+temp

GY-21
vcc - 3.3v 
scl - D1
sca - D2

//temp liquid

DS18B20
data - D4 (4.7кОм -> vcc)
vcc  - 3.3v
gnd

//soil moisture

capactive soil mois. sensor(analog)
data - A0
vcc  - 5v

//distance

HC-SR04
vcc  - 5v
echo - D6 
trig - D5

Relay:

vcc - 3.3v
pmp - D7





