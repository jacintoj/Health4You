# Health4You
### Descripción
Health4You es una aplicación web de un gimnasio, gracias a la cual los monitores pueden elaborar mejores entrenamientos personalizados a los clientes/socios y éstos pueden ver el plan de entrenamiento que tienen que realizar. 
De esta forma, se puede mejorar la gestión y coordinación de dichos planes de entrenamiento y conseguir una mejora de los servicios ofrecidos por el gimansio.

### Funcionalidades
* __Pública__: vamos a mostrar la descripción del gimnasio, su ubicación del gimnasio, la publicidad sobre el mismo haciendo alusión al factor diferencial de los planes de entrenamiento personalizados. También aparecerán los monitores de dicho gimnasio (foto y descripción) junto con comentarios que hayan hecho los socios sobre ellos. También hemos pensado que podría ser interesante tener un timeline de Facebook y otro de Twitter para ver en tiempo real lo que comentan sobre el gimnasio.

* __Privada__:
  * *__Administrador__*: gestión de monitores del gimnasio (alta, lectura, borrado, modificación), gestión de los socios (alta, lectura, borrado, modificación), gestión de ejercicios disponibles.
  * *__Monitores__*: hacerse monitor de los socios, gestión (alta, lectura, borrado, modificación) de los planes de entrenamiento personalizados. 
  * *__Socios__*: acceso a la visualización de sus planes de entrenamiento, con posibilidad de descargárselos en PDF; poder hacer un comentario del monitor que tienen asignado.
 
 
> Estamos evaluando la posibilidad de tener algún tipo de gamificación, en relación a la cantidad de ejercicio que realicen los socios, para motivar más el deporte y la vida sana.
 
### Descripción de las entidades
* *__Gimnasio__*: contiene los datos correspondientes al gimnasio.
* *__Usuario__*: representa un usuario de la aplicación, el cual puede ser un administrador, un monitor o un socio/cliente.
* *__Comentario__*: esta entidad representa al comentario que un socio hace sobre un determinado monitor.
* *__Catagoría de ejercicio__*: representa la categoría de ejercicio que se le está poniendo al socio. Ejemplos de categorías son: cardio - bicicleta vertical, cardio-bicicleta recline, cardio-step, cardio-elíptica, clase colectiva, fuerza-tren superior, fuerza-tren medio, etc...
* *__Plan de entrenamiento__*: se compone del conjunto de ejercicios que el socio tiene que realizar durante el periodo de tiempo marcado.
* *__Ejercicio__*: es la unidad de entrenamiento. Cada ejercicio pertenece a una categoría, tiene marcado el peso con el que realizarlo, el número de repeticiones, el número de series, el tiempo de descanso entre las mismas. Y se acompaña una foto del ejercicio.

### Integrantes
* __David Fernández Llamazares__
  * *__Email__*: [d.fernandezll@alumnos.urjc.es](d.fernandezll@alumnos.urjc.es)
  * *__Cuenta github__*: [https://github.com/dfernandezll](https://github.com/dfernandezll)

* __Jacinto José Cruz Nieto__
  * *__Email__*: [jj.cruz@alumnos.urjc.es](jj.cruz@alumnos.urjc.es)
  * *__Cuenta github__*: [https://github.com/jacintoj](https://github.com/jacintoj)
  
__Tablero Trello__: https://trello.com/b/Qd7JKv8N/practica-sistemas-distribuidos
