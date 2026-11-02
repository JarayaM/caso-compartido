---
date: 2026-11-02
source: real, survey
opportunity: colaboracion-fuera-de-teams
sources:
  - product/interviews/ (10 transcripciones completas, real)
  - product/surveys/2026-10-25-1800-respuestas-colaboracion-en-vivo-fuera-de-teams.csv (210 completas, 182 que salen; sin la columna de contacto R4)
  - product/interview-guides/2026-10-21-2030-colaboracion-en-vivo-fuera-de-teams.md
  - product/surveys/2026-10-21-1944-colaboracion-en-vivo-fuera-de-teams.md
beliefs: product/overview.md (#1 a #8)
---

# Contraste de creencias con las transcripciones y el CSV

**Método.** Leí las 10 transcripciones completas, recalculé la encuesta desde el CSV, codifiqué las 95 respuestas de Q11 y crucé lo que cada entrevistado marcó en la encuesta con lo que contó. Apliqué los criterios de refutación escritos en cada creencia.

## Resultado

| # | Creencia | Veredicto | Razón principal |
|---|---|---|---|
| 1 | Salen porque lo nativo no sirve | **Refutada como explicación general; se sostiene solo en pizarras** | De los 6 entrevistados que salen, 4 lo hacen porque ahí vive el trabajo o es su estándar |
| 2 | Pierden ≥10 min y quieren resolverlo | **Dividida: refutada en acceso, se sostiene en el después** | 6% tarda ≥10 min en entrar; 7/10 dedican ≥10 min, casi todo después de la reunión |
| 3 | La colaboración justifica subir a Max | **Sin evidencia** | Nadie menciona Max ni el precio; 4/10 dicen por su cuenta que no necesitan más herramientas |
| 4 | La subida depende de los Team Leads | **Sin evidencia sobre el pago** | Nadie reclama capacidades, pero 8/10 desconocen alguna función |
| 5 | Teams se usa porque es obligatorio | **No contrastable** | La muestra y el ancla de la guía se limitan a reuniones de Teams |
| 6 | Prefieren menos reuniones a más funciones | **No contrastable; señal débil** | Nadie tuvo que elegir; 1/10 lo afirma con claridad |
| 7 | Las bajas se concentran en cuentas chicas | **No contrastable** | No hay datos de bajas ni cuentas chicas |
| 8 | Se pierde lo decidido, cuesta ≥10 min y se quiere resolver | **Se sostiene en esta muestra, sin prueba independiente** | 10/10 recuerdan un caso, pero se les preguntó directamente, y 6/10 lo viven como problema |

## #1. Las herramientas nativas no sirven

**Criterio:** la guía la da por equivocada si la razón es "así se hace", "el tablero ya estaba ahí" o nunca probaron nada y no saben qué hay. La creencia pasa a ser un problema de descubrimiento si no las conocen.

**Los 6 entrevistados que salen de Teams (según Q1):**

| Persona | Herramienta | Por qué está ahí | ¿Probó la pizarra? |
|---|---|---|---|
| Javier | Miro y Slido | Lo trajo su antecesor; Slido para votar | Sí, falló: sin votación, lenta |
| Tomás | Miro | Continuidad entre retros | Sí, falló y se perdió |
| Martina | Jira, Grafana; Miro en la retro | "Ahí vive todo" | No |
| Diego | Power BI | El dashboard es el sistema del equipo | No; en Q10 no sabía que existía |
| Sofía | Confluence; Google Doc en kickoffs | "No hay otra opción"; acceso de comercial | Sí, en un taller: lenta y se perdió |
| Valeria | FigJam | "Lo que usamos en diseño para todo" | Solo una vez, abierta por un compañero |

**Solo en 2 de 6 (Javier y Tomás)** la falla de lo nativo explica el uso externo, y aun así no es el único motivo. Los otros 4 cumplen el criterio de "ahí vive todo" o "así se hace". Sofía probó la pizarra, pero no es la razón por la que usa Confluence.

**Los otros 4 no salen (Q1 = "En ninguna"):** Lucía lo tiene prohibido y usa la pizarra aunque le falla; Paula usa las notas y le funcionan; Andrés y Ricardo no necesitan más que Excel o la voz.

**Encuesta:** el 51% trabaja en un artefacto que ya existía (92/182). Solo en pizarras la creencia se sostiene: de 61 usuarios, 36 (59%) probaron Whiteboard y la dejaron, y 3 (5%) no la conocían. Las pizarras son el 34% de los que salen.

**Descubrimiento, más amplio de lo que decía el análisis.** En las entrevistas, 3 de 10 revelan no conocer alguna función. Pero según sus respuestas en Q10, **8 de 10 desconocían al menos una** (todos menos Tomás y Paula). Sobre el total, 31% no conoce las notas y 40% no conoce las apps.

**Resta por saber:** el 27% conoce Whiteboard y nunca la usó, y no se sabe por qué.

## #2. Pierden ≥10 min por reunión y quieren resolverlo

**Criterio:** se refuta si la mayoría reporta menos de 10 minutos o dice que el flujo con Miro o Docs funciona bien.

**Durante la reunión: refutada.**
- Acceso (Q6): 87% tarda menos de 10 minutos y 6% tarda 10 o más (11/182). En reuniones sin externos es el 4% (6/137).
- Cambio de herramienta: la encuesta no lo mide y solo Javier lo trae como costo.
- Trabajo en la herramienta: se elogia. Tomás: "funciona muy bien"; Martina, sobre Miro: "funciona bien"; Sofía, sobre el Google Doc: "funciona muy bien".

**Después de la reunión: se sostiene en la muestra.**

| Dedica ≥10 min (7/10) | Dedica menos (3/10) |
|---|---|
| Valeria, casi 1 h · Javier 30 · Andrés 30+ · Lucía 30 · Diego 20 · Tomás 20 · Paula 10+ | Sofía, un par de minutos · Martina, "queda solo" en Jira · Ricardo, nada |

**Dos matices.** Javier y Valeria describen plannings trimestrales, así que ese tiempo no se repite en cada reunión. El destino tampoco es Teams, como dice la creencia, sino Jira, correo, Slack o Confluence (Javier también lo publica en el canal de Teams).

**¿Lo viven como problema?** La guía de la ronda siguiente pide mirar lo que hicieron, no lo que opinan.
- **Sí, 6/10:** Javier reescribe el recap ("si no lo hago, vuelve a pasar"); Martina dejó Copilot y pide algo que cierre; Sofía ("lo que nos falla es cómo se cierra"); Lucía hace capturas por falta de algo mejor; Andrés ("el correo no sirve tanto"); Valeria se dedica casi una hora tras una reunión.
- **Lo normalizan o lo atribuyen a otra cosa, 4/10:** Diego ("es disciplina", "a mí no me falta nada en Teams"); Tomás ("medio ridículo, pero funciona"); Paula ("no es terrible"); Ricardo (cree que el problema es de cantidad de gente y reuniones).

Sofía también oscila: dice que el proceso no falló y luego reconoce el problema.

## #3. La colaboración justifica subir a Max

Ningún entrevistado ni respuesta de Q11 menciona Max, el precio del plan o una razón para subir, y ninguno de los instrumentos lo preguntó. Hay una señal débil en contra: 4/10 dicen por su cuenta que no necesitan más (Martina: "no veo para qué querría otra herramienta"; Diego, Paula y Ricardo, en términos parecidos). Lucía va en el sentido contrario: "lo nativo es lo único que tengo". También hay un motivo no previsto: Tomás probó la pizarra para ahorrar licencias de Miro. Sigue dependiendo de Ventas y de IT.

## #4. La subida depende de los Team Leads

La creencia tiene dos partes:
- **"Hoy no reclaman capacidades":** es coherente con los datos, pero con otra causa posible. 8/10 desconocen alguna función y 4/10 no sienten falta.
- **"IT pagaría si reclamaran":** no se probó. Los líderes sí eligen herramientas (Javier y Slido, Valeria y FigJam), pero en cuentas reguladas seguridad y compliance bloquean lo externo durante meses (Lucía, R-126, R-173, R-190). Eso muestra quién decide sobre herramientas externas, no sobre el plan de Teams.

## #5. Teams se sostiene porque las reuniones son obligatorias

Nadie habla de obligación, pero tampoco se preguntó: la guía ancla en reuniones de Teams y deja fuera a quien mudó la reunión. Hay indicios de que el trabajo se va a otras herramientas de chat: el 23% dejó lo decidido en un chat fuera de Teams, Javier y Martina usan hilos de Slack, y Martina menciona a un manager que "hace todo por Slack".

## #6. Prefieren menos reuniones a más funciones

Solo Ricardo lo afirma con claridad ("Menos reuniones", 27 h por semana). En Q11 son unas 5 de 95 respuestas, 2 de ellas con texto idéntico (R-077 y R-196, esta última de Ricardo). Andrés apunta a otra cosa: su reunión debería durar 40 minutos, pero "es por todo esto que hablamos". Es decir, mejores funciones también podrían acortarla, así que la disyuntiva puede ser falsa. Paula, Ricardo, R-073 y R-207 sostienen además que las decisiones se toman en reuniones chicas.

## #7. Las bajas se concentran en cuentas chicas

No hay ningún dato: ni la encuesta ni las entrevistas miden bajas, y el perfil se limita a cuentas de 100 o más licencias. Hacen falta datos de renovación.

## #8. Se pierde lo decidido

**Criterio:** se refuta si la mayoría dedica menos de 10 minutos o no recuerda una decisión perdida, en una muestra que incluya cuentas chicas y otros sectores. **Esa muestra todavía no existe.**

- **Minutos:** 7/10 dedican 10 o más, con los matices de #2.
- **Recuerdo:** los 10 cuentan un caso, y Ricardo necesitó tiempo para recordarlo. En 8 hubo trabajo rehecho, clientes o presupuesto afectados (Javier, Diego, Andrés, Sofía, Paula, Valeria, Lucía, Ricardo). En 2 se volvió a discutir lo ya acordado (Martina y Tomás). El análisis original contaba 9.
- **Inducción:** las 10 entrevistas preguntan cómo quedó registrada la decisión, y casi todas piden después un caso de falla.
- **Encuesta:** es la categoría más mencionada en Q11, con 30 de 95 en sentido amplio. **22 de esas 30** hablan de lo decidido; las otras 8 hablan de continuidad o de encontrar material. Son el 14% de las 210 completas. Además, **Q11 pregunta por "llegar a una decisión"**, así que también orienta hacia el tema, aunque no hacia el registro.
- **"No quedó registrado" (Q9):** 24% (44/182), 26% entre quienes tomaron decisiones (44/170). Tres de cada cuatro sí lo registran en algún lado. Valeria marcó esa opción, pero en la entrevista cuenta que lo pasó a Jira: la cifra puede mezclar "no quedó nada" con "no quedó nada durante la reunión".
- **Atribución:** Sofía y Diego lo atribuyen en parte a disciplina, y Ricardo al tamaño de la reunión. Una herramienta no necesariamente lo resuelve.

## Lo que cambia en el análisis de entrevistas

| El análisis decía | Lo que muestran las fuentes |
|---|---|
| 5/10 abandonaron la pizarra | **4/10** (Javier, Tomás, Sofía, Ricardo). Lucía la perdió pero sigue usándola: "La uso en algunas reuniones" en Q10 |
| 3/10 no conocían alguna función | 3/10 lo revelan en la entrevista; **8/10** según Q10 |
| Artefacto preexistente en 7/10 | **6/10** en la reunión ancla (Javier, Martina, Diego, Tomás, Andrés, Sofía). Se crearon para la reunión en Valeria, Lucía y las notas de Paula; Ricardo no tiene artefacto. El kickoff de Sofía es otra reunión |
| 20–60 min por reunión | **10–60 min en 7/10**, y 3/10 no dedican ese tiempo |
| "Varios" dicen que nadie más lo hace | Lo dicen 3: Javier, Tomás y Valeria |
| 9 incidentes | 10 casos: 8 con costo concreto y 2 de rediscusión |
| El recap no sirve | No sirve como registro, pero tiene valor: a Paula le "ahorra un montón", Diego lo usa para acordarse y Lucía lo ve útil para quien no vino |

**La encuesta sí coincide.** Reproduje Q1 por canal, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10 y los cruces con externos y pizarras. Las cifras de `2026-10-28-1045` son correctas.

**Contradicciones entre encuesta y entrevista.** Javier marcó en Q4 que el tablero se creó para esa reunión, pero es el mismo desde hace años. Tomás admitió haber exagerado en Q1. Valeria marcó "no registrado" y luego lo pasó a Jira. Con 3 casos en 10, Q4 y Q9 podrían tener algo de error de medición.

## Implicancias

- **El reencuadre hacia el cierre sigue siendo razonable**, pero se apoya en evidencia preguntada de forma directa y en empresas tecnológicas de 650 a 2.000 empleados.
- **Falta lo decisivo para el negocio:** ninguna evidencia conecta el cierre con Max.
- **La guía `2026-10-27-1159` sirve para probar #8** si no pregunta primero por decisiones perdidas: su P4 pregunta qué pasó con lo producido y cuánto tomó. Conviene registrar si el tema surge sin preguntar.
