# 📁 Transcripción de audio y generación de FAQ con Whisper

Este flujo de trabajo permite convertir grabaciones de llamadas reales en un conjunto estructurado de preguntas frecuentes (FAQ), utilizando el modelo Whisper de OpenAI de forma totalmente local (sin conexión a servicios externos).

Se incluyen tanto el script de transcripción automática como el archivo JSON con las FAQs generadas y la documentación técnica necesaria para instalar Whisper en un entorno local.

---

## 🎯 Objetivo

Transformar conversaciones grabadas en texto estructurado y generar un FAQ reutilizable para asistentes conversacionales o flujos automatizados de atención al cliente.

---

## ⚙️ Características del flujo

- Transcripción automática de archivos de audio `.mp3` y `.wav` con Whisper local
- Generación automática de archivos `.txt` con el contenido transcrito
- Extracción manual de preguntas y respuestas frecuentes a partir del texto
- Exportación del contenido a formato `.json` estructurado
- Uso totalmente local, sin necesidad de claves API o conexión a servicios externos

---

## 📄 Archivos incluidos

- Script Python: `run_whisper_auto.py`
- Archivo JSON generado: `calls_full_faq_v2.json`
- Documentación técnica: `Add_Documentacion_Whisper_Local.pdf`

---

📂 Carpeta: `/Audio-to-FAQ Whisper/`

Este flujo de trabajo forma parte del desarrollo de un asistente conversacional en entorno local.  
No se incluyen los audios ni las transcripciones originales por motivos de privacidad.
