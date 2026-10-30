# Benchmark · WhatsApp y la organización de planes en grupo

Curso UX/UI · La Salle · Proyecto final · Entregable 1 (Investigación)
Borrador de trabajo para el equipo · 30 de octubre de 2026

> El benchmark es **investigación secundaria**: no se entrega, pero alimenta el **Research plan** y el **User Journey Map**, que sí se entregan el **8 de noviembre**.
> Este documento es un punto de partida. El curso lo dice claro: *"La IA sugiere. El diseñador verifica."* Todo lo marcado como **(verificar)** hay que comprobarlo en la app y respaldarlo con capturas.

---

## 0. Qué nos piden (resumen de los 4 documentos)

| Documento | Lo que importa para nosotros |
|---|---|
| **Kick off · Proyecto final** | Crear una nueva funcionalidad para WhatsApp **sin alterar la experiencia actual**. Premisa: *"WhatsApp quiere ayudar a sus usuarios con su organización"* personal y social. Ya tiene grupos, comunidades, encuestas y mensajes de difusión. |
| | **User persona:** Laura, 24 años, estudiante de veterinaria. Sociable, le gusta salir con los amigos. Es de un pueblo, pero estudia y vive en Barcelona. |
| | Investigación secundaria: propuesta de valor, usuarios y objetivos, cómo se comunica la marca, en qué se diferencia de la competencia. |
| **Benchmarking en Product Design** | Un benchmark no busca copiar soluciones, busca **entender decisiones**. El resultado **no son pantallas, son conclusiones**. |
| | Tipos de competidores: **directos**, **indirectos** y **aspiracionales/análogos**. Para WhatsApp en organización, el propio curso pone Notion como ejemplo de indirecto. |
| | Entregable: 1) pregunta · 2) referentes (3-5: idealmente 2 directos + 1 indirecto + 1 análogo) · 3) evidencias · 4) comparación (problema / flow / patrones / fortalezas / fricciones) · 5) 3-5 conclusiones · 6) 2-3 oportunidades. |
| | Método: **Observación → Patrón → Insight → Oportunidad**. *Feature ≠ insight.* |
| | 5 errores que evitar: solo directos · comparar si tienen o no una feature · capturas sin conclusiones · confundir "me gusta" con criterio UX · copiar el patrón dominante porque "todo el mundo lo hace". |
| **Product Thinking** | Separar **problem space** (qué pasa y por qué) de **solution space** (qué construimos). Ejemplo del propio curso: *"Los usuarios pierden información importante dentro de los grupos de WhatsApp"* es un problema; *"Crear carpetas dentro de WhatsApp"* es una solución. |
| | Una buena solución es **deseable (usuario) × viable (negocio) × factible (tecnología)**. |
| **Introducción UX/UI** | Empatizar es el centro: comportamientos, necesidades, objetivos y frustraciones del usuario antes que wireframes. |

**Calendario:** Entregable 1 (research plan + journey map) **8 nov** · Entregable 2 (wireframes + UI kit) **20 nov** · Entregable 3 (prototipo Figma) **27 nov** · Entregable 4 (HTML + CSS) **29 nov** · Entrega presentación **2 dic** · Presentación (7 min) **4 dic**.

---

## 1. Contexto: WhatsApp hoy

**Propuesta de valor.** Mensajería simple, fiable y privada: cifrado de extremo a extremo por defecto y sin necesidad de "añadir amigos", porque funciona con el número de teléfono.

**Usuarios y objetivos.** Más de 3.000 millones de usuarios al mes (Meta, primer trimestre de 2025). En España es la red más usada según el Estudio de Redes Sociales de IAB Spain 2025 (verificar el porcentaje en el PDF oficial). Se usa para hablar con la gente cercana y para **coordinarse**: familia, amigos, clase, piso, trabajo.

**Cómo se comunica.** Tono sencillo y cercano, con la privacidad como mensaje central. Lanza funciones de forma gradual y las anuncia en su blog y en el newsroom de Meta.

**En qué se diferencia.** Efecto red (todo el mundo lo tiene), simplicidad y privacidad. Telegram y Discord ofrecen más estructura y funciones, pero no tienen esa base de usuarios en España.

**Lo que ya ofrece para organizarse** (revisado en octubre de 2026):

