---
layout: mermaid
title: MÓDULO 5
---

## MÓDULO 5 — Casos de uso por perfil

> Volver al [inicio](index.md)

Llegamos al módulo más personal del workshop. Hasta acá aprendimos herramientas, estructuras y conceptos. Ahora el ejercicio es conectar todo eso con **tu trabajo real, hoy**.

No hay respuesta correcta ni incorrecta. El objetivo es que salgas con al menos **una tarea real de tu trabajo que puedas delegar o acelerar con IA esta semana**.

> 💡 **Regla del módulo:** Todo lo que hagamos aquí parte de situaciones reales. Nada hipotético.

---

### 👤 Perfil 1 — Organizadora de eventos deportivos

**Contexto del perfil:**
La organización de un evento deportivo implica coordinar múltiples variables: ubicación, horarios, participantes y recursos. La IA facilita esta tarea mediante análisis de datos para ofrecer soluciones óptimas, desde la gestión de inscripciones hasta la asignación de recursos, la predicción de afluencia y la optimización de calendarios. Todo eso que antes tomaba horas de planillas y coordinaciones manuales hoy se puede acelerar con las herramientas que ya conocemos.

---

#### 🔵 Tarea 1 — Crear un timeline de evento desde cero

**Herramienta:** Claude (Artefacto) o ChatGPT (Canvas)
**Por qué:** Ambas permiten trabajar el documento de forma iterativa sin perder el hilo. Claude genera el artefacto en un panel lateral que puedes editar sección por sección; Canvas de ChatGPT permite seleccionar partes específicas del timeline y mejorarlas sin tocar el resto.

**Prompt de arranque para hacer en vivo:**

```markdown
Actúa como una coordinadora de producción de eventos deportivos
con 10 años de experiencia. Voy a organizar [tipo de evento]
para [número de personas] en Lima, Perú. La fecha tentativa
es [fecha] y el presupuesto aproximado es [monto en soles].
Crea un timeline completo de producción con todas las tareas
organizadas desde hoy hasta el día del evento. Incluye:
semanas previas, días previos, día del evento y post-evento.
Formato: tabla con columnas → Fecha / Tarea / Responsable
/ Estado (pendiente por defecto) / Observaciones.
```

**Iteración sugerida después de la primera respuesta:**
> *"Toma la sección de 'semana del evento' y desglósala por días con horarios específicos de 8am a 8pm."*

---

#### 🟣 Tarea 2 — Investigar proveedores y precios actuales

**Herramienta:** Perplexity (búsqueda en tiempo real + fuentes verificables)
**Por qué:** Los precios de proveedores cambian. Perplexity busca en tiempo real y cita las fuentes, lo que hace la información verificable y actualizada. Mucho mejor que confiar en lo que un modelo entrenado en datos viejos "recuerda" sobre precios.

**Prompt de arranque:**

```markdown
Busca en Lima, Perú los principales proveedores de [sonido
profesional / carpas / tarimas / seguridad / catering deportivo]
para eventos de entre 200 y 500 personas. Para cada proveedor:
nombre, rango de precios aproximado, página web si existe,
y reseñas o reputación si encuentras referencias. Prioriza
fuentes de 2025-2026.
```

---

#### 🔵 Tarea 3 — Informe de tendencias con Deep Research

**Herramienta:** Gemini Deep Research
**Por qué:** Para propuestas a clientes o sponsors, un informe de tendencias con fuentes da credibilidad. En 2026 se espera que los organizadores de eventos aumenten la inversión en análisis de datos y herramientas de IA para recopilar información sobre el comportamiento de los asistentes y mejorar la toma de decisiones. Gemini Deep Research puede generar ese informe en 5-10 minutos con más de 100 fuentes.

**Prompt:**

