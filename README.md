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

## 📌 OBJETIVOS 

### Objetivo General

Desarrollar un sistema de información mediante un Chatbot de WhatsApp, que
automatice el proceso de agendamiento de citas para múltiples barberías.

---

### Objetivos Específicos

1. **Levantar y documentar** los requerimientos funcionales y no funcionales
mediante técnicas de recolección de información para definir las necesidades
de clientes, barberos y administradores.

2. **Diseñar la arquitectura** del sistema y los flujos conversacionales del Chatbot
en WhatsApp, utilizando diagramas de casos de uso para establecer una
solución.

3. ** Desarrollar el sistema digital** de agendamiento de forma iterativa por medio
de Sprints, integrando módulos de registro, gestión de disponibilidad y
catálogo de servicios.

4. **Implementar un módulo de reportes** y control que permita al administrador
visualizar el rendimiento del sistema y la gestión de los barberos activos.

5. **Validar el funcionamiento del sistema** con los usuarios finales para realizar
ajustes en la documentación y asegurar que el sistema sea eficiente y
eliminar los errores de doble asignación de turnos.

---

## 💎 Valor del Producto

El producto reduce la carga operativa del personal de la barbería, minimiza errores de agenda,
mejora la experiencia del cliente al ofrecer disponibilidad 24/7 y facilita la toma de decisiones
mediante reportes y estadísticas. El ChatBot permite una interacción ágil y moderna, reduciendo la
necesidad de intervención humana en tareas repetitivas.

---

## ⚙️ Requisitos de las Interfaces

### 💻 Interfaz de Hardware
* El sistema funcionará en servidores web estándar con capacidad para soportar al menos 500 usuarios concurrentes.
* Compatible con dispositivos móviles, tablets y computadoras de escritorio.
* No requiere hardware especializado.

---

### 🔌 Interfaz de Software
* **Backend:** 
*(Cerebro detrás de escena. Lógica de negocio, procesamiento de datos y seguridad)*
  * Python 
  * FastAPI

* **Frontend:** 
*(Cara visible de la aplicación con la que interactúa el usuario)*
  * React 
  * HTML 
  * CSS

* **Base de datos:** 
*(Almacén digital estructurado donde se guarda y organiza toda la información del sistema de forma  permanente)*
  * PostgreSQL 

* **Servicio de correo:** 
*(Sistema especializado en el envío automatizado transaccional evitando la bandeja de SPAM)*
  *  SMTP para envío de notificaciones y recuperación de contraseñas.

* **ChatBot:** 
*(Programa informático para simular conversaciones 24/7)*
  * Integración con API de Dialogflow
  * API de WhatsApp

---

### 🌐 Interfaz de Comunicación
* **Protocolo:** HTTPS para todas las comunicaciones cliente-servidor.
* **Autenticación:** JWT(JSON Web Tokens) con expiración para transmisión segura de identidad.
* **Tiempo Real:** WebSockets para actualización instantánea de disponibilidad y notificaciones.
* **Correos electrónicos:** Confirmaciones, recordatorios, recuperación de contraseña, alertas de cancelación.
* **Exportación de datos:** Formats PDF y Excel para reportes.

---

## 🛠️ Requisitos Funcionales (RF)

