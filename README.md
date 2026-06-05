# ChatBotBarber-Proyecto
---

## PROBLEMÁTICA

Las barberías presentan una notable brecha digital en la gestión de sus servicios.
Actualmente, la reserva de citas depende de métodos manuales o comunicación por
llamadas telefónicas, lo que genera una ineficiencia operativa crítica. Esta falta de
automatización no solo provoca errores como la duplicidad de horarios y la pérdida
de datos personales de los clientes, sino que también degrada la experiencia del
cliente, quien busca y quiere respuestas inmediatas.

---

## ALCANCE DEL PROYECTO

El alcance del proyecto es desarrollar un ChatBot integrado con WhatsApp para
gestionar citas de forma automatizada, permitiendo asignarlas, reprogramarlas y
cancelarlas con validación en tiempo real. Incluye registro de usuarios, notificaciones
automáticas y funciones adicionales.
La innovación de nuestro proyecto va de la mano con la IA, asistente artificial que
ayude con el agendamiento y administración de horarios de cualquier barbería.

---

## OBJETIVO GENERAL

Desarrollar un sistema de información mediante un Chatbot de WhatsApp, que
automatice el proceso de agendamiento de citas para múltiples barberías.

---

## OBJETIVOS ESPECIFICOS

**1**. Levantar y documentar los requerimientos funcionales y no funcionales
mediante técnicas de recolección de información para definir las necesidades
de clientes, barberos y administradores.

**2.** Diseñar la arquitectura del sistema y los flujos conversacionales del Chatbot
en WhatsApp, utilizando diagramas de casos de uso para establecer una
solución.

**3.** Desarrollar el sistema digital de agendamiento de forma iterativa por medio
de Sprints, integrando módulos de registro, gestión de disponibilidad y
catálogo de servicios.

**4.** Implementar un módulo de reportes y control que permita al administrador
visualizar el rendimiento del sistema y la gestión de los barberos activos.

**5.** Validar el funcionamiento del sistema con los usuarios finales para realizar
ajustes en la documentación y asegurar que el sistema sea eficiente y
eliminar los errores de doble asignación de turnos.

---

## Valor del Producto

El producto reduce la carga operativa del personal de la barbería, minimiza errores de agenda,
mejora la experiencia del cliente al ofrecer disponibilidad 24/7 y facilita la toma de decisiones
mediante reportes y estadísticas. El ChatBot permite una interacción ágil y moderna, reduciendo la
necesidad de intervención humana en tareas repetitivas.

---

## Requisitos de la interfaz de hardware

* El sistema funcionará en servidores web estándar con capacidad para soportar al menos 500 usuarios concurrentes.
* Compatible con dispositivos móviles, tablets y computadoras de escritorio.
* No requiere hardware especializado.

---

## Requisitos de la interfaz de software

* **Backend:** 
Es el cerebro detrás de escena. Es el código que corre en el servidor y se encarga de la lógica del negocio, procesar los datos, la seguridad y la comunicación entre los distintos sistemas.
&nbsp;  Python 
&nbsp;  FastAPI

* **Frontend:** 
Es la cara visible de la aplicación, todo lo que el usuario ve, toca e interactúa directamente. En aplicaciones web o móviles, incluye los botones, colores, menús y animaciones.
- React 
- HTML 
- CSS

* **Base de datos:** 
Es el almacén digital estructurado donde se guarda y organiza toda la información del sistema de forma permanente para que no se pierda al apagar el servidor.
- PostgreSQL 

* **Servicio de correo:** 
Es un sistema externo o interno especializado en el envío automatizado de correos electrónicos masivos o transaccionales (como confirmaciones, notificaciones o restablecimiento de contraseñas), evitando que estos mensajes caigan en la carpeta de SPAM.
- SMTP para envío de notificaciones y recuperación de contraseñas.

* **ChatBot:** 
Es un programa informático diseñado para simular una conversación con usuarios humanos, ya sea a través de texto o de voz. Funciona de forma automatizada respondiendo preguntas comunes, guiando al usuario en tareas específicas (como agendar una cita) y operando de manera ininterrumpida las 24 horas del día.
- Integración con API de Dialogflow
- API de WhatsApp