```markdown
Investiga las tendencias más relevantes en organización de
eventos deportivos en Latinoamérica para 2026. Incluye:
tecnología usada, experiencia del asistente, sostenibilidad,
marketing digital y nuevas fuentes de ingreso para organizadores.
Genera el informe con fuentes citadas y un resumen ejecutivo
de máximo una página al inicio.
```

---

#### ⚡ Bonus — Gema o Skill especializado

Diseñar en vivo la instrucción para una Gema de "asistente de eventos deportivos" que ya sepa: ciudad de operación, tipo de eventos que organiza, rango de presupuesto típico, y que siempre devuelva checklist y timelines como formato de salida por defecto.

---

### 👤 Perfil 2 — Creadora de contenido visual

**Contexto del perfil:**
La capacidad de generar y ajustar creatividades en tiempo real con IA transforma el flujo de producción de contenido visual. Equipos que antes tardaban días en producir materiales visuales ahora lo hacen en horas. Casi el 90% de todo el contenido online podría ser generado o asistido por IA en 2026, y las marcas que dominan esta habilidad tienen una ventaja competitiva clara en velocidad y consistencia.

---

#### 🟢 Tarea 1 — Edición y composición de imágenes con IA para contenido deportivo

**Herramientas:** ChatGPT (edición con DALL·E) + Canva (Magic Edit + Quitafondos)
**Por qué:** La IA permite crear y editar contenido visual deportivo sin ser diseñadora ni fotógrafa profesional. Desde generar fondos para una meta hasta cambiar el contexto de una foto real de corredores, el flujo es más rápido que el proceso tradicional. Eso sí, hay que conocer qué hace bien la IA hoy y qué todavía tiene limitaciones.

##### ⚠️ Lo que hay que saber antes de empezar

Insertar caras reales específicas en una escena nueva con fidelidad fotográfica **no es algo que las IAs públicas hagan bien hoy**. Es una restricción deliberada por temas de privacidad y deepfakes. Lo que sí funciona muy bien es: generar el fondo por separado y cambiar el fondo de una foto real manteniendo a las personas intactas. El flujo más efectivo combina ambas herramientas.

##### Flujo de trabajo completo: corredores llegando a la meta

Tienes dos fotos: los corredores de tu evento y la locación real de la meta. El objetivo es una composición que parezca que están llegando a esa meta.

##### Paso 1 — Generar el fondo de la meta con ChatGPT o Gemini

Primero creas el fondo solo, sin personas, para tener control total sobre cómo se ve:

```markdown
Fotografía deportiva de alta calidad de la línea de meta
de una carrera de running urbana en Lima, vista desde atrás
mirando hacia los corredores que llegan. Cinta roja de meta
en primer plano, público animando a ambos lados, avenida
arbolada al fondo. Hora dorada, luz cálida y dramática,
colores naranja y azul marino. El centro de la imagen
debe estar despejado para insertar personas después.
Estilo foto editorial deportiva profesional. Formato 4:5.
```

**Iteración si el primer resultado no convence:**
> *"Mantén el fondo pero hazlo más oscuro y dramático, con más contraste. Que el público de los costados sea más numeroso y el cielo tenga nubes naranjas de atardecer."*

##### Paso 2 — Cambiar el fondo de la foto real de los corredores en ChatGPT

Sube la foto real de tus corredores directamente a ChatGPT y escribe:

```markdown
Esta foto tiene corredores en [fondo actual, ej: una pista
de entrenamiento]. Necesito que cambies el fondo por una
meta de carrera deportiva con cinta roja, público animando
a los costados y cielo de atardecer con luz dorada.
Mantén a las personas exactamente como están, sin cambiar
sus caras, ropa ni posiciones. La iluminación del fondo
nuevo debe ser consistente con la luz que ya tienen
las personas en la foto.
```

##### Paso 3 — Flujo alternativo en Canva si ChatGPT no da el resultado esperado

Canva da más control manual sobre la composición:

