# Diseño: diagrama de clases

## Clases principales

### Usuario
- id: entero
- nombre: texto
- email: texto
- iniciarSesion()
- cerrarSesion()

### Proyecto
- id: entero
- nombre: texto
- descripcion: texto
- crearTarea()

### Tarea
- id: entero
- titulo: texto
- descripcion: texto
- estado: texto
- prioridad: texto
- actualizarEstado()

## Relaciones
- Un usuario puede gestionar varios proyectos.
- Un proyecto contiene varias tareas.
- Una tarea puede estar asignada a un usuario.
