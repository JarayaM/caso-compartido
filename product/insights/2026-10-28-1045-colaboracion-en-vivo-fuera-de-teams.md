---
date: 2026-10-28
source: survey
survey: product/surveys/2026-10-21-1944-colaboracion-en-vivo-fuera-de-teams.md
results: product/surveys/2026-10-25-1800-respuestas-colaboracion-en-vivo-fuera-de-teams.csv
n: 210 completas (email 76, panel 134)
opportunity: colaboracion-fuera-de-teams
---

# Análisis de encuesta: trabajo colaborativo fuera de Teams en reuniones de más de 5 participantes

> **Revisión del 2026-11-02.** Las cifras se recalcularon desde el CSV y coinciden. Dos salvedades de lectura: las 30 menciones de "la decisión se pierde" en Q11 incluyen 8 sobre continuidad o material (22 en sentido estricto), y Q11 pregunta por "llegar a una decisión"; además, "No quedó registrado" (Q9) puede incluir a quienes lo registraron después (caso de R-024). Detalle en `product/insights/2026-11-02-1357-contraste-creencias.md`.

## Base y límites

| | Email (canal propio) | Panel B2B | Total |
|---|---|---|---|
| Completas | 76 | 134 (89% de la cuota de 150) | **210** |
| Descalificadas / parciales | 8 / 1 | 26 / 4 | 34 / 5 |
| Trabajaron fuera (Q1 ≠ "En ninguna") | 65 | 117 | **182** (meta ≥150 ✔) |
| "En ninguna" | 11 | 17 | **28** (meta ≥30 ✘ → direccional) |

- **Tasa de respuesta del email: no calculable.** El alcance nunca se confirmó. El email aportó 76 completas frente a las ~150 esperadas, así que la meta de ≥30 por canal se cumple, pero el balance previsto entre canales no.
- **Diferencia entre canales en Q1, coherente con el sesgo declarado.** En email, el 39% sale "en menos de la mitad" de sus reuniones (panel: 18%). Los que salen "en más de la mitad" o "en todas" son el 21% en email y el 39% en el panel. Es un hallazgo sobre la muestra: el canal propio sobrerrepresenta a quienes se quedan en Teams. **No se reporta una frecuencia agregada de salida.**
- **Lo demás es estable entre canales:** Q3, Q4, Q5, Q6 y Q7 difieren en pocos puntos entre email y panel. Esos hallazgos no parecen un efecto del canal.
- **Diferencias menores entre canales:** el email registra más decisiones en el chat o las notas de Teams (23% frente a 7%) y conoce más la IA en reuniones (solo el 5% no sabía que existía, frente al 16% del panel).
- **Calidad.** Hay 9 completas en menos de 90 segundos (4%), que se mantienen. Algunos textos abiertos se repiten casi iguales entre personas distintas (R-077/R-196, R-046/R-170, R-207/R-224); también se mantienen, con la nota. La firmografía del panel es autodeclarada (S3 y S4 filtraron 26).
- Los porcentajes del grupo "En ninguna" (n=28) son direccionales.

## O1. Origen del artefacto

**Creíamos:** el tablero o documento externo se crea para la reunión. Por eso el problema sería de colaboración en vivo.

**Los datos (n=182):**

| Q4: origen y vida del artefacto | n | % |
|---|---|---|
| Ya existía y se siguió usando | 92 | 51% |
| Se creó para la reunión y se siguió usando | 44 | 24% |
| Se creó para la reunión y no se volvió a usar | 28 | 15% |
| No lo sé | 13 | 7% |
| Ya existía y no se volvió a usar | 5 | 3% |

- Herramientas (Q2, opción múltiple): Google Docs/Sheets/Slides 32%, Jira 29%, Miro 20%, dashboards 16%, Confluence 14%, FigJam 12%, Notion 12%, Slido/Mentimeter 9%, Mural 9%, Lucidspark 4%. "Otra" quedó en 5% (ClickUp, Canva, Retrotool, Excel en SharePoint, Trello), así que la lista estaba bien.
- **Las pizarras son la excepción.** De los 61 que usaron Miro, Mural, FigJam o Lucidspark, 50 (82%) crearon el tablero para esa reunión. Jira, Confluence, los dashboards y Docs, en cambio, mayormente ya existían.

**Decisión:** la colaboración en vivo pura, con un artefacto que nace en la reunión, es sobre todo el caso de las pizarras: alrededor de un tercio de los que salen. Para la mayoría, el problema es de integración con los sistemas donde ya vive el trabajo.

