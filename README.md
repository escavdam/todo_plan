# todo_plan
Planning de todo-app

# Expectativas del cliente:
1. Aplicación web  para realizar tareas sincronizadas con la web y el terminal.
   
2. Funcionalidades:
   
- Crea la tabla.

- Asignar tareas a un grupo.

- Cambiar el estado de una tarea.  (Pendiente, en progreso o completada)

- Eliminar las tareas.

- Listar tareas.

- Listar tareas por grupo.

- Listar tareas por estado.

3. La app CLI (Interfaz de línea de comandos) y web comparten base de datos con datos persistentes.

**Estructura de la base de datos**:
*Modelo Mono-Tabla.*

Todas las entidades se guardan en una sola tabla llamada "todo" que tiene los siguientes campos:
- Id: Identificador único de cada tarea. Tipo: Integer.
- Title: Titulo de la tarea. Tipo: String. Obligatorio.
- Estado: Descripción de la tarea. Tipo: Text.
- Group: Nombre del grupo al que pertenece la tarea. Tipo: String.


- Fecha (¿Limite?) Para priorizar tareas?


**Endpoints necesarios**:
- GET /todos -> Devuelve todas las tareas.
- POST /todos -> Crea una nueva tarea. Recibe como parámetro el titulo y el grupo. Devuelve el id generado.
- PUT /todos/:id -> Modifica una tare.
- DELETE /todos/:id -> Borra una tarea.

**Front-End**
La interfaz debe ser sencilla y clara para poder utilizar la aplicación sin tener conocimientos técnicos avanzados.

**Referencias de otras apps:**
Recordatorios de Iphone.



















