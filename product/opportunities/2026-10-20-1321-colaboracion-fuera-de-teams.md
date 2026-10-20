---
status: framed
segment: Team Leads y mandos medios que conducen reuniones de trabajo conjunto (planificar, priorizar, revisar) con más de 5 participantes, en cuentas M365 que pagan, de cualquier tamaño
personas: valentina-rojas, martin-aguirre, carolina-mendez, rodrigo-salinas, diego-paredes, ana-lucia-torres
---

# Oportunidad: la colaboración se va fuera de Teams durante la reunión

Cuando una reunión de trabajo necesita que varias personas hagan algo juntas, quien la conduce saca el trabajo a Miro, Mural, FigJam o Google Docs. Pierde tiempo en accesos y cambios de herramienta, y lo producido queda fuera de Teams. Es urgente ahora porque la subida a Max está estancada en 2,4%, Max se diferencia justamente por reuniones, y CollabCon es en 5 meses.

Llegó como: "Mejorar significativamente la colaboración y la interacción en tiempo real durante las reuniones y sesiones de trabajo, a través de herramientas colaborativas integradas". La parte "a través de herramientas colaborativas integradas" es una solución y quedó apartada como idea candidata.

## Segmento y personas

- Valentina Rojas (primary): sufre el problema de forma directa. Conduce, pega el enlace y resuelve los accesos.
- Martín Aguirre (secondary): lo sufre por efecto. No logra abrir los enlaces externos y se queda callado.
- Carolina Méndez (tertiary): no lo sufre. Sirve para la creencia de viabilidad en cuentas chicas, donde ya hay equipos pagando Slack y Notion por fuera.
- Rodrigo Salinas (tertiary): no lo sufre; para él el costo es el riesgo de fuga de datos. Sirve para la creencia de viabilidad en cuentas grandes y puede bloquear cualquier solución.
- Diego Paredes (negative): sufre algo parecido como invitado externo, pero queda fuera de alcance. Sirve para no confundir sus enlaces con los del segmento.
- Ana Lucía Torres (negative): no lo sufre. No colabora en reuniones.
- Falta: un Team Lead en una cuenta de menos de 100 licencias, que es el 71% de las cuentas y donde el riesgo de baja es mayor.

## Señales

| Señal | Origen | Fuente |
|---|---|---|
| "Colaboración durante reuniones" es la 3ª categoría del portal de feedback: 4.700 solicitudes del segmento en 12 meses | unverified | brief del caso, que cita el portal de feedback (sin export) |
| 22% de los comentarios negativos post-reunión del segmento mencionan la colaboración en vivo ("terminamos en otra herramienta", "la pizarra es difícil de encontrar y nadie la usa") | unverified | brief del caso, que cita la encuesta post-reunión (sin n) |
| En el 38% de las reuniones del segmento con más de 5 participantes se comparte un enlace a Miro, Mural o FigJam, y mientras dura la actividad en Teams cae | unverified | brief del caso |
| Whiteboard se abre en el 6% de las reuniones del segmento; en la mitad de esas se cierra antes de 2 minutos | unverified | brief del caso |
| En renovaciones de cuentas grandes, "colaboración" aparece en las conversaciones sobre Max (sin conteo) | unverified | brief del caso, que cita a Ventas (anecdótico) |
| 37% de las organizaciones tienen Slack o Google Chat activo; "el equipo ya usa otras herramientas" es motivo de baja | unverified | brief del caso, ver product/overview.md |
| Valentina deja Whiteboard por Miro; Martín no logra abrir los enlaces; Rodrigo bloquea Miro por seguridad | synthetic | product/personas/ |

**Tensión abierta:** que Whiteboard se cierre antes de 2 minutos sugiere que la gente lo encuentra y no le sirve. Pero un comentario dice "la pizarra es difícil de encontrar". Hay evidencia para los dos lados de la creencia #1.

**Problema vecino, fuera de esta oportunidad:** "pierdo tiempo pasando lo que decidimos a un documento después" (lo que pasa después de la reunión).

## Resultado de negocio

