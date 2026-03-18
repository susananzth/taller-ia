---
layout: default
title: MÓDULO 0
---

## MÓDULO 0 — Introducción y contexto

> Volver al [inicio](./)

Antes de arrancar con herramientas y demos, necesitamos pararnos un momento en lo básico: **¿qué es realmente esto que todo el mundo llama IA?** Porque hay mucho ruido, mucho hype, y también mucho miedo innecesario. Y la mejor forma de usarla bien es entender, aunque sea a grandes rasgos, qué hay debajo.

### Parte 1: ¿Qué es la IA y qué no es?

La inteligencia artificial que usamos hoy en los chats, ChatGPT, Gemini, Claude, no es una mente. No piensa, no entiende, no tiene opiniones propias, no siente. Lo que hace es **predecir**. Fue entrenada con cantidades enormes de texto de internet, libros, artículos, foros, código, y aprendió a reconocer patrones: dada esta secuencia de palabras, ¿cuál es la siguiente más probable?

Imagínalo así: es como un estudiante que leyó toda la biblioteca del mundo, pero nunca vivió nada. Sabe *describir* cómo se siente perder a alguien, pero nunca perdió a nadie. Sabe *explicar* cómo se organiza un evento, pero nunca organizó uno. Por eso puede ser brillante y equivocarse al mismo tiempo.

**Tres cosas que la IA no es:**

- ❌ No es infalible. Puede inventar datos, citar fuentes que no existen, equivocarse en cálculos.
- ❌ No es omnisciente. Tiene una fecha de corte de conocimiento y no sabe lo que pasó después (salvo las que tienen acceso a internet en tiempo real).
- ❌ No es neutral. Refleja los sesgos del texto con el que fue entrenada.

**Y lo que sí es:**

- ✅ Un colaborador muy rápido que nunca se cansa.
- ✅ Una herramienta que mejora drásticamente con instrucciones precisas.
- ✅ Un amplificador: hace más grande lo que tú ya sabes hacer.

> 💡 **Frase clave para que recuerden:** *"La IA no reemplaza tu criterio. Lo amplifica. Pero para amplificarlo necesita que tú lo tengas primero."*

---

### Parte 2: ¿Por qué hay tantas y en qué se diferencian?

**Lo que puedes decirles:**

No existe una sola IA porque no existe una sola empresa ni una sola filosofía de cómo construirla. Cada una viene de un lugar distinto y eso se nota en cómo responde, en qué es buena y en qué falla.

Aquí van las que vamos a ver hoy y quiénes están detrás:

| Herramienta | Quién la hace | Su origen / filosofía |
| --- | --- | --- |
| **ChatGPT** | OpenAI | Surgió para ser lo más versátil posible. La primera en masificarse. |
| **Gemini** | Google | Nació integrada al ecosistema Google. Su ventaja es que ya conoce tus Docs, Gmail, Drive. |
| **Claude** | Anthropic | Creada por ex-investigadores de OpenAI con foco en seguridad y respuestas cuidadosas. Muy buena con textos largos. |
| **Perplexity** | Perplexity AI | No es un modelo propio, sino un buscador potenciado con IA. Su diferencial: siempre cita fuentes verificables. |
| **NotebookLM** | Google | No es un chat general. Es una herramienta para analizar *tus* documentos. Solo sabe lo que tú le das. |

**La pregunta que siempre va a aparecer es:** *"¿Cuál es la mejor?"* Y la respuesta honesta es: **depende de para qué**. Durante el workshop vamos a ver exactamente eso. Hoy al terminar, cada una va a saber cuál le conviene para su trabajo.

---

### Parte 3: Ejercicio de apertura

**Instrucciones para el grupo:**

> Tomen una hoja o abran el bloc de notas de su celular. Escriban de 3 a 5 tareas concretas de su trabajo que les quitan tiempo, que hacen de forma repetitiva, o que les cuestan porque no saben bien cómo empezar. No importa si saben o no cómo la IA las podría ayudar. Solo lístelas.

Guarden esa lista. Al final del workshop van a volver a ella y va a ser notorio cuántas de esas tareas la IA puede atacar directamente.

---

### 📊 Diagrama Mermaid — Mapa mental de las IAs

Este diagrama sirve para la diapositiva 4 o como material impreso/proyectado durante la explicación:

<div class="mermaid">
mindmap
  root((IAs que vamos a ver))
    ChatGPT
      OpenAI
      Versatilidad general
      Imágenes con DALL·E
      Canvas para documentos
    Gemini
      Google
      Integrado con Workspace
      Gemas personalizadas
      Deep Research
    Claude
      Anthropic
      Textos y docs largos
      Proyectos y Artefactos
      Skills automatizados
    Perplexity
      Perplexity AI
      Búsqueda con fuentes
      Tiempo real verificable
      Deep Search
    NotebookLM
      Google
      Solo tus documentos
      Audio Overview podcast
      Citas exactas por fuente
</div>

---

### 📊 Diagrama Mermaid — Cómo funciona una IA de lenguaje

Este diagrama es útil para ilustrar la explicación de "qué es la IA" sin tecnicismos:

<div class="mermaid">
flowchart LR
    A["🧑 Tú escribes\nun mensaje"] --> B["📥 El modelo\nrecibe el texto"]
    B --> C["🔍 Analiza patrones\nde millones de textos\ncon los que fue entrenado"]
    C --> D["🎲 Predice cuál es\nla respuesta más probable\npalabra por palabra"]
    D --> E["💬 Te devuelve\nuna respuesta"]
    E --> F{"¿Es correcta?"}
    F -- "Generalmente sí,\npero no siempre" --> G["✅ Úsala,\nverifica lo importante"]
    F -- "A veces inventa\n(alucinaciones)" --> H["⚠️ Revisa,\ncorrige, vuelve a pedir"]
</div>

---

### 📎 Material complementario del módulo

- 🎥 **Ver antes del workshop** — *Cómo funcionan los LLMs (6 min)*: [https://www.youtube.com/watch?v=LPZh9BOjkQs](https://www.youtube.com/watch?v=LPZh9BOjkQs) — introducción ligera a predicción de palabras, preentrenamiento y transformadores. No necesitan entender todo, solo la idea general.
- 🎥 **Para profundizar después** — Curso IA gratuito de 3 videos, canal *Inteligencia Artificial*: [ver playlist](https://www.youtube.com/watch?v=BF4fQlUDC7s&list=PL9WNEV0osabbUN0QLHhNloGs06LlSkNNs) *(el primer video de esta playlist puede servir como complemento directo de este módulo)*
