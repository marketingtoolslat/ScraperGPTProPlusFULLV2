# 🚀 ScraperGPTProPlus

**ScraperGPTProPlus** es una herramienta avanzada de scraping automatizado y análisis de campañas publicitarias en Facebook Ads Library. Integra una interfaz visual con Gradio y procesamiento en backend para generar insights de forma sencilla, automatizada y exportable.

---

## ✅ ¿Qué hace esta herramienta?

- 🔍 Extrae dinámicamente anuncios activos desde Facebook Ads Library usando URLs o IDs de páginas.
- 📊 Analiza campañas según CTA, idioma, país, copywriting, estilo, número de anuncios, fechas y más.
- 📁 Exporta resultados a `.csv` o Google Sheets.
- 🧠 Integra procesamiento GPT para generar resúmenes inteligentes.
- 🖥 Interfaz visual integrada con Gradio.
- 🔧 Soporta múltiples URLs o IDs simultáneamente.
- ⚙️ Automatización sin interacción manual.
- 🌎 Despliegue en Render (online).

---

## 💻 Tecnologías

- Python 3.x
- Gradio
- Playwright
- Requests, Pandas
- Render (deployment)
- Google Sheets API (opcional)
- OpenAI API (opcional para GPT)

---

## 🛠 Cómo usar

1. Clona o sube el código a tu GitHub.
2. Conecta tu repositorio a [Render](https://render.com).
3. Usa los siguientes comandos:

```
Build command:     pip install -r requirements.txt
Start command:     python backend_scraper.py
```

4. Abre la URL del servicio desplegado.
5. Ingresa la URL de Facebook Ads Library o el ID.
6. ¡Disfruta de tu análisis y exporta cuando quieras!

---

## 📦 Estructura de archivos

- `backend_scraper.py` → motor de scraping
- `dashboard_full.py` → interfaz Gradio visual
- `requirements.txt` → dependencias
- `start.sh` → script de arranque
- `README.md` → documentación del proyecto

---

## 📤 Exportación

- Local `.csv`
- Google Sheets (conectando tu token de servicio)

---

¿Listo para sacarle el jugo a los datos publicitarios con IA?  
Hecho por y para marketers inteligentes 🚀