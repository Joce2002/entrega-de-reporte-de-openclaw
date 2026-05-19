# entrega-de-reporte-de-openclaw

Universidad: [INSTITUTO TECNOLÓGICO DE TIJUANA]

Carrera: [Tecnologías de la Información y Comunicaciones]

Materia: [Ing Conocimiento]

Estudiante: Tome Salazar Karen Jocelyn

Fecha: [19 de Mayo 2026]

1. Introducción
OpenClaw es una herramienta de código abierto que permite integrar modelos de inteligencia artificial locales (como Ollama) con plataformas de mensajería (Telegram, WhatsApp, etc.). Este reporte detalla el proceso de configuración, personalización y puesta en marcha de un asistente de IA mediante OpenClaw, utilizando el modelo Qwen 3.5 y un bot de Telegram como interfaz de usuario. El objetivo es demostrar la capacidad de crear soluciones de IA accesibles y personalizables para entornos académicos o personales.

Instalacion
<img width="1294" height="975" alt="image" src="https://github.com/user-attachments/assets/62037d09-747d-4359-90d1-d653aa24e0e6" />

Acceso a la página oficial:
https://openclaw.ai/ para obtener el script de instalación.

Ejecución del comando en PowerShell:


irm https://openclaw.ai/install.ps1 | iex

<img width="1331" height="767" alt="image" src="https://github.com/user-attachments/assets/de8cedde-ee9f-4275-8e89-e321093cc01d" />

Integración con Telegram

Creación del bot en Telegram:

Se accedió a BotFather en Telegram y se ejecutaron los comandos:

/start  
/newbot

<img width="1701" height="871" alt="image" src="https://github.com/user-attachments/assets/f5800b11-be13-40be-b835-04fc4efc2c9b" />


Se asignaron los siguientes datos:

Nombre del bot: Ultron

Username: galletggresaws_ai_bot

API Key obtenida: 8615605568:AAEvTJC1-mOQBDT4EMG7WmffGMl6idWMAc8

<img width="1726" height="909" alt="image" src="https://github.com/user-attachments/assets/54332196-907d-4d10-bf21-1f468f6f6c47" />

El bot se conectó a Telegram y estuvo listo para recibir comandos.

<img width="1906" height="768" alt="image" src="https://github.com/user-attachments/assets/8a2ed4b6-25e3-4b0b-969e-c214d9d14a49" />

<img width="1899" height="794" alt="image" src="https://github.com/user-attachments/assets/d5fbe384-cf74-4e2b-9305-74b13992233f" />

Funcionalidad de Todos los Skills

/ia [pregunta]
Envía la consulta al modelo de IA local (Qwen 3.5) y devuelve respuestas precisas.
Ejemplo: /ia ¿Cuál es la capital de Francia? → La capital de Francia es París.


/clima [ciudad]
Proporciona datos climáticos en tiempo real (temperatura, humedad, pronóstico, viento, etc.) mediante OpenWeatherMap.
Ejemplo: /clima Madrid → Muestra clima actual y pronóstico detallado con emojis y formato estructurado.


/motivacion
Genera frases motivacionales personalizadas mediante el modelo de IA local.
Ejemplo: /motivacion → ¡Sigue adelante! Cada pequeño paso te acerca a tus metas. 💪✨


/hoy
Muestra efemérides o celebraciones del día actual utilizando el modelo de IA.
Ejemplo: /hoy → 🎉 Hoy se celebra el Día Internacional de la Felicidad. ¡Sonríe! 😊





