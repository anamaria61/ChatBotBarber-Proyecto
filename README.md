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
&nbsp; * Python 
&nbsp; * FastAPI

* **Frontend:** 
Es la cara visible de la aplicación, todo lo que el usuario ve, toca e interactúa directamente. En aplicaciones web o móviles, incluye los botones, colores, menús y animaciones.
&nbsp; * React 
&nbsp; * HTML 
&nbsp; * CSS

* **Base de datos:** 
Es el almacén digital estructurado donde se guarda y organiza toda la información del sistema de forma permanente para que no se pierda al apagar el servidor.
* PostgreSQL 

* **Servicio de correo:** 
Es un sistema externo o interno especializado en el envío automatizado de correos electrónicos masivos o transaccionales (como confirmaciones, notificaciones o restablecimiento de contraseñas), evitando que estos mensajes caigan en la carpeta de SPAM.
&nbsp; * SMTP para envío de notificaciones y recuperación de contraseñas.

* **ChatBot:** 
Es un programa informático diseñado para simular una conversación con usuarios humanos, ya sea a través de texto o de voz. Funciona de forma automatizada respondiendo preguntas comunes, guiando al usuario en tareas específicas (como agendar una cita) y operando de manera ininterrumpida las 24 horas del día.
&nbsp; * Integración con API de Dialogflow
&nbsp; * API de WhatsApp

## Requisitos de la interfaz de comunicación

* **Protocolo:** HTTPS para todas las comunicaciones cliente-servidor.

* **Autenticación:** JWT(JSON Web Tokens) con expiración.

JWT es un estándar abierto utilizado para transmitir información de forma segura entre partes en formato JSON. Se usa principalmente para la autenticación y autorización de usuarios.

* **Tiempo Real:** WebSockets para actualización de disponibilidad y notificaciones.

WebSockets es un protocolo de comunicación que permite un canal de comunicación bidireccional y en tiempo real entre el usuario (navegador/cliente) y el servidor a través de una única conexión abierta. Una vez abierta la conexión, tanto el cliente como el servidor pueden enviarse datos en cualquier momento, de forma instantánea y sin esperas.

* **Correos electrónicos:** Confirmaciones, recordatorios, recuperación de contraseña, alertas de cancelación.

* **Exportación de datos:** Formats PDF y Excel para reportes.
