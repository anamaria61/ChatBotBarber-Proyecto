# ChatBotBarber-Proyecto 💈

> **ChatBotBarber** es un sistema automatizado que permite agendar citas de barbería de forma rápida y sencilla a través de WhatsApp. Optimiza la gestión de tu negocio, reduce la duplicidad y ofrece atención 24/7 a los clientes.

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
