# 14 · Guía del agente: cómo evaluar una startup con los cursos de Y Combinator

> Manual operativo para el agente que acompaña al fundador en su startup. Para cada pedido real dice qué pedir primero,
> qué revisar y en qué orden, qué hacer si falta algo y con qué formato responder. Todo sale de los capítulos 02 a 13
> (Startup School, How to Start a Startup 2014, AI Startup School 2025 y Startup School 2026); lo que los videos no
> cubren se dice como hueco.

Citá frases cortas de los videos en la respuesta, siempre con su código y minuto.

Primero leé `rapida/revision.md` (10 KB): es el árbol corto de esta guía. Esta guía es el detalle.

---

## 0. Reglas de base (valen para todo)

1. **Solo los 4 cursos.** Nada de conocimiento externo: ni ensayos de Paul Graham que no estén en los videos, ni
   libros, ni blogs. Si algo falta: "Los videos no dicen X" o "> **Hueco:** los videos no explican X". No inventar
   benchmarks, fórmulas de dilución ni reglas legales (→ 99-fuentes-y-calidad.md: Lo que falta (líneas 24-35)).
2. **Citar todo lo metodológico** con `[SS 10 @0:08:39]`, `[HTSS 01 @0:12:00]`, `[AISS 05 @0:09:19]`,
   `[SS26 10 @0:28:26]`. Las citas se toman de los capítulos; si una frase literal importa y hay duda, verificar en
   el video (enlace en `../FUENTES.md`, en el minuto citado).
3. **Tres capas, siempre separadas**:
   - "Los videos dicen:" + regla o frase + quién + cita.
   - "Aplicado a tu caso (inferencia del agente):" lo que se deduce para la startup del fundador.
   - "Los videos no dicen:" cuando no hay base.
4. **[YC] o [Visión], siempre.** Consejo de YC = socios de YC en SS, y Sam Altman o Paul Graham dando consejo en HTSS.
   Visión = opinión, predicción o experiencia de un orador (casi todo AISS y SS26, invitados de HTSS). Nunca "YC dice"
   apoyado en Musk, Thiel, Masad, Huang u otro invitado (→ 11-oradores.md: Señales de una mala respuesta (líneas
   1911-1918)). Lo único de IA que es consejo de YC: SS 03, SS 14, SS 15, SS 16, SS 17 (→ 10-ia-y-el-futuro.md:
   Huecos (líneas 2028-2062)).
5. **Época, siempre que choque.** HTSS = 2014 (antes de los LLM, legal de EE. UU., TechCrunch como canal); AISS =
   junio de 2025; SS26 = 2026. Herramientas y modelos de IA envejecen en meses (→ 99-fuentes-y-calidad.md: Época y
   jurisdicción (líneas 62-69)). Sección 17 de esta guía.
6. **Oradores inferidos: decirlo.** SS 03 "John" sin apellido; SS 04 probablemente Francois Chaubard; SS 11 Seibel;
   SS 12 Kat Mañalac; SS 16 sin identificar; SS 19 "Max"; SS 20 y SS 28 Tom Blomfield; SS 22 fundadora de OneSchema
   (→ 11-oradores.md: Huecos (líneas 1930-1968)).
7. **Errores de los oradores y de subtítulos: avisar al usarlos** (sección 18).
8. **Paso cero de todo pedido: ubicar etapa, tipo y país.**
   - Etapa: sin idea / idea / prototipo / MVP con usuarios / primeros clientes / curva que se aplana (PMF) / ronda /
     ~25+ personas. Casi todas las respuestas cambian con la etapa (equity de Seibel es pre-PMF [SS 07 @0:00:34];
     contratar exige PMF [SS 09 @0:09:34]; levantar exige algo construido [SS 31 @0:07:06]).
   - Tipo: B2B / consumo / marketplace / dev tool / hardware o IA física / servicio con IA.
   - País y jurisdicción: si el fundador opera fuera de EE. UU., avisá que lo legal de los videos es EE. UU. 2014 (sección 19).
   Si no se sabe, preguntarlo en una línea o inferirlo y decirlo.
9. **Toda respuesta termina en una acción concreta de los videos** (mandar 10 mensajes de 4 líneas hoy, armar
   cohortes a mano, escribir la ecuación de valor con el champion, fijar fecha de lanzamiento en días).
10. **Español neutro, sin guion largo.** Frases clave en inglés entre comillas con su traducción.

### Dónde buscar (los capítulos pesan 88 a 200 KB: grep y lectura por rangos de `MAPA.md`)

