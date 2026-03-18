---
layout: default
title: MÓDULO 6
---

## MÓDULO 6 — Límites, errores comunes y buenas prácticas

> Volver al [inicio](./)

Llegamos al módulo que más gente se salta cuando aprende IA por su cuenta, y que más falta hace. Saber usar la herramienta es importante. Saber **cuándo no confiar en ella** es igual de importante. Este módulo no es para asustar sino para que salgan con criterio: saber qué le puedes pedir, qué debes verificar y qué nunca debes hacer.

> 💡 **Frase clave:** *"La IA es tan confiable como tu capacidad de cuestionarla."*

---

### Parte 1: Lo que la IA no hace bien — y hay que saber

---

#### 🔴 Las alucinaciones: el error más peligroso porque no avisa

Las alucinaciones ocurren cuando la IA entrega información incorrecta, mezcla hechos o simplemente inventa algo que suena real. No lo hace con mala intención: es parte de cómo están diseñados los modelos actuales, que predicen palabras según probabilidades, no certezas.

Lo más traicionero no es que se equivoque. Es que la IA responde con confianza a pesar de que la información es falsa. Esta diferencia es vital, pues los usuarios tienden a confiar en las respuestas seguras aunque sean incorrectas.

Un ejemplo concreto del tipo que puede pasarle a cualquiera del grupo:

> *Le preguntas a ChatGPT por un proveedor de sonido en Lima y te da nombre, teléfono, dirección y reseñas. Todo suena real. Pero el teléfono no existe, la dirección es de otro negocio y las reseñas las inventó. La IA no sabía que no sabía.*

Según análisis de la startup Vectara, la tasa de alucinación de los chatbots oscila entre un 3% y un 27% dependiendo del modelo y el tipo de pregunta. No es un error raro. Es una característica del sistema.

**¿Cuándo hay más riesgo de alucinación?**

- Datos muy locales y específicos (proveedores, precios, personas, lugares concretos)
- Información reciente que puede no estar en su entrenamiento
- Números, estadísticas y citas con fuente específica
- Preguntas que tienen una respuesta muy concreta (fechas exactas, nombres propios, leyes)

**¿Cuándo hay menos riesgo?**

- Tareas de creación y redacción (el "error" es de calidad, no de dato falso)
- Explicaciones de conceptos generales y bien documentados
- Análisis de texto que tú mismo le proporcionas
- Cuando usa búsqueda web en tiempo real con fuentes citadas (Perplexity)

---

**🔴 Matemáticas y cálculos complejos**
Los modelos de lenguaje no calculan: razonan en texto. Pueden equivocarse en operaciones que parecen simples. Si necesitas cálculos exactos, verifica siempre con una calculadora o pídele que use su herramienta de ejecución de código para calcular.

---

**🔴 Información local muy específica**
Precios actuales de proveedores en Lima, horarios de negocios, disponibilidad de productos locales, regulaciones municipales recientes. Aquí la IA es especialmente propensa a inventar con confianza. La solución: Perplexity con búsqueda en tiempo real o verificar directamente con la fuente.

---

**🔴 Todo lo que ocurrió recientemente**
Salvo las IAs con acceso a internet en tiempo real (Perplexity, Gemini con búsqueda activada), los modelos tienen una fecha de corte de conocimiento. Incluso los sistemas más avanzados pueden generar errores cuando se enfrentan a información reciente, preguntas ambiguas o datos incompletos. Por ese motivo, los especialistas recomiendan utilizarlos como apoyo para la búsqueda de información, pero siempre contrastando las respuestas con fuentes adicionales.

---

**🔴 Datos sensibles y confidenciales**
Este punto merece su propio momento en el módulo, especialmente con la monitora de servidores presente:

> 🚨 **Nunca pegar en ninguna IA pública:** contraseñas o credenciales, datos personales de clientes (nombre, DNI, cuenta bancaria, teléfono), información interna confidencial de empresas, IPs y arquitectura de red real, fragmentos de código con variables de entorno reales, logs con información identificable.

