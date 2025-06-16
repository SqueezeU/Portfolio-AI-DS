## 🟨 Audio Transcription and FAQ Generation with Whisper

This project is part of a workflow designed to convert real voice calls into a structured database of frequently asked questions (FAQs).  
It uses the **Whisper** model from OpenAI to perform transcriptions **automatically and offline** (local installation).

---

### 🎯 Objective

Transform voice recordings into text and generate a structured set of anonymous FAQs.  
This type of structure can serve as a basis for virtual assistants or conversational bots.

---

### ⚙️ Workflow Features

- Automatic transcription of `.mp3` and `.wav` files using local Whisper  
- Generation of `.txt` files for each audio recording  
- Manual extraction of frequently asked questions and answers from the transcribed content  
- Export of results in structured `.json` format  
- Detailed technical documentation included in PDF

---

### 📂 Project Files

- `run_whisper_auto.py` – Script for automatic transcription with local Whisper  
- `calls_full_faq_v2.json` – Frequently asked questions generated from the transcriptions  
- `Add_Documentacion_Whisper_Local.pdf` – Technical guide for setup and usage of the script

---

> ⚠️ This project is part of the general workflow for developing a conversational bot.  
> Original recordings are not included due to privacy concerns.
