# 馃摑Task Manager 

## 馃捇Entrega: Eventos

Para esta entrega ya se encuentra funcionando la posibilidad de crear nuevas tareas a partir del ingreso del dato en la caja de texto y presionando el bot贸n + o la tecla enter. 

Se hicieron modificaciones en la funci贸n que creaba en DOM una tarea, ahora es m谩s modular, se tiene para cada elemento que forma una tarea la variable correspondiente: checkbox, texto y bot贸n de eliminaci贸n. Cuando se crea una tarea se le asigna un id a la misma y un event listener para el checkbox y bot贸n de eliminaci贸n.

Queda a煤n por implementar la l贸gica de eliminar una tarea y actualizar el DOM, adem谩s de marcarla como terminada con el checkbox. Por el momento se hace un console.log cuando se hace click en el bot贸n o checkbox para verificar el event listener de cada uno de estos.


## 鉁忥笍 Funcionalidades

La idea del proyecto de es crear una aplicaci贸n web de manejo de tareas. Donde el usuario pueda agregar nuevas tareas a una lista y gestionarla.

### 馃敎 Como funcionalidades a futuro se plantean:

* Crear y eliminar tareas individualmente.
* Hacer un check a tareas terminadas.
* Mostrar filtrando por tareas activas, terminadas, o todas.
* Limpiar todas las tareas.
* Visualizaci贸n de hora de creaci贸n de tarea.
* Tarea con fecha de vencimiento y mostrar tiempo restante.
* Etiquetas para tareas urgentes.
* Tareas arrastrables para re-ubicarlas en la lista.