| :--- | :--- | 
| RF-01: Crear Cuenta | RF-47: Ver Disponibilidad |
| RF-02: Digitar Nombre | RF-48: Solicitar Datos Cliente |
| RF-03: Digitar Correo | RF-49: Registrar Datos Cliente |
| RF-04: Digitar Confirmación Correo | RF-50: Reprogramar Cita |
| RF-05: Digitar Teléfono | RF-51: Poner Nueva Fecha y Hora |
| RF-06: Iniciar Sesión | RF-52: Validar Disponibilidad |
| RF-07: Digitar nombre_usuario | RF-53: Cancelar Cita |
| RF-08: Digitar Contraseña | RF-54: Notificar Cancelación |
| RF-06: Iniciar Sesión | RF-55: Notificar |
| RF-07: Digitar nombre_usuario | RF-56: Mandar Notificaciones |
| RF-08: Digitar Contraseña | RF-57: Enviar Confirmación |
| RF-09: Recuperar contraseña | RF-58: Enviar Recordatorios |
| RF-10: Ingresar Correo de Recuperación | RF-59: Notificar Cancelación |
| RF-11: Digitar Rol | RF-60: Soporte Técnico | RF-61: Enseñar Información |
| RF-12: Interacción con el ChatBot | RF-62: Mostrar Correo |
| RF-13: Enviar Mensajes | RF-63: Mostrar Teléfono |
| RF-14: Agendar Cita | RF-64: Ver Buzón de PQR |
| RF-15: Consultar Disponibilidad | RF-65: Gestionar Servicios |
| RF-16: Seleccionar Servicio | RF-66: Añadir Servicio |
| RF-17: Elegir Barbero | RF-67: Modificar Servicio |
| RF-18: Seleccionar Fecha y Hora | RF-68: Eliminar Servicio |
| RF-19: Recibir Notificaciones | RF-69: Gestionar Barberos |
| RF-20: Enviar Recordatorios | RF-70: Añadir Barbero |
| RF-21: Reprogramar Cita | RF-71: Modificar Barbero |
| RF-22: Ver Cita | RF-72: Eliminar Barbero |
| RF-23: Seleccionar Cita | RF-73: Ver estadísticas por barbero |
| RF-24: Editar Cita | RF-74: Gerstionar Clientes |
| RF-25: Consultar Cita | RF-75: Ver historial de citas por cliente |
| RF-26: Ver Estado Cita | RF-76: Acceder a datos de contacto |
| RF-27: Cancelar Cita | RF-77: Importar/Exportar base de datos del cliente |
| RF-28: Perfil | RF-78: Configurar ChatBot | 
| RF-29: Editar Datos Personales | RF-79: Establecer mensajes automáticos |
| RF-30: Ver Historial de Citas | RF-80: Establecer recordatorios automáticos |
| RF-31: Soporte/Contacto | RF-81: Ver Reportes |
| RF-32: Ver Buzón de PQR | RF-82: Exportar PDF |
| RF-33: Peticiones | RF-83: Exportar Excel |
| RF-34: Quejas | RF-84: Ver Agenda |
| RF-35: Reclamos | RF-85: Aceptar Cita |
| RF-36: Sugerencias | RF-86: Marcar Completada |
| RF-37: Contactar una Persona | RF-87: Marcar Pendiente |
| RF-38: Llamar a Soporte | RF-88: Rechazar Cita |
| RF-39: Iniciar Conversación | RF-89: Ver Historial Clientes atendidos |
| RF-40: Saludar | RF-90: Acceder a Datos Básicos del Cliente |
| RF-41: Mostrar Menú | RF-91: Configurar Horario Laboral |
| RF-42: Agendar Cita | RF-92: Seleccionar Horas Disponibles |
| RF-43: Recopilar Servicio Escogido | RF-93: Seleccionar Fechas Disponibles |
| RF-44: Recopilar Barbero | RF-94: Configurar Disponibilidad Semanal |
| RF-45: Validar Disponibilidad | RF-95: Definir Días Hábiles |
| RF-46: Revisar Calendario | RF-96: Definir Hora Entrada y Salida |

---

## 🔒 Requisitos No Funcionales (RNF)

### 🛡️ Seguridad

RNF-01: Seguridad de Datos. El sistema debe proteger la información y los datos mediante cifrado seguro, las contraseñas
deben almacenarse con hash bcrypt (costo 10). Correos y teléfonos en base de datos cifrada.

RNF-09: Integridad de Datos. El sistema debe evitar pérdida de información.

RNF-10: Confidencialidad. El sistema debe garantizar privacidad de datos.

RNF-11: Autenticación. El sistema debe validar usuarios antes del acceso.

RNF-20: Auditoría. El sistema debe registrar cambios importantes, en log inmutable: creación, modificación y
cancelación de citas, con ID de usuario, timestamp y datos previos/nuevos.

### ⚡ Capacidad

RNF-03: Rendimiento. El 95% de las peticiones (login, agendar, consultar disponibilidad) deben resolverse en ≤ 2
segundos, midiendo desde el servidor con 100 usuarios concurrentes.

RNF-13: Actualización Tiempo Real. El sistema debe actualizar información instantáneamente.

### 📱 Compatibilidad

