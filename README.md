# 🎬 T-Flix Fast — Aplicaciones Oficiales (Clientes)

<div align="center">

[![Latest Release](https://img.shields.io/github/v/release/T-Flix-Fast/apps?style=for-the-badge&color=E50914&label=Versi%C3%B3n)](https://github.com/T-Flix-Fast/apps/releases/latest)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/Plataformas-macOS%20%7C%20Windows%20%7C%20Android%20TV-informational?style=for-the-badge)](https://github.com/T-Flix-Fast/apps/releases/latest)

**Descarga las aplicaciones oficiales de T-Flix Fast con aceleración gráfica por hardware y Escudo Nativo Anti-Publicidad.**

[Descargas Directas](#-descargas-directas-última-versión-estable) • [Características](#-por-qué-usar-las-apps-nativas-en-lugar-del-navegador) • [Guía de Instalación](#-guía-de-instalación-rápida) • [Conexión al Servidor](#-cómo-conectar-la-app-a-tu-servidor)

</div>

---

## 📥 Descargas Directas (Última Versión Estable)

| Plataforma | Arquitectura / Sistema | Tipo de Archivo | Enlace de Descarga |
| :--- | :--- | :--- | :--- |
| 🍎 **macOS** | Apple Silicon (M1, M2, M3, M4) & Intel | Instalador `.dmg` | [**Descargar .dmg**](https://github.com/T-Flix-Fast/apps/releases/latest/download/tflix-mac.dmg) |
| 🪟 **Windows** | Windows 10 / 11 (64-bit) | Instalador `.exe` | [**Descargar Setup .exe**](https://github.com/T-Flix-Fast/apps/releases/latest/download/tflix-win.exe) |
| 🪟 **Windows** | Versión Sin Instalación | Portable `.exe` | [**Descargar Portable .exe**](https://github.com/T-Flix-Fast/apps/releases/latest/download/tflix-win-portable.exe) |
| 📺 **Android TV** | Smart TV, Google TV, TV Box, Fire TV Stick | Paquete `.apk` | [**Descargar .apk**](https://github.com/T-Flix-Fast/apps/releases/latest/download/tflix.apk) |

> 💡 **Tip para Android TV / Fire TV:** Si estás usando la app **Downloader**, puedes ingresar la URL directa `https://github.com/T-Flix-Fast/apps/releases/latest/download/tflix.apk` para instalarla directamente con el control remoto.

---

## 🌟 ¿Por qué usar las Apps Nativas en lugar del Navegador?

* 🛡️ **Escudo Anti-Publicidad Nativo:** Las aplicaciones de escritorio integran un motor de red que bloquea en nanosegundos cualquier intento de abrir pestañas emergentes, pop-ups o anuncios intrusivos de servidores externos de video.
* ⚡ **Aceleración por GPU a 120 FPS:** Decodificación fluida vía Metal (macOS) y DirectX (Windows), reduciendo el consumo de batería y temperatura de tu equipo.
* 📺 **Experiencia 100% Sala para TV (D-Pad):** Diseñada desde cero para el control remoto, con navegación intuitiva por cruceta, foco visible en pantalla y reproducción directa ultra-rápida vía ExoPlayer.
* 🌐 **Soporte Multi-Servidor (Estilo Jellyfin):** Puedes guardar múltiples servidores (casa, oficina, amigos) y cambiar entre ellos con un solo clic.

---

## 🚀 Guía de Instalación Rápida

### 🍎 En macOS
1. Descarga el archivo [`tflix-mac.dmg`](https://github.com/T-Flix-Fast/apps/releases/latest/download/tflix-mac.dmg).
2. Abre el `.dmg` y arrastra el icono de **T-Flix Fast** a tu carpeta de **Aplicaciones**.
3. **Primera apertura:** Al tratarse de software de desarrollador independiente, si macOS muestra el aviso de seguridad de *Gatekeeper*, haz **clic derecho** sobre la app en tu carpeta de Aplicaciones y selecciona **Abrir** (solo se hace la primera vez).

### 🪟 En Windows
1. Descarga [`tflix-win.exe`](https://github.com/T-Flix-Fast/apps/releases/latest/download/tflix-win.exe).
2. Ejecuta el instalador. Si Windows SmartScreen muestra la pantalla azul informativa, haz clic en **Más información** y luego en **Ejecutar de todas formas**.
3. Se creará un acceso directo en tu Escritorio y Menú Inicio.

### 📺 En Android TV / Google TV / Fire TV
1. En tu televisor, instala la app gratuita **Downloader** desde la Play Store o Amazon AppStore.
2. Abre Downloader y escribe la URL directa:
   ```text
   https://github.com/T-Flix-Fast/apps/releases/latest/download/tflix.apk
   ```
3. Acepta la descarga e instala la aplicación.

---

## 🔌 Cómo Conectar la App a tu Servidor

1. Abre **T-Flix Fast** en tu dispositivo.
2. En la pantalla inicial o en el selector de servidores, escribe la dirección de tu servidor:
   * **Servidor en la misma red de casa:** `http://192.168.1.xxx:3000` (o el puerto configurado).
   * **Servidor con dominio propio:** `https://stream.tudominio.com`.
3. Inicia sesión con tu usuario y contraseña, elige tu perfil y ¡a disfrutar!

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **GNU General Public License v3.0 (GPLv3)**. Consulta el archivo [LICENSE](LICENSE) para más detalles.
