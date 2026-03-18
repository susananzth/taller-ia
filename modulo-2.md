---
layout: default
title: MÓDULO 2
---

## MÓDULO 2 — El arte del prompt: cómo hablarle a una IA

> Volver al [inicio](./)

Ya sabemos qué es la IA y cuál usar para qué. Ahora viene la habilidad que más diferencia a quien saca resultados reales de quien se frustra y abandona: **saber pedirle las cosas**. A eso se le llama prompt engineering, que en términos simples significa escribir instrucciones bien construidas.

No necesitas saber programar. No hay fórmula mágica. Pero sí hay una estructura que funciona, y en cuanto la incorporas, dejas de recibir respuestas genéricas y empiezas a recibir lo que realmente necesitas.

> 💡 **Frase clave:** *"La IA es tan buena como la instrucción que recibe. Tú eres la directora. Ella es la productora."*

---

### Parte 1: ¿Qué es un prompt?

Un prompt es todo lo que le escribes a la IA para que haga algo. Puede ser una pregunta, una instrucción, un contexto o una combinación de todo eso. Un prompt mal diseñado genera respuestas vagas o incorrectas. Un prompt bien diseñado obtiene exactamente lo que necesitas.

La diferencia más clara posible:

| ❌ Prompt vago | ✅ Prompt bien construido |
| --- | --- |
| "Dame ideas para mi evento" | "Actúa como organizadora de eventos deportivos. Necesito 10 ideas de activaciones para un torneo de fútbol amateur de 300 personas en Lima. Público mixto de 25-45 años. Dame las ideas en una tabla con nombre de la actividad, descripción breve y costo estimado." |
| "Hazme un post" | "Eres una creadora de contenido para Instagram de eventos deportivos. Escribe 3 opciones de caption para una foto de premiación de atletas. Tono emotivo pero energético, máximo 150 caracteres, con hashtags al final." |
| "Cómo vendo más" | "Soy emprendedora y vendo accesorios de moda en una tienda física en Lima. Mi cliente típica es mujer de 25-40 años. Dame 5 estrategias concretas para aumentar el ticket promedio por visita, con ejemplos prácticos de cómo implementarlas esta semana." |

---

### Parte 2: Las 6 partes de un prompt bien construido

No todas son obligatorias en todos los casos, pero conocerlas te da el control total sobre el resultado. La estructura lógica es: Rol + Contexto + Tarea + Restricciones. Aquí la expandimos en 6 componentes para tener más matices:

---

**1. 🎭 Rol / Persona**
Le dices a la IA *desde qué posición* debe responderte. Esto cambia radicalmente el tono, el vocabulario y el nivel de detalle.

> *"Actúa como un experto en logística de eventos deportivos..."*
> *"Eres un consultor financiero con experiencia en pequeños negocios..."*
> *"Actúa como un ingeniero DevOps senior con experiencia en banca..."*

Asignar un rol específico activa patrones de lenguaje, estructura y tono apropiados para ese nicho. La IA adapta automáticamente el vocabulario y los ejemplos según la expertise que le asignas.

---

**2. 🗂️ Contexto**
Le das la información de fondo que necesita para no inventar suposiciones. Quién eres tú, cuál es la situación, qué ya existe o ya se sabe.

> *"Estoy organizando un evento para 300 personas en Lima, presupuesto de 5,000 soles..."*
> *"Tengo una tienda física de accesorios, llevo 2 años en el negocio, no tengo presencia digital aún..."*
> *"Este es el mensaje de error que me apareció en el servidor a las 3am: [pegar el error]..."*

---

**3. 🎯 Tarea específica**
La instrucción concreta de lo que necesitas. Verbo + objeto + alcance.

> *"Dame una lista de 10 proveedores..."*
> *"Redacta 3 versiones del mismo caption..."*
> *"Explica qué significa este error y cuáles son las 3 causas más probables..."*

---

**4. 📋 Formato de salida**
Cómo quieres que te entregue la respuesta. Esto es muy subestimado y marca enorme diferencia en la utilidad del resultado.

> *"En una tabla con columnas: nombre / descripción / costo"*
> *"En pasos numerados, máximo 10"*
> *"Como un correo formal listo para enviar"*
> *"En bullet points cortos, sin introducción ni cierre"*
> *"Con código comentado línea por línea"*

---

**5. 🚧 Restricciones**
Lo que **no** quieres, los límites, el tono, el nivel de complejidad.

