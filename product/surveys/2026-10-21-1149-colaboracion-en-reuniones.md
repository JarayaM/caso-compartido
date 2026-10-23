---
opportunity: colaboracion-fuera-de-teams
beliefs: "#1, #2, #4 (y contexto de alcance)"
status: ready
date: 2026-10-21
---

# Encuesta: trabajo conjunto durante las reuniones de Teams

- **Objetivos de aprendizaje:**
  - **G1 · Minutos y vivencia (#2).** Cuántos minutos se pierden en una reunión de trabajo conjunto entre accesos, cambio de herramienta y pasar los resultados a Teams, y si quien conduce ya hizo algo para cambiarlo o lo da por normal. → Decide si el problema vale el presupuesto de USD 5M.
  - **G2 · Whiteboard: ¿no sirve o no se encuentra? (#1).** Si conocen Whiteboard, si lo probaron y por qué lo dejaron. → Decide si el problema es de producto o de descubrimiento. Si es de descubrimiento, la solución es mucho más barata.
  - **G3 · Herramienta, dentro o fuera de Teams, externos.** Qué herramienta usan, si la abren como app dentro de la reunión o como enlace en el navegador, si había invitados externos, y qué permite la política de IT. → Decide el alcance del segmento (¿entran las reuniones con externos?) y si la señal del 38% está inflada.
  - **G4 · Quién elige y quién pide (#4).** Quién decidió la herramienta, si el Team Lead le pidió algo a IT y quién inicia las compras o mejoras de plan. → Decide a quién se le vende y se le comunica.
- **Respondentes objetivo:** tres segmentos, separados en el screening.
  - **TL-grande:** Team Leads o mandos medios que en el último mes condujeron al menos una reunión de trabajo conjunto con más de 5 participantes, en organizaciones de 100 personas o más con cuenta M365 pagada (tipo Valentina Rojas).
  - **TL-chica:** el mismo perfil en organizaciones de menos de 100 personas. Es el hueco que señala el brief: el 71% de las cuentas y donde el riesgo de baja es mayor.
  - **IT:** administradores de M365 o Teams, en cualquier tamaño de organización (tipo Carolina Méndez y Rodrigo Salinas).
- **Duración estimada:** recorrido Team Lead, 4 preguntas de screening + 11 preguntas (~5 min). Recorrido IT, 3 preguntas de screening + 6 preguntas (~3 min). Quien elige "ambas" en S1 hace los dos recorridos (~7 min); se acepta porque en cuentas chicas el admin suele ser la misma persona que conduce.
- **Campo oculto:** `canal`, que se toma del enlace (ver Distribución). No se le muestra al respondente.

## Screening

S1. ¿Cuál de estas opciones describe mejor lo que haces en Microsoft Teams? [elección única]
   - Convoco y conduzco reuniones de trabajo con mi equipo u otras áreas → recorrido Team Lead
   - Administro Microsoft 365 o Teams en mi organización (configuración, licencias, permisos) → recorrido IT
   - Las dos anteriores → recorrido Team Lead y después recorrido IT
   - Participo en reuniones, pero casi nunca las convoco ni las conduzco → descalificar
   - No uso Microsoft Teams en el trabajo → descalificar
   > Goal: separa los segmentos TL e IT y deja fuera a los participantes (tipo Martín) y a quienes no usan Teams.

S2. ¿Cuántas personas trabajan en tu organización, aproximadamente? [elección única]
   - Menos de 20
   - 20 a 99
   - 100 a 999
   - 1.000 o más
   - No sé
   > Goal: corta TL-chica / TL-grande. Se pregunta por personas y no por licencias porque un Team Lead no suele saber cuántas licencias tiene la cuenta. Con "No sé" la respuesta queda en el total pero fuera del corte por tamaño.

S3. ¿Tu organización usa Teams con una cuenta de trabajo pagada por la empresa? [elección única]
   - Sí
   - No, usamos la versión gratuita o personal → descalificar
   - No sé
   > Goal: el segmento son cuentas M365 que pagan. "No sé" no descalifica.

*(Solo el recorrido Team Lead)*

S4. En el último mes, ¿cuántas reuniones de Teams condujiste con más de 5 participantes en las que el grupo tenía que producir algo juntos (planificar, priorizar, revisar, decidir)? [elección única]
   - Ninguna → descalificar
   - 1 a 3
   - 4 a 8
   - 9 o más
   > Goal: califica para el segmento y da la frecuencia que multiplica los minutos de Q4 (G1).

## Preguntas: recorrido Team Lead

*Las preguntas Q1 a Q5 piden pensar en la última reunión de ese tipo que condujiste.*

Q1. En esa última reunión, ¿qué usaron para trabajar juntos? Marca todas las que correspondan. [opción múltiple]
   - Microsoft Whiteboard
   - Notas de la reunión o componentes Loop de Teams
   - Word, Excel o PowerPoint compartidos para editar entre varios
   - Miro
   - Mural
   - FigJam
   - Google Docs, Sheets o Slides
   - Notion
   - Nada para editar juntos: compartí pantalla y edité solo yo
   - Otra: ____
   > Goal: G3 (qué herramienta) y G2 (uso real de Whiteboard antes de nombrarlo en Q7).

Q2. *(Si en Q1 marcó Miro, Mural, FigJam, Google, Notion u Otra.)* ¿Cómo la abrieron? [elección única]
   - Como app dentro de la reunión de Teams
   - Con un enlace que se abrió en el navegador
   - De las dos maneras, según la persona
   - No recuerdo
   > Goal: G3. Distingue "otra app" de "app de terceros dentro de Teams", la aclaración que dejó pendiente la research.

Q3. En esa reunión, ¿participó alguien de fuera de tu organización (clientes, proveedores, consultores)? [elección única]
   - Sí
   - No
   - No sé
   > Goal: G3. Mide qué parte del problema se explica por invitados externos, la fricción mejor documentada en la research.

Q4. En esa reunión, ¿cuántos minutos se fueron, aproximadamente, en cada una de estas cosas? [matriz; filas × columnas]
   - Filas:
     - a) Resolver accesos o permisos (alguien no podía entrar, ver o editar)
     - b) Cambiar de herramienta y lograr que todos estuvieran en el mismo lugar
     - c) Después de la reunión, pasar lo que se produjo a Teams, a un correo o a un documento
   - Columnas: 0 · 1–5 · 6–10 · 11–20 · Más de 20 · No sé
   > Goal: G1, el número de la creencia #2 (≥10 min). Las filas a y b son "durante" y la c es "después". La c se reporta aparte porque toca el problema vecino que el brief dejó fuera, y así #2 se puede evaluar con y sin ella.

