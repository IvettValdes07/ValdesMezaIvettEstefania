# 🌐 API Mashup Dashboard — 6 Categorías de APIs

> Dashboard unificado tipo Mashup que integra seis categorías de APIs en una sola pantalla interactiva.

---

## 📋 Descripción del Proyecto

Este proyecto implementa un **Dashboard tipo Mashup** que consume de manera individual seis categorías de APIs, todas visualizadas en una sola pantalla unificada.

---

## 🗂️ Estructura del Proyecto

```
api-mashup-dashboard/
├── dashboard_mashup.html        ← 🌟 Dashboard principal (TODO en uno)
├── api1_geolocalizacion.html    ← 📍 API individual: Geolocalización
├── api2_redes_sociales.html     ← 📱 API individual: Redes Sociales
├── api3_ecommerce.html          ← 🛒 API individual: E-Commerce
├── api4_base_datos.html         ← 🗄️ API individual: Base de Datos
├── api5_comunicaciones.html     ← 📨 API individual: SMS/Comunicaciones
├── api6_streaming.html          ← 🎬 API individual: Streaming
└── README.md                    ← 📖 Este archivo
```

---

## 🚀 Categorías Implementadas

### 📍 API 1 — Geolocalización
- **Servicio:** OpenStreetMap + Leaflet.js
- **Funcionalidad:** Mapa interactivo con marcadores, geolocalización del usuario, búsqueda por coordenadas
- **Tecnologías:** `navigator.geolocation`, Leaflet.js, OpenStreetMap Tiles
- **Archivo:** `api1_geolocalizacion.html`

### 📱 API 2 — Redes Sociales
- **Servicio:** GitHub REST API v3
- **Funcionalidad:** Búsqueda de perfiles, visualización de repositorios, stats de seguidores
- **Endpoint:** `https://api.github.com/users/{username}`
- **Archivo:** `api2_redes_sociales.html`

### 🛒 API 3 — E-Commerce
- **Servicio:** FakeStore API
- **Funcionalidad:** Catálogo de productos con imagen, precio y categoría; carrito de compras; filtros de búsqueda
- **Endpoint:** `https://fakestoreapi.com/products`
- **Archivo:** `api3_ecommerce.html`

### 🗄️ API 4 — Bases de Datos
- **Servicio:** JSONBin.io (nube) + localStorage (respaldo local)
- **Funcionalidad:** Registro de usuarios con nombre, email y rol; almacenamiento en la nube; historial de registros
- **Endpoint:** `https://api.jsonbin.io/v3/b`
- **Archivo:** `api4_base_datos.html`

### 📨 API 5 — Protocolos de Comunicación
- **Servicio:** Twilio REST API (simulado/demo)
- **Funcionalidad:** Simulación de envío de SMS, mensajes OTP, alertas, marketing; historial de conversación
- **Protocolo:** HTTP REST (POST) — Twilio Messages API
- **Archivo:** `api5_comunicaciones.html`

### 🎬 API 6 — Plataforma Online / Streaming
- **Servicio:** YouTube IFrame Player API + Web Audio API
- **Funcionalidad:** Reproductor de video embebido con control de YouTube, reproductor de audio con tracks externos
- **APIs:** YouTube IFrame API, HTML5 Audio/Web Audio API
- **Archivo:** `api6_streaming.html`

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
|-----------|-----|
| HTML5 / CSS3 / JavaScript | Base del proyecto (vanilla, sin frameworks) |
| Leaflet.js 1.9.4 | Mapa interactivo (Panel Geo) |
| OpenStreetMap | Tiles del mapa |
| GitHub REST API v3 | Datos de perfiles (Panel Social) |
| FakeStore API | Catálogo de productos (Panel E-Com) |
| JSONBin.io API | Base de datos en la nube (Panel BD) |
| localStorage | Almacenamiento local de respaldo |
| Twilio API (simulado) | Protocolo SMS (Panel Comunicaciones) |
| YouTube IFrame API | Reproductor de video (Panel Streaming) |
| Web Audio API / HTML5 Audio | Reproductor de audio |

---

## ▶️ Cómo Ejecutar

### Opción 1 — Abrir directamente en navegador
1. Clona o descarga este repositorio
2. Abre `dashboard_mashup.html` en tu navegador moderno (Chrome, Firefox, Edge)
3. No requiere servidor ni instalación

### Opción 2 — Con servidor local (recomendado)
```bash
# Con Python
python -m http.server 8080

# Con Node.js (npx)
npx serve .

# Luego abre: http://localhost:8080/dashboard_mashup.html
```

---

## 📸 Vistas del Dashboard

El dashboard muestra una cuadrícula de 3×2 con los 6 paneles activos simultáneamente:

```
┌─────────────────┬─────────────────┬─────────────────┐
│ 📍 Geoloc.      │ 📱 Redes Soc.   │ 🛒 E-Commerce   │
│ Leaflet Map     │ GitHub API      │ FakeStore API   │
├─────────────────┼─────────────────┼─────────────────┤
│ 🗄️ Base Datos   │ 📨 SMS/Comm.    │ 🎬 Streaming    │
│ JSONBin.io      │ Twilio (sim)    │ YouTube + Audio │
└─────────────────┴─────────────────┴─────────────────┘
```

---

## 🔗 APIs y Servicios Externos

| API | Tipo | Autenticación |
|-----|------|---------------|
| OpenStreetMap / Leaflet | Pública | No requerida |
| GitHub REST API | Pública | No requerida (rate limit: 60 req/h) |
| FakeStore API | Pública | No requerida |
| JSONBin.io | Pública / Free | No requerida (bin público) |
| Twilio (simulado) | Simulación | N/A (demo) |
| YouTube IFrame | Pública | No requerida para embed |
| SoundHelix (Audio) | Pública | No requerida |

---

## 👨‍💻 Desarrollo

Proyecto desarrollado como práctica de integración de APIs para la materia de **Desarrollo Web / Programación**.

### Requerimientos cubiertos:
- [x] Geolocalización — Mapa interactivo con coordenadas
- [x] Redes Sociales — Extracción y visualización de perfiles
- [x] E-Commerce — Catálogo con imagen y precio
- [x] Bases de Datos — Registro de información en la nube
- [x] Protocolos de Comunicación — Simulación de SMS/notificaciones
- [x] Streaming — Reproductor de audio/video embebido con controles
- [x] Dashboard unificado (Mashup) — Todas las APIs en una pantalla
- [x] Archivos individuales por categoría

---

## 📄 Licencia

Proyecto académico — Uso educativo.