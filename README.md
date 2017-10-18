# Cacharreo-ElectroAcustico

Asimtria.org | La Jaquer Es Cool

En el marco de la residencia de Asimtria.org en Platohedro, entre otros proyectos desarrollados, documentamos el cómo hacer los dispositovos vistos durante los talleres de Contrucción Electroacústica.

1.

En la primera etapa del ciclo de talleres Marco Valdivia brindó a los participantes unas palabras y algunos referentes teóricos acerca de qué es el mundo de la electroacústica y cómo a partir de prácticas experimentales podemos acercanos a esa materia.

 1.1. Acercamientos teóricos sobre la electroacústica. 
 
 Referentes...
 
 1.2. Construcción de Piezo-eléctrico. 
 
El piezo electrico es un dispositivo que permite la apmificación de señales por medio de la presión y/o vibración sobre sí mismo o sobre la superficie que lo soporte.
 
 Materiales 
 
  * 1 Piezo.
  * 2 cables.
  * 1 Plug de 1/4.
  
  ![Piezo Conexion](https://github.com/Noisk8/Cacharreo-ElectroAcustico/blob/master/piezo-directo.jpg)
  
Como vemos el piezo es una pieza simple que consta de dos círculos; en el centro uno blanco que es el positivo, y otro círculo amarillento que es la tierra. De ahí con la ayuda de dos cables, estaño y cautín sacamos dos terminales de los círculos que luego van conectadas al plug de 1/4 como lo indica la imagen. 
 
2. Construcción de amplificador e hidrófono.

2.1. Amplificador.

A partir de un chip Lm386 construimos un circuito electrónico que permitiera recibir la señal del piezo-electrico y amplificar la señal al mismo tiempo. 

Materiales.

* 1 Circuito Integrado Lm386.
* 1 Condensador Ceramico de 104 nf.
* 1 Condensador Electrolitico 470 uf.
* 1 Portapila de 9V.
* 1 Placa de cobre agujerada.
* 4 Cables.
* 2 Jack hembra 1/4.

![Esquematico](https://github.com/Noisk8/Cacharreo-ElectroAcustico/blob/master/Ampli-peque.png)

La función de este circuito consiste en amplificar señales. El circuito integrado Lm386 con la configuración que muestra la imagen se encarga de amplificar las señales que lleguen a él. Como podemos observar en el esquemático, la señal (en nuestro caso la del piezo eléctrico) es recibida por medio del Pin 3 (IN) y amplificada por medio del Pin 5 (OUT), el cual deberá ser conectado al parlante o sistema de amplificación. En este caso vamos a colocar 2 jacks hembras de 1/4 en los pines 3 y 5 respectivamente.


2.2. Hidrófono.

Con la premisa del piezo-eléctrico, adaptamos a éste un par de componentes de acrílico para poder usar el piezo como hidrófono.
Un hidrófono es básicamente un micrófono por medio del cual podemos capturar sonido bajo el agua o cualquier otro líquido. 

Materiales.

* 1 Piezoeléctrico con plug.
* 2 Laminas de acrílico.
* Silicona.

La construcción de dicha pieza es muy simple. Se debe colocar el piezo-eléctrico en medio de los dos trozos de acrílico, y sellarlo herméticamente con la silicona de manera que no quede ningún orificio por donde se pueda filtrar el agua.