Q5. Comparada con las demás reuniones de este tipo que conduces, esa última fue: [elección única]
   - Más fácil de lo habitual
   - Típica
   - Más complicada de lo habitual
   > Goal: G1. Calibra Q4: si la mayoría dice "más complicada", los minutos sobreestiman lo habitual.

Q6. En los últimos 3 meses, ¿hiciste alguna de estas cosas para que tus reuniones de trabajo conjunto funcionen mejor? Marca todas las que correspondan. [opción múltiple]
   - Probé otra herramienta
   - Mandé los enlaces o los accesos antes de la reunión para no perder tiempo
   - Armé una plantilla o una rutina propia para estas reuniones
   - Dejé de hacer actividades entre todos y ahora comparto pantalla y edito yo
   - Busqué ayuda (tutorial, soporte, un colega) sobre alguna herramienta
   - Ninguna, así como está funciona bien
   - Otra: ____
   > Goal: G1, la vivencia de #2 medida como conducta y no como opinión. Hacer algo indica que lo viven como problema. "Funciona bien" es la refutación explícita de #2.

Q7. ¿Cuál describe mejor tu experiencia con Microsoft Whiteboard en las reuniones de Teams? [elección única]
   - No sabía que existía
   - Sé que existe, pero no sé cómo abrirlo en una reunión
   - Sé cómo abrirlo, pero nunca lo usé
   - Lo usé y lo dejé de usar
   - Lo uso a veces
   - Lo uso habitualmente
   > Goal: G2. Las dos primeras opciones indican un problema de descubrimiento y la cuarta, un problema de producto. Va después de Q1–Q6 para no sesgarlas.

