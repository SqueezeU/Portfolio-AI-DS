# 🤖 Chatbots

En esta carpeta se documentan ejemplos de chatbots, flujos conversacionales y pruebas con modelos de lenguaje grandes (LLMs).

# 💬 Chatbots – Aplicaciones conversacionales con IA

Este apartado presenta dos ejemplos de chatbot desarrollados durante mis ejercicios prácticos.  
Uno utiliza una conexión en la nube (GPT-4 + Gradio), el otro emplea recuperación local de información (RAG) con llama-index.

---

## 🤖 Chatbot Cloud con GPT-4 (Gradio)

Este bot simula un asistente de atención al cliente utilizando **Gradio** como interfaz web y **GPT-4** como motor de respuestas.

🔍 Componentes:
- Prompts definidos
- Interfaz de usuario con Gradio
- Codificación directa en Python

📎 Notebook: `Bot Cloud Gradio + GPT4.ipynb`

---

## 🧠 Chatbot con recuperación local (RAG)

Una segunda versión implementa un enfoque de **Retrieval-Augmented Generation (RAG)**.  
Utiliza documentos locales combinados con generación de respuestas mediante GPT-4.

🔧 Herramientas utilizadas:
- `llama-index` para indexación de documentos locales (`.txt`, `.csv`, `.pdf`)
- `OpenAI` como motor generativo
- `Gradio` como interfaz conversacional

📎 Notebook: `RAG_llama_index_Errol.ipynb`  
📄 Explicación complementaria: `Bot_Cliente_Codigo_y_Explicacion_ES.docx`

---

## 🔐 Cómo usar la API de OpenAI localmente

El archivo [`API_Key_OpenAI_Einbinden.md`](../Chatbots/API_Key_OpenAI_Einbinden.md) explica cómo añadir tu clave de API de OpenAI como variable de entorno local (Windows), sin escribirla en el código.

⚠️ Las claves API nunca deben subirse a GitHub.

...