| Función | Qué hace | Nota |
|---|---|---|
| Grupos y comunidades | Conversación de grupo; comunidades agrupan varios grupos con avisos | |
| Encuestas | Votar entre opciones, con una o varias respuestas; se ve quién vota qué | ¿Se pueden cerrar o poner plazo? (verificar) |
| Eventos en grupos | Crear un plan con fecha, hora y lugar; confirmar asistencia y añadir acompañante; queda fijado arriba del chat | Desde 2024. ¿Hay opción "quizás"? (verificar) |
| Recordatorios de eventos | El organizador programa un aviso previo para los invitados | Enero 2026 |
| Etiquetas de miembro | Cada persona se pone una etiqueta en cada grupo ("Conductora", "Tesorero") | Enero 2026 |
| Mensajes fijados | Hasta 3 por chat | |
| Mensajes destacados | Guardar mensajes para encontrarlos después | |
| Mensaje a ti mismo | Chat contigo para notas, enlaces y recordatorios | Uso como bloc de notas: señal de organización personal |
| Listas de chats | Agrupar chats en listas propias (Familia, Piso, Uni…) | |
| Canales y listas de difusión | Comunicación de uno a muchos | |

**Lo que no tiene en España:** listas de tareas colaborativas, reparto de gastos ni pagos.

---

## 2. Pregunta de benchmark

> **¿Cómo ayudan otros productos a un grupo a pasar de "hablar de un plan" a tenerlo cerrado (decidido, confirmado y repartido) sin que la información se pierda por el camino?**

La pregunta se divide en cinco momentos del plan. Son las **dimensiones de comparación**:

| Momento | Pregunta concreta |
|---|---|
| **Decidir** | ¿Cómo elige el grupo entre opciones (fecha, sitio) y cómo se cierra la decisión? |
| **Confirmar** | ¿Cómo se ve quién viene, quién no y quién no ha contestado? |
| **Repartir** | ¿Cómo se reparten tareas y gastos, y cómo se ve quién ha cumplido? |
| **Recordar y recuperar** | ¿Cómo se encuentra después la información clave y cómo se evita olvidarla? |
| **Estado del plan** | ¿Cómo se sabe en qué punto está el plan sin leer todo el chat? |

**Por qué esta pregunta.** Laura es sociable, sale con amigos y vive entre Barcelona y su pueblo: su organización social pasa por planes de grupo. La pregunta habla del problema, no de una solución ("añadir un calendario"), y nos deja comparar productos muy distintos con el mismo criterio. *"Analizar WhatsApp"* no sería una pregunta válida según el curso.

**Escenario para capturar evidencias** (el mismo en todas las apps, para comparar en igualdad de condiciones):
*Laura organiza con 5 amigos de Barcelona ir un fin de semana a las fiestas de su pueblo: decidir qué fin de semana, quién va, quién lleva coche, qué hay que comprar y cómo se reparten los gastos.*

**Otros enfoques posibles** si el equipo prefiere otro foco (cambian la pregunta y algunos competidores):
- **Piso compartido:** tareas de casa, compra y gastos comunes.
- **Organización académica:** trabajos en grupo, apuntes, exámenes y prácticas.
- **Vínculo con el pueblo y la familia:** mantenerse al día sin agobiarse con 20 grupos.

---

## 3. Mapa de competidores

### Criterios

| Tipo | Definición (del curso) | Aplicado a WhatsApp + organización |
|---|---|---|
| **Directo** | Resuelve el mismo problema para un público similar. | Apps de mensajería donde un grupo de amigos habla **y** se organiza. |
| **Indirecto** | Resuelve una parte de la misma necesidad, pero de otra forma. | Herramientas de organización que **no son mensajería**: calendario, gastos, listas, elegir fecha. |
| **Análogo** | Otro sector, pero con un **patrón de interacción** parecido. | Productos donde **varias personas aportan a un resultado común** con fecha límite. |
| **Aspiracional** | Referente de excelencia que marca **lo que el usuario ya espera** en un patrón concreto. | Productos que hacen muy bien **mostrar el estado** de un proceso y **avisar en el momento justo**. |

> **Ojo con el curso:** la diapositiva 05 del benchmark agrupa análogo y aspiracional en una sola categoría ("Aspiracional": Amazon, Revolut, Uber Eats). La diapositiva 10 la llama "análogo". Aquí los separamos: el **análogo** nos enseña un *patrón de interacción* y el **aspiracional** nos enseña el *nivel de experiencia* que Laura ya da por hecho en otras apps. Esto conecta con la columna **Expectativas** del curso: *¿qué esperan encontrar los usuarios?*