Q8. *(Si en Q7 eligió "Lo usé y lo dejé de usar".)* ¿Qué pasó, principalmente? [elección única]
   - No tenía lo que necesitaba (plantillas, votar, ordenar ideas, temporizador)
   - Algunos participantes no podían entrar o editar
   - Funcionaba lento con varias personas a la vez
   - Después no encontré lo que habíamos hecho
   - El equipo ya usaba otra herramienta
   - Otra: ____
   > Goal: G2. Separa "no sirve" (opciones 1 y 3) de "acceso o externos" (opción 2), "continuidad del artefacto" (opción 4) y "hábito" (opción 5).

Q9. ¿Quién decidió qué herramienta se usa para trabajar juntos en tus reuniones? [elección única]
   - Yo
   - Mi equipo, entre todos
   - Mi jefatura o mi área
   - IT o la empresa (es la herramienta estándar)
   - Un cliente o un socio externo
   - Nadie: cada vez se usa lo que haya a mano
   > Goal: G4. Indica si el uso nace del Team Lead (PLG) o viene impuesto.

Q10. En los últimos 12 meses, ¿le pediste a IT, o a quien gestiona Microsoft 365, alguna herramienta, permiso o función para tus reuniones? [elección única]
   - No
   - Sí, y me lo dieron
   - Sí, y me dijeron que no
   - Sí, y no tuve respuesta
   > Goal: G4, la conducta de "reclamar" en la que se apoya #4 (hoy Valentina "ya dejó de pedir").

Q11. ¿Qué es lo más difícil de lograr que un grupo trabaje junto durante una reunión de Teams? [abierta, opcional]
   > Goal: G1 y G2. Pregunta abierta para codificar por temas y fuente de citas. Suele ser la pregunta que más rinde.

## Preguntas: recorrido IT

IT1. ¿Qué permite hoy tu organización sobre las apps de terceros (Miro, Mural, FigJam, etc.) dentro de las reuniones de Teams? [elección única]
   - Se permite cualquier app
   - Solo las apps que aprobamos
   - Están bloqueadas
   - No tenemos una política definida
   - No sé
   > Goal: G3. Mide el cumplimiento: cuántas cuentas restringen apps externas, es decir, dónde una solución nativa no tiene competencia.

IT2. ¿Whiteboard está habilitado en las reuniones de Teams de tu organización? [elección única]
   - Sí, para todos, incluidos los invitados externos
   - Sí, solo para usuarios internos
   - Sí, solo para algunos grupos
   - No, está deshabilitado
   - No sé
   > Goal: G2. Si está deshabilitado o restringido, "no se encuentra" puede ser una decisión de IT y no un problema de producto.

IT3. En los últimos 12 meses, ¿cuántas veces te pidieron Team Leads o jefaturas herramientas, permisos o funciones para trabajar en conjunto en reuniones? [elección única]
   - Ninguna
   - 1 a 2
   - 3 a 5
   - 6 o más
   - No sé
   > Goal: G4. Es el reflejo de Q10 desde IT: si los Team Leads reclaman, IT lo nota.

IT4. La última vez que tu organización cambió de plan de Microsoft 365 o sumó un complemento, ¿quién lo propuso primero? [elección única]
   - IT
   - Un área de negocio o sus jefaturas
   - La dirección o Finanzas
   - Microsoft o un partner
   - No hubo cambios en los últimos 12 meses
   - No sé
   > Goal: G4, la conducta detrás de #4: quién inicia la compra.

IT5. ¿Tu organización paga hoy alguna de estas herramientas: Miro, Mural, FigJam o Notion? [elección única]
   - Sí, contratadas por IT
   - Sí, pagadas por las áreas por su cuenta
   - Sí, de las dos maneras
   - No
   - No sé
   > Goal: G4 y contexto de #3. Indica si el gasto en colaboración ya existe y quién lo controla.

