# Métricas, retención y crecimiento · ficha rápida
La retención por cohortes es la prueba de "make something people want": lo único que importa es que la curva se aplane; sin eso, growth es llenar un balde agujereado. Después: pocas métricas bien definidas, ingresos como KPI, crecimiento semanal, orgánico antes que pago. Detalle: → 07-metricas-retencion-y-crecimiento.md
YC: Lieb (SS 26-27), Blomfield (SS 28-29), Divya (SS 30). HTSS 2014: Schultz (Facebook), Cheung (Homejoy).

## Checklist para evaluar
Retención:
- [ ] Curvas de cohortes (una línea por cohorte, normalizadas), no un solo número [SS 26 @0:09:21]
- [ ] "Activo" = acción de valor (rúbrica "sentado al lado del cliente"), no "abrió la app" ni solo "paga" [SS 26 @0:18:04]
- [ ] Período = uso esperado (diario social, semanal utilidad, trimestral/anual viajes) [SS 26 @0:06:03]
- [ ] ¿Se aplanan? ¿En qué nivel vs comparable? [HTSS 06 @0:09:12]
- [ ] Cohortes nuevas por encima de las viejas [SS 26 @0:21:57]
- [ ] Armadas a mano al menos una vez y coinciden con la herramienta [SS 26 @0:20:17]
- [ ] Dot plot o miraron usuarios individuales [SS 27 @0:00:00]
- [ ] B2B: retención de logos y NDR ≥ 125% temprano, nunca < 100%; asientos activados vs comprados [SS 29 @0:15:54]
KPI y crecimiento:
- [ ] KPI primario escrito (tras lanzar: ingresos) + 3-5 secundarios [SS 30 @0:05:27]
- [ ] 4-5 métricas con definiciones escritas, sin cambios recientes [SS 29 @0:03:12]
- [ ] Crecimiento semanal medido vs 5-7% [SS 30 @0:19:08]; meta top-down y bottom-up visible [SS 30 @0:22:24]
- [ ] Sin vanidad: registros totales, page views, GMV como ingreso, pilotos como ARR, gratuitos como crecimiento [SS 29 @0:05:43]
Adquisición y economía:
- [ ] Origen de cada usuario guardado (UTM o "¿dónde nos conociste?") [SS 28 @0:06:45]
- [ ] Orgánico ≥ 50% (ideal > 80%) [SS 28 @0:20:31]
- [ ] CAC por canal hasta usuario retenido; payback ≤ 3 meses (≤ 12 con riesgo) [HTSS 04 @0:45:39]
- [ ] Unit economics positivas o plan escrito; margen bruto con COGS honestos (créditos de IA incluidos) [SS 29 @0:18:01]
- [ ] Update a inversores: ingresos, burn y runway arriba [SS 29 @0:08:17]

