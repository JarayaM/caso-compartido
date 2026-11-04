---
opportunity: decisiones-perdidas-tras-la-reunion
solutions: product/solutions/2026-11-02-1453-decisiones-perdidas-tras-la-reunion.md
status: designed
---

# Pruebas de solución para: lo decidido se pierde entre la reunión y el trabajo

## Por qué probar
Se prueban A1 (decisión fijada en vivo) y A3 (cierre de tres minutos). La evidencia actual es sobre el problema: 7 de 10 dedican entre 10 y 60 minutos a reconstruir lo decidido. Nadie reaccionó a ninguna de las dos soluciones. Para A1, no se sabe si quien conduce puede registrar mientras modera, y Lucía dice que le cuesta. Para A3, no se sabe si el cierre sobrevive cuando se acaba el tiempo, que es justo cuando varios entrevistados terminan decidiendo solos.

## T1. decision-fijada-en-vivo: registrar en vivo en una reunión real
- **Test status:** ready
- **Belief under test:** #13 "Quien conduce puede registrar responsable, fecha y motivo durante la reunión sin perder el hilo de la conducción. Se refuta si la mayoría deja la captura para después o dice que perdió el hilo por registrar."
- **Risk:** [usability]
- **Test type:** usability-test
- **What we do:**
  1. Antes de la reunión, se hace una inducción de 10 minutos para mostrar la plantilla. No se ensaya.
  2. El líder conduce una reunión real suya de más de 5 personas en la que se va a decidir algo. Usa la plantilla cada vez que se toma una decisión.
  3. Un observador en silencio marca cada momento de decisión con un criterio fijo: alguien propone, nadie objeta y se pasa al tema siguiente. Para cada decisión anota si quedó registrada antes de terminar la reunión y con qué campos. También anota las pérdidas del hilo, que son tres eventos observables:
     - la conducción se detiene más de 10 segundos mientras el líder escribe;
     - otra persona tiene que retomar la conversación;
     - el líder pide que le repitan algo.
  4. Al terminar, hay un debrief de 10 minutos con preguntas factuales: "¿Hubo un momento en que perdiste el hilo por registrar? ¿Cuándo?" y "¿Qué dejaste para completar después?". No se pregunta si le gustó.
- **With whom:** 5 de los entrevistados reales, en cuentas de 100 o más licencias. Se priorizan quienes hoy reconstruyen después de la reunión. Propuesta: Javier, Tomás, Lucía, Paula y Martina. Se recontactan por el mismo canal de las entrevistas. Si aceptan menos de 4, el resultado es inconclusive.
- **Material needed:** una plantilla que funcione dentro de una reunión de Teams sin desarrollo (por ejemplo, un componente de tabla en el chat de la reunión). Tiene una fila por decisión con 4 campos: qué, responsable, para cuándo y por qué. Deja fuera a propósito la publicación en Jira, Slack o correo, cualquier IA, la votación y los invitados externos. Además, una hoja de captura para el observador con: hora de la decisión, hora del registro, campos completos, eventos de pérdida del hilo y respuestas del debrief.
- **Material:** [t1-decision-fijada-en-vivo](materials/t1-decision-fijada-en-vivo/): [plantilla e inducción](materials/t1-decision-fijada-en-vivo/plantilla-e-induccion.md), [hoja del observador](materials/t1-decision-fijada-en-vivo/hoja-observador.md), [mensaje de reclutamiento](materials/t1-decision-fijada-en-vivo/mensaje-reclutamiento.md)
- **Duration:** una reunión por líder (de 30 a 60 minutos) más 20 minutos entre la inducción y el debrief. Ventana del 2026-11-09 al 2026-11-20.
- **Signal and threshold:**
  - Captura en vivo: el porcentaje de decisiones registradas antes del fin de la reunión con los 4 campos. Un líder pasa con 80% o más.
  - Hilo: el líder no pierde el hilo si tiene como máximo 1 evento observado y responde "no" en el debrief.
  - **Pasa** si al menos 4 de 5 líderes cumplen las dos condiciones.
  - Si la reunión tiene menos de 2 decisiones, no cuenta y se reemplaza.