> *"No uses jerga técnica, el lector no tiene experiencia en tecnología"*
> *"Máximo 200 palabras"*
> *"No incluyas opciones que requieran presupuesto mayor a 1,000 soles"*
> *"Evita recomendaciones genéricas, quiero cosas que se puedan hacer esta semana"*

---

**6. 💡 Ejemplos (el más poderoso y el más ignorado)**
Mostrarle un ejemplo del tipo de resultado que buscas es la forma más rápida de calibrarla. Un buen prompt es como una buena pregunta: entre más claro, preciso y humano seas, mejor será la respuesta.

> *"Algo parecido a esto: [pegar ejemplo de un post que te gustó]"*
> *"El tono que busco es como el de esta descripción: [ejemplo]"*
> *"Quiero una tabla así: Nombre | Costo | Tiempo | Observaciones"*

---

### Parte 3: Tipos de prompt según el objetivo

Dependiendo de lo que necesitas, el tipo de prompt cambia. No es lo mismo pedirle que cree algo desde cero que pedirle que analice algo que ya existe.

GENERACIÓN: Crear algo nuevo desde cero.

```markdown
"Escríbeme un plan de evento para..."
```

TRANSFORMACIÓN: Cambiar algo que ya existe.

```markdown
"Reescribe este correo en tono más formal..."
"Traduce este texto y adapta los ejemplos a Perú..."
"Resume este documento en 5 puntos clave..."
```

ANÁLISIS: Evaluar, comparar, encontrar problemas.

```markdown
"Revisa este contrato y dime qué cláusulas son riesgosas..."
"Compara estas dos propuestas y dame un cuadro comparativo..."
"Analiza este log de error y dime qué está fallando..."
```

EXTRACCIÓN: Sacar datos de un texto que ya tienes.

```markdown
"De esta lista de reseñas, extrae las 3 quejas más repetidas..."
"De este PDF, dame todos los plazos y fechas importantes..."
```

SIMULACIÓN: Juego de roles, escenarios hipotéticos.

```markdown
"Actúa como un cliente difícil y hazme las 5 objeciones más comunes..."
"Simula que eres el área de sistemas y evalúa esta propuesta..."
```

ITERACIÓN: Refinar la respuesta anterior.

```markdown
"Bien, ahora hazla más corta y cambia el tono a informal..."
"Toma la opción 2 y desarróllala más con ejemplos concretos..."
```

---

### Parte 4: El truco más poderoso — pedirle a la IA que mejore tu propio prompt

Puedes pedirle a la IA que te ayude a escribir mejores preguntas para la IA. Concretamente:

> *"Estoy aprendiendo a escribir mejores prompts. Analiza este prompt que te voy a dar y dime cómo mejorarlo para obtener mejores resultados: [tu prompt]"*

También puedes decirle directamente:

> *"Antes de responderme, necesito que me hagas las preguntas que te faltan para poder darme la mejor respuesta posible."*

Esto la convierte en colaboradora activa del proceso, no solo ejecutora de instrucciones.

---

### Parte 5: Ejercicio práctico

**Paso 1:** escribe un "prompt malo": lo primero que se te ocurra para una tarea real de tu trabajo. Sin pensar mucho.

**Paso 2:** reconstruye el prompt usando la estructura de 6 partes.

**Paso 3:** abre dos chats y envía un prompt a cada una. compara los dos resultados.

---

**Prompts malos → reconstruidos, por perfil:**

#### 🏆 Organizadora de eventos deportivos

*Malo:* `dame ideas para mi evento`

*Bueno:*

```markdown
Actúa como una especialista en producción de eventos deportivos.
Estoy organizando un torneo de fútbol amateur en Lima para 300
participantes, presupuesto total de 8,000 soles, al aire libre,
público mixto de 20-45 años. Necesito 8 ideas de activaciones
y entretenimiento para los momentos entre partidos. Preséntalas
en una tabla con: nombre de la actividad | descripción en 2 líneas
| costo estimado | dificultad de implementación (baja/media/alta).
No incluyas actividades que requieran instalaciones especiales.
```

---

#### 🎨 Creadora de contenido visual

*Malo:* `hazme un post`

*Bueno:*

