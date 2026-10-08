# 🔮 Oráculo Estelar

**PWA de Tarot y Carta Natal** — instalable, offline, sin dependencias.

![PWA](https://img.shields.io/badge/PWA-installable-7c3aed)
![Offline](https://img.shields.io/badge/offline-ready-e8c56a)
![Vanilla JS](https://img.shields.io/badge/vanilla-JS-f7df1e)
![License](https://img.shields.io/badge/license-MIT-blue)

> Creado y diseñado por **Abraham Fernando Ulloa O.**

## ✨ Demo

👉 **https://ciberhackerahualulco.github.io/Nombre-De-Tu-Repositorio/**

## 🌟 Características

### 🔮 Tarot
- 22 arcanos mayores con significado al derecho e invertido
- Tirada de **1 carta** o **3 cartas** (Pasado / Presente / Futuro)
- Animación de volteo 3D + vibración al voltear (Android)
- **Historial de tiradas** guardado en `localStorage`
- Botón para **compartir** la lectura por WhatsApp u otras apps

### 🌌 Carta Natal
- **Rueda zodiacal SVG** con los 12 signos y los planetas ubicados por grado
- **Aspectos planetarios** dibujados dentro de la rueda (☌ ⚹ □ △ ☍)
- **Sol, Luna y Ascendente** destacados
- **10 planetas + Nodo Norte + Medio Cielo (MC) + Ascendente**
- **Zonas horarias reales** con `Intl.DateTimeFormat` (soporta DST)
- 21 ciudades precargadas + entrada manual
- Botón para **compartir** la carta completa

### 🎨 Interfaz
- **Modo claro / oscuro** (respeta preferencia del sistema y se guarda)
- Diseño responsive, táctil y minimalista

### 📲 PWA
- Instalable en Android, iOS y escritorio
- Funciona **offline** con Service Worker
- Service Worker con estrategia **stale-while-revalidate**
- Listo para **GitHub Pages**

## 📸 Capturas

> Agrega aquí tus screenshots en `/screenshots/`

## 🚀 Uso local

```bash
git clone https://github.com/ciberhackerahualulco/Nombre-De-Tu-Repositorio.git
cd Nombre-De-Tu-Repositorio
python3 -m http.server 8000