1. Subir la foto de los corredores a Canva.
2. Usar **Quitafondos** (Editar foto → Quitafondos) para aislar a las personas.
3. Agregar el fondo generado en el Paso 1 como imagen de fondo del lienzo.
4. Colocar a los corredores sobre ese fondo y ajustar escala y posición.
5. Usar **Magic Edit** para suavizar bordes si quedan bordes artificiales:

```markdown
Suaviza los bordes de las personas para que se integren
naturalmente con el fondo. Ajusta las sombras para que
sean consistentes con la luz del fondo.
```

---

**Tabla de resultados esperados según herramienta:**

| Flujo | Herramienta | Resultado típico | Tiempo estimado |
| --- | --- | --- | --- |
| Generar escena completa desde cero | DALL·E / Imagen 3 | ⭐⭐⭐⭐ Muy bueno para promoción previa al evento | 5 min |
| Cambiar fondo de foto real | ChatGPT edición | ⭐⭐⭐ Bueno si el fondo original es separable | 5-10 min |
| Composición manual con fondo de IA | Canva + DALL·E | ⭐⭐⭐⭐⭐ Mejor resultado, más control | 15-20 min |
| Insertar cara real específica en escena | Cualquier IA pública | ❌ No confiable en 2026 | — |

---

#### 🟠 Tarea 2 — Brief de contenido visual con Claude

**Herramienta:** Claude (Artefacto) o ChatGPT (Canvas)
**Por qué:** Antes de generar cualquier imagen o piezas visuales, un brief bien construido ahorra iteraciones y alineaciones. Claude es especialmente fuerte para documentos estructurados con criterio editorial.

**Prompt de arranque:**

```markdown
Actúa como una directora de arte con experiencia en marcas
deportivas. Crea un brief de contenido visual completo para
[nombre del evento o marca]. El brief debe incluir:
- Objetivo de comunicación
- Público objetivo (edad, intereses, plataforma principal)
- Paleta de colores (con códigos hex si puedes sugerirlos)
- Tipografía y estilo visual recomendado
- Tono de la comunicación (3 adjetivos)
- 5 tipos de piezas recomendadas para Instagram con descripción
- 3 cosas que NUNCA debe hacer esta marca visualmente
Formato: documento estructurado con secciones claras.
```

---

#### 🟡 Tarea 3 — NotebookLM para analizar referencias de marca

**Herramienta:** NotebookLM
**Por qué:** Si la cliente le dio un manual de marca en PDF, o si tiene artículos de referencia de marcas que admira, NotebookLM permite analizarlos y hacer preguntas específicas sin que la IA invente ni mezcle con otras fuentes.

**Flujo de trabajo:**

1. Subir el manual de marca o referencias en PDF a NotebookLM.
2. Preguntar: *"¿Cuáles son los valores visuales principales de esta marca según el documento?"*
3. Preguntar: *"¿Qué restricciones de uso del logo menciona este manual?"*
4. Generar Audio Overview para escuchar el resumen del manual mientras trabaja.

---

#### ⚡ Bonus — Skill de identidad de marca

Crear un Skill en Claude con el manual de identidad completo. Una vez cargado, Claude lo aplica automáticamente: cada vez que pidas contenido, ya conoce colores, tono y restricciones sin que lo repitas.

---

### 👤 Perfil 3 — Emprendedora

**Contexto del perfil:**
Un análisis de 2025 muestra que el 77% de las pequeñas empresas a nivel mundial ya utiliza alguna herramienta de IA para funciones como servicio al cliente, marketing o gestión de inventario. Las herramientas de IA para ventas transforman la forma de conectar con los clientes al analizar su comportamiento, historial de pedidos y preferencias, entregando información para recomendaciones personalizadas y mensajes de marketing adaptados. La buena noticia: no necesitas una plataforma especializada para empezar. Las herramientas del workshop son suficientes para el 80% de los casos de uso.

---

#### 🟢 Tarea 1 — Investigación de mercado y competencia