## Fórmulas y frameworks
**Cohortes, 3 definiciones** (Lieb) [SS 26 @0:02:45]: (1) cómo aislar cohortes (fecha de alta; luego país, canal, dispositivo); (2) acción de "activo" correlacionada con valor (Instagram: vio 3+ posts; Uber: completó un viaje); (3) período. Rúbrica: "imagine you're sitting next to one of your customers... what is the thing that's going through your head that helps you answer... whether that user is a good user". Si usás pago: "paga **y** usó algo este mes".
**Triángulo → layer cake** (Lieb): filas = cohortes, columnas = períodos desde alta; normalizar (primera columna 100%); fila = una cohorte, columna = si mejoran; graficar una línea por cohorte; apilar en tiempo absoluto = layer cake ("the most beautiful chart that you'll ever see in your startup") [SS 26 @0:27:55].
**4 formas de engañarse** (Lieb, "las cometí todas") [SS 26 @0:13:42]: período demasiado largo; acción demasiado fácil (inflable con notificaciones); un solo punto en vez de la forma ("80% semana a semana", ¿qué semana?); confiar ciegamente en la herramienta (rolling retention).
**Mejorar retención** (Lieb) [SS 26 @0:21:24]: mejor producto · mejores usuarios (cortar cohortes por segmento, "often this is the easiest way") · primera experiencia/onboarding ("the cheapest and easiest") · efecto de red. Santo grial: curvas que suben y cohortes cada vez mejores.
**Dot plot** (Lieb) [SS 27]: grilla usuario × día; un punto por día con evento de valor; día uno con anillo; ordenar por atributo. Errores: evento equivocado (abrir app), semanas en vez de días. "The dot plot could be your only dashboard" hasta cientos de usuarios; con IA se arma "in like 10 minutes" [SS 27 @0:12:46].
**Razonamiento dimensional** (Schultz): activos públicos de un comparable ÷ universo posible = piso de su retención [HTSS 06 @0:08:09].
**North star, magic moment, usuario marginal** (Schultz): north star la fija el CEO (Facebook MAU, WhatsApp sends, Airbnb noches); acortar el camino al magic moment; crecer para el que casi no usa: "Don't think about yourself" [HTSS 06 @0:21:07].
**Magic moment** (Blomfield): comparar mejores usuarios vs resto → umbral (Facebook 7 amigos en 10 días; Monzo 3 amigos) → onboarding para llegar rápido → no obsesionarse con el número exacto [SS 28 @0:15:02].
**CAC y payback** (Cheung): CAC = CPC / conversión; anuncio bueno si CLV − CAC ≥ 0, por segmento; payback "safe... three months; if you're very risk loving maybe 12" [HTSS 04 @0:45:39]. Divya: solo payback, "LTV can really be a rabbit hole" [SS 30 @0:24:03].
**NDR** (Blomfield) [SS 29 @0:12:46]: 10 × 10.000 = 100.000 MRR; −2 clientes (−20.000); 3 suben a 20.000 (+30.000) → 110.000 = NDR 110%. Temprano debería ser muy > 100% (subvaluaste el precio, sumás funciones, mejorás upsell).
**Margen bruto** = ingreso − COGS. Créditos gratis: "doesn't mean that that's the cost that doesn't exist. It just means you're hiding it" [SS 29 @0:18:01].
**KPIs** (Divya): primario = crecimiento de ingresos (sin lanzar: semanas al lanzamiento o conversaciones); excepciones: marketplace (GMV/registros), enterprise largo (LOIs), hardware/biotech (hitos auditados). Secundarios 3-5: retención/churn, unit economics, CAC. Test: "is this directly on my path to revenue growth? is this my biggest blocker?" [SS 30 @0:17:28]. Pairing metrics (Rabois): medir el opuesto [HTSS 14 @0:24:46].

## Cómo se hace
1. Antes de lanzar: 4-5 métricas, analítica simple (SQL, PostHog), definiciones escritas. Responder: % de registros DAU/WAU, nuevos vs recurrentes, ingreso por usuario [SS 29 @0:02:30].
2. Armar cohortes a mano (script o Sheets); refrescar cada 1-2 semanas, no varias veces al día [SS 26 @0:20:50].
3. Priorizar (Divya) [SS 30 @0:08:12]: meta de la semana → mayor cuello de botella → anotar todas las ideas → rankear por probabilidad, sub-rankear por complejidad → elegir un par → si no se mueve, "por qué" varias veces → retro semanal.
4. Metas: top-down (hito → tasa semanal) y bottom-up (realista próxima semana); quedarse en el medio, evitando "underwhelming but consistent growth" [SS 30 @0:23:30].
5. Adquisición: orgánico primero; tests pagos para conocer payback; recién con orgánico "crank up the ad spend" [SS 30 @0:20:15].
6. Update mensual: ingresos, burn, runway arriba, aunque el ingreso sea cero [SS 29 @0:07:42].
→ 07: Cómo se hace (578-664), Qué hacer después (1000-1016).

