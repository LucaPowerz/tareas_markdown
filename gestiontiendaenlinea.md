# Diagrama de Casos de Uso - Sistema de Gestión de Tienda en Línea

## Descripción del Sistema
El sistema de gestión de tienda en línea permite a los clientes realizar compras de productos disponibles en la tienda y al administrador gestionar el inventario, los pedidos y otros aspectos del negocio.

## Actores
- Cliente
- Administrador

## Casos de Uso

### 1. Ver Catálogo
- **Descripción**: Permite al cliente ver los productos disponibles en la tienda.
- **Actores**: Cliente
- **Flujo Principal**:
    1. El cliente accede a la página principal de la tienda en línea.
    2. El sistema muestra una lista de productos disponibles con detalles como nombre, descripción y precio.

### 2. Realizar Compra
- **Descripción**: Permite al cliente realizar una compra de productos.
- **Actores**: Cliente
- **Flujo Principal**:
    1. El cliente selecciona un producto para comprar.
    2. El cliente agrega el producto al carrito de compras.
    3. El cliente procede al pago y proporciona la información de envío.
    4. El sistema procesa el pago y confirma la compra.

### 3. Gestionar Inventario
- **Descripción**: Permite al administrador gestionar el inventario de productos.
- **Actores**: Administrador
- **Flujo Principal**:
    1. El administrador inicia sesión en el sistema de gestión.
    2. El administrador accede al panel de administración de productos.
    3. El administrador agrega nuevos productos al inventario.
    4. El administrador actualiza la información de los productos existentes, como nombre, descripción y precio.
    5. El administrador elimina productos del inventario si es necesario.

### 4. Gestionar Pedidos
- **Descripción**: Permite al administrador gestionar los pedidos realizados por los clientes.
- **Actores**: Administrador
- **Flujo Principal**:
    1. El administrador inicia sesión en el sistema de gestión.
    2. El administrador accede al panel de administración de pedidos.
    3. El administrador visualiza una lista de pedidos pendientes.
    4. El administrador marca los pedidos como procesados una vez que se han completado.