**Herramienta:** Perplexity (con fuentes verificables)
**Por qué:** Antes de tomar decisiones de precios, lanzamiento de producto o expansión, necesitas datos reales y actuales. Perplexity es la herramienta más adecuada para esto porque cada dato viene con fuente.

**Prompt de arranque:**

```markdown
Investiga el mercado de [tipo de producto que vende] en Lima,
Perú, para 2025-2026. Necesito saber:
1. Rango de precios promedio en tiendas físicas
2. Tendencias de consumo actuales en ese segmento
3. Principales competidores o referentes en Lima
4. Qué busca el consumidor peruano en ese tipo de producto hoy
Cita todas las fuentes. Prioriza información del último año.
```

---

#### 🟢 Tarea 2 — Motor de contenido para redes y tienda

**Herramienta:** ChatGPT con Canvas o Claude con Artefacto
**Por qué:** Las herramientas de IA para creación de contenido pueden escribir automáticamente descripciones de productos, mensajes de ventas personalizados y correos de seguimiento, basándose en datos del cliente y actividad de la tienda, creando contenido que parezca personalizado y oportuno sin el trabajo manual.

**Prompt para generar contenido en lote:**

```markdown
Tengo una tienda física de [tipo de productos] en Lima.
Mi cliente típica es [descripción del perfil]. Voy a darte
una lista de 5 productos y necesito para cada uno:
- Descripción corta para etiqueta en tienda (máx. 3 líneas)
- Caption para Instagram con 3 hashtags relevantes (tono
  [emotivo/divertido/aspiracional])
- Mensaje para WhatsApp de seguimiento post-compra
Lista de productos: [pegar lista]
Devuélvelo como tabla organizada por producto.
```

---

#### 🟢 Tarea 3 — ChatGPT con memoria como asistente de negocio continuo

**Herramienta:** ChatGPT (con memoria activada)
**Por qué:** La memoria de ChatGPT permite construir un historial de decisiones de negocio. Cada conversación queda guardada y en la siguiente puedes retomar desde donde dejaste.

**Cómo configurarlo:**

1. Decirle en la primera conversación: *"Soy dueña de [descripción del negocio]. A partir de ahora quiero que recuerdes mi negocio y me des seguimiento como si fueras mi asistente de estrategia. Cuando te dé actualizaciones, quiero que las guardes y las uses como contexto en las próximas conversaciones."*
2. Verificar en Configuración → Gestionar memoria que quedó guardado.
3. A partir de entonces: cada idea, cada decisión, cada pregunta queda en el historial.

---

#### ⚡ Bonus — Gema de "asistente de negocio"

Configurar en Gemini una Gema que ya sepa todo sobre el negocio: qué vende, a quién, en qué zonas, cuál es el ticket promedio, cuáles son los meses bajos y los meses altos. Para no repetir ese contexto nunca más.

### 🤖 Bonus 2 — Gema de "asistente de catálogo" en Gemini

Este es el contexto que configures una Gema para no repetirlo nunca más:

```markdown
Soy consultora independiente de cosméticos [Farmasi/Yanbal/Esika/L'Bel]
en Lima, Perú. Vendo por catálogo, por WhatsApp, Instagram y
en persona. Mi clienta típica es mujer de 25 a 50 años. Mis
campañas duran entre 21 y 25 días. Los principales problemas
que me ayudas a resolver son:
1. Escribir mensajes de WhatsApp para mis clientas
2. Crear captions para Instagram de mis productos
3. Hacer seguimiento a clientas que no compraron
4. Ideas para conseguir clientas nuevas

Cuando te pida ayuda:
- Escribe como si fueras yo, no como una marca grande
- Tono cercano, femenino, sin tecnicismos
- Los mensajes de WhatsApp deben ser cortos (máximo 5 líneas)
- Los posts de Instagram deben incluir hashtags al final
- Si te doy el nombre de un producto, asume que es de mi catálogo
```

#### ⚡ Bonus 3 — Prompts para el seguimiento a clientas que no compraron

