---
status: framed
segment: Team Leads y mandos medios que conducen reuniones de trabajo conjunto con más de 5 participantes en las que el grupo tiene que priorizar o decidir, en cuentas M365 que pagan. La evidencia real cubre empresas tecnológicas con operación en 3 o más países
personas: valentina-rojas, martin-aguirre, carolina-mendez, rodrigo-salinas, diego-paredes, ana-lucia-torres
---

# Oportunidad: el grupo no llega a una decisión con todos participando

Cuando una reunión de más de 5 personas tiene que priorizar o decidir, la discusión se traba, parte del grupo queda fuera y quien conduce termina decidiendo solo, con objeciones que aparecen tarde. Es urgente ahora porque la subida a Max está estancada en 2,4%, Max se diferencia justamente por reuniones, y CollabCon es en 5 meses.

**Relación con `decisiones-perdidas-tras-la-reunion`.** Esa oportunidad trata de lo que pasa con la decisión después de tomada; esta, de cómo se llega a ella. Pueden requerir soluciones distintas, por eso se enmarcan por separado. Si la evidencia muestra que son un mismo problema, se fusionan.

## Segmento y personas

- Valentina Rojas (primary): lo sufre en parte. Prioriza incidencias con su equipo y, cuando alguien no tiene acceso, el grupo pierde tiempo.
- Martín Aguirre (secondary): lo sufre de forma directa como participante. No logra entrar a los enlaces y prefiere quedarse callado.
- Carolina Méndez (tertiary): no lo sufre. Sirve para la creencia de viabilidad en cuentas chicas.
- Rodrigo Salinas (tertiary): no lo sufre. Sirve para la viabilidad en cuentas reguladas, donde lo externo está bloqueado.
- Diego Paredes (negative): no lo sufre como parte del segmento. Sirve para separar la exclusión de invitados externos de la de participantes internos.
- Ana Lucía Torres (negative): no lo sufre. No participa en decisiones de reunión.
- Falta: un participante real que no conduce. Las 10 entrevistas son a quienes conducen, así que quienes quedan fuera solo se conocen por lo que cuentan otros. También falta un Team Lead en una cuenta de menos de 100 licencias.

## Señales

| Señal | Origen | Fuente |
|---|---|---|
| Votar o priorizar es lo que más hacen los grupos en herramientas externas: 40% (72/182) | survey | product/surveys/2026-10-25-1800-respuestas-colaboracion-en-vivo-fuera-de-teams.csv, Q5 (n=182) |
| En el 46% de las reuniones sin externos, al menos una persona no logró entrar a la herramienta (63/137); con externos, el 64% (25/39) | survey | mismo CSV, Q7 × Q8. Solo cubre reuniones con herramienta externa |
| Converger o priorizar y participación suman hasta 24 de 95 menciones en la pregunta abierta (12 y 12; pueden solaparse). "Termino decidiendo yo y no siempre es lo ideal" (R-078) | survey | product/insights/2026-10-28-1045-colaboracion-en-vivo-fuera-de-teams.md, Q11. La pregunta orienta hacia decidir |
| En 6 de 10 entrevistas la discusión se traba y quien conduce decide solo o casi solo (Javier, Martina, Tomás, Andrés, Sofía, Lucía) | real | product/interviews/ (n=10) |
| En al menos 5 entrevistas hay participantes que casi no intervienen (Martina, Andrés, Sofía, Valeria, Ricardo). A Valeria, la objeción de Gloria le llegó una semana después, en un café | real | product/interviews/ (n=10). La guía pregunta quién casi no intervino |
| En 4 entrevistas alguien no pudo entrar o editar (Javier, Tomás, Sofía, Valeria) | real | product/interviews/ (n=10) |
| 4 terminan contando votos a mano (Andrés, Lucía, Ricardo con reacciones o manos; Valeria tras votos duplicados en FigJam). "No te fías del todo del número" (Lucía) | real | product/interviews/ (n=10) |
| La falta de votación en la pizarra nativa se menciona como motivo de abandono | real / survey | Javier y Tomás; R-005, R-113 y R-239 en Q11 |