---

## Requisitos de la interfaz de comunicación

* **Protocolo:** HTTPS para todas las comunicaciones cliente-servidor.

* **Autenticación:** JWT(JSON Web Tokens) con expiración.

JWT es un estándar abierto utilizado para transmitir información de forma segura entre partes en formato JSON. Se usa principalmente para la autenticación y autorización de usuarios.

* **Tiempo Real:** WebSockets para actualización de disponibilidad y notificaciones.

WebSockets es un protocolo de comunicación que permite un canal de comunicación bidireccional y en tiempo real entre el usuario (navegador/cliente) y el servidor a través de una única conexión abierta. Una vez abierta la conexión, tanto el cliente como el servidor pueden enviarse datos en cualquier momento, de forma instantánea y sin esperas.

* **Correos electrónicos:** Confirmaciones, recordatorios, recuperación de contraseña, alertas de cancelación.

* **Exportación de datos:** Formats PDF y Excel para reportes.

---

## Requisitos Funcionales

RF-01: Crear Cuenta
RF-02: Digitar Nombre
RF-03: Digitar Correo
RF-04: Digitar Confirmación Correo
RF-05: Digitar Teléfono
RF-06: Iniciar Sesión
RF-07: Digitar nombre_usuario
RF-08: Digitar ContraseñaRF-06: Iniciar Sesión
RF-07: Digitar nombre_usuario
RF-08: Digitar Contraseña
RF-09: Recuperar contraseña
RF-10: Ingresar Correo de Recuperación
RF-11: Digitar Rol
RF-12: Interacción con el ChatBot
RF-13: Enviar Mensajes
RF-14: Agendar Cita
RF-15: Consultar Disponibilidad
RF-16: Seleccionar Servicio
RF-17: Elegir Barbero
RF-18: Seleccionar Fecha y Hora
RF-19: Recibir Notificaciones
RF-20: Enviar Recordatorios
RF-21: Reprogramar Cita
RF-22: Ver Cita
RF-23: Seleccionar Cita
RF-24: Editar Cita
RF-25: Consultar Cita
RF-26: Ver Estado Cita
RF-27: Cancelar Cita
RF-28: Perfil
RF-29: Editar Datos Personales
RF-30: Ver Historial de Citas
RF-31: Soporte/Contacto
RF-32: Ver Buzón de PQR
RF-33: Peticiones
RF-34: Quejas
RF-35: Reclamos
RF-36: Sugerencias
RF-37: Contactar una Persona
RF-38: Llamar a Soporte
RF-39: Iniciar Conversación
RF-40: Saludar
RF-41: Mostrar Menú
RF-42: Agendar Cita
RF-43: Recopilar Servicio Escogido
RF-44: Recopilar Barbero
RF-45: Validar Disponibilidad
RF-46: Revisar Calendario
RF-47: Ver Disponibilidad
RF-48: Solicitar Datos Cliente
RF-49: Registrar Datos Cliente
RF-50: Reprogramar Cita
RF-51: Poner Nueva Fecha y Hora
RF-52: Validar Disponibilidad
RF-53: Cancelar Cita
RF-54: Notificar Cancelación
RF-55: Notificar
RF-56: Mandar Notificaciones
RF-57: Enviar Confirmación
RF-58: Enviar Recordatorios
RF-59: Notificar Cancelación
RF-60: Soporte Técnico
RF-61: Enseñar Información
RF-62: Mostrar Correo
RF-63: Mostrar Teléfono
RF-64: Ver Buzón de PQR
RF-65: Gestionar Servicios
RF-66: Añadir Servicio
RF-67: Modificar Servicio
RF-68: Eliminar Servicio
RF-69: Gestionar Barberos
RF-70: Añadir Barbero
RF-71: Modificar Barbero
RF-72: Eliminar Barbero
RF-73: Ver estadísticas por barbero
RF-74: Gerstionar Clientes
RF-75: Ver historial de citas por clientes
RF-76: Acceder a datos de contacto
RF-77: Importar/Exportar base de datos del cliente
RF-78: Configurar ChatBot
RF-79: Establecer mensajes automáticos
RF-80: Establecer recordatorios automáticos
RF-81: Ver Reportes
RF-82: Exportar PDF
RF-83: Exportar Excel
RF-84: Ver Agenda
RF-85: Aceptar Cita
RF-86: Marcar Completada
RF-87: Marcar Pendiente
RF-88: Rechazar Cita
RF-89: Ver Historial Clientes atendidos
RF-90: Acceder a Datos Básicos del Cliente
RF-91: Configurar Horario Laboral
RF-92: Seleccionar Horas Disponibles
RF-93: Seleccionar Fechas Disponibles
RF-94: Configurar Disponibilidad Semanal
RF-95: Definir Días Hábiles
RF-96: Definir Hora Entrada y Salida