Los prompts más útiles para este caso, listos para usar directamente en ChatGPT o Gemini:

**Mensaje de seguimiento post-visita (sin compra):**

```markdown
Soy consultora de cosméticos Yanbal/Esika en Lima. Una clienta
revisó el catálogo hace 3 días pero no hizo pedido. Escríbeme
3 versiones de mensaje de WhatsApp para retomar el contacto
de forma natural, sin presionar. Que suenen como yo, no como
un robot. Tono: cálido, cercano, breve. Máximo 4 líneas
cada mensaje. Primera versión: curiosidad sobre qué le gustó.
Segunda: compartir una oferta de esta campaña. Tercera:
pregunta abierta sobre qué necesita para el mes.
```

**Mensaje para campaña nueva:**

```markdown
Tengo una nueva campaña de Yanbal con [producto estrella]
en oferta. Escríbeme un mensaje para enviar por WhatsApp
a mis clientas habituales anunciando la campaña. Tono:
entusiasta pero no invasivo. Máximo 5 líneas. Que incluya
un llamado a la acción claro al final. Sin emojis exagerados.
```

**Post de Instagram para producto específico:**

```markdown
Soy consultora independiente de cosméticos en Lima. Voy
a postear una foto del [nombre del producto, ej: perfume
Vibranza de Yanbal]. Escríbeme 3 opciones de caption para
Instagram. Cada una con un ángulo distinto: una emotiva,
una con beneficio del producto, una con testimonio ficticio
pero creíble. Máximo 100 palabras cada una. 3 hashtags
al final de cada opción. Tono: femenino, moderno, cercano.
```

---

### 👤 Perfil 4 — Monitora de servidores en banca

**Contexto del perfil — y la advertencia más importante del módulo:**
Este perfil tiene las oportunidades más grandes con la IA, y también los riesgos más serios si se usa sin criterio. El uso de herramientas de IA sin autorización —llamado Shadow AI— la pérdida de datos por malas prácticas y las vulnerabilidades en aplicaciones generativas representan uno de los mayores riesgos en entornos corporativos y bancarios para 2026. La formación, la gobernanza y las buenas prácticas internas son esenciales para mitigar este riesgo.

Antes de cualquier caso de uso técnico, la regla de oro:

> 🚨 **Nunca pegar en una IA pública:** credenciales, contraseñas, tokens o API keys; datos personales de clientes (nombres, DNI, cuentas, transacciones); IPs internas, arquitectura de red real, nombres de servidores de producción; fragmentos de código con variables de entorno reales; logs que contengan información identificable de clientes o transacciones.

**La solución práctica:** anonimizar antes de pegar. Reemplaza datos reales con placeholders: `[SERVIDOR_A]`, `[IP_INTERNA]`, `[USUARIO_123]`. La IA analiza igual el patrón del error sin necesidad de ver los datos reales.

---

#### 🟠 Tarea 1 — Análisis de logs y diagnóstico de errores

**Herramienta:** Claude
**Por qué:** Claude es el más fuerte del grupo para análisis de texto técnico largo, razonamiento estructurado y documentación de incidentes. Su ventana de contexto permite pegar logs extensos sin que pierda el hilo.

**Prompt de diagnóstico diferencial:**

```markdown
Actúa como un ingeniero DevOps senior con experiencia en
infraestructura de servicios financieros. Analiza el siguiente
mensaje de error que apareció en nuestros logs a las [hora]:

[PEGAR ERROR CON DATOS ANONIMIZADOS]

Necesito:
1. Qué significa este error en lenguaje claro
2. Las 3 causas más probables, ordenadas de más a menos común
3. Qué información adicional necesito revisar para confirmar
   cuál es la causa real
4. Pasos de diagnóstico recomendados en orden lógico
5. Si hay un workaround inmediato mientras se investiga

Responde con encabezados numerados. No asumas acceso a
sistemas específicos. Solo el razonamiento técnico.
```

