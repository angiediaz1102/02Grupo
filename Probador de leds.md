### 06-02-2019
# MATERIALES 
* Placa Arduino
* Leds
* Cable para timbre 
* Pinzas de punta
* Pinzas de corte
* Protoboard
* Resistencias (En este caso la utilazada es de 220 Ohms)
# PROCEDIMIENDO
* Energizamos el sistema por medio de un cable con salida en uno de los buses del protoboard y llegada a la placa arduino en el pin de 5v. Posterior a eso conectamos el polo a tierra desde otro de los buses del protoboard hasta GND en la placa (GROUND) cerrando el sistema. En la imagen observamos el cable rojo como positivo y el negro como polo a tierra.
* Luego, unimos la resitencia con un extremo en negro (polo a tierra) y con otro a alguna pista del protoboard.
* De la misma pista que conectamos la resistencia colocsmos el cátodo del led, y en otra pista el ánodo. Para terminar el sistema de la misma pista dónde pusimos el ánodo del led hacemos un puente hasta el bus que lleva el positivo.
* Finalmente damos energía al sistema conectando por puerto USB la place de arduino.
# DIAGRAMA PICTORICO
La conexion entre la placa Arduino y la unidad del computador emitira un voltaje de 5V en este caso, suficiente para hacer que el LED se encienda. 
![1](https://github.com/angiediaz1102/02Grupo/blob/master/protoboard.png) 

# DIAGRAMA ESQUEMATICO
![1](https://github.com/angiediaz1102/02Grupo/blob/master/Sketch_esquem%C3%A1tico.png)

# FUNCIONAMIENTO 
![1](https://github.com/angiediaz1102/02Grupo/blob/master/IMG-20190210-WA0034.jpg)
#### Este es un montaje realizado en protoboard con ayuda de una placa Arduino Mega con el fin de probar un led sin necesidad de utilizar una batería común, por el contrario lo probamos con la ayuda de un puerto USB conectado del computador a la placa Arduino que seria su alimentador energético.
