Estructura de Automatización Local (Agente Python)
​Este espacio está destinado al desarrollo del agente en Python encargado de:
​Conectarse a la API de Google Sheets para extraer los datos validados por el portal.
​Realizar la inyección directa al motor SQL Server de CONTPAQi.
​Gestionar los logs de auditoría para el despacho contable.
​Nota para la IA: El código debe ser modular, capaz de empaquetarse con PyInstaller y manejar excepciones de conexión SQL.
​Guarda los cambios:
​Dale clic al botón verde "Commit changes..." al final de la página.
​Por qué esto es lo correcto:
​Organización: Ya tienes el index.html (Validador) y tickets.html (Captura) en la raíz, y ahora una carpeta dedicada exclusivamente a la lógica pesada del servidor.  
​Contexto para la IA: Cuando le pidas ayuda a otra IA para programar el agente de Python, solo tendrás que darle el link de este repositorio y decirle: "Trabaja en la carpeta agente_local, necesito que el script lea el Google Sheet y lo inyecte al SQL de Compac".
