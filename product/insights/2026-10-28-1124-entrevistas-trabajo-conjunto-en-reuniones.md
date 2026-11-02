---
date: 2026-10-28
source: real
opportunity: colaboracion-fuera-de-teams
guide: product/interview-guides/2026-10-21-2030-colaboracion-en-vivo-fuera-de-teams.md
sources:
  - product/interviews/2026-10-26-0900-javier-molina.md (real)
  - product/interviews/2026-10-26-0930-martina-rojas.md (real)
  - product/interviews/2026-10-26-1000-diego-paredes.md (real)
  - product/interviews/2026-10-26-1000-tomas-aguirre.md (real)
  - product/interviews/2026-10-26-1100-andres-quintero.md (real)
  - product/interviews/2026-10-26-1200-sofia-martinez.md (real)
  - product/interviews/2026-10-26-1400-paula-benitez.md (real)
  - product/interviews/2026-10-26-1500-valeria-castro.md (real)
  - product/interviews/2026-10-26-1600-lucia-fernandez.md (real)
  - product/interviews/2026-10-26-1700-ricardo-salinas.md (real)
n: 10 entrevistas de exploración (26–34 min), 6 del panel y 4 del email
---

# Insights de entrevistas: trabajo conjunto en reuniones de más de 5 personas

> **Revisión del 2026-11-02.** Varios conteos de este análisis se corrigieron con las transcripciones y el CSV. Los principales: 4/10 abandonaron la pizarra (no 5), el artefacto preexistía en 6/10 (no 7), 7/10 dedican 10–60 min al cierre (no 20–60 en todos), hay 10 casos (8 con costo concreto y 2 de rediscusión; no 9 incidentes) y 8/10 desconocen alguna función según Q10 (no 3). Si hay diferencias con el texto de abajo, vale `product/insights/2026-11-02-1357-contraste-creencias.md`.

**Lectura general.** La encuesta ya lo anticipaba y las entrevistas lo refuerzan: el dolor más caro no está en colaborar en vivo dentro o fuera de Teams, sino en **cerrar la reunión**. Hay que dejar registrado qué se decidió, quién lo hace, para cuándo y por qué, y que eso llegue a donde vive el trabajo. Aparece en las 10 entrevistas, con incidentes concretos que costaron entre días y semanas. La colaboración en vivo deja dolores reales, pero más chicos: tableros nativos que se pierden, no poder señalar y voces que no se escuchan.

## 1. La decisión se pierde entre la reunión y el trabajo, y lo arregla el líder a mano con 20–60 min por reunión

En las 10 entrevistas, lo decidido no queda capturado en el momento con responsable, fecha y motivo. El líder lo reconstruye después, solo: Javier dedica 30 min, Diego 20, Tomás 20, Andrés más de 30, Valeria casi 1 h, Lucía 30 y Paula 10 o más. Varios lo dicen literalmente: "nadie más lo hace". Cuando ese paso falla o se atrasa, el costo es grande y concreto: hay 9 incidentes con trabajo rehecho o clientes afectados. En tres casos el problema es de **responsable ambiguo** ("yo entendí que lo pasaba él", según Andrés, Lucía y Ricardo). En otros, es el **porqué perdido**, que obliga a reabrir la discusión (Martina, Tomás). Esto pide una capacidad que, *durante* la reunión, fije cada decisión con responsable, fecha y motivo, la haga confirmar por el grupo antes de cerrar y la publique donde vive el trabajo (Jira, el canal, el correo, Confluence), en lugar de un acta más.

> Evidencia: "Desde entonces, después de cada planning, reescribo el recap. Media hora, más o menos. Una lista: decisión, responsable, fecha. […] Es trabajo mío, nadie más lo hace. Y si no lo hago, vuelve a pasar." — Javier Molina (antes de eso, el equipo de México entregó dos semanas tarde y hubo que mover una release)
>
> "Lo que sí me serviría es algo que cierre la reunión con lo decidido y el por qué, y que eso quede en el ticket. Eso no lo tengo." — Martina Rojas
>
> "Lo que nos falla es cómo se cierra la reunión: que quede claro qué se decidió, que lo sepan todos, incluso los que no hablaron." — Sofía Martínez (una decisión quedó escondida en un hilo de comentarios marcado como resuelto y costó dos semanas de trabajo que hubo que sacar)
>
> Otros costos: el cliente esperó 4 días (Andrés), estuvo 1 semana sin respuesta (Lucía), la campaña siguió 3 días más (Diego), un diseñador perdió 1 semana (Valeria) y hubo 2 días de arreglos más una guardia de fin de semana (Ricardo).

