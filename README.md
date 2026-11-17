# ⚡ SUPERSALCHICHA MUSIC AGENCY ⚡
### Underground Cyber-Trap & Techno Alliance — Web Showcase
> **Proyecto Académico 4º ESO**  
> **Creadores y Directores:** Álvaro Pinar Cazorla, Dani Barceló González, Alejandro Canet Murillo  
> **Aesthetic:** Underground Cyber-Trap / Dark-Mode Glassmorphism (Syne + Space Grotesk + Tailwind CSS)

---

## 🚀 Cómo abrir y visualizar la web

### Opción 1: Con servidor local (Recomendado)
Abre una terminal en esta carpeta y ejecuta:
```bash
python -m http.server 8080
```
Luego abre tu navegador en:
👉 **[http://localhost:8080](http://localhost:8080)**

### Opción 2: Directamente en el navegador
Puedes hacer doble clic en `index.html` para abrirlo directamente en Google Chrome, Edge o tu navegador preferido.

---

## 📁 Estructura del Sitio Unificado

| Archivo | Sección | Descripción |
|---|---|---|
| [`index.html`](index.html) | **Home** | Portada con Hero cyber, live ticker marquesina 148 BPM, directores, estadísticas y roster secreto. |
| [`artists.html`](artists.html) | **Artists Roster** | Fichas de Eladio Carrión, Dei V, DJ Konik, Unicorn on Ketamine con botones de contratación directa. |
| [`tours.html`](tours.html) | **Tours & Festivals** | Propuestas de festivales (Sónar, Arenal Sound, Medusa Sunbeach) con filtros interactivos de categoría. |
| [`map.html`](map.html) | **Interactive Radar Map** | Mapa interactivo de festivales con HUD dinámico en tiempo real según el evento seleccionado. |
| [`reviews.html`](reviews.html) | **Voices from the Underground** | Reseñas y testimonios de promotores y artistas con pestañas de filtrado dinámico. |
| [`about.html`](about.html) | **About Us & Manifesto** | Historia del proyecto de 4º ESO, filosofía, metodología, equipo cofundador y pilares. |
| [`contact.html`](contact.html) | **Contact & Press Hub** | Terminal de contacto y prensa, canales directos de los 3 directores, sedes y formulario. |
| [`DESIGN.md`](DESIGN.md) | **Design System Tokens** | Guía de estilos, paleta de colores obsidian & neon pink (`#FF1493`), tipografías y spacing. |

---

## ⚡ Nuevas Funcionalidades y Mejoras Añadidas

1. **Navegación Totalmente Conectada:**  
   Menú superior unificado en todas las pantallas con indicador visual activo (`aria-current="page"`).
2. **Menú Responsive Móvil:**  
   Botón hamburguesa y cajón desplegable táctil para pantallas de tablet y smartphone.
3. **Modal Global de Contratación (Booking Protocol):**  
   Al pulsar *BOOK AN ARTIST* desde cualquier página o artista, se despliega un formulario cyber con selección de artista, fechas y confirmación con feedback visual interactivo.
4. **Sintetizador de Audio Cyber 148 BPM (Web Audio API):**  
   Al pulsar el indicador de ondas `148 BPM` en la cabecera, se activa en tiempo real una base electrónica sintetizada en el navegador.
5. **Ticker Marquee Animado:**  
   Animación fluida CSS de la marquesina de noticias y sesiones secretas en la parte superior.
6. **Filtros Interactivos:**  
   Filtros funcionales de festivales en *Tours* y de categorías en *Reviews*.
7. **Corrección de Codificación UTF-8:**  
   Nombres, tildes y caracteres especiales perfectamente preservados y legibles.
