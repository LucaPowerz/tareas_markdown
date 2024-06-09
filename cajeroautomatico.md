# Diagrama de Casos de Uso - Sistema de Cajero Automático

## Descripción del Sistema
El sistema de cajero automático permite a los clientes bancarios realizar diversas operaciones financieras, como retiros de efectivo, transferencias, consultas de saldo, entre otras. El administrador tiene acceso adicional para gestionar el funcionamiento del cajero y supervisar las transacciones.

## Actores
- Cliente bancario
- Administrador

## Casos de Uso

### 1. Hacer Login
- **Descripción**: Permite al cliente bancario iniciar sesión en el sistema del cajero automático.
- **Actores**: Cliente bancario
- **Flujo Principal**:
    1. El cliente bancario introduce su tarjeta bancaria en el lector de tarjetas.
    2. El cliente ingresa su código PIN.
    3. El sistema verifica la autenticidad de la tarjeta y el PIN.
    4. Si la autenticación es exitosa, el cliente accede al menú principal del cajero.

### 2. Realizar Transferencia
- **Descripción**: Permite al cliente bancario transferir fondos entre cuentas bancarias.
- **Actores**: Cliente bancario
- **Flujo Principal**:
    1. El cliente selecciona la opción de realizar una transferencia.
    2. El cliente ingresa los detalles de la transferencia, como el número de cuenta de destino y el monto a transferir.
    3. El sistema verifica la disponibilidad de fondos en la cuenta del cliente.
    4. Si hay fondos suficientes, el sistema realiza la transferencia y actualiza los saldos de las cuentas involucradas.

### 3. Ingresar Dinero
- **Descripción**: Permite al cliente bancario ingresar dinero en efectivo en su cuenta bancaria.
- **Actores**: Cliente bancario
- **Flujo Principal**:
    1. El cliente selecciona la opción de ingresar dinero.
    2. El cliente introduce el efectivo en el dispensador de billetes.
    3. El sistema verifica la autenticidad de los billetes y actualiza el saldo de la cuenta del cliente.

### 4. Ver Saldo
- **Descripción**: Permite al cliente bancario consultar el saldo disponible en su cuenta bancaria.
- **Actores**: Cliente bancario
- **Flujo Principal**:
    1. El cliente selecciona la opción de ver saldo.
    2. El sistema muestra el saldo actual de la cuenta del cliente en la pantalla del cajero.

### 5. Poner Dinero al Móvil
- **Descripción**: Permite al cliente bancario recargar el saldo de su teléfono móvil utilizando su cuenta bancaria.
- **Actores**: Cliente bancario
- **Flujo Principal**:
    1. El cliente selecciona la opción de poner dinero al móvil.
    2. El cliente introduce el número de teléfono móvil y el monto a recargar.
    3. El sistema verifica la disponibilidad de fondos en la cuenta del cliente y realiza la recarga.
