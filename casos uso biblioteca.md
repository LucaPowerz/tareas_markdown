# Diagrama de Casos de Uso - Sistema de Biblioteca

## Descripción del Sistema
El sistema de biblioteca permite a los usuarios y bibliotecarios realizar diversas acciones relacionadas con la gestión de libros.

## Actores
- **Usuario**: Persona que utiliza el sistema para buscar y solicitar libros.
- **Bibliotecario**: Persona encargada de administrar la biblioteca y gestionar los libros prestados.

## Casos de Uso

### 1. Prestar Libro
- **Descripción**: Permite a un usuario solicitar el préstamo de un libro.
- **Actores**: Usuario, Bibliotecario
- **Flujo Principal**:
    1. El Usuario solicita el préstamo de un libro.
    2. El Bibliotecario verifica la disponibilidad del libro.
    3. Si el libro está disponible, el Bibliotecario registra el préstamo.
    4. El Usuario recibe el libro prestado.

### 2. Devolver Libro
- **Descripción**: Permite a un usuario devolver un libro prestado.
- **Actores**: Usuario, Bibliotecario
- **Flujo Principal**:
    1. El Usuario devuelve el libro prestado.
    2. El Bibliotecario registra la devolución del libro.
    3. El libro se marca como disponible en el sistema.

### 3. Buscar Libro
- **Descripción**: Permite a un usuario buscar libros en el catálogo de la biblioteca.
- **Actores**: Usuario
- **Flujo Principal**:
    1. El Usuario realiza una búsqueda de libros por título, autor o categoría.
    2. El Sistema muestra una lista de libros que coinciden con los criterios de búsqueda.
    3. El Usuario selecciona un libro de la lista para ver más detalles.

### 4. Gestionar Inventario
- **Descripción**: Permite a un bibliotecario gestionar el inventario de libros.
- **Actores**: Bibliotecario
- **Flujo Principal**:
    1. El Bibliotecario agrega nuevos libros al inventario.
    2. El Bibliotecario elimina libros del inventario.
    3. El Bibliotecario actualiza la información de los libros, como el título, autor o categoría.