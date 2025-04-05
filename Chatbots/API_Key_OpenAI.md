# 🔐 Cómo configurar la clave API de OpenAI (local)

Para que las aplicaciones locales funcionen con GPT-4 u otros modelos de OpenAI, es necesario configurar correctamente una clave API personal.

---

## 🧾 1. ¿Dónde obtener la clave?

Accede a: [https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)  
➤ Inicia sesión y haz clic en **“Create new secret key”**  
➤ Copia la clave (por ejemplo: comienza con `sk-...`)  
🔐 Guárdala en un lugar seguro – solo se muestra una vez.

---

## ⚙️ 2. Cómo configurar la clave localmente (Windows)

1. Abre la ventana de **variables de entorno del sistema**  
   (Panel de control → Sistema → Configuración avanzada → Variables de entorno)

2. En “Variables de usuario”, haz clic en **Nueva…**

3. Introduce:

   - **Nombre de la variable**: `OpenAI_API_Key`  
   - **Valor**: `sk-...` (tu clave secreta)

4. Haz clic en **Aceptar** para guardar.

---

## ✅ 3. Probar la configuración en JupyterLab

Abre un nuevo Notebook y ejecuta este código:

```python
import os

api_key = os.getenv("OpenAI_API_Key")

if api_key and api_key.startswith("sk-"):
    print("✅ Clave API detectada correctamente.")
else:
    print("⚠️ No se detectó ninguna clave API.")
