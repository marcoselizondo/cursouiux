# Messenger visto desde WhatsApp

Análisis de competidor directo · Benchmark del proyecto final · Curso UX/UI
Borrador · 31 de octubre de 2026

> Este análisis forma parte del benchmark de equipo (`01-investigacion/benchmark-whatsapp.md`). Usa la misma premisa (*"WhatsApp quiere ayudar a sus usuarios con su organización"*), la misma user persona (Laura, 24 años) y el mismo escenario de prueba.
> **(verificar)** = comprobar en la app y respaldar con capturas. La IA sugiere, el diseñador verifica.

---

## 1. Resumen ejecutivo

1. **Es directo por categoría, pero no por público.** Hace lo mismo que WhatsApp (mensajería personal y de grupo) y es de la misma empresa, pero en España su base de usuarios es mayor: las personas de 18 a 24 años son solo el **5,9 %** de sus usuarios (NapoleonCat, octubre 2024). Laura probablemente lo usa poco o nada (validar en entrevistas).
2. **Su diferencia de fondo es la identidad.** Messenger funciona con la **cuenta de Facebook** (obligatoria desde 2019), no con el número de teléfono. Eso le permite hablar con gente sin intercambiar números (Marketplace, grupos de Facebook). WhatsApp está neutralizando esa ventaja con los **nombres de usuario** (reservas desde junio de 2026).
3. **En organización no va por delante de WhatsApp.** Tiene encuestas en grupos desde 2016, pero no hemos encontrado eventos con confirmación ni recordatorios actuales (verificar en la app). Su inversión visible ha ido a la **expresión**: temas, efectos y reacciones.
4. **La lección para WhatsApp es estratégica.** Messenger tiene muchas funciones y aun así pierde alcance, y Meta lo está volviendo a atar a Facebook (cierre de las apps de escritorio en diciembre de 2025). Más funciones no garantizan uso, y depender de otra plataforma excluye a quien no la usa.

---

## 2. Por qué es competidor directo y por qué es un caso especial

**Directo:** resuelve el mismo problema (comunicarse y coordinarse con gente cercana, en privado y en grupo) para un público que se solapa.

**Caso especial:** Messenger y WhatsApp son de **Meta**. No compiten por cuota como Telegram, sino que son dos apuestas de la misma empresa para públicos y contextos distintos. Meta suele probar funciones en una app y llevarlas a otras: encuestas, comunidades, cifrado de extremo a extremo, Meta AI. Analizar Messenger sirve para ver **qué decisiones tomó Meta en otro contexto y qué resultado tuvieron**.

---

## 3. Ficha de producto

Responde a las preguntas de investigación secundaria del kick-off.

| | Messenger | WhatsApp (referencia) |
|---|---|---|
| **Propuesta de valor** | Chatear con tu gente de Facebook de forma expresiva: temas, efectos, reacciones, llamadas | Mensajería simple, fiable y privada |
| **Identidad / acceso** | Cuenta de Facebook (obligatoria desde 2019, salvo cuentas antiguas solo de Messenger) | Número de teléfono; nombres de usuario opcionales en despliegue (2026) |
| **Usuarios** | Unos 940 millones en el mundo (Statista, octubre 2025); alcance publicitario a la baja (DataReportal, enero 2025) | Más de 3.000 millones (Meta, 2025) |
| **Público en España** | Base de mayor edad: 18-24 años = 5,9 % de usuarios (NapoleonCat, octubre 2024) | La red más usada (IAB Spain 2025) |
| **Privacidad** | Cifrado por defecto en chats individuales desde diciembre de 2023; en grupos era opcional (verificar si ha cambiado) | Cifrado de extremo a extremo por defecto en todo |
| **Plataformas** | Móvil; en ordenador solo vía web desde que cerró las apps de escritorio (15 de diciembre de 2025) | Móvil, apps de escritorio y web |
| **Cómo se comunica** | Tono lúdico y social, centrado en la expresión | Tono sencillo, centrado en la privacidad |
| **Contexto de uso típico** (hipótesis) | Gente de Facebook de la que no tienes el número, Marketplace, familiares mayores, grupos de Facebook | Todo lo cercano: familia, amigos, clase, piso, trabajo |

