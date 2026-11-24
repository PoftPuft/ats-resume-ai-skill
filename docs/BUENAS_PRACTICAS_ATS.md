# ⚙️ Buenas Prácticas ATS: Los Bastidores de la Skill

El `SKILL.es.md` de este repositorio se construyó basándose en reglas estrictas de parsing (análisis sintáctico) de Applicant Tracking Systems, además de enfocarse en la eficiencia de consumo de _tokens_ de las LLMs. Aquí detallamos el porqué de cada instrucción contenida en la skill.

### 1. Investigación Web Integrada (LinkedIn)

El mercado tecnológico y de negocios cambia rápidamente. La skill instruye a la IA a hacer un barrido en ofertas recién publicadas en LinkedIn utilizando el cargo que pretende el usuario. Esto garantiza que el currículo no use palabras clave genéricas, sino los términos exactos que los reclutadores están configurando en sus filtros ATS en ese preciso momento.

### 2. Diseño Minimalista y Economía de Tokens

La instrucción exige la creación de un documento en página única, en blanco y negro y sin formato excesivo (como tablas de colores o gráficos de habilidades). Hay dos motivos para esto:

- **Parseabilidad (ATS):** Los bots no leen diseño. Elementos gráficos, cajas de texto flotantes o barras de progreso a menudo corrompen la extracción de datos.
- **Eficiencia de la LLM:** Las IAs consumen _tokens_ para generar respuestas. Obligar a la IA a intentar dibujar un currículo visualmente complejo utilizando código desperdicia el límite de procesamiento y aumenta la chance de alucinaciones. El diseño limpio mantiene a la IA enfocada en la calidad del contenido.

### 3. Formato de Archivo: ¿Por qué exigimos el `.docx`?

Aunque el PDF es genial para mantener el formato visual, puede ser el peor enemigo de sistemas ATS antiguos (que muchas veces leen la página como imagen). El formato `.docx` (Microsoft Word) está estructurado nativamente en texto puro bajo el capó (XML), garantizando una altísima tasa de acierto en la lectura del robot.

### 4. Título del Objetivo

Los algoritmos de IA cruzan la requisición de la vacante (Job Description) con el tope de tu currículo. La skill exige el nombre exacto del cargo deseado (sin intentar "adivinar" lo que quiere el usuario) justo al inicio para garantizar el "match" inicial de indexación.

### 5. Verbos de Acción y Resultados

Las IAs están entrenadas para identificar el impacto que causaste, no solo tus obligaciones. La skill reescribe experiencias insertando verbos de acción proactivos ("Desarrolló", "Optimizó") orientados a resultados.

---

_Documentación integrante de la skill **ats-resume-optimizer**._
_Desarrollada originalmente por [PoftPuft](https://github.com/PoftPuft) bajo licencia CC BY-NC-SA 4.0._