La razón práctica: todo lo que escribes en un chat de IA puede usarse para mejorar los modelos, a menos que uses versiones enterprise con contratos de privacidad de datos. Lo que entra, no necesariamente se queda solo contigo.

---

### Parte 2: Errores comunes de usuarios nuevos

Estos son los patrones que más se repiten cuando alguien empieza a usar IA sin guía:

---

**❌ Error 1 — Creerle todo sin verificar**
Ya lo cubrimos con las alucinaciones. El hábito que hay que desarrollar: antes de usar un dato concreto que la IA te dio (precio, estadística, nombre, fecha), verificarlo con una fuente primaria. No siempre, pero sí cuando importa.

**¿Cómo detectar una posible alucinación?**

- Te dio un número muy específico sin citar fuente
- Mencionó un nombre o negocio local que no reconoces
- La respuesta suena perfecta y completa pero nunca habías visto esa información antes
- Le preguntas de dónde sacó eso y no puede mostrarte la fuente

---

**❌ Error 2 — Prompt vago + frustración + abandono**
"Le pregunté y me dio una respuesta horrible." Casi siempre esto es un problema del prompt, no de la IA. El error es concluir que "la IA no sirve" en lugar de reformular la instrucción. *(Este error se ataca directamente con el Módulo 2.)*

---

**❌ Error 3 — No iterar**
Pedir una vez, no quedar conforme, cerrar la pestaña. La IA está diseñada para trabajar en conversación. El primer resultado es un borrador. La magia está en el segundo, tercero y cuarto intercambio.

---

**❌ Error 4 — Usar solo una IA para todo**
Usar únicamente ChatGPT cuando Perplexity es mejor para verificar datos, NotebookLM es mejor para analizar un contrato y Claude es mejor para analizar un log técnico. Conocer el mapa (Módulo 1) es precisamente para evitar este error.

---

**❌ Error 5 — No aprovechar el contexto y repetir siempre las mismas instrucciones**
Empezar cada conversación desde cero cuando existe la Gema, el Proyecto o el Skill que ya tiene todo ese contexto cargado. Este error cuesta tiempo todos los días. *(Se ataca con los Módulos 3 y 3B.)*

---

**❌ Error 6 — Tratar a la IA como un oráculo en decisiones importantes**
Pedirle que decida por ti en lugar de pedirle que te ayude a pensar. *"¿Debo invertir en este proveedor?"* vs *"Ayúdame a evaluar los pros y contras de este proveedor según estos criterios."* La segunda pregunta usa la IA como lo que es: un amplificador de tu criterio, no un reemplazo.

---

### Parte 3: Buenas prácticas — el kit de convivencia con la IA

---

**✅ Práctica 1 — Construye tu biblioteca personal de prompts**
Cuando encuentres un prompt que funciona muy bien para una tarea tuya, guárdalo. En una nota, un documento, donde quieras. Con el tiempo vas a tener una colección personalizada que vale más que cualquier guía genérica, porque está calibrada a tu trabajo real.

---

**✅ Práctica 2 — Itera siempre**
El primer resultado es un punto de partida. Nunca el final. Si no quedaste conforme, no abandones: refina. *"Esto estuvo bien pero necesito que sea más corto y cambie el tono a más informal."* La IA mejora con cada vuelta.

---

**✅ Práctica 3 — Pídele que cite sus fuentes cuando importa**
Puedes agregar al final de cualquier prompt: *"Para cada dato estadístico o afirmación factual que incluyas, indica la fuente."* Esto no garantiza que la fuente sea real, pero reduce alucinaciones y te da algo que verificar. Diseñar prompts que obliguen al modelo a devolver citas o a decir que no sabe algo cuando la información no está disponible es uno de los métodos más efectivos para reducir la frecuencia de alucinaciones.

---

**✅ Práctica 4 — Revisa periódicamente qué recuerda la IA sobre ti**
La memoria de ChatGPT y el contexto de tus Gemas/Proyectos acumulan información con el tiempo. Revisarlo cada mes o dos meses sirve para corregir datos desactualizados, eliminar cosas que ya no aplican y agregar contexto nuevo. Una IA con contexto desactualizado puede darte sugerencias que ya no encajan con tu situación real.