---

## 4. Decisiones de producto y qué nos enseñan

El curso insiste en que *con el benchmark no buscamos copiar soluciones, buscamos entender decisiones*.

| Decisión de Messenger | Efecto en la experiencia | Lectura para WhatsApp |
|---|---|---|
| **Identidad basada en Facebook** (desde 2019) | Puedes escribir a cualquiera de tu red sin pedirle el número, pero sin cuenta de Facebook no hay Messenger | WhatsApp añade nombres de usuario opcionales (sin directorio público) sin abandonar el número: gana la ventaja de Messenger sin su dependencia |
| **Apuesta por la expresión** (temas, efectos, reacciones) | Conversaciones más divertidas, interfaz más cargada | WhatsApp ha sido sobrio, y la premisa pide no alterar la experiencia actual: una función nueva no debe añadir ruido |
| **Cifrado por defecto tardío** (2023) y grupos opcionales | Menos confianza; algunas funciones pueden no estar en chats cifrados (verificar encuestas) | El cifrado limita las funciones "inteligentes": el servidor no puede leer los mensajes. Esto también condiciona lo que podemos proponer en WhatsApp |
| **Cierre de las apps de escritorio** y redirección a facebook.com (diciembre 2025) | Messenger vuelve a depender de Facebook | Una app de mensajería subordinada a una red social pierde a quien no usa esa red, que son justamente los jóvenes |
| **Community chats** en Grupos de Facebook: lanzados en 2022, retirados en octubre de 2025 (Messenger Communities sigue) | Meta probó una estructura tipo Discord y la quitó de Grupos (no hemos encontrado el motivo público) | Señal de que mucha estructura no garantiza adopción: no sobrediseñar para grupos de amigos |

---

## 5. Funciones de organización

| Función | Estado en Messenger | Qué comprobar |
|---|---|---|
| Chats de grupo | ✓ | Si todos los miembros necesitan cuenta de Facebook |
| Encuestas en grupos | ✓ desde 2016 (relanzadas en 2020) | ¿Se ve quién vota qué? ¿Se pueden cerrar? ¿Funcionan en chats cifrados? |
| Planes / eventos con confirmación de asistencia | ? Existieron "Planes" en el pasado; no hemos encontrado fuentes actuales | **Prioritario:** ¿existen hoy? ¿Cómo se confirma asistencia? |
| Recordatorios | ? | ¿Hay recordatorios en el chat o solo vía Eventos de Facebook? |
| Messenger Communities | ✓ según Meta | ¿Disponible en España? ¿Cómo se crea? |
| Mensajes fijados | ? | ¿Existen? ¿Cuántos? |
| Búsqueda y archivos compartidos | ? | ¿Cómo se encuentra una hora o una dirección antigua? |
| Pagos entre amigos | Solo en EE. UU. (verificar) | Confirmar que no hay pagos en España |
| Meta AI | Presente en las apps de Meta (verificar en Messenger) | ¿Qué hace en un chat de grupo? |

---

## 6. Recorrido de tarea con el escenario

**Escenario:** *Laura organiza con 5 amigos de Barcelona ir un fin de semana a las fiestas de su pueblo.*
Haced el recorrido en Messenger, capturad cada paso y evaluadlo con las heurísticas de Nielsen (el "padre de la usabilidad" que vimos en clase).

| Paso | Qué hacer en Messenger | Qué observar | Heurística |
|---|---|---|---|
| 1. Crear el grupo | Crear un chat con 5 personas | ¿Alguien se queda fuera por no tener Facebook? ¿Cuántos pasos hacen falta? | Flexibilidad y eficiencia |
| 2. Proponer fechas | Crear una encuesta con 3 fines de semana | ¿Es fácil encontrar la opción? ¿Se ve quién ha votado? ¿Se puede cerrar? | Visibilidad del estado del sistema |
| 3. Confirmar quién va | Buscar cómo confirmar asistencia | ¿Hay planes o eventos dentro del chat, o hay que ir a Facebook? | Coincidencia con el mundo real |
| 4. Repartir tareas y gastos | Apuntarse al coche, a la compra y a los gastos | ¿Hay algo nativo o hay que salir de la app? | Control y libertad del usuario |
| 5. Recuperar la información | Encontrar la hora y la dirección 50 mensajes después | Fijados, búsqueda, archivos | Reconocer antes que recordar |
| 6. El día del plan | Ver si llega algún recordatorio | ¿La app avisa o hay que acordarse? | Visibilidad del estado del sistema |
| 7. El ruido | Fijarse en temas, efectos, reacciones e IA durante todo el recorrido | ¿Ayudan a organizarse o distraen? | Diseño estético y minimalista |