RNF-05: Compatibilidad. El sistema debe funcionar en diferentes dispositivos.

RNF-12: Compatibilidad Navegadores. El sistema debe funcionar en varios navegadores (Chrome, Firefox, Edge y Safari).

RNF-15: Compatibilidad BD. El sistema debe integrarse con la base de datos.

RNF-22: Compatibilidad Móvil. El sistema debe adaptarse a celulares y tablets.

### 💎 Confiabilidad

RNF-02: Disponibilidad. El sistema debe estar disponible las 24 horas y ser operativo 99.9% del tiempo.

RNF-07: Respaldo de información. La base de datos debe respaldarse cada 24 horas. El respaldo debe ser restaurable en menos
de 2 horas.

RNF-14: Disponibilidad ChatBot. El chatbot debe estar activo permanentemente.

RNF-16: Manejo de errores. El sistema debe controlar errores correctamente, cualquier excepción no controlada debe mostrar al usuario un mensaje amigable "Ocurrió un error inesperado. Inténtalo más tarde." y registrar error interno

### 📈 Escalabilidad y Mantenibilidad

RNF-04: Escalabilidad. El sistema debe soportar al menos 500 usuarios concurrentes con tiempo de respuesta ≤ 3 segundos, agregando instancias del backend.

RNF-18: Modularidad. El sistema debe dividirse en módulos independientes.

RNF-19: Portabilidad. El sistema debe funcionar en distintos entornos.

### 🎨 Facilidad de uso

RNF-06: Interfaz intuitiva. El sistema debe ser fácil de usar.

RNF-08: Accesibilidad. El sistema debe ser accesible para todos los usuarios.

RNF-17: Facilidad aprendizaje. Un usuario nuevo debe completar el flujo de agendar una cita en menos de 3 minutos, sin asistencia externa (medido con 5 usuarios).

RNF-21: Experiencia usuario. El sistema debe brindar una buena experiencia fluida.

RNF-24: Diseño. El sistema debe adaptarse a diferentes pantallas sin barras de desplazamiento horizontales no
deseadas.

### 🎨 Otro 

RNF-23: Validación datos. El sistema debe validar datos ingresados.

---

## 💬 Requisitos de Interfaz Externa

