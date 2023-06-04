SISTEMA EXPERTO DE POL�GONOS
----------------------------

Autor:  Sebasti�n Asunci�n.
Fecha:  Mayo del 2023.

Este programa esta desarrollado en Prolog (SWI-Prolog) y se ha programado un sistema experto para averiguar el tipo de pol�gono.
El sistema experto s�lo tratar� los pol�gonos de 3 y 4 lados, para el resto de lados solo contestara true.

El sistema realiza las siguientes preguntas:
  N�mero de lados.
  Si se contesto 3 lados, el sistema preguntar�:
     Lados iguales.
     Existen �ngulo recto.

  Si se contesto 4 lados, el sistema preguntar�:
     Cuantos lados paralelos tiene.
     Tienen �ngulo recto.
     Cuantos lados iguales tiene.

El sistema contestar� indicando que tipo de pol�gono es.  Puede dar varias pol�gonos como respuesta.


INSTRUCCIONES B�SICAS DE PROLOG
--------------------------------
Recordar que una vez cargado el fichero desde File --> Consult, el programa se arranca con la instrucci�n "solve." (recordar que
en Prolog el signo punto hace que el sistema trate la instrucci�n introduccida y sin doble comillas).
A toda contestaci�n que introduzcamos debera acabar con punto para que el sistema lo trate.