★ = seleccionado para el análisis a fondo.

### Directos

| Producto | Qué resuelve | Qué nos interesa observar |
|---|---|---|
| **Telegram** ★ | Mensajería con grupos grandes, temas, encuestas y checklists | Cómo estructura la conversación (temas) y las tareas (checklists) sin salir del chat |
| **Discord** ★ | Comunidades con canales, hilos, eventos y encuestas; muy usado por la generación de Laura | Cómo separa la conversación del plan; eventos con "me interesa"; encuestas con duración |
| Instagram (mensajes directos) | Chats de grupo donde muchos jóvenes proponen planes | ¿Los planes nacen aquí y luego pasan a WhatsApp? Mejor como pregunta de entrevista |
| Mensajes de Apple (iMessage) | Grupos entre usuarios de iPhone | Uso minoritario en España; sirve de contraste |
| Signal | Mensajería centrada en la privacidad | Misma base que WhatsApp con menos funciones: muestra el "mínimo" del sector |

### Indirectos

| Producto | Qué resuelve | Qué nos interesa observar |
|---|---|---|
| **Tricount** ★ | Gastos compartidos de un grupo: quién ha pagado y quién debe a quién | Cómo hace visible el estado del dinero sin conversaciones incómodas |
| Splitwise | Lo mismo que Tricount | Alternativa si alguien del equipo la usa |
| Google Calendar / Calendario de Apple | Invitaciones con confirmación (sí / no / quizás) y recordatorios en la agenda personal | Cómo muestra quién está "pendiente de responder"; une lo social con lo personal |
| Doodle | Elegir fecha según la disponibilidad de cada uno | Cómo se decide una fecha con muchas personas |
| Notion | Organización compartida: listas, tablas, planificación de viajes (ejemplo del curso) | Cuánta estructura acepta un grupo de amigos antes de abandonar |
| Google Keep / Recordatorios de Apple | Listas compartidas (la compra del piso) | Listas colaborativas ligeras |
| Bizum | Enviar y pedir dinero a amigos (España) | Dónde se mueve el dinero real después de repartir |

### Análogos

| Producto | Qué resuelve | Qué nos interesa observar |
|---|---|---|
| **Uber Eats · pedido en grupo** ★ | Varias personas piden juntas: cada una añade lo suyo antes de una fecha límite y puede pagar su parte | Fecha límite + cierre + "quién falta": cómo se convierte la indecisión en decisión |
| Spotify · listas colaborativas | Varias personas construyen una lista común | Aportar a un objeto compartido sin coordinarse por chat |
| Airbnb · listas de favoritos compartidas | Un grupo reúne opciones de alojamiento para decidir | Comparar opciones en grupo (¿permite votar? verificar) |
| Google Docs | Edición conjunta con comentarios asignados a personas | Asignar responsables dentro de un objeto común |

### Aspiracionales

| Producto | Qué resuelve | Qué nos interesa observar |
|---|---|---|
| **Glovo · seguimiento del pedido** ★ | Saber en todo momento en qué punto está el pedido (empresa de Barcelona, probablemente Laura la usa) | Estados paso a paso, hora estimada y aviso en cada cambio: no hay que preguntar |
| Amazon · seguimiento del envío | Barra de progreso del envío (ejemplo del curso) | Hacer visible el estado reduce la incertidumbre en procesos largos |
| Revolut · transferencias | Estado del pago claro y notificación inmediata (ejemplo del curso) | Confirmación instantánea de que algo se ha completado |
| Actividades en directo (iPhone) | La información del momento aparece en la pantalla de bloqueo sin abrir la app | Recordar sin buscar |

### Selección para el análisis a fondo

| Tipo | Producto | Qué aporta a la pregunta |
|---|---|---|
| Base | **WhatsApp** | Cómo lo resuelve hoy "nuestra" app |
| Directo | **Telegram** | Decidir (cerrar encuesta) · Repartir (checklist) · Recuperar (temas, varios fijados) |
| Directo | **Discord** | Decidir (encuesta con duración) · Confirmar (evento con interesados) · Recuperar (canales e hilos) |
| Indirecto | **Tricount** | Repartir gastos · Estado del dinero |
| Análogo | **Uber Eats · pedido en grupo** | Decidir con fecha límite · Aportación individual · Ver quién falta |
| Aspiracional | **Glovo · seguimiento** | Estado del proceso · Avisos proactivos |

