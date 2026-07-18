<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a6bff&height=220&section=header&text=Julio%20Castro%20Alejos&fontColor=ffffff&fontSize=42&fontAlignY=35&desc=Full%20Stack%20Developer%20%7C%20Software%20Engineering%20Student&descColor=58a6ff&descSize=18&descAlignY=55&animation=fadeIn" />

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juliocastroalejos/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JulioXC4)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:julioc4.dev@gmail.com)

</div>

## Sobre Mí

Soy estudiante de Ingeniería de Software con experiencia práctica desarrollando sistemas empresariales reales. Mi base es el desarrollo backend, pero estoy creciendo activamente hacia el **Full Stack** — he trabajado en proyectos que abarcan desde APIs REST y sistemas IoT hasta aplicaciones móviles e interfaces web completas.

Recientemente finalicé mis prácticas preprofesionales en **Devdatep Consulting**, donde participé en el desarrollo de un sistema de facturación electrónica integrado con la SUNAT. Trabajar en un sistema del que dependen negocios reales me dio una fuerte apreciación por la arquitectura limpia, las integraciones confiables y el código que otras personas realmente tienen que mantener.

Me gusta entender los problemas de punta a punta — desde el requerimiento de negocio hasta la consulta a base de datos. Me importa escribir código limpio y documentado, y diseñar sistemas que escalen con propósito.

---

## 💼 Experiencia Profesional

### Backend Developer Intern · Devdatep Consulting
**2026 · Lima, Perú**

Participé en el desarrollo del sistema **EmiteFacil**, una plataforma SaaS de facturación electrónica para empresas peruanas.

- Diseñé e implementé APIs RESTful usando **Laravel 11** y **PHP 8.2**, siguiendo arquitectura orientada a servicios (SOA) con patrones Repository y DTO
- Integración con **SUNAT** para generación de comprobantes electrónicos XML bajo estándar UBL
- Construí funcionalidades de validación de clientes mediante APIs externas de RUC y DNI
- Implementé autenticación con **Laravel Sanctum** y contribuí al catálogo de productos, gestión de series y generación de PDFs
- Participé en decisiones de arquitectura, documentación de APIs y procesos de revisión de código

---

## 🚀 Proyecto Destacado

<div align="center">

### 🔗 [Restock — Sistema IoT para Gestión de Inventarios en Restaurantes](https://github.com/desarrollo-de-soluciones-iot-17757)

</div>

> Sistema integral de gestión de inventarios basado en IoT diseñado para restaurantes. Combina sensores físicos de peso, temperatura y humedad, procesamiento edge, una API cloud, un dashboard web y una app móvil con soporte offline para automatizar completamente el control de stock.

<table>
<tr>
<td width="50%" valign="top">

**🔧 ¿Cómo funciona?**

1. Sensores de peso, temperatura y humedad conectados a microcontroladores **ESP32** monitorean los contenedores de ingredientes en tiempo real
2. Los datos se transmiten por protocolo **MQTT** hacia la capa edge
3. Un **servicio edge** (Python/Flask) filtra ruido, detecta cambios significativos y reenvía datos relevantes al cloud
4. El backend en **Spring Boot** con **DDD y CQRS** procesa la información, actualiza niveles de stock y dispara alertas
5. El **dashboard web** (Angular) muestra métricas en tiempo real con gráficos interactivos
6. La **app móvil** (Flutter + BLoC) permite monitoreo desde cualquier lugar con soporte offline via SQLite

</td>
<td width="50%" valign="top">

**📐 Arquitectura del Sistema**

| Componente | Tecnología |
|---|---|
| **Backend** | Spring Boot, Java, MongoDB, DDD, CQRS |
| **Frontend** | Angular, TypeScript, Angular Material |
| **App Móvil** | Flutter, Dart, BLoC, SQLite |
| **Edge** | Python, Flask, SQLite, Peewee ORM |
| **IoT** | ESP32, C++, MQTT, HX711, DHT |
| **Landing** | HTML, CSS, JavaScript |

</td>
</tr>
</table>

<details>
<summary><b>🔍 Ver características principales</b></summary>

<br>