---

## Requisitos No Funcionales

### Seguridad

RNF-01: Seguridad de Datos. El sistema debe proteger la información y los datos mediante cifrado seguro, las contraseñas
deben almacenarse con hash bcrypt (costo 10). Correos y teléfonos en base de datos cifrada.

RNF-09: Integridad de Datos. El sistema debe evitar pérdida de información.

RNF-10: Confidencialidad. El sistema debe garantizar privacidad de datos.

RNF-11: Autenticación. El sistema debe validar usuarios antes del acceso.

RNF-20: Auditoría. El sistema debe registrar cambios importantes, en log inmutable: creación, modificación y
cancelación de citas, con ID de usuario, timestamp y datos previos/nuevos.

### Capacidad

RNF-03: Rendimiento. El 95% de las peticiones (login, agendar, consultar disponibilidad) deben resolverse en ≤ 2
segundos, midiendo desde el servidor con 100 usuarios concurrentes.

RNF-13: Actualización Tiempo Real. El sistema debe actualizar información instantáneamente.

### Compatibilidad

RNF-05: Compatibilidad. El sistema debe funcionar en diferentes dispositivos.

RNF-12: Compatibilidad Navegadores. El sistema debe funcionar en varios navegadores (Chrome, Firefox, Edge y Safari).

RNF-15: Compatibilidad BD. El sistema debe integrarse con la base de datos.

RNF-22: Compatibilidad Móvil. El sistema debe adaptarse a celulares y tablets.

### Confiabilidad

RNF-02: Disponibilidad. El sistema debe estar disponible las 24 horas y ser operativo 99.9% del tiempo.

RNF-07: Respaldo de información. La base de datos debe respaldarse cada 24 horas. El respaldo debe ser restaurable en menos
de 2 horas.

RNF-14: Disponibilidad ChatBot. El chatbot debe estar activo permanentemente.

RNF-16: Manejo de errores. El sistema debe controlar errores correctamente, cualquier excepción no controlada debe mostrar al usuario un mensaje amigable "Ocurrió un error inesperado. Inténtalo más tarde." y registrar error interno

### Escalabilidad

RNF-04: Escalabilidad. El sistema debe soportar al menos 500 usuarios concurrentes con tiempo de respuesta ≤ 3 segundos, agregando instancias del backend.

### Mantenibilidad

RNF-18: Modularidad. El sistema debe dividirse en módulos independientes.

RNF-19: Portabilidad. El sistema debe funcionar en distintos entornos.

### Facilidad de uso

RNF-06: Interfaz intuitiva. El sistema debe ser fácil de usar.

RNF-08: Accesibilidad. El sistema debe ser accesible para todos los usuarios.

RNF-17: Facilidad aprendizaje. Un usuario nuevo debe completar el flujo de agendar una cita en menos de 3 minutos, sin asistencia externa (medido con 5 usuarios).

RNF-21: Experiencia usuario. El sistema debe brindar una buena experiencia fluida.

RNF-24: Diseño. El sistema debe adaptarse a diferentes pantallas sin barras de desplazamiento horizontales no
deseadas.

### Otro 

RNF-23: Validación datos. El sistema debe validar datos ingresados.

---

## Requisitos de Interfaz Externa

