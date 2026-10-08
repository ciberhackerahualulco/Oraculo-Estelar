# 🔮 Oráculo Estelar

**PWA de Tarot y Carta Natal** — instalable, offline, sin dependencias.

![PWA](https://img.shields.io/badge/PWA-installable-7c3aed)
![Offline](https://img.shields.io/badge/offline-ready-e8c56a)
![Vanilla JS](https://img.shields.io/badge/vanilla-JS-f7df1e)
![License](https://img.shields.io/badge/license-MIT-blue)

## ✨ Demo

👉 **https://TU-USUARIO.github.io/oraculo-estelar/**

## 🌟 Características

### 🔮 Tarot
- 22 arcanos mayores con significado **al derecho e invertido**
- Tirada de **1 carta** o **3 cartas** (Pasado / Presente / Futuro)
- Animación de volteo CSS 3D
- Invertida aleatoria (~35%)
- Interpretación automática debajo de las cartas

### 🌌 Carta Natal
- **Sol, Luna y Ascendente** destacados
- **10 planetas** con signo y grado
- Cálculo astronómico real:
  - Día juliano
  - GMST (Greenwich Mean Sidereal Time)
  - Ascensión recta y oblicuidad de la eclíptica
  - Conversión heliocéntrica → geocéntrica
- 19 ciudades precargadas + entrada manual (lat, lon, UTC)

### 📲 PWA
- Instalable desde el navegador (botón flotante automático)
- Funciona **offline** vía service worker
- Listo para **GitHub Pages**
- Un solo archivo HTML, sin build, sin frameworks

## 📸 Capturas

> Agrega aquí tus screenshots en `/screenshots/`

## 🚀 Instalación local

```bash
git clone https://github.com/TU-USUARIO/oraculo-estelar.git
cd oraculo-estelar

# Cualquier servidor estático
python3 -m http.server 8000
# o
npx serve .