IT6. La última vez que bloqueaste o restringiste una herramienta de colaboración, ¿por qué fue? [abierta, opcional]
   > Goal: G3 y G4. Muestra qué exige IT (seguridad, costo, duplicación) para aprobar cualquier solución.

## Screening + opt-in (reclutamiento para entrevistas)

R1. ¿Trabajas en Microsoft, en un partner de Microsoft o en una empresa que vende herramientas de colaboración? [sí / no] → no es candidato si responde "sí"

R2. *(Solo el recorrido Team Lead.)* ¿Vas a conducir alguna reunión de trabajo conjunto en las próximas 2 semanas? [sí / no] → no es candidato si responde "no" (el perfil de la entrevista exige un caso reciente para reconstruir)

R3. ¿Aceptarías una conversación de 30 minutos sobre este tema? [sí / no]

R4. *(Solo si respondió "sí" en R3.)* ¿Cómo te podemos contactar? [abierta, opcional: correo o teléfono]

## Distribución

| Canal | A quién llega y su sesgo | Alcance aprox. | Enlace |
|---|---|---|---|
| Encuesta in-product en Teams (al final de las reuniones de más de 5 participantes, a quien las organizó) | TL-grande y TL-chica. **Canal propio:** solo llega a usuarios activos y sobrerrepresenta a quienes se quedaron en Teams; deja afuera a quienes ya trabajan en otra herramienta. Se espera que domine el volumen. | unknown | `?canal=inproduct` |
| Grupo de LinkedIn de managers: **{nombre del grupo, por definir}** | TL-grande y TL-chica que no son necesariamente clientes satisfechos. Sobrerrepresenta perfiles tech y personas activas en LinkedIn. | unknown | `?canal=linkedin` |
| Panel pago (Prolific o Pollfish), filtrado por rol de manager y uso de M365 | TL-chica sobre todo, fuera del alcance de Ventas. Respondentes profesionales que contestan rápido: conviene poner una pregunta de atención. Tiene costo por respuesta y el pool en español puede ser chico. | unknown | `?canal=panel-tl` |
| Aviso en el centro de administración de M365 (Message Center o banner para admins de cuentas Premium) | IT de todos los tamaños. **Canal propio:** sobrerrepresenta a los admins comprometidos con M365. | unknown | `?canal=admincenter` |
| Comunidad de admins: Microsoft Tech Community **{foro, por definir}** y r/sysadmin | IT crítico y de cuentas grandes. Perfil muy técnico y con opinión fuerte; el público es mayormente angloparlante, así que hace falta una versión en inglés o asumir un n bajo. | unknown | `?canal=comunidad-it` |
| Panel pago filtrado por rol IT | IT de cuentas chicas, donde el admin suele ser el dueño. Respondentes profesionales. | unknown | `?canal=panel-it` |

- **n objetivo:** TL-grande 50 · TL-chica 50 · IT 30. Con menos de 30 en un segmento, los resultados son solo direccionales. Con 50 en los segmentos TL se puede cortar por canal.
- **Primera revisión:** 2026-11-03.
- **Cierre:** abierta hasta llegar al n objetivo.
- **Riesgos antes de publicar:**
  - **Calendario.** La agenda pide validar #2 hacia el 2026-11-20, y las entrevistas salen de los opt-ins. Si al 2026-11-03 algún segmento TL está lejos de 50, conviene reclutar entrevistas con los opt-ins que haya, en vez de esperar al cierre.
  - **Alcance desconocido.** Como todos los alcances son `unknown`, no se puede verificar que lleguen al n. TL-chica e IT dependen sobre todo de los paneles: es la palanca que se puede controlar comprando cuota. Conviene cotizarla antes de publicar.
  - **Sesgo de canal propio.** Si casi todo TL-grande llega desde el canal in-product, el resultado de #2 va a estar sesgado hacia quienes se quedaron en Teams. En `/analyze-survey` hay que cortar por `canal` antes de concluir.