Son 5 referentes + WhatsApp, dentro del rango 3-5 del curso. Si queréis profundizar en **confirmar asistencia**, cambiad Tricount por **Google Calendar**.

---

## 4. Evidencias: qué capturar

Usad siempre el **escenario de las fiestas del pueblo**. Nombrad los archivos como `app_momento_n.png` (por ejemplo, `whatsapp_decidir_1.png`) y anotad la fecha de la captura. **Anonimizad** cualquier chat real: borrad nombres, fotos y números.

| App | Capturas / flows |
|---|---|
| **WhatsApp** | 1) Crear encuesta de fechas y ver resultados · 2) Dónde queda la encuesta después de 30-40 mensajes · 3) Crear evento → confirmar asistencia → recordatorio · 4) Mensajes fijados · 5) Info del grupo: eventos, archivos, enlaces · 6) Ejemplo real (anonimizado) de **lista que se copia y pega** o de *"¿a qué hora era?"* |
| **Telegram** | 1) Encuesta y cerrar encuesta · 2) Checklist con tareas marcadas (crearla requiere Premium; si nadie lo tiene, usad las capturas del blog oficial) · 3) Grupo con temas · 4) Varios mensajes fijados · 5) Mensaje programado |
| **Discord** | 1) Crear evento programado + "me interesa" · 2) Encuesta con duración · 3) Canal del plan + hilo para un subtema |
| **Tricount** | 1) Crear un tricount y compartir el enlace · 2) Añadir un gasto · 3) Pestaña de saldos · 4) Reembolsos sugeridos · 5) Marcar como pagado |
| **Uber Eats** | 1) Iniciar pedido en grupo · 2) Elegir fecha límite · 3) Vista de participantes · 4) Pago dividido (verificar que existe en España) |
| **Glovo** | 1) Estados del pedido · 2) Hora estimada y mapa · 3) Notificaciones en cada cambio |

---

## 5. Comparación

### 5.1 Ficha por referente (problema / flow / patrones / fortalezas / fricciones)

**Telegram** (directo)
- **Problema que resuelve:** conversación de grupo, también en grupos muy grandes.
- **Flow (escenario):** grupo → encuesta de fechas, que el creador puede cerrar → checklist "Qué llevar", donde cada uno marca lo suyo → temas "Transporte" y "Gastos" → mensajes fijados.
- **Patrones:** estructura opcional dentro del chat; tareas como objeto marcable, no como mensaje.
- **Fortalezas:** la checklist resuelve la lista que se copia y pega; los temas evitan que todo se mezcle.
- **Fricciones:** crear checklists es de pago (Premium); los temas están pensados para grupos grandes y sobran en uno de 6; en España pocos amigos de Laura lo tendrán (efecto red).

**Discord** (directo)
- **Problema que resuelve:** comunidades con conversación ordenada por temas.
- **Flow:** servidor → canal #fiestas-pueblo → evento programado; cada uno pulsa "me interesa" y recibe aviso → encuesta con duración, que se cierra sola → hilos por subtema.
- **Patrones:** el plan (evento) vive aparte de la conversación; las decisiones tienen fecha de caducidad.
- **Fortalezas:** lista visible de interesados; cierre automático de encuestas; cada tema tiene su espacio.
- **Fricciones:** solo existe "me interesa" (no hay "no voy" ni "quizás"), así que no sabes quién **no** viene. Montar un servidor es pesado para 6 amigos, y la cultura es de comunidad y gaming.

**Tricount** (indirecto)
- **Problema que resuelve:** repartir gastos de grupo y saber quién debe a quién.
- **Flow:** crear tricount "Fiestas" → compartir enlace → cada uno añade lo que paga, con foto del ticket → pestaña de saldos → reembolsos sugeridos → marcar como pagado.
- **Patrones:** un estado del dinero siempre visible y calculado por el sistema.
- **Fortalezas:** nadie tiene que hacer cuentas ni reclamar a mano; los reembolsos sugeridos minimizan transferencias; es gratis.
- **Fricciones:** es otra app u otro enlace que todos deben abrir. El dinero se mueve en otra parte (Bizum), y el *"¿me haces el Bizum?"* vuelve a WhatsApp.