RI-01: Botón Registrarse / Crear Cuenta
RI-02: Ingresar Nombre
RI-03: Ingresar Correo
RI-04: Ingresar Confirmación Correo
RI-05: Ingresar Teléfono
RI-06: Botón Iniciar Sesión
RI-07: Ingresar nombre de usuario
RI-08: Ingresar contraseña
RI-09: Botón Olvidé mi Contraseña
RI-10: Digitar Correo
RI-11: Ingresar Rol
RI-12: Interacción ChatBot
RI-13: Envío de Mensajes
RI-14: Manejo de Citas
RI-15: Consulta de Disponibilidad
RI-16: Opciones de Servicio
RI-17: Opciones de Barbero
RI-18: Elección Fecha y Hora
RI-19: Recibir Notificaciones
RI-20: Recordatorios Automáticos
RI-21: Mensaje Reprogramar Cita
RI-22: Opción Ver Cita
RI-23: Seleccionar Cita
RI-24: Opción Editar Cita
RI-25: Consultar Cita
RI-26: Opción Ver Estado de la Cita
RI-27: Mensaje Cancelar Cita
RI-28: Botón Perfil
RI-29: Botón Actualizar Datos
RI-30: Botón Ver Historial de Citas
RI-31: Botón de Soporte
RI-32: Botón Buzón de PQR
RI-33: Opción de Peticiones
RI-34: Opción de Quejas
RI-35: Opción de Reclamos
RI-36: Opción de Sugerencias
RI-37: Botón Contactar Persona
RI-38: Botón Llamar a Soporte
RI-39: Inicio Conversación ChatBot
RI-40: Mensaje de Saludo
RI-41: Mensaje de Menú
RI-42: Mensaje de Agendar Cita
RI-43: Mensaje de Servicio Escogido
RI-44: Mensaje de Barbero Escogido
RI-45: Verificación de Disponibilidad
RI-46: Revisar el Calendario
RI-47: Consulta de Disponibilidad
RI-48: Mensaje de Solicitud de Datos
RI-49: Registrar Datos
RI-50: Mensaje de Reprogramar Cita
RI-51: Dar Nueva Fecha y Hora
RI-52: Confirmación de Disponibilidad
RI-53: Mensaje de Cancelar Cita
RI-54: Envío de Mensaje de Cancelación
RI-55: Mensajes de Notificaciones
RI-56: Mensajes de Notificaciones
RI-57: Mensaje de Confirmación
RI-58: Mensaje de Recortarios
RI-59: Mensaje de Cancelación
RI-60: Asistencia Técnica
RI-61: Opción Enseñar Información
RI-62: Mostrar Correo
RI-63: Mostrar Teléfono
RI-64: Botón Buzón de PQR
RI-65: Botón Gestionar Servicios
RI-66: Botón Agregar
RI-67: Botón Modificar
RI-68: Botón Eliminar
RI-69: Botón Gestionar Barberos
RI-70: Botón Agregar
RI-71: Botón Modificar
RI-72: Botón Eliminar
RI-73: Botón Ver Estadísticas
RI-74: Botón Gestionar Clientes
RI-75: Botón Ver historial Clientes
RI-76: Botón Acceder a Datos
RI-77: Botón Importar/Exportar BD
RI-78: Personalización ChatBot
RI-79: Configuración Mensajes Automáticos
RI-80: Configuración Recordatorios Automáticos
RI-81: Botón Ver Reportes
RI-82: Botón Exportar en PDF
RI-83: Botón Exportar en Excel
RI-84: Botón Ver Agenda
RI-85: Botón Aceptar Cita
RI-86: Botón Completada
RI-87: Botón Pendiente
RI-88: Botón Rechazar Cita
RI-89: Botón Historial Clientes Atendidos
RI-90: Consulta Datos Cliente
RI-91: Botón Configurar Horario Laboral
RI-92: Seleccionar Horas
RI-93: Seleccionar Fechas
RI-94: Botón Configurar Disponibilidad Semanal
RI-95: Ingresar Días Hábiles
RI-96: Ingresar Hora de Entrada y Salida

---
