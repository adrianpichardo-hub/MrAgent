🎮 EL DESPACHO DE NUEVA PALMIRA
Juego de Aventura tipo Monkey Island (HTML5 + Canvas)
![Status](https://img.shields.io/badge/Status-Completado-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Version](https://img.shields.io/badge/Version-1.0-blue)
---
📖 DESCRIPCIÓN
"El Despacho de Nueva Palmira" es un juego de aventura punto-y-click tipo Monkey Island 1, ambientado en el puerto fluvial de Nueva Palmira, Uruguay.
Tu rol es Cristhian Q, un despachador de buques que debe completar una serie de trámites burocráticos para que un carguero importante pueda entrar a puerto.
El Argumento:
Un buque carguero está fondeado en la Rada (área de espera del río). Cristhian debe:
Ir a Migraciones → Obtener documento de entrada
Ir a Prefectura → Conseguir autorización oficial
Ir a Oficina → Imprimir el despacho
Ir a Aduana → Sellar el documento final
PERO CUIDADO: Si intentas saltarte pasos, ¡la Oficial Malhumorada te dará un cachetazo épico! 💥
---
🕹️ CARACTERÍSTICAS
Locaciones (7 total)
🌊 Mapa Central - Puerto de Nueva Palmira
🚢 Puerto AÑP - Información sobre el buque
📦 Terminal Navios - Mini-juego de adivinanza
📋 Migraciones - Primera parada obligatoria
🏛️ Prefectura - Con riesgo de cachetazo
📄 Oficina - Mini-juego de selección
🛃 Aduana - Última parada hacia la victoria
NPCs (8 personajes)
Oficial Gómez - Amable, otorga documento
Oficial Malhumorada - PELIGROSA (cachetazos)
Capitán López - Pide cigarrillos
Empleada Martina - Distraída, come empanadas
Inspector Rodríguez - Paranoico, sospecha de todo
Marinero - Fumador, info sobre el buque
Supervisor - Serio, mini-juego de peso
Práctico - Voz de radio en la intro
Mecánicas de Juego
✅ Sistema de Diálogos - Opciones ramificadas estilo MI  
✅ Inventario Visual - Muestra items obtenidos  
✅ Lógica de Dependencias - No puedes saltarte pasos  
✅ 2 Mini-Juegos - Terminal (adivinanza) y Oficina (selección)  
✅ Cachetazo Épico - Penalización por orden incorrecto  
✅ Sonidos Retro Atari - Efectos generados proceduralmente  
✅ Estadísticas Finales - Cachetazos, diálogos, tiempo jugado
---
🎵 SONIDOS RETRO ATARI
Todos los sonidos son generados proceduralmente con Web Audio API:
Evento	Sonido
Intro	🔊 Radio estática
Cambiar locación	🚪 Puerta
Obtener documento	✅ Ding ascendente
Cachetazo	❌ PLAAACK brutal
Error mini-juego	⚠️ Bzzzzt
Mini-juego ganado	🎮 Fanfarria
Victoria final	🏆 Fanfarria épica
Click en opción	🖱️ Beep
💡 Toggle ON/OFF en la esquina superior derecha
---
🎮 CÓMO JUGAR
Controles
CLICK en las puertas para navegar entre locaciones
CLICK en opciones de diálogo para responder
R para reiniciar el juego
Flujo Correcto (Sin Cachetazos)
```
INTRO → MONÓLOGO → MAPA
  ↓
MIGRACIONES (obtener documento)
  ↓
PREFECTURA (obtener autorización)
  ↓
OFICINA (mini-juego imprimir despacho)
  ↓
ADUANA (obtener sello final)
  ↓
¡¡VICTORIA!!
```
Si Cometes Errores
❌ Entrar a PREFECTURA sin documento → CACHETAZO ÉPICO
❌ Entrar a OFICINA sin autorización → CACHETAZO DOBLE
❌ Seleccionar opción incorrecta en mini-juegos → Reintentar
---
🛠️ TECNOLOGÍA
HTML5 - Estructura
Canvas 2D - Gráficos
Web Audio API - Sonidos procedurales
Vanilla JavaScript - Lógica sin frameworks
CSS3 - Interfaz terminal retro
Tamaño
Un solo archivo HTML (~20 KB)
Sin dependencias externas
Sin archivos de imagen o sonido
---
🚀 INSTALACIÓN
Opción 1: GitHub Pages (Recomendado)
```
1. Haz fork de este repositorio
2. Ve a Settings → Pages
3. Selecciona "Deploy from a branch" → "main"
4. Tu juego estará en: https://TU_USUARIO.github.io/despacho-nueva-palmira/
```
Opción 2: Descarga Local
```
1. Descarga el archivo index.html
2. Abre en navegador (Chrome, Firefox, Edge, Safari)
3. ¡A jugar!
```
Opción 3: Servidor Local
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js
npx http-server

# Luego abre http://localhost:8000
```
---
📊 ESTADÍSTICAS DE JUEGO
Al completar, verás:
🤕 Cachetazos recibidos
💬 Diálogos completados
🎮 Mini-juegos ganados
⏱️ Tiempo jugado
---
🎨 ESTÉTICA
Retro Atari/Monkey Island 1 - Gráficos pixel art ASCII
Tema terminal hacker - Verde fosforescente sobre negro
Diálogos en español - Con jerga portuaria uruguaya
Sonidos procedurales - Osciladores sine/square auténticos
---
🐛 CONOCIDAS
Los sonidos requieren interacción del usuario (limitación de navegadores)
El juego funciona mejor en navegadores modernos (Chrome 60+, Firefox 55+)
La resolución se adapta automáticamente a pantallas
---
🔄 HISTORIA DEL DESARROLLO
Versión	Fecha	Cambios
1.0	2025-03-28	Versión inicial completa
---
📝 CRÉDITOS
Concepto & Desarrollo: Basado en la mecánica de Monkey Island 1 de LucasArts
Temática: Puerto fluvial de Nueva Palmira, Uruguay
Inspiración:
The Secret of Monkey Island (1990)
Operaciones portuarias reales
Humor de sitcoms argentinas/uruguayas
---
📄 LICENCIA
Este proyecto está bajo licencia MIT - Eres libre de usar, modificar y distribuir.
---
🤝 CONTRIBUCIONES
¿Quieres mejorar el juego?
Ideas para agregar:
🎵 Música de fondo
🖼️ Sprites mejorados
📱 Versión mobile
🌐 Traducción a otros idiomas
🎭 Más NPCs y locaciones
🎯 Puzzles más complejos
---
💬 CONTACTO
Si encuentras bugs o tienes sugerencias, abre un Issue en GitHub.
---
🎮 ¡A JUGAR!
```
https://TU_USUARIO.github.io/despacho-nueva-palmira/
```
"El Capitán confía en mí... ¿Qué tan difícil puede ser?"
---
Hecho con ❤️ en Uruguay 🇺🇾
