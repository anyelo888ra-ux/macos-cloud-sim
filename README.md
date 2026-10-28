# 🍏 macOS Cloud Simulator — Web OS Experience

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-000000?style=flat&logo=vercel)](https://vercel.app)

Un simulador web avanzado e interactivo de **macOS** enfocado en la ejecución de aplicaciones totalmente funcionales directamente desde el navegador, sin necesidad de instalaciones ni dependencia de recursos de hardware pesados.

---

## 🌟 Características Principales

* 🍎 **Ecosistema macOS Fiel:** Menú superior dinámico (*Top Bar*), reloj en tiempo real, menús desplegables intermedios y *Dock* flotante con efecto *Magnification*.
* 📹 **OBS Studio Web:** Captura de pantalla real mediante `getDisplayMedia` y grabación de video `.webm` con la API `MediaRecorder`.
* 💻 **VMware Virtual Machine (WASM):** Entorno de emulación x86 ligero impulsado por WebAssembly (`v86`) para bootear distribuciones reales de Linux directamente en la RAM.
* 🖥️ **Terminal ZSH Virtual:** Emulador de terminal con comandos reales (`neofetch`, `ls`, `echo`, `clear`, `date`).
* 🌐 **Safari Web Browser:** Navegador funcional optimizado para navegación web dentro del simulador.
* 📁 **Finder:** Explorador de archivos intuitivo para administrar el ecosistema virtual.

---

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript (ES6+), Tailwind CSS.
* **Emulación & APIS:** WebAssembly (`v86`), WebRTC / Screen Capture API, `MediaRecorder` API.
* **Alojamiento:** Desplegado en **Vercel** para velocidad y compatibilidad de rutas.

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
