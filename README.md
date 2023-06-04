SISTEMA EXPERTO DE POLÍGONOS.
----------------------------

Autor:  Sebastián Asunción.

Fecha:  Mayo del 2023.

Este programa esta desarrollado en Prolog (SWI-Prolog) y se ha programado un sistema experto para averiguar el tipo de polígono.
El sistema experto sólo tratará los polígonos de 3 y 4 lados, para el resto de lados solo contestara true.

El sistema realiza las siguientes preguntas:

  1-Número de lados.
  Si se contesto 3 lados, el sistema preguntará:
  
  2-Lados iguales.
  
  3-Existen ángulo recto.

  Si se contesto 4 lados, el sistema preguntará:
  
  2-Cuantos lados paralelos tiene.
  
  3-Tienen ángulo recto.
  
  4-Cuantos lados iguales tiene.
  

El sistema contestará indicando que tipo de polígono es.  Puede dar varias polígonos como respuesta.


INSTRUCCIONES BÁSICAS DE PROLOG
--------------------------------
Recordar que una vez cargado el fichero desde File --> Consult, el programa se arranca con la instrucción "solve." (recordar que en Prolog el signo punto hace que el sistema trate la instrucción introduccida y sin doble comillas).

A toda contestación que introduzcamos debera acabar con punto para que el sistema lo trate.
