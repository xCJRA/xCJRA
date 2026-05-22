# 👋 Hola, soy César Reyes

**Backend Developer · APIs REST · Integración de Sistemas**  
📍 Tepotzotlán, México &nbsp;|&nbsp; 📧 cesarjreyesa1@gmail.com &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/xCJRA/) &nbsp;|&nbsp; [GitHub](https://github.com/xCJRA)

---

## 🚀 Sobre mí

Backend Developer con **más de 3 años de experiencia** diseñando e integrando APIs REST en entornos de producción. He automatizado procesos críticos de negocio —pagos, facturación electrónica y firmas electrónicas (ESignature)— logrando reducir trabajo manual hasta un **50%** y tiempos de inactividad entre un **40% y 60%**.

- 🎯 Especializado en **facturación electrónica (CFDI)**, **pasarelas de pago** y **firma electrónica** — integrandolos a sistemas funcionales.
- 🔧 Experiencia en **integración de APIs externas** (Stripe, MercadoPago, SAT, Twilio) y automatización de flujos operativos.
- 🧠 Orientado a **clean code**, documentación Swagger/OpenAPI y buenas prácticas de arquitectura REST.
- 🌍 Disponible para oportunidades **remotas** o **presenciales** (condiciones negociables).

---

## 💼 Experiencia profesional

### 🔹 Freelance — Backend Developer
📍 Remoto &nbsp;·&nbsp; 🗓️ Abril 2026 – Presente

- Desarrollo de soluciones backend a medida para clientes del sector privado.
- Entrega de resultados orientados a necesidades específicas del negocio.

---

### 🔹 Zora Systems — Backend Developer (PHP)
📍 Santa Fe, CDMX &nbsp;·&nbsp; 🗓️ Abril 2022 – Marzo 2026

- Resolví incidencias críticas en producción, reduciendo tiempos de inactividad entre un **40% y 60%** mediante diagnóstico rápido y soluciones preventivas.
- Diseñé e implementé **APIs REST** e integraciones con servicios externos (pagos, facturación electrónica, firmas electrónicas, generación de PDFs), automatizando procesos clave y reduciendo trabajo manual en **~50%**.
- Optimicé consultas en **MySQL** logrando mejoras de rendimiento entre un **30% y 50%** en módulos críticos.
- Desarrollé funcionalidades a medida con base en requerimientos de clientes, mejorando la eficiencia operativa.

---

### 🔹 H. Ayuntamiento de Tepotzotlán — Junior SQL Developer
📍 Tepotzotlán, México &nbsp;·&nbsp; 🗓️ Enero 2020 – Agosto 2020

- Diseñé una base de datos para control de registros administrativos.
- Implementé un sistema de reportes que redujo el tiempo de obtención de información en **~60%**.

---

### 🔹 Hospital Regional de Alta Especialidad — Backend Developer (PHP)
📍 Zumpango, México &nbsp;·&nbsp; 🗓️ Enero 2019 – Agosto 2019

- Desarrollé un sistema web para el registro y seguimiento de incidencias, mejorando trazabilidad de procesos internos.
- Colaboré en el análisis de requerimientos con el personal operativo, reduciendo tiempos de gestión.

---

## 🛠️ Tech Stack

### Lenguajes
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Frameworks y herramientas
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## 📂 Proyectos de Portafolio

> Proyectos construidos sobre dominios de negocio reales del mercado mexicano. Todos documentados con Swagger y siguiendo Conventional Commits.

---

### 🧾 [API de Facturación Electrónica (CFDI)](https://github.com/xCJRA/laravel-cfdi-api)
**Stack:** `Laravel 11` · `MySQL` · `Sanctum` · `Swagger`

API REST que simula el flujo completo de generación y consulta de CFDIs (facturas electrónicas mexicanas). Incluye validación de RFC, cálculo automático de IVA, generación de folios UUID y manejo de estados (borrador → emitida → cancelada).

**Lo que demuestra:** Conocimiento del dominio fiscal mexicano · Diseño REST · Autenticación con tokens · Documentación Swagger

---

### 💳 [Pasarela de Pagos Unificada](https://github.com/xCJRA/laravel-payment-gateway)
**Stack:** `Laravel 11` · `MySQL` · `Stripe SDK` · `MercadoPago API` · `Swagger`

API que abstrae Stripe y MercadoPago detrás de una interfaz unificada usando el patrón **Strategy**. Un solo endpoint para cobrar, reembolsar y recibir webhooks de ambas pasarelas. Incluye log de auditoría de transacciones.

**Lo que demuestra:** Patrón Strategy / Interface · Integración con APIs de pago · Manejo de webhooks · Arquitectura limpia

---

### 📬 [Sistema de Notificaciones Multi-canal](https://github.com/xCJRA/node-notifications-api)
**Stack:** `Node.js` · `Express` · `MySQL` · `Nodemailer` · `Twilio` · `JWT` · `Swagger`

API en Node.js que recibe notificaciones y las enruta automáticamente por email (Gmail SMTP), WhatsApp (Twilio sandbox) o SMS simulado. Incluye reintentos automáticos (hasta 3 intentos), autenticación JWT e historial filtrable.

**Lo que demuestra:** Node.js funcional · Arquitectura de servicios · Integración de APIs externas · Documentación profesional

---

### ✍️ [API de Firma Electrónica de Documentos](https://github.com/xCJRA/laravel-firma-digital)
**Stack:** `Laravel 11` · `MySQL` · `DomPDF` · `Sanctum` · `Swagger`

API que gestiona el ciclo completo de firma electrónica: subida de documentos, registro de firmantes con orden secuencial, validación de tokens, registro de firma con timestamp e IP, y generación del PDF final con tabla de firmas. Tokens con expiración configurable y log de auditoría completo.

**Lo que demuestra:** Lógica de negocio compleja · Manejo de estados · Seguridad con tokens · Generación de PDFs · Dominio de alto valor

---

## 🌱 Actualmente aprendiendo

- **PostgreSQL** — migrando conocimiento de MySQL a un motor más robusto
- **GitHub Actions** — CI/CD para automatizar tests y despliegues
- **Arquitectura backend avanzada** — patrones de diseño aplicados a APIs REST

---
## 📫 Contacto

¿Tienes un proyecto o posición que requiera experiencia en **APIs REST, integración de sistemas o dominio fiscal/pagos en México**? Hablemos.

- 💼 [LinkedIn](https://www.linkedin.com/in/xCJRA/)
- 📧 cesarjreyesa1@gmail.com
- 📍 Tepotzotlán, México