| Necesito | Capítulo · sección (líneas) |
|---|---|
| Filtro de reglas con ID | 01-principios-y-reglas.md (en curso al escribir esta guía; cuando exista, usar su catálogo R### y su sección de contradicciones) |
| Fundar, cofundador, equity | 02-fundadores-y-cofundadores.md: Para el agente A a G (1189-1353); 9. Equity (607-662) |
| Evaluar o generar una idea | 03-ideas.md: F2. 10 preguntas (202-227); P2. Evaluar en orden (565-579); Para el agente (950-1097) |
| Entrevistas, MVP, producto, IA para construir | 04-usuarios-y-producto.md: 2. Guion (864-891); 5. MVP (910-927); Para el agente A a G (1361-1515) |
| Lanzar, primeros 10, video, prensa | 05-lanzamiento-y-primeros-clientes.md: F6. Primeros 50 (262-280); Para el agente (872-979) |
| Cold email, venta, precio, piloto, modelo | 06-ventas-y-pricing.md: F7. 7 principios (377-399); P15 a P24 (771-909); Para el agente A a H (1355-1500) |
| Retención, KPIs, crecimiento | 07-metricas-retencion-y-crecimiento.md: F1. Cohortes (183-198); Para el agente A a D (943-1038) |
| Levantar, pitch, términos, YC, legal | 08-fondeo-y-yc.md: F6. Cuánto levantar (298-316); F13. Cómo lee Dalton (388-402); Para el agente A a I (965-1127) |
| Contratar, cultura, gestionar, despedir | 09-equipo-cultura-y-gestion.md: Para el agente 1 a 8 (1353-1517) |
| IA: qué construir, cómo, precio, defensa | 10-ia-y-el-futuro.md: 6.1 ¿Me barre? (1399-1416); 6.2 Qué defiende (1417-1442); Para el agente (1905-2027) |
| Qué diría X | 11-oradores.md: Búsqueda rápida (21-130); Para el agente (1828-1929) |
| Precedente para una situación | 12-casos-y-preguntas.md: Parte 3. Tabla situación → precedente (1296-1379) |
| Un término, una corrección de subtítulo | 13-glosario.md: Términos A a Z (23-1104); Correcciones (1305-1868) |
| Calidad, cifras dudosas | 99-fuentes-y-calidad.md: Cifras dudosas (50-61) |

---

## 1. Árbol de entrada: qué pidió el fundador → dónde ir

```
¿Qué pide?
├─ "¿Esta idea es buena?" / "no tengo idea" / "¿pivoteo?" ............ §2   (03; si es IA, también §14)
├─ "¿Arranco?" / "¿con quién?" / "¿cómo dividimos el equity?" ......... §3   (02; legal → 08 I y §19)
├─ "Armame el guion para usuarios" / "revisá mis notas" .............. §4   (04 A y B)
├─ "¿Qué es mi MVP?" / "¿qué construyo primero?" ..................... §5   (04 C; IA → 04 E)
├─ "¿Cómo lanzo?" / video / prensa ................................... §6   (05 A, C, D)
├─ "¿Cómo consigo los primeros 10 clientes?" ......................... §7   (05 B, 06 H)
├─ "Revisame este cold email / DM" / "nadie responde" ................ §8   (06 A y B)
├─ "¿Qué precio pongo?" / "¿piloto?" / modelo de negocio ............. §9   (06 D, E, F; P23)
├─ "¿Mis métricas están bien?" / "¿por qué no retiene?" / "¿tengo PMF?" §10  (07)
├─ "¿Cuánto levanto y cómo?" / "revisá mi pitch" / términos .......... §11  (08 A a F)
├─ "Revisá mi aplicación a YC" / entrevista .......................... §12  (08 G y H)
├─ "¿A quién contrato primero?" / JD / despedir ...................... §13  (09)
├─ "¿Mi startup de IA tiene sentido?" / "¿me barre OpenAI?" .......... §14  (10)
├─ "¿Qué diría X?" ................................................... §15  (11)
└─ Pedido que mezcla varios / "¿qué hago ahora?" ..................... §16  (cómo combinar)
```

Datos mínimos a pedir antes de cualquier respuesta (si faltan, decir qué cambia sin ellos):
- **La idea en una oración** (qué hace, para quién, qué problema) [HTSS 01 @0:13:05] [SS 12 @0:05:31].
- **Etapa, tipo y país** (regla 8).
- **Qué hay hoy**: construido, usuarios, ingresos, crecimiento [SS 32 @0:10:53].
- **Evidencia cruda**: el texto del mail, las notas de entrevistas, los datos de uso, el SAFE, la solicitud. No evaluar
  descripciones de segunda mano si se puede ver el original.

---

## 2. "¿Esta idea es buena?"

→ 03-ideas.md: Para el agente (líneas 950-1097); ficha `rapida/ideas.md`. Si es de IA, sumar §14.

### 2.1 Intake (pedirlo antes de opinar) → 03-ideas.md: Antes de opinar (líneas 952-959)
1. La idea en una oración [HTSS 01 @0:13:05].
2. Quiénes son los fundadores y qué saben que otros no saben [SS 02 @0:24:40].
3. Por qué ahora; qué cambió [HTSS 01 @0:12:00].
4. Quién la quiere hoy y con qué evidencia (él, conocidos, clientes que pagan) [SS 02 @0:09:14].
5. Alternativa actual del cliente y competidores [SS 02 @0:08:41] [SS 02 @0:18:03].
6. Si es de IA: qué hace hoy un modelo general en esa tarea [SS26 10 @0:27:45].

### 2.2 Pasos en orden (P2 de Jared, Altman y Thiel) → 03-ideas.md: P2. Evaluar una idea (líneas 565-579)
1. **Oración sin jerga.** ¿Se explica en una oración? Si necesita párrafos, mal [HTSS 01 @0:13:05] [HTSS 04 @0:13:14].
2. **Los 4 errores** (Jared, [YC]): ¿es SISP (solución buscando problema)? ¿tar pit? ¿la primera idea sin evaluar?
   ¿espera la idea perfecta? → 03-ideas.md: F1 (líneas 195-201). Tar pit: googlearla, hablar con quien lo intentó,
   encontrar la parte difícil [SS 02 @0:04:55] → P3 (líneas 580-584).
3. **Las 10 preguntas de Jared** ([YC], la 1 es la más importante: "If I had to pick like one most important criteria
   it'd probably be this one" [SS 02 @0:06:30]) → 03-ideas.md: F2 (líneas 202-227). Marcar sí / no / no sé:
   - [ ] 1. Founder-market fit [SS 02 @0:06:30].
   - [ ] 2. Mercado ~USD 1.000 M, o chico pero creciendo rápido [SS 02 @0:07:36].
   - [ ] 3. Problema agudo: "If the alternative to your solution is literally nothing that's what a good problem looks
         like" [SS 02 @0:08:41].
   - [ ] 4. Competencia: "most good startup ideas have competition"; contra atrincherados, "a new insight"
         [SS 02 @0:09:14].
   - [ ] 5. ¿Lo quiere él? ¿Conoce gente que lo quiera? Si ambas son no, "maybe nobody wants this" [SS 02 @0:09:46].
   - [ ] 6. ¿Recién se volvió posible o necesario? [SS 02 @0:09:46].
   - [ ] 7. ¿Hay proxies? (DoorDash para Rappi) [SS 02 @0:10:54].
   - [ ] 8. ¿Querría trabajar en esto años? [SS 02 @0:10:54].
   - [ ] 9. ¿Escala con software, no con mano de obra calificada? [SS 02 @0:11:57].
   - [ ] 10. ¿Buen idea space (tasa histórica de acierto)? [SS 02 @0:12:30].
4. **Las 3 que parecen malas y son buenas**: difícil, aburrida, con competidores; si la descartó por eso, volver a
   mirarla → 03-ideas.md: F3 (líneas 228-238).
5. **Altman 2014** ([YC]): why now, mercado chico que crece, "I know it sounds like a bad idea but here's specifically
   why it's actually a great one", difícil de replicar [HTSS 01 @0:09:51] [HTSS 01 @0:12:00] → F4 (líneas 239-253);
   plantillas P6 (líneas 613-622).
6. **Thiel** ([Visión]): ¿el mercado es una intersección inventada? ¿10x mejor? ¿por qué seguirías liderando en 10-20
   años? [HTSS 05 @0:09:33] [HTSS 05 @0:27:19] → F9 (líneas 333-358).
7. **Prueba contrarian de Hoffman** ([Visión]): ¿qué persona inteligente discrepa y qué sabés vos que ella no?
   [HTSS 13 @0:10:27] → P9 (líneas 648-653).
8. **Si es de IA**: checklist extra → 03-ideas.md: Checklist extra (líneas 1012-1032) y §14.
9. **Validación real**: pull (alguien usa o paga, aunque sea un prototipo tosco), uso sostenido después del "wow"
   [SS 03 @0:06:04] [AISS 09 @0:09:13] [SS 01 @0:15:24] → P7 (líneas 623-636).
10. **Compromiso**: ¿es la idea en la que más piensa sin querer? ¿quemó las otras naves? [HTSS 01 @0:06:02]
    [SS 03 @0:03:20].

### 2.3 Árbol "si falta X, hacé Y" → 03-ideas.md: Qué hacer después (líneas 1059-1075)

```
¿Qué falta?
├─ No hay idea ............ auditoría de experiencia (tres preguntas de Jared) y las 7 recetas en orden
│                           [SS 02 @0:24:40] [SS 02 @0:21:20] → 03: P1 (550-564), F7 (286-303)
├─ No hay idea ni cofundador  conversaciones con gente inteligente, side projects chicos, o trabajar en una startup
│                           [SS 01 @0:11:45] [SS 01 @0:12:58]
├─ Idea vaga .............. especificarla hasta que un ingeniero la construya; prototipo para falsar [AISS 04 @0:05:34]
├─ Sin founder-market fit . AtoB (ir a donde están) o "go undercover" [SS 02 @0:29:35] [AISS 07 @0:13:36] → P4 (585-600)
├─ Sin evidencia de demanda  pregunta de pago; landing de una tarde; hacer el servicio a mano [SS 04 @0:05:00]
│                           [HTSS 08 @0:03:16] → §4 y §5
├─ Varias ideas en paralelo  elegir una (la que más piensa sin querer), quemar naves [HTSS 01 @0:06:02] [SS 03 @0:03:20]
├─ Sin "why now" .......... formularlo; si no hay, decidir a conciencia: Altman lo pide [HTSS 01 @0:12:00],
│                           Scholl no [SS26 12 @0:21:11] (mostrar las dos)
├─ Competidores fuertes ... el insight que se perdieron, el nicho que no atienden [SS 02 @0:18:37] [AISS 12 @0:39:08]
├─ Mercado "gigante" ...... buscar el submercado chico que puede dominar [HTSS 05 @0:13:48]
└─ Semanas sin avanzar .... plan semanal; 3-4 semanas sin crecer = reconsiderar [HTSS 04 @0:48:24];
                            tesis con confianza que baja [HTSS 13 @0:40:15] → P11. Pivotar (663-677)
```

### 2.4 Señales rápidas → 03-ideas.md: Señales (líneas 1033-1058)
- Bien: nació de algo que el equipo vio de cerca; suena rara pero hay explicación específica; un usuario apasionado de
  un prototipo tosco [SS 02 @0:23:33] [HTSS 01 @0:09:51] [SS 01 @0:15:24].
- Mal: "IA para X" sin problema; "nadie lo hace" sin googlear; "somos los únicos en [intersección]"; waitlist grande
  sin un usuario apasionado; todos dicen que es buena; pivota con cada conversación [SS 02 @0:02:11]
  [HTSS 05 @0:07:09] [HTSS 13 @0:10:27] [AISS 04 @0:08:18].

### 2.5 Formato de salida: "¿Esta idea es buena?"
```
Veredicto: prometedora / dudosa / no así, en una línea, con la razón principal.
La idea como la entiendo: <una oración>. (Si no pude armarla: ese es el primer problema.)
Las 10 preguntas de Jared [SS 02]: tabla # · pregunta · sí/no/no sé · evidencia del fundador.
Lo más fuerte: 1 a 3 puntos con cita.
Lo que falta o falla: 1 a 3 puntos con cita y con quién lo dice [YC]/[Visión].
Si es de IA: prueba 0-1% de Dean, Sam Altman test, ¿asistente central? (→ §14).
Contradicción relevante (si la hay): las dos versiones y cuál aplica a su caso.
Siguiente paso (una acción de los videos, con fecha): p. ej. "hablá con 10 que tengan el problema esta semana".
```
Nunca un puntaje ponderado: los videos no dan pesos, solo dicen que founder-market fit es la más importante
(→ 03-ideas.md: Huecos (líneas 1098-1128)).

---

## 3. "¿Arranco?" / "¿Con quién?" / "¿Cómo dividimos el equity?"

→ 02-fundadores-y-cofundadores.md: Para el agente A a G (líneas 1189-1353); ficha `rapida/fundadores-y-equity.md`.

### 3.1 "¿Debería arrancar?" / "¿dejo mi trabajo?" → 02: A (líneas 1191-1222)
Checklist (cada punto con evidencia del fundador):
- [ ] Calculó el peor caso (≥ 1 año sin sueldo y cerrar) y puede vivir con él [SS 01 @0:07:22] → 02: F1 (243-261).
- [ ] Hay una idea que lo obsesiona [HTSS 01 @0:06:02]; pasa el "can't not do it" (Moskovitz, [Visión])
      [HTSS 01 @0:40:43].
- [ ] La razón no es glamour, ser jefe, flexibilidad ni plata sin hacer la cuenta [HTSS 01 @0:26:00].
- [ ] Dispuesto a ~10 años [HTSS 01 @0:31:21]; full time ("a part-time founder isn't a founder") [SS 07 @0:14:58].
- [ ] Tiene cofundador o plan concreto [SS 05 @0:02:45]; si es software, al menos un fundador técnico [SS 32 @0:16:13].
- [ ] Ya hay un side project con al menos un usuario apasionado (no una waitlist) [SS 01 @0:15:24].
Árbol:
- No está listo → plan de Harj (conversaciones, side projects, lanzarlos, aprender a programar) y de Graham ("learn a
  lot about things that matter... with people you like and respect") [SS 01 @0:10:27] [HTSS 03 @0:25:44].
- Duda por miedo → "the only way to find out is to try" [HTSS 03 @0:24:06]; la industria perdona el fracaso franco
  [SS26 13 @0:38:29].
- Se va de un empleo con mucho para perder → peor caso con números propios (ahorros, meses de runway personal)
  [SS 01 @0:07:22].
- Está en la universidad → PG: "Do not start a startup in college" [HTSS 03 @0:18:32] vs Collison, que dejó dos veces
  [SS26 09 @0:05:07] (mostrar las dos).

### 3.2 "¿Este es un buen cofundador?" / "¿Con quién fundo?" → 02: B (líneas 1223-1259)
- [ ] Se conocen hace años o trabajaron juntos bajo estrés [HTSS 02 @0:03:47] [SS 05 @0:04:24].
- [ ] Mismo objetivo (venture vs lifestyle) [SS 05 @0:06:05]; "relentlessly resourceful" [HTSS 02 @0:04:53].
- [ ] Cubre lo técnico si el fundador no [SS 05 @0:07:46]; aprende rápido [SS 05 @0:07:14].
- [ ] Respeto mutuo, CEO definido, ética de trabajo alineada: las 3 causas de ruptura [SS 05 @0:14:53]
      [SS 05 @0:16:01] [SS 05 @0:16:33].
- [ ] Finanzas personales compatibles [SS 06 @0:11:24].
- [ ] "¿Le darías casi la mitad?" Si no, no es cofundador [HTSS 02 @0:24:48].
- [ ] Hicieron las 20 horas y la conversación del divorcio (Hoffman) o un trial de 2-4 semanas [HTSS 13 @0:47:45]
      [SS 06 @0:13:35].
- [ ] Misma ciudad (Altman 2014: "don't do it" remoto [HTSS 02 @0:28:02]; los videos 2025-26 no lo retoman).
Árbol:
- Hay candidato → cuestionario → 02: Cuestionario antes de comprometerse (líneas 887-902) + trial project con plazo,
  objetivo y dueño → Plantilla de trial (líneas 903-909).
- No hay nadie → lista de gente con la que disfrutó trabajar; preguntar con el guion de Harj → 02: Pedirle a alguien
  (líneas 875-881) [SS 05 @0:09:57]; Co-Founder Matching mostrando progreso [SS 06 @0:09:14].
- Es no técnico sin técnico → aprender lo suficiente para una v1; nunca un dev shop [SS 01 @0:14:09] [SS 06 @0:12:28].
  En dev tools no hace falta cofundador de negocio [SS 17 @0:06:39]; Koomen: el técnico puede vender [SS 23 @0:02:13].
- Quiere fundar solo → "better to have no co-founder than a bad one" (Altman 2014) [HTSS 02 @0:04:19]; Altman 2026:
  solo es "very lonely" [SS26 13 @0:15:36] → 02: F5 (443-493).

### 3.3 "¿Cómo dividimos el equity?" → 02: C (líneas 1260-1284) y 9. Equity (líneas 607-662)
Pasos:
1. Confirmar alcance: el modelo de Seibel es para software con VC, pre-PMF [SS 07 @0:00:34]. Si alguien se suma
   post-PMF o tras una ronda, los videos no dan cifras (hueco).
2. Checklist:
   - [ ] Split casi igual, diferencia chica y explicable mirando hacia adelante [SS 07 @0:02:48].
   - [ ] Cada fundador ≥ 10% (si no, para YC no es cofundador) [SS 06 @0:00:33].
   - [ ] Ninguna mala razón: idea, empecé antes, edad, sueldo, desempate, MVP previo, plata levantada, "aceptó"
         [SS 06 @0:15:12] [SS 07 @0:09:28].
   - [ ] Vesting 4 años, cliff 1, para todos [SS 07 @0:04:27]; el CEO puede despedir fundadores [SS 07 @0:06:05].
   - [ ] Sin equity por desempeño, sin acuerdos dinámicos, sin part-time contados [SS 07 @0:13:50].
   - [ ] Reglas de ruptura conversadas [SS 07 @0:06:38]; definido en las primeras semanas [HTSS 02 @0:24:48].
   - [ ] Papeles firmados (EE. UU.: compra de acciones, 83(b), IP asignada) [HTSS 18 @0:11:34] [HTSS 18 @0:13:13].
3. Si sale muy desigual → preguntas de Levy ("¿qué conversación no está ocurriendo?") y el ejercicio de Seibel: ¿qué lo
   mantiene motivado en el año 3 cuando todo va mal? [HTSS 18 @0:09:22] [SS 07 @0:09:28].
4. Si uno necesita sueldo y otro no → sueldo para vivir, equity para motivar, por separado [SS 07 @0:11:39].
5. Si es sociedad colombiana → §19 (los videos no cubren SAS ni vesting local).
Contradicción: Harj y Divya dicen igual [SS 05 @0:13:45] [SS 06 @0:14:38]; Seibel, "cercana a igual" [SS 07 @0:02:48].
Por defecto: igual o casi igual con vesting; ninguno lo justifica por el pasado.
Error a avisar: "a token amount of equity 5% to 2%" [SS 07 @0:07:13] casi seguro es 0,5% a 2% (sección 18).

### 3.4 "Tengo un problema con mi cofundador" → 02: D (líneas 1285-1303)
Diagnóstico: ¿una de las 3 causas (respeto, CEO, ética)? ¿hay estructura de decisiones? ¿one-on-ones? ¿alguien
embotella o está quemado? ¿el problema real es que la empresa no anda? [SS 05 @0:14:53] [SS 06 @0:25:24]
[HTSS 02 @0:43:13]. Acción: tener la conversación ya ("death by a thousand cuts") [SS 05 @0:18:12]; desacuerdo de
producto → "ask your users" [HTSS 02 @0:43:13]; si no tiene arreglo → guías de ruptura de YC → 02: F11 (702-731).

### 3.5 Formato de salida
```
Veredicto: <arrancá / todavía no / este cofundador sí-no-falta probar / split propuesto>.
Checklist: tabla punto · cumple/no/no sé · evidencia.
Riesgo principal: <una de las 3 causas de ruptura o la que aplique> [cita].
Propuesta concreta: p. ej. "50/50, vesting 4 años con cliff de 1, CEO = X, conversación del divorcio esta semana".
Ojo jurisdicción: lo legal de los videos es EE. UU. 2014; para Colombia, ver un abogado local (los videos no lo cubren).
Siguiente paso con fecha.
```

---

## 4. "Armame el guion para hablar con usuarios" / "Revisá mis notas"

→ 04-usuarios-y-producto.md: A y B (líneas 1368-1398); 2. Guion (líneas 864-891); ficha `rapida/usuarios-y-mvp.md`.

### 4.1 Armar el guion (pasos)
1. **A quién**: tipo de persona, segmento, quién paga, quién decide, dónde se lo encuentra; sumar un grupo de no
   usuarios o usuarios de la competencia [HTSS 16 @0:04:53] [HTSS 16 @0:29:40]. Fuentes en orden: red, ex compañeros,
   fuera de tus círculos (LinkedIn, Reddit, Slack, eventos) [SS 10 @0:03:17] → 04: 1. Conseguir entrevistas (846-863).
2. **Pedido de contacto**: corto, personal, 20 minutos, sin pitch [SS 10 @0:05:25] (el texto de ejemplo de SS 10
   estaba en pantalla: hueco).
3. **Guion literal** (Gustaf [YC] + Shear) → 04: 2. Guion (líneas 864-891):
   - Apertura: "I'm thinking about starting another company and I have a couple questions... about this area I'm
     interested in" [SS 10 @0:07:00].
   - "Tell me how you do X today" [SS 10 @0:08:39]; "What software do you use for this stuff today?" [HTSS 16 @0:12:48].
   - "What is the hardest thing [about doing] X?" · "Why is it hard?" · "How often do you have to do X?" ·
     "Why is it important for your company to do X?" (profundizar acá) [SS 10 @0:08:39].
   - "What do you do to solve this problem for yourself today?" y pedir que lo muestre en pantalla [SS 10 @0:09:11].
   - Honestidad de uso: "be honest do you actually go back and ever actually look at these notes?" [HTSS 16 @0:13:20].
   - Modo detective: "huh that's interesting can you tell me more about that" [HTSS 16 @0:37:44].
   - B2B: "what's the part of your job you hate the most?", "if you could wave a magic wand..." [SS 20 @0:02:46].
4. **Prohibidas**: "¿lo usarías?", "¿qué features?", "¿cómo sería mejor?", sí/no, dobles, "¿pagarías?", "¿te gusta
   esta feature?", mostrar el producto [SS 10 @0:09:43] [HTSS 16 @0:35:03].
5. **Logística**: video, teléfono o en persona; email "basically useless"; grabar con permiso [HTSS 16 @0:36:40];
   5-10 entrevistas, 6-8 por grupo; síntesis en buckets [SS 10 @0:12:25] [HTSS 16 @0:18:12]; no pagar a los
   entrevistados [HTSS 16 @0:40:30].
6. **Idioma**: entrevistar en la lengua del cliente con gente nativa ("just really hard" en otro idioma, Twitch)
   [HTSS 16 @0:38:16].

### 4.2 Revisar un guion que trae el fundador (checklist 04 A, en orden)
- [ ] Define a quién y dónde; hay grupo de no usuarios o competencia.
- [ ] Pedido corto, 20 min, sin pitch.
- [ ] Arranca por "cómo hacés X hoy", no por la idea.
- [ ] Cubre las 6 de Gustaf.
- [ ] Pide ver el comportamiento.
- [ ] Seguimientos abiertos y modo detective.
- [ ] Ninguna prohibida.
- [ ] Video/teléfono/persona, grabado.
- [ ] Plan de 5-10 y de síntesis.
Reescritura obligada: "¿usarías una app que...?" → "Tell me how you do X today" + "What do you do to solve this
problem for yourself today?" + "Why is it important for your company to do X?" (→ 04: A (líneas 1368-1385)).

### 4.3 Leer notas o resultados (checklist 04 B) → 04: B (líneas 1386-1398)
1. ¿Las conclusiones son problemas y objetivos o una lista de features? Si son features, preguntar el porqué de cada
   una: "buenos problemas, malas soluciones" (Gmail, Airbnb) [HTSS 16 @0:31:49] [SS 10 @0:11:19].
2. ¿Hay un bloqueo grande y repetido? Si no aparece, señal quizá negativa: otro grupo [HTSS 16 @0:17:40].
3. Tres pruebas de valor: ¿ya pagan por algo?, ¿se conforman con Excel?, ¿es fácil venderles? [SS 10 @0:13:31]
4. ¿El que habla tiene el problema? Si no, "is useless at best" [SS 23 @0:07:08].
5. ¿Conocidos (curva de honestidad) o gente que pagó? [HTSS 04 @0:21:27]
6. Siguiente: hipótesis "one quantum better" sobre lo que ya usan; validarla con hack mínimo o cobro
   [HTSS 16 @0:18:48] [HTSS 16 @0:24:18].

### 4.4 Árbol "si falta X"
- Sin entrevistas → hoy 10 mensajes de 4 líneas pidiendo 20 minutos [SS 10 @0:05:25].
- Entrevistas sin bloqueo claro → cambiar de grupo (competencia, no usuarios, quien paga) [HTSS 16 @0:29:40].
- Solo encuestas → "you can learn a lot more from a five minute video interview than 500 or 5 000 survey responses"
  [SS 10 @0:05:57].
- Problema claro → §5 (MVP).
- Quiere construir una feature cara → hack mínimo o cobro por adelantado [HTSS 16 @0:23:44].

### 4.5 Formato de salida
```
Guion (listo para usar): apertura · 6-9 preguntas literales con traducción · seguimientos · cierre.
A quién: segmento, cantidad (5-10, 6-8 por grupo), dónde encontrarlos, mensaje de contacto de 4 líneas.
Si revisé su guion: tabla pregunta original → problema (regla violada + cita) → reescritura.
Si revisé notas: problemas encontrados · bloqueo repetido sí/no · 3 pruebas de valor · qué no sirve como evidencia.
Siguiente paso: cantidad de entrevistas y fecha; qué hipótesis validar después.
```
Hueco: no hay plantilla escrita de síntesis más allá de "buckets" [SS 10 @0:12:25].

---

## 5. "¿Qué es mi MVP?"

→ 04-usuarios-y-producto.md: C (líneas 1399-1418); 5. Definir y construir el MVP (líneas 910-927); F4. Ciclo del
MVP de Seibel (líneas 419-443); F5. Diana Hu (líneas 444-461).

### 5.1 Pasos (con checklist)
1. **Problema en una oración, producto en una línea** ("this does X, Y and Z"; "get your place clean for $20 an
   hour") [HTSS 04 @0:03:19] [HTSS 04 @0:13:14].
2. **Cliente con el pelo en llamas**, con nombres, no un mercado [SS 11 @0:10:28].
3. **Subconjunto más chico**: ¿qué dimensión se cortó (90/10: geografía, usuario, datos, dispositivo)? DoorDash solo en
   Palo Alto [HTSS 01 @0:20:10] [SS 09 @0:12:22].
4. **Fecha límite de 2 a 6 semanas** [SS 11 @0:14:29].
5. **Spec recortada**: cada función pasa "¿un cliente desesperado la necesita para empezar?" [SS 11 @0:15:00].
6. **Viable**: resuelve algo de punta a punta para ese grupo, aunque sea con partes manuales [HTSS 04 @0:11:37].
7. **A mano** lo que se pueda (onboarding, operación, soporte) [SS 09 @0:11:15] [HTSS 04 @0:24:44].
8. **Stack conocido + APIs de terceros**; nada de "what would Google do" [SS 09 @0:15:43].
9. **Usuarios con nombre esperando** y pitch de early adopter [SS 11 @0:03:52].
10. **Cómo se mide**: uso sostenido, retención, pago; no registros [HTSS 01 @0:24:25] [AISS 09 @0:09:13].
11. **Iterar 3 a 6 veces con los mismos usuarios** [SS 11 @0:02:12].
12. Si es hardware o IA física: cuántos nueves y cuál es lo más simple que da "multiple shots on goal"
    [SS26 08 @0:11:48] [SS26 12 @0:33:55] → 04: G (líneas 1467-1481).
13. Si lo construye con IA (vibe coding): plan en markdown con "won't do", git, tests de alto nivel, forma de
    verificar [SS 14 @0:04:55] [SS 14 @0:07:06] [SS26 14 @0:22:22] → 04: E (líneas 1436-1453). Ojo época: SS 14 es
    primavera de 2025; SS26 14 es 2026.

### 5.2 Árbol
```
¿Cómo viene el MVP?
├─ Más de un tipo de usuario, > 6 semanas, login/pagos/admin hechos a mano, "minimum lovable product",
│  microservicios → sobredimensionado: recortar con la pregunta del cliente desesperado [SS 11 @0:02:43] [SS 09 @0:16:16]
├─ No hay problema claro todavía → volver a §4 (entrevistas)
├─ Le da vergüenza lanzarlo feo → iPhone sin App Store, Google "an ugly web page" [SS 11 @0:06:05] [HTSS 01 @0:20:42];
│  ejercicio "¿este miedo es real?" [SS 11 @0:04:24]
├─ Contrata a un dev shop o freelancers → no: los fundadores construyen [SS 09 @0:09:34] [SS 06 @0:12:28]
├─ Es una demo de IA sin usuarios → "A working demo is 1% at best of the work" [SS26 08 @0:08:08]
└─ Quiere validar sin construir → landing de una tarde, Google Forms (DoorDash), servicio a mano, cobrar por adelantado
   [HTSS 08 @0:03:16] [SS 09 @0:06:11] → 04: 4. Validar (901-909)
```
Contradicción: MVP mínimo (Seibel, Kat) vs empezar ambicioso (Collison 2026, John "la versión más ambiciosa", Thiel
escéptico del lean) [SS26 09 @0:17:26] [SS 03 @0:08:15] [HTSS 05 @0:44:34]. Por defecto [YC]: lo mínimo para un grupo
chico que lo necesita mucho, dentro de una idea ambiciosa.

### 5.3 Formato de salida
```
MVP propuesto: una línea "this does X, Y and Z" para <grupo con nombre>.
Corte 90/10: qué dimensión se recortó y por qué.
Incluye (3-5 funciones) / No incluye (con la pregunta del cliente desesperado) / A mano.
Fecha: <2-6 semanas>. Usuarios con nombre que lo van a usar el día 1.
Cómo medimos: acción de valor y período (→ §10), no registros.
Precedente: Airbnb, Justin.tv, Stripe, DoorDash u Optimizely [12: fila 13].
```

---

## 6. "¿Cómo lanzo?"

→ 05-lanzamiento-y-primeros-clientes.md: A, C, D (líneas 874-923); F2 a F4 (líneas 206-249); P1. Preparar (líneas
425-442); ficha `rapida/lanzamiento.md`.

### 6.1 Checklist (05 A, en orden)
- [ ] Fecha en días o semanas, no meses: "ASAP. It's probably right now" [SS 12 @0:01:07]; Seibel 2 semanas a 1,5
      meses [SS 11 @0:14:29].
- [ ] One-liner que pasa las tres reglas (qué hace, sin jerga, corto) y versión sin "X para Y" [SS 12 @0:05:31]
      → 05: F3 (217-230).
- [ ] Landing con dominio, nombre, descripción, contacto real (no no-reply) y CTA [SS 12 @0:12:11].
- [ ] 4-5 métricas instrumentadas con definiciones escritas antes de lanzar [SS 29 @0:02:30] (lanzamientos a ciegas
      en HN o Product Hunt: no saber si retienen [SS 29 @0:00:35]).
- [ ] Tipo de lanzamiento elegido y comunidades donde participa genuinamente [SS 12 @0:14:54] → 05: F4 (231-249).
- [ ] Plan de relanzar (las próximas 3 cosas), no un solo gran día [SS 12 @0:20:22]: Airbnb lanzó tres veces
      [SS 12 @0:02:16].
- [ ] Plan para hablar uno por uno con los que se queden [SS 13 @0:06:43] [HTSS 01 @0:23:22].
- [ ] Cobra desde el inicio o hay razón explícita [SS 18 @0:13:37].
- [ ] No depende de prensa, Google Ads, una partnership ni un video caro [SS 12 @0:19:16] [HTSS 08 @0:16:59].
- [ ] Onboarding pensado (manual si hace falta) [SS 18 @0:09:13].
- [ ] Dev tool: Show HN sin marketing y respuesta a todos los comentarios [SS 17 @0:12:09] → 05: F11 (389-396).
- [ ] Hardware: pre-venta evaluada con escepticismo [SS 12 @0:18:12].

### 6.2 Árbol por situación → 05: Qué hacer después (líneas 948-967)
- **No lanzó** → fecha en días; landing silenciosa; lanzar a amigos y familia esta semana y a una comunidad la
  siguiente [SS 12 @0:12:11].
- **Lanzó y nadie se enteró** → no rendirse: iterar y relanzar en otra comunidad; revisar el one-liner
  [SS 12 @0:02:16] [SS 12 @0:03:54].
- **Pico y caída** → es la startup curve (→ 05: F1 (190-205)); hablar con los que quedaron, mirar cohortes; si no se
  aplana, producto, no growth [SS 18 @0:02:42] [HTSS 06 @0:05:59].
- **Quiere un video** → fórmula de Farza "este soy yo / esto pasa / esto hago / te muestro", primer cuadro que pase
  "¿me detendría yo?", setup 10-20%, audio bueno, link rastreable; reto de 30 días con el teléfono, no productora
  [SS 13 @0:21:41] [SS 13 @0:08:36] [SS 13 @0:45:55] → 05: C (905-914), F9 (339-365).
- **Quiere prensa** → objetivo y audiencia primero; intro cálida; sin ronda ni producto que funcione, no gastar tiempo
  [HTSS 08 @0:34:36] [SS 12 @0:19:16] → 05: D (915-923). Época: el consejo de prensa de 2014 envejeció peor; Farza
  2026: "all the old media is kind of just gone" [SS 13 @0:02:59].
- **Dominio con alto costo de falla** (salud, seguridad, IA física) → excepción defendible a "ASAP": Collison (Stripe
  tardó casi dos años pero con usuarios reales en producción) y Dolgov (nueves antes que demo) [SS26 09 @0:16:42]
  [SS26 08 @0:14:43]. Nunca como excusa para construir en secreto.

### 6.3 Formato de salida
```
Veredicto: listo para lanzar / falta X (lo mínimo que bloquea).
Fecha propuesta (en días) y tipo de lanzamiento: amigos y familia → comunidad → HN/Product Hunt → relanzamientos.
One-liner (2 versiones) y crítica con las 3 reglas.
Métricas a instrumentar antes: 4-5 con definición.
Plan post-lanzamiento: a quién llamar, cómo medir retención (→ §10).
Ojo: <prensa, ads o partnership no son plan> con cita.
```

---

## 7. "¿Cómo consigo los primeros 10 clientes?"

→ 05-lanzamiento-y-primeros-clientes.md: B (líneas 890-904); F6. Primeros 50 por tramos (líneas 262-280); P4 a P9
(líneas 474-511); 06-ventas-y-pricing.md: H (líneas 1460-1468); F3. Embudo hacia atrás (líneas 327-343).

### 7.1 Pasos
1. **Dónde vive el comprador** (Max): ¿en el email, en LinkedIn, en ferias, por teléfono, en persona? Si es directivo
   escolar, agente de seguros o despachante, el email no sirve [SS 19 @0:01:07] [SS 19 @0:02:12] → 06: P1 (613-622).
2. **Clientes 1 a 3**: lista de red personal y de segundo grado con pedidos de intro específicos [SS 19 @0:03:17]
   [SS 19 @0:03:48] → 05: P5 (482-485).
3. **Clientes 4 a 10**: al menos dos tácticas que no escalan: ir en persona, conferencia con Calendly, cena de ICP, DMs
   en Reddit a comentaristas de hilos viejos, dar algo antes de pedir [SS 19 @0:11:51] → 05: P6 a P9 (486-511).
   Precedente: un fundador legacy logró más en 3 días de feria que en 3 meses de email [SS 19 @0:01:39]; vuelo a Hawái
   [SS 19 @0:04:52].
4. **Lo hace el fundador**, no un vendedor, agencia o pasante [SS 18 @0:03:47].
5. **Embudo hacia atrás**: planilla con contactos → respuestas → demos → cierres, y metas desde el número de clientes
   [SS 18 @0:09:45] [SS 18 @0:15:49]. Error a avisar: en SS 18, 250 aperturas × 5% = 12,5, no "about 20".
6. **A quién primero**: los más fáciles de cerrar entre quienes tienen el problema, presupuesto y autoridad
   [SS 18 @0:10:18] [SS 23 @0:09:20]. Startups son fáciles solo si tienen el problema [SS 18 @0:11:57]
   [SS 23 @0:08:14].
7. **Cobrar desde el primero**; opt-out en vez de free trial [SS 18 @0:13:37] [SS 18 @0:14:43].
8. **Herramientas** (Apollo, Clay, secuencias) recién desde ~10 clientes [SS 19 @0:12:23]; automatizar no antes de ~100
   contactos manuales [SS 22 @0:00:36].
9. **Seguimiento** a cada cliente nuevo: email personal, WhatsApp o Slack [HTSS 08 @0:08:44] [SS 10 @0:15:39].

### 7.2 Árbol
- No tiene clientes 1-3 → hoy la lista de red y segundo grado y 5 pedidos de intro.
- Atascado entre 4 y 10 → una táctica que no escala por semana [SS 19 @0:04:19] [SS 19 @0:05:23].
- "Ventas no funciona" con < 200 contactos → volumen primero (06: Señales (1469-1477)).
- Cold con cero respuestas → §8 (checklist B).
- Lo da gratis "para feedback" → cobrar (Segment, Scribd) [SS 25 @0:29:13] [SS 30 @0:25:07].
- Firmó pero no usan → implementación como proyecto propio [SS 23 @0:20:18] → 06: P27 (932-943).

### 7.3 Formato de salida
```
Dónde vive tu comprador: <respuesta concreta> → canal principal.
Tramo 1-3: lista de N nombres de red / segundo grado + texto del pedido de intro.
Tramo 4-10: 2 tácticas que no escalan, con fecha y lugar.
Embudo hacia atrás: meta → tasas supuestas → contactos por semana (aclarar que las tasas son ilustrativas: Aaron dice que
no hay estándar [SS 21 @0:04:28]).
Precio y contrato desde el primero (→ §9).
Qué NO hacer todavía: herramientas, vendedores, ads.
```

---

## 8. "Revisame este cold email" (o DM de LinkedIn)

→ 06-ventas-y-pricing.md: A y B (líneas 1357-1391); F7. 7 principios de Aaron (líneas 377-399); F8. 7 reglas de
Gustaf (líneas 400-410); F9 y F10. OneSchema (líneas 411-432); P7. Plantilla integrada (líneas 665-701); ficha
`rapida/ventas-y-pricing.md`.

### 8.1 Checklist en este orden (no saltear: el targeting va primero)
1. **Targeting**: ¿la persona tiene el problema, presupuesto y autoridad? ¿Cargo con más para ganar? ¿Empresa
   verificada a mano? Si no, ningún copy lo salva [SS 21 @0:22:30] [SS 22 @0:01:15] → 06: P3 (635-646).
2. **Canal**: ¿el comprador vive en el email? (Max) [SS 19 @0:01:07].
3. **Remitente**: nombre personal del fundador [SS 21 @0:06:06].
4. **Asunto**: corto, humano, curioso; nada de marketing [SS 21 @0:06:40].
5. **Las 7 de Aaron** ([YC]), sí/no una por una: "have a focus specific goal, be human, personalize, keep it short,
   establish credibility, make sure it's all about the reader not about you and have a clear call to action"
   [SS 21 @0:20:53]. Cumplir las siete = top 5% de los mails.
6. **Largo**: ≤ 8 oraciones en email (ideal < 75 palabras); 2-5 en LinkedIn.
7. **Problema, no features**: lo que le quita el sueño o lo hace quedar bien, no "built in rust" [SS 22 @0:04:18].
8. **CTA concreta con tiempo**: "¿20 minutos esta semana?" + link o franjas, no "¿te interesa?" [SS 22 @0:05:31].
9. **Prueba de voz alta**: ¿se lo dirías así a una persona? ¿suena a LLM? [SS 19 @0:10:13]; Aaron: los LLM "often
   struggle with a lot of this personal connection" [SS 21 @0:13:14].
10. **Encuadre honesto**: si pide "consejo", ¿de verdad quiere aprender? [SS 19 @0:08:36].
11. **Follow-up**: 2-4 toques, el último breakup [SS 22 @0:09:52] → 06: P12 (748-758).
Señales de mal hecho: "hello Mr", "hi there", "love what you're doing at [company]", muro de texto, "we", "I I I",
varios pedidos, "does this sound interesting?", PS de opt-out, HTML, explicar cómo encontraste su email.

### 8.2 "Nadie responde" (checklist B) → 06: B (líneas 1380-1391); F10 (422-432)
1. ¿Mandó al menos 100 a mano? Si no, eso primero [SS 22 @0:00:36].
2. ¿Tiene números del embudo? Si no, planilla y embudo hacia atrás (F3).
3. Si < 2-3 respuestas cada 100: depurar en orden persona → empresas → asuntos → mensaje → materiales (sitio,
   LinkedIn) → entregabilidad [SS 22 @0:09:14].
4. ¿Follow-up y bloque fijo en el calendario? [SS 22 @0:10:29]
5. ¿Agotó red y segundo grado antes del cold?
6. Todo bien y sigue en cero → probablemente PMF: volver a §4 [SS 22 @0:09:14].
Hueco: entregabilidad, dominios y calentamiento no se explican (→ 06: Huecos (1501-1538)).

### 8.3 Contradicciones que cambian la respuesta → 06: Contradicciones (líneas 1304-1354)
- Valor del cold email: Aaron le dedica un video entero; Koomen lo llama "usually the least efficient way"
  [SS 23 @0:06:04]; Max: no sirve para muchos compradores. Depende de dónde vive el comprador.
- Email vs LinkedIn: Aaron, email [SS 21 @0:06:40]; Max, LinkedIn fue el canal cold de mayor conversión de un
  fundador [SS 19 @0:08:04].
- Largo: 6-8 oraciones, 5-8 oraciones, < 75 palabras; usar 75 palabras como lo más estricto.
- Plantillas: Aaron las condena pero su mail de Creative Market era plantilla: lo que importa es que se sienta
  especial [SS 21 @0:12:41] [SS 21 @0:28:03].

### 8.4 Formato de salida
```
Veredicto: mandalo / corregí y mandalo / el problema no es el copy (targeting o canal).
Targeting y canal: ok / no, por qué.
Las 7 de Aaron: tabla principio · cumple sí/no · frase del mail que lo rompe.
Reescritura completa (≤ 75 palabras, asunto incluido).
Cambios: lista "antes → después → principio violado [cita]".
Follow-up: 2-3 toques más con el breakup.
Precedente: Smoothie party, Aptin, Creative Market, Go Terps [12: fila 27].
```

---

## 9. "¿Qué precio pongo?" / "¿Hago un piloto?"

→ 06-ventas-y-pricing.md: D, E, F (líneas 1403-1451); P17 a P25 (líneas 798-924); F13. Tres partes del precio
(líneas 453-462); ficha `rapida/ventas-y-pricing.md`. IA → 10-ia-y-el-futuro.md: precio y venta (líneas 1950-1960).

### 9.1 Árbol de entrada
```
¿Qué vende?
├─ B2B (lo más cubierto) ............... 9.2
├─ Producto de IA que asiste o reemplaza trabajo  9.2 + 9.3 (marcar [Visión] salvo SS 16)
├─ Dev tool ............................ 06: G (1452-1459): runtime vs build time; open source → hosting u open core
├─ Consumo (B2C) ....................... hueco grande: solo Netflix, Scribd, el split test 80 vs 200 USD (SS 29) y
│                                        el "$5 excited" de Shear; los videos no explican freemium ni tiers de consumo
└─ No sabe qué modelo de negocio ....... 06: F (1439-1451): uno de los 9 de Aaron, uno solo, recurrente
```

### 9.2 Precio B2B: pasos (checklist 06 D) [YC]
1. **Ecuación de valor con el champion** (Tom Blomfield, inferido en SS 20; nombrado en SS 24): escribir cuánto ahorra
   o genera por año, paso a paso, y pedirle que la cuestione ("to prod it"). Precio = 25-50% del valor (≈ un tercio)
   [SS 24 @0:02:42] → 06: P18 (813-828). Ejemplo literal: 100 agentes × 100.000 USD = 10 M; elimina 20% = 2 M; cobrar
   ~700.000.
2. **Piso de costo**: margen bruto 80-90% en SaaS; créditos de nube y tokens cuentan como costo; si el tercio del
   valor no cubre el costo, "you're in a bad business" [SS 24 @0:05:27] [SS 24 @0:04:55].
3. **Competencia**: diferenciarse; nunca "igual pero más barato" [SS 25 @0:23:11].
4. **Estructura**: la que el cliente ya conoce; si es uso, con tope; preferir recurrente comprometido → 06: P19
   (829-843).
5. **Planes**: 1-2 self-serve publicados + contact sales para enterprise (SOC 2, SSO, audit logs) [SS 24 @0:10:54].
6. **Preguntas antes de cotizar** (Koomen): "How much is this problem costing your company?", "What's your budget for
   solving this problem?", "How much are you spending on my competitor?" [SS 23 @0:14:50]; número "that makes you a
   little uncomfortable" [SS 23 @0:17:32] → 06: P17 (798-812).
7. **¿Paga un vendedor?** Contrato anual × deals por AE contra 5:1 [SS 24 @0:11:28]; con contratos de ~1.000 USD/año,
   self-serve o inside sales.
8. **Calibrar**: si cierra todo al instante, subir 50% en el próximo; lo correcto es perder > 25% de deals solo por
   precio [SS 24 @0:15:26] → 06: P20 (844-859).
9. **Descuento solo a cambio de algo**: primer usuario, logo, lock-in, renovación más alta [SS 25 @0:25:55] → 06: F17
   (483-490).
Señales de que cobra de menos: precio calibrado con sus suscripciones personales; nadie se queja; cierra todo; NDR
cerca de 100%; un cliente dice como en Segment "I hope you would charge me more" [SS 24 @0:00:32] [SS 25 @0:29:13].

### 9.3 Precio de IA (visión de oradores salvo SS 16) → 06: E (1424-1438); 10: (1950-1960)
- ¿Asiste, reemplaza o lo impensable? Anclar al costo humano o a lo que cobra el profesional; lo impensable, 10-20% del
  valor (Heller) [AISS 05 @0:37:33] [AISS 05 @0:38:05].
- Vender resultado o servicio, no USD 20/mes: "sell outcomes, not seats or tokens" ([YC], SS 16) [SS 16 @0:07:15].
- Preguntar "how would you rather pay for this?" (Casetext: los clientes pidieron puesto fijo para presupuestar)
  [AISS 05 @0:26:09].
- Precio entre costo humano y costo del agente, con parte recurrente, sin ser "offensive" (Levie) [AISS 12 @0:21:07]
  [AISS 12 @0:25:27].
- Margen: poco software sobre los tokens → ~2x tokens; mucho → 80-90% [AISS 12 @0:22:44].
- Riesgo a avisar: Heller cree que la competencia baja el precio a "10 cents on the dollar" fuera de espacios
  protegidos; Levie cree que aguanta si no sos ofensivo. Mostrar las dos.

### 9.4 ¿Piloto? (árbol) → 06: P22 a P25 (866-924); F6. Escalera de contratos (362-376)
```
¿Qué propone el fundador?
├─ Piloto gratis / design partner sin pago hace meses → no: cobrar; contrato con opt-out de 30-60 días
│  [SS 18 @0:14:43] [SS 20 @0:13:44]
├─ Piloto pago → debajo del límite de firma del champion; 2-4 semanas [SS 24 @0:13:46]; métricas de éxito = la
│  ecuación de valor; pregunta "If I can solve this problem for you and deliver these metrics..., how much would that be
│  worth to you?" [SS 20 @0:09:23]
├─ Cliente listo → "pro move": "this is how customers buy our product. Typically, we offer annual contracts with a
│  30-day grace period or an opt-out..." [SS 20 @0:14:18]
└─ Muchos pilotos → pocos y que conviertan; no contarlos como ARR (Heller) [AISS 05 @0:28:20]; "the pilot is the
   product" pero limitar su número (SS 16) [SS 16 @0:07:15]
```
Error a avisar en SS 24: "$149.99" para un piloto con límite de firma de 15.000 USD es casi seguro 14.999 USD.

### 9.5 Formato de salida
```
Precio propuesto: <número y unidad> (por qué: ecuación de valor / costo humano / anclaje).
Ecuación de valor: supuestos en tabla (para validar con el champion).
Piso de costo y margen bruto estimado.
Estructura y planes: self-serve publicado / contact sales.
Piloto o contrato: tipo, duración, criterio de éxito, opt-out.
Cómo calibrar: +50% al próximo si cierra sin fricción; meta perder > 25% por precio.
[Visión] si es IA: Heller vs Levie sobre la caída de precios.
Hueco si es consumo o Latinoamérica: los videos no cubren precios por país ni freemium.
```

---

## 10. "¿Mis métricas están bien?" / "¿Por qué no retiene?" / "¿Tengo PMF?"

→ 07-metricas-retencion-y-crecimiento.md: Para el agente A a D (líneas 943-1038); F1. Cohortes (líneas 183-198);
1. Armar curvas (líneas 580-602); ficha `rapida/metricas.md`.

### 10.1 Paso cero: pedir datos crudos
Export de eventos o logs, no capturas de dashboards. "Nunca evaluar con un solo número" [07: D].

### 10.2 Diagnóstico en orden (checklist 07 A)
1. **Las tres definiciones de Lieb** ([YC]) [SS 26 @0:02:45]:
   - Cohorte por fecha de alta (después por país, canal, dispositivo).
   - Acción de "activo" = valor; rúbrica: "imagine you're sitting next to one of your customers ... what is the thing
     that's going through your head that helps you answer the question of whether that user is a good user"
     [SS 26 @0:18:04]. Si es pago: "paga **y** usó algo este mes" [SS 26 @0:17:31].
   - Período = uso esperado (diario social, semanal utilidad, trimestral/anual viajes) [SS 26 @0:06:03].
2. **¿Las curvas se aplanan?** ¿En qué nivel vs el comparable (razonamiento dimensional; Schultz: e-commerce 20-30%
   mensual, social ~80%)? [HTSS 06 @0:09:12] → 07: F8 (289-299).
3. **¿Cohortes nuevas mejores que las viejas?** [SS 26 @0:21:57]
4. **¿Las armaron a mano una vez?** [SS 26 @0:20:17]; **¿miraron usuarios individuales (dot plot)?** [SS 27]
   → 07: F7 (266-288).
5. **B2B**: retención de logos y NDR ≥ 125% temprano, nunca < 100%; asientos activados vs comprados
   [SS 29 @0:15:54] [SS 27 @0:10:50].
6. **KPI primario escrito** (tras lanzar: ingresos) + 3-5 secundarios [SS 30 @0:05:27] → 07: F20 (484-497).
7. **Crecimiento semanal** vs 5-7% bueno, 10% excepcional [SS 30 @0:19:08]; consumo: 15% mensual bueno
   [SS 28 @0:00:43].
8. **Vanidad**: registros totales, page views, GMV como ingreso, pilotos como ARR, gratuitos como crecimiento
   [SS 29 @0:05:43] [AISS 05 @0:28:20].
9. **Adquisición**: origen de cada usuario; orgánico ≥ 50% (ideal > 80%); CAC hasta usuario retenido; payback ≤ 3 meses
   (≤ 12 con riesgo) [SS 28 @0:06:45] [SS 28 @0:20:31] [HTSS 04 @0:45:39].
10. **Unit economics y margen** con COGS honestos (créditos de IA incluidos) [SS 29 @0:18:01].

### 10.3 "¿Por qué no retiene?" (árbol) → 07: C (líneas 1000-1016); F5 y F6 (236-265)
```
¿Cómo es la curva?
├─ No hay curvas → armarlas a mano (script o Sheets), luego dot plot [SS 26 @0:20:17]
├─ Va a cero → frenar growth, viralidad y pago; cortar cohortes por segmento; hablar con usuarios; atacar producto,
│  segmento, onboarding, red [HTSS 06 @0:05:59] [SS 26 @0:24:06]. Error número uno de Schultz: growth antes de que se
│  aplane.
├─ Se aplana pero bajo → magic moment: encontrarlo y llevar a todos ahí (Facebook 10 amigos en 14 días; Monzo 3
│  amigos) [SS 28 @0:15:02] [HTSS 06 @0:25:28] → 07: F10 (313-325)
├─ "Retención buena" solo en mensual → revisar si se ensanchó el período (Bump) o la acción es trivial (Google+)
│  [SS 26 @0:14:47] [SS 26 @0:16:26] → 07: F5. Cuatro formas de engañarse (236-247)
├─ Un segmento no retiene → alinear a quién se adquiere con lo que hace el producto (Google Photos y Gen Z)
│  [SS 26 @0:22:30]
├─ B2B con asientos sin activar → dot plot y proteger al champion antes de la renovación [SS 27 @0:10:50]
└─ Se aplana y quieren crecer → north star, usuario marginal, un canal por semana, viralidad (K), SEO
   [HTSS 06 @0:21:07] [HTSS 04 @0:29:49]
```

### 10.4 "¿Tengo PMF?"
Cuantitativo: curva que se aplana [HTSS 06 @0:03:14] + uso sostenido tras el pico [AISS 09 @0:09:46] + crecimiento
orgánico [HTSS 01 @0:19:37]. Cualitativo: el desafío pasó de entender qué quieren a crecer [SS 08 @0:07:23]. "Gustan
medio" (el peor caso según Altman): registros que crecen y uso que no, nadie recomienda [HTSS 01 @0:16:54].

### 10.5 Contradicciones que cambian la respuesta → 07: Contradicciones (líneas 901-942)
- 5-7% semanal (Divya, durante YC) vs 15% mensual (Blomfield, consumo): contextos distintos; aclarar cuál se usa.
- KPI en consumo: Divya, ingresos; Blomfield, base activa al principio. Por defecto: ingresos si ya cobra.
- GMV: vanidad (Blomfield) vs north star de un marketplace (Schultz, Divya): puede guiar, no reemplaza al ingreso.
- "Está pagando" como retención: Lieb exige "paga y usa"; usar el criterio de Lieb.
- Época IA: Cursor 10% semanal, Legora 1 a 100 M en un año son visiones de oradores, no benchmark de YC.
- Subtítulo de SS 28 dice "organic" donde quiso decir "paid": vale la recapitulación (≥ 50% orgánico) [SS 28 @0:20:31].

### 10.6 Formato de salida
```
Estado de retención: forma de la curva (va a cero / se aplana en X%) con definición de cohorte, acción y período.
Crecimiento: X% semanal vs 5-7% [SS 30].
Mezcla orgánico/pago y payback por canal.
Unit economics y margen (con COGS honestos).
Qué número es vanidad y cuál lo reemplaza.
Diagnóstico: <rama del árbol 10.3>.
Acción de la tabla 07 C con cita, y el próximo número a mirar en una semana.
```

---

## 11. "¿Cuánto levanto y cómo?" / "Revisá mi pitch"

→ 08-fondeo-y-yc.md: A a F (líneas 967-1034); F1. Siete mitos (líneas 220-233); F2. SAFE (líneas 234-248); F3.
Cap y dilución (líneas 249-261); F5. Cebolla (líneas 273-297); F6. Cuánto levantar (líneas 298-316); ficha
`rapida/fondeo-y-yc.md`.

### 11.1 "¿Levanto ahora?" (checklist 08 A)
- [ ] Hay producto construido (aunque sea de juguete) y usuarios [SS 31 @0:07:06].
- [ ] Hay señales de promesa: crecimiento, retención que se aplana, clientes que pagan [HTSS 19 @0:47:02].
- [ ] Es negocio de escala venture, no de 5 a 10 M/año que conviene bootstrappear [SS 08 @0:09:59].
- [ ] Sabe para qué es la plata: qué riesgos pela y qué hitos logra [HTSS 09 @0:13:04].
- [ ] Si no funciona todavía: ≤ 100.000 a 200.000 [HTSS 19 @0:47:36].
Señal de "no todavía": nada construido, deck pidiendo millones, "necesito plata para empezar". Acción: versión mínima,
10 usuarios, volver a evaluar (§5, §7).

### 11.2 "¿Cuánto y a qué cap?" (checklist 08 B y F6)
1. Lo que pelan los riesgos de esta etapa (cebolla de Rachleff/Andreessen), no "lo que pueda" [HTSS 09 @0:13:39].
2. Lo que necesitás, probando el umbral que acepta el mercado (Parker Conrad) [HTSS 09 @0:23:05].
3. Dilución: seed 10-15% (2014) o 10-20% (SAFE, ≈2022); A 20-30% [HTSS 09 @0:24:51] [SS 31 @0:18:35].
4. Proyectar la cap table sumando todos los SAFEs + la próxima ronda (ejemplo de Nathoo: ≈45% entregado)
   [HTSS 18 @0:21:57]; pregunta de Conway: ¿en qué porcentaje me desmotivo? [HTSS 09 @0:24:51]
5. Deep tech ([Visión], Hodak): precio del experimento hasta el próximo punto de inflexión de valor, x2 [SS26 06 @0:43:55].
6. No terminar con más plata de la que se puede usar (Legora: más intereses que clientes) [SS26 01 @0:13:46].
Ojo: los videos no explican pre-money vs post-money; confirmar con el documento SAFE que se use (→ 08: Huecos
(1128-1176)).

### 11.3 Revisar un pitch o primera reunión (checklist 08 C)
- [ ] Una frase que haga visualizar el producto (¿un tercero puede repetirla?) [HTSS 09 @0:04:29].
- [ ] Dos frases sin jerga [SS 32 @0:14:04].
- [ ] Demo o evidencia de uso real, no adjetivos (Retool) [SS 31 @0:13:11].
- [ ] Qué hay hoy: construido, usuarios, ingresos, crecimiento [SS 32 @0:10:53].
- [ ] Por qué puede ser enorme, aunque sea "one percent chance", en lenguaje simple [SS 31 @0:12:05].
- [ ] Riesgos pelados y por pelar con esta ronda [HTSS 09 @0:13:04].
- [ ] Números honestos: sin anual disfrazado de mensual ni pilotos como ARR [SS 32 @0:15:07] [AISS 05 @0:28:20].
- [ ] Sin NDA, sin tono de Shark Tank [HTSS 09 @0:14:15].
Deck: Moritz "I prefer to just talk about the business"; Retool sin deck [SS 31 @0:10:58]. Hueco: los videos no
explican cómo armar un deck ni conseguir reuniones paso a paso (remiten a guías de YC que no están).

### 11.4 Términos antes de firmar (checklist 08 D) → 08: D (1008-1019); F12. Pedidos de inversores (374-387)
Documento estándar (SAFE de YC o Clerky); board seat no por defecto; acciones por asesorar no; pro rata con dilución
calculada; information rights sí, presupuesto mensual no; compromiso verbal confirmado por email el mismo día; "the
burden is on you" [HTSS 18 @0:24:41].

### 11.5 Árbol
- Muchos meses sin compromisos y quiere "mejorar el pitch" → el problema es la startup: mejorar la startup, no las
  palabras [SS 31 @0:12:05]; alcanza con que "a few of them believe" [SS 31 @0:26:10].
- No hay demanda al cap → bajarlo hasta el umbral y cerrar en días [HTSS 09 @0:22:32].
- "No tengo red en Silicon Valley" → Podium, Zapier, Freshpaint [SS 31 @0:22:24]; mito 6 de Flora.
- Alguien ofrece levantar por él → pedirle solo la intro [SS 31 @0:23:30].
- Rechazos → normales (Airbnb 15 no, nVision 50+) [SS 31 @0:24:02].
- ¿No levantar? → Conway "Bootstrap as long as you possibly can" vs Flora "bootstrapping your company forever sucks"
  [HTSS 09 @0:08:36] [SS 31 @0:20:11]: mostrar las dos.

### 11.6 Formato de salida
```
Veredicto: levantá ahora / todavía no (qué falta) / levantá menos o más.
Monto propuesto: <USD> para <hitos y riesgos que pela>; dilución estimada y cap table proyectada (con supuestos).
Pitch: frase de una línea propuesta; checklist C con evidencia; 3 cambios concretos.
Términos: lo aceptable / lo que no.
Precedente: [12: filas 48-55].
Ojo jurisdicción: SAFE y Delaware son EE. UU.; levantar con inversores locales en Colombia no está cubierto (→ §19).
```

---

## 12. "Revisá mi aplicación a YC"

→ 08-fondeo-y-yc.md: G y H (líneas 1035-1061); F13. Cómo lee Dalton (líneas 388-402); F14. Qué sube y baja las
chances (líneas 403-413); 7. Aplicar a YC (líneas 584-603); 9. La entrevista (líneas 615-633).

### 12.1 Pasos
1. **Leerla como Dalton** ([YC]): las seis preguntas [SS 32 @0:10:20] a [SS 32 @0:11:57]:
   1. ¿Quiénes son, cómo se conocen, quién hace qué?
   2. ¿Cuál es la idea? ¿La entiendo?
   3. ¿Qué tienen **hoy**? ("the current state of the union").
   4. ¿Evidencia de que la gente lo quiere?
   5. ¿Evidencia de que son serios (dejaron el trabajo, más progreso que la vez anterior)?
   6. ¿Qué es impresionante, único o especial?
2. **Prueba de la "little story"**: ¿el agente puede contarla con personajes, principio y fin? ("two friends ... both
   programmers working on infrastructure at Facebook and they quit their jobs three months ago...") [SS 32 @0:12:28].
   Si no puede, la solicitud es débil: "if I can't even understand basics ... you're not even in the ballpark"
   [SS 32 @0:13:01].
3. **Checklist de forma** (08 G): todo completo con biografías; gramática y mayúsculas impecables; video según las
   instrucciones; respuestas cortas que contestan la pregunta; idea en pocas oraciones (estándar GitLab); ninguna cifra
   exagerada [SS 32 @0:09:17] [SS 32 @0:09:48] [SS 32 @0:13:32] [SS 32 @0:15:07].
4. **La variable más grande**: fundador técnico de nivel contratable en una top de YC: 5x chances; las más bajas: sin
   técnico y con tar pit sin lanzar [SS 32 @0:16:13] [SS 32 @0:16:46]. Si falta: co-founder matching.
5. **Reaplicación**: el feedback anterior atendido y visible [SS 32 @0:23:23].
6. **Si queda entrevista** (08 H): simular 10 minutos con la solicitud abierta; números, riesgos y próximo paso
   dominados; tipos de cliente sabidos al detalle (Legora fue rechazada por no saber qué abogados) [SS 32 @0:18:25]
   [SS26 01 @0:07:30]; respuestas naturales; todos los fundadores presentes.

### 12.2 Árbol
- No sabe si aplicar → Dalton: aplicá, no lo pienses tanto; buenas y malas razones para no aplicar → 08: F15
  (414-431) [SS 32 @0:07:07].
- No lanzó todavía → igual puede aplicar, pero "qué tienen hoy" pesa; lanzar antes si se puede (§6).
- Rechazado → leer el feedback, atenderlo y reaplicar mostrando progreso (Legora reaplicó dos meses después)
  [SS 32 @0:23:23] [SS26 01 @0:08:44].
- Está en Colombia → YC "fund[s] people from all over the world" [SS 32 @0:05:29]; la mecánica (Delaware desde fuera)
  no está en los videos (§19).
Hueco: el deal de YC se describe solo como "half a million dollars up front", sin desglose [SS 32 @0:04:57].

### 12.3 Formato de salida
```
La little story (como la contaría Dalton): <3-4 frases>. Si no se pudo: qué falta para poder.
Las 6 preguntas: tabla pregunta · respuesta en su solicitud · fuerte/débil · arreglo.
Cambios de forma (gramática, largo, video).
Respuesta por respuesta: original → reescrita (corta, concreta, con números).
Riesgo mayor: <técnico, tracción, claridad>.
Preguntas probables de la entrevista y respuesta de 1-2 frases para cada una.
```

---

## 13. "¿A quién contrato primero?"

→ 09-equipo-cultura-y-gestion.md: 1 y 2 (líneas 1361-1385); "¿A quién contrato primero?" (líneas 1494-1503);
3 a 8 (líneas 1386-1449); ficha `rapida/equipo.md`.

### 13.1 Paso cero: ¿contrato ahora? (checklist 09 1)
- [ ] Necesidad desesperada que los fundadores no pueden cubrir: "only hire when you have a desperate need" (Altman)
      [HTSS 02 @0:08:07].
- [ ] PMF o convicción fuerte; si no, los fundadores construyen [SS 09 @0:09:34].
- [ ] Si es ventas: el fundador ya vende de forma repetible [SS 18 @0:03:47]; Algolia, primer vendedor cerca de USD 1 M
      de ARR [SS 17 @0:21:57].
- [ ] El rol no lo cubre un agente o herramienta ([YC] 2025-26: factura de API "uncomfortably high" antes que más gente)
      [SS 15 @0:08:23].
- [ ] La persona sería un barril o hay un barril que la dirija (Rabois) [HTSS 14 @0:40:55].
- [ ] Valores escritos [HTSS 10 @0:17:26]; ~25% del tiempo del fundador para contratar [HTSS 02 @0:11:22].
Si falla alguno: no contratar todavía y decir qué hacer.

### 13.2 La respuesta guía, en orden → 09 (1494-1503)
1. Antes, los fundadores construyen y venden hasta el PMF [SS 09 @0:09:34] [SS 18 @0:03:47].
2. La primera contratación cubre la necesidad desesperada, no un rol "de manual" [HTSS 02 @0:08:07].
3. "Young scrappy" que haga cosas; por pendiente, no por logos ("hire for slope") [AISS 03 @0:30:45]
   [AISS 03 @0:31:51] [SS26 01 @0:17:50].
4. Alguien conocido o referido, probado trabajando juntos [HTSS 02 @0:13:30] [HTSS 02 @0:15:07].
5. Vara: "Will I bet the future of this company on this single hire?" [HTSS 02 @0:12:26].
6. Equity pensada: ~10% para los primeros 10, 4 años, cliff 1 [HTSS 02 @0:18:20].
Ejemplos no obvios: un cineasta (Farza) [SS 13 @0:39:22]; usuarios apasionados (Stripe) [HTSS 11 @0:50:04].

### 13.3 Proceso (si ya toca contratar) → 09: 2 a 5 (1373-1416); P3. Sourcing (708-747)
Referidos primero; 100 mails por semana firmados por fundadores y 10 entrevistas por semana [SS 33 @0:19:26]; prueba
con trabajo real difícil de hacer con IA [SS26 06 @0:13:38]; referencias con la pregunta de escasez [HTSS 11 @0:22:49];
proceso de 7 a 14 días [SS 33 @0:24:49]; JD corto que vende ≥ 30% la empresa y no suena a ChatGPT [SS 33 @0:36:33].
Error a avisar: "your response rate is roughly half of your interested rate" está invertida en el subtítulo
[SS 33 @0:18:52].

### 13.4 Otros pedidos de equipo (remisión)
- Revisar un JD → 09: 3 (1386-1394). Mail a candidato → 09: 4 (1395-1406). Entrevista → 09: 5 (1407-1416).
- Valores y cultura → 09: 6 (1417-1423), método de Lin → 09: F12 (527-541).
- Equipo de 20-50 → 09: 7 (1424-1438). ¿Lo despido? → 09: 8 (1439-1449): "every first-time founder waits too long"
  [HTSS 02 @0:22:07].
- Contratar en Colombia, EOR, contratistas internacionales → no está en los videos (§19).

### 13.5 Formato de salida
```
Veredicto: no contrates todavía (qué hacer en su lugar) / contratá <rol> ahora.
Por qué este rol: la necesidad desesperada concreta [cita].
Perfil: 3-4 rasgos, pendiente > logos, vara de Altman.
Dónde buscar y ritmo: referidos → outreach (100/semana) → proceso de 7-14 días.
Equity orientativa (rango de los videos) + hueco: no hay benchmarks por rol individual ni de salarios.
Ojo legal: lo de los videos es EE. UU. 2014.
```

---

## 14. "¿Mi startup de IA tiene sentido?" / "¿Me barre OpenAI?"

→ 10-ia-y-el-futuro.md: Para el agente (líneas 1905-2027); 6.1 ¿Me va a barrer? (líneas 1399-1416); 6.2 Qué
defiende (líneas 1417-1442); 1.1 Heller (líneas 183-206); 1.8 Dean (líneas 359-376); 1.11 John (líneas 436-454); 1.12
Servicios nativos de IA (líneas 455-487); 03-ideas.md: Checklist extra IA (líneas 1012-1032).

Regla: casi todo es [Visión]. Lo único de YC: SS 03 (cualidades de una idea), SS 14 (vibe coding), SS 15 (empresa
nativa de IA), SS 16 (servicios nativos de IA), SS 17 (dev tools). Decir la fecha (2025 o 2026) y que envejece rápido.

### 14.1 Checklist de la idea de IA (en orden)
1. **Qué trabajo pagado reemplaza o asiste**: se paga hoy a personas y sabe cuánto; no "AI is cool, what could I
   apply AI to?" (Heller) [AISS 05 @0:03:47]; asistir, reemplazar o lo impensable [AISS 05 @0:09:19].
2. **Concreta**: un ingeniero podría construirla con lo que dice (Ng) [AISS 04 @0:04:28].
3. **En el borde**: hoy apenas funciona y mejora con cada modelo ([YC], John) [SS 03 @0:06:04].
4. **Prueba de Dean**: ¿el modelo general acierta hoy 0-1% (bien) o ~20% (mal, lo va a absorber)? ¿Lo hará bien en
   6-12 meses o no en 2-3 años? [SS26 10 @0:27:45] [SS26 10 @0:28:26]
5. **Sam Altman test** ([YC], SS 16): cuando el modelo mejore, el producto se fortalece y no se commoditiza
   [SS 16 @0:03:25].
6. **No es el asistente central** de un laboratorio ni "CRM with AI" ni una de las ideas de moda [AISS 03 @0:14:57]
   [AISS 12 @0:17:51].
7. **Mercado transformado por IA** ("if your market is not truly transformed by AI, don't touch it") [AISS 12 @0:31:56].
8. **Fuente de ventaja**: datos que el modelo general no ve, contexto propio, integración profunda, confianza o
   licencias, loop de datos; si la única ventaja es "capacidad técnica", es "a rat race" (Fischer) [AISS 15 @0:21:11].
9. **Saber cómo trabaja el profesional** o plan para aprenderlo pegado al cliente [AISS 05 @0:10:25]
   [SS26 01 @0:28:12].
10. **Cuántos nueves** necesita (demo, copiloto, autónomo) [SS26 08 @0:11:48].
11. **Si es servicio con IA** ([YC], SS 16): low trust, low judgment por tarea, umbral de inteligencia alto, regulación
    a favor; humanos por juicio, no para tapar huecos; ingresos que crecen más rápido que la gente [SS 16 @0:01:48]
    [SS 16 @0:06:11].

### 14.2 "¿Me barre OpenAI?" (mostrar todos, es [Visión])
- Altman: "don't build our core chat assistant"; hay una ventana antes de necesitar foso [AISS 03 @0:14:24]
  [AISS 03 @0:15:31].
- Srinivas: "they will copy anything that's good"; "embrace" el miedo [AISS 09 @0:30:26].
- Ng: "it's not that easy to casually wipe out thousands of startups" [AISS 04 @0:29:02].
- Heller: "Just build it... Don't be scared" [AISS 05 @0:39:10].
- Collison: el miedo está "overstated" [SS26 09 @0:23:18].
- Dean: elegí lo que el modelo hace 0-1% [SS26 10 @0:28:26].
- Levie: "it's always good to overestimate your competitor's capabilities"; vendé a la parte del mercado que el
  incumbente no atiende [AISS 12 @0:40:12].
Lo que todos comparten: no hagas el asistente central; buscá vertical, datos o resultado vendido.

### 14.3 Producto de IA bien construido (checklist 10) → 10 (1934-1949); 04: E (1436-1453); 04: F15 (678-703)
Evals antes que tecnología (~100 casos por prompt antes de beta, set de reserva, cada queja se vuelve test)
[AISS 05 @0:18:39]; workflow o agente con criterio [AISS 05 @0:13:40]; forma de verificar [SS26 14 @0:19:47]; humano en
el ciclo con slider de autonomía [AISS 01 @0:19:55]; no atado a un proveedor (OpenClaw optimizado para un modelo y le
cortaron con 24 h) [SS26 05 @0:17:23]; prompt podado [SS26 14 @0:06:26].

### 14.4 Árbol → 10: Qué hacer después (1989-2009)
- No sabe cómo trabaja el cliente → "go undercover" una semana o almuerzos pagados con profesionales (Legora)
  [AISS 07 @0:13:36] [SS26 01 @0:05:16].
- No sabe si el modelo ya lo hace → darle al modelo más nuevo la tarea real con forma de verificar [SS26 14 @0:14:55].
- No tiene evals → una docena de casos reales esta semana; meta 100 por prompt [AISS 05 @0:18:39].
- Depende de un modelo → capa para cambiar de proveedor y evals contra 2-3 modelos [AISS 04 @0:37:16].
- "¿Soy un GPT wrapper?" → el trabajo real está en integraciones, verificación y evals [AISS 05 @0:38:38].
- ¿Fine-tuning? → Legora no (apostó a que mejoren los modelos); Cursor solo donde medía mejor [SS26 01 @0:30:13]
  [AISS 14 @0:16:55].

### 14.5 Formato de salida
```
Veredicto con fecha: "con lo que dicen los oradores de 2025-2026, ..." (todo [Visión] salvo SS 03, 14, 15, 16, 17).
Trabajo que reemplaza/asiste y cuánto se paga hoy.
Prueba de Dean: 0-1% / ~20% (cómo comprobarlo esta semana).
Sam Altman test: pasa / no pasa, por qué.
Fuente de ventaja: cuál; si es solo técnica, avisar "rat race".
Riesgo laboratorio: posturas (Altman, Srinivas, Collison, Dean) y lectura para su caso.
Producto: evals, verificación, independencia de proveedor.
Precio: → §9.3.
Siguiente paso concreto.
```

---

## 15. "¿Qué diría X?"

→ 11-oradores.md: Para el agente (líneas 1828-1929); Búsqueda rápida (líneas 21-130); "Qué diría" de cada capítulo.

### 15.1 Pasos → 11: Cómo responder (líneas 1830-1855)
1. Ubicar a X en la búsqueda rápida. Si no habla en estos cursos, decirlo (ver "Citados pero no oradores"). Paul Graham
   solo da HTSS 03: casi todo lo que se le atribuye en otros videos son citas de ensayos que no están (→ 11: Huecos).
2. Leer su ficha y elegir 1 a 3 ideas que respondan la pregunta concreta, con video y minuto.
3. Marcar [YC] o [Visión].
4. Poner la época (Altman 2014 ≠ Altman 2025-2026: sobre cofundadores, remoto, ideas).
5. Si la identificación es inferida, decirlo.
6. Si otro orador opina distinto, mostrarlo (→ 11: Desacuerdos (líneas 1879-1899)).
7. Cerrar con la acción concreta que sale de la cita, sin agregarle al orador cosas que no dijo.

### 15.2 Atajos por persona (fichas y "Qué diría" de los capítulos)
| X | En una línea | Detalle |
|---|---|---|
| Paul Graham [YC] | "make something users really love"; ideas que se notan, no que se piensan; no fundar en la universidad [HTSS 03] | 11: Paul Graham (591-628) |
| Michael Seibel [YC] | lanzá algo chico rápido al que tiene el pelo en llamas; equity casi igual con vesting; levantar no cambia mucho las chances [SS 11] [SS 07] | 11: Seibel (389-425) |
| Sam Altman | 2014 [YC]: why now, una oración, pocos que aman, "desperate need" para contratar. 2025-26 [Visión]: no hagas nuestro asistente; nunca hubo mejor momento | 11: Altman (133-206) |
| Jared Friedman [YC] | las 10 preguntas; founder-market fit primero | 11: Jared (766-794) |
| Harj Taggar [YC] | resiliencia; peor caso; siempre hacé la pregunta al cofundador | 11: Harj (261-301) |
| Gustaf Alströmer [YC] | "tell me how you do X today"; ¿cuántos mails y tus tasas? | 11: Gustaf (426-454) |
| Aaron Epstein [YC] | las 7 del cold email; casi seguro cobrás de menos | 11: Aaron (455-487) |
| Tom Blomfield [YC] | ecuación de valor y un tercio; ≥ 50% orgánico; NDR | 11: Blomfield (302-347) |
| Pete Koomen [YC] | calificá, no pitchees; implementación es tu trabajo | 11: Koomen (818-843) |
| Dalton Caldwell [YC] | aplicá; la little story; claro y honesto | 11: Dalton (488-516) |
| David Lieb [YC] | ¿se aplanan tus curvas? | 11: Lieb (567-590) |
| Divya [YC] | ¿cuál es tu KPI primario y tu mayor cuello de botella? | 11: Divya (517-544) |
| Diana Hu [YC] | técnico socio; prototipo en días; empresa nativa de IA | 11: Diana Hu (348-388) |
| Garry Tan | [Visión] personal: contexto propio, skills; "LinkedIn is where you get customers" | 11: Garry Tan (207-260) |
| Patrick Collison | [Visión]: problemas concretos; descorrelacionarse; miedo a laboratorios exagerado | 11: Collison (702-739) |
| Aaron Levie | [Visión]: sustantivos y verbos; precio por trabajo hecho | 11: Levie (663-701) |
| Thiel, Hoffman, Heller, Dean, Karpathy, Ng... | ver búsqueda rápida y "Qué diría" de 03, 08 y 10 | 11 (21-130); 10 (2010-2027) |

### 15.3 Formato de salida (plantilla de 11)
```
X (rol, video, año) [YC o Visión]:
- Idea 1: "frase literal" (traducción) [código @minuto]
- Idea 2: ...
Aplicado a tu caso: <acción concreta que sale de las citas>.
Ojo: <quién opina distinto o qué es inferido>.
```
Si X no habla del tema: "> **Hueco:** X no habla de esto en los videos" y ofrecer al orador que sí (→ 11: A quién
consultar (líneas 1856-1878)).

---

## 16. Cómo combinar capítulos

### 16.1 Secuencia por etapa (qué mirar según dónde está el fundador)
| Etapa | Orden de capítulos | Pregunta de corte para pasar a la siguiente |
|---|---|---|
| Sin idea / ¿fundo? | 02 A → 03 (P1, F7) | ¿Hay una idea que pasa las 10 preguntas y un cofundador? |
| Idea | 03 → 04 (entrevistas) → 10 si es IA | ¿Hay un bloqueo grande y repetido en 5-10 entrevistas? |
| Problema validado | 04 C (MVP) → 02 E (técnico) | ¿Hay usuarios con nombre y fecha de 2-6 semanas? |
| MVP | 05 (lanzar) → 07 F17 (qué medir antes) | ¿Hay uso que vuelve? |
| Primeros clientes | 05 B → 06 (cold, venta, precio) | ¿Hay 10 que pagan? |
| Retención | 07 → 04 D (¿aman?) | ¿Se aplana la curva? |
| Ronda | 08 → 07 (update) → 12 casos 48-57 | ¿Hay tracción para contar en la little story? |
| Equipo | 09 → 08 I (legal) | ¿Hay necesidad desesperada? |

### 16.2 Pedidos que cruzan capítulos (combinaciones frecuentes)
- **"¿Qué hago ahora?"** → ubicar etapa (tabla 16.1) y responder solo el cuello de botella de esa etapa: Divya, un KPI
  y el mayor cuello de botella [SS 30 @0:08:12]; progreso falso si no [SS 30 @0:10:21].
- **Idea de IA** → 03 (10 preguntas) + 10 (checklist IA) + 06 E (precio IA).
- **"Nadie me compra"** → 06 B (outbound) → si todo bien y cero, 04 (entrevistas) y 07 (PMF) [SS 22 @0:09:14].
- **"Quiero levantar para crecer"** → 07 (¿se aplana?) antes de 08: "investors want to jump on trains that are in
  motion" [SS 31 @0:06:33].
- **"Quiero contratar vendedores"** → 06 (¿el fundador cerró 10?, ratio 5:1) antes de 09.
- **Equity + legal** → 02 C + 08 I + §19.
- **Precedente** → 12 Parte 3 (1296-1379) siempre como contraste, eligiendo por etapa, tipo y época (→ 12: Para el
  agente (1406-1464)).
- **Término dudoso** → 13 antes de citar (MVP, PMF, SAFE, cohorte, champion, wedge tienen más de una versión)
  (→ 13: Para el agente (1869-1885)).

### 16.3 Precedencia cuando dos capítulos responden distinto
1. Consejo de YC de SS sobre la etapa y el tipo del fundador.
2. Altman o PG en HTSS como consejo, salvo que choque con algo de IA o 2025-26 (entonces mostrar ambos).
3. Visión de orador como contraste o para IA, marcada.
4. Casos (12) como prueba, no como regla.

---

## 17. Contradicciones y época: versión por defecto

| Tema | Una versión | La otra | Por defecto para el fundador |
|---|---|---|---|
| Lanzar ya vs tarde | "ASAP" (Kat, Seibel, Field) [SS 12 @0:01:07] | Collison: Stripe tardó con usuarios en producción; Dolgov: nueves [SS26 09 @0:16:42] | Lanzar ya; si el costo de fallar es alto, tardar pero con usuarios reales |
| Lean vs ambición | MVP mínimo (Seibel) [SS 11] | Collison 2026 "de-correlate"; Thiel escéptico [SS26 09 @0:17:26] [HTSS 05 @0:44:34] | MVP mínimo dentro de una idea ambiciosa |
| Competencia | "Competition is for losers" (Thiel) [HTSS 05 @0:00:36] | "most good startup ideas have competition" (Jared) [SS 02 @0:09:14] | Jared ([YC]); Thiel para pensar el nicho a dominar |
| Why now | Altman 2014 lo exige [HTSS 01 @0:12:00] | Scholl: no hace falta [SS26 12 @0:21:11] | Buscarlo; si no hay, decidir a conciencia |
| Experiencia de dominio | Masad, Altman 2014 [AISS 10 @0:37:44] [HTSS 19 @0:45:22] | Junestrand, John, Altman 2026 [SS26 01 @0:28:12] [SS 03 @0:01:41] | Saber exactamente cómo trabaja el cliente, venga de donde venga |
| Cofundador remoto | Altman 2014 "don't do it" [HTSS 02 @0:28:02] | Hale: Wufoo remoto con disciplina [HTSS 07 @0:42:09] | Mismo lugar al principio; los videos 2025-26 no lo retoman |
| Equity | Igual (Harj, Divya) | Casi igual (Seibel) | Igual o casi igual con vesting |
| Cold email | Aaron, video entero | Koomen "least efficient" [SS 23 @0:06:04] | Según dónde vive el comprador |
| Gratis vs cobrar | Cobrá (SS 18) | Precio menor por el primer logo (SS 25) | "Más barato" a cambio de algo sí; gratis no |
| Cuánto del valor | 25-50% (Tom) | 20% (SS 20); 10-20% lo impensable (Heller) | Un tercio en B2B; IA, anclar al costo humano |
| Precio de IA | Se mantiene si no sos ofensivo (Levie) | Baja a centavos (Heller) | Empezar en el valor, defender margen con software |
| Crecimiento | 5-7% semanal (Divya) | 15% mensual consumo (Blomfield) | Usar el de su contexto y decir cuál |
| Bootstrapping | Conway "as long as you possibly can" | Flora "forever sucks" | Mostrar ambos; levantar solo con algo construido |
| Mudarse a SF | Altman: probablemente sí [SS26 13 @0:16:48] | Scholl: basta un ecosistema [SS26 12 @0:45:48] | Estar en un ecosistema (12: fila 72) |
| LinkedIn | Wang "Ignore LinkedIn" (consejos) | Garry Tan "where you get customers" | Sí para clientes B2B |
| Escuchar usuarios | Field: feedback largo es pull | Truell: no seguir a los ruidosos | Escuchar problemas, filtrar pedidos |
| Frenar ventas | YC: vender desde el día uno | Legora frenó 6 meses con 35 M | YC; lo de Legora solo con plata y producto roto |
| Tokens | Ng: no te preocupes; Diana: factura alta | Tom 80-90% margen; SS 16 COGS | Gastar en prototipo; vigilar margen al cobrar |

Más detalle: → 03-ideas.md: Contradicciones (líneas 813-917); 05 (831-871); 06 (1304-1354); 07 (901-942); 10
(1821-1854); 11: Desacuerdos (1879-1899); 12: Contradicciones entre casos (1380-1405).

Época, regla práctica:
- **2014 (HTSS)**: vigente para cofundadores, ideas, cosas que no escalan, cultura, gestión. Viejo para: prensa
  (TechCrunch), legal (Delaware, payroll de SF, notas convertibles vs SAFE), montos de rondas, enterprise por asiento.
- **2025 (AISS)**: visión sobre IA de junio de 2025; herramientas de SS 14 (Sonnet 3.7, GPT-4.1) ya cambiaron.
- **2026 (SS26)**: lo más nuevo, también visión; modelos (Opus 5 y otros) vienen de whisper sin verificar.

---

## 18. Errores de los oradores y de subtítulos que cambian la respuesta

→ 99-fuentes-y-calidad.md: Cifras dudosas (líneas 50-61); 13-glosario.md: Correcciones (líneas 1305-1868).

| Dónde | Dice | Usar |
|---|---|---|
| SS 07 @0:07:13 | "a token amount of equity 5% to 2%" | casi seguro 0,5% a 2% (antes del cliff) |
| SS 18 @0:15:49 | 5% de 250 aperturas = "about 20" respuestas | 12,5 |
| SS 24 @0:09:49 | piloto de "$149.99" con límite de 15.000 | 14.999 USD |
| SS 24 @0:12:37 | contrato de 25.000 anual "about $22,000 a month" | ≈ 2.000 por mes |
| SS 28 @0:10:34 | "more than 50% ... organic" como problema | quiso decir pagos; vale ≥ 50% orgánico [SS 28 @0:20:31] |
| SS 29 @0:05:43 | GTV de Monzo de 500 billones | imposible; no citar la cifra |
| SS 33 @0:18:52 | respuesta = mitad de interesados | invertido: interesados ≈ mitad de respuestas |
| AISS 12 @0:21:07 | "saved me 80%" con 2 USD sobre 5-10 | ahorro de 60-80% |
| SS 08 (todo) | "simple future equity agreement", "seeding round" | retraducción automática: no citar frases literales de Dalton de ese video |
| SS26 13 | 3 meses de YC en "7 minutos", "17 segundos", "17 minutos" | cifra inconsistente: no citar |
| HTSS 07 @0:01:45 | venta de Wufoo "in 2013" | fecha dudosa (marcada en 11 y 99): no usarla |

---

## 19. Lo que los videos NO cubren (y cómo decirlo)

Decirlo siempre que el pedido toque esto. Formato: "Los videos no cubren X. Lo más cercano que dicen es Y [cita]. Para
X necesitás <tipo de fuente: abogado local, contador local>." No rellenar con conocimiento externo.

| Tema | Qué hay | Qué decir |
|---|---|---|
| **Latinoamérica como mercado** | Rappi como proxy de DoorDash, Nuvocargo "Flexport para Latinoamérica", estudio del Banco Mundial [SS 02 @0:10:54] [SS 02 @0:26:51] | Los proxies de EE. UU. sirven para validar; nada sobre tamaño de mercado, canales ni comportamiento de compra en LatAm (12: Huecos) |
| **¿Quedarse en LatAm o ir a SF?** | Altman, Scholl (12: fila 72) | Mostrar ambos; no hay guía para fundar desde Colombia |
| **Incorporar desde Colombia** (SAS, holding en Delaware) | Solo C corp de Delaware en EE. UU. 2014 [HTSS 18 @0:02:46]; YC financia de todo el mundo [SS 32 @0:05:29] | Hueco total (08: Huecos 1128-1176) |
| **Vesting, recompra, 83(b) fuera de EE. UU.** | Solo EE. UU.; la 83(b) ni siquiera se explica [HTSS 18 @0:12:41] | Hueco; el principio (vesting 4/1) sí aplica como acuerdo entre socios (02: G (1347-1353)) |
| **Ley laboral, contratar en Colombia, EOR, remoto entre países** | Solo EE. UU. 2014 [HTSS 18 @0:35:44] | Hueco (09: Huecos 1518-1551) |
| **Impuestos, contabilidad local** | IRS, CPA de EE. UU. | Hueco |
| **Levantar con inversores locales** | Nada | Hueco; el método (SAFE, little story, tracción) es de EE. UU. |
| **Precio por país, monedas, mercados emergentes** | Nada | Hueco (06: Huecos) |
| **Pricing de consumo** (freemium, tiers, prueba gratis) | Netflix, Scribd, split test 80 vs 200 (SS 29), "$5 excited" | Hueco |
| **Pitch deck paso a paso, conseguir reuniones** | Remite a guías de YC que no están [SS 31 @0:00:34] | Hueco |
| **Pre-money vs post-money, descuento, down round** | Nombrados sin definir | Hueco: confirmar en el documento |
| **Entregabilidad del email** | Paso de depuración sin explicar | Hueco |
| **Compensación de vendedores** | Solo ratio 5:1 | Hueco |
| **Benchmarks de retención por vertical, LTV completo** | Schultz (e-commerce, social), Lieb, 70-80% B2B | Usar razonamiento dimensional; hueco |
| **Salarios y equity por rol** | Solo 10% para los primeros 10 | Hueco |
| **Diapositivas** (mails de SS 18, mensajes de SS 10, tabla top 100) | No hay OCR | "Estaba en pantalla, no en el audio" |
| **Ensayos de PG** ("Do Things That Don't Scale", "How to Get Startup Ideas") | Se citan sin resumir | No resumirlos desde afuera |

---

## Huecos de esta guía

> **Hueco:** `01-principios-y-reglas.md` estaba en curso al escribir esta guía; no se pudo remitir a sus IDs (R###) ni a
> sus rangos. Cuando exista, regenerar `MAPA.md` y sumar sus remisiones en "Dónde buscar" y en la sección 17.

> **Hueco:** no hay ficha rápida de IA en `rapida/`; para IA, ir directo a `10-ia-y-el-futuro.md: Para el agente
> (líneas 1905-2027)`.

> **Hueco:** los rangos de líneas son los de `MAPA.md` regenerado al escribir esta guía; si un capítulo se edita, se
> corren. Volver a correr `herramientas/wiki/mapa.py` y verificar antes de citar un rango.

> **Hueco:** la guía no inventa pesos para comparar ideas, ni fórmulas de dilución, ni benchmarks que los videos no dan;
> donde los capítulos los marcan como hueco, acá también.
