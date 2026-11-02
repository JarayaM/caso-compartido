---
opportunity: decisiones-perdidas-tras-la-reunion
status: testing-several
chosen: decision-fijada-en-vivo, cierre-tres-minutos
---

# Soluciones para: lo decidido se pierde entre la reunión y el trabajo

## Qué dice hoy la evidencia
- #8 se sostiene sin prueba independiente: 7/10 dedican 10–60 min (2 casos son plannings trimestrales), 6/10 lo viven como problema y 4/10 lo normalizan. El tema se preguntó directamente y la muestra son tecnológicas de 650 a 2.000 empleados (real, n=10).
- #11 solo tiene evidencia indirecta: 7 relatos contados por quienes conducen. El 2026-11-02 se decidió no entrevistar a quienes ejecutan.
- #12 no tiene evidencia: nadie mencionó Max ni el precio.
- Toda la evidencia es sobre el problema. Lo más cercano a una solución es el uso del resumen de IA (36%, survey) y lo que algunos líderes hacen a mano.
- Pendiente: datos del producto sobre uso y corrección del resumen (2026-11-15).

## Línea base: lo que hacen hoy
Quien conduce reconstruye lo decidido a mano, casi siempre después de la reunión (real, n=10; product/interviews/ y product/insights/2026-11-02-1357-contraste-creencias.md):

- Javier reescribe el recap (30 min).
- Tomás crea un ticket por acuerdo en Jira (20 min).
- Diego envía un correo con los acuerdos (20 min).
- Lucía escribe en el chat en vivo y luego pasa a Jira y correo (30 min).
- Paula corrige el resumen de IA (10 min o más).
- Sofía mantiene una sección "Decisiones" en el PRD (un par de minutos).
- Martina no hace nada: el qué queda en Jira y el porqué se pierde.
- Ricardo no hace nada: lo dicho se queda en la llamada.

Cuando el paso se atrasa u omite aparece el costo (los 3 días de campaña de Diego, el SPEI de Sofía). En la encuesta, 24% marca "no quedó registrado" y 23% lo dejó en un chat fuera de Teams (survey, Q9, n=182).

## Alternativas

### A1. Decisión fijada en vivo (`decision-fijada-en-vivo`)
Durante la reunión, alguien marca una decisión con responsable, fecha y motivo, y esta se publica donde vive el trabajo (Jira, canal, correo, Confluence). Ataca la captura y la entrega. Para Felipe Ortega y Camila Herrera (primary, derivadas) y Elena Vidal (primary, derivada, confianza baja). Reemplaza la reconstrucción posterior y el paso manual a otros sistemas.

### A2. Resumen de IA validado (`resumen-ia-validado`)
El resumen separa lo decidido de lo propuesto, propone responsable y fecha, y el líder lo aprueba antes de publicarlo. Ataca los minutos de reconstrucción y la confianza en el registro. Para Hernán Cáceres (secondary, derivada), Valentina Rojas (primary, sintética) y Felipe Ortega. Reemplaza escribir el recap desde cero o corregirlo sin guía.

### A3. Cierre de tres minutos (`cierre-tres-minutos`)
Práctica sin software: antes de terminar, quien conduce lee cada decisión con su responsable y fecha, y el grupo confirma. Queda escrita en el chat con una plantilla, y Teams solo la difunde como guía. Ataca el responsable ambiguo y que cada uno salga con su versión. Para Valentina Rojas, Felipe Ortega y Hernán Cáceres. Reemplaza la suposición de que todos entendieron lo mismo; no elimina el traspaso a Jira.

### A4. Registro de decisiones de la serie (`registro-decisiones-serie`)
Lugar persistente por serie de reuniones o canal, que sobrevive a una reprogramación y permite buscar qué se decidió y por qué. Ataca el porqué perdido, las discusiones que se reabren y lo que no se vuelve a encontrar. Para Martín Aguirre (secondary, sintética), Felipe Ortega y Elena Vidal. Reemplaza buscar en hilos, capturas y la grabación.

### A5. Registrador rotativo (`registrador-rotativo`)
Práctica sin software: una persona distinta de quien conduce toma las decisiones con una plantilla y las publica al terminar. Ataca el costo de moderar y escribir a la vez. Para Elena Vidal, Hernán Cáceres y Camila Herrera. Reemplaza el trabajo en solitario del líder.

## Comparación

Fuentes: [contraste] product/insights/2026-11-02-1357-contraste-creencias.md · [entrevistas] product/insights/2026-10-28-1124-entrevistas-trabajo-conjunto-en-reuniones.md · [encuesta] product/insights/2026-10-28-1045-colaboracion-en-vivo-fuera-de-teams.md · [research] product/research/2026-10-20-1349-colaboracion-en-reuniones.md

