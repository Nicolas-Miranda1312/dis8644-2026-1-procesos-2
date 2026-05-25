# sesion-11b
Falte a esta clase, ya que estaba y estoy muy enferma 
ese día tuve fiebre:(pipipi

Busque información sobre osciladores y el chip 4046. 
también vi info en https://hackaday.com/2015/08/07/logic-noise-4046-voltage-controlled-oscillator-part-one/
## Oscilador 
Un oscilador convierte corriente continua en alterna con una frecuencia y forma de onda específicas. Es como un metrónomo electrónico: sincroniza microprocesadores, genera tonos musicales o porta señales de radiofrecuencia.

Modificación del oscilador 
-La idea es reemplazarlo o ajustarlo usando el chip 4046.

## Chip 4046 (PLL – Phase Locked Loop)

![4046](./imagenes/4046.png).

-Es un circuito integrado CMOS que incluye un oscilador controlado por voltaje (VCO) y dos comparadores de fase.

-El VCO se controla con un voltaje en el pin 9 y entrega la salida en el pin 4.

-El PLL compara la frecuencia de entrada con la del VCO interno y ajusta el voltaje para mantenerlas sincronizadas.

-Puede generar ondas cuadradas sincronizadas con la señal externa, pero también permite multiplicar la frecuencia.

-El consumo es bajo (micropower)

## Aplicaciones típicas del 4046

-Generar osciladores estables que se ajustan automáticamente a una referencia.

-Multiplicación de frecuencia (por ejemplo, tomar una señal y obtener otra más rápida).

-Demodulación de FM

-Generación de tonos digitales.

-Circuitos de reloj en sistemas digitales.

-El capacitor y la resistencia conectados al VCO definen el rango de frecuencia.

-El pin 9 recibe el voltaje de control: variando este voltaje se cambia la frecuencia de salida. El pin 4 entrega la señal oscilada (onda cuadrada).

Los comparadores de fase permiten sincronizar con una señal externa si se quiere “enganchar” el oscilador a otra fuente.

Para usarlo como oscilador independiente, basta con configurar el VCO con los componentes externos adecuados.

Cap 6 y 7 
