# 🌉 EL PUENTE Companion

> *"Cruzar el puente es decidir que ya no quieres vivir en piloto automático."*

**Un espacio para detenerte, mirar hacia adentro y encontrarte.**

**EL PUENTE Companion** es el acompañante digital interactivo para la experiencia y libro "EL PUENTE" de Marco Antonio Gálvez Estrada. Está diseñado para ser un refugio personal donde puedes leer, reflexionar, escuchar música y documentar tu viaje de transformación personal.

---

## ✨ Módulos y Funcionalidades

La aplicación está dividida en módulos interactivos para acompañar tu proceso de **Cruzar · Comprender · Transformar**:

*   📄 **Leer el Libro:** Visor de PDF integrado con modo pantalla completa y navegación fluida.
*   🎬 **Videos:** Reproductor de listas de reproducción de video (MP4, WebM, MOV).
*   🎵 **Musicalidad:** Reproductor de audio con estética de *cassette retro 80s*. La música continúa sonando mientras navegas por otros módulos.
*   📝 **Bitácora de viaje:** Tu libro de vida. Escribe reflexiones, cartas a tu yo del pasado/presente/futuro, registra tu estado de ánimo y guarda tus aprendizajes.
*   📊 **Infografías:** Galería de imágenes optimizada para formato vertical.
*   🎴 **Tarjetas Didácticas:** Sistema de *flashcards* (importables desde CSV) con modo aleatorio para estudiar los conceptos del libro.
*   🖼️ **Presentación:** Visor para archivos PDF, PPTX u ODP.
*   💬 **Comunicación con Marco:** Integración directa con WhatsApp para enviar mensajes, dudas o pedir acompañamiento (se guarda historial local).
*   👤 **Sobre Marco:** Semblanza, filosofía de trabajo y datos de contacto del autor.
*   ⚙️ **Configuración:** Exporta, importa o limpia tus datos locales en formato JSON.

---

## 🛠️ Características Técnicas

*   **100% Local y Offline:** No requiere servidor backend. Todo funciona directamente en tu navegador.
*   **Privacidad Total:** Tus archivos, reflexiones y mensajes nunca salen de tu dispositivo. Todo se almacena de forma segura usando **IndexedDB**.
*   **Diseño Responsivo e Inmersivo:** Interfaz cuidada con estética retro/moderna y animaciones fluidas.
*   **Un solo archivo:** Todo el motor de la aplicación está contenido en un solo archivo `Index.html` (HTML + CSS + JS), lo que facilita su distribución y uso.

---

## 🚀 Cómo usarlo

No necesitas instalar dependencias ni compilar nada. 

1. Clona este repositorio o descarga el archivo `Index.html`.
2. Abre el archivo `Index.html` en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
3. ¡Listo! Cruza el puente 🌉.

*Si deseas alojarlo en GitHub Pages, Netlify o Vercel, simplemente sube el archivo `Index.html` y la plataforma lo servirá como un sitio web estático.*

---

## ⌨️ Atajos de Teclado

Para una experiencia más fluida, puedes usar los siguientes atajos:

| Tecla | Acción |
| :--- | :--- |
| `Espacio` | Play / Pausa en el reproductor musical |
| `←` / `→` | Navegar en PDFs, presentaciones, infografías y tarjetas |
| `F` | Activar / Desactivar pantalla completa |
| `Esc` | Cerrar modales o salir de pantalla completa |

---

## 🔒 Privacidad y Gestión de Datos

Esta aplicación respeta tu privacidad por encima de todo. 
*   **Almacenamiento:** Se utiliza `IndexedDB` en tu navegador.
*   **Respaldo:** Puedes exportar todas tus reflexiones, historial de mensajes y configuración a un archivo `.json` desde el módulo de **Configuración**.
*   **Migración
