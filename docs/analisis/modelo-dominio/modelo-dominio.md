# Modelo del Dominio

El dominio del sistema está compuesto por las entidades principales involucradas en el proceso de reservas.

## Entidades principales

### Usuario

Representa las personas que utilizan el sistema.

### Residente

Usuario que realiza solicitudes de reserva.

### Administrador

Usuario encargado de la gestión del sistema.

### Vigilante

Usuario encargado del control de acceso.

### Zona Común

Espacio disponible para reserva.

### Reserva

Solicitud realizada por un residente.

### Horario

Franja horaria disponible para una zona común.

### EstadoReserva

Representa el estado actual de una reserva.

Valores posibles:

- PENDIENTE
- APROBADA
- RECHAZADA
- CANCELADA
- FINALIZADA

### Notificación

Comunicación generada por el sistema sobre eventos relacionados con las reservas.