---

## 7. Comparación directa con WhatsApp

Las celdas describen cómo se resuelve cada momento, no si la función existe o no.

| Momento | WhatsApp | Messenger |
|---|---|---|
| **Decidir** | Encuesta con una o varias respuestas; se ve quién vota qué | Encuesta en grupos (verificar si se ve quién vota y si se cierra) |
| **Confirmar** | Evento con asistiré / no asistiré y acompañante, fijado arriba del chat | Sin eventos confirmados en el chat (verificar); alternativa: encuesta o Eventos de Facebook, fuera del chat |
| **Repartir** | Nada nativo: lista que se copia y pega, Bizum o Tricount | Nada nativo en España (los pagos son solo de EE. UU.) |
| **Recordar y recuperar** | Hasta 3 fijados, destacados, búsqueda, recordatorio de evento (2026) | Verificar fijados, búsqueda y recordatorios |
| **Estado del plan** | Implícito: hay que leer el chat | Implícito (verificar) |
| **Acceso** | Número de teléfono (y nombres de usuario en 2026) | Cuenta de Facebook |
| **Privacidad** | Cifrado por defecto en todo | Por defecto en chats individuales; grupos opcionales (verificar) |
| **Tono** | Sobrio y funcional | Expresivo y lúdico |

---

## 8. Observación → Patrón → Insight → Oportunidad

| | Observación | Patrón | Insight | Oportunidad |
|---|---|---|---|---|
| **1** | Messenger y WhatsApp tienen encuestas desde hace años, pero el resultado de la votación no se convierte en un plan (verificar en Messenger). | La decisión no está conectada con la acción. | Votar no es organizar: el trabajo empieza después del voto (confirmar, repartir, recordar). | Conectar la decisión del grupo con su siguiente paso. |
| **2** | Messenger ha invertido en expresión y su público en España envejece; WhatsApp, más sobrio, domina. | Lo lúdico no retiene si la utilidad base no es mejor. | Para Laura, la app donde se organiza es la que tiene a **todo** su grupo, no la más divertida. | La nueva función debe vivir donde ya está el grupo y no añadir ruido. |
| **3** | Messenger exige Facebook, y Meta cerró las apps de escritorio para llevar a la gente a facebook.com. | Cada requisito de acceso deja a alguien fuera del grupo. | Una herramienta de organización solo funciona si **todo** el grupo puede participar sin crear cuentas ni instalar nada. Esto también aplica a Tricount o Doodle. | Cualquier función nueva debe funcionar para todos los miembros, sin requisitos extra. |
| **4** | Meta lanzó community chats tipo Discord en Grupos de Facebook (2022) y los retiró en 2025. | Estructura pesada, adopción incierta. | Un grupo de amigos no quiere administrar una comunidad. | Estructura mínima, que aparezca solo cuando haga falta. |

---

## 9. Conclusiones

1. **Messenger es un competidor directo débil para el público de Laura.** Conviene decirlo en el benchmark: es directo en categoría, no en audiencia. Para ella, probablemente sean más relevantes los mensajes directos de Instagram (validar en entrevistas).
2. **Ninguna de las dos apps resuelve el "después de votar".** La oportunidad de organización sigue abierta en ambas.
3. **El acceso es parte de la experiencia.** La barrera de la cuenta de Facebook es la mayor fricción de Messenger para organizar un grupo mixto.
4. **Más funciones y más expresión no han frenado su declive.** Una mejora de organización en WhatsApp debe ser útil y discreta, no vistosa.

---

## 10. Qué llevo a la matriz del equipo

