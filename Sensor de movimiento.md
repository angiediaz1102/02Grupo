## 10-02-19
# MATERIALES 
* Sensor PIR para arduino
* Placa Arduino MEGA 2560
* Protoboard
* Leds
* Resistencias
* Jumpers 
# PROCEDIMIENTO
* Energizamos el protoboard por medio de un jumber con conección en los buses superior para GND e inferior para 5v de la placa.
* Luego de esto conectamos el sensor de la siguiente manera. La salida VCC la conectamos al protobard en el bus positivo, la GND al bus negativo y el componente que es la salida del medio la conectamos a la placa en uno de los puertos digitales, en el caso del diagrama esquemático en el 4.
* Para finalizar la construcción conectamos el ánodo del led a una de las entradas digitales de la placa y el cátodo a la resistencia que se una al bus de GND en el protoard.
* El circuito funciona al importar a la placa la información que programamos en Arduino IDE.
# CÓDIGO ARDUINO 
![1](https://github.com/angiediaz1102/02Grupo/blob/master/imagenes/sketch_feb12a.ino) 
# DIAGRAMA PICTORICO

![1](https://github.com/angiediaz1102/02Grupo/blob/master/imagenes/bb.png) 

# DIAGRAMA ESQUEMATICO
![1](https://github.com/angiediaz1102/02Grupo/blob/master/imagenes/esquem%C3%A1tico.png) 
# DESCRIPCION
Se realizo un sensor de movimiento en una placa arduino ,con el fin de que cuando este detectara cambios de calor, como por ejemplo cuando una persona se mueve a través de una habitación, se activara el led, lo anterior captando señales infrarojas que emite el cuerpo.
# CONSTRUCCIÓN 
![1]( https://github.com/angiediaz1102/02Grupo/blob/master/imagenes/WhatsApp%20Image%202019-02-12%20at%205.21.01%20PM.jpeg)
 Este montaje de hizo con el fin de que el led se encienda cuando sienta presencia de calor por el sensor pir  y activará el led, dependiendo de la configuración dada anteriormente este se apagará en cierto tiempo cuando deje de sentir calor.
 Es uno de los montajes para la luz de los edificios a pequeña escala, que cuando una persona va subiendo escaleras se prende sin necesidad de interruptores.