## O2. Costo de acceso

**Creíamos:** pasan 5 minutos o más hasta que todos entran, y el problema es del Team Lead que conduce reuniones internas.

**Los datos (n=182):**

| Q6: hasta que todos estuvieron dentro | n | % |
|---|---|---|
| Menos de 1 min | 35 | 19% |
| 1 a 2 min | 49 | 27% |
| 3 a 4 min | 36 | 20% |
| 5 a 9 min | 39 | 21% |
| 10 min o más | 11 | 6% |
| No lo sé | 12 | 7% |

- **El umbral de 5 minutos se cumple solo en el 27%** y el de 10 minutos en el 6%.
- **Corte por externos (Q8):** con externos en la reunión, el 62% (24/39) tarda 5 min o más; sin externos, el 18% (24/137). La demora fuerte se concentra en reuniones con externos. Según la regla de decisión de O2, esa parte es de otro segmento (consultores y agencias, perfil Diego Paredes).
- **Exclusión (Q7): el 50% dejó al menos a 1 participante mirando la pantalla de otro.** Sin externos, el 46% (63/137) dejó al menos a 1 persona afuera; con externos, el 64% (25/39). La exclusión existe también en reuniones internas (perfil Martín Aguirre).
- **Cómo llegan (Q3):** pegando un enlace en el chat el 54%, ya lo tenían abierto el 22%, por pantalla compartida el 15% y como app dentro de Teams el 8%. **La telemetría de enlaces pegados en el chat ve más o menos la mitad del uso externo.** Las cifras del brief (29% y 38%) probablemente lo subestiman.

**Decisión:** el umbral de 5 minutos no se sostiene para las reuniones internas. El problema de acceso que sí es del segmento es la **exclusión** de participantes, no la demora.

## O3. Qué se hace fuera y dónde queda la decisión

**Creíamos:** se sale de Teams para hacer trabajo de pizarra.

**Los datos (Q5, n=182, opción múltiple):** votar o priorizar 40%, editar un documento entre varios 35%, revisar datos o métricas 34%, anotar decisiones o acuerdos 33%, aportar ideas 29%, actualizar tareas 25%, agrupar ideas 22%, dibujar diagramas 13%. "Otro" quedó en 5% (revisar incidentes ×3, planning poker o estimar ×3, roadmap ×2, presupuesto ×2).

**Dónde quedó lo decidido (Q9, n=182, opción múltiple):**

| | n | % |
|---|---|---|
| No quedó registrado en ningún lado | 44 | 24% |
| En un chat fuera de Teams | 42 | 23% |
| En Jira u otro gestor | 41 | 23% |
| Otro | 32 | **18%** |
| En la misma herramienta externa | 28 | 15% |
| En el chat o las notas de Teams | 23 | 13% |
| En un documento de actas | 21 | 12% |
| En un correo | 19 | 10% |
| No se tomaron decisiones | 12 | 7% |

- **"Otro" superó el umbral del 15%: la lista de Q9 estaba incompleta.** La categoría que faltaba era el **resumen de IA, el recap o la transcripción: 22 menciones (12%)**, a la par del chat o las notas de Teams. Cerca de la mitad de esas menciones trae una queja: "resume todo pero no distingue lo decidido" (R-097), "en el recap pero le faltaba quién hacía qué" (R-231), "en el resumen de IA, que nadie leyó" (R-025). Otras 4 menciones son de la grabación ("en la grabación, se supone", R-168).

**Decisión:** cualquier solución tiene que cubrir votar o priorizar y dejar la decisión registrada, no solo el lienzo. La capacidad de IA con más tracción potencial es **distinguir y registrar lo decidido**: hoy el recap ya ocupa ese lugar, pero lo hace mal.

## O4. Conocimiento y uso de lo nativo

