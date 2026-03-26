# 🎬 MiniPlayer - Video Keystone Player

Reproductor de vídeo en bucle amb correcció de perspectiva (keystone) en temps real per projectors i pantalles.

## ✨ Com funciona

1. **Posa els vídeos** a la carpeta `videos/` al mateix directori que `miniplayer.exe`
2. **Executa** `miniplayer.exe`
3. **Automàtic**: reproduïx tots els vídeos (.mp4, .avi, .mov, .mkv) per ordre alfabètic en bucle infinit
4. **Fullscreen** adaptat a la resolució de la teva pantalla

## 🎛️ Controls Keystone (correcció perspectiva)

C → Activa/desactiva mode edit (overlay)<br>
1, 2, 3, 4 → Selecciona cantonada (verd = activa)<br>
← → ↑ ↓ → Mou cantonada seleccionada<br>
ESC → Surt del programa<br>

*Nota*: Quan desactives edit (C), el vídeo queda *net* però amb keystone aplicat permanentment.

## 📱 Exemple d'ús
<pre>
📁 MP/
├── miniplayer.exe ← Executable
└── 📁 videos/
      ├── intro.mp4
      ├── main_content.mp4
      └── outro.mp4
</pre>

## 💻 Instal·lació

**Només Windows** — sense necessitar Python:
1. Descarrega `miniplayer.exe`
2. Crea carpeta `videos/` al mateix directori
3. Copia els teus vídeos dins `videos/`
4. Executa `miniplayer.exe`

## 🔧 Tecnologies

- **OpenCV** - processament vídeo i keystone
- **PyInstaller** - empaquetat .exe autònom (~60MB)
- **NumPy** - operacions matriu

## 🎯 Casos d'ús
- **Projectors** amb perspectiva distorsionada
- **Instal·lacions AV** loops infinits
- **Presentacions** amb vídeo mapping
- **DJ sets** amb projectors

##📄 Llicència

[![CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

L'Snake 1K està sota llicència **Creative Commons Reconeixement 4.0 Internacional (CC BY 4.0)**.

> Pots **copiar, modificar, distribuir i fins i tot vendre** derivats del codi sempre que:
> - **Citis l'autor original**
> - **Enllaços a la llicència**: https://creativecommons.org/licenses/by/4.0/


Fet amb python i ❤️ per [Burinat](https://github.com/Burinat)

⭐ Star si t'ha servit!


---
*Versió 1.0 - Març 2026*
