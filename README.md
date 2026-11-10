<div align="center">

# Pedro José Bermúdez López

### Desarrollador Backend · Full Stack · Automatización de procesos

📍 Armenia, Quindío, Colombia · 🟢 Disponible de inmediato · Full-Time o remoto

[![Portafolio](https://img.shields.io/badge/Portafolio-peterjhosep31.dev-14304a?style=for-the-badge&logo=googlechrome&logoColor=white)](https://peterjhosep31.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectemos-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/peterjhosep31)
[![Correo](https://img.shields.io/badge/Correo-Escríbeme-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bermudezlopezpedrojose@gmail.com)

</div>

---

## `whoami`

```ts
const pedro = {
  rol:         "Backend / Full Stack / Automatización",
  experiencia: "~3 años en software empresarial (PHP + MySQL)",
  formacion:   "Tecnólogo en Análisis y Desarrollo de Software · SENA",
  hago:        ["APIs REST seguras", "bots y chatbots", "web scraping", "tareas programadas"],
  meGusta:     "convertir tareas manuales de horas en minutos",
  buscando:    "rol backend, full stack o automatización · Armenia o remoto",
};
```

- 🔧 Rediseñé desde cero el **módulo de inventario** de una aplicación empresarial.
- ⚡ Construí un **bot que redujo una tarea de 3–4 horas a unos 10 minutos**.
- 💬 Desarrollé un **chatbot de WhatsApp** (API de Meta) y la asignación de sesiones a agentes en un sistema de atención tipo PBX.

---

## 🚀 Proyectos

### 📦 [PTR — Gestor de paquetes](https://github.com/peterjhosep31/ptr-package-manager) · *código abierto*
CLI + API REST que resuelve dependencias, automatiza builds y trae un **chatbot integrado** que ayuda con la instalación y las dudas del proyecto. Desplegado con Docker.
`TypeScript` `Node.js` `Express` `Docker`

### 🔐 ConfigManager — Gestor de credenciales *(vault)* · [demo en vivo](https://configmanager.peterjhosep31.dev/)
Guarda y comparte secretos entre servicios y equipos sin exponerlos en texto plano.
- API firmada: **HMAC-SHA256** por petición, **nonce** de un solo uso y respuestas firmadas
- **MFA/TOTP** y **Magic Links**, roles y permisos por sección
- Secretos cifrados en reposo con **AES-256-GCM**
- Expuesto por **Cloudflare Tunnel**, sin abrir puertos

`Node.js` `TypeScript` `Express` `React` `SQLite` `Docker Compose`

### 🐖 Sistema de gestión porcícola · *full stack*
Ciclo reproductivo, engorde, inventario de cuidos con facturación, capital e inversores y **scraping diario** del precio del cerdo en pie.
- ~80 endpoints en 12 routers, arquitectura por capas
- **JWT** con refresh token en cookie HttpOnly, **OTP** por WhatsApp o email, roles y rate limiting
- **104 pruebas automatizadas** (pytest + vitest) y migraciones con Alembic

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `React` `TypeScript`

> 🔒 ConfigManager y el sistema porcícola son repositorios privados. Si te interesa ver el código, escríbeme y te doy acceso.

---

## 🧱 Cómo construyo

```mermaid
flowchart LR
    C[Cliente<br/>React · TypeScript] -->|HTTPS| T[Cloudflare Tunnel]
    T --> A[API REST<br/>Node/Express · FastAPI]
    A --> S[Servicios<br/>reglas de negocio]
    S --> D[(MySQL · PostgreSQL · SQLite)]
    A --> J[Tareas programadas<br/>scraping · bots]
    A --> M[APIs externas<br/>WhatsApp · email]
```

Capas claras (modelos → schemas → servicios → routers), seguridad desde el diseño (firmas, MFA, cifrado en reposo), pruebas automatizadas y despliegue con Docker.

---

## 🛠️ Tecnologías

**Backend**
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Datos**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Herramientas e infraestructura**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

<div align="center">

**¿Tienes una vacante de backend, full stack o automatización?**
[Escríbeme](mailto:bermudezlopezpedrojose@gmail.com) · [Mira mi portafolio](https://peterjhosep31.dev)

</div>