**Recurrencia:** 10/10. Es el insight más fuerte del corpus. **Salvedad:** el tema no surgió solo. La guía lo pregunta en Q5 y Q6: las 10 entrevistas incluyen la pregunta por cómo quedó registrada la decisión, y al menos 7 piden además un caso de alguien que se enteró tarde o de algo hecho distinto de lo acordado. El 10/10 y los 9 incidentes muestran que el problema existe y lo que cuesta, no con qué frecuencia ocurre. La encuesta lo refuerza como la categoría más mencionada en la pregunta abierta Q11 (30 de 95; 22 en sentido estricto), aunque Q11 pregunta por "llegar a una decisión" y también orienta hacia el tema.

## 2. El recap de IA no sirve para cerrar: resume la conversación, no las decisiones, y a veces inventa decisiones

6 de los 10 usan o probaron el resumen de Copilot, y ninguno lo usa como registro de decisiones sin corregirlo. Las fallas son cuatro: **aplana** todo al mismo nivel (Javier, Martina); **convierte ideas en decisiones** (Paula, con el costo de 1 semana de 2 desarrolladores); **no ve lo que pasa fuera de la voz**, como el tablero de FigJam, el hilo de Slack o el filtro del dashboard (Valeria, Martina, Diego); y **no dice quién se comprometió a qué** (Lucía). Martina lo abandonó. Paula lo sigue usando, pero lo revisa 10 min o más cada vez. La palanca está dentro de Teams y es la más directa: un recap que separe lo decidido de lo propuesto, con responsable y fecha, que el líder valide antes de publicarlo y que incorpore el contexto del artefacto compartido.

> Evidencia: "El recap resume todo al mismo nivel. Dos páginas. No distingues qué se decidió de qué se comentó." — Javier Molina (el equipo de México leyó "se habló de la API de geocercas" y entendió que no era prioridad)
>
> "Marca como decisión cosas que eran solo ideas. […] Es trabajo que yo pensaba que me estaba ahorrando." — Paula Benítez
>
> "No ve lo que pasó en el FigJam, solo lo que se habló. […] El resumen decía algo como 'se discutieron prioridades'. Pues sí, gracias." — Valeria Castro

**Recurrencia:** 6/6 de quienes lo usan (Javier, Martina, Diego, Paula, Valeria, Lucía).

## 3. La pizarra nativa se abandona porque es lenta y no permite votar ni agrupar, y sobre todo porque se pierde: queda atada a la instancia de la reunión

5 de los 10 probaron la pizarra de Teams y la dejaron (Javier, Tomás, Sofía, Lucía, Ricardo). Los motivos funcionales se repiten: es lenta con 9–14 personas, no tiene votación, no permite agrupar ni trae plantillas. El motivo decisivo es otro: **3 no la volvieron a encontrar** cuando se recreó la serie o se armó una convocatoria nueva (Tomás, Sofía, Lucía). Paula tiene el mismo problema con las notas de la reunión cuando reprograma. Perder el tablero significó perder los acuerdos: Tomás y Lucía terminaron rediscutiéndolos o reconstruyéndolos de memoria, con una tarea que quedó sin responsable. Lo que retiene a la gente en Miro es justamente la **continuidad**: un solo tablero por trimestre (Tomás) o el mismo tablero desde hace años (Javier). Por eso la persistencia (que el tablero o las notas vivan en la serie, el canal o el equipo, sobrevivan a una reprogramación y se encuentren) es requisito previo a cualquier mejora de la pizarra. Pesa más en cuentas con compliance, donde lo nativo es la única opción.

> Evidencia: "Fui a buscarla y no estaba. Quedó colgada del chat de esa reunión, y justo en el medio se había recreado la serie de la reunión […]. Perdí los acuerdos, así de simple." — Tomás Aguirre
>
> "Por compliance, cualquier herramienta externa con datos de clientes está prohibida. […] Lo nativo es lo único que tengo. Necesito que funcione mejor." — Lucía Fernández (perdió la pizarra entre dos sesiones y ahora hace una captura y la pega en Confluence)
>
> "Esa continuidad es la razón por la que estamos en Miro. Si tuviera que empezar de cero cada vez, perdería el hilo." — Tomás Aguirre

