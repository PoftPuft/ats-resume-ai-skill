# 🛡️ Política de Seguridad

La seguridad y la privacidad de los usuarios de esta Skill son prioridades absolutas. Dado que este proyecto no consiste en software ejecutable, sino en ingeniería de prompts (System Prompt) para LLMs, el alcance de seguridad se centra principalmente en la protección de datos personales y la mitigación de comportamientos no deseados de la Inteligencia Artificial.

## 📌 Alcance de Seguridad

Consideramos como incidentes de seguridad válidos para reporte en este repositorio:

- **Fuga Involuntaria de Datos:** El prompt induce u obliga al usuario a proporcionar datos sensibles (DNI, NIE, dirección exacta) que no deberían solicitarse.
- **Fallos de Output (Prompt Injection):** El prompt puede ser fácilmente subvertido para generar contenidos maliciosos, ofensivos o fuera del ámbito profesional de reclutamiento.
- **Violaciones de Privacidad:** El comportamiento de la IA vulnera las directrices estipuladas en el archivo `AVISO_LEGAL_GDPR.md`.

_Nota: No nos responsabilizamos de cómo terceras empresas (OpenAI, Google, Anthropic) procesan o almacenan los datos introducidos en sus respectivos chats._

## 🚨 Cómo reportar una vulnerabilidad o problema de privacidad

Si encuentras un problema que encaje en el alcance anterior, **NO abras un Issue público** inmediatamente, ya que esto puede exponer la falla antes de que podamos mitigarla en la instrucción principal.

1. Envía un correo directamente al mantenedor del proyecto o utiliza mensajes directos vía [GitHub](https://github.com/PoftPuft).
2. Incluye en el reporte:
   - Qué LLM estabas utilizando (Gemini, ChatGPT, Claude, etc.).
   - El comportamiento exacto que exhibió la IA.
   - El fragmento del prompt que crees que causa el fallo (si lo sabes).
3. Intentaremos responder y aplicar correcciones en el archivo `SKILL.es.md` lo más rápido posible, generalmente dentro de 48 horas.

## ✅ Versiones Soportadas

Solo la versión más reciente presente en la branch `main` del archivo `SKILL.es.md` recibe soporte y actualizaciones de seguridad.

---

_Política de seguridad integrante de la skill **ats-resume-optimizer**._
_Desarrollada originalmente por [PoftPuft](https://github.com/PoftPuft) bajo licencia CC BY-NC-SA 4.0._