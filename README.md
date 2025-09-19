# 🌱 PlantAlo – App de Huerta Comunitaria (Open Source)

> Una aplicación web open-source para gestionar huertas comunitarias, familiares o escolares. Ideal para promover el cuidado colaborativo de las plantas en proyectos educativos, barriales o personales.

---

## 🧠 Descripción

**PlantAlo** es una herramienta digital para ayudar a grupos de personas a cuidar y registrar sus plantas de forma colaborativa. Está diseñada para ser simple, libre y accesible para cualquier comunidad, familia, escuela o espacio que desee mantener una huerta, jardín o espacio verde.

Está construida con tecnologías modernas como Angular y .NET, y pensada para funcionar **offline**, en celulares o computadoras, sin depender de servicios externos.

---

## 🚀 Funcionalidades (MVP)

- 🪴 Gestión de plantas con fichas, fotos y fechas importantes  
- 📅 Registro de eventos: riego, poda, fertilización, cosecha, etc.  
- 👨‍👩‍👧 Familias/grupos: usuarios organizados por "hogares" o espacios comunes  
- 📊 Estadísticas por planta o por usuario  
- 🔔 Notificaciones locales y en tiempo real (opcional)  
- 🌐 Multilenguaje (español, inglés)  
- 🎨 Modo claro y oscuro con theming SCSS  
- 📱 Instalación como app (PWA) + soporte para Android (Capacitor)

---

## 🧱 Tecnologías utilizadas

| Capa         | Stack tecnológico                           |
|--------------|----------------------------------------------|
| Frontend     | Angular 20 (standalone components, SCSS, ngx-translate) |
| Backend      | .NET 10 + PostgreSQL                          |
| Realtime     | SignalR (opcional)                           |
| Hosting      | Docker-ready (local o nube)                  |
| Mobile       | Capacitor (opcional para Android)            |

---

## ✨ Objetivos

- Democratizar el acceso a herramientas de gestión para huertas
- Promover el trabajo colaborativo y el aprendizaje agroecológico
- Fomentar la soberanía alimentaria y la conexión con la naturaleza

---

## 🛠️ Instalación (Próximamente)

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/plantalo.git

# Frontend
cd frontend
npm install
ng serve

# Backend
cd backend
dotnet restore
dotnet ef database update
dotnet run
```

Próximamente: archivos Docker y docker-compose.yml para despliegue local

📦 Roadmap
- Estructura inicial Angular + .NET
-  CRUD de plantas y eventos
-  Vistas para familias y usuarios
-  Modo offline (PWA)
-  Multilenguaje e interfaz accesible
-  Deploy en plataformas gratuitas (Render, Vercel, Railway)

🤝 Contribuciones

¿Querés ayudar? ¡Sos más que bienvenido/a!
- 📥 Abrí un issue para sugerencias o reportes
- 💻 Enviá un PR con nuevas ideas o mejoras
- 🌍 Ayudanos a traducir la app a otros idiomas
- 📄 Licencia

Este proyecto está bajo la licencia MIT
.

💚 Créditos

Desarrollado con ❤️ por Favio Leyva
 y colaboradores.
Inspirado por proyectos comunitarios, educativos y agroecológicos.
