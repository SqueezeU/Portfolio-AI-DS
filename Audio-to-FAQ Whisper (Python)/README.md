# 📁 Transcripción de audio y generación de FAQ con Whisper

Este proyecto forma parte de un flujo de trabajo para convertir llamadas reales en una base de datos estructurada con preguntas frecuentes (FAQ).  
Se utiliza el modelo **Whisper** de OpenAI para realizar transcripciones de manera automática y **sin conexión** (instalación local).

---

## 🎯 Objetivo

Transformar grabaciones de voz en texto y generar un conjunto estructurado de FAQs anónimas.  
Este tipo de estructura puede utilizarse como base para asistentes virtuales o bots conversacionales.

---

## ⚙️ Características del flujo

- Transcripción automática de archivos `.mp3` y `.wav` con Whisper local
- Generación de archivos `.txt` para cada grabación
- Extracción manual de preguntas y respuestas frecuentes a partir del contenido transcrito
- Exportación de los resultados en formato `.json` estructurado
- Documentación técnica detallada incluida en PDF

---

## 📄 Archivos del proyecto

- `run_whisper_auto.py` → Script de transcripción automática con Whisper local
- `calls_full_faq_v2.json` → Preguntas frecuentes generadas a partir de las transcripciones
- `Add_Documentacion_Whisper_Local.pdf` → Manual técnico con pasos de instalación y uso del script

---

📂 Este proyecto es parte del flujo de trabajo general para el desarrollo de un bot conversacional.  
Las grabaciones originales no están incluidas por motivos de privacidad.
