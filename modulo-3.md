---
layout: default
title: MÓDULO 3
---

## MÓDULO 3 — Configurar contexto: que la IA te conozca

> Volver al [inicio](./)

Hasta ahora aprendiste qué es la IA, cuál usar para qué, y cómo hablarle bien. Pero hay un problema que aparece cuando ya la usas un poco: **cada conversación empieza desde cero**. Cada vez que abres un chat nuevo, la IA no sabe del todo quién eres, qué haces, qué nivel tienes, qué no te gusta que te digan. Tienes que repetirte.

La solución para eso es configurar contexto.

> 💡 **Frase clave:** *"Una IA sin contexto es un colaborador nuevo en su primer día. Una IA con contexto es alguien que ya te conoce y sabe cómo trabajas."*

---

### Parte 1: ¿Qué es configurar contexto y por qué importa?

Configurar contexto es darle a la IA información persistente sobre ti: quién eres, cómo piensas, qué necesitas y cómo quieres que te responda. El objetivo es no tener que repetir esas cosas en cada conversación.

Hay dos niveles distintos que vamos a ver, y se usan en combinación:

- **Nivel 1 — Instrucciones globales:** aplican a *todas* las conversaciones. Definen el comportamiento base de la IA contigo.
- **Nivel 2 — Contextos especializados:** aplican solo cuando entras a un espacio específico (Gema, Proyecto, GPT). Contexto profundo para un tema concreto.

Los tres (instrucciones personalizadas, Proyectos y Gemas) hacen lo mismo esencialmente: recuerdan tus preferencias para que no tengas que repetirte. La diferencia está en el alcance y la profundidad.

---

### Parte 2: Nivel 1 — Instrucciones globales

Se configura una sola vez y aplica a todas las conversaciones nuevas. Es la forma más básica pero más poderosa de personalizar la IA porque establece el tono de toda la relación.

**¿Dónde se configura en cada IA?**

| IA | Ruta de configuración |
| --- | --- |
| **ChatGPT** | Perfil → Configuración → Personalizar ChatGPT |
| **Gemini** | Configuración del perfil de usuario |
| **Claude** | Ajustes → Preferencias de usuario |

**Ejemplo real — Instrucción global de ChatGPT:**

Este es el tipo de instrucción que yo misma tengo configurada:

```markdown
Quién soy:
- Soy desarrolladora de software en Lima, Perú. 
- Tengo experiencia intermedia-avanzada en programación.
- También gestiono proyectos propios y tengo interés en marca personal.

Cómo quiero que respondas:
- Sé crítico y directo. No valides todo lo que te digo.
- Respondeme en acento y jerga venezolana.
- Si veo que una idea tiene problemas, dímelo con argumentos.
- No empieces tus respuestas con frases aduladoras.
- Si hago una afirmación que necesita verificación, usa fuentes reales y cítamelas. No inventes datos.
- Si no sabes algo, dilo. Prefiero "no sé" a una respuesta
  inventada con confianza.
- Responde de forma concisa y directa. Sin relleno.
```

**¿Por qué esta instrucción importa?** Porque sin ella, la IA tiende a ser aduladora por defecto. Si le dices "quiero invertir en Bitcoin", sin instrucción global puede responderte con *"¡Wow, excelente decisión explorar las criptomonedas! Eres muy visionaria..."*. Con la instrucción configurada, te responde con datos, riesgos reales y fuentes verificables.

**Un punto importante:** las instrucciones base conviven con los prompts específicos. Si en tu instrucción global dijiste "responde en español" pero en un chat específico escribes "responde en inglés", la IA prioriza el prompt específico sobre la instrucción general.

---

### Parte 3: Nivel 2 — Contextos especializados: Gemas, Proyectos y GPTs

Este es el nivel donde la personalización se vuelve realmente poderosa. En lugar de un contexto genérico para todo, creas espacios con contexto profundo para cada área de tu vida o trabajo.

Los Proyectos de ChatGPT son espacios de trabajo donde puedes configurar instrucciones que aplican a todos los chats del proyecto y subir documentos de referencia de hasta 200,000 tokens (token son letras o palabras, no es una unidad de medida tan concreta). Son ideales para contextos diferenciados como "Desarrollo Web", "Content Marketing" o "Análisis de Datos". Las Gemas de Gemini son asistentes preconfigurados que creas para tareas específicas, viven en tu sidebar y se activan con un clic.

**Ejemplo real, mis gemas :p — Gemas en Gemini:**

Tengo varias Gemas, cada una con su propio contexto:

#### 🐍 Gema: Python

```markdown
Soy desarrolladora con conocimiento intermedio de Python.
Uso principalmente pandas, FastAPI y scripts de automatización.
Cuando me expliques código, siempre dime el POR QUÉ de cada decisión, no solo el cómo. Si hay varias formas de hacer algo, muéstrame la más limpia y explícame por qué las otras son peores o mejores según el contexto. No me des código sin explicación. Usa comentarios en el código.
```

#### 🥗 Gema: Recetas

