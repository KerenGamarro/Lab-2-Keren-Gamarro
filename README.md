# Lab 2-Keren Gamarro
Esta programacion es para controlar un contador de 4 bits y mostrar el valor de este utilizando 4 leds
Se esta utilizando un ESP32 dev module kit v.1
El contador puede contar de dos formas distintas, en decadas y en binario pero no de manera simultanea, y se cambia entre modulos utilizando un boton
Los otros dos botones aumentan o disminuyen el contador, independiente del modo en que se encuentre
Se utilizan los pines GPIO como entrada y salida

# Materiales:
- 1 protoboard
- 1 controlador ESP32
- 3 push buttons
- 4 LEDs
- Jumpers
- 4 Resistencias de 220 Ohms a 1 kOhms
- 1 Resistencia de 10 kOhms

# Requerimientos que pedia la guia:
- Todos los botones deben implementarse con anti-rebote y no deben bloquearse
entre ellos.
- Los contadores deben implementarse modificando los GPIOs.
- Cada botón debe estar conectado de forma distinta. Uno debe estar configurado
como pull-up, otro como pull-down y el último se debe implementar (ya sea pullup o pull-down) de forma física, utilizando una resistencia externa.
- El código debe entregarse debidamente comentado

# Parte A: Contador de décadas (40pts) – Entregable en Clase
- En esta parte, para el Hardware, debe implementar 4 LEDs y 2 botones para
sumar y restar al contador.
- El contador debe ser circular, es decir que no debe para al llegar al número
máximo o mínimo, sin que debe de reiniciarse.
- Ejemplo contador de décadas: https://www.youtube.com/watch?v=iL0J4uSXDk4
Parte B: Cambio de modo (20pts)
- Para esta parte debe implementar un tercer botón en su circuito, el cual funcionará
para cambiar de modo su contador.
- Recuerde que todos los botones deben contar con anti-rebote.
# Parte B: Cambio de modo (20pts)
- Para esta parte debe implementar un tercer botón en su circuito, el cual funcionará
para cambiar de modo su contador.
- Recuerde que todos los botones deben contar con anti-rebote.
# Parte C: Contador binario (40pts)
- Utilizando el mismo Hardware ya implementado, debe con código implementar el
segundo modo del contador. Este contador debe ser binario.
- Al igual que el contador anterior, este debe ser circular, es decir que no debe para
al llegar al número máximo o mínimo, sin que debe de reiniciarse. 