---

#### 🟡 Tarea 2 — NotebookLM como base de conocimiento técnico

**Herramienta:** NotebookLM
**Por qué:** La documentación técnica interna (manuales de procedimientos, runbooks, guías de respuesta a incidentes) es exactamente el tipo de contenido para el que NotebookLM fue diseñado: fuentes propias, citas exactas, sin inventar nada.

**Flujo de trabajo:**

1. Cargar documentación técnica genérica o pública del stack (manuales de herramientas de monitoreo, documentación oficial de sistemas, runbooks sin datos sensibles).
2. Crear el notebook "Base de conocimiento operaciones".
3. Preguntar: *"¿Cuál es el procedimiento para [tipo de incidente] según este manual?"*
4. Generar el Audio Overview para repasar procedimientos en audio.

**Nota:** Solo cargar documentación que no contenga información sensible de la infraestructura real del banco.

---

#### 🟠 Tarea 3 — Skill técnico con contexto del equipo

**Herramienta:** Claude (Skill)
**Por qué:** Un Skill con el stack tecnológico del equipo (en términos generales, sin datos sensibles), los tipos de alertas más frecuentes y el formato estándar de reporte de incidentes, permite que Claude siempre responda en el contexto correcto sin tener que repetirlo.

**Contenido del Skill (versión anonimizada):**

```markdown
Soy especialista en monitoreo de infraestructura en una
institución financiera. Trabajo con herramientas de monitoreo
[tipo genérico: APM, SIEM, etc.]. Los tipos de incidentes más
frecuentes son: [categorías generales]. El formato estándar
de reporte de incidentes que usamos es:
→ Descripción del síntoma
→ Hora de detección
→ Sistemas afectados (en categorías, no IPs reales)
→ Causa raíz probable
→ Acciones tomadas
→ Estado actual
Cuando me ayudes a analizar errores, usa siempre ese formato
para la respuesta. No incluyas datos reales de sistemas.
```

---

### 📊 Diagrama Mermaid — Regla de seguridad: qué sí y qué no pegar en la IA

<div class="mermaid">
flowchart LR
    A["📋 Información\nque tienes"] --> B{"¿Es sensible?"}

    B --> C["✅ SÍ puedes pegar"]
    B --> D["🚫 NUNCA pegar"]

    C --> C1["Mensajes de error\ngeneralizados"]
    C --> C2["Documentación\noficial pública"]
    C --> C3["Código con\nvariables vacías"]
    C --> C4["Preguntas técnicas\nsin contexto real"]

    D --> D1["Credenciales\ny contraseñas"]
    D --> D2["IPs y nombres\nde servidores reales"]
    D --> D3["Datos de clientes\n(nombre, DNI, cuenta)"]
    D --> D4["Logs con info\nidentificable"]
    D --> D5["Arquitectura de red\ninterna real"]

    style D fill:#ef4444,color:#fff
    style C fill:#2d6a4f,color:#fff
    style D1 fill:#fecaca,color:#000
    style D2 fill:#fecaca,color:#000
    style D3 fill:#fecaca,color:#000
    style D4 fill:#fecaca,color:#000
    style D5 fill:#fecaca,color:#000
</div>

---

### 📎 Material complementario por perfil

**Organizadora de eventos:**

