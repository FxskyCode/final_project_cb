Proyecto Final - Respuesta en Vivo a Incidentes
Proyecto Final – Live Incident Response

La organización 4Geeks Academy ha detectado comportamientos anómalos en uno de sus servidores internos. El equipo de ciberseguridad ha sido activado para contener la amenaza, identificar el alcance del incidente y restaurar la seguridad del sistema.

Asumirás el rol de Analista de Ciberseguridad, encargado de:

    Inspeccionar el sistema comprometido en tiempo real.
    Detectar vulnerabilidades explotadas.
    Identificar persistencias maliciosas.
    Restaurar la integridad y disponibilidad del sistema.
    Elaborar un informe profesional con recomendaciones.

🌱 ¿Cómo empezar este proyecto?

    Descarga la máquina virtual desde este enlace:

https://storage.googleapis.com/cybersecurity-machines/4geeks-server-lab.ova

    Importa la máquina en tu gestor de virtualización preferido (VirtualBox, VMware, etc.).
    Una vez iniciada la máquina, ¡ya puedes comenzar con el laboratorio!
    Las credenciales para acceder a la maquina son:

username: sysadmin

password: Sys4dm1n2024

📝 Instrucciones

Dado que el servidor afectado forma parte de un sistema crítico en producción, no es posible apagarlo ni extraer su disco para análisis forense tradicional. Por eso, tu tarea se centrará en un enfoque de Live Incident Response, es decir, inspección directa sobre un sistema activo. Esto es debido a que:

    La disponibilidad del servicio es prioritaria.
    No hay tiempo ni capacidad para un apagado controlado.
    El objetivo es contener la amenaza con rapidez, documentar hallazgos y restaurar operaciones.

Fase 1: Reconocimiento y recolección de evidencias

    Analiza el servidor comprometido en tiempo real.
    Detecta huellas de la intrusión.
    Identifica las acciones del atacante: procesos maliciosos, usuarios sospechosos, cronjobs anómalos, reglas de red modificadas, etc.
    Comienza a documentar tus hallazgos con capturas y descripciones justificadas.

    📘 Para guiarte en esta fase, puedes consultar la Guía de Investigación de Incidentes para Analistas Blue Team, que detalla comandos clave, razonamientos técnicos y mejores prácticas.

Fase 2: Remediación y restauración del sistema

Elimina cualquier rastro del atacante, restaura el estado seguro del servidor y refuerza su configuración de seguridad.

Durante esta fase deberás:

    Evaluar los hallazgos de la Fase 1 y decidir qué acciones correctivas son necesarias.
    Aplicar medidas de remediación que garanticen la eliminación de cualquier persistencia maliciosa.
    Verificar que el sistema haya recuperado su integridad y que solo se mantengan configuraciones legítimas.
    Implementar medidas de fortalecimiento del sistema para evitar incidentes similares en el futuro.

    Justifica cada acción que apliques. Tu razonamiento y evidencia serán tan importantes como las acciones técnicas.

Fase 3: Informe técnico final

Prepara un informe único y completo, que incluya:

    Revisión del incidente desde el servidor activo (Live Incident Response).
    Vulnerabilidades detectadas y corregidas.
    Acciones de contención, erradicación y recuperación aplicadas.
    Recomendaciones para fortalecer el sistema y evitar futuras intrusiones.
    Capturas justificadas de comandos clave y hallazgos técnicos.

Este informe debe demostrar tu razonamiento técnico, claridad en la documentación y capacidad de respuesta ante incidentes reales.
