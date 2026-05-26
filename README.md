<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/4712/4712109.png" />

# 🎙️ Voice Activity Detection Unity

### Librería VAD para Unity con detección inteligente de voz 🚀

<p align="center">
  <b>Voice Activity Detection Unity</b> es una librería desarrollada para detectar actividad de voz en tiempo real dentro de proyectos Unity, permitiendo grabación, buffering y procesamiento de audio mediante una arquitectura modular y extensible.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Unity-VAD-black?style=for-the-badge&logo=unity&logoColor=white">
  <img src="https://img.shields.io/badge/C%23-VoiceDetection-239120?style=for-the-badge&logo=csharp&logoColor=white">
  <img src="https://img.shields.io/badge/Audio-Processing-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/OpenAI-Whisper-412991?style=for-the-badge&logo=openai&logoColor=white">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-samples">Samples</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Voice Activity Detection Unity** es una librería diseñada para proyectos de audio y voz dentro de Unity, enfocada en detectar automáticamente cuándo una persona está hablando.

El sistema permite:

- 🎤 Capturar audio desde múltiples fuentes
- 🧠 Detectar actividad de voz en tiempo real
- 💾 Guardar audio automáticamente
- 📡 Integrar transcripción con Whisper API
- 🔊 Procesar AudioClips dinámicamente
- ⚡ Implementar lógica VAD personalizada
- 🧩 Integrarse fácilmente con proyectos Unity
- 🚀 Crear sistemas de voz inteligentes

---

# ✨ Características

## 🎤 Fuentes de audio compatibles

- 🎙️ Unity Microphone
- 🔊 Unity AudioSource
- 📡 Captura mediante callbacks
- ⚡ Arquitectura extensible
- 🧩 Soporte para fuentes personalizadas

---

## 🧠 Sistemas de detección VAD

### 📦 Queueing Voice Activity Detector

- Menor uso de memoria
- Detección rápida
- Fácil implementación
- Ideal para proyectos ligeros

---

### ⚡ Cumulative Voice Activity Detector

- Mayor estabilidad
- Mejor precisión
- Procesamiento acumulativo
- Ideal para aplicaciones avanzadas

---

## 💾 Buffers de audio

- 📄 Null Buffer
- 🎵 AudioClip Buffer
- 💿 WAV File Buffer
- 🔄 Buffering en tiempo real
- 📡 Exportación de audio

---

## 🌐 Integraciones

- 🤖 OpenAI Whisper API
- 🎧 NAudio
- 🔄 UniTask
- ⚡ UniRx
- 🧩 Unity Package Manager

---

# 👨‍💻 Arquitectura del sistema

## 🎤 Voice Sources

Módulos encargados de capturar audio desde distintas fuentes.

### Funcionalidades

- Captura desde micrófono
- Lectura desde AudioSource
- Streaming de audio
- Procesamiento en tiempo real

---

## 🧠 Voice Activity Detector

Sistema principal encargado de detectar actividad de voz.

### Funcionalidades

- Detección inteligente
- Análisis de amplitud
- Filtrado de ruido
- Activación automática

---

## 💾 Voice Buffers

Módulos encargados de almacenar y exportar audio.

### Funcionalidades

- Guardado WAV
- Buffers dinámicos
- Exportación AudioClip
- Almacenamiento temporal

---

# 🛠️ Tecnologías utilizadas

## ⚙️ Desarrollo

<p>
  <img src="https://skillicons.dev/icons?i=unity,cs" />
</p>

- Unity Engine
- C#
- Audio Processing
- VAD Algorithms

---

## 🎧 Audio & Streaming

<p>
  <img src="https://skillicons.dev/icons?i=github" />
</p>

- NAudio
- AudioClip API
- WAV Encoding
- Audio Buffers

---

## 🔄 Librerías adicionales

- UniTask
- UniRx
- OpenAI Whisper API
- Unity Package Manager

---

# 📂 Estructura del proyecto

```bash
LibreriaVADUnityDeteccionVoz/
│
├── Assets/
│   ├── Mochineko/
│   │   ├── VoiceActivityDetection/
│   │   ├── VoiceActivityDetection.Samples/
│
├── Packages/
├── CHANGELOG.md
├── NOTICE.md
├── LICENSE
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Unity
- .NET / C#
- Unity Package Manager
- Git

---

# 🚀 Configuración del proyecto

## 1️⃣ Agregar dependencias

Editar:

```json
Packages/manifest.json
```

Agregar:

```json
{
  "dependencies": {
    "com.mochineko.voice-activity-detection": "https://github.com/mochi-neko/voice-activity-detection-unity.git?path=/Assets/Mochineko/VoiceActivityDetection#0.4.2",
    "com.cysharp.unitask": "https://github.com/Cysharp/UniTask.git?path=src/UniTask/Assets/Plugins/UniTask",
    "com.neuecc.unirx": "https://github.com/neuecc/UniRx.git?path=Assets/Plugins/UniRx/Scripts"
  }
}
```

---

## 2️⃣ Abrir Unity

Importar el proyecto y esperar la instalación automática de dependencias.

---

## 3️⃣ Ejecutar Samples

Los ejemplos se encuentran en:

```bash
Assets/Mochineko/VoiceActivityDetection.Samples/
```

---

# 🧪 Samples

## 🎤 VAD Sample

- Detección básica de voz
- Activación automática
- Procesamiento en tiempo real

---

## 🔊 VAD Audio Echo

- Reproducción de audio
- Efecto eco
- Buffering dinámico

---

## 🤖 Whisper API Sample

- Transcripción automática
- Integración OpenAI
- Procesamiento de voz

---

## ⚡ AudioSource Sample

- Captura desde AudioSource
- Callback processing
- Streaming interno

---

# 📊 Funcionalidades principales

## 🎙️ Captura de voz

- Grabación automática
- Detección de actividad
- Audio en tiempo real
- Compatibilidad Unity

---

## 🧠 Procesamiento inteligente

- VAD dinámico
- Análisis acumulativo
- Filtrado de ruido
- Gestión de buffers

---

## 🌐 Integración avanzada

- Whisper API
- Exportación WAV
- AudioClip management
- Procesamiento modular

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y desarrollo

- Procesamiento de audio
- Inteligencia de voz
- Integración Unity
- Arquitectura modular
- Sistemas VAD
- APIs de transcripción
- Programación en C#

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 🎙️ Soporte para micrófono nativo
- 🤖 IA avanzada de detección
- 📡 Streaming online
- 🌐 Integración cloud
- 📱 Compatibilidad móvil
- 🔊 Reducción de ruido avanzada
- 🧩 Más buffers personalizados

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/new-feature
```

2. Commit

```bash
git commit -m "✨ Add new feature"
```

3. Push

```bash
git push origin feature/new-feature
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Unity Audio Developer

Desarrollador enfocado en sistemas de audio, procesamiento de voz y herramientas avanzadas para Unity 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT orientado al desarrollo de sistemas de detección de voz y procesamiento de audio para Unity.

---

<div align="center">

### 🎙️ Voice Activity Detection Unity — procesamiento inteligente de voz en tiempo real 🚀

</div>
