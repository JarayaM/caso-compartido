---
status: framed
segment: Quienes conducen reuniones de trabajo conjunto de más de 5 personas en las que se decide algo, y quienes reciben o ejecutan esas decisiones, en cuentas M365 de 100 o más licencias
personas: valentina-rojas, martin-aguirre, carolina-mendez, rodrigo-salinas, diego-paredes, ana-lucia-torres, camila-herrera, felipe-ortega, elena-vidal, hernan-caceres
---

# Oportunidad: lo decidido se pierde entre la reunión y el trabajo

Lo decidido en reuniones de más de 5 personas no llega completo (qué, quién, para cuándo y por qué) a donde se trabaja: quien conduce lo reconstruye a mano y, cuando eso falla, quienes ejecutan rehacen trabajo o afectan a clientes. Es urgente ahora porque la subida a Max está estancada en 2,4%, Max se diferencia por reuniones, y CollabCon es en marzo de 2027.

**Origen:** es un pivote desde `colaboracion-fuera-de-teams`, que queda inactiva. La encuesta y las entrevistas mostraron que el mayor costo no está en colaborar durante la reunión, sino en lo que pasa después.

## Segmento y personas

Quienes conducen y quienes reciben o ejecutan son segmento principal por igual. Hay evidencia real solo de los primeros. Las cuentas de menos de 100 licencias quedan como pregunta de investigación.

- Valentina Rojas (primary): lo sufre. Dedica unos 20 minutos por reunión a escribir el resumen y las tareas.
- Martín Aguirre (secondary): lo sufre. Quiere entender lo que se decide sin estar en todas las reuniones.
- Camila Herrera (primary, derivada): lo sufre. Pasa a mano lo acordado en el tablero a Jira o Slack.
- Felipe Ortega (primary, derivada): lo sufre. Lo decidido o su motivo no quedan donde se trabaja.
- Elena Vidal (primary, derivada, confianza baja): lo sufre. Registra a mano y necesita dejar constancia para auditoría.
- Hernán Cáceres (secondary, derivada): lo sufre en parte. La reunión grande no decide, pero sus fallas también ocurren al ejecutar lo dicho ahí.
- Carolina Méndez (tertiary): no lo sufre. Responde la viabilidad en cuentas chicas; nadie le ha pedido capacidades avanzadas.
- Rodrigo Salinas (tertiary): no lo sufre. Responde la viabilidad en cuentas grandes y reguladas.
- Diego Paredes (negative): no lo sufre como parte del segmento. Es un invitado externo y está fuera de alcance.
- Ana Lucía Torres (negative): no lo sufre. No participa en estas decisiones.
- Falta: una persona que ejecute decisiones de reuniones a las que no asistió, y un Team Lead en una cuenta de menos de 100 licencias.

## Señales

| Señal | Origen | Fuente |
|---|---|---|
| 7 de 10 dedican 10–60 min a reconstruir lo decidido (en 2 casos, tras plannings trimestrales). 6 de 10 lo viven como problema y 4 lo normalizan o atribuyen a otra cosa | real | product/insights/2026-11-02-1357-contraste-creencias.md (n=10; tema preguntado) |
| Los 10 recuerdan un caso: 8 con costo concreto y 2 de rediscusión | real | product/interviews/ (n=10; tema preguntado) |
| Quienes reciben pagan la falla en 7 relatos (México, Chile, Medellín, Porto Alegre, Ecuador, Bogotá y un diseñador de Kora) | real | product/interviews/; evidencia indirecta, lo cuentan quienes conducen |
| Ninguno de los 6 que usan o probaron el resumen de IA confía en él como registro sin corregirlo, aunque 3 le ven valor | real | product/interviews/ (n=6) |
| Es la categoría más mencionada en la pregunta abierta: 22 de 95 en sentido estricto, 30 en sentido amplio | survey | product/insights/2026-11-02-1357-contraste-creencias.md (Q11; la pregunta orienta hacia decidir) |
| 24% marca "no quedó registrado" (puede incluir a quienes lo registraron después), 23% lo dejó en un chat fuera de Teams y 13% en Teams | survey | product/surveys/2026-10-25-1800-respuestas-colaboracion-en-vivo-fuera-de-teams.csv, Q9 (n=182) |
| El resumen de IA ya ocupa este lugar: 22 menciones espontáneas, cerca de la mitad con queja, y 36% lo usa | survey | product/insights/2026-10-28-1045-colaboracion-en-vivo-fuera-de-teams.md (Q9, n=182; Q10, n=210) |
| 55% dice que los próximos pasos quedan poco claros | secondary | Work Trend Index 2023, en product/research/2026-10-20-1349-colaboracion-en-reuniones.md |
| La IA de los competidores documenta, pero no ayuda a decidir | secondary | product/research/2026-10-20-1349-colaboracion-en-reuniones.md |

**Evidencia en contra**

