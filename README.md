#Trello

Vamos a replicar el tablero de Trello, siguiendo un flujo de versiones.

##Versión 0.0.1

Se mostrará el texto "Añadir una lista ...".
Al hacer click se debe ocultar el texto y mostrar un formulario.
El formulario está conformado por un input y un botón para que pueda añadir tareas a tu lista.

###Versión 0.0.2

Al dar click en el botón de "Guardar", se mostrará un nuevo cuadro donde estará el nombre de la lista agregada.
Mostrar un texto de "Añadir una tarea" dentro de la lista.

####Versión 0.0.3

Al dar click en "Añadir una tarea", deberá mostrar un formulario con un textarea y un botón que diga "Añadir".

#####Versión 0.0.4

Poner focus al input al dar click en "Agregar nueva tarea".
Al dar click en el botón de "Añadir", deberá aparecer el texto de la tarea debajo del título de la lista.

######Versión 0.0.5

Mostrar el formulario nuevamente debajo de la última tarea añadida.

#######Versión 0.0.6 (Extra)

Poder agregar múltiples listas con tarjetas. Para esto, el formulario de "Añadir una lista" debe aparecer a la derecha de la lista anteriormente creada.

##html
Creacion de cuerpo de trabajo por cajas
seccionamiento en partes semanticas
declaracion de clases y id,
e inputs y botones.

###JS

1. Declaracion de variables para llamar a la lista.
2. Llamar a la lista haciendo mencion que al ocurrir un evento de tipo click se creara nueva lista.
3. Llamando a los elementos de la listas.
4. Declaracion de variables para darle funcion al boton.
5. Nueva seccion que contendra las nuevas listas.
6. Creacion de las Tarjetas.
7. añadiendo funcion para crear nuevas tarjetas.
8. creacion del contenedor del area de texto.
9. creacion del divisor de secciones
10. area donde se escrbiran las nuevas tarjetas.
11. agregando boton para guardar tareas.
12. agregando funcion para la creacion de una nueva lista al evento de dar click al boton.

####CSS

Estilo del body:
color de fondo: #1D8DC2.
Fuente:sans-serif.

Estilo de clases e id en botones:
color del boton: #519839.

Color de lista:#eee.

Cambiando estilos cuando se activen

Color de fondo:#147AA7.
color:#fff.
cursor de puntero.

Cambiando estilos cuando se desactive
Color de fondo:#C6567E;
color:#fff.

Estilo de iconos y tableros
color de fondo tablero:#66A3C1.
color de fondo boton:#519839.
color:#fff.

boton desactivado
color de fondo:#A5E0FC;
color:#fff.

Iconos de aweson usados:
fa-search
fa-star
fa-lock
fa-trello
fa-bell
fa-info-circle
fa-plus.