## Números de referencia
| Qué | Número | Cita |
|---|---|---|
| Crecimiento en YC (Divya citando a PG) | 5-7% semanal bueno; 10% excepcional | [SS 30 @0:19:08] |
| Activos en consumo (Blomfield) | 15% mensual bueno; 10% ok; ≤ 5% difícil | [SS 28 @0:00:43] |
| Retención terminal (Schultz) | e-commerce 20-30% mensual bien, 60% fantástico; social ~80% o no hay red | [HTSS 06 @0:09:12] |
| B2B retención (Blomfield) | "might be 80% or 70%" | [SS 29 @0:08:58] |
| 95% vs 90% mensual | quedan 54 vs 28 de 100 al año | [SS 25 @0:12:40] |
| NPS (Blomfield) | +50 mínimo en consumo nuevo | [SS 28 @0:18:20] |
| NDR | temprano 125%, 150% genial; maduras 110-120% | [SS 29 @0:15:54] |
| Margen bruto | SaaS ~95%; operativos 5-15%; objetivo 80-90% | [SS 29 @0:17:19] |
| Señal de pivote (Cheung) | 3-4 semanas sin crecer trabajando a full | [HTSS 04 @0:48:24] |

## Señales: bien / mal
Bien: curvas que se aplanan (aunque sea en 20%) y cohortes nuevas mejores; layer cake con capas viejas gruesas; mayoría orgánica; NDR > 100%; el fundador explica numerador, denominador, acción y período de cada número.
Mal: curva que va a cero; "80% de retención" sin forma; definiciones que cambian; GMV o registros como titular; mayoría pago; créditos que maquillan el margen; "no estamos enfocados en crecer ahora".
No se hizo: sin métricas antes de lanzar; nadie sabe de dónde vienen los usuarios.

## Errores típicos
- Growth sobre una curva que no se aplana: "don't go and do growth tactics... Focus on getting product market fit" (Schultz) [HTSS 06 @0:05:59].
- 30 o 500 métricas en vez de 4-5 [SS 29 @0:01:51].
- Escalar con unit economics negativas sin plan (blitzscaling: "a whole wasteland of startups") [SS 29 @0:20:40].
- Equipo de growth en etapa temprana [HTSS 06 @0:10:52]; split test de botones sin escala [SS 29 @0:01:51].

## Qué diría cada uno
- **Lieb**: ¿se aplanan tus curvas? · **Blomfield**: ¿cuánto es orgánico y cuál es tu NPS? · **Divya**: ¿KPI primario y mayor cuello de botella esta semana? · **Schultz**: ¿north star y magic moment? · **Altman**: ¿estás creciendo esta semana? · **Thiel**: ¿y la durabilidad? [HTSS 05 @0:24:29]

## Ojo
- **Unidades**: 5-7% **semanal** (durante YC) vs 15% **mensual** (consumo, Blomfield). No son equivalentes; usar semanal para la etapa de batch.
- **Subtítulo de SS 28** dice que ninguna gran empresa de consumo escala con más de 50% orgánico; la recapitulación dice lo opuesto. Vale: al menos 50% orgánico [SS 28 @0:20:31].
- **KPI en consumo**: Divya, ingresos; Blomfield y Schultz aceptan activos o north stars no monetarias. GMV puede guiar un marketplace pero no reemplaza al ingreso.
- **"Paga" como retención**: Lieb exige "paga y usa"; Blomfield usa "sigue pagando" en B2B. Usar el de Lieb.
- **Facebook**: 7 amigos en 10 días (Blomfield) vs 10 en 14 (Schultz); el número exacto no importa.
- **Época IA** [Visión]: Cursor 10% semanal, Legora de 1 a 100 M ARR en un año, Collison "un millón en tu primer mes" (él mismo lo llama exageración) [SS26 09 @0:26:36]. No son benchmark de YC.
- **Huecos**: sin benchmarks de retención para SaaS, marketplaces o fintech (usar razonamiento dimensional); sin fórmula de LTV completa; sin churn mensual B2B de referencia.
- Detalle: → 07: Para el agente (943-1038), Contradicciones (901-942), Números (665-713).
