# IA y startups · ficha rápida
Consejo de YC sobre IA = solo SS 03, 14, 15, 16, 17, 24, 29. Todo AISS (2025) y SS26 (2026) es [Visión] de un orador. Lo de modelos envejece en meses. Detalle: → 10-ia-y-el-futuro.md

## Consejo de YC (lo que sí es método)
- **3 cualidades de una idea de IA** (John, YC) [SS 03 @0:06:04]: 1) **en el borde** de lo que hacen los modelos: apenas funciona hoy y mejora con cada modelo, "Live in the future and then build what's missing"; 2) **verticaliza**: vendé el resultado, "Don't build software for insurance companies, just be the insurer"; 3) **la versión más ambiciosa** (cuesta lo mismo y da foso). → 1.11 (líneas 436-454)
- Error: "AI is cool, what could I apply AI to?" (solución buscando problema) [SS 02 @0:01:39]. Empezá con humano en el loop antes de gastar en cómputo [SS 04 @0:05:37].
- **Servicios nativos de IA** (socio de YC) [SS 16 @0:01:48]: buen mercado = **low trust** (ya tercerizado, importa el resultado, "where the budget already lives"), **low judgment at the task level**, **high intelligence threshold**, **regulación** como foso. **"Sam Altman test"**: "as the models get better, does your service get stronger or does the model itself commoditize you?" [SS 16 @0:03:25]. "The product is an operation"; "automating the process is the product"; pocos pilotos; precio por unidad o resultado, nunca cost-plus: "sell outcomes, not seats or tokens. The pilot is the product"; COGS = modelos + hosting + humanos, meta 50%+ de margen; no compres un servicio para ponerle IA ("you just can't acquire product market fit"). → 1.12 (líneas 455-487)
- **Dev tools** (Dessaigne, YC): ideas "tar pit" pueden funcionar hoy; en ideas obvias (observabilidad de LLM) sabé cómo te diferenciás [SS 17 @0:02:54]. → 1.13 (488-495)
- **Vibe coding** (Blomfield, YC, 2025): plan en markdown, por secciones, tests, "Use Git religiously", `git reset --hard` ante un intento fallido, tests escritos a mano como guardrails [SS 14 @0:04:55]. → 2.16 (924-943)
- **Empresa nativa de IA** (Diana Hu, YC) [SS 15 @0:01:14]: la IA es "the operating system your company runs on"; procesos en **ciclo cerrado**; "Every important action should produce an artifact"; humanos escriben spec y tests, agentes implementan; "almost no human middleware"; "uncomfortably high API bill" antes que más gente. → 3.5 (1080-1106)
- **Precio** (Blomfield, YC): margen bruto 80-90%; bajar precio porque bajan los tokens es "a really risky maneuver" [SS 24 @0:06:00]. Créditos gratis: "you're hiding it for the moment", van al COGS [SS 29 @0:18:01].

## Checklist: ¿mi idea de IA tiene sentido?
- [ ] Hoy **se paga a personas** por ese trabajo y sabés cuánto (Heller [AISS 05 @0:03:47]); es asistir, reemplazar o lo antes impensable [AISS 05 @0:09:19].
- [ ] **Concreta**: un ingeniero la construye con lo que decís (Ng [AISS 04 @0:04:28]).
- [ ] **Prueba de Dean** [Visión]: el modelo general hoy acierta 0-1% (bien) o ~20% (mal, la absorbe) [SS26 10 @0:28:26].
- [ ] Pasa el Sam Altman test (YC) y no es el asistente central de un laboratorio ni "CRM with AI" [AISS 03 @0:14:57] [AISS 12 @0:17:51].
- [ ] Ventaja que no sea solo capacidad técnica ("a rat race", Fischer [AISS 15 @0:21:11]): datos que el modelo no ve, contexto, integración, licencias, loop de datos.
- [ ] Alguien sabe exactamente cómo trabaja el profesional, o hay plan para pegarse al cliente [AISS 05 @0:10:25].
- [ ] Sabés **cuántos nueves** necesitás (demo, copiloto, autónomo) (Dolgov [SS26 08 @0:14:43]).
→ Checklist completo (líneas 1912-1933)

