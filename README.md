Funcionalidad de la Aplicación
La aplicación permite a los usuarios crear y administrar tareas con fechas y horas específicas. Cuando una tarea alcanza su fecha y hora designadas, la tarjeta de la tarea se destacará visualmente mediante un cambio de color y una animación. Esto alerta al usuario de que la tarea está vencida y requiere atención inmediata.

Implementación Técnica
La aplicación se compone de tres partes principales: HTML, CSS y JavaScript.

HTML
El HTML define la estructura básica de la aplicación, incluyendo el formulario para agregar nuevas tareas y la sección para mostrar las tareas existentes.

CSS
El CSS proporciona estilos visuales para la aplicación, incluyendo colores, diseño y animaciones. Se ha añadido una animación llamada dueAnimation que alterna el color de fondo de la tarjeta de tarea cuando está vencida.

JavaScript
El JavaScript se encarga de la lógica de la aplicación. Algunas de las funciones clave son:

Agregar una nueva tarea: Captura los datos del formulario y crea una nueva tarjeta de tarea con los detalles proporcionados.
Verificar la fecha y hora de la tarea: Utiliza un intervalo para comprobar continuamente si la fecha y hora actual son mayores o iguales a la fecha y hora de la tarea. Cuando se cumple esta condición, se añade la clase due a la tarjeta de tarea, desencadenando así la animación y el cambio de color.
Actualizar una tarea: Permite al usuario actualizar los detalles de una tarea existente, como el título, la fecha y la descripción.
Cerrar el formulario de actualización: Proporciona la funcionalidad para cerrar el formulario de actualización de tarea.