- **Decision rule:**
  - **continue** si al menos 4 de 5 cumplen las dos condiciones.
  - **change** si se registra en vivo, pero falla un campo de forma sistemática (por ejemplo, el motivo queda vacío en la mayoría) o pierden el hilo 2 de 5. En ese caso se reduce lo que se exige en vivo o se evalúa un híbrido donde la IA propone y el líder confirma, y A2 vuelve a estar en juego. La versión cambiada necesita su propia prueba.
  - **discard** si 3 o más de 5 dejan la captura para después (menos de 50% registrado en vivo) o pierden el hilo. Es la refutación tal como está registrada.
- **Expected provenance:** real
- **Next step if it passes:** probar la #14 [value] con un Wizard of Oz durante 2 semanas. Lo fijado en vivo se publica a mano detrás de escena en Jira, Slack o correo, y se miden dos cosas: los minutos posteriores del líder frente a su línea base de las entrevistas, y las preguntas de "¿qué se decidió?" que recibe.

## T2. cierre-tres-minutos: mantener el cierre cuando falta tiempo
- **Test status:** designed
- **Belief under test:** #15 "Quien conduce mantiene el cierre aunque la reunión vaya pasada de hora. Se refuta si la mayoría lo omite cuando falta tiempo."
- **Risk:** [usability]
- **Test type:** practice-trial (una práctica aplicada en reuniones reales, sin software nuevo)
- **What we do:**
  1. Se hace una inducción de 15 minutos con cada líder sobre el cierre: leer cada decisión con su responsable y su fecha, que el grupo confirme y pegar el resultado en el chat con la plantilla.
  2. Durante 2 semanas, el líder lo aplica en todas sus reuniones de más de 5 personas en las que se decide algo.
  3. Por cada reunión, el líder completa la hoja de registro en menos de 1 minuto. El cierre pegado en el chat, con su hora, sirve como verificación objetiva.
  4. A los 3 días se hace un control de 5 minutos para comprobar que el registro se está llevando.
- **With whom:** los otros 5 entrevistados reales. Ninguno participa en T1. Se priorizan los casos de responsable ambiguo o versiones distintas. Propuesta: Andrés, Ricardo, Sofía, Diego y Valeria. Si aceptan menos de 4, el resultado es inconclusive.
- **Material needed:**
  - La plantilla del cierre para el chat: una línea por decisión con qué, responsable, para cuándo, y "confirmado por el grupo: sí o no".
  - Un guion de 3 líneas para abrir el cierre.
  - Una hoja de registro por reunión con: fecha, hora de término prevista, hora de término real, si a 5 minutos del término todavía se discutía, si se hizo el cierre (completo, parcial o no), quién lo hizo y si se delegó (eso alimenta el dato de A5).
  - Deja fuera a propósito cualquier herramienta, recordatorio automático o publicación en Jira.
- **Material:** pendiente de /build-solution-test
- **Duration:** 2 semanas de práctica por líder. Ventana del 2026-11-09 al 2026-11-20.
- **Signal and threshold:**
  - Una reunión cuenta como "pasada de hora" si terminó después de lo previsto o si a 5 minutos del término todavía se discutía.
  - Señal: el porcentaje de esas reuniones en que se hizo el cierre completo (todas las decisiones leídas con responsable y fecha, y confirmadas).
  - **Pasa** con 70% o más.
  - Si en total hay menos de 8 reuniones pasadas de hora, el resultado es inconclusive.
- **Decision rule:**
  - **continue** si el cierre completo ocurre en 70% o más de las reuniones pasadas de hora.
  - **change** si ocurre entre 50% y 69%, o si aparece sobre todo como cierre parcial. En ese caso se mueve el cierre a un punto fijo antes del final (por ejemplo, el minuto 50 de 60) y se vuelve a probar.
  - **discard** si ocurre en menos de 50%. La mayoría lo omite cuando falta tiempo, que es la refutación tal como está registrada.
- **Expected provenance:** real
- **Next step if it passes:** probar la #16 [value]. A las 48 horas de cada reunión con cierre, se pregunta a 2 asistentes qué se decidió, quién lo hace y para cuándo, y se comparan sus versiones con el cierre publicado. Ahí se compara con A1 (#14), que es lo que define si vale la pena construir.

## Results
Pendiente de /analyze-solution-tests.

## Decision
Pendiente de /analyze-solution-tests.