- 📄 [IA en la organización de eventos deportivos: guía práctica — Blog Urquiabas](https://blog.urquiabas.com/la-inteligencia-artificial-en-la-organizacion-de-eventos-deportivos/) — casos concretos de cómo la IA optimiza logística, inscripciones y predicción de afluencia.
- 📄 [15 tendencias en la industria de eventos 2026 — Time.ly](https://time.ly/es/blog/nuevas-tendencias-en-la-industria-de-eventos-que-debes-seguir/) — publicado en febrero 2026, con énfasis en automatización y análisis de datos.

**Creadora de contenido visual:**

- 📄 [57 prompts para editar fotos en ChatGPT con ejemplos reales — TuExpertoApps](https://www.tuexpertoapps.com/2025/11/12/mejores-prompts-para-editar-y-mejorar-fotos-en-chatgpt/) — incluye capturas reales del resultado de cada prompt.
- 📄 [Cómo usar Canva Magic Edit y Quitafondos — Canva oficial](https://www.canva.com/es_mx/funciones/editor-fotos-ia/) — flujo paso a paso con ejemplos visuales.
- 📺 [Demo corta en TikTok: ChatGPT editando fotos en vivo](https://www.tiktok.com/@polcorominas/video/7486436938543582486) — 39 segundos que muestran el tipo de edición posible hoy.
- 📄 [IA en deportes y producción de contenido visual — Cyberclick](https://www.cyberclick.es/numerical-blog/ia-en-deportes-el-motor-tecnologico-de-los-juegos-olimpicos-milan-2026) — cómo PSG, NBA y eventos olímpicos están usando IA generativa para producción de contenido.
- 📄 [Las mejores herramientas de IA para planificación de eventos con enfoque visual — Eventtia](https://www.eventtia.com/es/las-mejores-herramientas-de-ia-para-la-planificacion-de-eventos/) — incluye Gemini, Lovable y Synthesia para contenido visual.

**Emprendedora:**

- 📄 [Las mejores herramientas de IA para vender en 2026 — Shopify](https://www.shopify.com/es/blog/ia-para-vender) — guía práctica con casos de uso para tiendas físicas y digitales.
- 📄 [Automatización IA para Pymes 2025: guía completa — Nexoestelar](https://nexoestelar.com/automatizacion-ia-pymes-2025-herramientas/) — estadísticas de adopción y herramientas accesibles para pequeños negocios en Latinoamérica.
- 🎓 [Curso: ChatGPT para Ventas y Marketing — Udemy en español](https://www.udemy.com/course/chat-gpt-para-ventas-y-marketing/) — más de 3 horas de video práctico, incluye plantillas de mensajes de prospección, seguimiento y cierre. Diseñado exactamente para vendedores sin experiencia técnica. Tiene versión con descuento frecuente.
- 📄 [10 prompts de ChatGPT para conseguir clientes sin gastar en publicidad — AprenderGratis](https://aprendergratis.es/inteligencia-artificial/guia-chatgpt-10-prompts-para-crear-un-negocio-y-generar-ingresos/) — incluye el prompt completo para diseñar una estrategia de prospección usando solo WhatsApp y redes sociales. Listo para copiar y adaptar.
- 📺 **Demo corta en TikTok:** ChatGPT editando y generando imágenes de productos en vivo — [ver demo de Pol Corominas](https://www.tiktok.com/@polcorominas/video/7486436938543582486) *(39 segundos, ideal para mostrar en el workshop lo que es posible)*

**Monitora de servidores:**

- 📄 [Ciberseguridad en la era de la IA: tendencias 2026 — Computing](https://www.computing.es/seguridad/ciberseguridad-en-la-era-de-la-ia-tendencias-retos-y-casos-de-exito-para-2026-y-mas-alla/) — incluye casos de éxito en el sector financiero con IA para detección de amenazas.
- 📄 [Perspectivas de ciberseguridad para 2026: IA como herramienta defensiva — TyN Magazine](https://tynmagazine.com/perspectivas-de-ciberseguridad-para-2026-en-ia/) — tendencias de monitoreo, respuesta automatizada y gobernanza de IA en entornos regulados.
- 📄 [Riesgos del Shadow AI en entornos corporativos 2026 — Panorama Económico](https://panoramaeconomicopma.com/2025/11/retos-y-tendencias-del-futuro-digital-2026-la-ia-y-la-ciberseguridad/) — explica por qué el uso no autorizado de IA pública en entornos bancarios es un riesgo real y creciente.