```markdown
Vivo en Surquillo, Lima. Cuando me des recetas:
- Evita ingredientes que irriten la mucosa gástrica (picante, ácidos fuertes, frituras).
- Los ingredientes deben conseguirse en mercados o supermercados de Surquillo (Plaza Vea, Tottus, mercado La Hermelinda).
- Preferencia por recetas rápidas de menos de 30 minutos.
- Indica si algún ingrediente puede ser difícil de conseguir y sugiere sustituto local.
```

**¿Por qué esto es poderoso?** Porque ahora cuando abro la Gema de Recetas y escribo simplemente "quiero algo con pollo para el almuerzo", la IA ya sabe todo lo demás. No tengo que repetirlo nunca más.

---

### Parte 4: ¿Por qué esto importa?

- **🏆 Organización de eventos:** Gema/Proyecto que sabe que trabajas con eventos deportivos en Lima, que manejas cierto rango de presupuesto, que necesitas siempre un timeline y un checklist como outputs.
- **🎨 Creación de contenido:** Gema que tiene cargado el manual de marca: colores, tipografías, tono de voz, red social principal, tipo de audiencia.
- **🛍️ Emprendedimiento:** Gema de "asistente de negocio" que sabe qué vende, a qué público, en qué zonas opera, cuál es su ticket promedio.
- **🖥️ Monitora de servidores:** Proyecto con el stack tecnológico del banco, tipos de alertas frecuentes y procedimientos de respuesta. *(Con nota importante: nunca cargar datos sensibles reales, solo estructura y terminología.)*

---

### Parte 5: Ejercicio

**Paso 1:** escribe un block de notas dos cosas:

1. Tu **instrucción global** ideal: 3 a 5 puntos sobre quién eres y cómo quieres que te responda.
2. Una **idea de contexto especializado**: para qué tema lo haría y qué información incluiría.

**Paso 2:** configura las instrucciones globales en la IA de su preferencia.

---

### 📊 Diagrama Mermaid — Los 2 niveles de contexto

<div class="mermaid">
flowchart TD
    subgraph NIVEL1["🌐 NIVEL 1 — Instrucciones Globales (aplica a TODO)"]
        G1["Quién soy y qué hago"]
        G2["Cómo quiero que me respondan"]
        G3["Qué NO quiero que haga\n(adular, inventar, repetir frases)"]
        G4["Nivel de detalle y formato preferido"]
    end

    subgraph NIVEL2["🎯 NIVEL 2 — Contextos Especializados (por tema)"]
        direction LR
        C1["🐍 Gema Python\nStack, librerías,\npedir el 'por qué'"]
        C2["🥗 Gema Recetas\nGastritis, zona Lima,\ningredientes locales"]
        C3["🏷️ Gema Marca\nPersonal\nTono, audiencia,\nobjetivos"]
        C4["🎯 Tu Gema\nPersonalizada\n..."]
    end

    NIVEL1 --> NIVEL2

    style NIVEL1 fill:#1d3557,color:#fff
    style NIVEL2 fill:#2d6a4f,color:#fff
</div>

---

### 📊 Diagrama Mermaid — Cómo diseñar tu instrucción global

Este diagrama sirve como guía para el ejercicio. Puedes seguirlo para construir tu propia instrucción:

<div class="mermaid">
flowchart LR
    A["✍️ Tu instrucción\nglobal ideal"] --> B["👤 QUIÉN SOY\n¿Cuál es tu trabajo?\n¿En qué ciudad?\n¿Qué nivel tienes?"]
    A --> C["🎯 QUÉ HAGO\n¿Para qué usas\nla IA principalmente?"]
    A --> D["🗣️ CÓMO RESPONDER\n¿Qué tono quieres?\n¿Qué formato?\n¿Qué longitud?"]
    A --> E["🚫 QUÉ EVITAR\n¿Qué frases te molestan?\n¿Qué comportamientos\nno quieres?"]
    A --> F["✅ QUÉ PRIORIZAR\n¿Precisión? ¿Velocidad?\n¿Fuentes verificables?\n¿Ejemplos concretos?"]

    B & C & D & E & F --> G["🤖 IA que responde\ncomo tú necesitas\ndesde el primer mensaje"]

    style G fill:#2d6a4f,color:#fff
    style A fill:#1d3557,color:#fff
</div>

---

### 📊 Diagrama Mermaid — Diseñar una Gema/Proyecto especializado

Para mostrar qué información debe tener un contexto especializado bien construido:

<div class="mermaid">
mindmap
  root((Tu Gema o\nProyecto ideal))
    Contexto de quién eres
      Tu rol específico
      Tu nivel en ese tema
      Tu situación particular
    El objetivo del espacio
      Para qué lo usas
      Qué tipo de tareas le pides
      Qué outputs necesitas siempre
    Restricciones específicas
      Qué no puede sugerir
      Limitaciones de recursos
      Consideraciones locales
    Formato esperado
      Cómo quieres las respuestas
      Si debe usar tablas o listas
      Qué tan larga debe ser la respuesta
    Información de referencia
      Datos que debe saber siempre
      Vocabulario o jerga del área
      Referencias o estándares que usas
</div>

---

## 📎 Material complementario