| :--- | :--- |
| RI-01: Botón Registrarse / Crear Cuenta | RI-49: Registrar Datos |
| RI-02: Ingresar Nombre | RI-50: Mensaje de Reprogramar Cita |
| RI-03: Ingresar Correo | RI-51: Dar Nueva Fecha y Hora |
| RI-04: Ingresar Confirmación Correo | RI-52: Confirmación de Disponibilidad |
| RI-05: Ingresar Teléfono | RI-53: Mensaje de Cancelar Cita |
| RI-06: Botón Iniciar Sesión | RI-54: Envío de Mensaje de Cancelación |
| RI-07: Ingresar nombre de usuario | RI-55: Mensajes de Notificaciones |
| RI-08: Ingresar contraseña | RI-56: Mensajes de Notificaciones |
| RI-09: Botón Olvidé mi Contraseña | RI-57: Mensaje de Confirmación |
| RI-10: Digitar Correo | RI-58: Mensaje de Recortarios |
| RI-11: Ingresar Rol | RI-59: Mensaje de Cancelación |
| RI-12: Interacción ChatBot | RI-60: Asistencia Técnica |
| RI-13: Envío de Mensajes | RI-61: Opción Enseñar Información |
| RI-14: Manejo de Citas | RI-62: Mostrar Correo |
| RI-15: Consulta de Disponibilidad | RI-63: Mostrar Teléfono |
| RI-16: Opciones de Servicio | RI-64: Botón Buzón de PQR |
| RI-17: Opciones de Barbero | RI-65: Botón Gestionar Servicios |
| RI-18: Elección Fecha y Hora | RI-66: Botón Agregar |
| RI-19: Recibir Notificaciones | RI-67: Botón Modificar |
| RI-20: Recordatorios Automáticos | RI-68: Botón Eliminar |
| RI-21: Mensaje Reprogramar Cita | RI-69: Botón Gestionar Barberos |
| RI-22: Opción Ver Cita | RI-70: Botón Agregar |
| RI-23: Seleccionar Cita | RI-71: Botón Modificar |
| RI-24: Opción Editar Cita | RI-72: Botón Eliminar |
| RI-25: Consultar Cita | RI-73: Botón Ver Estadísticas |
| RI-26: Opción Ver Estado de la Cita | RI-74: Botón Gestionar Clientes |
| RI-27: Mensaje Cancelar Cita | RI-75: Botón Ver historial Clientes |
| RI-28: Botón Perfil | RI-76: Botón Acceder a Datos | 
| RI-29: Botón Actualizar Datos | RI-77: Botón Importar/Exportar BD |
| RI-30: Botón Ver Historial de Citas | RI-78: Personalización ChatBot |
| RI-31: Botón de Soporte | RI-79: Configuración Mensajes Automáticos |
| RI-32: Botón Buzón de PQR | RI-80: Configuración Recordatorios Automáticos |
| RI-33: Opción de Peticiones | RI-81: Botón Ver Reportes |
| RI-34: Opción de Quejas | RI-82: Botón Exportar en PDF |
| RI-35: Opción de Reclamos |  RI-83: Botón Exportar en Excel |
| RI-36: Opción de Sugerencias | RI-84: Botón Ver Agenda |
| RI-37: Botón Contactar Persona | RI-85: Botón Aceptar Cita |
| RI-38: Botón Llamar a Soporte | RI-86: Botón Completada |
| RI-39: Inicio Conversación ChatBot | RI-87: Botón Pendiente |
| RI-40: Mensaje de Saludo | RI-88: Botón Rechazar Cita |
| RI-41: Mensaje de Menú | RI-89: Botón Historial Clientes Atendidos |
| RI-42: Mensaje de Agendar Cita | RI-90: Consulta Datos Cliente |
| RI-43: Mensaje de Servicio Escogido | RI-91: Botón Configurar Horario Laboral |
| RI-44: Mensaje de Barbero Escogido | RI-92: Seleccionar Horas |
| RI-45: Verificación de Disponibilidad | RI-93: Seleccionar Fechas |
| RI-46: Revisar el Calendario | RI-94: Botón Configurar Disponibilidad Semanal |
| RI-47: Consulta de Disponibilidad | RI-95: Ingresar Días Hábiles |
| RI-48: Mensaje de Solicitud de Datos | RI-96: Ingresar Hora de Entrada y Salida |

---

## Definiciones y Acrónimos

| Acrónimo / Término | Definición Completa | Descripción en el Proyecto |
| :--- | :--- | :--- |
| **SRS** | *Software Requirements Specification* | Documento formal de Especificación de Requisitos de Software. |
| **RF** | Requisito Funcional | Acción o comportamiento directo que el software debe ejecutar. |
| **RNF** | Requisito No Funcional | Atributos de calidad o restricciones del sistema (seguridad, velocidad). |
| **RI** | Requisito de Interfaz | Elementos visuales, botones o pantallas de cara al usuario. |
| **PQR** | Peticiones, Quejas y Reclamos | Módulo de atención para el feedback y soporte del cliente. |
| **ChatBot** | Bot Conversacional | Programa automático que interactúa mediante lenguaje natural (WhatsApp). |
| **Responsivo** | *Responsive Design* | Capacidad del diseño de amoldarse a celulares, tablets o monitores. |
| **BD** | Base de Datos | Almacenamiento estructurado en PostgreSQL para persistencia de datos. |
| **PDF / Excel** | Formatos de Archivo | Formatos de salida para la generación y exportación de reportes. |
| **API** | *Application Programming Interface* | Interfaz que conecta el backend con WhatsApp o Dialogflow. |
| **HTTPS** | *Hypertext Transfer Protocol Secure* | Protocolo web seguro que encripta la comunicación cliente-servidor. |
| **SQL** | *Structured Query Language* | Lenguaje utilizado para gestionar y consultar la base de datos. |
| **SMTP** | *Simple Mail Transfer Protocol* | Protocolo para el envío automático de correos electrónicos. |
| **JWT** | *JSON Web Token* | Token compacto y seguro para validar sesiones de usuarios en la API. |
| **WebSockets** | ** | Protocolo de comunicación que crea un canal de comunicación directo, bidireccional y continuo entre un cliente(el navegador) y un servidor. |