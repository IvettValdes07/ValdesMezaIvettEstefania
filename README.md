🌐 --API Mashup Dashboard — 6 Categorías

Dashboard unificado tipo Mashup que integra seis categorías de APIs en una sola pantalla interactiva.

📋 -Descripción del Proyecto

Este proyecto implementa un Dashboard tipo Mashup que consume de manera individual seis categorías de APIs, todas visualizadas en una sola pantalla unificada.

El objetivo es demostrar la integración de múltiples servicios web en una sola interfaz.

🗂️ Estructura del Proyecto
api-mashup-dashboard/
├── dashboard_mashup.html     ← 🌟 Dashboard principal (TODO en uno)
├── api1_geolocalizacion.html ← 📍 API individual: Geolocalización
├── api2_redes_sociales.html  ← 📱 API individual: Redes Sociales
├── api3_ecommerce.html       ← 🛒 API individual: E-Commerce
├── api4_base_datos.html      ← 🗄️ API individual: Base de Datos
├── api5_comunicaciones.html  ← 📨 API individual: SMS/Comunicaciones
├── api6_streaming.html       ← 🎬 API individual: Streaming
└── README.md                 ← 📖 Documentación
🚀 --Categorías Implementadas
📍- API 1 — Geolocalización
Servicio: OpenStreetMap + Leaflet.js
Funcionalidad:
Mapa interactivo
Geolocalización del usuario
Búsqueda por coordenadas
Tecnologías: navigator.geolocation, Leaflet.js
Archivo: api1_geolocalizacion.html
📱 API 2 — Redes Sociales
Servicio: GitHub REST API v3
Funcionalidad:
Búsqueda de perfiles
Visualización de repositorios
Estadísticas de seguidores

Endpoint:

https://api.github.com/users/{username}
Archivo: api2_redes_sociales.html
🛒 API 3 — E-Commerce
Servicio: FakeStore API
Funcionalidad:
Catálogo de productos
Filtros de búsqueda
Simulación de carrito

Endpoint:

https://fakestoreapi.com/products
Archivo: api3_ecommerce.html
🗄️ API 4 — Bases de Datos
Servicio: JSONBin.io + localStorage
Funcionalidad:
Registro de usuarios
Almacenamiento en la nube
Historial de datos

Endpoint:

https://api.jsonbin.io/v3/b
Archivo: api4_base_datos.html
📨 API 5 — Comunicación
Servicio: Twilio API (simulado)
Funcionalidad:
Envío de SMS (simulado)
OTP y alertas
Historial de mensajes
Protocolo: HTTP REST (POST)
Archivo: api5_comunicaciones.html
🎬 API 6 — Streaming
Servicios:
YouTube IFrame Player API
Web Audio API
Funcionalidad:
Reproductor de video
Reproductor de audio
Archivo: api6_streaming.html
🛠️ Tecnologías Utilizadas
Tecnología	Uso
HTML5 / CSS3 / JS	Base del proyecto
Leaflet.js	Mapa interactivo
OpenStreetMap	Tiles del mapa
GitHub REST API	Datos de usuarios
FakeStore API	Productos
JSONBin.io	Base de datos
localStorage	Respaldo local
Twilio API (simulado)	SMS
YouTube IFrame API	Video
Web Audio API	Audio
▶️ Cómo Ejecutar
🔹 Opción 1 — Abrir directo
Descarga o clona el repositorio
Abre:
dashboard_mashup.html
🔹 Opción 2 — Servidor local (recomendado)
Con Python:
python -m http.server 8080
Con Node.js:
npx serve .

Luego abre:

http://localhost:8080/dashboard_mashup.html
📸 Vista del Dashboard
┌─────────────────┬─────────────────┬─────────────────┐
│ 📍 Geoloc.      │ 📱 Redes Soc.   │ 🛒 E-Commerce   │
├─────────────────┼─────────────────┼─────────────────┤
│ 🗄️ Base Datos   │ 📨 SMS/Comm.    │ 🎬 Streaming    │
└─────────────────┴─────────────────┴─────────────────┘
🔗 --APIs y Servicios
API	Tipo	Auth
OpenStreetMap	Pública	❌
GitHub API	Pública	❌
FakeStore API	Pública	❌
JSONBin.io	Pública	❌
Twilio (demo)	Simulada	N/A
YouTube IFrame	Pública	❌
👨‍💻 Desarrollo

Proyecto académico para la materia de Desarrollo Web / Programación.

✔️ Requerimientos cubiertos:
Geolocalización
Redes sociales
E-commerce
Base de datos
Comunicación
Streaming
Dashboard unificado
📄 Licencia

Proyecto académico — uso educativo.