- 📄 [Custom Instructions: Configura ChatGPT, Claude y Gemini a tu manera — FindSkill.ai](https://findskill.ai/es/blog/custom-instructions-configura-chatgpt-claude-y-gemini-a-tu-manera/) — cubre las tres IAs en un solo artículo con ejemplos por perfil profesional. Actualizado a enero 2026.
- 📄 [Cómo personalizar ChatGPT a tu estilo 2026 — DonWeb](https://blog.donweb.com/como-personalizar-chatgpt-personaliza-chatgpt/) — guía muy detallada sobre las nuevas funciones de personalización incluyendo los controles deslizantes de características. Actualizado a marzo 2026.
- 📄 [Instrucciones personalizadas de ChatGPT: guía práctica con ejemplos reales — fvivas.com](https://fvivas.com/es/instrucciones-personalizadas-de-chatgpt/) — incluye plantillas listas para copiar y cómo adaptarlas a Claude y Gemini.
- 📄 [Cómo importar tu memoria de ChatGPT y Gemini a Claude — Hipertextual](https://hipertextual.com/guias/importar-chats-memoria-datos-gemini-chatgpt-claude/) — guía paso a paso para migrar contexto entre plataformas. Publicado el 14 de marzo 2026.

---

## MÓDULO 3B — Skills: el siguiente nivel después del contexto

> 💡 El futuro de los chats con contexto personalizado

**¿Qué son los Skills?**
Un Skill es un paquete completo que puede incluir instrucciones detalladas en formato Markdown, archivos de referencia como guías de marca, fórmulas o plantillas, y scripts que Claude puede ejecutar directamente. Todo empaquetado para que Claude lo lea automáticamente cuando detecta que es relevante para lo que le estás pidiendo.

En palabras simples: si las Gemas o los Proyectos son "conversaciones con memoria", los Skills son "manuales de trabajo permanentes con lógica incluida". Son más poderosos porque no solo guardan instrucciones de texto, sino también flujos de trabajo, plantillas y archivos de referencia.

**¿En qué se diferencia un Skill de una Gema o un Proyecto?**
La diferencia clave es la autonomía y la portabilidad. No le dices "usa mi Skill de marca". Le dices "maquétame esto" y Claude ya sabe cómo hacerlo porque detectó que el Skill aplica. Claude escanea todos los Skills disponibles, identifica cuál aplica, y lo carga solo, sin que tú hagas nada. Además son portables: un Skill creado para Claude.ai funciona igual en Claude Code y en la API; lo construyes una vez y lo usas en todas partes.

**Comparativa rápida con otras IAs:**
Los Skills de Claude permiten instrucciones de múltiples páginas, código embebido, plantillas y árboles de decisión. Las Gemas de Gemini tienen un límite de alrededor de 4.000 caracteres, suficiente para personalización básica pero no para flujos complejos. Los GPTs de ChatGPT ofrecen alrededor de 8.000 caracteres más la capacidad de subir archivos y conectar APIs externas. Claude Skills gana en profundidad de instrucciones; ChatGPT GPTs gana en conexiones a APIs externas.

**Tipos de Skills:**
Anthropic proporciona Skills integradas disponibles para todos los usuarios, incluyendo creación y manipulación avanzada de archivos Excel. Además de las nativas, puedes crear las tuyas propias o usar las de la comunidad.

**¿Cómo se crea un Skill?**
Hay dos caminos: escribir los archivos tú mismo para tener control total, o crearlos conversando con Claude. Describes tu proceso de forma natural y Claude se encarga del formato y la estructura, lo que hace que Skills sea accesible para cualquier persona independientemente de su trasfondo técnico.

**Ejemplos de Skills útiles por perfil:**

- *Creadora de contenido:* Skill con el manual de identidad visual de la marca, colores, tipografías y tono. Claude lo aplica automáticamente cada vez que le pides crear algo.
- *Emprendedora:* Skill con el catálogo de productos, precios y descripción del público objetivo. Genera descripciones, posts y respuestas a clientes siempre alineados.
- *Organizadora de eventos:* Skill con checklist estándar de eventos, proveedores frecuentes y estructura de timelines. Cada nuevo evento parte desde esa base.
- *Monitora de servidores:* Skill con el stack tecnológico, tipos de alertas comunes y procedimientos de respuesta a incidentes del equipo.

**Ejercicio:** describe en palabras simples un flujo de trabajo repetitivo de tu trabajo. Usa esa descripción para pedirle a Claude que cree un Skill para ti.

**Material complementario:**

- 📄 [Documentación oficial de Skills en Claude — Anthropic](https://support.claude.com/es/articles/12512180-usar-skills-en-claude)
- 📄 [Cómo crear un Skill conversando con Claude — Anthropic](https://support.claude.com/es/articles/12599426-como-crear-una-habilidad-con-claude-a-traves-de-la-conversacion)
- 📄 [Guía definitiva de Claude Skills en español — Vilma Núñez](https://vilmanunez.substack.com/p/skills-de-claude-la-guia-definitiva)
- 📄 [Tutorial práctico con prueba real de Skills — Hostinger](https://www.hostinger.com/es/tutoriales/skills-de-claude)