- Principal: tasa de subida de Premium a Max (hoy 2,4%).
- Secundario: retención en la renovación (hoy 3,6% baja de plan o no renueva).
- La dirección mira también los ingresos por licencia en este segmento.

## Restricciones

- Presupuesto máximo de USD 5M.
- Fecha: lo que se elija se presenta en CollabCon, en 5 meses (marzo de 2027).
- Cualquier solución tiene que cumplir: facilidad de uso, accesibilidad, compatibilidad con Microsoft 365, privacidad y seguridad corporativas, funcionamiento en tiempo real e impacto mínimo en el rendimiento de la reunión.

## Creencias

Referencias a product/overview.md, el único registro de creencias:

- [product] [value] (#1 del registro) Los Team Leads usan Miro, Notion o Google Docs en reuniones porque las herramientas nativas no les sirven, no porque no las conozcan.
- [opportunity: colaboracion-fuera-de-teams] [value] (#2 del registro) En las reuniones de trabajo conjunto, los Team Leads del segmento pierden al menos 10 minutos por reunión entre accesos, cambio de herramienta y pasar los resultados a Teams, y lo viven como un problema que quieren resolver, no como un costo normal.
- [opportunity: colaboracion-fuera-de-teams] [viability] (#3 del registro) En cuentas medianas y grandes, tener colaboración en vivo dentro de Teams es razón suficiente para subir a Max, al menos para una parte de los usuarios, y Ventas puede convertir esa razón en upgrades.
- [product] [viability] (#4 del registro) La subida a Max depende de lo que pidan los Team Leads; IT pagaría si quienes conducen reclamaran capacidades.

## Agenda de investigación

| Creencia o pregunta | Instrumento (de menor a mayor costo) | Decisión que habilita | Fecha |
|---|---|---|---|
| ¿Cuánto del 38% de enlaces externos viene de invitados externos (tipo Diego) y no del segmento? | Datos del producto: separar enlaces por usuario interno o invitado | Si la señal principal se mantiene o se infla | 2026-10-31 |
| #1: Whiteboard, ¿no sirve o no se encuentra? | Datos del producto (desde dónde se abre, qué se hace antes de cerrarlo), luego entrevistas a Team Leads | Si el problema es de producto o de descubrimiento; con descubrimiento, la solución es mucho más barata | 2026-11-20 |
| #2 [opportunity] [value]: ≥10 min por reunión y voluntad de resolverlo | Encuesta al segmento (/design-survey) con opt-in, luego entrevistas (/design-interview) a quienes contradigan la creencia | Si el problema vale el presupuesto de USD 5M | 2026-11-20 |
| #3 [opportunity] [viability]: colaboración como razón para pasar a Max | Conteo de Ventas en las renovaciones de cuentas grandes, más conversaciones con compradores de IT | Si se presenta como palanca de Max en CollabCon o como mejora de Premium | 2026-11-30 |
| #4: ¿quién empuja la subida, Team Leads o IT? | Investigación secundaria (/research-market: cómo cobran Zoom, Google Meet y Miro la colaboración), luego entrevistas a IT de cuentas chicas y grandes | A quién se le vende y se le comunica | 2026-11-30 |
| Retención: ¿las "otras herramientas" de quienes bajan de plan son de colaboración en reuniones? | Datos: texto libre de los motivos de baja | Si la retención es un resultado real de esta oportunidad o solo un supuesto | 2026-11-15 |
| Cumplimiento: ¿cuántas cuentas grandes restringen apps externas en reuniones? | Datos del centro de administración (políticas de apps de terceros) | El tamaño del segmento donde una solución nativa no tiene competencia | 2026-11-15 |

**Riesgo de calendario:** para llegar a CollabCon, el problema debería quedar validado hacia el 2026-11-30 y la solución elegida hacia mediados de diciembre. Si la fecha empuja a saltar directo a una solución, el brief debe dejarlo registrado como decisión, no como omisión.

## Ideas candidatas (sin evaluar)

- Herramientas colaborativas integradas (tal como llegó la oportunidad)
- Editar un documento entre varios durante la llamada (del portal de feedback)
- Votar o priorizar en vivo (del portal de feedback)
- Hacer una sesión de trabajo sin salir de Teams (del portal de feedback)
