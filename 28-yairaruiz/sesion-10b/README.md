# sesion-10b

### Flusser, cap. 6, 7

escribir apuntes

## Apuntes en clase: 

En esta clase tomé apuntes del libro "Make electronic music from scratch" para reforzar la materia sobre los osciladores, primero anoté algo importante que sale en el libro y que mencionó el profe Aaron en la clase:

**¿Cual es la diferencia entre un dispositivo eléctrico y un electrónico?**

Ambos usan electricidad, pero filosóficamente es distinta, un dispositivo eléctrico usa la electricidad como fuente de energía y requieren un usuario quien hace el pensamiento de su función. 

un dispositivo electrónico usa electricidad como un lenguaje, además usa señales de voltaje como una forma de comunicarse consigo mismo. Utiliza cantidad diminuta de voltaje para cada función del dispositivo. 

Por ejemplo : 

+ Los circuitos eléctricos es como ver una maratón y corren en círculos 

+ Los circuitos electrónicos parecen corredores atravesando pista de obstáculos y en cada obstáculo sus cuerpos reaccionan de forma interesante e inesperada 

### Osciladores: 

**“El corazón del sintetizador es el oscilador”** se mueve de un lado al otro entre dos extremos. 

+ Oscilador electrónico: se refiere a un circuito que produce una onda repetitiva de voltaje. Se usa esa onda de voltaje para mover la frecuencia que queremos. 


### Circuito IC

Son pequeñas cajas negras llenas de resistencias, capacitores, diodos y otro componentes. 

Se numeran comenzando desde la esquina inferior izquierda y siguiendo el sentido antihorario 

+ Pendiente: Leer capitulo 06: cómo combinar osciladores 
+ Capítulo 13: 4046

## trabajo en proyecto 02 : 

Primero empezamos a investigar que chips podíamos conseguir y que onda se generaba 

+ consideramos: 

+ 40106 cmos
+ 4046 cmos (onda cuadrada)
+ 4093 (cuadrada) 
+ LM324 (onda cuadrada y triangular) 

(Las más sencillas de hacer son las cuadradas y la triangular)


Preguntando al profe Misa qué recomendación nos daba de chip para generar ondas de sierra y nos recomendó este esquemático para la primera propuesta: 

imagen 

(aca solo se considera la parte del oscilador, para nos confundirnos el profe nos ayudó a entender el esquemático específicamente del oscilador) 

imagen 


Para este oscilador necesitamos estos componentes que no tenemos: 

+ chip 40106 y LM324

+ LM741 y LM358  pueden ser una opción de  reemplazo de LM324

+ 4 DIODOS IN4148

**Tipo de onda que se genera:**

imagen 


Elegimos el 40106 y el LM324 porque permiten crear un oscilador simple y experimental. El circuito genera una onda cuadrada, pero produce variaciones attack y decay, acercándose a una onda sierra o triangular.  

Esto hace que la señal no sea completamente brusca como una onda cuadrada pura, sino que tenga transiciones más suaves que modifican el sonido.

