# 🎬 GODS Clasificador

**Clasificador Inteligente de Videos con IA para Creadores de Contenido**

[![Descargar](https://img.shields.io/badge/Descargar-v1.0.0-blue?style=for-the-badge)](https://github.com/ader200/gods/releases/download/Gods_v1.0.0/gods_v1.0.0.exe)
[![Licencia MIT](https://img.shields.io/badge/Licencia-MIT-green?style=for-the-badge)](LICENSE)
[![YouTube](https://img.shields.io/badge/YouTube-Tutoriales-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/@gomenoflolixd1982)

---

## 📖 Descripción

GODS Clasificador es una aplicación de escritorio con interfaz gráfica que utiliza **Inteligencia Artificial** (Google Gemini) para clasificar y organizar automáticamente tus videos. Analiza el contenido de cada video, genera nombres descriptivos, crea categorías inteligentes y produce descripciones optimizadas con hashtags para redes sociales.

**🌐 Página Web del Proyecto:** [https://ader200.github.io/gods](https://ader200.github.io/gods)

---

## ✨ Características Principales

- 🤖 **Clasificación Automática con IA** - Analiza el contenido usando Google Gemini AI
- 📝 **Renombrado Inteligente** - Genera nombres descriptivos basados en el contenido real
- 📁 **Organización por Categorías** - Crea carpetas automáticamente según el tema del video
- 💬 **Descripciones para Redes Sociales** - Genera descripciones optimizadas para YouTube, TikTok, Instagram
- #️⃣ **Hashtags Relevantes** - Crea hashtags trending basados en el contenido
- ⚡ **Interfaz Moderna** - GUI intuitiva con progreso en tiempo real
- 🎯 **Progreso Detallado** - Barras de progreso, tiempo estimado y notificaciones en español
- 💾 **Ejecutable Independiente** - No requiere instalación de Python ni dependencias

---

## ⬇️ Descargas

### Versión Actual: **v1.0.0**

| Formato | Tamaño | Enlace de Descarga |
|---------|--------|-------------------|
| **Ejecutable (.exe)** | ~50 MB | [⬇️ gods_v1.0.0.exe](https://github.com/ader200/gods/releases/download/Gods_v1.0.0/gods_v1.0.0.exe) |
| **Comprimido (.rar)** | ~30 MB | [⬇️ gods_v1.0.0.rar](https://github.com/ader200/gods/releases/download/Gods_v1.0.0/gods_v1.0.0.rar) |

**📦 Todas las versiones:** [Ver Releases](https://github.com/ader200/gods/releases)

> **Nota:** Si Windows Defender bloquea el archivo, es un falso positivo común con ejecutables de PyInstaller. Agrégalo a las excepciones de forma segura.

---

## 🚀 Inicio Rápido

### 1️⃣ Descargar e Instalar

1. Descarga el archivo `.exe` o `.rar` desde la sección de [Descargas](#️-descargas)
2. Si descargaste el `.rar`, descomprímelo
3. Ejecuta `gods_v1.0.0.exe`

### 2️⃣ Configurar API Key

1. Obtén tu API Key gratuita de Google Gemini: [https://makersuite.google.com/app/apikey](https://makersuite.google.com/app/apikey)
2. Abre GODS Clasificador
3. Ingresa tu API Key en el campo correspondiente
4. Haz clic en **"Guardar"**

### 3️⃣ Clasificar Videos

1. Haz clic en **"Seleccionar"** junto a "Carpeta de Videos"
2. Elige la carpeta con tus archivos `.mp4`
3. Haz clic en **"▶ Iniciar Clasificación"**
4. ¡Observa cómo la IA organiza tus videos automáticamente!

---

## 📺 Video Tutoriales

Aprende a usar GODS Clasificador con estos tutoriales paso a paso:

| Tutorial | Duración | Enlace |
|----------|----------|--------|
| 🔧 Instalación y Configuración Inicial | 5 min | [Ver en YouTube](https://youtu.be/ZqW798K8ndg) |
| 🎬 Cómo Clasificar tus Videos | 8 min | [Ver en YouTube](https://youtu.be/RHqwW4vYwjw) |
| 💡 Tips y Solución de Problemas | 6 min | [Ver en YouTube](https://youtu.be/SFHXSHISAmg) |

**📺 Canal de YouTube:** [https://www.youtube.com/@gomenoflolixd1982](https://www.youtube.com/@gomenoflolixd1982)

---

## 💻 Requisitos del Sistema

### Mínimos
- **Sistema Operativo:** Windows 10 (64-bit) o superior
- **RAM:** 4 GB (8 GB recomendado)
- **Espacio en Disco:** 500 MB
- **Internet:** Conexión activa (para la API de Gemini)

### Necesarios
- **API Key de Google Gemini** (gratuita)
- **Videos en formato .mp4** con pista de audio
- **Audio en español** (recomendado para mejor precisión)

---

## 🎯 Ejemplo de Uso

### Antes de usar GODS Clasificador:
```
videos/
  ├── VID_20231120_143022.mp4
  ├── VID_20231121_091533.mp4
  └── VID_20231122_183044.mp4
```

### Después de usar GODS Clasificador:
```
videos/
  ├── Minecraft/
  │   ├── tutorial_construccion_casa.mp4
  │   └── tutorial_construccion_casa.txt
  ├── Vlogs/
  │   ├── dia_en_la_playa.mp4
  │   └── dia_en_la_playa.txt
  └── Gaming/
      ├── gameplay_fortnite_victoria.mp4
      └── gameplay_fortnite_victoria.txt
```

Cada archivo `.txt` contiene:
- Descripción optimizada para redes sociales
- Hashtags relevantes y trending
- Categoría asignada

---

## 🔧 Solución de Problemas

### "No se encontraron archivos .mp4"
- Verifica que la carpeta contenga videos `.mp4`
- Los videos deben estar directamente en la carpeta, no en subcarpetas

### "Error procesando audio"
- Asegúrate de que el video tenga pista de audio
- Verifica que el formato sea `.mp4` válido

### "IA bloqueó la respuesta"
- El contenido del video puede ser sensible
- La IA tiene filtros de seguridad activados

### "Límite de API alcanzado"
- Estás haciendo demasiadas peticiones
- La aplicación esperará automáticamente y reintentará
- Considera espaciar el procesamiento de videos

### Windows Defender bloquea el .exe
- Es un falso positivo común con PyInstaller
- Agrega el archivo a las excepciones de Windows Defender
- El programa es seguro de usar

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

**Permisos:**
- ✅ Uso comercial
- ✅ Distribución
- ✅ Uso privado

**Condiciones:**
- 📋 Incluir aviso de licencia y copyright

**Limitaciones:**
- ❌ Sin garantía
- ❌ Sin responsabilidad del autor

---

## 🔗 Enlaces Importantes

- 🌐 **Página Web:** [https://ader200.github.io/gods](https://ader200.github.io/gods)
- 📦 **Releases:** [https://github.com/ader200/gods/releases](https://github.com/ader200/gods/releases)
- 🐛 **Reportar Bug:** [https://github.com/ader200/gods/issues](https://github.com/ader200/gods/issues)
- 💬 **Discusiones:** [https://github.com/ader200/gods/discussions](https://github.com/ader200/gods/discussions)
- 📺 **YouTube:** [https://www.youtube.com/@gomenoflolixd1982](https://www.youtube.com/@gomenoflolixd1982)
- 🔑 **Obtener API Key:** [https://makersuite.google.com/app/apikey](https://makersuite.google.com/app/apikey)

---

## 📝 Notas Adicionales

- **Idioma:** La transcripción está optimizada para español (es-ES)
- **Formato:** Solo procesa archivos `.mp4`
- **Duración:** Videos más largos tardan más en procesarse
- **Internet:** Requiere conexión activa para usar la API de Gemini
- **Privacidad:** Los videos se procesan localmente, solo el audio se envía a la API de Gemini

---

## 🤝 Soporte

¿Necesitas ayuda? Aquí tienes varias opciones:

1. 📺 **Ver los tutoriales en YouTube** - La forma más rápida de aprender
2. 🐛 **Reportar un bug** - [Crear issue](https://github.com/ader200/gods/issues)
3. 💬 **Hacer una pregunta** - [Iniciar discusión](https://github.com/ader200/gods/discussions)
4. 📧 **Contacto directo** - A través del canal de YouTube

---

<div align="center">

**Desarrollado con ❤️ usando Python, tkinter y Google Gemini AI**

⭐ Si te gusta este proyecto, dale una estrella en GitHub

[⬇️ Descargar](https://github.com/ader200/gods/releases/latest) • [🌐 Página Web](https://ader200.github.io/gods) • [📺 Tutoriales](https://www.youtube.com/@gomenoflolixd1982)

</div>