---

**✅ Práctica 5 — Anonimiza antes de pegar (especialmente en entornos de trabajo)**
Si necesitas ayuda con algo de tu trabajo que contiene datos reales, primero reemplaza los datos sensibles con placeholders: `[NOMBRE_CLIENTE]`, `[MONTO]`, `[SERVIDOR_X]`. La IA analiza igual el patrón o el problema sin necesidad de ver los datos reales.

---

**✅ Práctica 6 — Para entornos corporativos: usar solo versiones enterprise**
Adoptar la tecnología con un enfoque crítico, basado en datos confiables y con supervisión humana, permite maximizar los beneficios mientras se minimizan los riesgos. En entornos bancarios o con información sensible de clientes, la única opción segura es usar versiones enterprise (ChatGPT Enterprise, Claude for Work, Gemini Workspace) que tienen contratos de privacidad de datos donde la información no se usa para entrenar modelos.

---

### 📊 Diagrama Mermaid — ¿Cuándo confiar y cuándo verificar?

<div class="mermaid">
flowchart TD
    A["📋 La IA te dio\nuna respuesta"] --> B{"¿Qué tipo\nde información es?"}

    B --> C["Redacción, ideas,\nestructura, tono"]
    B --> D["Dato factual: precio,\nfecha, nombre, estadística"]
    B --> E["Información local\no muy específica"]
    B --> F["Análisis de texto\nque yo le di"]

    C --> C1["✅ Riesgo bajo\nUsa con criterio\npropio de calidad"]
    D --> D1["⚠️ Riesgo medio\nVerifica con\nfuente primaria"]
    E --> E1["🔴 Riesgo alto\nVerifica siempre\nPreferir Perplexity"]
    F --> F1["✅ Riesgo bajo\nLa fuente eres tú,\nno puede inventar\nlo que no está"]

    style C1 fill:#2d6a4f,color:#fff
    style D1 fill:#f59e0b,color:#000
    style E1 fill:#ef4444,color:#fff
    style F1 fill:#2d6a4f,color:#fff
</div>

---

### 📊 Diagrama Mermaid — El ciclo de buenas prácticas

<div class="mermaid">
flowchart LR
    A["✍️ Escribes\nun buen prompt\n(Módulo 2)"] --> B["🤖 La IA\nresponde"]
    B --> C{"¿El resultado\nes factual\no creativo?"}

    C -- "Creativo\nRedacción\nIdeas" --> D["✅ Evalúa con\ntu criterio\ny refina"]
    C -- "Factual\nDatos\nFuentes" --> E["🔍 Verifica con\nfuente primaria\nantes de usar"]

    D --> F["💾 Si funcionó bien:\nguarda el prompt\nen tu biblioteca"]
    E --> F

    F --> G["🔄 Revisa\nperiódicamente\ntu contexto\ny memoria"]
    G --> A

    style F fill:#1d3557,color:#fff
    style E fill:#f59e0b,color:#000
</div>

---

## 📎 Material complementario

- 📄 [Alucinaciones en IA: por qué todas las hacen y qué hacer — ReyesIA](https://reyesia.com/blog/alucinaciones-ia) — explicación muy clara y directa, sin tecnicismos, ideal para compartir con el grupo. Publicado noviembre 2025.
- 📄 [La IA que más falla y la que es casi infalible en datos — Infobae](https://www.infobae.com/tecno/2026/03/17/cuidado-con-las-alucinaciones-la-inteligencia-artificial-que-mas-falla-al-dar-datos-y-la-que-es-casi-infalible/) — comparativa actualizada a marzo 2026 de qué modelos alucinan más y en qué contextos. Muy útil para entender en cuál confiar según el caso.
- 📄 [Cómo evitar que ChatGPT, Gemini y Meta AI respondan con errores — N5now](https://blog.n5now.com/alucinaciones-la-mayor-falla-de-la-inteligencia-artificialcomo-evitar-que-chatgpt-gemini-y-meta-ai-respondancon-errores/) — incluye consejos prácticos de verificación para usuarios no técnicos. Muy accesible.
