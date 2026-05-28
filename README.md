# DB-Coursework-2026-2

Repositorio de entrega para la asignatura de Bases de Datos (semestre 2026-2).

## Instrucciones de entrega — Fork y Pull Request

Cada estudiante debe integrar su proyecto a este repositorio mediante un Pull Request (PR) desde su fork. Sigue este procedimiento y el formato de ejemplo: https://github.com/gabrielhuav/DB-Coursework-2026-1

Pasos rápidos para enviar tu PR:

1. Haz fork de este repositorio a tu cuenta de GitHub.
2. Clona tu fork localmente:

```bash
git clone https://github.com/<tu-usuario>/DB-Coursework-2026-2.git
cd DB-Coursework-2026-2
```

3. Modifica el `README.md` y


4. Haz commit y push a tu fork (usa `main` o una rama propia):

```bash
git add <tu-usuario>
git commit -m "Add project for <tu-usuario>"
git push origin main
```

6. Abre un Pull Request desde tu fork hacia `gabrielhuav/DB-Coursework-2026-2` (base: `main`).

Recomendaciones para el PR:

- Título sugerido: `Add <nombre corto del proyecto>`
- En la descripción incluye:
	- Nombre completo y matrícula
	- Resumen del proyecto (2–3 líneas)
	- Pasos para ejecutar y comprobar la entrega
	- Notas sobre requisitos especiales (puertos, credenciales de prueba, etc.)
- Mantén todos los archivos del proyecto dentro de tu carpeta. No modifiques carpetas de otros estudiantes ni archivos globales.

Plantilla breve para la descripción del PR:

# Proyecto3: MANTRA — Red social de eventos

MANTRA es una plataforma web tipo red social enfocada en la publicación, descubrimiento e interacción alrededor de eventos. El sistema permite que los usuarios se registren según su rol: asistidor u organizador. Los asistidores pueden descubrir eventos, confirmar asistencia, comentar, dejar reseñas, seguir organizadores, agregar amigos y usar chat. Los organizadores pueden publicar eventos con imágenes promocionales, administrar sus eventos y consultar métricas básicas.

## 🛠️ Tecnologías implementadas

**Backend:** Node.js con Express.js
**Base de Datos:** PostgreSQL en Render
**Frontend:** HTML, CSS y JavaScript
**Almacenamiento de imágenes:** Cloudinary
**Despliegue:** Render
**Control de versiones:** Git y GitHub

## ✨ Funcionalidades principales

* Registro e inicio de sesión de usuarios.
* Manejo de roles: asistidor, organizador y owner.
* Publicación de eventos por organizadores.
* Subida de imágenes promocionales usando Cloudinary.
* Feed de eventos para usuarios asistentes.
* Confirmación de asistencia a eventos.
* Sistema de reseñas y calificaciones.
* Comentarios en eventos.
* Seguimiento de organizadores.
* Perfil de usuario con foto, biografía e intereses.
* Comunidad tipo red social con publicaciones, imágenes y likes.
* Solicitudes de amistad entre usuarios.
* Notificaciones.
* Logros de usuario.
* Chat básico entre amigos.
* Dashboard de organizador con métricas.

## 🖼️ Capturas de pantalla

### Landing page

<img src="./capturas/landing.png" alt="Landing page de MANTRA" loading="lazy" width="700">

### Feed de eventos

<img src="./capturas/feed-eventos.png" alt="Feed de eventos" loading="lazy" width="700">

### Dashboard organizador

<img src="./capturas/dashboard-organizador.png" alt="Dashboard del organizador" loading="lazy" width="700">

### Comunidad

<img src="./capturas/comunidad.png" alt="Comunidad MANTRA" loading="lazy" width="700">

### Perfil de usuario

<img src="./capturas/perfil.png" alt="Perfil de usuario" loading="lazy" width="700">

### Chat

<img src="./capturas/chat.png" alt="Chat entre usuarios" loading="lazy" width="700">

## 🔗 Enlaces

**Repositorio del proyecto:**
https://github.com/JULIO-MILAN/mantra-backend

**Demo en vivo:**
https://mantra-backend-24g1.onrender.com/


## 📂 Estructura general del proyecto

```txt
MANTRA/
├── index.js
├── package.json
├── index.html
├── feed-eventos.html
├── dashboard-organizador.html
├── perfil.html
├── comunidad.html
├── social.html
├── chat.html
└── capturas/
    ├── landing.png
    ├── feed-eventos.png
    ├── dashboard-organizador.png
    ├── comunidad.png
    ├── perfil.png
    └── chat.png
```
