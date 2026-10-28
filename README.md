# 🍏 macOS Cloud Simulator — Web OS Enterprise v4.0

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-000000?style=flat&logo=vercel)](https://vercel.app)

![Banner Principal del Proyecto](banner.svg)

Simulador web avanzado de **macOS** con gestión de servidores en la nube en **servers.com**, control de versiones con **CloudHub (Git)**, soporte multilenguaje global y simulación de vida en 3D.

---

## 🌟 Novedades v4.0 Enterprise

* 🌐 **servers.com (Hosting Simulator):** Alquila servidores web, hosts de Minecraft y bases de datos con generación de ingresos pasivos.
* ☁️ **CloudHub (Git Platform):** Plataforma de repositorios colaborativos con gestión propia de commits y control de versiones.
* 🌍 **Selector Multilingüe Global:** Cambia el idioma del sistema a español, inglés, francés, alemán, japonés, chino, ruso y árabe al instante.
* 🏠 **Mundo 3D & Sistema de Mamá:** Explora tu casa en primera persona, evita que te descubran usando la laptop de trabajo de tu mamá y escapa de asaltos callejeros.

---

## 📂 Estructura del Proyecto

```text
macos-cloud-sim/
├── index.html        # Núcleo y emulador completo
├── banner.svg        # Banner oficial
├── vercel.json       # Configuración para Vercel
├── favicon.svg       # Icono SVG de macOS
├── README.md         # Documentación oficial
└── LICENSE           # Licencia MIT

```

---

## 📄 Licencia

Bajo Licencia **MIT**.


## 🧩 Módulos añadidos y límites actuales

La barra flotante de la esquina inferior derecha abre cuatro módulos nuevos sin reemplazar las aplicaciones anteriores:

- **servers.com (simulador):** compra servidores ficticios para web, Minecraft, SQL y hosting avanzado. El saldo y los servidores se guardan en el navegador; los ingresos del juego son simulados.
- **Sim Browser:** navegador interno separado de Safari. Solo acepta direcciones ficticias `cloud://home`, `cloud://servers`, `cloud://cloudhub` y `cloud://status`; no navega por Internet real.
- **CloudHub:** historial local de commits de demostración, guardado en `localStorage`, con exportación JSON. No implementa Git real, sincronización remota ni colaboración todavía.
- **Idioma:** selector para español, inglés, francés, alemán, portugués, japonés, chino simplificado, ruso, árabe, italiano, coreano e hindi. Por ahora el selector traduce parcialmente los módulos nuevos; no traduce automáticamente cada app antigua.

Estos módulos son una simulación front-end: no realizan compras reales, no alojan sitios ni servidores de Minecraft reales y no suben repositorios a un proveedor cloud. Los datos permanecen en el navegador donde se usan.

