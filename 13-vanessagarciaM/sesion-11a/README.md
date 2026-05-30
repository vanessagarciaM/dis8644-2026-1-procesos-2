# sesion-11a

Sobre la PCB: la máscara de soldadura protege del calor. 

Cum laude, palabra nueva que aprendí. Es una locución latina que significa "con alabanza" o "con elogio". Se utiliza en el ámbito universitario para otorgar un reconocimiento académico especial a estudiantes que se gradúan con honores o que obtienen calificaciones sobresalientes, generalmente asociada al grado de doctor. 

___

## Trabajo en clase 

Dato: revisar cuánto es el voltaje que soporta el chip. 

### Opción 1 

CD4046: es un circuito integrado CMOS que incluye un bucle de enganche de fase (PLL) y un oscilador controlado por tensión (VCO). Es ampliamente utilizado para multiplicar frecuencias, demodular señales FM y crear conversores de tensión a frecuencia. 

Opera en un rango de voltaje de 3 V a 18 V. 

NE555P: es un circuito integrado temporizador de precisión altamente versátil, fabricado por Texas Instruments, capaz de generar retardos de tiempo exactos, pulsos y oscilaciones. 

Opera en un rango de voltaje de 4,5 V a 16 V. 

CD4017: es un circuito integrado contador/divisor de décadas. Recibe pulsos de reloj (señales digitales) y activa secuencialmente sus 10 salidas (del 0 al 9), una por una. Es ampliamente utilizado para crear secuenciadores de luces, temporizadores y contadores. 

Funciona en un amplio rango, desde 3 V a 15 V (o incluso 18 V, dependiendo del fabricante). 

### Opción 2

CD4046 

CD40106: es un circuito integrado que contiene seis inversores digitales con entradas de disparo Schmitt Trigger. Su característica clave es la histéresis, que le permite filtrar el ruido de señales inestables y crear osciladores o generadores de ondas cuadradas utilizando solo un condensador y una resistencia. 

Opera en un amplio rango de 3 V a 18 V (usualmente a 9 V o 5 V). 

Realizamos los esquemáticos en KiCad con las propuestas que teníamos. 

![opcion1](./imagenes/opcion1.jpeg)
![opcion2](./imagenes/opcion2.jpeg)

___

Estándares (son importantes) 

Eurorack: es un formato estandarizado de sintetizador modular creado por Dieter Doepfer en 1995. En lugar de tener todo en un solo teclado, se construye un instrumento personalizado combinando módulos individuales (osciladores, filtros y secuenciadores) montados en un chasis o rack. 
+ Doepfer: creador del formato Eurorack. 
+ ModularGrid: es el plano arquitectónico virtual de Eurorack. Al ser un ecosistema físico donde cada módulo tiene dimensiones y consumos eléctricos estrictos, la plataforma resuelve los tres problemas principales al armar un sintetizador Eurorack real. 

Barrel_jack_switch (para la alimentación). 

SW_SPDT (interruptor). 

Audiojack 2 
+ Cambiar y poner 1, 2 y 3.

Chip L7805 (favorito de Aarón) 
+ "Quita la espuma". 
+ Regulador de voltaje. 

___

Mis comentarios y reflexiones sobre el libro Hacia una filosofía de la fotografía, de Vilém Flusser 

### Capítulo 8: El universo fotográfico 

Habla mucho de lo redundantes que son las fotografías y de cómo están tan presentes en nuestra vida cotidiana que terminamos creando una realidad propia que, de cierta manera, influye en cómo vemos el mundo. También habla sobre la diferencia entre los colores y sus significados en el antes y el ahora. Además, menciona cómo el aparato está programado y es omnisciente y omnipotente dentro de su propio universo. 

Reflexión propia: Las fotografías que vemos en los malls, en las calles y en las redes sociales muestran que estamos rodeados de imágenes por todos lados, y a veces ya no les prestamos suficiente atención. También muchas veces vivimos a través de ellas, en vez de vivir la experiencia misma. 





 




















