Una línea por momento para la tabla de comparación del benchmark de grupo:

- **Decidir:** encuestas en grupos desde 2016; sin conexión con un plan (verificar cierre).
- **Confirmar:** sin eventos con confirmación en el chat (verificar); se sale a Facebook.
- **Repartir:** nada nativo en España.
- **Recordar y recuperar:** pendiente de verificar.
- **Estado del plan:** implícito.
- **Aporte único:** la identidad sin número de teléfono, y la lección de que depender de otra plataforma excluye a parte del grupo.

---

## 11. Preguntas para las entrevistas

- ¿Usas Messenger? ¿Cuándo fue la última vez?
- ¿Con quién hablas por Messenger que no hables por WhatsApp? ¿Por qué ahí?
- ¿Alguna vez has organizado un plan por Messenger o por Instagram? ¿Cómo fue?
- ¿Te ha pasado que alguien no podía unirse a un grupo por no tener una app o una cuenta?

---

## 12. Evidencias que capturar

1. Crear un chat de grupo (y lo que pasa si alguien no tiene Facebook).
2. Crear una encuesta y ver los resultados.
3. Buscar cómo crear un plan o evento y confirmar asistencia.
4. Mensajes fijados y búsqueda dentro del chat.
5. Menú de opciones del chat de grupo, completo.
6. Temas, efectos y Meta AI en un chat de grupo.
7. Messenger Communities, si está disponible.

Nombrad los archivos como `messenger_paso_n.png`, anotad la fecha y anonimizad nombres y fotos.

---

## 13. Pendiente de verificar

- ¿Existen hoy planes o eventos con confirmación de asistencia en los chats de Messenger?
- ¿Las encuestas muestran quién vota, se pueden cerrar y funcionan en chats cifrados?
- ¿Los chats de grupo ya están cifrados por defecto?
- ¿Hay mensajes fijados? ¿Cuántos?
- ¿Messenger Communities está disponible en España?
- ¿Los pagos siguen siendo solo de EE. UU.?
- ¿Qué hace Meta AI en un chat de grupo?

---

## Fuentes

- [Wikipedia · Facebook Messenger (cuenta de Facebook obligatoria desde 2019; cierre del escritorio)](https://en.wikipedia.org/wiki/Facebook_Messenger)
- [TechCrunch · La app de escritorio de Messenger ya no existe (diciembre 2025)](https://techcrunch.com/2025/12/15/facebook-messengers-desktop-app-is-no-more/)
- [CP24 · Cierre de las apps de escritorio y acceso sin cuenta de Facebook](https://www.cp24.com/news/canada/2025/12/16/metas-messenger-desktop-apps-shut-down)
- [Meta · Cifrado de extremo a extremo por defecto en Messenger (diciembre 2023)](https://about.fb.com/news/2023/12/default-end-to-end-encryption-on-messenger/)
- [PhoneArena · Cifrado de chats de grupo en Messenger](https://www.phonearena.com/news/messenger-end-to-end-encryption-feature-released_id138152)
- [TechCrunch · Encuestas en Messenger (2016)](https://techcrunch.com/2016/09/22/messenger-polls/)
- [Meta · Community Chats en Messenger y Facebook (2022; aviso de retirada en Grupos, octubre 2025)](https://about.fb.com/news/2022/09/community-chats-on-messenger-and-facebook/)
- [DataReportal · Estadísticas de Messenger 2025](https://datareportal.com/essential-facebook-messenger-stats)
- [Statista · Facebook Messenger](https://www.statista.com/study/52004/facebook-messenger)
- [NapoleonCat · Redes sociales más usadas en España](https://napoleoncat.com/es/blog/redes-sociales-mas-usadas-en-espana/)
- [AppleInsider · Nombres de usuario de WhatsApp (junio 2026)](https://appleinsider.com/articles/26/06/29/whatsapps-new-username-system-keeps-phone-numbers-private-by-design)
- [WABetaInfo · Actualización oficial sobre nombres de usuario](https://wabetainfo.com/whatsapp-shares-official-update-on-usernames-and-business-scoped-ids-ahead-of-2026-deadline/)
