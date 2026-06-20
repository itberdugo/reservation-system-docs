# Documento de Visión del Producto

## Sistema de Reservas de Zonas Comunes

**Conjunto Residencial Peñas Blancas**

---

## 1. Propósito del documento

Este documento tiene como propósito definir la visión inicial del sistema de reservas de zonas comunes para el Conjunto Residencial Peñas Blancas.

La intención es establecer una base clara sobre el problema actual, los usuarios involucrados, los objetivos del sistema, el alcance inicial y los beneficios esperados.

Este documento servirá como punto de partida para la toma de decisiones, levantamiento de requerimientos, diseño funcional y construcción del sistema.

---

## 2. Problema actual

Actualmente, para realizar la reserva de una zona común, como el auditorio, salón social u otro espacio disponible, el residente debe comunicarse directamente con la administración del conjunto.

La administradora debe verificar manualmente si el espacio se encuentra disponible para la fecha solicitada, confirmar las condiciones de uso y registrar la reserva.

Este proceso puede generar demoras, cruces de información, dependencia de una sola persona, dificultad para consultar disponibilidad y poca trazabilidad sobre las reservas realizadas.

---

## 3. Objetivo del producto

El objetivo del producto es construir un sistema informático que permita gestionar digitalmente la reserva de zonas comunes dentro del conjunto residencial.

El sistema deberá permitir que los residentes consulten disponibilidad, soliciten reservas y reciban confirmación de manera organizada.

A su vez, la administración podrá gestionar solicitudes, aprobar o rechazar reservas, configurar espacios, consultar el calendario y mantener control sobre el uso de las zonas comunes.

---

## 4. Usuarios principales

Los usuarios principales del sistema serán:

### Residentes

Personas que viven en el conjunto residencial y desean reservar una zona común para una fecha y horario específico.

### Administración

Personal encargado de revisar, aprobar, rechazar y gestionar las reservas solicitadas por los residentes.

### Vigilancia

Visualiza reservas activas para controlar el acceso.

### Consejo o comité administrativo

Usuarios que pueden requerir consulta de información, reportes o seguimiento sobre el uso de las zonas comunes.

---

## 5. Alcance inicial del sistema

El alcance inicial del sistema contempla las siguientes funcionalidades:

* Registro e inicio de sesión de usuarios.
* Consulta de zonas comunes disponibles.
* Visualización de calendario de disponibilidad.
* Solicitud de reserva por parte del residente.
* Aprobación o rechazo de reservas por parte de administración.
* Gestión de zonas comunes.
* Configuración de horarios disponibles.
* Consulta del historial de reservas.
* Notificación del estado de la solicitud.
* Panel administrativo para control de reservas.

En esta primera versión no se contempla integración como lo pueden ser control de acceso físico, aplicación móvil nativa ni integración automática con WhatsApp, aunque estas funcionalidades podrían ser consideradas para futuras versiones.

---

## 6. Beneficios esperados

La implementación del sistema permitirá:

* Reducir la carga manual de la administración.
* Evitar cruces o dobles reservas.
* Mejorar la experiencia de los residentes.
* Reservar desde cualquier lugar. 
* Centralizar la información de reservas.
* Tener trazabilidad sobre solicitudes, aprobaciones y cancelaciones.
* Consultar disponibilidad en tiempo real.
* Organizar mejor el uso de las zonas comunes.
* Generar una base para futuras automatizaciones.

---

## 7. Funcionalidades futuras

En versiones posteriores, el sistema podría incluir:

* Notificaciones automáticas por WhatsApp o correo electrónico.
* Pagos en línea para reservas que tengan costo.
* Firma digital de reglamentos de uso.
* Generación de comprobantes de reserva.
* Reportes administrativos.
* App móvil para residentes.
* Integración con control de acceso.
* Bloqueo automático de fechas por mantenimiento.
* Encuestas de satisfacción después del uso del espacio.

---
## 8. REGLAS DE NEGOCIO INICIALES

### RN-001
* Una zona no puede tener dos reservas superpuestas.

### RN-002
* Una reserva puede requerir aprobación de la administración.

### RN-003
* Un residente sólo podrá reservar si está activo.

### RN-004
* Una reserva aprobada notificará automáticamente a administración y vigilancia.

### RN-005
* Una reserva podrá ser cancelada con una anticipación mínima definida por el conjunto.

### RN-006
* La administración podrá bloquear fechas por mantenimiento.

### RN-007
* Cada zona tendrá un horario configurable.

### RN-008
* Las reservas tendrán estados:
    * PENDIENTE 
    * APROBADA 
    * RECHAZADA 
    * CANCELADA 
    * FINALIZADA 


---

## 9. Criterios de éxito

El proyecto será considerado exitoso si logra:

* Permitir a los residentes consultar disponibilidad sin depender directamente de la administración.
* Reducir errores o conflictos en la asignación de reservas.
* Facilitar a la administración la aprobación y control de solicitudes.
* Mantener un historial claro de reservas realizadas.
* Mejorar la percepción del servicio por parte de los residentes.
* Servir como base escalable para futuras mejoras del producto.