**Creíamos (#1):** no usan lo nativo porque no les sirve, no porque no sepan que existe.

**Los datos (Q10, n=210):**

| | No sabía | Sabe, nunca la usó | La usó y la dejó | La usa (algunas o la mayoría de las reuniones) |
|---|---|---|---|---|
| Whiteboard | 8% | 27% | **43%** | 21% |
| Notas de la reunión (Loop) | **31%** | 28% | 14% | 27% |
| Apps dentro de la reunión | **40%** | 28% | 9% | 23% |
| Resumen o asistente de IA | 12% | 39% | 13% | 36% |

- **Whiteboard: el problema es "no me sirve".** Entre quienes usan pizarras externas (n=61), el 59% probó Whiteboard y la dejó. En Q11, los motivos son que le faltan votación, agrupación y plantillas (4 menciones), que el tablero no se vuelve a encontrar porque "está colgado del chat de esa reunión" (5), que no saben cómo abrirla en medio de la reunión (3) y que es lenta con muchos participantes (2).
- **Notas y apps dentro de la reunión: el problema es de descubrimiento.** El 31% y el 40% no sabían que existían. Hay una tensión llamativa: el 34% de los que salen usa pizarras externas, y el 40% no sabe que puede abrirlas dentro de la reunión.
- En el grupo "En ninguna" (n=28, direccional), el uso de Whiteboard no difiere del resto (25% frente a 21%).

**Decisión:** la creencia #1 vale para Whiteboard y no vale para las notas ni para las apps dentro de la reunión. En las notas y las apps, un trabajo de descubrimiento puede mover el uso sin construir nada nuevo.

## Q11, abierta: lo más difícil de trabajar juntos y decidir

95 de 210 respondieron. Una respuesta puede caer en más de un tema.

| Tema | Menciones | Citas |
|---|---|---|
| **La decisión se pierde: registro, seguimiento, continuidad entre reuniones** | **30** | "Que quede registro del POR QUÉ decidimos algo. El qué queda en Jira, el por qué se pierde" (R-207) · "Muchas veces creemos que decidimos y en realidad cada uno entendió algo distinto" (R-099) |
| Converger, votar, priorizar, cerrar | 12 | "Divergir es fácil, todos tiran ideas. Ordenarlas y elegir es lo que nos cuesta" (R-011) · "Usamos reacciones en el chat pero nadie sabe cuántos votaron ni qué ganó" (R-053) |
| Participación (hablan los mismos, cámaras apagadas, celular, facilitar y opinar a la vez) | 12 | "Hay 12 personas y opinan 3, el resto escucha o está en otra cosa" (R-049) |
| Whiteboard nativa: faltan funciones, no se encuentra, no se sabe abrir, es lenta | 12 | "Armé una retro en la whiteboard de Teams y a la semana siguiente no la pude encontrar para continuar. Volvimos a Miro" (R-089) |
| Acceso a la herramienta externa (externos 4, permisos, SSO, licencias por filial) | 11 | "Los permisos del Miro. Siempre hay alguien que no puede editar y pierde los primeros 10 minutos" (R-244) |
| Demasiadas reuniones o falta de tiempo | 5 | "Honestamente la mayoría de estas reuniones podrían ser un mail" (R-157) |
| Husos horarios e idioma | 4 | "Poner a todos de acuerdo con gente en 3 husos horarios" (R-228) |
| Compliance obliga a quedarse en Teams | 3 (+2 en Q12) | "Compliance no nos deja meter datos de clientes en Miro, así que o lo hacemos en Teams o no se hace. Y en Teams cuesta" (R-190) |
| Técnico (audio, memoria, conexión) | 3 | — |
| Sin problema o no aplica | 3 | "No hay problema real, funcionamos bien" (R-181) |

El tema de la decisión perdida también trae costo de trabajo posterior: "me paso casi una hora pasando lo del FigJam a Jira" (R-024), "me lleva media hora" armar el resumen (R-050).

**Q12, abierta (16 de los 28 que respondieron "En ninguna"):** 7 usan lo nativo de Teams (Forms, reacciones, notas, Whiteboard), 4 lo resuelven de palabra o a mano alzada, 2 comparten la pantalla de un Excel, 2 resuelven antes de la reunión de forma asíncrona y 1 decide en reuniones más chicas. 2 de ellos están en Teams por compliance (R-009 y R-143, una de España).

## Insights priorizados

1. **Alto. Lo que más duele es que la decisión se pierde, más que el acceso a la herramienta.**
   - *Evidencia:* es el tema más mencionado en Q11 (30 de 95). En el 24% de los casos la decisión no queda registrada y el 23% termina en un chat fuera de Teams; solo el 13% queda en Teams. El recap de IA ya ocupa el 12%, pero no separa lo decidido de lo conversado.
   - *Acción:* reconsiderar el alcance de la oportunidad, que había dejado este "problema vecino" fuera. Evaluar una capacidad de IA que registre lo decidido, con responsable y motivo.
   - *Por qué (para entrevistas):* qué le falta al recap para servir, y si perder la decisión se vive como problema o como costo normal.
2. **Alto. Una pizarra mejor cubre alrededor de un tercio de los que salen.**
   - *Evidencia:* el 51% trabaja en artefactos que ya existían (Jira, Confluence, dashboards, Docs). Las pizarras nacen para la reunión en el 82% de los casos, pero solo las usa el 34%.
   - *Acción:* comparar las alternativas "pizarra nativa mejor" e "integración con el artefacto existente" por cobertura.
3. **Alto. Hay dos problemas de acceso distintos.**
   - *Evidencia:* la demora de 5 minutos o más se concentra en reuniones con externos (62% frente a 18%). La exclusión de al menos 1 participante ocurre en el 46% de las reuniones internas.
   - *Acción:* separar el segmento externo (Diego). Para el segmento, medir la exclusión, no los minutos.
   - *Por qué (para entrevistas):* qué impide entrar en las reuniones internas (permisos, SSO, no ver el enlace, el celular).
4. **Medio. Whiteboard se abandona; las notas y las apps se desconocen.**
   - *Evidencia:* el 43% probó Whiteboard y la dejó. Los motivos son la falta de votación, agrupación y plantillas, y que el tablero no se vuelve a encontrar. Las notas (31%) y las apps dentro de la reunión (40%) no se conocen.
   - *Acción:* el descubrimiento de las apps dentro de la reunión es la palanca más barata. La persistencia y el hallazgo del tablero nativo son una brecha de producto concreta.
5. **Medio. La telemetría de enlaces ve alrededor de la mitad del uso externo.**
   - *Evidencia:* solo el 54% llegó a la herramienta por un enlace pegado en el chat.
   - *Acción:* corregir las señales de la oportunidad que se apoyan en esa telemetría (29% y 38%).
6. **Bajo, a vigilar. Compliance retiene uso en Teams.**
   - *Evidencia:* 5 menciones, 2 de España (EEE). Es el perfil de Rodrigo.
   - *Por qué (para entrevistas):* si para las cuentas reguladas lo nativo es la única opción, ¿cambia eso la viabilidad de Max?

## Pool de reclutamiento

- Aceptaron conversar 77.
- Se excluyen: IT (6), quienes conducen 0 o 1 reuniones por semana (7) y quienes no dejaron contacto (6: R-076, R-110, R-132, R-194, R-227, R-245).
- Quedan **58 candidatos con contacto**. La etiqueta sigue los criterios del diseño; se agregó "nunca probó Whiteboard" para la creencia #1.

**Primero, los que contradicen la creencia:**

- **"En ninguna"** (11): R-009 (compliance), R-143 (compliance, España), R-046, R-085, R-088, R-120, R-135, R-153 (usa IA y la corrige), R-170, R-196, R-242.
- **Artefacto preexistente, acceso rápido y nunca probó Whiteboard** (8): R-036, R-094, R-102, R-128, R-176, R-224, R-229, R-235.
- **Artefacto preexistente y acceso rápido** (7): R-057, R-131, R-144, R-151, R-180, R-234, R-240, R-247.
- **Acceso rápido y nunca probó Whiteboard** (3): R-074, R-090, R-173 (normativa europea).

**Después, los que confirman** (acceso de 5 minutos o más y abandonaron Whiteboard): R-031, R-077, R-097, R-103, R-113, R-205, R-228.

⚠ R-036 se llama igual que la persona sintética negativa "Diego Paredes" (`product/personas/diego-paredes.md`). Hay que verificar que sea una persona real antes de contactarla.

## Preguntas abiertas para entrevistas

- ¿Por qué el recap o resumen de IA no sirve para registrar decisiones? ¿Qué tendría que distinguir?
- ¿Perder la decisión se vive como problema por resolver o como costo normal? (Esto es parte de la creencia #2 y la encuesta no lo midió.)
- ¿Qué impide entrar a la herramienta en las reuniones internas?
- ¿Por qué no se descubren las apps dentro de la reunión, si un tercio usa justamente esas herramientas?
- En las cuentas con compliance, ¿lo nativo es la única opción? ¿Cuánto pesa eso en la decisión de IT?

## Limitaciones de redacción

- Q9 no tenía la opción "resumen de IA o recap", así que esa cifra sale de "Otro" y probablemente está subestimada.
- Q6 mide solo el acceso. No cubre el costo de cambiar de herramienta ni el de pasar los resultados de vuelta a Teams, que forman parte de la creencia #2.
