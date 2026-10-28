# 🍏 macOS Cloud Simulator — Web OS Experience v3.5 Ultra

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-000000?style=flat&logo=vercel)](https://vercel.app)

![Banner Principal del Proyecto](banner.svg)

Un simulador web avanzado e interactivo de **macOS** ejecutado directamente desde el navegador, combinando herramientas de desarrollo reales, emulación en la nube y un modo de exploración en primera persona (*Mundo 3D*).

---

## 🌟 Características Principales

* 🍎 **Ecosistema macOS Fiel:** Menú superior dinámico, reloj en tiempo real, menús desplegables y *Dock* interactivo.
* 💻 **VS Code & Game3DMaker:** Editor de código fuente integrado para ver y modificar el `index.html` en tiempo real, junto con un creador de minijuegos 3D.
* 🎮 **PlayFree.com (Economía & Dinero):** Publica tus juegos creados y gana ingresos automáticos ($1 por cada descarga simulada) para comprar hardware en el simulador.
* 🪟 **Laptop de Mamá (Windows 10) & Patrullaje:** Si tu MacBook explota por usar el Wi-Fi gratuito de McDonald's, puedes usar la laptop de trabajo de tu mamá... ¡pero cuidado con que te descubra y te castigue!
* 🏠 **Mundo 3D en 1ª Persona (WASD):** Explora tu habitación en el piso de arriba, baja por la casa, sal a la calle y visita la tienda Apple para comprar una laptop nueva.
* 📹 **OBS Studio Web:** Captura de pantalla real mediante `getDisplayMedia` y grabación de video `.webm`.
* 💻 **VMware Virtual Machine (WASM):** Entorno de emulación x86 con `v86` para ejecutar Linux directamente en la RAM.
* 🖥️ **Terminal ZSH Virtual:** Emulador con comandos reales (`neofetch`, `ls`, `echo`, `clear`, `date`).

---

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript (ES6+), Tailwind CSS, Three.js (3D).
* **Emulación & APIS:** WebAssembly (`v86`), WebRTC / Screen Capture API, `MediaRecorder` API.
* **Alojamiento:** Desplegado en **Vercel** con compatibilidad de rutas automáticas.

---

## 📂 Estructura del Proyecto

```text
macos-cloud-sim/
├── index.html        # Núcleo del simulador, apps y entorno 3D
├── banner.svg        # Banner gráfico oficial del proyecto
├── vercel.json       # Configuración de reescrituras para Vercel
├── favicon.svg       # Icono SVG de macOS
├── README.md         # Documentación oficial
└── LICENSE           # Licencia MIT

```

---

## 📄 Licencia

Este proyecto está bajo la Licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.
