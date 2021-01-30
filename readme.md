Clarion Windows Formater
========================

La idea de esta aplicaci�n, en desarrollo a�n, es simple.
Muchas veces nos pasa que, en una ventana, alg�n campo se visualiza con una tipograf�a distinta a la de la ventana original.
O luego de copiar y pegar controles, o de manipular manualmente el c�digo de la ventana, algo empieza a fallar.
Con este programa (en desarrollo, a�n), la idea es pegar el c�digo de la ventana, y, en funci�n de los controles actuales (y los que a futuro se vayan agregando), eliminar por busqueda y reemplazo los modificadores que pueden ser problematicos (FONT, #ORIG, #ORDINAL y #SEQ, por el momento)

Utilizaci�n
===========
- Pegar el c�digo en la ventana
- El primer bot�n, "Pre-Procesar", unifica las lineas (separadas por |)
- El bot�n "Elimina Fonts" elimina de todo el c�digo el modificador FONT
- El bot�n "Elimina Orig" elimina de todo el c�digo el modificador #ORIG
- El bot�n "Elimina Ord" elimina de todo el c�digo el modificador #ORDINAL
- El bot�n "Elimina Seq" elimina de todo el c�digo el modificador #SEQ

Luego del proceso, el texto se muestra en el campo text, y se copia al portapapeles

A futuro, pienso agregarle:
- Insertar FONT general, para la ventana
- Insertar Altura estandar de campos, por tipo de control
Y la lista esta abierta a colaboraciones y sugerencias

Tambi�n, voy a programar una versi�n similar, para Reportes.

RESPONSABILIDAD POR USO
=======================
No me hago responsable, en absoluto, por los errores que puedan generarse por el uso de esta herramienta

Historia de modificaciones
==========================
v1.0 - 30-01-2021
Versi�n Inicial