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

## Proyecto 1: Booksnexus (Red social de libros)
Plataforma web tipo red social enfocada en lectores, donde los usuarios pueden registrarse, compartir reseñas, publicar opiniones sobre libros, seguir a otros usuarios y descubrir nuevas lecturas mediante interacción social.

### 🛠️ Tecnologías
* *Backend:* Node.js con Express.js
* *Base de Datos:* PostgreSQL (Supabase)
* *Frontend:* HTML, CSS y JavaScript vanilla (Fetch API)
* *Despliegue:* Render y GitHub pages

<details>
<summary>🖼️ Ver capturas de pantalla</summary>

| | |
|---|---|
| <img loading="lazy" src="URL_IMAGEN_1" alt="Vista principal de Booksnexus" width="800"/> | |
| <img loading="lazy" src="URL_IMAGEN_2" alt="Perfil de usuario" width="400"/> | <img loading="lazy" src="URL_IMAGEN_3" alt="Timeline de publicaciones" width="400"/> |
| <img loading="lazy" src="URL_IMAGEN_4" alt="Gestión de libros y reseñas" width="800"/> | |
</details>

### ✨ Funcionalidades principales
* Registro e inicio de sesión de usuarios
* Publicación de reseñas y opiniones de libros
* Sistema de seguidores y seguidos
* Timeline con publicaciones de usuarios seguidos
* Gestión de libros favoritos
* Persistencia de datos mediante PostgreSQL
* API REST para comunicación entre frontend y backend

