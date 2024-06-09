# Casos de Uso - Tarea App Transport

## Descripción
Realiza la especificación de los casos de uso asociados al diagrama explicativo anteriormente. Edita todo utilizando markdown y súbelo a tu repositorio de la asignatura.

Documenta adecuadamente cada caso de uso y los actores.

## Caso de Uso: App Transport

### Actores
- Administrador
- Usuario
- Sistema de geoposicionamiento externo

### Descripción
Este caso de uso describe el proceso de gestión de viajes dentro de la aplicación de transporte.

### Flujo Básico
1. El administrador define el medio de transporte.
2. El administrador define el precio del transporte.
3. El administrador gestiona el alta y baja de usuarios.
4. El usuario se da de alta en la aplicación.
5. El usuario inicia sesión en la aplicación.
6. El usuario utiliza el sistema de geoposicionamiento para establecer su ubicación actual.
7. El usuario define su destino.
8. El usuario modifica la ruta si es necesario.
9. El sistema de geoposicionamiento calcula la ruta óptima hasta el destino.
10. El usuario confirma la ruta.

### Extensiones
- El usuario selecciona "Sugerir Destinos Interesantes":
  - El sistema muestra una lista de destinos interesantes cercanos.
  - El usuario selecciona uno de los destinos sugeridos.
  - El sistema calcula la ruta óptima hasta el destino seleccionado.
- El usuario selecciona "Mostrar Puntos de Interés en Ruta":
  - El sistema muestra los puntos de interés que se encuentran en la ruta.
  - El usuario visualiza los puntos de interés en el mapa.

### Precondiciones
- El administrador tiene permisos para definir el medio de transporte y el precio.
- El usuario ha iniciado sesión en la aplicación.
- El sistema de geoposicionamiento externo está disponible.

### Postcondiciones
- Se ha definido la ruta del viaje.
- El usuario ha confirmado la ruta.