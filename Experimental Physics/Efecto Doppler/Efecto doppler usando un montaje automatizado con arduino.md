#dopler_effect
El experimento consiste en obtener una medición para la frecuencia como función de la velocidad. 

# Sensores y transductores
## HC-SR04

Emite 8 pulsos de 40 Hz, es decir, 8 pulsos cuadrados con una separación temporal de $\frac{1}{40}\text{s}$ entre crestas.

¿El sensor es capaz de detectar ondas con frecuencias disntintas pero cercanas a $40 \text{kHz}$? El sensor tal como está no sirve para medir lo que se requiere, ya que el output del circuito $\text{Echo}$ arroja expresamente el tiempo que tarda en recibirse la onda reflejada. Es necesario utilizar transductores en un nuevo circuito. Especialmente para el receptor 


![[Receptor]]

# Referencias
[FreqCount library](https://www.pjrc.com/teensy/td_libs_FreqCount.html)
[Model project](https://create.arduino.cc/projecthub/Klausj/doppler-effect-at-very-slow-speeds-c68f12)

How to count the difference in frecuency from pulses?
Counting pulses and its duration

#materiales 
cable naranja
dos rollos