**Recurrencia:** 5/10 la abandonaron, 4/10 perdieron un artefacto nativo y 3/10 no sabían que existía alguna función nativa (Valeria la pizarra, Andrés las notas, Ricardo las apps dentro de la reunión).

## 4. Con la pantalla compartida nadie puede señalar, todo pasa por un solo conductor, y eso cuesta minutos y errores

En la mitad de las reuniones descritas, el grupo trabaja sobre la pantalla de una sola persona (un Excel, Jira, Figma o Power BI). Los demás no pueden señalar ni editar, así que dictan. Cada reunión pierde varias rondas de "no, la de abajo" (Andrés, Tomás, Valeria, Diego), y eso produce errores reales: Andrés cerró el ticket equivocado y al cliente le llegó la notificación de cierre. Además, 5 líderes terminan transcribiendo lo que les dictan otros por voz o por chat (Martina, Andrés, Tomás, Javier, Lucía). La necesidad es que los espectadores puedan apuntar o marcar sobre el contenido compartido sin tomar el control. Es una mejora acotada y no exige sacar el artefacto de donde vive.

> Evidencia: "Alguien me dice 'la fila 43', y yo me voy a la 43, y 'no, no, la de abajo, la del cliente de Lima'. […] Hace como un mes y medio cerré un ticket que no era." — Andrés Quintero
>
> "Si pudieran apuntar con algo, me dirían 'esta' y listo. Pero no, todo pasa por mí." — Andrés Quintero
>
> "Nadie puede señalar. Entonces es 'el botón de arriba, no, el otro, el de la derecha, más abajo'." — Valeria Castro

**Recurrencia:** 4/10 con el problema de señalar y 5/10 con el patrón de dictar al conductor.

## 5. Las voces silenciosas no llegan a la decisión: el voto se cuenta a mano y el líder termina decidiendo solo

En 6 de las 10 reuniones la discusión se traba y el líder decide solo porque se acaba el tiempo (Javier, Martina, Tomás, Andrés, Sofía, Lucía). Los perfiles nuevos, de otro idioma o de otro huso horario casi no hablan (Martina, Andrés, Sofía, Ricardo), y las objeciones llegan tarde. Gloria, por ejemplo, no pudo entrar al tablero y planteó su objeción una semana después, en un café. Votar con reacciones y contar a mano no da confianza (Andrés, Lucía, Ricardo), y en FigJam nada impide votar dos veces (Valeria). Hace falta un mecanismo liviano dentro de la reunión: priorizar con votos limitados y conteo automático, y dejar un canal para objeciones que no dependa de hablar. **Contrapunto:** Paula y Ricardo sostienen que las reuniones grandes no deben decidir, porque las decisiones de verdad se toman en reuniones de 3 o 4 personas. Por eso tiene menor prioridad que los insights 1 y 2.

> Evidencia: "No hay forma de que cada uno marque su prioridad sin que se transforme en conversación. Hablamos veinte minutos. Al final decidí yo." — Martina Rojas
>
> "La gente que no entra al tablero no es poca. En casi todas hay alguien mirando desde afuera, y esa gente no opina. Eso me preocupa más que los minutos." — Valeria Castro
>
> "Contar reacciones de nueve personas con la mitad sin cámara... a ver, funciona, pero no te fías del todo del número." — Lucía Fernández

**Recurrencia:** 6/10 deciden solos tras trabarse, 4/10 tienen participantes que casi no intervienen y 3/10 cuentan los votos a mano.

## Síntesis entre entrevistas

| Tema | Javier | Martina | Diego | Tomás | Andrés | Sofía | Paula | Valeria | Lucía | Ricardo | Total |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1. Decisión perdida o cierre manual | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | 10 |
| 2. El recap de IA no sirve para decisiones | ● | ● | ● | | | | ● | ● | ● | | 6 |
| 3. Pizarra nativa abandonada o perdida | ● | | | ● | | ● | ○ notas | | ● | ● | 5 (+1) |
| 4. No poder señalar o dictar al conductor | ● | ● | ● | ● | ● | | | ● | ● | | 7 |
| 5. Voces silenciosas o voto a mano | ● | ● | | ● | ● | ● | | ● | ● | ● | 8 |
| Acceso al artefacto externo de 5 min o más | ● | | | ● | | | | ● | | | 3 |

