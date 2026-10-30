# Grade9-Distance-Warning

Ultrasonic distance warning system gamit ang Arduino Uno at HC-SR04 sensor.

## Wokwi Simulation Link
https://wokwi.com/projects/479264168866872321
## Paano Gumagana
Ang TRIG pin ay nagpapadala ng ultrasonic pulse. Tinatanggap naman ito ng ECHO pin. Binibilang ng pulseIn() ang oras ng pagbalik ng tunog upang makalkula ang distansya sa cm. Kapag ang distansya ay mas mababa sa 30 cm, mag-o-ON ang warning LED.
