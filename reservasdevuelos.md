# Diagrama de Casos de Uso - Sistema de Reservas de Vuelos

## Descripción del Sistema
El sistema de reservas de vuelos permite a los pasajeros buscar vuelos disponibles, reservar vuelos, cancelar reservas y gestionar su información personal. Los agentes de reservas tienen acceso adicional para gestionar las reservas en nombre de los pasajeros.

## Actores
- Pasajero
- Agente de Reservas

## Casos de Uso

### 1. Buscar Vuelo
- **Descripción**: Permite al pasajero buscar vuelos disponibles según diferentes criterios, como origen, destino, fecha y hora.
- **Actores**: Pasajero
- **Flujo Principal**:
    1. El pasajero selecciona la opción de buscar vuelo.
    2. El sistema muestra un formulario de búsqueda.
    3. El pasajero ingresa los criterios de búsqueda (origen, destino, fecha, etc.).
    4. El sistema muestra una lista de vuelos disponibles que coinciden con los criterios de búsqueda.

### 2. Reservar Vuelo
- **Descripción**: Permite al pasajero reservar un vuelo seleccionado.
- **Actores**: Pasajero
- **Flujo Principal**:
    1. El pasajero selecciona un vuelo de la lista de vuelos disponibles.
    2. El sistema muestra los detalles del vuelo seleccionado.
    3. El pasajero confirma la reserva del vuelo.

### 3. Cancelar Reserva
- **Descripción**: Permite al pasajero cancelar una reserva existente.
- **Actores**: Pasajero
- **Flujo Principal**:
    1. El pasajero accede a su cuenta.
    2. El pasajero selecciona la opción de ver sus reservas.
    3. El sistema muestra una lista de las reservas del pasajero.
    4. El pasajero selecciona la reserva que desea cancelar.
    5. El pasajero confirma la cancelación de la reserva.

### 4. Gestionar Reservas (Agente de Reservas)
- **Descripción**: Permite al agente de reservas gestionar las reservas en nombre de los pasajeros.
- **Actores**: Agente de Reservas
- **Flujo Principal**:
    1. El agente de reservas inicia sesión en el sistema.
    2. El agente de reservas busca las reservas existentes por pasajero o por vuelo.
    3. El agente de reservas selecciona una reserva existente.
    4. El agente de reservas modifica o cancela la reserva según las instrucciones del pasajero.