| Señal | Origen | Fuente |
|---|---|---|
| La IA para después de la reunión ya es estándar (Copilot, Facilitator, Zoom, Otter), así que el espacio puede estar cubierto | secondary | product/research/2026-10-20-1349-colaboracion-en-reuniones.md |
| Sofía, Diego y Ricardo lo atribuyen en parte a disciplina o al tamaño de la reunión | real | product/interviews/ |
| 3 de 10 casi no dedican tiempo al cierre (Sofía, Martina, Ricardo) | real | product/interviews/ |

**Tensión abierta:** los competidores ya resumen, pero los usuarios no confían en esos resúmenes como registro de decisiones. Falta saber si es un vacío real o una etapa que la IA superará sola.

## Resultado de negocio

- Principal: subida de Premium a Max (hoy 2,4%).
- Secundario: retención en la renovación (hoy 3,6% baja o no renueva).
- Riesgo: el valor podría capturarse en Copilot y no en Max.

## Restricciones

- Presupuesto máximo de USD 5M, y CollabCon en marzo de 2027.
- Facilidad de uso, accesibilidad, compatibilidad con M365, privacidad y seguridad corporativas, tiempo real e impacto mínimo en el rendimiento.
- Las cuentas reguladas prohíben o tardan meses en aprobar herramientas externas (Lucía, R-126, R-173, R-190).
- La auditoría puede exigir que lo decidido salga por correo o un sistema de registro (Lucía).
- Copilot y Facilitator ya son oferta de Microsoft, y Facilitator requiere Copilot.

## Creencias

Referencias a product/overview.md, el único registro de creencias:

- [opportunity: decisiones-perdidas-tras-la-reunion] [value] (#8 del registro) Quien conduce dedica 10 minutos o más por reunión a reconstruir lo decidido y quiere resolverlo.
- [opportunity: decisiones-perdidas-tras-la-reunion] [value] (#11 del registro) Quien recibe o ejecuta actúa sobre una versión incompleta o tardía de lo decidido, y eso le cuesta retrabajo o preguntar de nuevo.
- [opportunity: decisiones-perdidas-tras-la-reunion] [viability] (#12 del registro) En cuentas de 100 o más licencias, resolver esto es razón suficiente para considerar Max, y el valor no queda ya cubierto por Copilot.

## Agenda de investigación

| Creencia o pregunta | Instrumento (de menor a mayor costo) | Decisión que habilita | Fecha |
|---|---|---|---|
| ¿Qué cubren ya Copilot, Facilitator y Zoom? | Decisión del 2026-11-02: no se hace una investigación de mercado nueva. Se usa `product/research/2026-10-20-1349-colaboracion-en-reuniones.md`, y la pregunta se responde con las conversaciones con Ventas e IT de #12 | Si hay un vacío o el espacio ya está ocupado | 2026-11-30 |
| #8 y #11: ¿cuánto se usa y se corrige el resumen? | Datos del producto: resúmenes abiertos, editados y compartidos en reuniones de más de 5 | El tamaño del problema con datos propios | 2026-11-15 |
| #8: ¿surge sin preguntar? ¿Existe fuera de estas empresas? | Decisión del 2026-11-02: no habrá nueva ronda de entrevistas. Queda sin prueba independiente; solo los datos del producto y las pruebas de solución pueden aportar más | Si el problema vale el presupuesto de USD 5M; se decide con la evidencia actual y los datos del producto | 2026-11-20 |
| #11: ¿lo sufre quien recibe? | Decisión del 2026-11-02: no habrá entrevistas a quienes ejecutan. Queda solo con evidencia indirecta | Si quien recibe sigue en el segmento; se mantiene sin validar | 2026-11-20 |
| #12: ¿mueve la subida a Max o queda en Copilot? | Conteo de Ventas en renovaciones y conversaciones con IT de cuentas grandes | Si se presenta como palanca de Max en CollabCon | 2026-11-30 |

**Riesgo de calendario:** el problema debería quedar validado hacia el 2026-11-30 y la solución elegida hacia mediados de diciembre.

## Ideas candidatas (sin evaluar)

- Fijar cada decisión durante la reunión con responsable, fecha y motivo, y publicarla donde vive el trabajo (de las entrevistas) — `chosen` para pruebas como A1: [product/solutions/2026-11-02-1453-decisiones-perdidas-tras-la-reunion.md](../solutions/2026-11-02-1453-decisiones-perdidas-tras-la-reunion.md)
- Un resumen de IA que separe lo decidido de lo propuesto y que el líder valide (de las entrevistas) — `parked` como A2: [product/solutions/2026-11-02-1453-decisiones-perdidas-tras-la-reunion.md](../solutions/2026-11-02-1453-decisiones-perdidas-tras-la-reunion.md)
- Que la decisión tenga confirmación del grupo antes de cerrar (de las entrevistas) — `chosen` para pruebas como A3, en su forma de práctica sin software: [product/solutions/2026-11-02-1453-decisiones-perdidas-tras-la-reunion.md](../solutions/2026-11-02-1453-decisiones-perdidas-tras-la-reunion.md)