**Uber Eats · pedido en grupo** (análogo)
- **Problema que resuelve:** que varias personas pidan juntas sin que una lo coordine a mano.
- **Flow:** el anfitrión inicia el pedido → pone fecha límite (hasta 7 días; cierre automático o manual) → comparte enlace → cada uno añade lo suyo → la app manda recordatorios antes del límite → el anfitrión paga todo o cada uno paga lo suyo.
- **Patrones:** objeto compartido + aportación individual + fecha límite + cierre.
- **Fortalezas:** el anfitrión no persigue a nadie, porque la app recuerda; el límite convierte la indecisión en decisión; cada uno se responsabiliza de lo suyo, incluido el pago.
- **Fricciones:** depende de que todos abran el enlace; solo vale para un restaurante; ocurre fuera de la conversación.

**Glovo · seguimiento del pedido** (aspiracional)
- **Problema que resuelve:** la incertidumbre de "¿dónde está mi pedido?".
- **Flow:** pedido aceptado → en preparación → en camino (mapa y hora estimada) → entregado, con una notificación en cada paso.
- **Patrones:** una línea de estados clara y avisos proactivos.
- **Fortalezas:** el usuario no tiene que preguntar ni buscar; siempre sabe "dónde estoy".
- **Fricciones:** es un proceso lineal y controlado por la empresa; un plan de amigos es más caótico. Hay que adaptar el patrón, no copiarlo.

**WhatsApp** (base)
- **Flow actual del escenario:** alguien propone el plan → conversación larga → encuesta de fechas (que sube con los mensajes nuevos) → a veces alguien crea un evento, si sabe que existe → lista que se copia y pega para apuntarse al coche o a la compra → gastos fuera de la app (Bizum, Tricount) → *"¿a qué hora era?"*
- **Fortalezas:** todo el mundo está ya ahí; las encuestas y los eventos existen y son fáciles; el cifrado da confianza.
- **Fricciones:** las piezas (encuesta, evento, fijado) están **desconectadas**: el resultado de la encuesta no se convierte en evento. No hay listas colaborativas, el estado del plan solo se sabe leyendo el chat y el dinero vive fuera.

### 5.2 Matriz por momento del plan

Las celdas describen **cómo** lo resuelve cada uno, no si "tiene o no" la función.

| Momento | WhatsApp | Telegram | Discord | Tricount | Uber Eats (grupo) | Glovo (seguimiento) |
|---|---|---|---|---|---|---|
| **Decidir** | Encuesta en el chat; se ve quién vota qué; sin cierre (verificar) y se pierde con el scroll | Encuesta pública o anónima; el creador la cierra | Encuesta con duración; se cierra sola | — | Cada uno decide lo suyo antes de una fecha límite | — |
| **Confirmar** | Evento con "asistiré / no asistiré" y acompañante; fijado arriba | Sin eventos nativos (verificar); se usa una encuesta "voy / no voy" | Evento con "me interesa" (sin "no voy") | — | Se ve quién ha añadido su parte | Confirmación inmediata del pedido |
| **Repartir** | Sin listas ni gastos → lista copia-pega; Bizum y Tricount fuera | Checklist con permisos (crear requiere Premium) | No nativo (bots) | Gastos, saldos, reembolsos sugeridos, marcar como pagado | Cada uno paga lo suyo | — |
| **Recordar y recuperar** | Hasta 3 fijados, destacados, búsqueda, evento en la info del grupo, recordatorio de evento | Varios fijados, temas, mensajes programados | Canales, hilos, fijados, eventos en la cabecera del servidor | Historial de gastos con fotos de tickets | Recordatorios antes del cierre | Avisos en cada cambio, sin tener que buscar |
| **Estado del plan** | Implícito: hay que leer el chat | Parcial: checklist hecho / pendiente | Parcial: lista de interesados | Claro para el dinero | Claro: abierto → cerrado → pedido | Muy claro: línea de estados + hora estimada |

---

## 6. Observación → Patrón → Insight → Oportunidad