**Evidencia en contra**

| Señal | Origen | Fuente |
|---|---|---|
| Las decisiones de verdad se toman en grupos chicos; las reuniones grandes no deberían decidir (Paula, Ricardo) | real | product/interviews/ (n=10) |
| Lo mismo en la encuesta: R-073 y R-207 | survey | Q11 y Q12 del CSV |
| El voto ya funciona en algunas herramientas: los puntos de Miro (Tomás, Martina) y escribir a la vez en un Google Doc, donde "habla hasta QA" (Sofía) | real | product/interviews/ (n=10) |
| Para Javier, la votación ordena pero no decide: el nudo sigue en la discusión | real | product/interviews/2026-10-26-0900-javier-molina.md |

**Tensión abierta:** no se sabe si la exclusión por acceso y el silencio son el mismo problema. Los de Lyon no participaban por falta de acceso, pero en otros casos la gente tiene acceso y aun así no habla por idioma, antigüedad o huso horario. Pueden pedir soluciones muy distintas.

## Resultado de negocio

- Principal: tasa de subida de Premium a Max (hoy 2,4%).
- Secundario: retención en la renovación (hoy 3,6% baja de plan o no renueva).
- No hay ninguna evidencia todavía de que resolver este problema mueva alguno de los dos.

## Restricciones

- Presupuesto máximo de USD 5M, según el brief del caso. No está definido como presupuesto separado de `decisiones-perdidas-tras-la-reunion`.
- Fecha: lo que se elija se presenta en CollabCon, en marzo de 2027.
- Cualquier solución tiene que cumplir: facilidad de uso, accesibilidad, compatibilidad con Microsoft 365, privacidad y seguridad corporativas, funcionamiento en tiempo real e impacto mínimo en el rendimiento de la reunión.
- En cuentas con compliance, lo externo está prohibido o tarda meses en aprobarse (Lucía, R-126, R-173, R-190).

## Creencias

Referencias a product/overview.md, el único registro de creencias:

- [opportunity: decidir-con-todos-en-la-reunion] [value] (#9 del registro) Las reuniones de más de 5 personas tienen que priorizar o decidir, y hoy quien conduce termina decidiendo sin el grupo o con parte de él fuera, y busca formas de evitarlo.
- [opportunity: decidir-con-todos-en-la-reunion] [viability] (#10 del registro) Mejorar cómo decide el grupo es razón suficiente para que una parte de las cuentas medianas y grandes considere subir a Max.

## Agenda de investigación

| Creencia o pregunta | Instrumento (de menor a mayor costo) | Decisión que habilita | Fecha |
|---|---|---|---|
| #9: ¿cuánto se vota o prioriza en reuniones de más de 5? | Datos del producto: uso de manos levantadas, reacciones y encuestas por tamaño de reunión | Si el problema es frecuente o de nicho | 2026-11-15 |
| #9: ¿las reuniones grandes deben decidir? | Decisión del 2026-11-02: no habrá nueva ronda de entrevistas. Queda abierta, con evidencia en ambos sentidos | Si esta oportunidad continúa o se descarta | 2026-11-20 |
| ¿Exclusión y silencio son el mismo problema? | Decisión del 2026-11-02: no habrá entrevistas a participantes que no conducen. Queda sin responder | Si se separa el problema de acceso del de participación | 2026-11-20 |
| ¿Qué impide entrar en reuniones internas? | Datos del producto y de soporte sobre permisos, SSO y licencias | Si la exclusión está al alcance de Teams | 2026-11-20 |
| #10: ¿mueve la subida a Max? | Sumarlo al conteo de Ventas y a las conversaciones con IT previstos para #12 | Si se presenta como palanca de Max en CollabCon | 2026-11-30 |

## Ideas candidatas (sin evaluar)

- Votar o priorizar en vivo (del portal de feedback)
- Votos limitados con conteo automático (de las entrevistas)
- Un canal para objetar sin tener que hablar (de las entrevistas)
- Ver quién quedó fuera de la herramienta durante la reunión (de la encuesta)
