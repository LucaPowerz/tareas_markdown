# Diagrama de Casos de Uso - Aplicación de Red Social

## Descripción del Sistema
La aplicación de red social permite a los usuarios interactuar entre sí compartiendo mensajes, conectándose con amigos y realizando diversas acciones en la plataforma. El administrador tiene acceso adicional para gestionar usuarios, contenido y otras actividades administrativas.

## Actores
- Usuario
- Administrador

## Casos de Uso

### 1. Publicar Mensaje
- **Descripción**: Permite al usuario publicar un mensaje en su perfil o en la plataforma.
- **Actores**: Usuario
- **Flujo Principal**:
    1. El usuario redacta un mensaje.
    2. El usuario selecciona la opción de publicar.
    3. El mensaje se muestra en el perfil del usuario y/o en la plataforma.

### 2. Conectar con Amigos
- **Descripción**: Permite al usuario conectar con amigos en la red social.
- **Actores**: Usuario
- **Flujo Principal**:
    1. El usuario busca amigos utilizando diferentes criterios, como nombre de usuario o correo electrónico.
    2. El usuario envía una solicitud de amistad a uno o más usuarios.
    3. Los usuarios reciben las solicitudes de amistad y las aceptan o rechazan.
    4. Una vez que una solicitud es aceptada, los usuarios se añaden a la lista de amigos del usuario.

### 3. Eliminar Publicación
- **Descripción**: Permite al usuario eliminar una publicación que ha realizado.
- **Actores**: Usuario
- **Flujo Principal**:
    1. El usuario accede a su perfil o a la publicación que desea eliminar.
    2. El usuario selecciona la opción de eliminar la publicación.
    3. La publicación se elimina de la plataforma y/o del perfil del usuario.

### 4. Gestionar Usuarios (Administrador)
- **Descripción**: Permite al administrador gestionar los usuarios registrados en la red social.
- **Actores**: Administrador
- **Flujo Principal**:
    1. El administrador accede al panel de administración de usuarios.
    2. El administrador visualiza una lista de usuarios registrados.
    3. El administrador puede suspender, eliminar o editar la información de los usuarios según sea necesario.

### 5. Moderar Contenido (Administrador)
- **Descripción**: Permite al administrador moderar el contenido publicado en la red social.
- **Actores**: Administrador
- **Flujo Principal**:
    1. El administrador accede al panel de moderación de contenido.
    2. El administrador visualiza una lista de publicaciones reportadas por los usuarios.
    3. El administrador puede eliminar o marcar las publicaciones como inapropiadas según las políticas de la red social.

## Diagrama de Casos de Uso

El diagrama de casos de uso se adjunta en un archivo de imagen llamado "casos_de_uso_red_social.png".