| Alternativa | Desirable | Feasible | Viable | Riskiest belief |
|---|---|---|---|---|
| A1 | mixed: pain evidenced, relief not tested. Martina lo pide y Lucía hace algo parecido en el chat, pero le cuesta moderar a la vez (real, n=1 cada una; product/interviews/) | to check with tech: conectores con Jira, Slack y Confluence; salida por correo para auditoría (real, Lucía) | unknown: sin evidencia sobre Max. Menos cubierta por Copilot (assumption), aunque Facilitator toma notas y propone tareas (secondary, [research]) | Se puede registrar responsable, fecha y motivo durante la reunión sin perder el hilo de la conducción |
| A2 | mixed: pain evidenced, relief not tested. Sustituto en uso (36%, survey, [encuesta]), pero 0 de 6 confían en él sin corregirlo (real, [entrevistas]) | to check with tech: distinguir lo decidido de lo propuesto; leer lo que pasa fuera de la voz | weak: el recap viene con Teams Premium o Copilot, y Facilitator requiere Copilot (secondary, [research]) | Validar el borrador toma menos que reconstruir, y el líder lo publica sin reescribirlo |
| A3 | mixed: pain evidenced, relief not tested. Responsable ambiguo en Andrés y Lucía; cada uno con su versión en Ricardo (real, [entrevistas]). En contra, varios deciden solos cuando se acaba el tiempo (real, [entrevistas]) | strong: no requiere desarrollo y Lucía ya escribe en el chat en vivo (real, product/interviews/) | weak: una práctica gratuita no da razones para pagar USD 8 más (assumption) | Quien conduce mantiene el cierre aunque la reunión vaya pasada de hora |
| A4 | mixed: pain evidenced, relief not tested. La continuidad retiene a Tomás en Miro (real, [entrevistas]). En contra, el destino real es Jira, correo, Slack o Confluence (real, [contraste]) | to check with tech: hoy pizarras y notas quedan atadas a la instancia (real, [entrevistas]) | unknown: la auditoría podría pesar; un caso real (Lucía) y una persona sintética (Rodrigo, synthetic) | Quien necesita una decisión la busca en ese registro, y no en Jira o preguntando |
| A5 | mixed: pain evidenced, relief not tested. Micaela y el hilo de Slack existen, pero Paula y Javier siguen haciendo el trabajo final (real, product/interviews/) | strong: no requiere desarrollo | weak: no aporta razón para subir a Max (assumption) | Alguien que no conduce acepta el rol y registra el motivo y el responsable con fidelidad |

## Decisión
El usuario eligió probar A1 y A3 en paralelo (2026-11-02), en línea con la recomendación. A1 es la candidata principal: es la única que cubre qué, quién, para cuándo, por qué y entrega. A3 es la prueba de control: si una práctica alivia el dolor, quizá no haga falta construir.

Esto no resuelve #12. A1 no se puede defender como palanca de Max hasta tener el conteo de Ventas y las conversaciones con IT (2026-11-30).

Qué cambiaría esta decisión:
- Si A3 alivia el dolor por sí sola, no conviene construir A1 sin una razón fuerte de Max. Se publicaría como práctica recomendada.
- Si A1 falla porque nadie puede registrar y moderar a la vez, se evalúa un híbrido donde la IA propone en vivo y una persona confirma. A2 volvería a estar en juego.
- Si Ventas e IT dicen que esto ya es parte de Copilot, ninguna alternativa con desarrollo sirve para el objetivo de Max, y se replantea la oportunidad.

## A probar
- A1 — "Se puede registrar responsable, fecha y motivo durante la reunión sin perder el hilo de la conducción": si es falso, la captura vuelve a quedar para después y A1 no supera la línea base. Lucía ya reporta ese costo. Se diseña en /design-solution-tests.
- A3 — "Quien conduce mantiene el cierre aunque la reunión vaya pasada de hora": si es falso, la práctica no ocurre justo en las reuniones que más la necesitan. Varios entrevistados deciden solos cuando se acaba el tiempo. Se diseña en /design-solution-tests.
- Entre ambas — si A3 por sí sola reduce las fallas de responsable y de versión tanto como A1: es lo que define si vale la pena construir.