## ¿Me barre OpenAI? (6.1-6.2, líneas 1399-1442)
- Altman [Visión]: no hagas el asistente central; "you have some window before which you have to build defensibility" [AISS 03 @0:15:31].
- Srinivas: "they will copy anything that's good"; "The only moat you have is speed" [AISS 09 @0:30:26] [AISS 09 @0:04:21].
- Ng: "it's not that easy to casually wipe out thousands of startups" [AISS 04 @0:29:02]. Heller: "Just build it… Don't be scared" [AISS 05 @0:39:10]. Collison (2026): el miedo está "overstated" [SS26 09 @0:23:18].
- Fosos citados: velocidad, marca, software sobre los tokens (Levie), circuito de datos (Nadella), evals y dominio (Heller), vender a quien el incumbente no atiende (Levie [AISS 12 @0:39:40]). Ningún producto de IA tiene aún efecto de red interno (Srinivas [AISS 09 @0:23:51]).

## Checklist: ¿cómo construyo con agentes? (producto)
- [ ] **Evals primero**: "bueno" definido y gradable, set de reserva, ~100 casos por prompt antes de beta, cada queja es un test (Heller [AISS 05 @0:17:01]). Demos sin evals: 60-70% [AISS 05 @0:15:20].
- [ ] Pasos fijos en código, no en prompts (Heller [AISS 05 @0:13:40]).
- [ ] El modelo puede **verificar** su trabajo (tests, screenshots) (Cherny [SS26 14 @0:19:47]).
- [ ] Humano en el ciclo con **slider de autonomía** y diffs chicos auditables (Karpathy [AISS 01 @0:22:57]).
- [ ] Cambiar de modelo = correr las evals contra 2-3 (Ng [AISS 04 @0:36:43]; Junestrand [SS26 01 @0:34:02]).
- [ ] Prompt podado y revisado con cada modelo nuevo (Cherny [SS26 14 @0:06:26]); seguridad no confiada a una línea del prompt (Steinberger [SS26 05 @0:34:07]).
→ (líneas 1934-1949); detalle 2.1-2.13 (498-904)

## Checklist: ¿cómo cobro un producto de IA? (2.17, líneas 944-968)
- [ ] Por **valor o trabajo hecho** (unidad, resultado), no asientos (Heller, Levie, YC SS 16).
- [ ] **Fórmula Levie** [AISS 12 @0:21:07]: precio entre costo humano y el tuyo. Ej.: humano US$ 5-10, agente US$ 0,10, precio US$ 2; con parte recurrente; no "offensive".
- [ ] **Margen**: sin software ≤ "2x max of the token cost"; con software 80-90% [AISS 12 @0:22:44]. YC: 80-90% [SS 24].
- [ ] Lo impensable: 10-20% del valor creado; preguntá "how would you rather pay for this?" (Heller [AISS 05 @0:37:33] [AISS 05 @0:26:09]).
- [ ] Pilotos no cuentan como ARR ("pilot recurring revenue") y hay plan de adopción después de la firma (Heller [AISS 05 @0:28:20]).

## Checklist: empresa nativa de IA (YC SS 15 + [Visión] Garry Tan)
- [ ] Reuniones grabadas, pocas DMs; un agente lee Linear, Slack, feedback y ventas [SS 15 @0:02:52].
- [ ] Specs y tests humanos, agentes implementan [SS 15 @0:04:32]; el fundador usa los agentes él mismo [SS 15 @0:08:56].
- [ ] Tareas repetidas como skills; contexto propio en markdown que controla el fundador (Garry Tan [SS26 07 @0:27:08]).