```markdown
Eres una estratega de contenido para redes sociales de marcas
deportivas. Crea 3 opciones de caption para Instagram para
acompañar una foto de premiación de un torneo de atletismo.
El tono debe ser emotivo y energético, orientado a jóvenes
deportistas de 18-30 años. Cada opción: máximo 120 caracteres
en el cuerpo del texto + 5 hashtags relevantes al final.
Las 3 opciones deben tener tonos distintos: uno inspiracional,
uno celebratorio y uno orientado a comunidad.
```

---

#### 🛍️ Emprendedora

*Malo:* `cómo vendo más`

*Bueno:*

```markdown
Soy dueña de una tienda física de accesorios de moda en Lima
(Miraflores). Mi clienta típica es mujer de 25-40 años que
compra 1 vez al mes, ticket promedio de 80 soles. Quiero
aumentar ese ticket promedio a 120 soles sin bajar precios.
Dame 5 estrategias concretas de venta en tienda física que
pueda implementar esta semana, sin inversión mayor a 200 soles.
Para cada estrategia: qué hacer | cómo implementarlo | por qué
funciona. Sin teoría, solo acciones concretas.
```

---

#### 🖥️ Monitora de servidores

*Malo:* `explícame este error`

*Bueno:*

```markdown
Actúa como un ingeniero DevOps senior con experiencia en
infraestructura bancaria. Este es un mensaje de error que
apareció en nuestros logs a las 3:17am:
[PEGAR AQUÍ EL ERROR EXACTO]
Necesito que me expliques:
1. Qué significa este error en términos simples
2. Las 3 causas más probables ordenadas de más a menos común
3. Qué información adicional debo revisar para confirmar la causa
4. Los pasos de diagnóstico recomendados
Responde en formato numerado. No asumas acceso a sistemas
específicos, solo dame el razonamiento técnico.
```

---

### 📊 Diagrama Mermaid — Las 6 partes de un prompt

<div class="mermaid">
flowchart TD
    A["✍️ Tu prompt"] --> B["🎭 ROL\n¿Desde qué posición\ndebe responderte?"]
    A --> C["🗂️ CONTEXTO\n¿Qué información\nde fondo necesita?"]
    A --> D["🎯 TAREA\n¿Qué exactamente\ndebe hacer?"]
    A --> E["📋 FORMATO\n¿Cómo quieres\nla respuesta?"]
    A --> F["🚧 RESTRICCIONES\n¿Qué NO quieres\no qué límites hay?"]
    A --> G["💡 EJEMPLOS\n¿Hay algún modelo\nque puedas mostrar?"]

    B & C & D & E & F & G --> H["💬 Respuesta precisa\ny útil"]

    style H fill:#2d6a4f,color:#fff
    style A fill:#1d3557,color:#fff
</div>

---

### 📊 Diagrama Mermaid — El ciclo de iteración del prompt

Este diagrama es clave para que entiendan que el proceso es una conversación, no un disparo único:

<div class="mermaid">
flowchart LR
    A["💭 Tienes\nuna necesidad"] --> B["✍️ Escribes\nun primer prompt"]
    B --> C["🤖 La IA\nresponde"]
    C --> D{"¿Es lo\nque necesitabas?"}
    D -- "Sí ✅" --> E["🎯 Usas\nel resultado"]
    D -- "Parcialmente 🟡" --> F["Refinás:\n'Ahora hacé X\nmás corto/específico...'"]
    D -- "No ❌" --> G["Reescribís\nagregando más\ncontexto o ejemplos"]
    F --> C
    G --> B
    E --> H["💾 Guardás el prompt\nen tu biblioteca personal"]

    style E fill:#2d6a4f,color:#fff
    style H fill:#1d3557,color:#fff
</div>

---

### 📎 Material complementario

- 📄 [Prompt Engineering Avanzado 2026 — Javadex](https://www.javadex.es/blog/prompt-engineering-avanzado-tecnicas-pro-guia-2026) — artículo muy completo con técnicas por modelo (Claude, ChatGPT, Gemini). Recomendado especialmente para la monitora de servidores y para ti como facilitadora.
- 📄 [Hub completo de Prompt Engineering — Aprender21](https://www.aprender21.com/blog/hub-prompt-engineering) — guía actualizada a marzo 2026, con técnicas básicas y avanzadas en español.
- 📄 [Guía de Prompt Engineering para Principiantes — Coderhouse](https://www.coderhouse.com/us/coderlibrary/guia-prompt-engineering-principiantes) — la más accesible del grupo, ideal para compartirla con las participantes que quieran repasar los conceptos por su cuenta.
