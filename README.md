# JANEY – Asistente de Voz Personal
**Creado por GGrubi42**

JANEY es una asistente de voz inspirada en JARVIS de Iron Man, diseñada para funcionar desde una Raspberry Pi portátil o desde una PC. Permite controlar música, obtener la hora, traducir idiomas en tiempo real y ejecutar múltiples tareas mediante comandos de voz.

## 🧠 ¿Qué puede hacer?

- Activarse por voz (wakeword “Janey”) en Raspberry Pi
- Reconocimiento directo de voz en PC (sin wakeword)
- Control completo de música (reproducción, pausa, siguiente, anterior, detener)
- Traducción en tiempo real de otros idiomas al español
- Responder preguntas básicas como la hora

## 🎧 Comandos de voz disponibles

Decí cualquiera de estos comandos después de “Janey” (en Raspberry Pi), o directamente (en PC):

### 🔊 Música
- `Música-Janey`  
  → Reproduce música aleatoria
- `Janey, pausa la música`  
  → Pausa la reproducción
- `Janey, reproduce la música de nuevo`  
  → Reanuda la reproducción
- `Janey, siguiente`  
  → Pasa a la siguiente canción
- `Janey, atrás`  
  → Vuelve a la canción anterior
- `Janey, detener la música` o `para la música`  
  → Detiene toda la reproducción

### 🕒 Información
- `Janey, la hora`  
  → Te dice la hora actual

### 🌐 Traducción
- `Traducción-Janey`  
  → Activa modo de traducción automática de voz al español

## ⚙️ Tecnología utilizada

- **Python** como lenguaje principal
- **Vosk** para reconocimiento de voz offline
- **eSpeakNG** o **pyttsx3** para síntesis de voz
- **pygame** para reproducir música
- **googletrans** para traducción automática
- **pvporcupine** para activación por wakeword en Raspberry Pi

## 📁 Estructura de carpetas esperada

- `/music/` → Carpeta donde colocar tus archivos `.mp3`
- `/vosk-model/` → Carpeta con el modelo de Vosk en español

## 📦 Versiones disponibles

- **Versión Raspberry Pi** → Usa wakeword (palabra clave “Janey”)
- **Versión PC** → No requiere wakeword, escucha directamente

---

**Creado por Grubi42**