## Propuesta de valor: A1. Decisión fijada en vivo
Para Felipe Ortega y Camila Herrera (primary, derivadas), y Elena Vidal (primary, derivada, confianza baja).
- **Dolor que alivia:** 7/10 dedican 10–60 min a reconstruir lo decidido (real, [contraste]). "Es trabajo mío, nadie más lo hace. Y si no lo hago, vuelve a pasar" (Javier). "El qué queda en Jira. El problema es el por qué" (Martina).
- **Beneficio que crea:** salir de la reunión con lo decidido ya publicado donde se trabaja, con su motivo y sin un segundo turno de trabajo.
- **Reemplaza:** la reconstrucción posterior y el paso manual a Jira, correo o Slack. Se cambiaría porque evita el doble trabajo y porque lo fijado se ve antes de terminar la reunión.
- **Deliberadamente no hace:** no reemplaza a Jira ni a Confluence, no resume la conversación, no detecta decisiones con IA, no ayuda a votar o priorizar, y no cubre invitados externos.

## Propuesta de valor: A3. Cierre de tres minutos
Para Valentina Rojas (primary, sintética), Felipe Ortega (primary, derivada) y Hernán Cáceres (secondary, derivada).
- **Dolor que alivia:** el responsable ambiguo y las versiones distintas: una incidencia una semana sin dueño (Lucía), un cliente 4 días esperando (Andrés), "cada uno se fue con su versión y nadie lo escribió" (Ricardo) (real, [entrevistas]).
- **Beneficio que crea:** todos salen con la misma versión, y las objeciones aparecen antes de cerrar y no una semana después.
- **Reemplaza:** la suposición de que todos entendieron lo mismo. Se cambiaría porque cuesta tres minutos y ninguna herramienta nueva.
- **Deliberadamente no hace:** no publica en Jira ni elimina el traspaso, no llega por sí sola a quien no asistió, y no captura decisiones tomadas en hilos fuera de la reunión.

## Creencias
Referencias al registro:
- [opportunity: decisiones-perdidas-tras-la-reunion] [value] #8 Quien conduce dedica 10 minutos o más por reunión a reconstruir lo decidido y quiere resolverlo.
- [opportunity: decisiones-perdidas-tras-la-reunion] [value] #11 Quien recibe o ejecuta actúa sobre una versión incompleta o tardía de lo decidido, y eso le cuesta retrabajo o preguntar de nuevo.
- [opportunity: decisiones-perdidas-tras-la-reunion] [viability] #12 En cuentas de 100 o más licencias, resolver esto es razón suficiente para considerar Max, y el valor no queda ya cubierto por Copilot.

Registradas en product/overview.md el 2026-11-02:
- #13 [feature: decision-fijada-en-vivo] [usability] Quien conduce puede registrar responsable, fecha y motivo durante la reunión sin perder el hilo de la conducción. Se refuta si la mayoría deja la captura para después o dice que perdió el hilo por registrar.
- #14 [feature: decision-fijada-en-vivo] [value] Lo fijado en vivo reduce el trabajo posterior de quien conduce y quien recibe sabe qué hacer sin preguntar de nuevo. Se refuta si quien conduce sigue reescribiendo lo publicado, o si quien recibe sigue preguntando qué se decidió, quién lo hace o por qué.
- #15 [feature: cierre-tres-minutos] [usability] Quien conduce mantiene el cierre aunque la reunión vaya pasada de hora. Se refuta si la mayoría lo omite cuando falta tiempo.
- #16 [feature: cierre-tres-minutos] [value] El cierre leído y confirmado reduce las fallas de responsable y de versión sin necesidad de software nuevo. Se refuta si siguen apareciendo responsables ambiguos o versiones distintas en las reuniones donde se hizo.

Solo en este archivo, pendiente de revisión técnica:
- [feature: decision-fijada-en-vivo] [feasibility] Se puede publicar en Jira, Confluence, Slack y correo dentro de las restricciones de seguridad y privacidad de las cuentas, incluidas las reguladas. Se refuta si tech o IT confirma que esos destinos requieren aprobaciones que no se pueden obtener para las cuentas del segmento.

## Descartadas o en pausa
- A2 — parked: tiene `weak` en Viable y Microsoft ya avanza por ese camino con Copilot y Facilitator. Volvería si los datos del 2026-11-15 muestran mucho uso y edición del resumen, y Ventas o IT no lo ven como parte de Copilot.
- A4 — parked: no resuelve la captura y el destino real del trabajo está fuera de Teams. Volvería si la auditoría aparece como motivo para Max en cuentas reguladas.
- A5 — discarded: no aporta a Max y, según lo que hacen Paula y Javier, no libera a quien conduce. Si en la prueba de A3 alguien delega el cierre, se registra como dato.

## Resultado
Pendiente de /analyze-solution-tests.