### 🔗 Enlaces
Código Fuente Backend: [Repositorio Backend](https://github.com/Diegocstln/booksnexus-back)
Código Fuente Frontend: [Repositorio Frontend](https://github.com/Diegocstln/mi-proyecto-bd)
Demo en Vivo: [Booksnexus Web](https://diegocstln.github.io/mi-proyecto-bd/)

## Proyecto 2: DestinyCafe (Sistema de Gestión para Cafetería Artesanal)

Sistema web integral para la gestión de una cafetería artesanal ubicada en Reforma, CDMX, que atiende tanto a turistas como a locales. La plataforma permite administrar clientes, productos, insumos, inventario, proveedores, ventas y horarios de empleados, resolviendo necesidades reales de control de stock, trazabilidad de compras y análisis de experiencia del cliente.

###  Tecnologías

- **Frontend:** HTML5, CSS3 y JavaScript 
- **Base de Datos:** PostgreSQL (Supabase)
- **Despliegue:** GitHub Pages (Frontend) y Supabase Cloud (Backend y BD)

<details>
<summary> Ver imagenes del proyecto </summary>

| | |
|---|---|
| <img loading="lazy" src="https://github.com/PerlaSantos/DestinyCafe/blob/0aeb3ca476dc1d6d692dc9c9264c140ae76295cd/Principal.png" alt="Vista principal de DestinyCafe - Página de inicio" width="800"/> | |
| <img loading="lazy" src="https://github.com/PerlaSantos/DestinyCafe/blob/0aeb3ca476dc1d6d692dc9c9264c140ae76295cd/Areas.png" alt="Sección de áreas: Barra, Cocina y Panadería" width="400"/> | <img loading="lazy" src="https://github.com/PerlaSantos/DestinyCafe/blob/0aeb3ca476dc1d6d692dc9c9264c140ae76295cd/Inventario.png" alt="Formulario de registro de insumos" width="400"/> |
| <img loading="lazy" src="https://github.com/PerlaSantos/DestinyCafe/blob/0aeb3ca476dc1d6d692dc9c9264c140ae76295cd/Ventas.png" alt="Formulario de registro de ventas." width="800"/> | |
</details>

###  Funcionalidades principales

- **Control de Inventario:** Registro de insumos, stock actual, stock mínimo (alertas de reabastecimiento con 3-4 días de anticipación) y fechas de vencimiento.
- **Administración de Proveedores:** Catálogo de proveedores (Central de Abastos, Costco, Sam's Club, tiendas locales), registro de compras, facturas y reseñas.
- **Gestión de Ventas:** Registro de transacciones, detalles de venta, métodos de pago, propinas y descuentos. Generación de reportes semanales de productos más y menos vendidos.


###  Integrantes del equipo de desarrollo

- Alarcón Herrera Julio Alexis
- Cedillo Baeza Martha Clara
- Santos Martínez Perla

###  Enlaces para consultar el proyecto

- **Código Fuente (Frontend):** [Repositorio en GitHub](https://github.com/PerlaSantos/DestinyCafe.git)
- **Demo en Vivo:** [DestinyCafe Web](https://perlasantos.github.io/DestinyCafe/)

---
## Proyecto 3: Patitas Felices (Refugio de Animales)

Plataforma web para la gestión integral de un refugio de animales, donde los usuarios pueden registrarse, buscar mascotas disponibles, enviar solicitudes de adopción y>

### 🛠️ Tecnologías

- **Backend:** Node.js con Express.js
- **Base de Datos:** PostgreSQL (Supabase)
- **Frontend:** HTML, CSS (Bootstrap 5) y JavaScript vanilla (Fetch API)
- **Despliegue:** Render y GitHub Pages

### ✨ Funcionalidades principales

* Registro e inicio de sesión de adoptantes y trabajadores (con roles: admin, veterinario, voluntario)
* Catálogo de animales con filtros por especie y estado
* Sistema de solicitudes de adopción (envío, aprobación y rechazo)
* Historial médico por animal
* Panel de estadísticas en tiempo real (animales disponibles, adoptados, solicitudes pendientes)
* Subida de fotos de animales en Base64

<details>
<summary>🖼️ Ver capturas de pantalla</summary>

| | |
|---|---|
| <img loading="lazy" src="https://github.com/user-attachments/assets/c04a0b8e-cdf1-4da3-b722-79644c8aad3c" alt="Vista principal" width="400"/> | <img loading="lazy" src="https://github.com/user-attachments/assets/474219f5-2c2c-4ad9-83b8-eed15b6ec1d0" alt="Panel admin" width="400"/> |
| <img loading="lazy" src="https://github.com/user-attachments/assets/352f3878-9982-435f-8235-43ea6d21d938" alt="Solicitudes" width="400"/> | <img loading="lazy"
src="https://github.com/user-attachments/assets/a7156165-26d1-42fd-be91-c1a9f80dbd53" alt="Historial" width="400"/> |

</details>

### 🔗 Enlaces

- **Código Fuente:** [Repositorio en GitHub](https://github.com/JOKERKORIO/patitas-api)
- **Demo en Vivo (Railway):** [Patitas Felices API](https://patitas-backend-production.up.railway.app/)
- **Demo en Vivo (GitHub Pages):** [Patitas Felices Web](https://jokerkorio.github.io/patitas-api/#)


## Proyecto 4: Restaurante 
# 🌮 Sistema de Gestión "Los Consentidos"

Aplicación web diseñada para la gestión integral de un restaurante. Permite la administración de órdenes, control de inventario, gestión de personal, mapa de mesas y recepción de reseñas mediante códigos QR. 

## 🚀 Tecnologías Utilizadas
* **Frontend:** HTML5, CSS3, JavaScript 
* **Backend / BaaS:** Supabase (PostgreSQL)
* **Hosting:** GitHub Pages
* **APIs Externas:** QR Server API

---

## 💻 Funcionalidades y capturas de pantalla

El sistema está dividido en secciones interactivas que se actualizan de forma asíncrona mediante llamadas a la API REST de Supabase:

* **🛒 Órdenes (Punto de Venta):** Permite abrir nuevas órdenes asignando a un empleado responsable. Cuenta con un carrito de compras interactivo que calcula subtotales y el total de la orden en tiempo real.
  <details>
  <summary>🖼️ Ver captura de Órdenes</summary>
  <br>
  <img loading="lazy" src="https://media.discordapp.net/attachments/1474619815225196635/1509423354266779658/image.png?ex=6a191f8b&is=6a17ce0b&hm=33e1addec4938fbb265aec06c4a3f7787df94a08a9686d7c664451baf2a9ee03&=&format=webp&quality=lossless&width=1589&height=800" alt="Módulo de Órdenes" width="800"/>
  </details>

* **🍽️ Menú:** Visualización del catálogo de alimentos filtrable por categorías. Permite registrar nuevos platillos indicando nombre, precio y categoría.
  <details>
  <summary>🖼️ Ver captura del Menú</summary>
  <br>
  <img loading="lazy" src="https://media.discordapp.net/attachments/1474619815225196635/1509423544562483310/image.png?ex=6a191fb8&is=6a17ce38&hm=436c9f43ca7d0159277702c2c680e614c2c00bcfadaddebc4d95e4087b0fed0d&=&format=webp&quality=lossless&width=1660&height=800" alt="Catálogo del Menú" width="800"/>
  </details>

* **🧺 Inventario:** Control estricto de insumos. Calcula las existencias reales sumando las entradas y muestra alertas de color (Agotado, Bajo, OK) basadas en un stock mínimo definido.
  <details>
  <summary>🖼️ Ver captura de Inventario</summary>
  <br>
  <img loading="lazy" src="https://media.discordapp.net/attachments/1474619815225196635/1509423719779401808/image.png?ex=6a191fe2&is=6a17ce62&hm=3a9a76046e974b6e5c57b51fa6d128bbc0103e54679b561d0a8679244c220c4e&=&format=webp&quality=lossless&width=1681&height=800" alt="Control de Inventario" width="800"/>
  </details>

* **👨‍💼 Personal:** Gestión de la plantilla de empleados. Permite registrar altas de meseros con información de contacto, asignación de rol y turno (Mañana, Tarde, Noche).
  <details>
  <summary>🖼️ Ver captura de Personal</summary>
  <br>
  <img loading="lazy" src="https://media.discordapp.net/attachments/1474619815225196635/1509423845696868402/image.png?ex=6a192000&is=6a17ce80&hm=e8ab1bf4a85c2df42db5d56901d8d05f34f9d150072d4eebafbdd8102caab83c&=&format=webp&quality=lossless&width=1684&height=800" alt="Gestión de Personal" width="800"/>
  </details>

* **🏷️ Mesas:** Plano virtual con 12 mesas. Muestra visualmente el estado (Libre / Ocupada) y un cronómetro en tiempo real con los minutos transcurridos desde que la mesa fue ocupada.
  <details>
  <summary>🖼️ Ver captura de Mesas</summary>
  <br>
  <img loading="lazy" src="https://media.discordapp.net/attachments/1474619815225196635/1509423973627072552/image.png?ex=6a19201f&is=6a17ce9f&hm=a949744c6e7f5a0e13c710a66aa8f2f21e57b6f40be3fe0fdc68a0e52b40bc03&=&format=webp&quality=lossless&width=1686&height=800" alt="Mapa de Mesas" width="800"/>
  </details>

* **💳 Caja:** Módulo de liquidación de cuentas pendientes. Permite dividir la cuenta entre varios comensales, seleccionar el método de pago (Efectivo, Tarjeta, Transferencia) y generar un ticket de compra con formato de impresión.
  <details>
  <summary>🖼️ Ver captura de Caja</summary>
  <br>
  <img loading="lazy" src="https://media.discordapp.net/attachments/1474619815225196635/1509424073187528855/image.png?ex=6a192036&is=6a17ceb6&hm=119e966a3234355dc6141f3c43056d5d7d0e65614180200af21d2d4af6924e40&=&format=webp&quality=lossless&width=1860&height=629" alt="Módulo de Caja y Cobro" width="800"/>
  </details>

* **⭐ Reseñas y Código QR:** Generador dinámico de códigos QR únicos por mesa (consumiendo la API de `qrserver`). Los clientes pueden escanearlo para acceder a una vista pública y dejar una calificación de 1 a 5 estrellas junto con comentarios.
  <details>
  <summary>🖼️ Ver captura de Reseñas</summary>
  <br>
  <img loading="lazy" src="https://media.discordapp.net/attachments/1474619815225196635/1509424191273697380/image.png?ex=6a192052&is=6a17ced2&hm=30177e2b70c68348ee0125c5094df35dd33b45387c4573dc27c0081ad8701a32&=&format=webp&quality=lossless&width=1699&height=800" alt="Generador QR y Reseñas" width="800"/>
  </details>

* **🔔 Notificaciones Inteligentes:** Un servicio en segundo plano revisa automáticamente (cada 60 segundos) el sistema para alertar sobre ingredientes con stock bajo y órdenes que no han sido cobradas.
  <details>
  <summary>🖼️ Ver captura de Notificaciones</summary>
  <br>
  <img loading="lazy" src="https://media.discordapp.net/attachments/1474619815225196635/1509424316297777242/image.png?ex=6a192070&is=6a17cef0&hm=ac33fe06fd7a3c3c25245662424b37230bf2bb975717ef7f1841426492326995&=&format=webp&quality=lossless&width=499&height=930" alt="Panel de Notificaciones" width="400"/>
  </details>


### 🔗 Enlaces
Código Fuente: [Repositorio](https://github.com/aeiou520814-del/abc)
Demo en Vivo: [Página Web](https://aeiou520814-del.github.io/abc/)

# Proyecto 7: MANTRA — Red social de eventos

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
* Persistencia de datos mediante PostgreSQL.
* API REST para comunicación entre frontend y backend.


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


