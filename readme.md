# 🕹️ Donkey Kong Country 3: Dixie Kong's Double Trouble! - Super Famicom (SNES) Web Emulator

Este proyecto contiene un emulador de Super Nintendo completamente funcional integrado directamente en el navegador mediante **EmulatorJS**, configurado específicamente para jugar a **Donkey Kong Country 3**.

---

## 🚀 Demostración en Vivo
Puedes jugar ingresando directamente al enlace de tu plataforma de GitHub Pages:
👉 **[Jugar Donkey Kong Country 3 Aquí](https://ferplex.github.io/dkc3)** *(Asegúrate de ajustar esta URL con el nombre exacto de tu repositorio)*

---

## 📂 Contenido del Repositorio

Para el correcto funcionamiento de la plataforma de emulación, asegúrate de mantener los archivos organizados de la siguiente forma:

*   `index.html` - El archivo de interfaz de usuario con los estilos personalizados y configuraciones del emulador.
*   `ddky3.zip` - La ROM original del juego (Super Famicom / SNES).
*   `README.md` - Esta guía de uso y documentación.

---

## 🎮 Controles de Teclado (Por Defecto)

Al iniciar la emulación web, se asignarán las siguientes teclas mapeadas de manera estándar:

| Acción SNES | Tecla en PC |
| :--- | :--- |
| **D-Pad (Movimiento / Agacharse)** | Flechas Direccionales (⬆️ ⬇️ ⬅️ ➡️) |
| **Botón A** | Tecla `X` |
| **Botón B** | Tecla `Z` |
| **Botón X** | Tecla `S` |
| **Botón Y** | Tecla `A` |
| **Gatillo L** | Tecla `Q` |
| **Gatillo R** | Tecla `W` |
| **START** | Tecla `Enter` |
| **SELECT** | Tecla `Shift` |

> ⚙️ **Configuración Avanzada:** Si prefieres cambiar el mapeo de teclas o deseas conectar un mando/gamepad USB o Bluetooth, haz clic en el botón de engranaje situado en la barra de herramientas inferior del emulador.

---

## 💻 Ejecución en Entorno Local

Si deseas probar la estabilidad del juego de forma local:

1. Clona o descarga los archivos de este repositorio en tu equipo.
2. Abre tu editor de código favorito (por ejemplo, **Visual Studio Code**).
3. Levanta un servidor local usando extensiones como **Live Server** (haciendo clic derecho sobre `index.html` -> *Open with Live Server*). 
4. _Nota:_ Evita abrir el archivo `index.html` haciendo doble clic directo, ya que las políticas CORS de los navegadores modernos bloquearán la carga dinámica del motor de EmulatorJS.

---

## ⚖️ Descargo de Responsabilidad
Este entorno se proporciona estrictamente con fines educativos, de pruebas técnicas y de preservación de software de consolas retro. Todos los derechos del juego y personajes pertenecen originalmente a **Rare** y **Nintendo**.
