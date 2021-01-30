Clarion Windows Formater
========================

La idea de esta aplicación, en desarrollo aún, es simple.
Muchas veces nos pasa que, en una ventana, algún campo se visualiza con una tipografía distinta a la de la ventana original.
O luego de copiar y pegar controles, o de manipular manualmente el código de la ventana, algo empieza a fallar.
Con este programa (en desarrollo, aún), la idea es pegar el código de la ventana, y, en función de los controles actuales (y los que a futuro se vayan agregando), eliminar por busqueda y reemplazo los modificadores que pueden ser problematicos (FONT, #ORIG, #ORDINAL y #SEQ, por el momento)

Utilización
===========
- Pegar el código en la ventana
- El primer botón, "Pre-Procesar", unifica las lineas (separadas por |)
- El botón "Elimina Fonts" elimina de todo el código el modificador FONT
- El botón "Elimina Orig" elimina de todo el código el modificador #ORIG
- El botón "Elimina Ord" elimina de todo el código el modificador #ORDINAL
- El botón "Elimina Seq" elimina de todo el código el modificador #SEQ

Luego del proceso, el texto se muestra en el campo text, y se copia al portapapeles

A futuro, pienso agregarle:
- Insertar FONT general, para la ventana
- Insertar Altura estandar de campos, por tipo de control
Y la lista esta abierta a colaboraciones y sugerencias

También, voy a programar una versión similar, para Reportes.

RESPONSABILIDAD POR USO
=======================
No me hago responsable, en absoluto, por los errores que puedan generarse por el uso de esta herramienta

Historia de modificaciones
==========================
v1.0 - 30-01-2021
Versión Inicial