- **Monitoreo en tiempo real** de peso, temperatura y humedad mediante sensores IoT
- **Edge Computing** — Procesamiento local antes de enviar datos al cloud, filtrando ruido y detectando cambios significativos
- **Alertas automáticas** cuando los ingredientes bajan del umbral configurado
- **Dashboard interactivo** con gráficos, analíticas y métricas de inventario
- **App móvil con modo offline** — Sincronización automática con almacenamiento local en SQLite
- **Domain-Driven Design** con bounded contexts y **CQRS** en el backend
- **Gestión de recetas** — Calculadora inteligente para control de costos y reducción de desperdicios
- **Patrón BLoC** para separación de lógica de negocio en la app móvil

</details>

---

## 📂 Otros Proyectos

<table>
<tr>
<td width="50%" valign="top">

### [🏥 Sistema de Citas Médicas](https://github.com/JulioXC4/gestion-citas-medicas)
Sistema full-stack de gestión de citas médicas con control de acceso por roles (Admin, Doctor, Paciente), autenticación JWT y validación de disponibilidad.

`Spring Boot` `Vue.js 3` `Pinia` `PostgreSQL` `JWT`

</td>
<td width="50%" valign="top">

### [🎫 Control de Acceso a Eventos](https://github.com/JulioXC4/event-access-control)
Sistema full-stack para check-in de eventos mediante escaneo de códigos QR. Backend con Clean Architecture y app móvil Flutter con Provider.

`Spring Boot` `Flutter` `PostgreSQL` `Clean Architecture`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [📦 Sistema de Inventario](https://github.com/JulioXC4/inventory-management-system)
Plataforma de gestión de inventario con roles (Admin, Almacenero, Empleado), alertas de stock, historial de movimientos y reportes PDF automatizados.

`Laravel 10` `Livewire 3` `MySQL` `TailwindCSS`

</td>
<td width="50%" valign="top">

### [✅ Task Manager](https://github.com/JulioXC4/task-manager-springboot)
API RESTful de gestión de tareas con Clean Architecture, autenticación JWT, control de acceso por roles y filtrado por estado, prioridad y rango de fechas.

`Spring Boot` `PostgreSQL` `JWT` `Clean Architecture`

</td>
</tr>
</table>

---

## 🛠️ Stack Tecnológico

### Lenguajes
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

### Backend
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

### Frontend & Móvil
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-FB70A9?style=flat-square&logo=livewire&logoColor=white)

### Bases de Datos
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

### Infraestructura & Herramientas
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=JulioXC4&theme=tokyonight&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" alt="GitHub Streak" />

</div>

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=JulioXC4&theme=tokyonight&hide_border=true" alt="Repos por lenguaje" />
&nbsp;
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=JulioXC4&theme=tokyonight&hide_border=true" alt="Lenguajes por commits" />
&nbsp;
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=JulioXC4&theme=tokyonight&hide_border=true" alt="Stats" />

</div>

---

## 🎯 Ruta de Aprendizaje y Crecimiento (Hacia Dónde Voy)

Mi meta a corto y mediano plazo es consolidar mi perfil como **Full Stack Developer** adquiriendo capacidades profundas en ingeniería y automatización. Actualmente estoy enfocando mi aprendizaje en:

* 🏗️ **Arquitectura de Software & Diseño**:
  * *Foco:* Domain-Driven Design (DDD), Clean Architecture, patrones de mensajería (MQTT, WebSockets) y diseño de microservicios.
  * *Propósito:* Diseñar sistemas desacoplados, tolerantes a fallos y fáciles de escalar.
* ☁️ **Cultura DevOps & Computación Cloud**:
  * *Foco:* Orquestación de contenedores, pipelines CI/CD (GitHub Actions) y administración de servicios cloud en Microsoft Azure.
  * *Propósito:* Automatizar el ciclo de vida del software para realizar entregas de valor constantes y estables.
* 💻 **Frontend Moderno**:
  * *Foco:* Profundizar en Angular y dominar patrones modernos de Vue.js 3 (Pinia y Composition API).
  * *Propósito:* Construir experiencias del lado del cliente fluidas, modulares y de alto rendimiento.
* 🤖 **Integración de Inteligencia Artificial**:
  * *Foco:* Aplicación práctica de servicios cognitivos y LLMs para optimizar procesos y automatizar tareas.
  * *Propósito:* Resolver problemas complejos del negocio mediante automatizaciones inteligentes.

---

<div align="center">

*"Construir cosas que funcionen. Documentar lo que importa. Mejorar lo que se puede medir."*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a6bff&height=120&section=footer" />
