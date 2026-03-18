---
layout: default
title: MÓDULO 6
---

## MÓDULO 7 — Cierre y plan de acción

> Volver al [inicio](./)

Llegaste al final. Y el final de un workshop no es cuando termina la explicación, es cuando decides qué vas a hacer diferente mañana. Porque la IA no cambia nada si se queda en el taller. Cambia cuando la usas en tu trabajo real, esta semana.

> 💡 **Frase de cierre:** *"No necesitas dominarla toda. Necesitas empezar con una tarea, con una herramienta, esta semana."*

---

### Parte 1: Revisión del ejercicio inicial

¿Recuerdan la lista que escribiste al inicio del workshop? La de tareas que te quitan tiempo o te cuesta arrancar. Sáquela.

- ¿Cuántas de esas tareas podrías ahora atacar con alguna de las herramientas que vimos?
- ¿Qué agregarías a la lista que al inicio no se te había ocurrido?
- ¿Qué cambió en cómo ves la IA entre el momento en que llegaste y ahora?

No hay respuesta correcta. El objetivo es que notes tu propio avance en el taller.

---

### Parte 2: El plan de acción

Escribe en papel o en tu celular tres compromisos concretos. No metas, compromisos. Con fecha.

**Las tres preguntas:**

**1. ¿Qué IA voy a usar esta semana?**
Una sola. No todas. La que más conectó con tu caso de uso real.

**2. ¿Qué configuración de contexto voy a hacer?**
Una instrucción global, una Gema, un Proyecto o un Skill. Algo que la IA "aprenda" sobre mi o mi trabajo esta semana.

**3. ¿Para qué tarea concreta la voy a usar?**
No *"voy a usar más la IA"*. Sino *"el martes voy a usar Perplexity para buscar tres proveedores de sonido para el evento de mayo"* o *"esta noche voy a crear la Gema de catálogo en Gemini"*.

---

**Compromisos sugeridos por perfil como guía si se bloquean:**

| Perfil | IA a arrancar | Configuración | Primera tarea concreta |
| --- | --- | --- | --- |
| 🏆 Organizadora de eventos | Perplexity | Gema de eventos en Gemini | Investigar proveedores para el próximo evento con fuentes |
| 🎨 Creadora de contenido | ChatGPT | Skill de identidad de marca en Claude | Generar 3 captions para el próximo post de evento |
| 🛍️ Emprendedora de catálogo | Gemini | Gema de asistente de catálogo | Escribir los mensajes de seguimiento para esta campaña |
| 🖥️ Monitora de servidores | Claude | Proyecto con documentación técnica | Analizar el próximo log de error antes de escalar |
| 💻 Tú (facilitadora) | — | Auditar y actualizar tus Gemas actuales | Crear el Skill para el próximo proyecto de desarrollo |

---

### 📊 Diagrama Mermaid — Tu hoja de ruta post-workshop

<div class="mermaid">
flowchart TD
    A["🎓 Saliste\ndel workshop"] --> B["Esta semana\n¿Qué hago primero?"]

    B --> C["1️⃣ Elige UNA IA\ncon la que arrancar"]
    C --> D["2️⃣ Configura\ntu contexto:\nInstrucción global\no Gema / Proyecto"]
    D --> E["3️⃣ Úsala en\nUNA tarea real\nde tu trabajo"]
    E --> F{"¿Funcionó\ncomo esperabas?"}

    F -- "Sí ✅" --> G["Guarda el prompt\nque funcionó\nen tu biblioteca"]
    F -- "Parcialmente 🟡" --> H["Itera: refina\nel prompt\ny vuelve a intentar"]
    F -- "No ❌" --> I["Revisa el módulo\nde prompts\ny reformula"]

    G --> J["Próxima semana:\nagregar una\nherramienta más"]
    H --> E
    I --> E

    J --> K["En un mes:\ntienes flujos\nde trabajo reales\ncon IA integrada"]

    style A fill:#1d3557,color:#fff
    style K fill:#2d6a4f,color:#fff
    style F fill:#f59e0b,color:#000
</div>