**El artefacto ya existía antes de la reunión en 7 de 10 casos** (Jira, Power BI, el Excel en SharePoint, el PRD en Confluence, los tableros de Miro de cada trimestre). Se creó para la reunión solo en 3: el FigJam de Valeria, el Google Doc del kickoff de Sofía y la pizarra de Lucía. Esto coincide con la encuesta (51% preexistente).

## Señales que no llegan a insight

- **Acceso: casos concretos, sin medida de frecuencia.** La guía deja el costo de acceso fuera de alcance y pide anotarlo sin profundizar, así que estas entrevistas no permiten concluir que duela poco. La medida válida es la de la encuesta (6% tarda 10 minutos o más y 27% tarda 5 o más). 3 de 10 contaron por su cuenta que pierden 5 minutos o más al arrancar: Javier más de 10 (instancias de Miro por país), Tomás 5–7 (invitados sin licencia) y Valeria 6–8 (cuentas personales de Google). Con SSO, Martina y Diego entran sin fricción. Javier sostiene que el costo real es **saltar entre ventanas durante las dos horas**, no el acceso. El efecto más serio del acceso es la exclusión (Gloria, Karla, los de Lyon), que alimenta el insight 5.
- **Desalineación sobre datos.** Diego perdió entre 10 y 15 minutos porque cada participante tenía un filtro distinto en Power BI. Es un caso único, pero muestra que "ver lo mismo" no está resuelto ni siquiera cuando el acceso funciona.
- **Demasiadas reuniones.** Ricardo tiene 27 h semanales de reuniones y Andrés dice que su reunión de 1 h 30 "debería durar cuarenta minutos". Ambos lo atribuyen al tema de esta investigación o a la cantidad de reuniones, no a las funciones.
- **La auditoría exige el correo** (Lucía): "si está en el correo, existe". Cualquier registro de decisiones tiene que poder salir hacia el correo o un sistema de registro.
- **Liderazgo sin herramienta.** Tres entrevistados derivaron a líderes que conducen reuniones sin artefactos (Fernanda, Carla, Mariana), y Ricardo y Paula operan así. Es un perfil a entrevistar para ver cómo cierran las decisiones sin un registro escrito.

## Calidad y límites

- **Exageración en la encuesta.** Tomás admitió haber marcado "salgo de Teams en todas las reuniones" sin que sea cierto. Es coherente con el sesgo del panel en Q1 que detectó la encuesta.
- **Respuestas casi idénticas.** R-170 (Andrés), R-196 (Ricardo) y R-224 (Martina) estaban en los pares de textos abiertos casi idénticos que marcó la encuesta. Las entrevistas no muestran señales de que sean personas falsas.
- **Diego Paredes (R-036)** no es la persona sintética del mismo nombre: es un Data Team Lead de una insurtech, no el fundador de una agencia. La alerta queda resuelta.
- **Fecha inconsistente.** Paula habla del "review de noviembre" en una entrevista del 26 de octubre. Probablemente quiso decir octubre; no cambia el insight.
- **Guía usada.** Las entrevistas siguieron `2026-10-21-2030-colaboracion-en-vivo-fuera-de-teams.md`, que es la que citan las transcripciones. `2026-10-27-1159-trabajo-conjunto-en-reuniones.md` es de una ronda posterior, con otras preguntas, y no sirve para evaluar estas entrevistas.
- **Funciones nativas sin nombrar.** La guía prohíbe nombrar primero las funciones de Teams, así que los 5 que abandonaron la pizarra probablemente sean un piso. Quien no la mencionó no necesariamente no la probó.
- **Base chica.** Con n=10, las recurrencias marcan la dirección, no la frecuencia. El segmento con compliance tiene una sola entrevista (Lucía).
- **Cobertura del segmento.** Los 10 trabajan en empresas tecnológicas de 650 a 2.000 empleados con operación en 3 o más países, como pedía el perfil de la guía. Estos hallazgos no dicen nada sobre cuentas de menos de 100 licencias ni sobre otros sectores.