| | Observación | Patrón | Insight | Oportunidad |
|---|---|---|---|---|
| **1** | Los 5 referentes sacan el plan del flujo de mensajes a un **objeto propio** (checklist, evento, tricount, pedido, seguimiento). WhatsApp tiene eventos, pero la decisión previa y las tareas siguen siendo mensajes. | El plan vive aparte de la conversación y tiene un sitio fijo. | Cuando un plan está repartido en mensajes, el grupo repite preguntas (*"¿a qué hora era?"*) y alguien acaba haciendo de secretario. | Conectar lo que WhatsApp ya tiene (encuesta → evento → recordatorio) en un plan con sitio fijo. |
| **2** | Discord (duración) y Uber Eats (fecha límite + cierre automático) ponen un final a la decisión; Telegram deja cerrarla a mano. | Límite temporal + cierre. | Sin un final, las decisiones de grupo se alargan, y nadie quiere ser quien las cierra. | Ayudar a cerrar decisiones a tiempo. |
| **3** | Uber Eats muestra quién ha añadido su parte, Tricount quién debe y Discord quién está interesado. | Estado por persona visible. | Perseguir a quien no contesta es la parte socialmente incómoda. Si el sistema lo hace visible y lo recuerda, nadie tiene que ser "el pesado". | Recordatorios y pendientes visibles sin señalar a nadie. |
| **4** | En WhatsApp las tareas se resuelven con listas que se copian y pegan, y los gastos se van a Tricount o Bizum. Telegram ya integra checklists. | Lo colaborativo se apunta, no se conversa. | El usuario ya ha inventado su propia herramienta dentro del chat: es la señal más clara de una necesidad no resuelta. | Listas colaborativas ligeras dentro del chat. |
| **5** | Telegram y Discord añaden mucha estructura (temas, canales, hilos, permisos), pensada para comunidades grandes. Glovo tiene un proceso lineal que un plan de amigos no tiene. | Más estructura = más curva de aprendizaje. | En un grupo de 5-10 amigos, la estructura debe aparecer solo cuando hace falta. La premisa pide no alterar la experiencia actual. | Diseñar algo ligero y opcional, construido sobre patrones que Laura ya conoce. |

---

## 7. Conclusiones (aprendizajes)

1. **Un plan es un objeto con estado, no un hilo de mensajes.** Los productos que mejor organizan dan al plan un sitio propio y visible. En WhatsApp las piezas existen (encuestas, eventos, fijados), pero no están conectadas.
2. **Decidir necesita un final.** Una fecha límite o un cierre automático convierten la indecisión en decisión; sin ellos, la encuesta se queda abierta y enterrada.
3. **Lo que más cuesta es perseguir a quien no responde.** Ver "quién falta" y delegar el recordatorio en el sistema quita el peso social al organizador.
4. **La organización está fragmentada, pero se coordina en WhatsApp.** El dinero va a Bizum o Tricount y las tareas a listas copiadas. Los apaños del usuario son la pista más fiable de dónde está el problema.
5. **Más funciones no es mejor organización.** Telegram y Discord estructuran más, pero para un grupo pequeño la ayuda debe ser ligera, opcional y sobre lo que ya se conoce.

---

## 8. Oportunidades (para validar, no para construir todavía)

Estas oportunidades siguen en el **problem space**. La funcionalidad se decide después de las entrevistas.

| | ¿Cómo podríamos…? | Usuario (¿deseable?) | Negocio (¿viable?) | Tecnología (¿factible?) |
|---|---|---|---|---|
| **O1** | …hacer visible **en qué punto está un plan** (decidido, quién viene, qué falta) sin salir del chat? | Menos búsqueda y menos preguntas repetidas | Más uso de grupos y eventos; retiene frente a apps de organización | Reutiliza encuestas, eventos y fijados. El cifrado de extremo a extremo impide que el servidor "lea" el plan: tiene que crearlo el usuario o procesarse en el dispositivo |
| **O2** | …ayudar a un grupo a **cerrar decisiones a tiempo** sin que nadie tenga que hacer de "pesado"? | Menos fricción social para quien organiza | Más planes que se materializan; más valor percibido | Plazos y recordatorios ya existen en eventos (2026); habría que extenderlos a encuestas |
| **O3** | …facilitar que el grupo **se reparta tareas** y vea quién ha cumplido, sin la lista que se copia y pega? | Sustituye un apaño muy extendido | Diferenciación frente a Telegram (allí es de pago) | Objeto colaborativo dentro del chat, similar a las encuestas |

---

## 9. Del benchmark a las entrevistas (Research plan)

