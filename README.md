# 🍏 macOS Cloud Simulator — Web OS Experience

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-000000?style=flat&logo=vercel)](https://vercel.app)

Un simulador web avanzado e interactivo de **macOS** enfocado en la ejecución de aplicaciones totalmente funcionales directamente desde el navegador, sin necesidad de instalaciones ni dependencia de recursos de hardware pesados.

---

## 🌟 Características Principales

* 🍎 **Ecosistema macOS Fiel:** Menú superior dinámico (*Top Bar*), *Control Center*, reloj en tiempo real y *Dock* flotante con efecto de aumento (*Magnification*).
* 📹 **OBS Studio Web:** Captura de pantalla real en tiempo real mediante `getDisplayMedia`, filtros de lienzo (*Canvas Filters*) y exportación/grabación de video `.webm`/`.mp4` con la API `MediaRecorder`.
* 💻 **VMware Virtual Machine (WASM):** Entorno de emulación x86 ligero impulsado por WebAssembly (`v86`) para bootear distribuciones reales de Linux o sistemas operativos clásicos directamente en la RAM.
* 🌐 **Safari Web Browser:** Navegador funcional optimizado para la lectura y navegación web.
* 🖥️ **Gestor de Ventanas (WindowManager):** Control completo de profundidad ($Z$-Index), arrastre fluido, redimensionamiento, maximizado y minimizado al Dock.
* 💾 **Sistema de Archivos Persistente:** Guardado automático de datos mediante `IndexedDB` y `LocalStorage`.

---

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript (ES6+), Tailwind CSS.
* **Iconos & Estilos:** FontAwesome 6, Google SF Pro Fonts.
* **Emulación & APIS:** WebAssembly (`v86`), WebRTC / Screen Capture API, `MediaRecorder` API.
* **Alojamiento:** Desplegado en **Vercel** para rendimiento de alta velocidad y compatibilidad de rutas dinámicas.

---

## 📂 Estructura del Proyecto

```text
macos-cloud-sim/
├── index.html        # Núcleo del simulador y controlador de ventanas
├── vercel.json       # Configuración de reescrituras para Vercel
├── favicon.svg       # Icono del proyecto
├── README.md         # Documentación oficial
└── LICENSE           # Licencia MIT

```

---

## 📄 Licencia

Este proyecto está bajo la Licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.
