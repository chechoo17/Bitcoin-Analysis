# Bitcoin v0.1 💸  
[![Version](https://img.shields.io/badge/version-v0.1-blue)](https://github.com/bitcoin/bitcoin/releases/tag/v0.1)  
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)  
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](#)  
[![Last Commit](https://img.shields.io/github/last-commit/bitcoin/bitcoin)](https://github.com/bitcoin/bitcoin)

---

## 🧠 Descripción

**Bitcoin v0.1** es la primera implementación pública de un sistema de dinero electrónico entre pares (peer-to-peer electronic cash system), desarrollado por *Satoshi Nakamoto* en 2009. Esta versión representa el inicio de la revolución de las criptomonedas, implementando una red descentralizada basada en pruebas de trabajo (Proof-of-Work) y un libro de contabilidad inmutable: la **blockchain**.

> "Una forma puramente peer-to-peer de dinero electrónico permitiría enviar pagos en línea directamente de una parte a otra sin pasar por una institución financiera." — *Satoshi Nakamoto, 2008*

---

## 📽 Demo

> Aunque Bitcoin v0.1 no tiene GUI moderna, puedes mostrar su funcionamiento con una animación terminal o capturas del software corriendo en Windows XP.

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/37/Bitcoin_Logo.svg/1200px-Bitcoin_Logo.svg.png" width="200" alt="Bitcoin Logo](https://logos-marcas.com/bitcoin-logo/"/>
</p>

Para un demo más visual puedes usar [asciinema](https://asciinema.org/) o grabar un GIF mostrando cómo se mina un bloque con CPU.

---

## ✨ Características clave

- 🔒 **Prueba de trabajo (SHA-256)** para consenso descentralizado  
- ⛓️ **Blockchain** para registro inmutable de transacciones  
- 💰 **Recompensas por bloque** iniciales de 50 BTC  
- 📡 **Red P2P** sin dependencia de servidores centrales  
- 🧾 **Transacciones firmadas** criptográficamente  
- 🖥️ **Minería por CPU** (ideal para hardware doméstico)  
- 📉 **Emisión limitada** a 21 millones de BTC  

---

## ⚙️ Instalación

> Requiere entorno Windows XP o compilador C++ para portar a otros sistemas.

```bash
# Clonar el repositorio original (histórico)
git clone https://github.com/bitcoin/bitcoin.git

# Cambiar a la primera versión
cd bitcoin
git checkout v0.1

# Compilar (en sistema compatible con C++ de 2009)
make  # o usar Visual Studio 2008 para Windows
