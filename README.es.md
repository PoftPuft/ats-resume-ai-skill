# 🚀 ATS & AI Resume Optimizer Skill

Una skill universal de prompt (instrucción de sistema) diseñada para transformar LLMs (Gemini, ChatGPT, Claude) en especialistas de reclutamiento. El enfoque principal es crear desde cero, reescribir y optimizar currículos para sortear los filtros de **Applicant Tracking Systems (ATS)** y algoritmos de cribado por Inteligencia Artificial.

## 🎯 ¿Por qué usar esta Skill?

Las empresas modernas utilizan software de cribado que lee currículos buscando palabras clave, estructuras lineales y patrones específicos. Un currículo visualmente bonito, pero mal estructurado en texto, a menudo es descartado antes de llegar a un humano. Esta skill garantiza que tu currículo "hable el idioma" de los robots de reclutamiento y genera un archivo listo para enviar.

## 🛠️ Cómo Utilizar

1. Copia el contenido del archivo [`SKILL.es.md`](SKILL.es.md).
2. Pégalo en la sección de configuración de tu IA preferida:
   - **Gemini:** Crea una nueva "Habilidad" (función que reemplaza a los antiguos "Gems").
   - **ChatGPT:** Pégalo en la sección "Custom Instructions" o crea un GPT personalizado.
   - **Claude:** Utiliza la funcionalidad de "Projects" para añadir el prompt de sistema.
3. Inicia la conversación. Tienes dos opciones:
   - **Opción A (Actualización):** Envía tu currículo actual adjunto (PDF o texto) y pide a la IA que lo optimice. La IA siempre preguntará cuál es el puesto objetivo antes de empezar.
   - **Opción B (Creación desde Cero):** Solo di "Quiero crear mi currículo". La skill activará el **Modo Cuestionario**, haciendo preguntas puntuales sobre tu carrera para construir el documento.

## ✨ Funcionalidades Principales

- **Análisis de Mercado vía LinkedIn:** Si la IA tiene acceso a web, busca ofertas reales en LinkedIn con el título que deseas y extrae las palabras clave más demandadas del mercado en este momento.
- **Integración de Memoria:** Recupera el historial de herramientas y área de actuación guardados en el perfil de la IA.
- **Diseño ATS Minimalista (Página Única):** Se centra en un diseño en blanco y negro, estructurado, sin elementos gráficos, ahorrando _tokens_ de la IA y garantizando que tanto reclutadores humanos como bots lean lo que importa.
- **Exportación a `.docx`:** La IA está instruida para generar un archivo Word listo para descargar, facilitando futuras ediciones y asegurando la mejor compatibilidad con lectores ATS.

## 🗂️ Estructura del Repositorio

- [`SKILL.es.md`](SKILL.es.md): El código fuente del prompt principal (System Prompt) para inyectar en la IA.
- [`README.es.md`](README.es.md): Documentación principal y escaparate del proyecto.
- [`SECURITY.es.md`](SECURITY.es.md): Política de seguridad, privacidad y mitigación de vulnerabilidades en prompts.
- [`LICENSE`](LICENSE): Licencia Creative Commons (CC BY-NC-SA 4.0).
- [`docs/BUENAS_PRACTICAS_ATS.md`](docs/BUENAS_PRACTICAS_ATS.md): Documentación técnica sobre parsers ATS y las reglas aplicadas.
- [`docs/AVISO_LEGAL_GDPR.md`](docs/AVISO_LEGAL_GDPR.md): Términos de uso, privacidad y protección de datos sensibles (LGPD/GDPR).

### 🌐 Versiones Multilingües

- **English:** [`README.md`](README.md) | [`SKILL.md`](SKILL.md) | [`SECURITY.md`](SECURITY.md) | [`docs/BEST_PRACTICES_ATS.md`](docs/BEST_PRACTICES_ATS.md) | [`docs/LEGAL_NOTICE_LGPD.md`](docs/LEGAL_NOTICE_LGPD.md)
- **Português:** [`README.pt.md`](README.pt.md) | [`SKILL.pt.md`](SKILL.pt.md) | [`SECURITY.pt.md`](SECURITY.pt.md) | [`docs/BOAS_PRATICAS_ATS.md`](docs/BOAS_PRATICAS_ATS.md) | [`docs/AVISO_LEGAL_LGPD.md`](docs/AVISO_LEGAL_LGPD.md)

## 👨‍💻 Autoría y Créditos

Este proyecto fue ideado, desarrollado y es mantenido por **[PoftPuft](https://github.com/PoftPuft)**.
Si esta skill optimizó tu currículum y te ayudó a conseguir una entrevista, conéctate conmigo en GitHub y comparte tu éxito.

## ⚖️ Licencia y Contribuciones

Siéntete libre de abrir _issues_ o enviar _pull requests_ con sugerencias. Este proyecto está bajo la licencia **Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)**, protegiendo los derechos de uso del autor original y prohibiendo la monetización o uso comercial por terceros.