## Señales
- Bien: demo medida en nueves ("count your nines before you count your demo views") [SS26 08 @0:14:43]; cada modelo nuevo mejora el producto sin reescribirlo [SS 16 @0:03:25]; ingresos crecen más rápido que la gente.
- Mal: el modelo general ya hace ~20%; chatbot pegado ("pixie dust") [AISS 15 @0:08:43]; ARR de pilotos; humanos tapando huecos; todo atado a un proveedor; roadmaps de 9-24 meses.

## Qué diría cada uno
Karpathy: "¿dónde está tu slider de autonomía?" · Heller: "¿qué trabajo pagado reemplazás y dónde están tus evals?" · Levie: "¿cuánto software hay sobre tus tokens?" · Dean: "¿0-1% o 20%?" · Cherny: "borrá el prompt, tarea difícil y forma de verificar" · Dolgov: "la demo es el 1%" · Altman: "no hagas nuestro asistente" · Ng: "prototipá en días". → (líneas 2010-2027)

## Ojo: contradicciones que cambian la respuesta (líneas 1821-1854)
- **¿Te copia el laboratorio?** Srinivas sí / Ng, Heller, Collison no. Usá: no hagas el asistente central y elegí lo que el modelo hace 0-1%.
- **Precio**: cobrá por valor (Heller) / la competencia lo baja a centavos (Heller [AISS 05 @0:37:33]). Usá: arrancá en el valor y defendé margen con software.
- **Vibe coding 2025 vs 2026**: YC SS 14 pide pasos chicos (era Sonnet 3.7, "might change in 2 or 3 months"); Cherny pide tareas "too hard" y "let the model cook" [SS26 14 @0:14:55]. Usá: lo que se mantiene es verificar con tests.
- **¿Más scaffolding?** Garry Tan "fat skills thin harness" / Cherny: borrá CLAUDE.md y skills cada 6 meses. Usá: guardá contexto, podá instrucciones midiendo.
- **¿Fine-tuning propio?** Junestrand no / Finn sí en robótica. Usá: en software solo donde mide mejor.
- **¿Leer todo el código de la IA?** Karpathy sí / Steinberger no. Usá: lo crítico se lee.
- **¿Lanzar rápido?** YC "launch early" / Dolgov y Collison: tardá si fallar cuesta caro, pero con usuarios reales.
- **¿Muere el SaaS?** Masad "will go to zero" / Nadella, Levie: coexisten. Depende de la vertical.
- Hueco: ningún video da retención, churn o NDR de productos de IA; cifras de Altman ("seven minutes"/"17 minutes") y la ventana de Levie (2-3 o 4 años) son inconsistentes.

## Predicciones con fecha [Visión] (AISS = jun 2025; SS26 = 2026) → (líneas 1633-1685)
| Quién | Predicción | Plazo |
|---|---|---|
| Musk | Superinteligencia | "this year or next year" (2025-26) [AISS 02 @0:42:13] |
| Altman | Superinteligencia | 10-20 años [AISS 03 @0:32:58] |
| Fischer | AGI | 2-3 años [AISS 15 @0:03:17] |
| Karpathy | "Decade of agents" | próxima década [AISS 01 @0:27:38] |
| Kaplan | Horizonte de tareas se duplica | cada ~7 meses [AISS 13 @0:09:28] |
| Levie | Cierra la ventana; ~100 startups de 5-20 mil M | 2-3 (o 4) años [AISS 12 @0:32:30] |
| Masad | "All application software will go to zero" | años [AISS 10 @0:15:37] |
| Dean (2026) | ML y ciencia que se automejoran | 2027 [SS26 10 @0:46:33] |
| Altman (2026) | 6 meses de modelos = últimos 2 años; inferencia 10x/año | 6 meses [SS26 13 @0:30:37] |
| Finn (2026) | Robótica a nivel ChatGPT | próximos años [SS26 04 @0:39:22] |
| Huang (2026) | IA física de US$ 100.000 M | 3-10 años [SS26 15 @0:38:34] |