**Hipótesis a validar:**
- **H1.** En el grupo de Laura suele organizar casi siempre la misma persona, y le resulta pesado.
- **H2.** La información clave de un plan (hora, sitio, quién viene) se pierde en el chat y se vuelve a preguntar.
- **H3.** Las encuestas sirven para votar, pero no cierran la decisión.
- **H4.** Los gastos se reparten fuera de WhatsApp (Bizum, Tricount) y generan recordatorios incómodos.
- **H5.** Pocos usuarios conocen o usan los eventos de WhatsApp.
- **H6.** Las listas que se copian y pegan son habituales para apuntarse a algo.

**Preguntas de entrevista.** Preguntad por comportamiento pasado, no por opiniones: *lo que dice la gente ≠ lo que hace la gente*.
- Cuéntame el último plan que organizaste con amigos. ¿Cómo empezó? ¿Dónde se decidió?
- ¿Qué fue lo más pesado de organizarlo?
- ¿Quién suele organizar en tu grupo? ¿Cómo te sientes cuando te toca a ti?
- ¿Alguna vez has tenido que buscar en el chat una hora o una dirección? ¿Cómo lo hiciste?
- ¿Cómo os repartís los gastos? ¿Qué apps usáis?
- ¿Has usado encuestas o eventos de WhatsApp? ¿Para qué? ¿Y alguna otra app para organizaros?
- **Observación:** *"¿Me enseñas el chat del último plan?"* (con permiso y sin capturar datos personales).

---

## 10. Verificación ("La IA sugiere, el diseñador verifica")

**Comprobado en fuentes públicas (octubre de 2026):**
- WhatsApp: eventos en grupos con confirmación de asistencia y acompañante (2024); recordatorios de eventos y etiquetas de miembro (enero 2026).
- WhatsApp supera los 3.000 millones de usuarios mensuales (Meta, primer trimestre de 2025).
- Telegram: checklists colaborativas desde julio de 2025; crearlas requiere Premium.
- Discord: los eventos programados solo tienen la opción "me interesa".
- Uber Eats: pedido en grupo con fecha límite (hasta 7 días), cierre automático o manual, recordatorios y pago dividido (relanzado en 2022).
- Tricount: gratis; saldos, reembolsos sugeridos y marcar como pagado.

**Pendiente de verificar en la app (con capturas):**
- ¿Las encuestas de WhatsApp se pueden cerrar o tener plazo?
- ¿Los eventos de WhatsApp tienen opción "quizás"?
- Opciones de duración de las encuestas de Discord.
- ¿El pedido en grupo de Uber Eats está disponible en España? Si no, usad capturas de su web.
- ¿Telegram tiene eventos nativos?
- Porcentaje de uso de WhatsApp en España (PDF oficial del Estudio de Redes Sociales de IAB Spain 2025).
- ¿Las listas de favoritos de Airbnb permiten votar?

---

## Fuentes

- [Meta Newsroom · Member tags, text stickers and event reminders (enero 2026)](https://about.fb.com/news/2026/01/whatsapp-group-chats-member-tags-text-stickers-event-reminders/)
- [WhatsApp Blog · Events in communities](https://blog.whatsapp.com/new-to-communities-events-and-replies-in-announcement-groups)
- [Gulf News · WhatsApp events in group chats (2024)](https://gulfnews.com/technology/media/whatsapp-now-lets-you-organise-events-in-group-chats-plan-parties-gatherings-easier-1.1714893885488)
- [TechCrunch · WhatsApp supera los 3.000 millones de usuarios (2025)](https://techcrunch.com/?p=3001817)
- [Marketing4eCommerce · Estudio de Redes Sociales en España 2025](https://marketing4ecommerce.net/estudio-redes-sociales-en-espana-2025/)
- [Telegram Blog · Checklists (julio 2025)](https://telegram.org/blog/checklists-suggested-posts)
- [Discord Support · Scheduled Events, más opciones que "interested"](https://support.discord.com/hc/de/community/posts/4413166913815-Scheduled-Events-More-options-than-just-interested)
- [Uber · Group orders](https://www.uber.com/blog/business-meal-group-orders)
- [TechCrunch · Uber Eats split the bill (2022)](https://techcrunch.com/2022/03/09/uber-eats-now-lets-you-split-the-bill)
- [Tricount · FAQs](https://help.tricount.com/articles/tricount-faqs)
- [Tricount · Track group expenses with friends](https://tricount.com/blog/the-easiest-way-to-track-group-expenses-with-friends)
