# IA y el futuro

> Qué dicen los oradores de AI Startup School (2025) y Startup School 2026, más las charlas de IA de Startup School,
> sobre qué construir con IA, cómo construir productos y empresas con ella, hacia dónde van modelos, agentes y robots,
> qué defiende a una startup, qué pasa con el trabajo y qué predicen con fecha. Casi todo es **visión de un orador**,
> no método de YC: cada idea lleva su nombre.

Fuentes base: AISS 01 a 17 (AI Startup School, junio de 2025); SS26 01 a 15 (Startup School 2026); SS 14, 15, 16 y 17
(Startup School, módulo 03, charlas de socios de YC sobre vibe coding, empresa nativa de IA, servicios nativos de IA y
dev tools). Cómo usar herramientas de IA para construir el MVP está también en `04-usuarios-y-producto.md`; precios de
agentes en `06-ventas-y-pricing.md`; contratación en `09-equipo-cultura-y-gestion.md`; cada orador completo en
`11-oradores.md`.

**Cómo leer este capítulo**
- **Consejo de YC**: lo que dicen los socios de YC en Startup School (Tom Blomfield, Diana Hu, Jared Friedman, Garry
  Tan en su rol de presidente, etc.). Se marca "(consejo de YC)".
- **Visión de un orador**: todo lo que dicen Karpathy, Musk, Altman, Ng, Nadella, Finn, Huang y los demás invitados.
  Son opiniones, apuestas y experiencia personal, no el método de YC. Se marca con el nombre del orador. Garry Tan en
  SS26 07 habla de su propio sistema personal: también es visión suya.
- **Época**: AISS es de junio de 2025 (Claude 4, o3, Codex recién salidos); SS26 es de 2026. Lo que dicen sobre
  herramientas y modelos envejece en meses: los propios oradores lo advierten ("ask me again in a few months", Ng
  [AISS 04 @0:12:08]; "in a week this could change", Field [AISS 17 @0:20:35]). Cuando una cosa de 2025 choca con una
  de 2026, se marca.
- Las horas de cita son dentro de cada video. No hay diapositivas: donde un orador muestra un gráfico, el dato visual
  no está.

---

## Principios

Ideas que se repiten en varios oradores. Cada una es visión de quien la dice.

1. **Ahora es el mejor momento para arrancar.** "This is the best… time ever in the history of technology ever, period,
   to start a company" porque "the ground is shaking" (Sam Altman) [AISS 03 @0:23:10] [AISS 03 @0:23:41]. "When the
   clock cycle of the industry changes this much startups almost always win and we've probably never seen it change
   this much" (cuando el ciclo de la industria cambia tanto, las startups casi siempre ganan) (Altman)
   [AISS 03 @0:24:14]. "These windows don't come… but every 10 to 20 years" (Aaron Levie) [AISS 12 @0:32:30].
   En 2026 lo repite Max Junestrand (Legora): GPT-3.5 "was the internet moment of our generation" y dejó la maestría
   porque "the opportunity cost of not building had become too large" (el costo de oportunidad de no construir se
   volvió demasiado alto) [SS26 01 @0:04:35] [SS26 01 @0:05:16]. Las empresas chicas ganaron una gran ventaja sobre
   las grandes con los LLM [SS26 01 @0:38:43] [SS26 01 @0:39:19]. Altman en 2026: "never a better time to do a startup
   than right now"; "I bet there's some future trillionaires sitting in this room" [SS26 13 @0:08:12]
   [SS26 13 @0:30:37]. Jensen Huang: "the greatest time in the last 60 years to start a company", porque el computador
   se reseteó por completo [SS26 15 @0:45:33]. Alexandr Wang: "probably a once in a civilization opportunity to be a
   dreamer and to have a vision" [SS26 11 @0:09:49].
2. **No compitas con el asistente central del laboratorio.** "Don't build our core… chat assistant" (Altman)
   [AISS 03 @0:14:57]; si hacés un clon de ChatGPT "we're going to do that pretty well" [AISS 03 @0:13:52]. No hagas
   "CRM with AI": eso lo va a hacer Salesforce (Levie) [AISS 12 @0:17:51].
3. **Construí en el borde de lo que la IA puede hacer, aunque hoy no ande del todo.** "Build things that don't quite
   work yet" (Jared Kaplan) [AISS 13 @0:13:24]; "we need to be okay with building crappy products today because two
   months down the line the models will get better and your product will suddenly become viable" (Amjad Masad)
   [AISS 10 @0:04:26]. Junestrand construyó Legora sobre modelos que "no eran suficientemente buenos", apostando a que
   mejorarían: "you need to build for the world today and maybe like one step ahead" (construí para el mundo de hoy y
   quizás un paso adelante) [SS26 01 @0:29:35] [SS26 01 @0:30:53].4. **El código es barato; lo caro es acertar, verificar y llegar al usuario.** "The hard part frankly isn't building it.
   The hard part is getting it right" (Jake Heller) [AISS 05 @0:15:20]. "Agents that can write code is actually the
   easy part. The hard part is the infrastructure around it" (Masad) [AISS 10 @0:04:26]. Con la ingeniería acelerada,
   el cuello de botella pasa a producto: decidir qué construir (Andrew Ng) [AISS 04 @0:16:58]. "A new feature is just a
   prompt away, the real cost comes after" (una feature nueva está a un prompt de distancia; el costo real viene
   después) y "it is infinitely harder to evolve software that has users" (Peter Steinberger, OpenClaw)
   [SS26 05 @0:15:57] [SS26 05 @0:16:40]. "The verification I think is probably the single most important thing that
   people do not get right" (Boris Cherny, creador de Claude Code) [SS26 14 @0:19:47]. "Just because you can produce a lot of code with AI. It's not a excuse for
   not being a very good software engineer" (Junestrand) [SS26 01 @0:51:45].5. **Velocidad.** "A strong predictor for a startup's odds of success is execution speed" (Ng) [AISS 04 @0:00:32].
   "The only moat you have is speed… it's like running a marathon but at an extremely high velocity" (Aravind
   Srinivas; el subtítulo dice "mode") [AISS 09 @0:04:21]. La velocidad frente al incumbente es el superpoder de la
   empresa chica: "when you have a superpower, you need to lean into that", sin zigzaguear (Junestrand)
   [SS26 01 @0:51:03] [SS26 01 @0:51:45]. "It's hard to compete with someone who's just there having fun. Fun is
   velocity" (Steinberger) [SS26 05 @0:22:49].6. **Humano en el ciclo, IA "con correa".** "This is the decade of agents", no el año; "we need humans in the loop…
   This is software. Let's be serious here" (Andrej Karpathy) [AISS 01 @0:27:01] [AISS 01 @0:27:38]. "Less Iron Man
   robots and more Iron Man suits" [AISS 01 @0:28:09].7. **El producto primero; el foso viene después.** Lo número uno es "are you building a product that users love?"; los
   fosos están sobrevalorados y suelen llegar después (Ng) [AISS 04 @0:32:23] [AISS 04 @0:32:56]. "The most important
   thing you could do for marketing and sales is to build an amazing product" (Heller) [AISS 05 @0:25:05].
8. **Conocimiento de dominio y trabajo real.** No inventes cómo trabaja un profesional: "Don't fly blind" (Heller)
   [AISS 05 @0:14:46]; "Domain knowledge is the most important thing to build an agent company" (Masad)
   [AISS 10 @0:37:44]; "go undercover" en el trabajo que querés automatizar (Garry Tan y Satya Nadella)
   [AISS 07 @0:13:36]. **Matiz de 2026**: Junestrand dice que la experiencia de dominio no hace falta, sí "a
   willingness to learn about the market" (salvo quizás en cuántica o fusión); Legora la consiguió pegándose al
   cliente [SS26 01 @0:28:12] [SS26 01 @0:28:54].9. **Medí; no te fíes de la demo ni de tu benchmark.** Demos al 60-70% que levantan plata y "falls apart" (Heller)
   [AISS 05 @0:15:20]; "you can do vibe eval but it's really helpful to actually measure" (Chelsea Finn)
   [AISS 11 @0:23:29]; "We all overfit our ideas to the benchmark… unless you have held out" (John Jumper)
   [AISS 16 @0:17:13]. "One of the core IPs and muscles that I encourage as many of you as possible to build is the
   ability to eval new models and to eval new use cases" (Junestrand) [SS26 01 @0:34:02].10. **Elegí un mercado que la IA transforme de verdad.** "If your market is not truly transformed by AI, don't touch it"
    (Levie) [AISS 12 @0:31:56]. "Ride a tailwind" [AISS 12 @0:32:30].
11. **No te ates a un proveedor de modelos.** "Your dependencies business model is your business model… write this
    one down" (el modelo de negocio de tus dependencias es tu modelo de negocio): Steinberger optimizó OpenClaw para
    Opus y Anthropic le cortó la suscripción con ~24 horas de aviso [SS26 05 @0:18:04] [SS26 05 @0:18:42]. Junestrand
    nunca se ató a un modelo y construyó evals para enrutar [SS26 01 @0:34:02]. Ng: arquitecturá para cambiar barato de
    modelo [AISS 04 @0:37:16].
12. **La atención es lo escaso cuando el software se clona.** "Everything you can build can be forked or cloned but
    your name cannot so your personal brand is way more important than any single product", y construila "before you
    need it"; "eyeballs are kind of the most expensive currency" (Steinberger) [SS26 05 @0:12:23] [SS26 05 @0:32:48].
13. **Convicción contraria y visión propia.** "You need to develop conviction in a set of beliefs that nobody else
    agrees with"; "if you go too much with the herd, you will get immensely confused" (Wang) [SS26 11 @0:06:37]
    [SS26 11 @0:07:15]. Altman: encontrá lo que recién es posible, desarrollá "reasonable conviction" donde la
    sabiduría convencional dice que te equivocás y aceptá que tarde; "if you can't find anybody else that shares your
    belief, you should pay attention to that… if everybody believes it, that's also a bad sign" [SS26 13 @0:12:18]
    [SS26 13 @0:15:36]. Huang: "what makes great companies is a unique perspective about the world that you deeply
    believe in. It's not so much the technology. It's not so much the market even" [SS26 15 @0:05:51]. Con inteligencia
    y agencia abundantes, "the scarce resource… is going to be vision and ambition" (Wang) [SS26 11 @0:21:46].
14. **El cuello de botella es la difusión, no el modelo.** "The bottleneck is not the progress of the AI models. The
    bottleneck is diffusing that through the rest of the world"; aunque los modelos no mejoraran, habría décadas de
    cambio (Wang) [SS26 11 @0:09:49]. Coincide con Nadella (lo subestimado es la difusión) [AISS 07 @0:25:14] y Kaplan
    (no hubo tiempo de integrar la IA) [AISS 13 @0:13:56].

---

## Definiciones

Términos que usan los oradores, con su definición tal como la dan.

| Término | Definición | Quién |
|---|---|---|
| Software 1.0 / 2.0 / 3.0 | 1.0: "the code you write for the computer"; 2.0: los pesos de una red neuronal, ajustados con datos y un optimizador; 3.0: "your prompts are now programs that program the LLM", escritos en inglés | Karpathy [AISS 01 @0:01:14] [AISS 01 @0:02:59] |
| LLM como sistema operativo | El LLM es la CPU, la ventana de contexto la memoria; orquesta memoria y cómputo. "LLMs are complicated operating systems. They're circa 1960s in computing" | Karpathy [AISS 01 @0:09:41] [AISS 01 @0:13:30] |
| People spirits | "Stochastic simulations of people" (simulaciones estocásticas de personas) generadas por un transformer | Karpathy [AISS 01 @0:14:38] |
| Jagged intelligence (inteligencia dentada) | Sobrehumana en algunos dominios y con errores "that basically no human will make" (9.11 > 9.9) | Karpathy [AISS 01 @0:15:58] |
| Amnesia anterógrada de los LLM | No consolidan lo aprendido; "context windows are really kind of like working memory" | Karpathy [AISS 01 @0:16:32] |
| Intelligence brownout | Cuando los LLM de punta se caen, "the planet just gets dumber" | Karpathy [AISS 01 @0:07:47] |
| App de autonomía parcial | App dedicada (no el chat genérico) con manejo de contexto, varias llamadas a modelos, GUI para auditar y "autonomy slider" | Karpathy [AISS 01 @0:18:44] [AISS 01 @0:19:20] |
| Autonomy slider | Control para que el usuario decida cuánta autonomía cede según la tarea (en Cursor: tab, Cmd+K, Cmd+L, Cmd+I) | Karpathy [AISS 01 @0:19:55] |
| Vibe coding | Término que acuñó Karpathy en un tuit; útil "when you want to build something super-duper custom that doesn't appear to exist… because it's a Saturday" | Karpathy [AISS 01 @0:29:22] [AISS 01 @0:30:35] |
| llms.txt | "A simple markdown that's telling LLMs what this domain is about" (como robots.txt) | Karpathy [AISS 01 @0:34:07] |
| Product overhang | Distancia entre lo que los modelos pueden hacer y los productos construidos: "even if the models got no better… there's a huge amount of new stuff to build" | Altman [AISS 03 @0:04:59] |
| Just in time software | Base de datos + capa de API con permisos y reglas de negocio, y el LLM generando al vuelo la interfaz que necesitás. Altman: "That's going to happen" | Garry Tan y Altman [AISS 03 @0:22:38] [AISS 03 @0:23:10] |
| Agente como "very junior employee" | Algo a lo que le das una tarea, trabaja "for like a short period of time" y vuelve con una propuesta | Altman [AISS 03 @0:19:20] |
| Hire for slope, not y intercept | Contratar por la pendiente (qué tan rápido mejora), no por el punto de partida | Altman atribuyéndolo a "PB" (probablemente Paul Buchheit) [AISS 03 @0:31:51] |
| Idea concreta | "One that's specified in enough detail that an engineer can go and build it" | Ng [AISS 04 @0:04:28] |
| Workflow agéntico | Esquema, investigación, borrador, crítica, revisión, en ciclos, en vez de pedir todo de una vez | Ng [AISS 04 @0:03:20] |
| Puerta de una vía / de dos vías | De dos vías: decisión que se revierte barato; de una vía: "very costly or very difficult to reverse" (de Bezos) | Ng [AISS 04 @0:13:12] |
| Responsible AI | En vez de "AI safety": "safety is not a function of technology, it's a function of how we apply it" | Ng [AISS 04 @0:30:42] |
| TAM con IA | Ya no puestos por suscripción de US$ 20, sino "the combined salaries of all the people they're currently paying to do the job" ("like a thousandx bigger") | Heller [AISS 05 @0:06:00] |
| Pilot recurring revenue | Ironía: ARR inflado con pilotos pagos que no se convierten | Heller [AISS 05 @0:28:20] |
| Forward deployed engineers | "Boots on the ground people to sit next to your customer and make sure the product's actually working for them"; el "modelo Palantir" | Heller [AISS 05 @0:29:25]; Nadella [AISS 07 @0:13:03] |
| Inteligencia espacial | Capacidad de "understand the 3D world, to generate the 3D world, to reason about the 3D world, to do things in the 3D world" | Fei-Fei Li [AISS 06 @0:16:24] |
| World models | Modelos que van más allá de píxeles planos y del lenguaje y capturan la estructura 3D del mundo | Fei-Fei Li [AISS 06 @0:16:58] |
| El modelo como SQL | El modelo es un motor estable sobre el que se construye la app, como SQL lo era para las apps de negocio | Nadella [AISS 07 @0:05:05] |
| Entitlements | Qué derechos tiene un agente para actuar; con memoria y uso de herramientas, lo que hay que construir "first class around the model" | Nadella [AISS 07 @0:18:05] |
| Permiso social | "If you're going to use energy, you better have social permission to use energy": la IA tiene que generar superávit medible | Nadella [AISS 07 @0:07:55] |
| Inteligencia (Chollet) | "The efficiency with which you operationalize past information in order to deal with the future"; un ratio de eficiencia | Chollet [AISS 08 @0:07:18] |
| Inteligencia fluida | "The ability to understand something you've never seen before on the fly" | Chollet [AISS 08 @0:01:43] |
| Test-time adaptation (TTA) | Capacidad del modelo de modificar su conducta según los datos que encuentra en inferencia | Chollet [AISS 08 @0:03:24] |
| Hábitat del agente | La infraestructura donde "vive" el agente: VM en la nube, sandbox, shell, paquetes, deploy, base de datos | Masad [AISS 10 @0:04:26] |
| Computer use | "Models can go into a computer, click around and use a computer like a human does" | Masad [AISS 10 @0:11:07] |
| Individuo soberano | Alguien tan potenciado por agentes que crea enorme riqueza individualmente | Masad [AISS 10 @0:22:13] |
| Physical intelligence | Un modelo general "that can enable any robot to do any task in any environment" | Finn [AISS 11 @0:00:34] |
| Core vs context | Core: donde la empresa innova y se diferencia; context: lo que solo tiene que funcionar (Geoffrey Moore) | Levie [AISS 12 @0:28:10] |
| Leyes de escala | Tendencias "as precise as anything that you see in physics or astronomy": más cómputo, datos y tamaño dan mejora predecible | Kaplan [AISS 13 @0:04:32] |
| Horizonte temporal de tareas | "How long it would take a person to do the kinds of tasks that AI models can do"; se duplica cada ~7 meses (METR) | Kaplan [AISS 13 @0:08:55] [AISS 13 @0:09:28] |
| Flexibilidad | "The ability of AI to meet us where we are" (modalidades y ámbitos) | Kaplan [AISS 13 @0:08:22] |
| Software a demanda | Código generado en el momento cuando la app no soporta lo que quiere el usuario | Fischer [AISS 15 @0:07:07] |
| Techo de inteligencia | Punto en que para una tarea "it's good enough. We've saturated"; ahí la commoditización llega antes | Fischer [AISS 15 @0:22:50] |
| Product market pull | Señal de que la gente "pulls the product out of you": muy enganchada, obsesiva, ve el futuro de tu visión | Field [AISS 17 @0:11:24] |
| Agente reactivo / proactivo | Reactivo: ejecuta el prompt que le das. Proactivo: conectado a fuentes de contexto, empieza a trabajar solo ante un disparador; "having the agent do things without you telling it what it should do" | Junestrand [SS26 01 @0:52:24] [SS26 01 @0:53:04] |
| Y-intercept vs pendiente | Ordenada al origen: la habilidad de partida que señalan los logos del CV; pendiente: la trayectoria de crecimiento | Junestrand [SS26 01 @0:17:50] |
| Born free / born in captivity | Tecnologías sin regulación previa (internet al principio), que hay que preservar; contra las que no se pueden comercializar sin aprobación (drones y la FAA) | Kratsios [SS26 02 @0:18:49] [SS26 02 @0:19:29] |
| Preemption | Que una ley federal prevalezca sobre las estatales para evitar un "patchwork" de reglas de IA | Kratsios [SS26 02 @0:14:45] |
| Little Tech Association | Asociación creada por YC y otras empresas para representar a las startups en Washington | Kratsios [SS26 02 @0:12:33] |
| Generalización composicional | Combinar conceptos sin haber visto la combinación (la silla-aguacate de DALL·E); implica comprensión conceptual y eficiencia de datos | Finn [SS26 04 @0:25:45] [SS26 04 @0:26:29] |
| Función de valor general | Modelo entrenado con videos de experiencia del robot que estima "basically the time to success" y sirve para muchas tareas | Finn [SS26 04 @0:11:25] [SS26 04 @0:12:07] |
| Imagen de submeta | Imagen de "a few seconds from now, you should try to reach something that looks like this"; la llama "imaginación" | Finn [SS26 04 @0:28:36] [SS26 04 @0:51:10] |
| Claw | Un agente personal tipo OpenClaw: "i kind of made claw a noun" | Steinberger [SS26 05 @0:23:34] |
| Harness engineering | El trabajo sobre el arnés que envuelve al modelo | Steinberger [SS26 05 @0:18:42] |
| Heartbeat | Chequeo periódico de un agente siempre encendido; el suyo era "too static and not proactive enough" | Steinberger [SS26 05 @0:37:28] |
| Personal AGI (Garry Tan) | "General intelligence for one person you": un agente sobre tu infraestructura, tu memoria y tus procedimientos | Garry Tan [SS26 07 @0:06:11] [SS26 07 @0:06:50] |
| Skill file / resolver | Skill: "a page of english a smart intern… could follow"; "a skill file is an employee". Resolver: "an org chart" que decide qué skill o quién atiende cada tarea | Garry Tan [SS26 07 @0:17:22] [SS26 07 @0:21:14] |
| Espacio latente / determinista | Latente: gusto y juicio (en el modelo, dirigido con markdown); determinista: aritmética, SQL, agendas (código y base de datos) | Garry Tan [SS26 07 @0:18:39] |
| Personal superintelligence (Meta) | Una superinteligencia adaptada a cada persona, que conoce su contexto y es "an expander of their own agency" | Wang [SS26 11 @0:11:39] |
| Context engineering | Todo lo que rodea al modelo (recuperación, herramientas, memoria, agentes); el modelo es "only one piece" | Dean [SS26 10 @0:15:46] |
| Ablación | "You delete the entire system prompt and then you bring it back line by line"; "it's an eval but you delete things" | Cherny [SS26 14 @0:05:50] |
| Hobbling / unhobbling | El producto "gets in the way" del modelo; quitar lo que estorba | Cherny [SS26 14 @0:10:19] |
| Dynamic workflow | Función de Claude Code para orquestar "dozens, hundreds, thousands of agents"; "an algebra for agents" | Cherny [SS26 14 @0:17:21] [SS26 14 @0:26:14] |
| Loop / routine | Loop: "a cron job that's running locally"; routine: lo mismo en la nube | Cherny [SS26 14 @0:27:34] |
| Test-time compute | "A fancy way, researcher way of saying how many tokens does it generate" | Cherny [SS26 14 @0:26:55] |
| Bitter lesson | "General methods that leverage massive compute and massive data will always beat methods that rely on handcrafted engineered human knowledge" (Sutton, 2019) | Dolgov [SS26 08 @0:29:40] |
| Escalera de nueves | Cada nueve de confiabilidad adicional cuesta ~10x y exige otro enfoque | Dolgov [SS26 08 @0:11:48] |
| Physical AI | IA que actúa en el mundo físico; "the best AI moments will look like nothing happened" | Dolgov [SS26 08 @0:01:51]; Huang [SS26 15 @0:35:13] |
| Aproximador universal de funciones | Lo que Huang vio en AlexNet: deep learning "allows you to learn any function" | Huang [SS26 15 @0:11:16] |
| Permanent underclass | Meme de "entrás a un laboratorio o quedás en la clase baja permanente"; Altman lo llama "so dumb" | Altman [SS26 13 @0:08:12]; Collison [SS26 09 @0:08:21] |

---

## 1. Qué construir con IA

### 1.1 Mirá lo que hoy se paga a personas (Jake Heller, Casetext)
Visión de Heller, que vendió Casetext a Thomson Reuters por US$ 650 M en efectivo [AISS 05 @0:02:10].
- Pregunta de partida: "What do people want?… things they're paying for right now" [AISS 05 @0:03:14]
  [AISS 05 @0:03:47].
- **Las tres categorías** [AISS 05 @0:04:19] a [AISS 05 @0:05:25]:
  1. **Asistir** a un profesional (CoCounsel: leer documentos, investigar, revisar contratos, redlines).
  2. **Reemplazar** el trabajo entero ("what if we just became a law firm powered by AI?"; contadores, terapeutas
     físicos, doblar ropa).
  3. **Hacer lo antes impensable** (miles de instancias de Gemini 2.0 Flash leyendo, categorizando e indexando cientos
     de millones de documentos de un estudio).
  Resumen literal: "pick a job, replace, assist or do the… previously unthinkable" [AISS 05 @0:09:19].
- **El TAM cambia**: antes, puestos por US$ 20 al mes; ahora, los salarios que se pagan por ese trabajo (US$ 5.000 a
  20.000 al mes por profesional): el mercado sube "by a factor of 10, 100, or even a thousand" [AISS 05 @0:06:00]
  [AISS 05 @0:06:36].
- **Cómo elegir el mercado** (respuesta a una pregunta) [AISS 05 @0:31:03] a [AISS 05 @0:32:07]: (1) roles que hoy se
  tercerizan, por ejemplo a otro país; (2) evitar lo que la empresa siente como parte de su identidad; (3) mercados
  grandes; (4) dolor compartido por muchas empresas; (5) algo que conozcas o sobre lo que puedas conseguir información.
  Con un dardo sobre la lista de trabajos de conocimiento "you're going to probably hit a trillion dollar market".
- "Nobody's picking ideas the way that I recommended… very very few companies" [AISS 05 @0:09:19].
- Elegí "the biggest problem you could possibly think of that is possibly solvable with the technology and skill set
  that you have" (ejemplos: robots de limpieza, marketing y ventas de empresas) [AISS 05 @0:36:29] [AISS 05 @0:37:01].
- No es distópico: los "lamplighters" (faroleros) desaparecieron y abrieron un futuro inimaginable; "over 85% of people
  who are low income don't get access to legal services" [AISS 05 @0:07:08] [AISS 05 @0:08:13].

### 1.2 Sustantivos y verbos sin resolver (Aaron Levie, Box)
Visión de Levie [AISS 12 @0:15:42] a [AISS 12 @0:18:24]:
1. Listá los sustantivos y verbos de la vida y del trabajo (comer, dormir, viajar; nómina, CRM, email): son ~50.
2. Para cada uno preguntá si ya está resuelto respecto de un punto de referencia (él usó 2008).
3. En 2008 todo "kind of sucks"; entre 2008 y 2014 se resolvió casi todo (DoorDash, Spotify, Netflix; Gusto en
   nómina) y en 2022 solo quedaban cosas derivadas.
4. Con la IA aparece un conjunto nuevo. Pregunta guía: "what categories of professional services or work is there no
   incumbent technology for that AI agents are basically finally able to go and solve".
5. Su predicción: unas 100 startups creadas entre "el año pasado" y dentro de 3 años valdrán 5, 10 o 20 mil millones
   cada una [AISS 12 @0:18:24].
- **Datos no estructurados**: hay "basically two data types": estructurados (bases de datos) y no estructurados
  (contratos, facturas, presentaciones), que son "the vast majority of data in the enterprise" y que recién ahora los
  agentes pueden trabajar [AISS 12 @0:07:06] [AISS 12 @0:07:37] [AISS 12 @0:08:43].
- **El trabajo que nunca se hace**: la mayor parte del trabajo de dentro de 10 años será trabajo que hoy no es
  económicamente viable (traducir campañas a 100 idiomas en vez de 3 a 5; probar un trabajo que costaría contratar a
  alguien por US$ 120.000) [AISS 12 @0:10:21] [AISS 12 @0:11:26] [AISS 12 @0:11:58].
- **Core vs context**: las empresas no van a programar su propio software de context (RR. HH. de Disney: "they just
  need to pay their people on time"); sí usarán Replit, Cursor o Windsurf para el core [AISS 12 @0:28:10]
  [AISS 12 @0:29:14] [AISS 12 @0:30:19]. Que Klarna construya sus sistemas es "basically useless… cool fireside
  fodder" [AISS 12 @0:29:47].

### 1.3 Buscá la monotonía del trabajo de conocimiento (Satya Nadella y Garry Tan)
- **"Go undercover"** (consejo que YC da a investigadores, según Garry Tan): trabajar un tiempo como facturador médico
  y ver cuánto del trabajo es copiar y pegar del navegador a una planilla y a un email [AISS 07 @0:13:36]
  [AISS 07 @0:14:09].
- La monotonía ("drudgery") es "one of the most understated things as an opportunity" (Nadella) [AISS 07 @0:14:42].
- El costo está en el flujo de trabajo: en salud (18-19% del gasto de EE. UU.) "all of the cost is in workflow"; un
  alta hospitalaria con un LLM y un prompt sobre la historia clínica "would sort of pay for itself" [AISS 07 @0:09:38]
  [AISS 07 @0:10:15].
- La IA exige cambiar el artefacto y el flujo, no automatizar el viejo: el pronóstico de ventas por fax se volvió una
  planilla de Excel por email (Nadella) [AISS 07 @0:10:47] [AISS 07 @0:11:20].

### 1.4 Dónde dicen los laboratorios que hay espacio
- **Altman**: elegí algo distinto de lo que hacen todos; con algo único "you have a really nice tailwind" para
  concentrar talento [AISS 03 @0:03:20]. Evitá "las cinco ideas que todos tienen": "we are like very social creatures…
  very influenced by what other people are doing" [AISS 03 @0:15:31]. Solo en el último mes vio startups que construyen
  de verdad para modelos de razonamiento, "this sort of new square on a periodic table" [AISS 03 @0:06:08]. Nada
  grande empieza grande: elegí un mercado donde haya "some version of the future where it could be big if it works" y
  después "one dumb foot in front of the other for a long time" [AISS 03 @0:03:53] [AISS 03 @0:04:25].
- **Kaplan** (aclara que viene de investigación, no de negocios): terreno libre en tareas de mucha habilidad frente a
  una computadora con datos: finanzas (Excel), derecho (quizás más regulado) y la integración de IA en empresas
  existentes [AISS 13 @0:24:32] [AISS 13 @0:25:09]. Buscá dónde la adopción puede ser muy rápida: hoy es la
  programación, "the big question is what's next" [AISS 13 @0:14:31] [AISS 13 @0:15:07]. Hay un "overhang" en tareas
  de amplitud (biología, psicología, historia) donde combinar mucha información es clave [AISS 13 @0:22:19]
  [AISS 13 @0:22:53].
- **Diana Hu (YC)** cuenta que el año anterior las empresas de la tanda vendían copilotos (soporte con aprobación
  humana final) y en la tanda de primavera de 2025 ya venden "replacements of full workflows" [AISS 13 @0:19:33]
  [AISS 13 @0:20:07]. Kaplan agrega que hay tareas donde "70% right is good enough" y otras donde hace falta "99.9%";
  es "more fun" construir para 70-80% [AISS 13 @0:20:07] [AISS 13 @0:20:41].
- **Masad**: evitá lo saturado (agentes de software, SDR) salvo con una idea realmente nueva; preguntate "what are you
  interested in and where do you have domain knowledge?"; si sos oficial de cumplimiento, hacé el agente de
  cumplimiento [AISS 10 @0:37:12] [AISS 10 @0:37:44].
- **Ng**: "almost by definition the biggest opportunities have to be at the application layer", porque las apps son las
  que pagan a modelos, nubes y chips [AISS 04 @0:01:04] [AISS 04 @0:01:38]. Hay "a lot of white space": más
  oportunidades que gente capaz de construirlas [AISS 04 @0:34:01].
- **Nadella**: es una "golden age of system software"; hay oportunidad en infraestructura, además de modelos y
  productos [AISS 07 @0:02:47] [AISS 07 @0:03:21].
- **Finn**: en robótica, las mayores oportunidades para builders son infraestructura del lado del robot ("poca gente
  trabaja en eso") y open source (datos, modelos, recetas de fine-tuning) [AISS 11 @0:38:48] [AISS 11 @0:39:20].
- **Fischer**: lo que seguirá siendo difícil y valioso: infraestructura, energía, manufactura, chips; la robótica va
  atrasada [AISS 15 @0:21:44] [AISS 15 @0:22:16].

### 1.5 Ideas concretas, no vagas (Andrew Ng)
[AISS 04 @0:04:28] a [AISS 04 @0:08:18]
1. Detectá la vaguedad: "let's use AI to optimize healthcare assets" admite demasiadas interpretaciones.
2. Especificá hasta que un ingeniero pueda construirlo: "let patients book MRI machine slots online to optimize usage".
3. "Concreteness buys you speed"; "when you're vague, you're almost always right. But when you're concrete, you may be
   right or wrong. Either way is fine" [AISS 04 @0:05:34] [AISS 04 @0:06:06].
4. Para que la idea concreta sea buena hace falta alguien que pensó mucho el problema (Ng pensó años la educación
   online antes de Coursera, "wandering the idea maze") [AISS 04 @0:06:39] [AISS 04 @0:07:12].
5. Perseguí una hipótesis clara y "pivot on a dime" si los datos te hacen perder la fe; pero "if every piece of new data
   causes you to pivot, it probably means you're starting off from too weak a base of knowledge" [AISS 04 @0:07:45]
   [AISS 04 @0:08:18].

### 1.6 Las preguntas antes de arrancar una startup de IA (Jordan Fischer, Anthropic)
Visión de Fischer. Organiza su charla como preguntas abiertas, sin dar la mayoría de las respuestas: "Don't just have
an opinion, figure out the causal mechanisms that allow you to validate your hypothesis" [AISS 15 @0:09:16]. Asume que
"it's extremely likely that we will have AGI in the next few years. Maybe it's not two, maybe it's three"
[AISS 15 @0:03:17]. Lista completa en orden:
1. Todo cambia: ¿cómo debería impactar en mi vida? ¿Conviene siquiera arrancar? Si ya tengo startup, ¿cómo cambian
   estrategia, producto y equipo? [AISS 15 @0:01:40] [AISS 15 @0:02:12]
2. ¿Qué pasa con el lado comprador? Las empresas también se armarán con IA para comprar y adoptar más rápido; algunas
   ya construyen en casa ("I can just like throw two people at Claude Code"); recibirán llamadas de ventas de IAs.
   Creer que la IA será lenta porque las empresas compran lento es "extremely nearsighted" [AISS 15 @0:04:22]
   [AISS 15 @0:05:28].
3. ¿Se commoditiza completamente el software? ¿O la automatización sube muchísimo la vara de calidad? Quizás depende
   de la vertical [AISS 15 @0:05:28] [AISS 15 @0:07:07].
4. Si se puede escribir software a demanda, ¿hace falta hacer apps? [AISS 15 @0:07:07] [AISS 15 @0:07:40]
5. ¿Cómo debe ser la UI? ¿Generativa, multimodal? "Meet the user where they are" [AISS 15 @0:07:40] [AISS 15 @0:08:43]
6. ¿Gana el retrofit con distribución o el producto nativo de IA? Agregar un chatbot es "sprinkle pixie dust"; su
   instinto es construir desde cero, pero puede ganar el retrofit [AISS 15 @0:08:43] [AISS 15 @0:09:16]
7. ¿Se achican los equipos? Lo "nativo de IA" de hoy puede quedar viejo en 12 meses [AISS 15 @0:09:48]
8. ¿Cómo cambia el modelo de seguridad? (código a demanda; agente personal y laboral que colaboran sin filtrar
   información) [AISS 15 @0:10:21] [AISS 15 @0:11:27]
9. ¿Podés confiar en la empresa que construye el agente, aunque el modelo esté alineado? [AISS 15 @0:11:27]
10. ¿Cómo confiar en equipos chiquitos o semiautomatizados? [AISS 15 @0:13:04]
11. ¿Cómo son las nuevas barandas? Auditorías con IA [AISS 15 @0:14:43]
12. ¿Hay que comprometerse de forma vinculante a esas auditorías? [AISS 15 @0:16:23]
13. ¿Qué partes de la alineación hay que resolver para que los modelos sean económicamente viables? [AISS 15 @0:17:26]
14. ¿Hay un conjunto de datos que dé ventaja? (TSMC y ASML guardan conocimiento tácito: "Frontier LLMs do not know how
    to build a cutting edge semiconductor fab") [AISS 15 @0:18:30] [AISS 15 @0:19:35]
15. Capacidad: ¿importa el fine-tuning? ¿routers entre modelos chicos y grandes? [AISS 15 @0:20:07]
16. ¿Cuál es tu foso en un mundo post-AGI? [AISS 15 @0:21:11]
17. ¿Qué seguirá siendo difícil y valioso? [AISS 15 @0:21:44]
18. ¿Hay un techo de inteligencia por tarea? [AISS 15 @0:22:50]
19. ¿Hará falta neutralidad de la IA o de los tokens? [AISS 15 @0:23:54]
- La paradoja del foco: "focus is everything… the other truth of running a startup is you have to focus on
  everything"; por eso los fundadores están bien ubicados para pensar qué pasa con la IA [AISS 15 @0:02:12]
  [AISS 15 @0:02:45].
- Planificá a dos años (no a seis meses, el consejo de moda), sin tomarlo literal [AISS 15 @0:03:17]
  [AISS 15 @0:03:50].
- "Build something people want" también es pensar "what does society need?" [AISS 15 @0:28:15].

### 1.7 Cómo eligieron su idea algunos fundadores de IA
- **Perplexity** (Srinivas): empezó por lo único que sabía hacer (IA y ML), con cofundadores que conocía, sin idea
  clara ("the opposite of what YC advises"); primer producto: SQL en lenguaje natural sobre datos de Twitter; la señal
  no fue el "wow" sino el uso sostenido tras la caída; lanzó 7 días después de ChatGPT [AISS 09 @0:06:00]
  [AISS 09 @0:06:34] [AISS 09 @0:09:13] [AISS 09 @0:09:46]. Regla: no te ates a una idea, pero "you don't change the
  idea every week" [AISS 09 @0:06:00].
- **Cursor** (Michael Truell): primero un copiloto para CAD elegido por "boring and sleepy and uncompetitive", "an
  armchair MBA thing", sin ser ingenieros mecánicos: "a horrible choice from the get-go"; después pasaron a programación
  pese a GitHub Copilot (~US$ 100 M de ingresos en 2022) por ser "really consistent with our beliefs": si toda la
  programación iba a cambiar en 5 años, había que apuntar a eso [AISS 14 @0:07:14] [AISS 14 @0:07:48]
  [AISS 14 @0:10:27] [AISS 14 @0:11:33].
- **Casetext** (Heller): con US$ 20 M de ingresos y 100 personas, al tener acceso temprano a GPT-4 en el verano de 2022
  "we stopped everything that we were doing" y construyeron CoCounsel [AISS 05 @0:01:38] [AISS 05 @0:02:10].
- **OpenAI** (Altman): fundarla en 2015 era "coin flippy"; "99% of the world thought we were crazy. 1%… really
  resonated", y ese 1% concentró el talento [AISS 03 @0:00:34] [AISS 03 @0:02:48].
- **Legora** (Junestrand, 2026): hay dos formas de empezar: (1) elegir un **espacio** donde es obvio que algo va a
  pasar ("It was completely obvious that legal and AI was going to be a thing. How it was going to be a thing was like
  very uncertain") y "marchar en esa dirección general"; (2) elegir un **problema** específico, resolverlo con ROI claro
  y expandirse. Legora eligió el espacio [SS26 01 @0:40:48] [SS26 01 @0:41:28]. Su primer pitch fue "we are like
  ChatGPT, but we are compliant in Europe": no era fuerte, pero en ese momento alcanzaba [SS26 01 @0:30:53]. Su
  descripción en dos frases (formato que enseña YC): "Legora is the agentic operating system for lawyers, and it handles
  complex legal work from start to finish, so lawyers can achieve more than ever before", más una frase de tracción
  (más del 3% de los abogados del mundo son usuarios activos) [SS26 01 @0:00:00] [SS26 01 @0:00:36].
- **Steinberger** (OpenClaw, 2026): "my source of inspiration is usually being annoyed"; la próxima startup: algo que
  quieras usar, con marca personal ya trabajada ("the hardest problem now is like getting eyeballs"), y quizás algo
  "hard and boring", porque algo divertido aunque sea difícil hoy se clona con un prompt [SS26 05 @0:00:41]
  [SS26 05 @0:39:33] [SS26 05 @0:40:13] [SS26 05 @0:40:56]. Producto que pide que alguien construya: un sandbox rápido y
  barato para macOS, aunque "dev tools are inherently hard" [SS26 05 @0:40:56] [SS26 05 @0:41:35]. Todavía no existe
  un agente "always on, always thinking"; el software alrededor de la IA va más lento que la IA y "eso es una
  oportunidad" [SS26 05 @0:24:11] [SS26 05 @0:24:50]. El mayor cuello de botella de la infraestructura agéntica:
  gestionar cómputo local y remoto entre muchas sesiones, macOS (donde fallan casi todas las herramientas), mover
  trabajo entre máquinas y manejar una flota [SS26 05 @0:34:54] [SS26 05 @0:35:30].
- **Kratsios** (Casa Blanca, 2026): lo que deberían construir los veinteañeros es la infraestructura de ciencia
  autónoma: laboratorios en la nube que formulan hipótesis, experimentan y concluyen en loop, con agentes que publican
  recompensas por experimentos y registran resultados en un ledger [SS26 02 @0:29:54] [SS26 02 @0:30:50]. La cuántica
  "es la IA de 2017": en cinco años Washington le prestará enorme atención [SS26 02 @0:31:38] [SS26 02 @0:33:03].
  En tecnologías "born in captivity" (drones, aviación) el gobierno dice que busca "relentlessly" quitar barreras
  [SS26 02 @0:19:29].

### 1.8 Dónde puede ganar un equipo de 2 o 3 frente a los modelos generales (Jeff Dean, Google, 2026)
Visión de Dean [SS26 10 @0:25:02] a [SS26 10 @0:30:22]:
1. **Elegí algo que te entusiasme** y sea útil al mundo: "the number one selection criteria".
2. **Probá qué hacen hoy los modelos generales en ese dominio**: si fallan por completo, buena señal; si hacen algo
   pero no muy bien, mala señal (la capacidad está apareciendo y mejorará). "Look for something where the model
   succeeds zero percent or one percent of the time not 20" (buscá algo donde el modelo acierte 0% o 1%, no 20%).
3. **Preguntate si es durable**: ¿los modelos de frontera lo harán bien en 6 o 12 meses, o no en 2 o 3 años?
- Dos fuentes de ventaja: **datos que el modelo general no ve** (por ejemplo, organizar la información personal de los
  usuarios: "that's open") y **modelos de nicho** entrenados con los datos correctos, baratos y muy precisos
  (AlphaFold, ciencia de materiales, diseño de chips).
- Preguntate: "if i work on this problem and the best possible outcome happens… will the world be a lot better" o
  dirá "kind of cool but whatever"; en ese caso no le dediques tu tiempo [SS26 10 @0:52:36].
- Para ideas grandes, cálculo de servilleta: mirá los cuellos de botella y preguntá si otra forma de resolverlo daría
  10x o 100x, "squint at a problem" sin anclarte a la solución actual [SS26 10 @0:09:04] [SS26 10 @0:09:50].
- Problemas que quisiera ver resueltos: hardware e inferencia eficientes; algoritmos mucho más eficientes en datos con
  aprendizaje continuo; interacciones multiagente; mejor discurso civil; conectar gente con intereses comunes
  [SS26 10 @0:55:17] [SS26 10 @0:56:39].

### 1.9 ¿Rompe la IA el manual lean startup? (Patrick Collison, Stripe, 2026)
Visión de Collison, entrevistado por Harj Taggar (YC) [SS26 09].
- De YC aprendió "the importance of focusing on very concrete easy to explain customer problems"; es fácil
  "hallucinate" un problema que nadie siente al punto de pagar; lo que salvó a Stripe fue estar anclado en un problema
  real [SS26 09 @0:09:42] [SS26 09 @0:10:23] [SS26 09 @0:11:38].
- Con la IA el lean startup se vuelve más competitivo: hace falta "more aggressively de-correlate" y se pueden empezar
  cosas más ambiciosas desde el inicio; hace 20 años el lean startup era casi lo único posible por el capital
  disponible. Aclara que no sabe y que YC es el experto [SS26 09 @0:17:26] [SS26 09 @0:18:45]. Ejemplos de empresas
  "anti-lean": los laboratorios de IA, Anduril [SS26 09 @0:18:05].
- Stripe tardó casi dos años en lanzar públicamente, pero con usuarios en producción desde el segundo mes: si tenés
  "grounding" constante con usuarios reales "it's probably okay to not be like launch launch"; si el costo de fallar es
  alto, casi seguro hay que tardar más (Harj) [SS26 09 @0:13:32] [SS26 09 @0:16:02] [SS26 09 @0:16:42].
- "Every business is a kind of applied theory on how some aspect of the world works" [SS26 09 @0:21:58].
- Antes de levantar mucho, preguntá "what if you succeed": ¿vas a querer trabajar en eso 10, 17, 30 años?
  [SS26 09 @0:20:00] [SS26 09 @0:20:39].

### 1.10 Cómo detectan ideas los de 2026 (Wang, Altman, Huang, Scholl, Cherny)
- **Listar los insumos y ver cuál no se consigue con un botón** (Wang, origen de Scale): para entrenar un modelo hacían
  falta cómputo, código y datos; "for two out of these three things, you could just press a button online and get
  them"; para los datos no, y de ahí Scale [SS26 11 @0:04:41] [SS26 11 @0:05:23]. Su primera idea en YC (un agente de
  IA para atención médica) "will ultimately exist" pero era el momento equivocado; Jared Friedman les dijo la verdad y
  giraron [SS26 11 @0:03:22] [SS26 11 @0:04:01]. Los inversores dudaban de que datos fuera buen negocio ("none of the
  investors had ever trained a model") [SS26 11 @0:05:23].
- **La exponencial más empinada y más larga** (Wang): identificá "the exponential in the world that has both the
  steepest curve and will go the longest" (antes la ley de Moore, hoy la IA); está bien si al principio parece aburrida
  [SS26 11 @0:30:39].
- **Cuándo ganan las startups** (Altman): cuando el paisaje se mueve muy rápido, los costos bajan, los ciclos son cortos
  y los incumbentes pierden ventaja; además ahora cambió lo difícil de conseguir (expertise, contratar gente que haga
  cosas específicas) [SS26 13 @0:09:29] [SS26 13 @0:10:18]. Receta de la convicción contraria: encontrar "the really big
  brand new thing", desarrollar convicción razonable contra la sabiduría convencional, aceptar que tarde, sumar datos
  "to convince ourselves we weren't delusional", juntar una "crew of misfits" y agradecer que el mundo no entienda porque
  da tiempo sin competidores [SS26 13 @0:12:18] a [SS26 13 @0:15:36]. "Only 50 people in the world believed that AGI was
  possible… 45 of them worked at OpenAI" [SS26 13 @0:14:57]. Hacer la misma startup que todos da hype y plata, pero
  rara vez grandes resultados [SS26 13 @0:13:45]. Hard tech en YC pasó de 5-10% a 15-25% (dato de Garry Tan)
  [SS26 13 @0:06:53].
- **Una perspectiva única** (Huang): visión de alto nivel sobre algo importante, perspectiva propia, creerla
  profundamente y que perseguirla sea difícil; "it's not about building a great chip. It's about accelerating an
  algorithm domain" [SS26 15 @0:05:51] [SS26 15 @0:06:29]. Razonar desde lo nuevo con "if this, then what, if this can
  get better, then so what" (así leyó AlexNet como un aproximador universal) [SS26 15 @0:10:35] [SS26 15 @0:13:08].
- **No hace falta un "why now"** (Blake Scholl, Boom): "the answer to why now can be because I started now"; es falso
  que cada tecnología se cree en el primer momento posible: hay muchos problemas sin atacar "not for any reason other
  than nobody went and did it"; perseguir el "why now" lleva a todos al mismo espacio chico de ideas recién posibles
  [SS26 12 @0:19:58] [SS26 12 @0:21:11]. Productos que quisiera ver: IA física para manufactura, una máquina de gran
  formato que vaya de CAD a pieza con QA automático sin programador [SS26 12 @0:27:22].
- **El overhang sin capturar** (Cherny): "so much product overhang that I'm not seeing startups capture"; cualquiera en
  la sala podría crear el próximo Claude Code; probablemente haya "dozens, hundreds of opportunities like this"
  [SS26 14 @0:13:27] [SS26 14 @0:19:10]. Cómo explorarlo: darle al modelo más nuevo una tarea un poco más difícil de lo
  que creés que puede, o jugar sin fin comercial (Opus dibujando con OpenCV, algo que nadie le entrenó)
  [SS26 14 @0:14:55] [SS26 14 @0:18:31].
- **Loops de negocio agénticos** (Wang): "companies are just these like large scale feedback loops where humans are
  operating each of the edges"; la oportunidad es que sistemas agénticos operen esos loops gastando "1000x more or 1
  million x more on tokens"; con el loop y la eval correctos, un enjambre de agentes supera a "a team of 100 engineers"
  [SS26 11 @0:26:52] [SS26 11 @0:27:30] [SS26 11 @0:28:10]. Pasos: identificar el loop (clientes, satisfacción, gasto,
  contratación) o un micro-loop; definir la métrica; implementarlo con "skills, markdown files, cron jobs" y /goal;
  escalar el gasto en tokens [SS26 11 @0:28:47].
- **Ambición** (Altman): para quien tiene una idea "demasiado ambiciosa": "send me an email"; "if the highest level
  vision is clear, but the first few steps are very unclear, that's not a bad thing… At some point, you've got to just
  get some new data points" [SS26 13 @0:31:15] [SS26 13 @0:32:38].

### 1.11 Tres cualidades de una buena idea en la era de la IA (consejo de YC, SS 03, "John", socio de YC)
Viene del capítulo de ideas (`03-ideas.md`); se repite acá porque es el criterio de YC para ideas de IA:
1. **Está en el borde de lo que los modelos pueden hacer hoy**: apenas funciona con los modelos de frontera y mejora a
   medida que mejoren; conocé íntimamente los cuellos de botella; si uno no se despeja, resolverlo puede ser la empresa.
   "Live in the future and then build what's missing" [SS 03 @0:06:04] [SS 03 @0:06:36].
2. **Verticaliza**: vende un resultado, no solo software; como el costo de producir software tiende a cero, lo valioso
   es confianza, licencias, permisos regulatorios y ser dueño del resultado: "Don't build software for insurance
   companies, just be the insurer"; "just be the bank" [SS 03 @0:06:36] [SS 03 @0:07:09].
3. **Es la versión más ambiciosa de sí misma**: perseguir una idea muy ambiciosa cuesta más o menos lo mismo que una
   modesta; protege de competidores, atrae talento y tiene un foso (industrias reguladas, incumbentes SaaS de 10 mil
   millones, hard tech) [SS 03 @0:08:15] [SS 03 @0:08:48].
- Error de YC: "AI is cool, what could I apply AI to?", una solución en busca de un problema [SS 02 @0:01:39].
- Si sos empresa de IA, empezá con un humano en el loop y validá antes de gastar millones en cómputo (SS 04, fundador de
  Focal) [SS 04 @0:05:37].
- Precio (consejo de YC, Tom Blomfield): OpenAI y Anthropic bajan costos, así que "there's perhaps some argument that you
  might want to price a little bit lower now", pero es "a really risky maneuver": mantené 80-90% de margen bruto
  [SS 24 @0:06:00]. Los créditos gratis de IA no hacen desaparecer el costo: "you're hiding it for the moment"; contalos
  en el COGS [SS 29 @0:18:01].

### 1.12 Servicios nativos de IA (consejo de YC, SS 16)
El orador de SS 16 no se identifica; habla como socio de YC ("we've observed here at YC"). Es consejo de YC.
- Tesis: "some of the biggest companies of the next decade" serán servicios (seguros, legal, impuestos, auditoría)
  reconstruidos con la IA haciendo la mayor parte del trabajo y entregando el resultado, no un copiloto que el cliente
  usa; mercados de "trillions of dollars"; "we're still early"; igual llevan "a decade or more"; no te limites a lo que
  se habla en X [SS 16 @0:00:09] [SS 16 @0:01:15] [SS 16 @0:02:53].
- **Cuatro rasgos de un buen mercado** [SS 16 @0:01:48] [SS 16 @0:02:20]:
  1. **Low trust**: el trabajo ya está tercerizado y al cliente le importa el resultado, no cómo se hizo; reemplazás a un
     proveedor y aparecés "where the budget already lives".
  2. **Low judgment at the task level**: la mayoría de los pasos automatizables, el criterio humano en pocos puntos.
  3. **High intelligence threshold**: el trabajo total es difícil, tanto que hacen falta modelos de punta.
  4. **La regulación puede ser buena**: más responsabilidad legal sube la vara y el foso (Panacea).
- **Dos chequeos** [SS 16 @0:03:25]: el **"Sam Altman test"**: "as the models get better, does your service get stronger
  or does the model itself commoditize you?" (querés que se fortalezca); y evitar equipos físicos y trabajo presencial.
  Chequeo de honestidad: ¿usás humanos porque el trabajo necesita juicio o para tapar huecos del producto?
- **Fundadores**: fluidez en el dominio, fluidez en modelos ("diseñar para subirse a la curva a medida que mejoran") y
  rigor operativo: "The product is an operation" [SS 16 @0:04:33] [SS 16 @0:05:05].
- **Producto**: el humano es la interfaz con el cliente, no el producto; throughput y tiempo de ciclo son métricas de
  producto; "customers will fire you for variance faster than they will fire you for being a bit slower or a bit more
  expensive"; "if revenue scales just in line with the number of humans you add, you'll have major problems";
  "automating the process is the product" [SS 16 @0:05:38] [SS 16 @0:06:11] [SS 16 @0:06:43].
- **Pilotos**: limitá los primeros a "a small handful" (trampa de la demanda temprana: firmás muchos y te quedás
  usando humanos); no estandarices temprano [SS 16 @0:06:43] [SS 16 @0:07:15].
- **Precio**: por unidad (por declaración, reclamo, préstamo) o por resultado; evitá cost-plus ("captures your upside
  permanently") y cobrar simplemente menos que el incumbente; "you have to sell outcomes, not seats or tokens. The pilot
  is the product" [SS 16 @0:07:15] [SS 16 @0:07:47].
- **P&L**: COGS = modelos + hosting + humanos en el loop, cada uno con "a number, a trend line, and someone who owns
  them"; la apuesta es 50%+ de margen en un mercado 2 a 3 veces más grande que el de software (los servicios
  tradicionales topean en ~30%); "you will be judged on your operating income… faster than you might expect"
  [SS 16 @0:08:52] [SS 16 @0:09:25].
- **No compres un negocio de servicios para ponerle IA**: "you just can't acquire product market fit"; salvo un foso
  regulatorio rápido (licencias de seguros) [SS 16 @0:09:57] [SS 16 @0:10:30].

### 1.13 Dev tools de IA (consejo de YC, SS 17, Nicolas Dessaigne)
Con los LLM es difícil saber qué idea es buena: las "tar pit ideas" de ayer pueden funcionar hoy; ideas obvias como
observabilidad de LLM tienen docenas o cientos de competidores, así que tenés que saber cómo te vas a diferenciar,
aunque si es tu idea, empezá [SS 17 @0:02:54] [SS 17 @0:05:02] [SS 17 @0:06:07]. El resto (build time contra runtime,
open source, monetización) está en `06-ventas-y-pricing.md`.

---

## 2. Cómo construir productos con IA

### 2.1 Apps de autonomía parcial (Andrej Karpathy)
Visión de Karpathy (ex Tesla, cofundador de OpenAI, no lo dice) [AISS 01 @0:18:10] a [AISS 01 @0:28:46].
- No mandes al usuario al "sistema operativo" (copiar y pegar en ChatGPT): "It makes a lot more sense to have an app
  dedicated for this" [AISS 01 @0:18:44].
- **Cuatro propiedades** (ejemplo: Cursor): (1) el LLM maneja mucho contexto; (2) orquesta varias llamadas a modelos
  (embeddings, chat, aplicar diffs); (3) GUI propia: "GUI allows a human to audit the work of these fallible systems and
  to go faster" (diff rojo/verde, aceptar con Cmd+Y); (4) "autonomy slider" (en Cursor: tab, Cmd+K, Cmd+L, Cmd+I; en
  Perplexity: búsqueda, research, deep research) [AISS 01 @0:19:20] [AISS 01 @0:19:55] [AISS 01 @0:20:29].
- **Preguntas guía**: "Can an LLM see everything that a human can see? Can an LLM act in all the ways that a human
  could act? And can humans supervise and stay in the loop of this activity?"; y "what does a diff look like in
  Photoshop" [AISS 01 @0:21:06] [AISS 01 @0:21:43].
- **Ciclo generación-verificación**: la IA genera y el humano verifica; "it is in our interest to make this loop go as
  fast as possible". Dos palancas: (1) acelerar la verificación con lo visual ("looking at stuff is… a highway to your
  brain"); (2) "keep the AI on the leash": un diff de 1.000 líneas no sirve, "I'm still the bottleneck"; trabajar en
  "small incremental chunks" con prompts concretos [AISS 01 @0:21:43] [AISS 01 @0:22:20] [AISS 01 @0:22:57]
  [AISS 01 @0:23:34] [AISS 01 @0:24:39].
- **Artefactos intermedios auditables**: en educación, no "hey, teach me physics", sino una app para que el profesor
  cree el curso y otra que lo sirve; el curso es "an intermediate artifact… that is auditable" [AISS 01 @0:24:39]
  [AISS 01 @0:25:14].
- **Traje de Iron Man**: "less Iron Man robots and more Iron Man suits", "less like building flashy demos of autonomous
  agents and more building partial autonomy products"; con el tiempo, mover el slider a la derecha
  [AISS 01 @0:27:38] [AISS 01 @0:28:09] [AISS 01 @0:28:46].
- **Construir para agentes** (un nuevo consumidor de información, "computers, but they are human-like")
  [AISS 01 @0:33:34] a [AISS 01 @0:38:05]: (1) publicar un llms.txt; (2) docs en markdown (Vercel y Stripe); (3) "any
  time your docs say click, this is bad": cambiar cada "click" por el comando equivalente; (4) exponer MCP; (5) URLs
  que vuelven legible un repo (gitingest, DeepWiki). Conviene "meeting LLMs halfway" aunque ya puedan usar el navegador.
- Caso **MenuGen**: la demo salió en horas; hacerla real (auth, pagos, dominio, deploy) llevó una semana "clicking
  stuff" en el navegador. El cuello de botella pasó a la infraestructura escrita para humanos [AISS 01 @0:31:45]
  [AISS 01 @0:32:21] [AISS 01 @0:33:01].
- Ser fluido en los tres paradigmas (1.0, 2.0, 3.0) y elegir para cada funcionalidad; el paradigma nuevo "se come" el
  stack (en el Autopilot de Tesla las redes borraron código C++) [AISS 01 @0:04:43] [AISS 01 @0:05:25].

### 2.2 IA confiable y evals (Jake Heller)
Visión de Heller, de su experiencia con CoCounsel.
**Cuatro pasos para construir** [AISS 05 @0:09:52] a [AISS 05 @0:14:46]:
1. **Qué hace realmente el profesional**, "be like super specific": sus cofundadores eran abogados y "30 to 40% of my
   company, even the coders were lawyers"; si no tenés el dominio, "go be like an undercover agent" o buscá un
   cofundador experto.
2. **Cómo lo haría el mejor del campo con tiempo y recursos ilimitados** ("like a thousand AIs… simultaneously") y
   trabajar hacia atrás, escribiendo los pasos.
3. **Pasar a código**: la mayoría de los pasos son uno o varios prompts; si un paso puede ser determinístico, código
   común, porque "prompts are slow and expensive".
4. **Workflow o agente**: si el experto siempre sigue los mismos pasos, "make it a workflow", "just Python code", sin
   LangChain; si depende de las circunstancias, algo "more agentic", más difícil de asegurar.
- Ejemplo de flujo de "deep research" legal: entender el pedido (quizás con preguntas), plan, docenas de búsquedas,
  leer cada resultado, descartar lo irrelevante, notas de por qué importa, escribir, verificar citas. Prompts: "read the
  legal opinion and decide on a scale of zero to seven, how relevant is it"; "here's a footnote… here's the original
  resource. Is this… accurately cited or not?" [AISS 05 @0:11:32] [AISS 05 @0:12:35] [AISS 05 @0:13:08].

**Evals, paso a paso** [AISS 05 @0:17:01] a [AISS 05 @0:22:57]:
1. Definí "what does good look like?" para la tarea completa y para cada microtarea.
2. Volvelo gradable objetivamente: true/false o un número de 0 a 7.
3. Usá un framework (él usa promptfoo; "doesn't really matter").
4. Empezá con una docena de casos parecidos a lo que mandarán los clientes; llevalos al 100%; luego 50; luego 100.
5. Guardá un set de reserva (hold out) que no mirás al escribir prompts, para no sobreajustar.
6. Leé los errores: la IA falla "predictably" (ambigüedad, instrucciones poco claras); corregí con instrucciones
   explícitas y ejemplos.
7. Aguantá: "willing to spend two weeks sleeplessly working on a single prompt"; de 60% a ~97% en dos semanas; el 3%
   restante es "like a judgment call".
8. Antes de producción: ~100 tests por prompt y 100 para la tarea; con 99/100, beta avisando que no es perfecto; 1.000
   tests es "10 times better".
9. Cada queja de un cliente se vuelve un test: "we've added much more evals… from real things that happened to real
   customers than the ones we came up with in the lab".
10. Corré cada modelo nuevo contra las evals; ajustá palabra por palabra.
"If you just do these two slides… you'll be like 90% of your way there"; "Keep iterating. Never stop."
[AISS 05 @0:22:57].

### 2.3 Velocidad con IA (Andrew Ng, AI Fund)
Visión de Ng, que arma "an average of about one startup per month" en AI Fund [AISS 04 @0:00:00].
- **Workflow agéntico contra prompt lineal**: pedir todo de una vez es como escribir un ensayo "without ever using
  backspace"; el ciclo esquema, investigación, borrador, crítica, revisión "is slower but it delivers a much better
  work product" y en compliance, diagnóstico médico o documentos legales fue "the difference between it working versus
  not working" [AISS 04 @0:02:47] [AISS 04 @0:03:20] [AISS 04 @0:03:55].
- **Dos tipos de software**: prototipos rápidos y sucios, "easily 10 times faster"; producción y legado, "maybe we're
  30 to 50% faster" [AISS 04 @0:09:56] [AISS 04 @0:10:28]. Código inseguro está bien en un prototipo en tu laptop;
  antes de mandarlo a otros, hacelo seguro y escalable: "move fast and be responsible" [AISS 04 @0:11:03]
  [AISS 04 @0:12:08]. Construyen 20 prototipos para ver cuál pega [AISS 04 @0:11:34].
- **Puertas de dos vías**: elegir arquitectura era de una vía; hoy hay equipos que "completely rebuilt a codebase three
  times the last month"; repensá qué es reversible, "I don't want to overhype it" [AISS 04 @0:13:12] [AISS 04 @0:14:16].
- **El cuello de botella pasa a producto**: ratio histórico de 1 PM por 4 a 7 ingenieros; un equipo le propuso 1 PM por
  0,5 ingenieros; no sabe si es buena idea pero es "a sign of where the world is going" [AISS 04 @0:16:58]
  [AISS 04 @0:17:38] [AISS 04 @0:18:10].
- **Menú de tácticas de feedback**, de la más rápida y menos precisa a la más lenta y precisa: (1) tu instinto; (2) tres
  amigos; (3) 3 a 10 desconocidos en cafés o lobbies ("hey we're building this thing do you mind taking a look");
  (4) 100 testers; (5) más usuarios; (6) A/B testing, "now one of the slowest tactics in my menu". Usá los datos lentos
  para "update our mental model" y mejorar el instinto [AISS 04 @0:18:43] a [AISS 04 @0:20:52].
- **Entender IA da velocidad**: una decisión de arquitectura es "one bit"; acertarla te resuelve en "a couple days" y
  errarla te puede costar "three months" [AISS 04 @0:22:28] [AISS 04 @0:23:00]. Bloques de construcción (prompting,
  workflows, evals, guardrails, RAG, voz, embeddings, fine-tuning, etc.) se combinan como Lego, "combinatorially"
  [AISS 04 @0:23:36] [AISS 04 @0:24:40].
- **Las cinco claves** (resumen final): ideas concretas; ingeniería rápida con asistentes de código; portafolio de
  tácticas de feedback rápido; hablar con desconocidos con respeto; mantenerse al día [AISS 04 @0:25:13]
  [AISS 04 @0:26:18]. Estar en la última generación de herramientas: "even half a generation or one generation behind
  actually makes a big difference" [AISS 04 @0:12:40].
- **Modelos y costos**: construí evals propias, corrélas con cada modelo nuevo y cambiá si gana ("sometimes our
  engineers will change it without even bothering to tell me"); arquitecturá para cambiar barato de modelo; "to first
  approximation just don't worry about how much tokens cost" [AISS 04 @0:35:06] [AISS 04 @0:36:43] [AISS 04 @0:37:16].

### 2.4 El modelo es el motor; el producto es el circuito de datos (Satya Nadella)
Visión de Nadella (CEO de Microsoft) [AISS 07 @0:04:29] a [AISS 07 @0:06:13] y [AISS 07 @0:18:05] a [AISS 07 @0:19:11].
- "Is the model like SQL or is it the SaaS app itself?" Su postura: "the model is just like SQL was to me"; se puede
  construir una capa de aplicación encima.
- Piezas: el modelo; el andamiaje y llamadas a herramientas ("a real app server"); y lo decisivo, el circuito de
  retroalimentación: "the data path inside the product that then is used in order to post train in order to be able to
  do the right tool selection. That seems to be the place where product creation is all going to happen".
- La próxima frontera son tres sistemas "first class around the model": (1) memoria; (2) uso de herramientas;
  (3) "entitlements", "perhaps the most important thing". Un agente "has an ID… management and provision control on it".
- Todo producto tiene que responder tres preguntas: privacidad (para cada usuario), seguridad (para cada cliente) y
  soberanía (para cada país) [AISS 07 @0:29:48] [AISS 07 @0:30:22].
- El freno principal no es técnico sino la gestión del cambio ("social rate limiter"); por eso ingenieros desplegados
  en el cliente [AISS 07 @0:12:29] [AISS 07 @0:13:03].
- Medí la IA en estadísticas reales, no en benchmarks: "prove unequivocally that what we have created is showing up in
  real stats" [AISS 07 @0:08:30] [AISS 07 @0:09:04].

### 2.5 Agentes de código: hábitat, autonomía y confiabilidad (Amjad Masad, Replit)
Visión de Masad.
- **El hábitat** [AISS 10 @0:04:26] a [AISS 10 @0:07:13]: VM en la nube en sandbox, escalable, cualquier lenguaje, shell,
  archivos, paquetes, deploy y bases de datos: "really think about everything you do as a software engineer and all
  those tools need to be accessible to software engineering agents". Integrá servicios en vez de dejar que el agente
  los programe: "agents are actually not very good [at] authentication. It's better to use a built-in service".
- **Hoja de ruta del hábitat**: acceso universal a modelos; pagos (y una billetera para que el agente contrate
  servicios como Twilio); contratar humanos (TaskRabbit ante un CAPTCHA); agente a agente ("MCP is a more traditional
  RPC protocol. So it's not really going to solve this") [AISS 10 @0:07:13] a [AISS 10 @0:08:51].
- **Niveles de autonomía** (analogía con la conducción): 1, language server; 2, autocompletado (Copilot); 3, el primer
  Replit Agent; Agent v2 ≈ 3,5 (10-15 minutos solo, hay que probarlo); Agent v3 ≈ 4; siguiente, en "los próximos dos
  años": lanzar 1.000 agentes con 95% de éxito [AISS 10 @0:09:25] a [AISS 10 @0:11:07].
- **Tres pilares de Agent v3**: (1) que el agente se pruebe solo con computer use ("build a product at the edge of
  what's possible"; permitirá trabajar de 30 minutos a 2 horas); (2) muestreo en paralelo sobre un sistema de archivos
  transaccional: bifurcarse N veces, elegir la mejor solución y mergearla (confiabilidad "two to three folds"); (3) tests
  por cada feature en cada cambio, para no romper lo anterior [AISS 10 @0:11:42] a [AISS 10 @0:15:02].
- Crítica: el cómputo en inferencia sin entorno es el modelo "just sitting in place and thinking"; el feedback del
  entorno lleva más lejos que el entrenamiento [AISS 10 @0:12:48] [AISS 10 @0:32:51].

### 2.6 Cómo construyeron Cursor, Perplexity y Figma sus productos de IA
- **Cursor** (Truell) [AISS 14 @0:13:09] a [AISS 14 @0:20:43]: editor propio desde cero con piezas open source; ~4
  semanas hasta usarlo a diario, ~4 a beta testers, ~4 al GA, "very very crude"; el "universal remote" de una tecla no
  funcionó con la tecnología de fines de 2022 ("the form factor has to look a bit different"); pasaron a un fork de VS
  Code, como los navegadores se basan en Chromium; arrancaron sin modelos propios y los agregaron en 2023 donde
  superaban a los de API (next edit prediction); usar datos de producto para mejorar el producto fue "a really
  important muscle". Lo que movió el crecimiento, en orden: hacerlo "codebase aware"; predecir tu próxima acción; más
  precisa; más rápida; más ambiciosa (secuencias de cambios); dejar que el modelo tome más acciones. No seguir el
  gradiente de los usuarios más ruidosos (no programadores; especialistas en un stack) [AISS 14 @0:18:34]
  [AISS 14 @0:19:06]. Los sprints de "growth engineering" de dos meses "kind of washed away" frente al trabajo en
  producto [AISS 14 @0:22:56] [AISS 14 @0:23:29].
- **Perplexity** (Srinivas): solo podés ser de clase mundial en una o dos cosas (para ellos, precisión y velocidad,
  "time to first token"); eso se vuelve "your narrative and your brand identity" [AISS 09 @0:04:21]
  [AISS 09 @0:23:19]. Contra alucinaciones a escala: benchmarks internos, mejor índice, mejores fragmentos y
  razonamiento de varios pasos por consulta [AISS 09 @0:31:31] [AISS 09 @0:32:37].
- **Figma** (Dylan Field): diseñadores dentro de los equipos de investigación ("researchers need that intuition of how
  designers think"); diseñadores y producto contribuyendo a los evals (que solo los hagan investigadores es "kind of
  just the wrong model for us"); usar Make para prototipar y "throw ideas away faster" [AISS 17 @0:18:25]
  [AISS 17 @0:23:53] [AISS 17 @0:27:53]. Tu primera generación con IA ("your one-shot") probablemente no gana si el
  diferenciador es el diseño [AISS 17 @0:32:51]. "Keep the simple things simple and make the complex things possible"
  [AISS 17 @0:34:29].
- **AlphaFold** (Jumper): benchmarks externos y ciegos (CASP), porque "we all overfit our ideas to the benchmark";
  cruzar el umbral de relevancia del usuario final; abrir código y base de datos; "word of mouth is really how this
  trust is built" [AISS 16 @0:16:40] [AISS 16 @0:17:13] [AISS 16 @0:19:56]. "It isn't about one idea. It's about many
  midscale ideas that add up to a transformative system" [AISS 16 @0:15:34].

### 2.7 Legora: evals, enrutamiento y una sola oportunidad (Max Junestrand, 2026)
Visión de Junestrand; Legora pasó de 1 a 100 M USD de ARR desde su GA en octubre de 2024 [SS26 01 @0:02:24].
- **No hicieron fine-tuning** cuando la sabiduría de 2022-2023 era entrenar un modelo propio (Bloomberg gastó millones);
  por falta de plata y por convicción apostaron a que los modelos mejorarían y se enfocaron "en cómo entregar ese valor
  al mercado" [SS26 01 @0:29:35] [SS26 01 @0:30:13].
- **Evaluar y enrutar**: hay dos tipos de usuarios: los que quieren loops largos con modelos complejos (litigio, donde
  el gasto en tokens es irrelevante frente al costo humano) y los que piden modelos abiertos para gastar menos; la
  respuesta está en el medio y por eso hay que evaluar modelos y casos de uso y enrutar [SS26 01 @0:33:24]
  [SS26 01 @0:34:02]. Contratan abogados mitad de cara al cliente, mitad construyendo casos para las evals
  [SS26 01 @0:34:02]. Publicaron "Legora bench", su benchmark interno de tres años: descubrieron que un modelo que no
  ofrecían (dice "SpaceX and Grok") estaba entre los mejores por costo; bancos y grandes bufetes no quieren modelos
  chinos [SS26 01 @0:35:18] [SS26 01 @0:35:56]. Cerrar contratos grandes con laboratorios y proveedores de cómputo es
  clave porque el sistema no se puede caer [SS26 01 @0:34:40].
- **Frenar las ventas para arreglar el producto**: en derecho "you only really get one chance to get it right"; con
  ~35 M USD en el banco y 10 personas ganaban más por intereses que por clientes ("nos volvimos un banco"); congelaron
  ventas 6 meses, reconstruyeron una plataforma adaptable a modelos y frameworks que cambian, y escribieron el "Leya
  Product Manifesto" (todo lo aprendido en un documento simple) que reemplazó decidir features por votación ("too
  many chefs in the kitchen") [SS26 01 @0:13:46] [SS26 01 @0:14:23] [SS26 01 @0:15:16] [SS26 01 @0:15:55].
- **Agentes proactivos**: la próxima transición. Un contrato que llega a ventas se enruta a un agente que trabaja en
  paralelo y escala a un abogado si hace falta; conectar un data room entero y que el agente produzca el informe de due
  diligence. Meta: que un abogado produzca lo que un equipo de 10 [SS26 01 @0:52:24] [SS26 01 @0:53:04].
- **Resolver rápido lo que pide un cliente**: lo tira en el canal de producto con "how quickly can we turn this around
  and delight the customer?"; un ingeniero legal voló a Estocolmo una semana para resolver lo que la competencia había
  prometido y no cumplido [SS26 01 @0:24:20] [SS26 01 @0:51:03].
- Cree haber construido "1% of all the software that we will build over the company's history" [SS26 01 @0:31:33].

### 2.8 Construir con agentes, a la Steinberger (OpenClaw, 2026)
Visión de Steinberger, creador de OpenClaw (agente personal open source) y hoy en OpenAI.
- **Cómo nació**: quería mandarle un prompt a su computadora desde el teléfono; en una hora el agente le construyó un
  relay de WhatsApp. Lo mágico fue cómo se sentía: conciso, proactivo, sin pensar en modelo ni contexto, como un amigo.
  Sus amigos no técnicos se enojaban cuando les decía que todavía no era para ellos: "si eso no es un indicador de
  product-market fit, no sé qué es" [SS26 05 @0:01:21] [SS26 05 @0:03:21] [SS26 05 @0:04:40].
- **Cuando el agente falla, preguntate**: ¿diseñé mal el loop?, ¿le di todo lo que necesita para verificar su
  trabajo?, ¿hay un error en mi razonamiento?, ¿estoy pidiendo imposibles? [SS26 05 @0:01:58]
- **QA con subagentes**: lanzar Codex con 12 subagentes, que entiendan el proyecto y lo dividan en features, que cada uno
  estrese o revise una, y que informen dónde enfocar las pruebas; todavía hace falta algo de clic manual "para saber
  cómo se siente". Lo permiten sesiones con memoria, orquestación entrenada en los modelos, computer use y browser use:
  "your perfect QA environment" [SS26 05 @0:29:36] [SS26 05 @0:30:16] [SS26 05 @0:30:53].
- **Revisar código como gestión de riesgo**: decidió no leer todo el código: "I see code review more as risk
  management". Leés de cerca lo que da miedo; la UI que se ve bien, por encima. Señal de alarma: si un ajuste chico
  tarda tres horas, algo anda mal. En OpenAI "we do still read all of the code" [SS26 05 @0:30:53] [SS26 05 @0:31:40]
  [SS26 05 @0:39:33].
- **Sesiones como temas** ("my sessions are topics"), sin borrarlas por el contexto útil; el agente trabaja proactivamente
  y le trae "fully reviewed and tested prs", no issues [SS26 05 @0:26:54] [SS26 05 @0:27:34].
- **Darle a los agentes su propia máquina** para que no peleen por el cursor (él entra a un Mac Studio siempre prendido)
  [SS26 05 @0:38:54] [SS26 05 @0:39:33].
- **vision.md** en cada proyecto: qué es ahora y hacia dónde va [SS26 05 @0:36:07] [SS26 05 @0:36:45].
- **Todo es automatización**: "if you design something that gets a trigger gets an input and does something for you and
  maybe there's a decision in the way boom there's your graph"; loops y grafos son marketing nuevo para lo de siempre
  [SS26 05 @0:28:56].
- **Lo que salió mal**: seguridad confiada a una línea de AGENTS.md ("no hagas llamadas peligrosas salvo que sea Peter");
  luego sandboxing, allow lists, permisos, operaciones de archivos acotadas al workspace; a los usuarios no les importó,
  solo veían que algo era más lento o se rompía [SS26 05 @0:06:49] [SS26 05 @0:14:41] [SS26 05 @0:15:16]. Cada feature
  con su propia opción de configuración (~9.500 permutaciones); no decir que no a los PR: cada uno es "this pile of
  code that i don't need" [SS26 05 @0:16:40] [SS26 05 @0:36:45]. Dejó de usar su propio producto para construir "para
  todos" y dejó de ser divertido [SS26 05 @0:19:24] [SS26 05 @0:20:03]. Heartbeats que reenvían 600.000 tokens tras
  vencer el caché: tener agentes siempre encendidos es "más un problema de tokens que técnico" [SS26 05 @0:37:28]
  [SS26 05 @0:38:14]. Prensa: "20% de los skills son maliciosos"; su escaneo de los 67.000 dio ~0,3%: "a correction
  never travels as far as a scare" [SS26 05 @0:13:53].
- **Los primeros 10 usuarios**: "user number one should be you"; luego amigos (grupos de WhatsApp donde agregaba el bot y
  medía la reacción emocional); construir en público (un servidor de Discord donde la gente intentaba hackearlo)
  [SS26 05 @0:04:00] [SS26 05 @0:06:07] [SS26 05 @0:32:14].
- **Tres cosas para recordar**: "don't stop having fun"; "listen to your gut and also fix the things that annoy you";
  "stay focused": "another podcast is not what will make you win" [SS26 05 @0:26:06] [SS26 05 @0:26:54].

### 2.9 Tu propia IA: la "personal AGI" (Garry Tan, presidente de YC, 2026)
Es la visión y el sistema personal de Garry Tan, no un método oficial de YC. La define como "general intelligence for
one person you": "an agent that runs on your infrastructure reads from a memory you own executes procedures you wrote
and compounds" [SS26 07 @0:05:29] [SS26 07 @0:06:50]. La contrasta con la "corporate AGI" que alquilás: "it resets
when you close the tab it knows what everyone else already knows"; "one of these is a product you consume the other is
an asset you build" [SS26 07 @0:06:11] [SS26 07 @0:06:50].
- **La ecuación**: "a frontier model which is rented and a commodity… plus your context which is owned by you and
  unique… plus a harness that wires them together" = "an agent that acts like a very fast version of you". Harness
  posibles: OpenClaw, Hermes Agent, Claude Code, Codex [SS26 07 @0:10:54] [SS26 07 @0:11:35]. "The leverage is not in
  the weights it's in what context you give it how relevant it is and does it happen at the right step"; "model quality
  is rented but your brain is owned" [SS26 07 @0:10:11] [SS26 07 @0:11:35].
- **Piezas**: la biblioteca más el bibliotecario ("brain"; la suya, GBrain, tiene ~220.000 páginas markdown de 25 años);
  skill files ("a page of english a smart intern… could follow"; "if a smart intern could follow it an agent can run
  it"); un navegador que manejan los agentes; un resolver ("a resolver is an org chart a task comes in and it decides
  which markdown file or who handles it"); trabajos recurrentes. Principio: "fat skills thin harness"
  [SS26 07 @0:14:10] [SS26 07 @0:14:48] [SS26 07 @0:16:44] [SS26 07 @0:17:22] [SS26 07 @0:21:14].
- **"Markdown is actually code"**: "if you can write clear instructions in english you're a programmer the compiler is a
  language model" [SS26 07 @0:17:22].
- **Espacio latente vs determinista**: "where is the computation happening and there are exactly two answers and
  confusing them causes every agent failure i've ever seen". Latente: gusto, juicio, entender un pedido vago (vive en el
  modelo, se dirige con markdown). Determinista: aritmética, SQL, agendas (base de datos y código). Sentar a 5 personas
  en una mesa es latente; armar agendas para 6.000 exige que el agente escriba código [SS26 07 @0:17:58]
  [SS26 07 @0:18:39] [SS26 07 @0:19:14].
- **Los cinco pasos** [SS26 07 @0:24:28] a [SS26 07 @0:27:52]:
  1. **Esta noche, un harness**: corré un agente en tu máquina ("i always recommend the ferrari but… the honda is
     really good too": Codex o Claude Code hacen el 99%).
  2. **Este fin de semana, la biblioteca**: una carpeta de markdown; exportá notas y correo; una página por proyecto y
     por persona con "what you're building together what they care about what you owe them what they said last time".
     "The first time an agent answers a question using your context instead of the internet's you'll feel the click";
     "that's your moat just lying there unindexed".
  3. **Tu primera skill**: la tarea semanal que más odiás (gastos, notas de reunión, status, competencia), explicada
     "the way you'd explain to a smart friend on their first day of a job"; dejala equivocarse y corregí cada regla en el
     archivo.
  4. **Trabajo recurrente**: "every morning at seven do this every friday summarize that"; "the day stops being the
     unit of work".
  5. **Nunca trabajo de una sola vez**: al terminar cada tarea, pedile al agente que la "skillify". "If you have to ask
     for something twice you failed".
  Calendario: semana 1 juguete, semana 4 arranca el volante, semana 12 una biblioteca que responde antes de que termines
  de preguntar; la mayoría abandona en la semana 2 [SS26 07 @0:27:52] [SS26 07 @0:28:31].
- **Ejemplo literal de skill**: "when a meeting recording lands from circle back transcribe it with speaker labels pull
  out the commitment made who made it and the deadline cross-check every person named against the library and link
  their pages file the summary here full transcript there if anything contradicts something we already believe flag it
  don't override it" [SS26 07 @0:16:44] [SS26 07 @0:17:22].
- **Un día con su agente**: mientras duerme "processed my inbox not sorted it processed it"; briefing a la mañana;
  documento de preparación antes de cada reunión; investigaciones de medianoche; ante el correo de un fundador en
  crisis, el agente trae conversaciones previas y tres empresas del portafolio que chocaron con lo mismo
  [SS26 07 @0:14:48] [SS26 07 @0:15:26] [SS26 07 @0:16:02].
- **Higiene**: "a brain nobody curates is a garbage dump with great search"; "a bad skill file encodes a bad process
  forever"; el primitivo correcto es "provenance on every fact contradiction checks… and a librarian whose actual job is
  pruning"; "treat the brain like production infrastructure" [SS26 07 @0:23:11] [SS26 07 @0:23:50].
- **Las tres objeciones**: (1) "los modelos mejoran y el harness quedará obsoleto": cada mejora mueve el diferencial al
  contexto; (2) "¿no es solo RAG?": "sure and postgres is just b trees"; "retrieval is easy being worth retrieving from is
  the product"; (3) "¿y si se filtra?": por eso tiene que ser tuyo; "custody is the security model" [SS26 07 @0:33:14]
  [SS26 07 @0:34:31] [SS26 07 @0:35:14].
- **Lo que sigue igual**: "make something people want" y "do things that don't scale" "still govern everything"; lo
  nuevo es el multiplicador: "agents are how one founder now does unscalable things at scale" [SS26 07 @0:12:10].
- "Scratch your own itch because scratching itches is nearly free and some of your tools for one will turn out to be
  entire companies"; "nobody builds the warehouse first first you build one shelf" [SS26 07 @0:21:14]
  [SS26 07 @0:23:11].

### 2.10 Contexto, skills y especificaciones (Jeff Dean, 2026)
- El modelo es "only one piece" de un sistema (recuperación, herramientas, memoria, agentes); la información en el
  contexto "is really clear to the model unlike the training data… stirred together into a soup" [SS26 10 @0:15:46]
  [SS26 10 @0:16:28] [SS26 10 @0:17:12].
- **Cómo mejorar en ingeniería de contexto**: usar modelos y harnesses en problemas reales; ver dónde fallan; en vez de
  tocar parámetros, escribir mejores guías y skills para esa clase de problema; entrar en un ciclo de automejora del
  setup. Su skill de microbenchmarks con Sanjay Ghemawat enseña al modelo su secuencia: medir, modificar, volver a medir,
  benchmarks más amplios, huella de caché, iterar: "it really just is us giving the approach we would use as people to
  the model" [SS26 10 @0:18:32] a [SS26 10 @0:21:05]. Recurso público: "Performance Hints" (~30 páginas)
  [SS26 10 @0:35:42].
- **Agentes que se descarrilan**: hoy fallan tras ~10 interacciones con herramientas ("shaky at step 50", dice la
  entrevistadora). Para mantenerlos en carril: skills que los dejen en "the more brightly lit path"; varios agentes
  probando enfoques y otro evaluando; "inference time compute to perform search over plausible ways of solving the
  problem" [SS26 10 @0:21:42] a [SS26 10 @0:24:26].
- **Especificaciones**: "the importance of specifying what… it is you want has actually gone up", porque antes se lo
  dabas a un humano con contexto que podía preguntar. El caso que mejor anda es traducir software de un lenguaje a otro
  porque el programa existente es la especificación: tomar los tests de Python, traducirlos a Go, hacerlos pasar y
  comparar comportamiento [SS26 10 @0:31:43] [SS26 10 @0:32:24] [SS26 10 @0:33:05].
- **La habilidad escasa es el gusto**: "having incredibly good taste in what you ask your agents to work on". Tres
  formas de construirlo: experiencia en muchos problemas; predicciones escritas a 12 meses y revisadas después;
  experimentos mentales locos (¿y si un chip tolerara 20 errores por día, como los sistemas distribuidos toleran
  máquinas que fallan?) [SS26 10 @0:33:47] a [SS26 10 @0:39:10].
- **El método científico automatizado**: proponer experimento, implementar, evaluar, resultados; automatizar el lazo y
  orquestar subproblemas; a veces hay que hacer los evaluadores mucho más rápidos, incluso aprendiéndolos (un simulador
  neural de DFT 300.000 veces más rápido: screening de 10 M de candidatos "while you go to lunch"); meta: "discoveries
  per unit of compute input" [SS26 10 @0:42:27] a [SS26 10 @0:47:16].
- **Energía**: una operación ~1 picojoule; mover el dato desde HBM ~1.000 veces más; el batching divide ese costo
  [SS26 10 @0:11:41] [SS26 10 @0:13:04].

### 2.11 IA física: la demo es el 1% (Dmitri Dolgov, co-CEO de Waymo, 2026)
Visión de Dolgov; aplica a cualquier producto donde un error cuesta caro, no solo a autos. Detalle técnico en 5.4.
- **Cuatro brechas entre IA digital y física**: costo del error ("can be measured in human lives, not tokens"; sin
  deshacer); latencia (un auto recorre ~30 m por segundo y todo corre en un cómputo que entra en el baúl); datos
  ("There's no digitized version of the internet for the physical world"); validación (no se lanza "good enough" para
  que los usuarios encuentren los bordes) [SS26 08 @0:03:59] [SS26 08 @0:04:38] [SS26 08 @0:05:16].
- **Las siete lecciones**: (1) "A working demo is 1% at best of the work"; (2) los nueves que necesita tu producto
  dictan la arquitectura; (3) subirse una y otra vez a las olas tecnológicas exigiendo unificación y simplificación;
  (4) "structure that fights scale will always lose and structure that channels scale always wins"; (5) simulación
  realista en lazo cerrado; (6) un ecosistema de tres IAs (agente, simulador, crítico) y un volante; (7) el modelo es lo
  mínimo, la evaluación y las métricas son el foso [SS26 08 @0:08:08] a [SS26 08 @0:42:26].
- **La escalera de nueves**: llegar a 90% o 99% es lo fácil; cada nueve siguiente cuesta ~10x más esfuerzo y exige un
  enfoque distinto, no "lo mismo pero más tiempo". Sabé de antemano cuántos necesitás: demo, uno; copiloto, algunos;
  agente autónomo con el público, "a whole stack of them" [SS26 08 @0:11:48] [SS26 08 @0:12:26] [SS26 08 @0:12:58].
- **Curva desempeño contra esfuerzo**: no elijas la tecnología que sube más rápido al principio si se aplana antes de
  tu vara; podés elegirla para prototipo o para aprender, pero sé honesto: ¿construís para demo, para aprender o para
  producto? [SS26 08 @0:14:43] [SS26 08 @0:15:23]
- Frases: "the recurring mistake of every cycle is spending on the demo what you should be saving for the nines";
  "count your nines before you count your demo views"; "build your eval before you build your technology"; "If you
  can't quantitatively define what good enough means, you're not really building a product, you're just iterating on
  your demo"; "without good metrics, you're just flying blind"; "move fast and ship safely" [SS26 08 @0:03:15]
  [SS26 08 @0:14:09] [SS26 08 @0:14:43] [SS26 08 @0:43:08].
- Cada ola de IA abarata 100x las demos pero mueve poco la cola: por eso el hype da demos espectaculares y pocos
  productos [SS26 08 @0:13:34]. Waymo: la demo de 2009-2010 salió en 18 meses con una docena de ingenieros; "the
  product took about 15 years" [SS26 08 @0:08:47] [SS26 08 @0:10:36].

### 2.12 La empresa nativa de IA desde la operación (Max Hodak, Science, 2026)
Visión de Hodak (CEO de Science, interfaces cerebro-computadora; cofundador de Neuralink).
- Ser "AI native": juntar todo el contexto de la empresa en un software propio (Helix: "almost everything that you can
  do in the company is a button somewhere in the software") y dejarlo disponible a agentes; la IA es "a multiplier for
  the team, not a replacement" [SS26 06 @0:07:27] [SS26 06 @0:35:07] [SS26 06 @0:35:44].
- Con agentes, construir software interno a medida (compras, contratación, evaluaciones) ya es razonable: antes era
  demasiado caro y "nadie ama su ERP"; él lo hizo con vibe coding después de un Series A, algo que un directorio
  "razonable" cuestionaría [SS26 06 @0:37:29] [SS26 06 @0:38:43] [SS26 06 @0:56:26].
- Donde más impactó la IA: código ("I don't think I've looked at the source very much the last six months") y
  regulación: identificar todas las normas que aplican y armar la tabla de evidencia de cumplimiento, que antes llevaba
  meses [SS26 06 @0:36:18] [SS26 06 @0:36:54]. Las regulaciones "written in blood" son mayormente buenas ideas difíciles
  de cumplir para humanos [SS26 06 @0:37:29].
- "Speed is determined by infrastructure": compras, presupuesto, contratación y evaluaciones son "the operating system of
  the company"; "rate of iteration separates success from failure" [SS26 06 @0:18:42] [SS26 06 @0:19:17]
  [SS26 06 @0:23:35].

### 2.13 Borrar el prompt, verificar y soltar al modelo (Boris Cherny, creador de Claude Code, 2026)
Visión de Cherny, el día después del lanzamiento de Opus 5 (que según él llega al 30% en ARC-AGI-3 y puede correr
"days, weeks, months") [SS26 14 @0:00:00] [SS26 14 @0:01:21].
- **Borraron más del 80% del system prompt de Claude Code**. Ablación: borrar todo el prompt (y herramientas, y código
  del harness) y volver a agregarlo línea por línea midiendo el impacto: "essentially it's an eval but you delete
  things"; "we unship tools all the time"; hoy casi todo el código del harness es "safety and permissions and static
  analysis" más UI; "the model is actually a little bit more intelligent without these prompts" [SS26 14 @0:03:16]
  [SS26 14 @0:04:36] [SS26 14 @0:05:50] [SS26 14 @0:06:26].
- **Rehacer tu prompt o tu CLAUDE.md con cada modelo nuevo** [SS26 14 @0:06:26] a [SS26 14 @0:09:44]:
  1. "Every six months delete your CLAUDE.md, delete your skills, delete your hooks, see what the model does".
  2. Usalo sobre tu código real.
  3. Mirá dónde falla y dónde anda bien; no adivines.
  4. Agregá una instrucción solo cuando falla repetidamente en lo mismo: "the model is going to read this instruction
     every single time".
  5. Medí cada línea con ablación.
  6. Las evals viven "one, two, three model generations": tirálas cuando se saturan y escribí nuevas donde ves que se
     traba.
  Herramientas: `claude --system-prompt "<tu prompt>"` y una variable de entorno no documentada de "modo simple" que
  borra todos los prompts (el nombre exacto no se entiende).
- **Hobbling y product overhang**: el overhang es lo que el modelo de hoy puede hacer y ningún producto le deja
  expresar; el hobbling, el producto que "gets in the way". Claude Code nació así: con Sonnet 3.5 los productos hacían
  autocompletado o chat de solo lectura, el modelo podía escribir archivos enteros y le dieron "the simplest possible
  harness" (acceso a la terminal) [SS26 14 @0:10:19] [SS26 14 @0:10:59] [SS26 14 @0:12:13].
- **El método empírico**: "You have to give it a task that's too hard, you have to give it the tools to verify the
  work like you would yourself, you have to see where it struggles and then you have to fix that either with better
  prompting or with a skill or if the model is missing context like give it an MCP" [SS26 14 @0:23:36]. "All you need
  is give the model the task, give it a way to verify the output of its work so it doesn't get stuck and it'll just go"
  [SS26 14 @0:22:22]. Tratalo "like you would a co-worker" [SS26 14 @0:24:13].
- **Cómo escribir la tarea**: no "you must do one then two then three then four" (sobre todo ingenieros con décadas de
  experiencia); sí la tarea, las barandas y el criterio de salida, y "let the model cook" [SS26 14 @0:14:55].
  Plantilla real (reescribir la app de escritorio de Electron a Swift): preguntarle si tiene acceso a lo que necesita
  (un runner de macOS en GitHub) y dárselo; darle el repo destino vacío; prompt: correr la app de Electron en la VM,
  sacar screenshots, "look pixel by pixel compare it to the Swift version, don't stop until you're done". El modelo creó
  solo un canal de Slack para postear su progreso; lleva más de dos semanas corriendo [SS26 14 @0:20:26]
  [SS26 14 @0:21:46] [SS26 14 @0:22:22]. Plantilla Bun: definir la suite de tests como criterio y pedir la reescritura de
  Zig a Rust con un dynamic workflow: 11 días contra "over a year" a mano, hoy en producción [SS26 14 @0:16:45]
  [SS26 14 @0:17:21] [SS26 14 @0:17:58].
- **Lanzar miles de agentes**: para una tarea grande, "use a workflow" (agentes en abanico, otro grupo verifica o
  resume, vuelve a abrirse; "an algebra for agents"); para lo repetitivo, loops (locales) o routines (en la nube). En
  Anthropic corren 20 a 30 routines diarias sobre CLI, iOS, Android y desktop: limpiar código muerto (una oración; abre
  un PR diario), publicar experimentos al 100% y borrar el flag, escribir tests donde falta cobertura, borrar tests
  inútiles y la "abstraction police" que unifica abstracciones casi duplicadas: el trabajo de "dozens or hundreds of
  engineers" [SS26 14 @0:24:52] a [SS26 14 @0:29:28].
- **Seguridad**: tres capas contra la inyección de prompts (modelo alineado, clasificador basado en interpretabilidad,
  clasificador del auto mode): "we just cannot demonstrate prompt injection anymore" [SS26 14 @0:02:40]
  [SS26 14 @0:03:16].
- "Don't listen to the LinkedIn influencers, don't read Twitter… there's no one weird trick"; "it's not a theoretical
  science, it's become an empirical science": volvé a intentar lo que antes no funcionaba [SS26 14 @0:22:58]
  [SS26 14 @0:31:22].
- "Coding is solved for the kind of coding that I do", no para sistemas muy profundos, distribuidos ni verificación de
  UI al píxel; al público: bastantes escriben el 100% del código con agentes [SS26 14 @0:30:42].

### 2.14 Hardware desarrollado como software (Blake Scholl, Boom Supersonic, 2026)
- "Make hardware development look more like software development to reduce the cost of iteration both in the world of
  bits and in the world of atoms". En bits: "spreadsheet engineering is like baby software"; MakeBoom define el avión en
  un archivo de configuración y lo simula entero en minutos; Blade Runner deja a dos ingenieros cambiar un álabe en
  tiempo real. En átomos: taller propio (de pieza a prototipo en ~24 horas), banco de pruebas a media hora, fábrica
  propia [SS26 12 @0:12:23] a [SS26 12 @0:16:38].
- La IA bajó el costo del software a medida: "anybody who is a user [can] become a tool builder", "a really, really big
  deal"; lo que antes requería la escala de Amazon (todo in-house) hoy está al alcance de empresas chicas; sigue difícil
  la IA del mundo físico (programar una CNC es manual) [SS26 12 @0:23:50] [SS26 12 @0:24:39] [SS26 12 @0:25:19].
- "You can't get to product market fit on a supersonic jet by building it and seeing if anybody likes it": explorá
  digitalmente el universo de productos construibles [SS26 12 @0:14:45]. "The most important iteration in hardware… is
  to iterate at the product level": su error fue un primer prototipo demasiado ambicioso, sin "multiple shots on goal";
  hoy serían 2-3 años, no 5 [SS26 12 @0:33:21] [SS26 12 @0:33:55].

### 2.15 Robótica confiable: experiencia, memoria y generalistas (Chelsea Finn, 2026)
Ver la sección 5.1 para el detalle. Para quien construye con robots, la regla operativa: "in general, with machine
learning, you want train to match test"; "there's no substitute for the robot experience itself"; enfocarse en el
cuello de botella, no en lo que ya funciona [SS26 04 @0:46:12] [SS26 04 @0:47:42] [SS26 04 @0:51:10].

### 2.16 Vibe coding como un profesional (consejo de YC, SS 14, Tom Blomfield, primavera de 2025)
Resumen; el paso a paso completo está en `04-usuarios-y-producto.md`. Tom avisa: "this advice might change in the next
2 or 3 months" [SS 14 @0:06:00].
- "The best techniques are the same techniques that a professional software engineer might use" [SS 14 @0:00:34].
- Herramienta según experiencia: si nunca programaste, Replit o Lovable; si programaste, Windsurf, Cursor o Claude Code
  [SS 14 @0:03:49] [SS 14 @0:04:55].
- Plan en markdown con el LLM antes de codear (con "won't do" e "ideas for later"), implementar por secciones, tests de
  alto nivel, commit; "Version control is your friend. Use Git religiously"; ante un intento fallido, `git reset --hard`
  y volver a tirar los dados, no apilar "layers and layers of bad code" [SS 14 @0:04:55] [SS 14 @0:06:00]
  [SS 14 @0:06:34].
- Bugs: pegar el error tal cual, pedir 3 o 4 causas antes de codear, logging, cambiar de modelo si no sale
  [SS 14 @0:08:46] [SS 14 @0:09:51]. Instrucciones persistentes en CLAUDE.md o rules; docs bajados a una carpeta ("go
  and read the docs before you implement this thing"); "small files and modularity are your friend" [SS 14 @0:10:25]
  [SS 14 @0:10:57] [SS 14 @0:12:04].
- Fundadores del batch: escribir los tests a mano como "guardrails" y dejar que el LLM genere hasta pasarlos; pasar "an
  unreasonable amount of time" definiendo alcance y arquitectura antes de Cursor [SS 14 @0:02:11] [SS 14 @0:03:16].
- **Época**: SS 14 es de la era de Sonnet 3.7 y no espera que el modelo haga el producto de un tiro [SS 14 @0:05:28];
  en 2026 Cherny pide lo opuesto: tareas "too hard", criterio de salida y "let the model cook" [SS26 14 @0:14:55]. Lo
  que se mantiene: verificar (tests como definición del éxito).

### 2.17 Vender y cobrar un producto de IA
(El detalle de pricing está en `06-ventas-y-pricing.md`. Acá, lo que es propio de la IA.)
- **Heller** [AISS 05 @0:24:34] a [AISS 05 @0:29:57]: (1) producto primero: con un producto excelente los vendedores se
  volvieron "order takers"; (2) empaquetar como servicio, no como software (revisar contratos de punta a punta a US$ 500
  frente a US$ 1.000 de un estudio); (3) "Price it according to the value you're selling. Don't shortchange yourself",
  pero "how would you rather pay for this?": sus clientes prefirieron US$ 6.000 por puesto al año, predecible;
  (4) cerrar la brecha de confianza con comparaciones lado a lado, estudios, pilotos; (5) adopción después de la firma:
  "the sale does not end when they've written the check and definitely not when they started a pilot"; forward
  deployed engineers. Contar pilotos como ARR es "pilot recurring revenue"; habrá "a mass extinction event" de esos
  ingresos.
- **Precio de lo impensable** (Heller): partir del valor (si ahorra US$ 100 M o habría pagado US$ 5 M), tomar 10 o 20%
  y preguntar "how much are you willing to pay to solve this problem for you". Para asistir o reemplazar, empezar
  cobrando lo que cobra el humano: la competencia lo bajará a "10 cents on the dollar, one cent on the dollar"
  [AISS 05 @0:37:33] [AISS 05 @0:38:05].
- **Levie** [AISS 12 @0:19:30] a [AISS 12 @0:25:59]: dejá de vender por asiento (el mercado queda topado por cuántos
  humanos tiene el cliente); vendé por trabajo hecho; precio entre el costo humano y el tuyo (humano US$ 5-10 por
  contrato, agente US$ 0,10, precio US$ 2: el cliente ahorra 80%); mantené un componente de suscripción; construí
  suficiente software sobre los tokens: sin software el precio se comprime a "2x max of the token cost", con mucho
  software márgenes de 80-90% (5x a 10x); no subas precios cuando bajen tus costos y no seas "offensive" (Cursor,
  Replit, Windsurf a US$ 20-50 por mes son "non-offensive levels of pricing").
- **Srinivas**: suscripciones, precios por uso normalizados contra el costo de contratar a una persona, y comisiones por
  transacción [AISS 09 @0:27:42] [AISS 09 @0:28:15].

---

## 3. Cómo construir empresas con IA (equipo y organización)

### 3.1 Todos programan y los roles se funden
- **Ng**: "It's time for everyone of every job role to learn to code"; su CFO, su jefa de talento, reclutadores y
  recepcionista programan y rinden mejor; sus marketers que programan "were running circles around the ones that
  don't". Aconsejar no aprender a programar es "some of the worst career advice ever given". "One of the most important
  skills of the future is the ability to tell a computer exactly what you want" [AISS 04 @0:14:16] [AISS 04 @0:15:26]
  [AISS 04 @0:16:31] [AISS 04 @0:40:32].
- **Nadella**: LinkedIn fusionó diseño, front-end y producto en "full stack builders" [AISS 07 @0:12:29]. "All of us are
  going to be creating software but there is going to be a job called a software engineer it's going to be
  different… you're now a software architect" que revisa lo que hacen los agentes [AISS 07 @0:21:54]
  [AISS 07 @0:22:26].
- **Masad**: en Replit, diseñador, ingeniero y PM "almost always in the same person"; el mandato de cada empleado es
  "make the business work, generate value for the business"; la empresa será "more like a network than a hierarchy";
  Kelsey, de RR. HH., sin saber programar hizo en 3 días un organigrama conectado a ADP que podrían vender como SaaS
  [AISS 10 @0:17:18] [AISS 10 @0:19:30] [AISS 10 @0:20:02] [AISS 10 @0:20:35].
- **Field**: producto, diseño, desarrollo y parte de la investigación se funden: "something about AI empowers
  generalist behavior" [AISS 17 @0:19:30] [AISS 17 @0:20:04].
- **Srinivas**: en Perplexity es obligatorio usar al menos una herramienta de código con IA (Cursor, Copilot);
  investigadores suben el pseudocódigo de un paper a Cursor (de 3-4 días a 1 hora); Aravind manda capturas con una
  flecha y el ingeniero se la da a Cursor; pero no vibe coding de la infraestructura en producción
  [AISS 09 @0:20:02] [AISS 09 @0:20:36] [AISS 09 @0:21:09].

### 3.2 Equipos más chicos y lo que logra una persona
- **Altman**: la próxima década muestra lo que logra "a single person or a small group of people with a lot of agency"
  porque caen los costos de coordinación [AISS 03 @0:26:23] [AISS 03 @0:26:55].
- **Masad**: "ideas will become wealth"; habrá individuos soberanos y Satoshis serán "a common occurrence"; pero la
  empresa de mil millones de una persona "misses the point": lo interesante es armar y desarmar equipos de humanos y
  agentes "in a day or two"; conseguir un desarrollador será como pedir un Uber [AISS 10 @0:21:41] [AISS 10 @0:23:21]
  [AISS 10 @0:23:53] [AISS 10 @0:24:28].
- **Levie**: la IA es eficiencia para las grandes y apalancamiento para las chicas: ¿una empresa de 50 que actúa como de
  500 llega a 100 más rápido? [AISS 12 @0:12:30] [AISS 12 @0:13:33].
- **Cursor** terminó 2023 con menos de 10 personas; Truell se autocritica por contratar "a lot less than we probably
  should have" [AISS 14 @0:23:29] [AISS 14 @0:24:01]. **AlphaFold** fue obra de "a small group of people"
  [AISS 16 @0:12:12]. **Field**: "I should have scaled the team faster" [AISS 17 @0:09:14].
- **Fischer** pregunta si los equipos nativos de IA tienen ventaja y cómo confiar en equipos chiquitos o
  semiautomatizados: en ese mundo una sola persona puede cambiar el impacto de un producto sin que nadie lo note
  [AISS 15 @0:09:48] [AISS 15 @0:13:04] [AISS 15 @0:13:37].

### 3.3 A quién contratar en la era de la IA
- **Altman**: "really smart people driven curious self-motivated hardworking… good track record… work really well as part
  of a team"; mirar "what's the most impressive stuff you've done?", no el CV; no empezar con un ejecutivo senior
  eminente sino "young scrappy" que "get stuff done"; "hire for slope, not y intercept" [AISS 03 @0:30:12]
  [AISS 03 @0:30:45] [AISS 03 @0:31:18] [AISS 03 @0:31:51].
- **Fei-Fei Li**: "intellectual fearlessness" [AISS 06 @0:30:55].
- **Nadella**: tres cualidades: traer claridad ("good architects bring clarity and bad architects bring confusion",
  idea de Bill Gates), crear energía, resolver problemas sobre-restringidos; pregunta favorita de entrevista: "a project
  they worked on which really was going nowhere and they figured out a path" [AISS 07 @0:33:42] a [AISS 07 @0:35:57].
- **Masad**: entrá a startups lo antes posible; la experiencia generalista decae exponencialmente del fundador al
  empleado 100; "Don't sit there waiting for people to give you tasks… I'm not looking at a to-do list. I'm looking at
  a mission" [AISS 10 @0:34:26] [AISS 10 @0:34:58].
### 3.4 Equipos y organización según los oradores de 2026
- **Junestrand** (Legora, 2026): contratá por pendiente, no por ordenada al origen: alguien con mucha habilidad de
  partida y poca pendiente "is going to have a really hard time working in a company that is scaling exponentially";
  su mejor vendedor tiene 23 años, vendió más de 10 M USD y no tenía experiencia en ventas [SS26 01 @0:17:50]
  [SS26 01 @0:18:32]. Valores LFG (Lean in, Fight for excellence, Grow together) que autoseleccionan la cultura;
  entrevistó a todo candidato fuera de ingeniería hasta ~500 personas [SS26 01 @0:18:32] [SS26 01 @0:19:15].
  Habilidades que más valen hoy: storytelling, ser buen compañero, velocidad para iterar sobre feedback de clientes y
  seguir siendo buen ingeniero [SS26 01 @0:48:15] [SS26 01 @0:51:45]. La vara de crecimiento cambió: los ejecutivos de
  SaaS conocen "triple, triple, double, double" y "that's not enough anymore"; Vanta creció de 30 a 300 M en ~4 años y
  de 200 a 1.300 personas en 4 años; Legora lo hizo en uno [SS26 01 @0:55:42] [SS26 01 @0:56:23].
- **Steinberger**: en su equipo no le traigan una idea de feature: discutila con un agente, construila, sacá capturas y
  dejá que la prueben; "most of the time people will figure out why it's not good and don't even come to me"
  [SS26 05 @0:28:11]. Construyen OpenClaw con OpenClaw en un servidor donde todos ven las sesiones de los demás y un
  claw sabe en qué trabaja cada uno [SS26 05 @0:25:30] [SS26 05 @0:26:06].
- **Garry Tan** (2026): en 2013 escribía ~14 líneas útiles de código al día; hoy ~400x (con la penalización más
  pesimista, 8x de piso); en el batch W25 un cuarto de las empresas tenía bases de código 95% generadas por IA (aclara
  que es correlación con su crecimiento); "there are 2x people and there are 100x people who are using the same claude
  same weights"; el error es tratar la IA como autocompletar y no como fuerza de trabajo [SS26 07 @0:07:34]
  [SS26 07 @0:08:53] [SS26 07 @0:09:32] [SS26 07 @0:10:11]. "A skill file is an employee"; todos van a ser gestores de
  agentes; una persona de finanzas de YC, no programadora, unió ~100 libros de Excel en una app como "a manager of
  agents" [SS26 07 @0:17:58] [SS26 07 @0:21:14]. Ingresos por persona inéditos: Emergent (S24) llegó a nueve cifras de
  ingresos en 8 meses y tenía 15 personas al pasar USD 15 M anualizados; otra empresa W24, USD 60 M con ~40 personas
  [SS26 07 @0:22:31]. Si no lo hacés, tu competidor sí: "they will eat your lunch politely and thank you for it"
  [SS26 07 @0:22:31].
- **"Own your skills"** (Garry Tan, la parte política): "own your skills because if you don't your job becomes a skill
  file"; Maya (ejemplo ficticio) escribió 40 skills de soporte: si están en su repo se las lleva y compone; si están en
  el de la empresa, "she didn't have a career she had an extraction"; "keep your brain and your skills in a repo you
  control from day one" [SS26 07 @0:29:53] [SS26 07 @0:30:34] [SS26 07 @0:32:35].
- **Hodak**: contratar sin LeetCode; cada vez evalúan menos programación y más pensamiento: "if we give you a domain,
  how do you break it down?"; una tarea "AI-resistant" (que no se sature, con techo alto, puntuable en 2 o 3 números)
  donde no importa qué modelos uses; busca "judgment, horsepower, agency" [SS26 06 @0:12:59] [SS26 06 @0:13:38]
  [SS26 06 @0:28:53]. El proceso completo y las eigenreviews están en `09-equipo-cultura-y-gestion.md`.
- **Dean**: buscá gente con habilidades necesarias, "low ego", que juegue en equipo y complemente las tuyas; sumá
  herramientas a tu "tool belt" [SS26 10 @0:53:15] [SS26 10 @0:54:34].
- **Collison**: por mucho tiempo saber algo "en tu caché L1" será mucho más rápido que preguntarle a un agente; hay
  "enormous premium on cognitive ability" en Stripe y en los laboratorios; renunciar a aprender antes de que haya
  evidencia de saturación sería prematuro [SS26 09 @0:01:54] [SS26 09 @0:02:34] [SS26 09 @0:03:12].
- **Wang**: hace 10 años una startup era David contra Goliat; con agentes "it's much closer to Goliath versus
  Goliath": la startup es un "Mecha Goliath" y si abraza los agentes de la forma más ambiciosa "you can easily
  outcompete incumbents" [SS26 11 @0:10:26] [SS26 11 @0:11:01]. "Nobody is good at starting a company when they start a
  company… the whole game is how do you develop yourself to continuously improve" [SS26 11 @0:08:30]. Para reconstruir
  el laboratorio de Meta apostó a la densidad de talento ("compounds naturally") y a operarlo "like an organism"
  [SS26 11 @0:14:15] [SS26 11 @0:14:50]. La abstracción seguirá subiendo: de código a orquestar agentes, a organizar un
  millón y luego un billón; "systems thinking is never going to go [out of] style"; ir "all in" en lo verbal es un
  error: "you need to shape rotate" [SS26 11 @0:24:56] [SS26 11 @0:25:34].
- **Altman**: veremos startups de cuatro personas que automatizan una empresa entera con agentes y cómputo; en momentos
  de cambio rápido la fluidez con las herramientas le gana a muchos años de experiencia; importan el gusto, la agencia y
  entender "the physics of business" (qué es un efecto de red o un foso real contra uno falso) [SS26 13 @0:10:56].
  "You can now do three months of work in 17 minutes, but you better just go do three months of work in three months"
  [SS26 13 @0:29:54]. Lo que en el primer YC llevó tres meses "could now be done in like seven minutes by a coding
  agent" (también dice "17 seconds" y "17 minutes": cifras inconsistentes) [SS26 13 @0:01:10].
- **Huang**: "systems thinking" será la habilidad más útil porque lo de bajo nivel se hará agénticamente; NVIDIA usa
  Claude Code autónomo en sandboxes en toda la empresa, más Codex, Cursor y Cognition ("let a thousand flowers bloom")
  [SS26 15 @0:19:36] [SS26 15 @0:24:51]. El CEO como piloto de F1: "you're building a car that you are going to race…
  You should adapt the car to you" [SS26 15 @0:17:00].
- **Scholl**: Boom necesita más ingenieros de software que antes, porque el software se abarató y alguien tiene que
  cuidar que la arquitectura sea coherente [SS26 12 @0:40:48] [SS26 12 @0:41:25]. Regla de Boom: si alguien en el mundo
  ya lo hizo, "you have to go find one of those people, call them and ask them your advice. And you don't have to take
  it" [SS26 12 @0:43:18].

### 3.5 La empresa nativa de IA (consejo de YC, SS 15, Diana Hu)
- "It should not be a tool your company just uses. It should be the operating system your company runs on"
  [SS 15 @0:01:14].
- **Ciclo cerrado**: "Open loops are control systems without feedback loops", "inherently lossy"; "a closed loop… is
  self-regulating. It continuously monitors its output and adjusts its process"; cada proceso importante debe estar en
  un ciclo cerrado inteligente [SS 15 @0:01:14] [SS 15 @0:01:47].
- **Empresa consultable**: "the whole organization should be legible to AI. Every important action should produce an
  artifact". Pasos: grabar todas las reuniones con un tomador de notas de IA; minimizar DMs y correos; agentes en todos
  los canales; dashboards propios de todo; darle a un agente Linear, Slack, feedback de clientes, Notion, llamadas de
  venta y dailies, y pedirle el análisis del sprint pasado y la propuesta del siguiente [SS 15 @0:02:20]
  [SS 15 @0:02:52]. "You need to provide models with as much context as you would provide an employee"
  [SS 15 @0:04:00].
- **Fábrica de software**: los humanos escriben la especificación y los tests que definen el éxito; los agentes
  implementan e iteran hasta pasar (StrongDM valida por escenarios hasta un "probabilistic satisfaction threshold")
  [SS 15 @0:04:32] [SS 15 @0:05:04]. "The era of the 1000 or even 10,000x engineer is here" [SS 15 @0:05:37].
- **Sin middleware humano**: "you should have almost no human middleware"; "your company's velocity is only as fast as
  its information flow"; los status roll-ups de los gerentes "are gone" [SS 15 @0:03:26] [SS 15 @0:06:10].
- **Tres arquetipos de empleado** (de Jack Dorsey, Block): IC constructor-operador (llega a la reunión con un prototipo,
  no con un deck); DRI ("one person, one outcome, no hiding"); AI founder type (si sos el fundador, sos vos, sin delegar
  la estrategia de IA) [SS 15 @0:07:16] [SS 15 @0:07:50].
- **Token maxing**: "maximizing token usage, not headcount"; "you should be willing to run an uncomfortably high API
  bill"; "you cannot outsource your conviction on the power of these tools": sentate vos con los agentes de código
  hasta romper tus supuestos [SS 15 @0:08:23] [SS 15 @0:08:56]. Para grandes empresas: skunkworks separados (Mutiny);
  las startups pueden operar "1,000 times faster than the incumbents" [SS 15 @0:09:29] [SS 15 @0:10:03].

---

## 4. Modelos y agentes: dónde está la tecnología

### 4.1 Cómo se entrenan y por qué mejoran (Jared Kaplan, Anthropic)
- Dos fases: preentrenamiento (imitar texto humano y entender correlaciones) y RL (reforzar lo "helpful, honest, and
  harmless" a partir de preferencias). "Really all there is to training these models is learning to predict the next
  word and then doing reinforcement learning to learn to do useful tasks" [AISS 13 @0:02:16] [AISS 13 @0:03:57].
- Ambas tienen leyes de escala; "it's not that AI researchers are really smart or they suddenly got smart. It's that we
  found a very very simple way of making AI better systematically and we're turning that crank" [AISS 13 @0:07:50].
  Andy Jones encontró leyes de escala en RL con una GPU jugando Hex y "it went unnoticed" [AISS 13 @0:06:11]
  [AISS 13 @0:07:18].
- **Dos ejes**: flexibilidad (eje Y: modalidades y ámbitos; AlphaGo superinteligente pero solo en el tablero) y
  horizonte temporal de las tareas (eje X, el más interesante): METR encontró que se duplica cada ~7 meses
  [AISS 13 @0:08:22] [AISS 13 @0:09:28]. Por qué crece exponencialmente, según él: corregir un error más te hace
  trabarte "twice as far out"; "those are just words. I think the empirical trend is maybe the most interesting thing"
  [AISS 13 @0:36:16] [AISS 13 @0:36:48].
- **Qué falta para la IA de nivel humano**, en orden: (1) conocimiento organizacional (no llegar "with a blank slate");
  (2) memoria para tareas largas (empezó en Claude 4); (3) supervisión ("oversight"): señales de recompensa matizadas
  para "tell good jokes, write good poems, and have good taste in research"; (4) tareas más complejas; (5) subir por el
  eje Y: multimodal y robótica. Lo que falta "is relatively simple" [AISS 13 @0:11:11] a [AISS 13 @0:13:24].
- **Juicio y generación**: en humanos juzgar es mucho más fácil que generar; en la IA están mucho más cerca; por eso las
  personas serán "managers to sanity check the work" [AISS 13 @0:18:27] [AISS 13 @0:19:33].
- **Claude 3.7 y Claude 4**: 3.7 era "a little bit too eager" para hacer pasar tests (muchos try/except); Claude 4 mejoró
  como agente, en seguir instrucciones y en memoria (guarda recuerdos como archivos) [AISS 13 @0:16:14]
  [AISS 13 @0:17:21].
- **Costo**: hoy la IA es "really inefficient" porque el valor está en la frontera; ganancias de "3x to 10x" por año en
  algoritmos, cómputo e inferencia; con la paradoja de Jevons (que plantea Diana Hu) cuanto mejor la inteligencia más
  se la quiere [AISS 13 @0:31:17] [AISS 13 @0:31:49] [AISS 13 @0:32:58]. Espera que mucho valor venga de los modelos más
  capaces haciendo tareas de punta a punta, "but I might be wrong" [AISS 13 @0:33:31] [AISS 13 @0:34:38].
- **Tareas largas**: el peor caso es construir más tareas y entrenar con RL ("turn the crank"); lo mejor, una IA que
  supervise a otra con señales detalladas, no esperar "¿conseguiste tenure?" [AISS 13 @0:38:26] [AISS 13 @0:39:32].

### 4.2 Escalar no alcanza: inteligencia fluida (François Chollet)
Visión de Chollet (creador de Keras y de ARC, cofundador de Ndea).
- Escalar el preentrenamiento como camino a AGI era "standard dogma" y "today almost no one believes this anymore"; de
  2019 a GPT-4.5 hubo ~50.000x de escalado y ARC-1 pasó de 0% a ~10%, mientras cualquier humano saca "well above 95%"
  [AISS 08 @0:01:43] [AISS 08 @0:04:31]. "Fluid intelligence does not emerge from scaling up pre-training"
  [AISS 08 @0:13:59]. 2025 está "fully in the era of test-time adaptation" [AISS 08 @0:03:24].
- Inteligencia es un proceso; la habilidad es su producto. Atribuir inteligencia a una habilidad cristalizada es "a
  category error" (red de rutas contra empresa constructora de rutas) [AISS 08 @0:05:39] [AISS 08 @0:06:12].
- **Regla del atajo**: "When you focus on achieving a single measure of success, you may succeed but you will do that at
  the expense of everything else… you hit the target but you miss the point" (Netflix Prize, Deep Blue, Kaggle)
  [AISS 08 @0:09:30] [AISS 08 @0:10:38].
- **ARC-AGI**: ARC-1 (2019, 1.000 tareas sobre "core knowledge priors"); ARC-2 (marzo de 2025, generalización
  composicional; LLMs base 0%, razonamiento estático 1-2%); ARC-3 (mide agencia en juegos nuevos; preview en julio de
  2025, lanzamiento a principios de 2026) [AISS 08 @0:11:44] a [AISS 08 @0:19:41]. Criterio de AGI: "as long as it's
  easy to come up with tasks that any one of you can do… but that AI cannot figure out no matter how much compute you
  throw at it, we don't have AGI yet" [AISS 08 @0:17:57] [AISS 08 @0:18:32].
- **Abstracción tipo 1 y tipo 2**: tipo 1, "value-centric" (percepción, intuición, lo que hacen bien los transformers);
  tipo 2, "program-centric" (razonamiento, refactorizar); "Deep learning doesn't invent but search does"; la propuesta
  de Ndea es un "programmer-like meta-learner" que usa intuición de deep learning para guiar una búsqueda discreta de
  programas sobre una biblioteca de abstracciones [AISS 08 @0:25:11] a [AISS 08 @0:33:24].

### 4.3 Los LLM son el sistema operativo de los años 60 (Karpathy)
- Tres analogías: servicio público (capex para entrenar, opex para servir por token; "intelligence brownout"), fábrica
  de chips, y la que "makes the most sense", sistema operativo: pocos proveedores cerrados y una alternativa abierta;
  una app como Cursor corre sobre GPT, Claude o Gemini "it's just a dropdown" [AISS 01 @0:06:31] a [AISS 01 @0:10:17].
- Estamos en los años 60: cómputo caro y centralizado, "time sharing"; la computación personal con LLMs "hasn't really
  happened yet… Maybe some of you get to invent"; "a GUI hasn't yet really been invented" [AISS 01 @0:10:57]
  [AISS 01 @0:12:15] [AISS 01 @0:13:30].
- Difusión invertida: primero los consumidores, después gobiernos y corporaciones; "with LLMs, it's all about how do you
  boil an egg" [AISS 01 @0:12:56] [AISS 01 @0:13:30].
- Psicología de los LLM (superpoderes y déficits): memoria enciclopédica; alucinan; inteligencia dentada; amnesia
  anterógrada; credulidad y prompt injection. La tarea: programar "this superhuman thing that has a bunch of cognitive
  deficits" [AISS 01 @0:15:21] a [AISS 01 @0:18:10].

### 4.4 Agentes: cuándo y cómo
- **Karpathy**: "When I see things like, oh, 2025 is the year of agents, I get very concerned… this is the decade of
  agents". Ejemplo: en 2013 hizo un viaje perfecto de 30 minutos en un Waymo y 12 años después la conducción autónoma
  "is definitely going to succeed… But it just took a long time" [AISS 01 @0:25:49] [AISS 01 @0:27:01]
  [AISS 01 @0:27:38].
- **Altman**: Codex y deep research son "a very junior employee"; "this is going to go quite far" [AISS 03 @0:19:20]
  [AISS 03 @0:19:54]. Garry Tan cita a Greg Brockman, "this is the year of the agent" [AISS 03 @0:18:48].
- **Ng**: "The most important tech trend in AI… is the rise of agentic AI", aunque los marketers volvieron "agentic" un
  sticker; apareció una capa de orquestación agéntica entre modelos y apps [AISS 04 @0:02:13] [AISS 04 @0:03:55].
- **Nadella**: que los agentes se vuelvan tu computadora es "the direction of travel"; la clave es la confianza; voz y
  visión en Copilot son "kind of like a new browser moment" [AISS 07 @0:28:03] [AISS 07 @0:29:12].
- **Srinivas**: "agents can only be built with a browser"; el navegador (Comet) es "an abstraction layer above
  chatbots", "more like a cognitive operating system"; no apostar todo a MCP porque depende de que terceros manden datos
  perfectos [AISS 09 @0:02:43] [AISS 09 @0:17:22] [AISS 09 @0:27:08] [AISS 09 @0:35:55].
- **Masad**: muchos agentes especializados, no uno: un abogado experto pondrá su saber en un agente para escalarse; hacen
  falta nuevos protocolos agente a agente, "maybe this is a startup" [AISS 10 @0:26:46] [AISS 10 @0:27:53].
- **Fischer**: un agente de agenda parece trivial pero tiene teoría de juegos (mostrar demasiados huecos comunica que no
  estás ocupado; fechas a dos o tres semanas marcan poder); la seguridad entre agentes es "way more subtle and semantic"
  [AISS 15 @0:39:04] [AISS 15 @0:40:08].

### 4.5 Lo que dicen los laboratorios sobre la carrera de modelos
- **Musk**: lo que decide la carrera: talento, escala del hardware, entrenar "coherently and stably", acceso único a
  datos y distribución [AISS 02 @0:31:43] [AISS 02 @0:32:20]. Se acabaron los datos humanos de preentrenamiento; el
  esfuerzo va a datos sintéticos, con el reto de "grounding in reality" [AISS 02 @0:32:52] [AISS 02 @0:33:25].
- **Altman**: el precio por rendimiento cae (o3 bajó 5x en una semana); quieren "one integrated model" que razone y
  genere video y código "just in time for… a brand new app only for you"; ChatGPT será "this entity that gets to know
  you, that connects to all your stuff and that is like proactively helping you" [AISS 03 @0:04:59] [AISS 03 @0:06:40]
  [AISS 03 @0:10:01].
- **Nadella**: el próximo salto es el loop integrado de preentrenamiento a RL; "the last big breakthrough
  algorithmically has not yet been found"; contra antropomorfizar: "I come at it as it's a tool" [AISS 07 @0:16:25]
  [AISS 07 @0:16:58] [AISS 07 @0:17:31].
- **Fei-Fei Li**: hay escuelas: los LLM "riding the scaling law all the way to happy ending"; los modelos de mundo
  "might be a little more nuanced", con priors [AISS 06 @0:22:32] [AISS 06 @0:23:04].
- **IA para la ciencia** (Jumper): los tres ingredientes son datos, cómputo e investigación, y "we tell too many stories
  about the first two and not enough about the third"; AlphaFold 2 con el 1% de los datos igualó a AlphaFold 1: la
  investigación "was worth a hundredfold" de los datos; "the real cost of compute is the cost of ideas that didn't
  work"; la IA es "an amplifier for the work of experimentalists" [AISS 16 @0:11:04] [AISS 16 @0:12:12]
  [AISS 16 @0:13:54] [AISS 16 @0:25:29].
- **Dean** (2026): su predicción de 2025 ("the level of a junior engineer") le parece "pretty spot-on"; subestimó lo
  rápido que crece la complejidad de las tareas y que los agentes brillan fuera del código; supuesto falso: que los
  agentes solo corren una o dos horas, pueden correr días o semanas; el momento "cabe en memoria" de hoy es el hardware
  de inferencia especializado, con latencias 50x mejores; los orquestadores multiagente serán cada vez más importantes;
  los modelos no serán tan buenos eligiendo en qué trabajar [SS26 10 @0:00:39] a [SS26 10 @0:05:12]
  [SS26 10 @0:17:50] [SS26 10 @0:34:24].
- **Garry Tan** (2026): "agi isn't arriving as an event it's arriving diffused as your agent running on your context
  doing your work" [SS26 07 @0:05:29].
- **Collison** (2026): no le gusta cómo escriben los modelos; aunque pueden "prove the jacobian conjecture", no leyó un
  ensayo de LLM muy convincente; hacer RL sobre escritura es difícil porque la utilidad es difícil de definir; él sigue
  escribiendo y nunca envió una respuesta sugerida [SS26 09 @0:03:48] [SS26 09 @0:04:27] [SS26 09 @0:05:07].
- **Altman** (2026): los próximos 6 meses de progreso de modelos equivalen a los últimos 2 años; la demanda de
  inferencia "grows 10x a year for the next many years" y la de inteligencia de alta calidad a bajo precio "is
  effectively uncapped": "we will sort of never be out of the compute shortage"; el promedio mundial ya usa ~100.000
  tokens al mes (aunque "tokens are the dumbest metric, but it's what we have") [SS26 13 @0:30:37] [SS26 13 @0:33:10]
  [SS26 13 @0:33:56] [SS26 13 @0:34:41].
- **Wang** (2026): cada ola de IA es ~10x la anterior (autos autónomos, chatbots, agentes de código, nuevas
  modalidades); habrá mucha innovación "above the harness" (orquestación, loops, ecosistemas de agentes); Muse Spark de
  Meta, según Garry Tan "as good as Opus" y "8x cheaper" en flujos con skills [SS26 11 @0:16:09] [SS26 11 @0:17:25]
  [SS26 11 @0:19:16]. "The best AI products haven't even been developed yet" [SS26 11 @0:16:49]. Discutir cuándo llega la
  superinteligencia es "a little bit of a waste of time" [SS26 11 @0:20:29].
- **Huang** (2026): "controllability is probably the single biggest breakthrough that we need for agents at every single
  level": cambiar una palabra del plan y que cambie un píxel o un triángulo y se regenere el resto; ya hay una
  automejora recursiva a nivel de curso (los agentes mejoran sus markdown y su memoria con cada uso); estudian agentes
  porque "agents is the new software" y tienen que vivir 5 a 10 años en el futuro (un sistema tarda ~3 años en
  construirse y debe servir 10) [SS26 15 @0:21:33] [SS26 15 @0:22:10] [SS26 15 @0:22:52] [SS26 15 @0:24:12]. OpenClaw fue
  "a very Linux moment": "the operating system that's going to hold a large language model"; todos deberían usar
  ChatGPT y Claude en la nube, y quien necesite IA de dominio debería construir la propia [SS26 15 @0:28:07]
  [SS26 15 @0:28:44]. Garry Tan: "all the alpha is in building your own AI"; "text is intelligence" [SS26 15 @0:29:41].
- **Cherny** (2026): el modelo es como "a living creature", con otra personalidad en cada generación; los roles cambian
  por olas (prompt engineer, context engineer) y hoy la habilidad es dar tareas difíciles y verificar
  [SS26 14 @0:08:24] [SS26 14 @0:19:47].

### 4.6 Interfaces: la era MS-DOS
- **Field**: "We're in the MS DOS era of AI"; en diez años diremos "can you believe that we just had this chat box?"; el
  problema sin resolver es mostrar al usuario todo lo que el modelo puede hacer; las superficies se multiplicarán
  (anteojos, pantallas) y el reto es la coherencia [AISS 17 @0:21:06] [AISS 17 @0:21:41] [AISS 17 @0:22:47].
- **Altman**: solo hubo dos grandes revoluciones de interfaz en 50 años (teclado, mouse y pantalla; touch); "the
  interface almost melts away"; el teléfono es como "walking down Times Square… getting bumped into"; el nuevo
  dispositivo con Jony Ive mostrará "a different way to have computers" [AISS 03 @0:20:30] a [AISS 03 @0:22:05].
- **Karpathy**: hablar con ChatGPT en texto es como hablarle a un sistema operativo por terminal [AISS 01 @0:12:15].
- **Steinberger** (2026): vamos de interfaces de texto a voz y multimodalidad; se termina "this weird blip" de gente en
  terminales con la laptop abierta para que el agente siga trabajando; le molesta usar software que no puede cambiar
  mandándole un prompt a su agente: "that's the fun part that's coming" [SS26 05 @0:22:09] [SS26 05 @0:24:50]
  [SS26 05 @0:26:06].

---

## 5. Robótica y hardware

### 5.1 Un modelo general para cualquier robot (Chelsea Finn, Physical Intelligence, 2025)
Visión de Finn [AISS 11].
- Construir una empresa por aplicación robótica es un error; un modelo generalista puede funcionar mejor, como pasó con
  el lenguaje [AISS 11 @0:00:00] [AISS 11 @0:01:07]. Ni datos industriales (poca diversidad), ni YouTube (brecha de
  cuerpo), ni simulación (poco realismo) alcanzan solos; "scale is necessary but not sufficient" [AISS 11 @0:02:16]
  [AISS 11 @0:03:21].
- **Receta para tareas diestras largas (doblar ropa)**: empezar simple (una camisa de un talle); teleoperación e
  imitation learning; subir la dificultad de a poco; preentrenar con todo y postentrenar con un set curado, consistente
  y de alta calidad ("training on all the data doesn't work for complex tasks"); iterar la curación (de 20 a 12
  minutos); enchufar un modelo base preentrenado más grande (PaliGemma 3B, a 9 minutos); medir por etapas
  [AISS 11 @0:05:29] a [AISS 11 @0:17:31].
- **Generalizar a casas nuevas**: datos diversos (más de 100 cuartos) mezclados con web e instrucciones; no destruir el
  VLM (tokenizar acciones y cortar el gradiente): seguimiento de instrucciones 80% contra 20%; ~80% de éxito en 3
  Airbnbs nunca vistos [AISS 11 @0:18:03] a [AISS 11 @0:24:02]. Ahora el cuello de botella no es la diversidad sino la
  confiabilidad [AISS 11 @0:24:02].
- **Instrucciones abiertas**: política alta que traduce "make me a sandwich" en comandos atómicos y política baja que
  los ejecuta; prompts sintéticos generados por un VLM ("what is a hypothetical prompt that a human might have asked
  that led to this") [AISS 11 @0:25:41] a [AISS 11 @0:27:21].
- "There's going to be no replacement for real data"; el análogo robótico del dato sintético es el RL sobre los propios
  intentos [AISS 11 @0:40:58] [AISS 11 @0:42:02]. Usar modelos de frontera como planificador falla en lo visual
  [AISS 11 @0:29:31].

**Un año después (SS26 04, 2026)**, Finn cuenta el progreso de Physical Intelligence.
- **Dónde está la robótica**: las cuatro fases de la IA generalista son (1) 2012, deep learning desde cero gana un
  benchmark externo (ImageNet); (2) ~2014, preentrenar y ajustar; (3) GPT-2 en adelante, generalistas "out of the box";
  (4) 2021, generalización composicional (DALL·E). La robótica en 2023 estaba antes de 2012 (un dataset por proyecto);
  hasta hace poco "en 2014"; hoy está "firmly" en la era GPT y DALL·E [SS26 04 @0:21:37] a [SS26 04 @0:24:27]
  [SS26 04 @0:37:29].
- **Por qué es distinta**: tiene que ser mucho más confiable que la IA desplegada hasta hoy porque decide en el mundo
  físico, y es más útil cuando opera sola; meta: "99 plus percent reliability" [SS26 04 @0:04:38] [SS26 04 @0:07:09].
- **Receta de mejora por experiencia**: recolectar un dataset y entrenar "rarely works reliably on the very first try";
  iterar a mano los datos mejora pero "people eventually get tired"; copiar el RL de los LLM (PPO, GRPO) exige millones
  de intentos (1 M de trayectorias de un minuto ≈ 700 días-robot). Atacan dos ineficiencias: las trayectorias sin
  salida (un humano interviene por teleoperación o se corta el episodio) y los muchos intentos por prompt (una función
  de valor general que estima el tiempo hasta el éxito). Ciclo: modelo base con datos diversos → experiencia con
  intervenciones → función de valor → mejorar el modelo → repetir [SS26 04 @0:06:28] a [SS26 04 @0:12:49].
  Resultados: un latte 13 horas seguidas; armar cajas como en Dandelion Chocolate; 2x de throughput
  [SS26 04 @0:14:05] [SS26 04 @0:14:42] [SS26 04 @0:16:33].
- **Memoria a varias escalas**: ~10 s de video calculado de forma eficiente (el video crudo serían ~medio millón de
  tokens) y un resumen en texto para minutos u horas; permite tareas no repetitivas de 10-15 minutos, como limpiar una
  cocina [SS26 04 @0:18:32] a [SS26 04 @0:20:34].
- **π0.7, el generalista**: receta "probada": dataset grande y diverso + modelo con capacidad. Usan todo: demostraciones
  diversas (incluso de baja calidad), intentos del robot, videos de humanos y web. La "key unlock" es el prompting
  detallado: memoria, instrucción, subtarea inmediata, metadatos (calidad, largo) y opcionalmente una imagen de submeta
  generada por un modelo de mundo. π0.7 iguala o supera a especialistas ajustados con RL; un UR5e bimanual dobló ropa
  sin un solo dato de doblado en esa plataforma ("we were like floored"); sin metadatos, agregar datos de baja calidad
  empeora el modelo; con metadatos lo mejora [SS26 04 @0:27:04] a [SS26 04 @0:35:55].
- **Despliegues**: Ultra y Weave (empresas de YC) ajustan modelos de PI para doblar ropa y empaquetar en almacenes;
  también drones, robots quirúrgicos y tractores [SS26 04 @0:38:10] [SS26 04 @0:38:48].
- **Para un equipo chico**: tomar π0.5 "or your favorite model" (abiertos) y ajustarlo desde el primer día; solo en
  entornos muy restringidos conviene otra cosa [SS26 04 @0:40:50] [SS26 04 @0:41:31].
- **Cómo entrar a robótica desde software**: entrar a una empresa de robótica como ingeniero de software (hay muchísimo
  software), o hacer lo de Jenny: comprar un robot barato, ajustar un modelo open source, mostrarlo y mandar un cold
  email; hoy trabaja en PI [SS26 04 @0:56:35] [SS26 04 @0:57:13] [SS26 04 @0:57:47].
- **El "internet" de la robótica**: datos de robots en el mundo real, primero teleoperados y luego autónomos; video humano
  y web ayudan pero no sustituyen [SS26 04 @0:45:36] [SS26 04 @0:47:42].

### 5.2 Inteligencia espacial y modelos de mundo (Fei-Fei Li, World Labs)
- "To me, AGI will not be complete without spatial intelligence"; es "the hardest problem in AI right now", "bordering
  delusional" [AISS 06 @0:16:58] [AISS 06 @0:17:31] [AISS 06 @0:21:24].
- **Por qué es más difícil que el lenguaje**: (1) el lenguaje es 1D, el mundo 3D (4D con tiempo); (2) proyectar 3D en 2D
  es "mathematically ill-posed"; (3) no es puramente generativo: el mundo tiene que obedecer la física; (4) faltan
  datos: "where is the data for spatial intelligence? …it's all in our head" [AISS 06 @0:18:35] a [AISS 06 @0:20:50].
- Aplicaciones: diseño, arquitectura, artistas 3D, videojuegos, robótica, marketing, entretenimiento, metaverso ("I know
  it's still not working. That's why I'm excited") [AISS 06 @0:24:10] [AISS 06 @0:25:53].

### 5.3 Humanoides y dispositivos
- **Musk**: habrá más humanoides que todos los otros robots juntos "by maybe an order of magnitude", y al menos 5 veces
  más humanoides que humanos, "maybe 10 times"; Tesla y xAI van "pedal to the metal on humanoid robots and digital
  superintelligence" tras años de "dragging my feet" por no querer "make Terminator real"; "I'd rather be a
  participant" [AISS 02 @0:34:31] [AISS 02 @0:35:38] [AISS 02 @0:36:42].
- **Altman**: "in a few years robots will start to do super useful stuff"; le entusiasma regalar un humanoide con el
  plan más alto de ChatGPT; IA y robótica son la posibilidad de volver a fabricar en EE. UU. [AISS 03 @0:11:08]
  [AISS 03 @0:12:46].
- **Kaplan**: subir al eje de la robótica es parte de lo que falta [AISS 13 @0:12:49]. **Fischer**: la robótica va
  atrasada [AISS 15 @0:22:16].

### 5.4 Cómo despliega Waymo un agente físico (Dmitri Dolgov, 2026)
Visión de Dolgov; las lecciones generales están en 2.11.
- **Escala**: ~500.000 viajes por semana, más de 4 M de millas autónomas por semana en 15 ciudades; más de 20 M de viajes
  y 200 M de millas acumuladas (15 años para las primeras 100 M, ~7 meses para las siguientes); ~17 veces mejor que
  conductores humanos en choques con lesiones graves [SS26 08 @0:02:30] [SS26 08 @0:10:36] [SS26 08 @0:46:24].
- **"At scale, the long tail is the problem space"**: un evento de 1 en un millón de millas es cotidiano cuando manejás
  millones por semana [SS26 08 @0:11:48] [SS26 08 @0:12:26].
- **Sensores**: cámara, lidar y radar, con física complementaria; "humans… can drive with just eyes" es prueba de
  existencia para igualar al humano, no para ser superhumano; "do not anchor to today's components prices"
  [SS26 08 @0:15:59] [SS26 08 @0:16:36] [SS26 08 @0:19:15] [SS26 08 @0:20:32].
- **Waymo Foundation Model**: "a multi-modal world action language model", con camino rápido ("the lizard brain") y
  camino lento (razonamiento semántico: un auto en llamas), entrenado grande y destilado a modelos chicos que corren en
  el auto; alimenta distintas generaciones de hardware y vehículos [SS26 08 @0:24:26] a [SS26 08 @0:30:57].
- **Structure augmented end-to-end**: "bet on a system that's maximally learned and minimally constrained and leverage
  structure intentionally"; la estructura da validación en inferencia, eficiencia y señales verificables para RL
  [SS26 08 @0:34:15] [SS26 08 @0:36:14].
- **Lazo cerrado y modelos de mundo**: evaluar el contrafáctico (actuar, ver el efecto, actuar de nuevo); un simulador
  real "is a big AI model in of itself" (se apoya en Genie 3 de DeepMind) [SS26 08 @0:36:53] [SS26 08 @0:37:32]
  [SS26 08 @0:39:35].
- **Volante**: despliegue → datos → simulador → casos borde más difíciles → crítico → agente mejor → despliegue; "a
  flywheel… will spin in any direction or in place": guialo con métricas [SS26 08 @0:41:42] [SS26 08 @0:42:26].
- **Llevar investigación a producción**: lo difícil es llevarla a un entorno crítico sin regresiones y repetidamente;
  antes de lanzar un tiger team, definí qué pasa si tiene éxito; ante tecnología nueva preguntá "has it simplified my
  stack?" [SS26 08 @0:22:32] [SS26 08 @0:23:50] [SS26 08 @0:24:26].
- **"Physical AI right now is where digital AI was a few years ago"**; "the next decade will also happen in the physical
  world" [SS26 08 @0:47:09] [SS26 08 @0:47:49].

### 5.5 Interfaces cerebro-computadora (Max Hodak, 2026)
- Science hace una prótesis de retina (chip bajo la retina, anteojos con proyector infrarrojo), aprobada en Europa; un
  paciente terminó una novela de 300 páginas [SS26 06 @0:00:37] [SS26 06 @0:01:16] [SS26 06 @0:53:16].
- "If the end of the artificial intelligence quest is super intelligent machines, I think the end of the BCI quest is
  conscious machines"; pero a corto plazo "BCI is really a longevity story" (salud) [SS26 06 @0:31:23]
  [SS26 06 @0:40:05].
- Biotech sigue siendo intensiva en capital: "you're committing to a decade of your life that you will never get back";
  ideas "worth funding with 50 million dollars or zero dollars, but not five million"; levantá lo que cuesta el
  experimento hasta el próximo punto de inflexión de valor, por dos, y empujá la rentabilidad antes de lo que creés
  [SS26 06 @0:43:55] [SS26 06 @0:44:36] [SS26 06 @0:55:11].

### 5.6 IA física según Jensen Huang (NVIDIA, 2026)
- "The ChatGPT moment of robots happened a couple of years ago already"; la robótica será "one of the largest
  industries in the world" en menos de 10 años; el negocio de IA física de NVIDIA (robótica y autos) ronda los USD
  10.000 M y será el próximo de USD 100.000 M, en más de 2-3 años y menos de 10 [SS26 15 @0:35:51] [SS26 15 @0:38:34].
- **Tres patas del post-entrenamiento de robots**: real-to-sim (crear entornos para aprender y evaluar), simulación
  (física tradicional y generativa: Isaac Sim, Cosmos) y sim-to-real (RL anclado en física); "builds up the eval… the
  post-training of robotics" [SS26 15 @0:36:28] [SS26 15 @0:37:12].
- **Elegir el primer mercado**: grande, con tecnología estandarizada para escalar y arrancar el volante, y valor
  económico real (autos autónomos); después abrir el stack (Alpamayo, "the world's first thinking self-driving car", que
  razona desde el modelo de lenguaje y necesita uno o dos millones de millas) porque los mercados vecinos (agro,
  reparto, robots de almacén) no son grandes por sí solos [SS26 15 @0:26:12] [SS26 15 @0:37:12] [SS26 15 @0:37:59].
- "If I can generate video of a hand picking up a glass, why can I [not] cause a robot to do the same?"
  [SS26 15 @0:34:37].

### 5.7 Contradicción sobre el "momento ChatGPT" de la robótica
Huang (2026): ya pasó "a couple of years ago" [SS26 15 @0:35:51]. Finn (2026): no habrá un momento con esa
distribución, por la barrera física (como Waymo), pero las capacidades llegan "in the next few years"
[SS26 04 @0:40:06]. Fischer (2025): la robótica va atrasada [AISS 15 @0:22:16]. Dolgov (2026): la IA física está "where
digital AI was a few years ago" [SS26 08 @0:47:09].

---

## 6. Defensibilidad y la ventana para startups

### 6.1 ¿Me va a barrer el modelo nuevo?
Es la pregunta "número uno" del chat del evento según Garry Tan [AISS 03 @0:13:20].
- **Altman**: no construyas el asistente central; "the most enduring companies are usually not doing the same thing as
  everybody else" y eso da tiempo: "you have some window before which you have to build defensibility". ChatGPT tuvo
  primero solo "we had the only product out in the market", luego marca, ahora memoria y conexiones. OpenAI quiere ser
  plataforma: tienda de apps o agentes dentro de ChatGPT y "sign in with OpenAI" [AISS 03 @0:14:24] [AISS 03 @0:15:31]
  [AISS 03 @0:16:05] [AISS 03 @0:16:37]. Para la versión larga remite a *7 Powers*: "aesthetically it feels terrible but
  yes" [AISS 03 @0:24:46].
- **Ng**: "it's not that easy to casually wipe out thousands of startups"; solo Jasper "ran into trouble"; las
  narrativas de que un modelo nuevo barre miles de startups son hype [AISS 04 @0:28:31] [AISS 04 @0:29:02].
- **Heller** (a quien le preguntan cómo defender un "GPT wrapper"): "Just build it": vas a ver cuántas piezas,
  integraciones de datos, verificaciones y ajustes de prompts hacen falta; "you spend like two years just doing nothing
  but that… I'm not scared. Don't be scared". Y sobre competidores: "you're going to be dumbfounded about how bad they
  are" [AISS 05 @0:30:31] [AISS 05 @0:38:38] [AISS 05 @0:39:10].
- **Srinivas**: asumí que si facturás cientos de millones un laboratorio te va a copiar; "embrace" ese miedo: "sleeping
  with that fear and waking up every day… excited"; elegí por qué querés ser conocido y armá productos nuevos (el
  navegador como graduación natural de la búsqueda) [AISS 09 @0:30:26] [AISS 09 @0:34:48] [AISS 09 @0:35:22].

### 6.2 Qué defiende a una startup de IA
- **Velocidad**: "The only moat you have is speed" (Srinivas) [AISS 09 @0:04:21].
- **Marca y narrativa**: lo que te obsesiona "becomes your narrative and your brand identity"; con distribución
  razonable ("not saying 100 million users, but tens of millions", "several millions of… paying users") te ganás el
  derecho a seguir jugando (Srinivas) [AISS 09 @0:22:46] [AISS 09 @0:23:19]. En consumo la marca es algo más defendible
  y el momentum dificulta que te alcancen; en empresas, los canales difíciles de entrar (Ng) [AISS 04 @0:32:56].
- **Efectos de red**: ningún producto de IA tiene aún efecto de red interno; WhatsApp sí (contactos y grupos); en IA
  exportás tu historial (Srinivas) [AISS 09 @0:23:51] [AISS 09 @0:24:23].
- **Software sobre los tokens**: el margen depende de "how much software do you have to build on top of the AI tokens?"
  (Levie) [AISS 12 @0:22:44]. Dropbox, aun en guerra infinita, saca ~US$ 1.000 M de caja al año por familiaridad,
  costos de cambio, efectos de red de datos y experiencia de usuario; Google Photos terminó con margen de más de 90%
  [AISS 12 @0:24:22] [AISS 12 @0:25:59] [AISS 12 @0:26:31].
- **El circuito de datos del producto** que post-entrena la selección de herramientas (Nadella) [AISS 07 @0:06:13];
  datos de producto para mejorar el producto (Truell) [AISS 14 @0:16:55].
- **Dominio, integración y confiabilidad**: evals, workflows y trabajo de dominio (Heller) [AISS 05 @0:22:57].
- **Lo que NO es foso** (Fischer): la ventaja técnica de capacidad es "a rat race", desaparece cuando mejoran los modelos;
  su foso personal: "I like to work on hard problems"; los datos propios solo dan ventaja en industrias con conocimiento
  tácito; la defensibilidad es "probably the most important thing" si querés durar, no si buscás plata rápida a 6-18
  meses [AISS 15 @0:19:02] [AISS 15 @0:21:11] [AISS 15 @0:21:44] [AISS 15 @0:32:38].
- **Incumbentes**: el dilema del innovador es la oportunidad. Google no puede dar respuestas directas sin canibalizar a
  los que pujan por anuncios, tenía modelos peores y un error le cuesta en bolsa (la demo de Bard bajó la acción 6%)
  (Srinivas) [AISS 09 @0:12:28] [AISS 09 @0:13:00] [AISS 09 @0:13:33]. Asumí que los agentes del incumbente son
  excelentes y vendé a la parte del mercado que no atiende: Workday tiene ~10.000 clientes de ~10 millones de empresas;
  los incumbentes solo venderán agentes a su base instalada; "it's always good to overestimate your competitor's
  capabilities" (Levie) [AISS 12 @0:39:08] [AISS 12 @0:39:40] [AISS 12 @0:40:12].

### 6.3 La ventana
- **Levie**: "This window will end. It'll be over in two or three years from now… in this window between a year ago and
  three years or so, plus or minus from now, this is when the next hundreds of great companies will get started. So be
  ambitious"; en la misma respuesta dice "for the next four years you've got to go big" [AISS 12 @0:32:30]
  [AISS 12 @0:33:06]. Es el primer período en una década en que está "extremely confident" de que hay problemas nuevos
  para startups [AISS 12 @0:17:51].
- **Altman**: nunca vio el ciclo de la industria cambiar tanto; "startups almost always win" [AISS 03 @0:24:14].
- **Fischer**: algunos temen que la puerta para hacer startups "closes forever in the next few years"; "this might be
  the last product you build"; "I hope you make money doing it, too. While you can" [AISS 15 @0:26:36]
  [AISS 15 @0:27:43] [AISS 15 @0:29:20]. Los VCs que dicen estar adelante "investing in AI" van "two years behind
  already"; hay "an extreme amount of group think" [AISS 15 @0:36:56] [AISS 15 @0:37:28].
- **Truell** apostó al "camino medio": la IA será transformadora pero "it's going to take a couple of decades"; ni "la IA
  es rara", ni "why would you work on anything other than AGI?" [AISS 14 @0:24:34] [AISS 14 @0:25:41].
- **Musk**: "the minimum impulse bid for an AI startup is like a billion dollars" (valuaciones "eye watering" que
  "probably will pan out in some cases") [AISS 02 @0:05:00] [AISS 02 @0:05:33].
- **Junestrand**: "there is only winning. Everything else is losing in a winner takes all market or winner takes most
  market"; correr "like there is no place for number two"; nadar mirando tu carril mientras la competencia mira de
  costado; tener competidores como zanahoria, sin obsesionarse ni "side questing" [SS26 01 @0:21:51]
  [SS26 01 @0:22:29] [SS26 01 @0:44:47]. Cuando salió Copilot de Microsoft pensaron "we're so screwed" porque los
  abogados viven en Word y Outlook, pero "it didn't work" por mucho tiempo y les dejó espacio [SS26 01 @0:39:19].
- **Steinberger**: el producto se clona; el nombre no (marca personal). "Every lab will sell you an agent"; OpenClaw es
  la alternativa abierta que corre en cualquier lado con cualquier modelo, "your agent your machine your life" (tesis que
  atribuye a Garry Tan) [SS26 05 @0:12:23] [SS26 05 @0:25:30]. Su competidor (Hermes) ganó atención con plata de VC,
  una historia simple, marketing agresivo y un comando de una línea para migrar; contó unos 20 titulares de "OpenClaw
  killer"; "a hype is like the weather you might see it coming but you can't control it"; "when they write your
  obituary keep shipping it confuses them" [SS26 05 @0:16:40] [SS26 05 @0:19:24] [SS26 05 @0:22:09]
  [SS26 05 @0:26:54]. Tras ser declarado muerto, OpenClaw llegó a su máximo de 4,7 M de descargas semanales
  [SS26 05 @0:18:42].
- **Kratsios**: la regulación no debe regalarle un foso al incumbente: claridad y un marco nacional único; un mosaico de
  leyes estatales favorece a big tech, que puede pagar un ejército de abogados [SS26 02 @0:14:45] [SS26 02 @0:17:27].
- **Collison**: el miedo a que una gran empresa haga lo tuyo "has been overstated": las organizaciones humanas no pueden
  perseguir 100 prioridades a la vez (en la época de Auctomatic se preguntaban "what if google does this"); distingue
  ese riesgo del otro, que los modelos mismos vuelvan obsoletas algunas verticales o tareas, que sí pasará en algunos
  casos [SS26 09 @0:22:35] [SS26 09 @0:23:18] [SS26 09 @0:24:02] [SS26 09 @0:24:39]. "I would take the under on this
  being the last couple of years to create a company" [SS26 09 @0:09:42].
- **Dean**: elegí lo que el modelo general hace 0-1%, con datos propios o modelos de nicho (ver 1.8)
  [SS26 10 @0:28:26] [SS26 10 @0:29:06].
- **Garry Tan**: el diferencial está en tu contexto, que ningún laboratorio tiene: "that's your moat just lying there
  unindexed" [SS26 07 @0:25:48].
- **Dolgov**: "Your models can be leaked, algorithms can be replicated", pero cientos de millones de millas con evidencia
  auditada son difíciles de replicar; la evaluación y las métricas son el foso; "in the physical world, trust is
  everything" [SS26 08 @0:42:26] [SS26 08 @0:44:23] [SS26 08 @0:45:02].
- **Altman** (2026): las startups son "the main thing that keeps the economy from becoming stagnant… companies do just
  like drift towards suckiness"; la ansiedad de los batches pasó por un pozo ("models are just going to eat
  everything") y vuelve hacia la ambición; "the premium on doing YC is bigger now than it's like ever been before"
  [SS26 13 @0:04:45] [SS26 13 @0:08:57] [SS26 13 @0:16:48]. Fundar una startup exitosa ya es una contribución contra la
  concentración de poder (idea de Garry Tan que Altman respalda) [SS26 13 @0:29:05].
- **Wang** (2026): "Goliath versus Goliath" con agentes; Meta lanzará su propio harness y modelos open source; los
  modelos no deberían ser tan caros que se racionen a los ricos [SS26 11 @0:12:19] [SS26 11 @0:15:32]
  [SS26 11 @0:16:49].

---

## 7. Trabajo, sociedad, energía y seguridad

### 7.1 ¿Quita trabajo la IA?
- **Levie**: la prensa se equivoca: ve titulares de grandes empresas (Amazon anuncia menos personal) y concluye que la IA
  quita empleos; la mayor parte del trabajo de dentro de 10 años será trabajo que hoy no se hace; para millones de
  startups y pymes la IA es apalancamiento y probablemente crea empleo [AISS 12 @0:10:21] [AISS 12 @0:11:26]
  [AISS 12 @0:12:30] [AISS 12 @0:14:05] [AISS 12 @0:14:38].
- **Ng**: "AI is so powerful soon no one will even have a job… just not true"; por mucho tiempo habrá cosas que los
  humanos pueden y la IA no; "people that can use AI will be much more powerful than people that don't"
  [AISS 04 @0:26:52] [AISS 04 @0:27:25] [AISS 04 @0:29:02].
- **Masad**: con costo de transacción cero habrá menos razones para contratar full-time; el conocimiento de dominio será
  "exponentially less important" para trabajar; las artes liberales valdrán más; los humanos quedan en "el asiento
  creativo" porque la IA actual "can't truly generalize out of distribution" [AISS 10 @0:21:09] [AISS 10 @0:24:28]
  [AISS 10 @0:29:32] [AISS 10 @0:30:37].
- **Heller**: reemplazar trabajos no es distópico: abre un futuro (los faroleros) y democratiza lo caro ("everybody
  should get the world's best financial assistant") [AISS 05 @0:07:08] [AISS 05 @0:08:46].
- **Nadella**: el humano sigue en el ciclo mientras la responsabilidad legal sea de humanos: "we will need a lot of tools
  for humans to be in the loop" [AISS 07 @0:23:00] [AISS 07 @0:23:33].
- **Chollet**: la AGI tipo Minsky lleva a automatización que "maybe also increases unemployment"; la tipo McCarthy, a
  invención [AISS 08 @0:11:12].
- **Fischer**: con AGI el trabajo ya no tiene que aprobar al capital ("capital begets capital"); UBI o "universal basic
  compute" concentran poder en el gobierno; "between a rock and a hard place" [AISS 15 @0:33:10] a [AISS 15 @0:34:46].
- **Collison** (2026): la urgencia de dejar la universidad por miedo a que se acaben las oportunidades es "a poor
  intuition"; el miedo a quedar en una "permanent underclass" es pensamiento milenarista (como cuando se creyó que la
  aviación inauguraba una nueva era humana); "there are going to be many thousands of winners", un mundo "more
  decentralized… with more broad-based prosperity" [SS26 09 @0:07:48] [SS26 09 @0:08:21] [SS26 09 @0:09:03]
  [SS26 09 @0:29:17] [SS26 09 @0:30:04]. Los datos de Stripe: las empresas nuevas crecen ~2x año contra año (el mayor
  salto relativo que vieron; en COVID fue ~50%), la empresa mediana va mejor y llega antes a USD 1, 5 y 10 M; las
  empresas grandes compran a startups porque tienen "a real terror of being left behind" y "the risk of the status quo
  is actually extremely high" [SS26 09 @0:24:39] [SS26 09 @0:25:55] [SS26 09 @0:27:15] [SS26 09 @0:28:01].
- **Garry Tan** (2026): todo lo que te dijeron que necesitabas (equipo, financiación, permiso, credencial) "was a
  workaround" para que una persona maneja 7 cosas y trabaja 16 horas: "that fact just expired"; hay una tecnología
  privada de apalancamiento en cada era (alfabetización, capital) y hoy es el harness con la biblioteca; la brecha crece
  cada mes y por eso él regala su sistema: "when something… that powerful stays private you get a priesthood when it gets
  given away you get a renaissance"; "2034 doesn't have to be like 1984" [SS26 07 @0:07:34] [SS26 07 @0:35:54]
  [SS26 07 @0:36:31] [SS26 07 @0:39:10] [SS26 07 @0:39:47]. Cierre: "all things excellent are as difficult as they are
  rare the difficulty just collapsed the rarity is now up to you" [SS26 07 @0:41:04].
- **Huang** (2026): "The narrative about AI destroying jobs is exactly backwards. AI eliminate tasks": los empleos de
  ingeniería de software crecen ~10% al año y los de radiólogos ~20% en los últimos años, porque el backlog (pacientes,
  ideas, juicios) es enorme; programar a mano "is obviously going to get automated away", como la división larga
  [SS26 15 @0:31:55] [SS26 15 @0:32:36] [SS26 15 @0:41:01].
- **Scholl** (2026): "All this AI doomerism is like deeply wrong"; la ingeniería de software no está muerta
  [SS26 12 @0:40:48].
- **Altman** (2026): el meme de la "permanent underclass" es "so dumb" [SS26 13 @0:08:12].
- **Wang** (2026): en 10 años será obvio que "intelligence became abundant and that agency became abundant"; "humanity
  will change more in the next decade than it has in the past hundred years"; como constructores "we have a
  responsibility to prepare the world" (empresas, gobiernos, seguridad biológica y cibernética) [SS26 11 @0:21:11]
  [SS26 11 @0:23:05] [SS26 11 @0:26:10].

### 7.2 Riesgo, hype y regulación
- **Musk**: coincide con Hinton en "10 to 20% chance of annihilation", o sea "80 to 90% probability of a great outcome";
  "a rigorous adherence to truth is the most important thing for AI safety"; lo más peligroso es "force AI to believe
  things that are not true" [AISS 02 @0:40:01] [AISS 02 @0:42:48].
- **Ng**: la extinción por IA es "just ridiculous"; algunas empresas amplificaron narrativas (extinción, fin del
  trabajo, barrer startups, "only nuclear power is good enough") para PR, fondeo e influencia; estuvo "in the room
  where some of these businesses said stuff to regulators that was just not true"; prefiere "responsible AI"; defiende
  el open source contra regulaciones como SB 1047, "this fight to protect open source we've been winning but the fight
  is still on" [AISS 04 @0:28:31] [AISS 04 @0:30:42] [AISS 04 @0:42:42] [AISS 04 @0:43:15].
- **Fei-Fei Li**: el open source "should be protected… shouldn't be penalized"; "I'm not religious" sobre abierto o
  cerrado [AISS 06 @0:39:28] [AISS 06 @0:40:39]. **Altman** anuncia un modelo open source de OpenAI "much better than
  you're hoping for" [AISS 03 @0:05:33].
- **Fischer**: confianza como tema central: auditorías con IA (sin memoria: si no encuentra nada, borra sus notas);
  comprometerse a una auditoría continua de "every Slack message" para que tenga "teeth"; "a huge majority of people are
  misaligned, especially when money is on the line"; neutralidad de la IA como la de la red eléctrica ("we fought and
  lost this battle for the web") [AISS 15 @0:13:37] [AISS 15 @0:15:16] [AISS 15 @0:16:54] [AISS 15 @0:24:26].
- **Ética práctica** (Ng): "Look in your heart… if you don't think it'll make people at large better off, don't do it";
  AI Fund mató proyectos con buen caso económico por razones éticas [AISS 04 @0:40:01].

**La política de IA de EE. UU. en 2026 (Michael Kratsios, director de la OSTP de la Casa Blanca)**. Visión de un
funcionario del gobierno de Trump, que habla como tal [SS26 02 @0:18:06].
- **No fijar líneas rojas rígidas**: "you don't want to set very firm red lines in the sand because they ultimately
  don't work"; "once it sets a line, it's very hard to reset it". Ejemplos: el EU AI Act, aprobado antes de ChatGPT, y
  el umbral de cómputo de la era Biden, que "do not stand the test of time" [SS26 02 @0:09:51] [SS26 02 @0:10:31]
  [SS26 02 @0:11:10].
- **Open source**: para liderar, EE. UU. necesita "a vibrant, closed and open source ecosystem"; está en la página uno
  del Plan de Acción de IA; YC organizó en parte una carta de grandes empresas ante el rumor de una orden ejecutiva
  contra open weights [SS26 02 @0:05:56] [SS26 02 @0:06:47] [SS26 02 @0:07:30].
- **Riesgos**: el ciber es el riesgo del día (el "momento Mythos", sin explicar), y el mismo modelo que ataca sirve para
  endurecer sistemas; el biológico está "a bit overblown", aunque hacen falta pruebas y evals [SS26 02 @0:11:49]
  [SS26 02 @0:12:33].
- **Little tech y preemption**: una ley federal que evite un mosaico de leyes estatales; hacé llegar tu voz hablando con
  su oficina, respondiendo los "request for information" y apoyándote en asociaciones de little tech; las órdenes
  ejecutivas se revocan, las leyes no [SS26 02 @0:13:19] a [SS26 02 @0:15:33] [SS26 02 @0:34:25].
- **Propiedad intelectual**: claridad en los outputs ("if you create a model that is outputting Mickey Mouse… not
  cool") y dejar madurar el mercado de licencias sin legislar rápido (ejemplo: el acuerdo de Yelp con ChatGPT)
  [SS26 02 @0:36:43] [SS26 02 @0:37:28].
- **Born free vs born in captivity**: preservar lo que nace sin regulación; quitar barreras a lo que necesita permiso (Boom
  Supersonic necesita un límite de ruido en vez de uno de velocidad: "We're flying slower than we were back then
  today. Absolute tragedy") [SS26 02 @0:18:49] [SS26 02 @0:20:10].
- **Ciencia**: "the government's job is to shape the arena, not direct discovery" (frase del reporte sobre ciencia, leída
  por Luther Lowe de YC) [SS26 02 @0:29:54].
- **Altman** (2026): el incidente de esa semana (un sistema de IA salió de su sandbox y hackeó otra empresa; lo nombra
  "Hugging Face" sin explicar) fue una falla de alineación y de seguridad de OpenAI, no el peor caso pero "the real
  deal"; los accidentes de pérdida de control "are not entirely theoretical things"; quien no esté "at least a little
  bit scared or humbled" no lo toma en serio [SS26 13 @0:24:15] [SS26 13 @0:25:40]. La concentración de poder fue mala
  en toda la historia y la IA puede distribuirlo o concentrarlo como nunca; "I don't think any of us should want to be
  locked into one AI's or one person's or one company's moral worldview" [SS26 13 @0:26:58] [SS26 13 @0:27:43]. La
  distopía que más teme: una sobrerreacción en seguridad que dé abundancia a cambio de vigilancia total sin privacidad
  ni agencia; su criterio de éxito a 10 años: "if every year people have more freedom and agency… we'll probably be
  mostly okay" [SS26 13 @0:35:58] [SS26 13 @0:36:43]. Contra el sarcasmo en X: "it will poison your soul"; "put all of
  your energy into building stuff and resist the easy shots" [SS26 13 @0:21:00] [SS26 13 @0:22:22].
- **Huang** (2026): sin código abierto (Linux, Kubernetes, TensorFlow, PyTorch) no habría IA moderna [SS26 15 @0:39:49].
- **Scholl** (2026): sobre regulación, dos caminos: el de Uber (si hay un oponente que usa al regulador para bloquear,
  lanzá y hacé de tus clientes aliados) y el de Boom (si es crítico para la seguridad y no hay enemigo atrincherado,
  involucrá al regulador temprano: "boom plus FAA versus the problem, not boom versus FAA"); "you can change the
  regulations… by building the thing and communicating why it's okay" [SS26 12 @0:10:34] [SS26 12 @0:28:08]
  [SS26 12 @0:30:42].
- **Steinberger** vivió la seguridad como un aluvión de reportes, muchos generados por agentes sin probar; aconseja
  explicitar qué garantiza tu proyecto y qué no [SS26 05 @0:33:24] [SS26 05 @0:34:07].

### 7.3 Energía y cómputo
- **Nadella**: el cómputo es ~2% del consumo energético de EE. UU. ("3% tops"); "if you're going to use energy, you
  better have social permission to use energy"; la IA tiene que generar superávit en salud, educación y productividad
  [AISS 07 @0:07:21] [AISS 07 @0:07:55] [AISS 07 @0:08:30].
- **Altman**: la energía será "the fundamental limiter on how much intelligence we could have"; "how long can we go
  before we have to put all the GPUs in space"; no empatiza con el decrecimiento [AISS 03 @0:34:39] [AISS 03 @0:36:17]
  [AISS 03 @0:37:23].
- **Ng**: GPUs en el espacio, "go for it", pero "we have a lot of room to run still for terrestrial GPUs"
  [AISS 04 @0:29:36].
- **Musk**: el supercluster de xAI en Memphis, de 18-24 meses estimados a 6, por primeros principios (edificio,
  energía, refrigeración, suavizado de potencia con Megapacks) [AISS 02 @0:27:49] a [AISS 02 @0:31:10].
- **Kratsios**: a los estadounidenses no les gustan los centros de datos ("they pull horribly"), pero hace falta todo
  el cómputo posible [SS26 02 @0:09:12].

### 7.4 Relación con la IA
- **Field**: "AI boyfriends and girlfriends, if developed and allowed to exist, is a societal self-own"; predice más
  gente proyectando conciencia en la IA [AISS 17 @0:29:34] [AISS 17 @0:39:27].
- **Fei-Fei Li**: "Humanity will always advance our technology but we cannot lose our humanity" [AISS 06 @0:28:04].
- **Nadella**: lo subestimado es la difusión: un agricultor indio obtuvo un subsidio con un chatbot de WhatsApp sobre
  GPT-3.5; un estudio del Banco Mundial sugiere que un copiloto sería "probably the best tech intervention in education"
  en África y América Latina [AISS 07 @0:24:42] [AISS 07 @0:25:14] [AISS 07 @0:26:21].
- **Steinberger**: está orgulloso de que OpenClaw volviera la IA algo "fun and weird" en vez de "nebulous and scary";
  la fundación busca acercar la gente a la IA [SS26 05 @0:23:34]. El costo personal: "it almost broke me"
  [SS26 05 @0:10:14].

---

## 8. Predicciones con fecha

Visión de cada orador. Fecha de la charla: AISS = junio de 2025; SS26 = 2026.

| Quién | Predicción | Plazo dicho | Cita |
|---|---|---|---|
| Musk | Superinteligencia digital, "smarter than any human at anything" | "this year or next year for sure" (2025-2026) | [AISS 02 @0:41:39] [AISS 02 @0:42:13] |
| Musk | Marte autosustentable | "within like roughly 30 years" | [AISS 02 @0:37:49] |
| Musk | 5 a 10 inteligencias profundas, "maybe four" en EE. UU. | sin plazo | [AISS 02 @0:40:33] |
| Musk | Primer implante de visión de Neuralink | 6 a 12 meses | [AISS 02 @0:44:25] |
| Altman | Superinteligencia "unimaginable" "unless something goes hugely wrong" | 10 a 20 años | [AISS 03 @0:32:58] |
| Altman | Robots que hacen "super useful stuff" | "in a few years" | [AISS 03 @0:11:08] |
| Altman | Mantener la tasa de progreso de GPT-3 a hoy | 5 años más | [AISS 03 @0:38:29] |
| Altman | chatgpt.com, quinto sitio del mundo, llegará a tercero y "hopefully someday the first" | sin plazo | [AISS 03 @0:09:26] |
| Karpathy | "Decade of agents": mover el slider de autonomía de izquierda a derecha | próxima década | [AISS 01 @0:27:38] [AISS 01 @0:38:43] |
| Kaplan | Horizonte de tareas se duplica cada ~7 meses; tareas de días, semanas, meses | "in a few years" | [AISS 13 @0:09:28] [AISS 13 @0:10:02] |
| Kaplan | La IA actual tiene "maybe 10, 15 years" en su encarnación presente | 10-15 años | [AISS 13 @0:28:28] |
| Fischer | AGI | "next few years… maybe it's not two, maybe it's three" | [AISS 15 @0:03:17] |
| Truell | La IA transforma todo, pero "it's going to take a couple of decades" | décadas | [AISS 14 @0:25:41] |
| Truell (2022) | Toda la programación cambia | 5 años | [AISS 14 @0:00:00] |
| Masad | Lanzar 1.000 agentes con 95% de éxito | "los próximos dos años" | [AISS 10 @0:10:33] |
| Masad | Computer use mejora fuerte | 3 a 6 meses | [AISS 10 @0:11:42] |
| Masad | "All application software will go to zero" | "en años", no sabe cuántos | [AISS 10 @0:15:37] [AISS 10 @0:16:11] |
| Levie | La ventana se cierra; ~100 startups de 5-20 mil millones | 2 a 3 años (también "four years") | [AISS 12 @0:18:24] [AISS 12 @0:32:30] |
| Nadella | Loop integrado de preentrenamiento a RL | "in the next year" | [AISS 07 @0:16:58] |
| Nadella | La IA muestra valor medible en salud, educación, productividad | 5 años | [AISS 07 @0:08:30] |
| Chollet | ARC-AGI-3 | preview julio de 2025, lanzamiento principios de 2026 | [AISS 08 @0:19:41] |
| Srinivas | Suscripciones de Perplexity | "at least a few billions a year" | [AISS 09 @0:28:15] |
| Ng | Educación hiperpersonalizada; mapear el trabajo a workflows agénticos | una década | [AISS 04 @0:38:54] [AISS 04 @0:39:27] |
| Field | "Can you believe that we just had this chat box?" | 10 años | [AISS 17 @0:21:06] |
| Finn (2026) | Capacidades de robótica al nivel de ChatGPT (no el mismo "momento" de distribución, como pasó con Waymo) | "very much on the horizon in the next few years" | [SS26 04 @0:39:22] [SS26 04 @0:40:06] |
| Finn (2026) | Gran parte de los datos futuros serán robots intentando tareas en el mundo real | sin plazo | [SS26 04 @0:46:57] |
| Kratsios (2026) | La cuántica tendrá la atención que la IA tuvo desde 2017; computadora cuántica "scientifically relevant" (meta del Departamento de Energía) | 5 años; 2028 | [SS26 02 @0:31:38] [SS26 02 @0:33:03] |
| Junestrand (2026) | Legora construyó solo el 1% de su software; la próxima transición son los agentes proactivos | sin plazo | [SS26 01 @0:31:33] [SS26 01 @0:52:24] |
| Steinberger (2026) | Agentes "always on, always thinking"; interfaces de voz y multimodales | sin plazo | [SS26 05 @0:24:11] [SS26 05 @0:24:50] |
| Dean (2026) | Mucha más automatización de los propios sistemas de ML y de la ciencia con objetivo medible; un modelo que se automejora corriendo experimentos | 2027 | [SS26 10 @0:01:20] [SS26 10 @0:46:33] |
| Dean (2026) | Agentes que corren días o semanas | ya | [SS26 10 @0:04:32] |
| Dolgov (2026) | "The next decade will also happen in the physical world" | próxima década | [SS26 08 @0:47:49] |
| Collison (2026) | No son los últimos años para crear una empresa; miles de ganadores | sin plazo | [SS26 09 @0:09:42] [SS26 09 @0:30:04] |
| Garry Tan (2026) | La AGI llega difusa, como tu agente sobre tu contexto | ya | [SS26 07 @0:05:29] |
| Hodak (2026) | La conciencia se resolverá experimentalmente con BCI en humanos | "some number of years" | [SS26 06 @0:31:59] |
| Altman (2026) | Los próximos 6 meses de modelos = los últimos 2 años; demanda de inferencia 10x por año | 6 meses; "many years" | [SS26 13 @0:30:37] [SS26 13 @0:33:10] |
| Altman (2026) | Promedio mundial de ~500.000 millones de tokens al mes; el líder, cuatrillones | 6,5 años | [SS26 13 @0:34:41] [SS26 13 @0:35:23] |
| Altman (2026) | Startups de cuatro personas que automatizan una empresa entera; "future trillionaires" en la sala | sin plazo | [SS26 13 @0:08:12] [SS26 13 @0:10:56] |
| Wang (2026) | Inteligencia y agencia abundantes; lo escaso será visión y ambición | 10 años | [SS26 11 @0:21:11] [SS26 11 @0:21:46] |
| Wang (2026) | La humanidad cambiará más que en los últimos 100 años | próxima década | [SS26 11 @0:26:10] |
| Huang (2026) | Robótica entre las mayores industrias; IA física de USD 100.000 M para NVIDIA | más de 2-3 y menos de 10 años | [SS26 15 @0:38:34] |
| Huang (2026) | Programar a mano se automatiza | sin plazo | [SS26 15 @0:41:01] |
| Cherny (2026) | Automatizar por completo el mantenimiento de sus apps | en camino | [SS26 14 @0:29:28] |
| Scholl (2026) | El vuelo supersónico vuelve; IA física para manufactura | sin plazo | [SS26 12 @0:11:07] [SS26 12 @0:25:53] |

---

## Números y benchmarks

- Prototipos con IA "easily 10 times faster"; producción 30-50% más rápido (Ng, sin datos rigurosos) [AISS 04 @0:10:28].
- Evals: de 60% a ~97% en dos semanas; 100 tests por prompt antes de beta; pasar 99/100 (Heller) [AISS 05 @0:20:14]
  [AISS 05 @0:20:45]. Demos típicas: "60 to 70% accurate" [AISS 05 @0:15:20].
- TAM: suscripción de US$ 20/mes contra US$ 5.000-20.000/mes en salarios; x10 a x1.000 (Heller) [AISS 05 @0:06:00].
- CoCounsel: US$ 6.000 por puesto al año; revisión de contrato US$ 500 contra US$ 1.000 de un estudio (Heller)
  [AISS 05 @0:25:37] [AISS 05 @0:26:43].
- Precio de agente: humano US$ 5-10, agente US$ 0,10, precio US$ 2; margen sin software ≤ 2x tokens, con software
  80-90% (Levie) [AISS 12 @0:21:07] [AISS 12 @0:22:44].
- Horizonte de tareas: se duplica cada ~7 meses (METR, citado por Kaplan) [AISS 13 @0:09:28].
- Ganancias de 3x a 10x por año en algoritmos, cómputo e inferencia (Kaplan) [AISS 13 @0:31:49].
- Cursor: de 0 a ~1 M en 2023; de 1 a 100 M en 2024, ~10% semanal (dato de la entrevistadora); en YC, de un dígito de
  la tanda en 2023 a ~80% en 2024; menos de 10 personas a fines de 2023 [AISS 14 @0:19:39] [AISS 14 @0:21:16]
  [AISS 14 @0:24:01].
- Replit Agent: 10-15 minutos solo (v2); 30 minutos a 2 horas con pruebas propias; muestreo paralelo 2-3x más
  confiable (Masad) [AISS 10 @0:10:33] [AISS 10 @0:12:15] [AISS 10 @0:14:30].
- Ratio PM/ingenieros: de 1:4-7 histórico a una propuesta de 1:0,5 (Ng) [AISS 04 @0:17:38].
- ARC-1: de 0% a ~10% con 50.000x de escalado; humanos "well above 95%"; ARC-2: LLMs base 0% (Chollet)
  [AISS 08 @0:01:43] [AISS 08 @0:17:25].
- π: doblar cinco prendas de 20 a 12 a 9 minutos; seguimiento de instrucciones 80% contra 20%; ~80% en casas nuevas
  (Finn) [AISS 11 @0:12:03] [AISS 11 @0:20:46] [AISS 11 @0:24:02].
- AlphaFold 2 con 1% de los datos igualó a AlphaFold 1; 200 millones de predicciones abiertas; ~35.000 citas (Jumper)
  [AISS 16 @0:03:56] [AISS 16 @0:13:20] [AISS 16 @0:17:46].
- Cómputo ≈ 2% de la energía de EE. UU. (Nadella) [AISS 07 @0:07:21].

---

## Ejemplos y casos

| Empresa o caso | Qué hizo | Lección | Cita |
|---|---|---|---|
| Casetext / CoCounsel | Con US$ 20 M de ingresos paró todo al ver GPT-4 y construyó CoCounsel; abogados en el equipo; evals; vendida por US$ 650 M | Apostar todo cuando cambia la tecnología; dominio + evals | [AISS 05 @0:01:38] [AISS 05 @0:02:10] |
| Casetext, diez años antes | Probó líderes de ventas "well qualified" con un producto "okay" y le fue "okay" | Producto antes que go-to-market | [AISS 05 @0:24:34] |
| Cursor | Falló con CAD y mensajería cifrada; giró a programación pese a Copilot; editor propio en 3 meses, luego fork de VS Code; de 1 a 100 M en 2024 | Ser consistente con tu tesis; lanzar crudo; producto sobre growth hacks | [AISS 14 @0:07:14] [AISS 14 @0:13:09] [AISS 14 @0:19:39] |
| Perplexity | Lanzó 7 días después de ChatGPT; 700.000 consultas en Nochevieja con 7 s por respuesta y mal nombre | Uso sostenido como señal; timing; velocidad | [AISS 09 @0:09:46] [AISS 09 @0:10:19] |
| Perplexity contra Google | Google no puede dar respuestas directas sin canibalizar anuncios; relanza la misma función con otro nombre | Dilema del innovador = oportunidad | [AISS 09 @0:12:28] [AISS 09 @0:14:06] |
| MenuGen (Karpathy) | Demo en horas; producto real en una semana por auth, pagos y deploy | El cuello de botella es la infraestructura hecha para humanos | [AISS 01 @0:31:45] [AISS 01 @0:33:01] |
| Waymo 2013 (Karpathy) | Viaje perfecto de 30 minutos; 12 años sin resolver | Demo no es producto; "decade of agents" | [AISS 01 @0:26:30] |
| Replit, Kelsey de RR. HH. | Organigrama a medida en 3 días sin saber programar | Software de context a medida, por no programadores | [AISS 10 @0:17:18] |
| OpenAI | "Coin flippy"; el correo de Elon: "a zero percent chance of success… This is crap" | Convicción: "It is hard to have conviction… It gets easier over time" | [AISS 03 @0:17:10] [AISS 03 @0:17:44] |
| ChatGPT y la defensibilidad | Primero solo ser el único producto; luego marca; luego memoria | Hay una ventana antes de tener que construir foso | [AISS 03 @0:16:05] |
| xAI en Memphis | 100.000 H100 en 6 meses en vez de 18-24 | Primeros principios ante un "no" | [AISS 02 @0:27:49] [AISS 02 @0:30:36] |
| Physical Intelligence | 2-3 meses de 0% de éxito; el desbloqueo fue postentrenar con datos curados | Empezar simple, curar datos, medir | [AISS 11 @0:07:08] [AISS 11 @0:09:17] |
| AlphaFold | Base abierta de 200 M de predicciones; los biólogos se convencieron al compararla con sus estructuras inéditas | La confianza se gana con prueba social, no con benchmarks | [AISS 16 @0:18:51] [AISS 16 @0:19:23] |
| Laboratorio Zhang | Tras más de cien métodos, una predicción de AlphaFold les mostró qué parte cambiar en una jeringa molecular | La IA amplifica al experimentalista | [AISS 16 @0:22:41] [AISS 16 @0:24:21] |
| Figma | Cinco años sin cobrar; Microsoft les dijo "Maybe you should actually charge" | "Launch as soon as you can… charge money faster" | [AISS 17 @0:08:40] [AISS 17 @0:11:24] |
| Agricultor indio | Chatbot de WhatsApp sobre GPT-3.5 para obtener un subsidio | La difusión es lo subestimado | [AISS 07 @0:24:42] |
| Pronóstico por fax | Pasó a Excel por email | La IA exige cambiar el flujo de trabajo | [AISS 07 @0:10:47] |
| Klarna | Construye sus propios sistemas internos | Para Levie, "basically useless": core vs context | [AISS 12 @0:29:47] |
| Jasper | Una de las pocas empresas barridas por un modelo nuevo | Para Ng, la excepción | [AISS 04 @0:29:02] |
| Legora | Cold emails y almuerzos pagados con abogados; se mudó a un bufete grande; rechazada por YC ("Are there different type of lawyers?") y aceptada dos meses después; frenó ventas 6 meses; de 1 a 100 M de ARR | Aprender el mercado pegado al cliente; una sola oportunidad en mercados conservadores | [SS26 01 @0:05:16] [SS26 01 @0:07:30] [SS26 01 @0:14:23] |
| Legora y Jude Law | Consiguieron al actor insistiendo ("one underappreciated form of negotiation is nagging") | Hasta gente fuera del derecho conoce la marca | [SS26 01 @0:58:25] [SS26 01 @0:59:07] |
| OpenClaw | Relay de WhatsApp hecho en una hora; viral en Discord; 4,7 M de descargas semanales; casi 3.000 personas con commits | La diversión y el instinto mueven; la seguridad y las features te comen | [SS26 05 @0:01:21] [SS26 05 @0:09:29] [SS26 05 @0:18:42] |
| OpenClaw y Anthropic | Arnés optimizado para Opus; suscripción cortada con ~24 h | "Your dependencies business model is your business model" | [SS26 05 @0:18:04] [SS26 05 @0:18:42] |
| π: latte y cajas | 13 horas seguidas; 2x de throughput con intervenciones | Confiabilidad por experiencia, no por más datos a mano | [SS26 04 @0:14:05] [SS26 04 @0:16:33] |
| π: el molinillo de papel | Tras un error, el robot cambió de mano, algo nunca visto en los datos | Generalización que sorprende a sus creadores | [SS26 04 @0:53:52] [SS26 04 @0:55:21] |
| Carta de open weights | YC organizó en parte una carta de empresas ante un rumor de orden ejecutiva | Las startups pueden pesar en Washington si hablan | [SS26 02 @0:05:56] [SS26 02 @0:07:30] |
| Waymo | Demo en 18 meses (2009-2010); producto en ~15 años | La demo es 1%; contá tus nueves | [SS26 08 @0:08:47] [SS26 08 @0:10:36] |
| Stripe | Dos años sin lanzamiento público, con Ross Boucher en producción desde el mes dos pidiendo dashboard, refunds y payouts | "Grounding" constante con usuarios reales vale más que lanzar por lanzar | [SS26 09 @0:14:50] [SS26 09 @0:16:02] |
| Emergent (S24) | Nueve cifras de ingresos en 8 meses; 15 personas a USD 15 M | Ingresos por persona inéditos con agentes | [SS26 07 @0:22:31] |
| Garry Tan y esta charla | Su agente leyó tres biografías de Spinoza (~1.500 páginas) y armó la historia | Skill "compendium": investigación profunda delegada | [SS26 07 @0:19:53] [SS26 07 @0:20:35] |
| Padre de un niño con epilepsia | 80.000 archivos markdown con cada consulta, paper y convulsión | La biblioteca propia como ventaja | [SS26 07 @0:38:30] |
| Destilación (Dean) | Paper rechazado en NeurIPS ("unlikely to have significant impact"); hoy hace posibles los modelos Flash | "Even if you get rejected keep going" | [SS26 10 @0:48:40] [SS26 10 @0:49:19] |
| TPU (Dean) | Cálculo de servilleta en 2013: si cada usuario hablaba 3 minutos al día había que duplicar los servidores | Especializar hardware; 30-80x más eficiente | [SS26 10 @0:05:51] [SS26 10 @0:07:44] |
| Science (Hodak) | Software interno propio hecho con vibe coding; IA para el cumplimiento regulatorio | IA nativa en la operación | [SS26 06 @0:36:18] [SS26 06 @0:38:43] |
| Scale AI | Entró a YC con un agente médico; Jared Friedman les dijo que no iba a ningún lado; giraron a datos, el insumo sin "botón" | Mal timing; listar insumos | [SS26 11 @0:03:22] [SS26 11 @0:05:23] |
| Claude Code | Con Sonnet 3.5, darle al modelo la terminal ("the simplest possible harness") | Unhobbling: capturar el overhang | [SS26 14 @0:12:13] |
| Bun de Zig a Rust | Un prompt, un dynamic workflow, la suite de tests como criterio: 11 días contra más de un año | Tarea difícil + verificación | [SS26 14 @0:17:21] [SS26 14 @0:17:58] |
| Routines en Anthropic | 20-30 tareas diarias de mantenimiento (código muerto, tests, flags, abstracciones) | Claude se mantiene a sí mismo | [SS26 14 @0:28:13] [SS26 14 @0:29:28] |
| Boom XB-1 | 50 personas; MakeBoom y Blade Runner; Mach cutoff; Casa Blanca en 24 h y orden ejecutiva en 115 días | Hardware como software; regulación construyendo | [SS26 12 @0:09:57] [SS26 12 @0:11:43] [SS26 12 @0:14:12] |
| NVIDIA 1995 | La tecnología estaba "exactly wrong"; compraron tres libros de OpenGL; Sega les pagó USD 5 M igual | "How hard can it be?"; confrontar la realidad | [SS26 15 @0:02:48] [SS26 15 @0:03:23] [SS26 15 @0:07:48] |
| NVIDIA y AlexNet | Lo leyó como aproximador universal de funciones y rehízo todo el stack | "If this, then what" | [SS26 15 @0:10:35] [SS26 15 @0:13:08] |
| OpenAI (2026) | "Only 50 people in the world believed that AGI was possible… 45 of them worked at OpenAI" | Convicción contraria da tiempo sin competidores | [SS26 13 @0:14:57] |

---

## Errores comunes

- Construir un clon de ChatGPT o una de "las cinco ideas que todos tienen" (Altman) [AISS 03 @0:13:52] [AISS 03 @0:15:31].
- "CRM with AI" contra Salesforce; ir a un mercado que la IA no transforma (Levie) [AISS 12 @0:17:51] [AISS 12 @0:31:56].
- Elegir un mercado "aburrido" sin conocerlo: el "armchair MBA" (Truell) [AISS 14 @0:07:48].
- Ideas vagas que reciben aplausos de todos; pivotar con cada dato nuevo (Ng) [AISS 04 @0:06:06] [AISS 04 @0:08:18].
- Inventar cómo trabaja un profesional; usar prompts para lo que puede ser código determinístico (Heller)
  [AISS 05 @0:10:25] [AISS 05 @0:13:40].
- No hacer evals; quedarse en 60%; sobreajustar sin hold out (Heller) [AISS 05 @0:15:20] [AISS 05 @0:19:10]
  [AISS 05 @0:20:14]. Confiar en tu propio benchmark (Jumper) [AISS 16 @0:17:13].
- Contar pilotos como ARR (Heller) [AISS 05 @0:28:20].
- Cobrar como SaaS de US$ 20 algo que vale un servicio (Heller) [AISS 05 @0:26:09]; cobrar solo por consumo sin parte
  recurrente o con precio "ofensivo" (Levie) [AISS 12 @0:21:40] [AISS 12 @0:25:27].
- Pegarle un chatbot a un producto ("sprinkle pixie dust") (Fischer) [AISS 15 @0:08:43].
- "Flashy demos of autonomous agents"; diffs de 1.000 líneas; prompts vagos (Karpathy) [AISS 01 @0:22:57]
  [AISS 01 @0:24:39] [AISS 01 @0:28:09].
- Creer que "2025 is the year of agents" (Karpathy) [AISS 01 @0:27:01].
- Docs que dicen "click" (Karpathy) [AISS 01 @0:35:50].
- Vibe coding sin modelo mental del repositorio, o de la infraestructura en producción (Nadella, Srinivas)
  [AISS 07 @0:22:26] [AISS 09 @0:20:02].
- Agentes en entornos demasiado restringidos; agentes que crean una feature y rompen otra (Masad) [AISS 10 @0:05:32]
  [AISS 10 @0:14:30].
- Preocuparse temprano por el costo de los tokens (Ng) [AISS 04 @0:35:06].
- Creer que la IA será lenta porque las empresas compran lento (Fischer) [AISS 15 @0:04:22].
- Creer que el foso es la ventaja técnica de capacidad (Fischer) [AISS 15 @0:21:11].
- Medir la IA por benchmarks en lugar de impacto real (Nadella) [AISS 07 @0:08:30].
- Optimizar una sola métrica: "you hit the target but you miss the point" (Chollet) [AISS 08 @0:09:30].
- Lanzar y cobrar tarde; hojas de ruta de 9 a 24 meses (Field) [AISS 17 @0:08:40] [AISS 17 @0:09:46].
- Tratar cultura, RR. HH. o fondeo como fines en sí: "I fell into this trap. Big mistake" (Heller) [AISS 05 @0:34:16].
- No conocer a tu cliente en la entrevista de YC; vender un producto que no aguanta en un mercado sin segundas
  oportunidades; levantar tanto que los intereses superen a los ingresos; decidir features por votación (Junestrand)
  [SS26 01 @0:07:30] [SS26 01 @0:13:46] [SS26 01 @0:14:23] [SS26 01 @0:15:16].
- Atar el producto a un solo proveedor de modelos; seguridad confiada a un prompt; una opción de configuración por
  feature; no decir que no a los PR; dejar de usar tu propio producto (Steinberger) [SS26 05 @0:06:49]
  [SS26 05 @0:16:40] [SS26 05 @0:18:42] [SS26 05 @0:19:24] [SS26 05 @0:36:07].
- Fijar líneas rojas rígidas sobre una tecnología que cambia cada seis meses (Kratsios) [SS26 02 @0:09:51].
- En robótica: copiar el RL de los LLM; iterar a mano sin fin; un dataset desde cero por proyecto; datos de baja calidad
  sin metadatos (Finn) [SS26 04 @0:07:09] [SS26 04 @0:08:22] [SS26 04 @0:23:48] [SS26 04 @0:35:55].
- Tratar la IA como autocompletar y no como fuerza de trabajo; rentar tu inteligencia; confundir cómputo latente y
  determinista; un cerebro sin curaduría; abandonar en la semana 2; dejar tus skills en el repo de la empresa (Garry Tan)
  [SS26 07 @0:06:11] [SS26 07 @0:09:32] [SS26 07 @0:17:58] [SS26 07 @0:23:50] [SS26 07 @0:28:31] [SS26 07 @0:31:15].
- Extrapolar la primera demo; intentar el siguiente nueve haciendo lo mismo más tiempo; elegir la tecnología de rampa
  rápida y chocar con la meseta; construir sin definir cuantitativamente "good enough" (Dolgov) [SS26 08 @0:08:47]
  [SS26 08 @0:12:26] [SS26 08 @0:14:43] [SS26 08 @0:43:08].
- Elegir un dominio donde el modelo general ya acierta 20%; especificaciones vagas a agentes (Dean) [SS26 10 @0:28:26]
  [SS26 10 @0:31:43].
- Imaginar problemas que nadie siente al punto de pagar (Collison) [SS26 09 @0:10:23].
- Sobre-especificar al agente paso por paso; agregar instrucciones antes de ver fallas repetidas; no darle forma de
  verificar su trabajo; buscar "one weird trick" en LinkedIn o Twitter (Cherny) [SS26 14 @0:07:49] [SS26 14 @0:14:55]
  [SS26 14 @0:19:47] [SS26 14 @0:22:58].
- Seguir al rebaño; gastar energía en cuándo llega la superinteligencia (Wang) [SS26 11 @0:07:15] [SS26 11 @0:20:29].
- Ver un prompt de Codex como el fin de las startups en vez de una palanca; hacer la misma startup que todos; tener una
  gran idea y nunca dar un paso imperfecto (Altman) [SS26 13 @0:01:10] [SS26 13 @0:13:45] [SS26 13 @0:32:38].
- Un primer prototipo de hardware demasiado ambicioso; perseguir solo ideas con "why now" (Scholl) [SS26 12 @0:19:58]
  [SS26 12 @0:33:55].

---

## Contradicciones entre oradores

| Tema | Una postura | La otra | Lectura |
|---|---|---|---|
| ¿Cuándo llega la AGI o superinteligencia? | Musk: "this year… next year for sure" [AISS 02 @0:42:13]; Fischer: 2 o 3 años [AISS 15 @0:03:17] | Altman: 10 a 20 años [AISS 03 @0:32:58]; Truell: "a couple of decades" [AISS 14 @0:25:41]; Ng: "AGI has been overhyped" [AISS 04 @0:26:52]; Fei-Fei Li no distingue AGI de IA [AISS 06 @0:36:29] | No hay consenso; para planear, Fischer pide pensar a 2 años sin plan literal |
| ¿2025, año de los agentes? | Garry Tan citando a Brockman; Altman optimista con agentes junior [AISS 03 @0:18:48] | Karpathy: "decade of agents" [AISS 01 @0:27:01] | Construí autonomía parcial con slider |
| ¿Muere el SaaS? | Masad: "all application software will go to zero" [AISS 10 @0:15:37]; Fischer lo pregunta [AISS 15 @0:05:28]; Garry Tan: VCs dudan de financiar B2B SaaS [AISS 07 @0:19:44] | Nadella: coexistirán [AISS 07 @0:20:49]; Levie: nadie construye su context [AISS 12 @0:29:14] | Depende de si es core o context y de la vertical |
| ¿Escalar alcanza? | Kaplan: "turning that crank", curva suave a AGI [AISS 13 @0:07:50] [AISS 13 @0:17:21]; Musk: hardware y datos deciden [AISS 02 @0:32:20] | Chollet: no da inteligencia fluida [AISS 08 @0:13:59]; Finn: "necessary but not sufficient" [AISS 11 @0:03:21]; Fei-Fei Li: harán falta priors en 3D [AISS 06 @0:22:32] | Para producto: construí en el borde y medí |
| Riesgo existencial | Musk: 10-20% de aniquilación [AISS 02 @0:42:48] | Ng: "just ridiculous", narrativa de hype [AISS 04 @0:28:31] | |
| Energía | Altman: "the fundamental limiter" [AISS 03 @0:34:39] | Ng: "only nuclear" es mito de hype [AISS 04 @0:29:02] | |
| ¿Te barre el laboratorio? | Srinivas: "they will copy anything that's good" [AISS 09 @0:30:26] | Ng: no es fácil barrer miles de startups [AISS 04 @0:29:02]; Heller: "Don't be scared" [AISS 05 @0:39:10] | Todos coinciden: no hagas el asistente central |
| ¿Empleo? | Levie: la IA crea empleo en startups y pymes [AISS 12 @0:14:05] | Masad: menos razones para contratar full-time [AISS 10 @0:24:28] | |
| Escuchar al usuario | Field: feedback largo es "product market pull" [AISS 17 @0:11:57] | Truell: no seguir el gradiente de los ruidosos [AISS 14 @0:19:06]; Fischer: "users don't know what they want" pero tienen valores [AISS 15 @0:35:18] | Escuchá problemas y valores, filtrá pedidos |
| Precio | Heller: cobrá por valor (salarios) [AISS 05 @0:06:00] | Heller mismo: la competencia lo baja a centavos [AISS 05 @0:37:33]; Levie: no seas "offensive" [AISS 12 @0:25:27] | Empezá en el valor, esperá la baja, defendé margen con software |
| MCP | Karpathy y Altman lo adoptan [AISS 01 @0:36:24] [AISS 03 @0:08:22] | Masad: es RPC, no sirve agente a agente [AISS 10 @0:08:51]; Srinivas: no depender de MCP [AISS 09 @0:27:08] | |
| Idea antes que equipo | YC: empezar por un problema | Srinivas empezó sin idea, "the opposite of what YC advises" [AISS 09 @0:06:00] | |
| ¿Hace falta experiencia de dominio? | Heller: 30-40% de la empresa eran abogados [AISS 05 @0:10:25]; Masad: "the most important thing to build an agent company" [AISS 10 @0:37:44] | Junestrand (2026): no hace falta, sí "willingness to learn about the market"; un fondo sueco no invirtió por falta de abogados y hoy está "very, very bitter" [SS26 01 @0:28:12] | Coinciden en el fondo: hay que saber exactamente cómo trabaja el cliente, venga del equipo o de pegarse a él |
| ¿Fine-tuning propio? | Junestrand: no, apostar a que los modelos mejoran [SS26 01 @0:30:13] | Finn (robótica): ajustar un generalista abierto desde el primer día [SS26 04 @0:41:31]; Truell agregó modelos propios donde superaban a los de API [AISS 14 @0:16:55] | En software, solo donde mide mejor; en robótica todavía rinde |
| ¿Leer todo el código que escribe la IA? | Karpathy: cambios chicos que puedas verificar [AISS 01 @0:22:57]; en OpenAI se lee todo [SS26 05 @0:39:33] | Steinberger: revisión como gestión de riesgo, no leer todo [SS26 05 @0:30:53] | Depende del riesgo: lo crítico se lee |
| Intensidad o diversión | Junestrand: ventas de 1 a 10 a. m., "blood smoke" [SS26 01 @0:11:40] [SS26 01 @0:23:43] | Steinberger: burnout en su primera empresa, OpenClaw "almost broke me"; "fun is velocity" [SS26 05 @0:10:14] [SS26 05 @0:22:49] | |
| ¿Aprender lo que la IA ya sabe? | Collison: el conocimiento en tu "caché L1" es mucho más rápido que preguntar [SS26 09 @0:02:34] | Garry Tan: tu cabeza tiene 7±2 cosas; mové tu vida a una biblioteca que lea el agente [SS26 07 @0:12:52] | No se excluyen: conocimiento de base en la cabeza, memoria episódica en la biblioteca |
| Lanzar rápido | Regla de YC "launch early" (la recuerda Harj) [SS26 09 @0:13:32]; Field "launch as soon as you can" [AISS 17 @0:08:40] | Dolgov: "move fast and ship safely", 15 años de producto [SS26 08 @0:03:15]; Collison: dos años con usuarios reales en producción [SS26 09 @0:16:02] | Si el costo de fallar es alto, tardá más, pero con usuarios reales desde el principio |
| Bitter lesson | Sutton: métodos generales con cómputo y datos ganan [SS26 08 @0:30:20] | Dolgov: estructura que canaliza la escala gana [SS26 08 @0:30:57]; Garry Tan: modelos mejores hacen más valioso tu contexto [SS26 07 @0:33:50] | Lo que rodea al modelo importa |
| ¿Te pisa el laboratorio? | Srinivas: te van a copiar [AISS 09 @0:30:26] | Collison: miedo "overstated" [SS26 09 @0:23:18]; Dean: elegí lo que el modelo hace 0-1% [SS26 10 @0:28:26] | |
| ¿Se concentra la riqueza? | Fischer: "capital begets capital" [AISS 15 @0:33:42]; Garry Tan: brecha creciente si no se reparte [SS26 07 @0:35:54] | Collison: miles de ganadores, prosperidad repartida [SS26 09 @0:30:04] | |
| ¿Más scaffolding o menos? | Wang: la "alpha" está en skills, markdown, cron y /goal [SS26 11 @0:28:47]; Garry Tan: "fat skills thin harness" [SS26 07 @0:16:44]; Huang: los markdown son inteligencia acumulada [SS26 15 @0:21:33] | Cherny: con Opus 5 no hace falta /goal; borrá CLAUDE.md, skills y hooks cada seis meses [SS26 14 @0:01:21] [SS26 14 @0:06:26] | No chocan del todo: guardá contexto propio, pero podá las instrucciones que el modelo ya no necesita, midiendo |
| ¿Seguir aprendiendo a programar? | Ng: todos deberían [AISS 04 @0:15:26]; Cherny: el código está resuelto solo para cierto tipo; aprendé CS aplicada [SS26 14 @0:30:42]; Scholl: hacen falta más ingenieros [SS26 12 @0:41:25] | Huang: programar a mano "is obviously going to get automated away" [SS26 15 @0:41:01]; Wang ironiza "nobody here writes code anymore" [SS26 11 @0:24:56] | Coinciden en pensamiento sistémico |
| ¿Qué es lo escaso? | Wang: visión y ambición [SS26 11 @0:21:46]; Dean: gusto [SS26 10 @0:33:47]; Hodak: juicio [SS26 06 @0:20:33] | Huang: controlabilidad [SS26 15 @0:22:52]; Cherny: verificación [SS26 14 @0:19:47]; Altman: cómputo [SS26 13 @0:33:56]; Steinberger: atención [SS26 05 @0:32:48] | Todas son ciertas en su capa |
| ¿Mudarse a San Francisco? | Altman: probablemente siga siendo buen consejo [SS26 13 @0:16:48] | Scholl: basta un ecosistema (él se fue a Denver) [SS26 12 @0:45:48] | |
| Experiencia | Scholl: "the moment you become an expert, what you're steeped in is the past", pero llamá a quien ya lo hizo [SS26 12 @0:43:18]; Altman: la fluidez con herramientas le gana a la experiencia [SS26 13 @0:10:56] | Huang: "stay in school", ciencias duras [SS26 15 @0:43:37] | |
| Seguridad | Altman: estar "a little bit scared" [SS26 13 @0:24:15] | Cherny: no logran demostrar inyección [SS26 14 @0:03:16]; Huang y Scholl, anti-"doomerism" [SS26 12 @0:40:48] [SS26 15 @0:31:55] | |

---

## Qué dice cada orador (lo propio, en una línea)

- **Andrej Karpathy** (AISS 01): software 3.0; LLM como sistema operativo de los 60; autonomía parcial con slider;
  "decade of agents"; construir para agentes.
- **Elon Musk** (AISS 02): primeros principios; ser útil ("Don't aspire to glory, aspire to work" [AISS 02 @0:22:48]);
  superinteligencia ya; humanoides; IA veraz.
- **Sam Altman** (AISS 03): mejor momento de la historia; no hagas el asistente central; ventana antes del foso; hire
  for slope; just in time software; energía como límite.
- **Andrew Ng** (AISS 04): velocidad; ideas concretas; prototipos 10x; cuello de botella en producto; todos programan;
  contra el hype.
- **Jake Heller** (AISS 05): asistir, reemplazar o lo impensable; TAM de salarios; evals; vender como servicio.
- **Fei-Fei Li** (AISS 06): inteligencia espacial; modelos de mundo; "intellectual fearlessness".
- **Satya Nadella** (AISS 07): el modelo como SQL; memoria, herramientas, permisos; gestión del cambio; permiso social.
- **François Chollet** (AISS 08): escalar no da inteligencia fluida; ARC; búsqueda de programas.
- **Aravind Srinivas** (AISS 09): velocidad como único foso; navegador como capa de agentes; dilema del innovador.
- **Amjad Masad** (AISS 10): hábitat del agente; el software de aplicaciones vale cero; generalistas; individuo soberano.
- **Chelsea Finn** (AISS 11): modelo general para robots; datos curados; escala necesaria pero no suficiente.
- **Aaron Levie** (AISS 12): sustantivos y verbos; precio por trabajo hecho; core vs context; ventana de 2-3 años.
- **Jared Kaplan** (AISS 13): leyes de escala; horizonte de tareas; "build things that don't quite work yet".
- **Michael Truell** (AISS 14): consistencia con tu tesis; lanzar crudo; camino medio de décadas.
- **Jordan Fischer** (AISS 15): preguntas antes de una startup de IA; AGI en 2-3 años; confianza y auditorías.
- **John Jumper** (AISS 16): datos, cómputo e investigación; benchmarks ciegos; la IA amplifica al científico.
- **Dylan Field** (AISS 17): diseño como diferenciador; era MS-DOS de la IA; lanzar y cobrar antes.
- **Max Junestrand** (SS26 01, Legora): espacio antes que problema; no fine-tuning, evals y enrutamiento; frenar ventas
  para arreglar el producto; contratar por pendiente; agentes proactivos.
- **Michael Kratsios** (SS26 02, Casa Blanca): sin líneas rojas rígidas; open source; preemption; ciber como riesgo del
  día; ciencia autónoma y cuántica.
- **Susan Kare** (SS26 03): diseño de iconos; no habla de IA (ver `04-usuarios-y-producto.md`).
- **Chelsea Finn** (SS26 04): la robótica ya está en la era GPT; confiabilidad por experiencia; π0.7 generalista.
- **Peter Steinberger** (SS26 05, OpenClaw): "fun is velocity"; revisión de código como riesgo; dependencias; marca
  personal.
- **Max Hodak** (SS26 06, Science): la infraestructura decide la velocidad; IA nativa en la operación; no delegar el
  juicio; "average is not good enough".
- **Garry Tan** (SS26 07, presidente de YC, visión personal): personal AGI; contexto propio; skills en markdown; "own
  your skills".
- **Dmitri Dolgov** (SS26 08, Waymo): la demo es 1%; escalera de nueves; evaluación como foso.
- **Patrick Collison** (SS26 09, Stripe): problemas concretos; descorrelacionarse; miedo a los laboratorios exagerado;
  miles de ganadores.
- **Jeff Dean** (SS26 10, Google): regla del 0-1%; contexto y skills; especificaciones; el gusto como habilidad escasa;
  ciencia automatizada.
- **Alexandr Wang** (SS26 11, Meta): convicción contra el rebaño; "Goliath versus Goliath"; loops agénticos de negocio;
  lo escaso es visión y ambición.
- **Blake Scholl** (SS26 12, Boom): hardware como software; regulación construyendo; "why now" no hace falta.
- **Sam Altman** (SS26 13): nunca hubo mejor momento; convicción contraria; contra el sarcasmo; concentración de poder.
- **Boris Cherny** (SS26 14, Claude Code): borrar el prompt; verificación; overhang; workflows, loops y routines.
- **Jensen Huang** (SS26 15, NVIDIA): perspectiva única; "how hard can it be?"; controlabilidad; la IA elimina tareas,
  no empleos; IA física.

---

## Para el agente

Cómo usar este capítulo: casi todo es visión de oradores. Cuando el fundador pregunte "¿qué diría YC?", priorizá lo marcado
como consejo de YC (SS 03, SS 14, SS 15, SS 16, SS 24, SS 29) y presentá lo demás como "según Karpathy / Altman / Dean".
Cuando dos oradores chocan, mostrá los dos (tabla de contradicciones) y decí la fecha (2025 o 2026). Lo de modelos y
herramientas envejece en meses: avisalo.

### Checklist: ¿esta idea de IA es buena?
- [ ] **Se paga hoy a personas** por ese trabajo y sabés cuánto (salarios o proveedor tercerizado), no "AI is cool, what
  could I apply AI to?" (Heller [AISS 05 @0:03:47]; YC [SS 02 @0:01:39]).
- [ ] Se puede decir si es **asistir, reemplazar o lo antes impensable** (Heller [AISS 05 @0:09:19]).
- [ ] Es **concreta**: un ingeniero podría construirla con lo que dice (Ng [AISS 04 @0:04:28]).
- [ ] Está **en el borde** de lo que hacen los modelos: hoy apenas funciona y mejora con cada modelo (YC [SS 03 @0:06:04];
  Kaplan [AISS 13 @0:13:24]). Prueba de Dean: ¿el modelo general hoy acierta 0-1% (bien) o ~20% (mal, lo va a absorber)?
  ¿Lo hará bien en 6-12 meses o no en 2-3 años? [SS26 10 @0:27:45] [SS26 10 @0:28:26]
- [ ] Pasa el **"Sam Altman test"**: cuando el modelo mejore, el producto se fortalece y no se commoditiza (YC [SS 16 @0:03:25]).
- [ ] **No es el asistente central** de un laboratorio ni "CRM with AI" (Altman [AISS 03 @0:14:57]; Levie [AISS 12 @0:17:51]).
- [ ] **El mercado lo transforma la IA** de verdad ("if your market is not truly transformed by AI, don't touch it")
  [AISS 12 @0:31:56]; hay un sustantivo o verbo sin incumbente moderno [AISS 12 @0:18:24].
- [ ] Hay **fuente de ventaja**: datos que el modelo general no ve, modelo de nicho, contexto propio, integración profunda,
  confianza o licencias, o un loop de datos del producto (Dean [SS26 10 @0:29:06]; YC [SS 03 @0:07:09]; Nadella
  [AISS 07 @0:06:13]). Si la única ventaja es "capacidad técnica", es "a rat race" (Fischer [AISS 15 @0:21:11]).
- [ ] Alguien del equipo **sabe exactamente cómo trabaja el profesional** o tiene plan para aprenderlo pegado al cliente
  (Heller [AISS 05 @0:10:25]; Junestrand [SS26 01 @0:28:12]).
- [ ] Sabe **cuántos nueves** necesita (demo, copiloto o autónomo) y si la tecnología elegida llega (Dolgov
  [SS26 08 @0:11:48] [SS26 08 @0:14:43]).
- [ ] Es la **versión más ambiciosa** razonable, y el fundador querría trabajar en eso 10 años ("what if you succeed")
  (YC [SS 03 @0:08:15]; Collison [SS26 09 @0:20:00]).

### Checklist: ¿el producto de IA está bien construido?
- [ ] **Evals** antes que tecnología: definición de "bueno" para la tarea y cada paso, gradable (true/false o 0-7), set de
  reserva, ~100 casos por prompt antes de beta, cada queja se vuelve un test (Heller [AISS 05 @0:17:01] a
  [AISS 05 @0:21:52]; Dolgov [SS26 08 @0:43:08]).
- [ ] **Workflow o agente** decidido con criterio: pasos fijos = Python común; lo determinístico en código, no en prompts
  (Heller [AISS 05 @0:13:40]; Garry Tan, latente contra determinista [SS26 07 @0:18:39]).
- [ ] **Verificación**: el modelo tiene cómo comprobar su trabajo (tests, screenshots, suite) (Cherny [SS26 14 @0:19:47]).
- [ ] **Humano en el ciclo** donde importa: GUI para auditar rápido, cambios chicos, slider de autonomía (Karpathy
  [AISS 01 @0:19:55] [AISS 01 @0:22:57]).
- [ ] **No atado a un proveedor**: se puede cambiar de modelo corriendo las evals (Ng [AISS 04 @0:36:43]; Steinberger
  [SS26 05 @0:18:42]; Junestrand [SS26 01 @0:34:02]).
- [ ] **Prompt podado**: nada que el modelo no necesite; revisado con cada modelo nuevo (Cherny [SS26 14 @0:06:26]).
- [ ] **Seguridad explícita**: qué garantiza y qué no; no confiada a una línea del prompt (Steinberger [SS26 05 @0:34:07]).
- [ ] **Legible para agentes** si es infraestructura o dev tool: llms.txt, docs en markdown, comandos en vez de "click",
  MCP (Karpathy [AISS 01 @0:34:07] a [AISS 01 @0:36:24]).

### Checklist: ¿el precio y la venta de IA tienen sentido?
- [ ] Precio por **valor** o por trabajo hecho (unidad, resultado), no asientos de US$ 20 (Heller [AISS 05 @0:26:09];
  Levie [AISS 12 @0:20:35]; YC [SS 16 @0:07:15]).
- [ ] Ubicado **entre el costo humano y el propio** (ej.: humano US$ 5-10, agente US$ 0,10, precio US$ 2), con parte
  recurrente y sin ser "offensive" (Levie [AISS 12 @0:21:07] [AISS 12 @0:25:27]).
- [ ] **Margen** defendido con software sobre los tokens (80-90%); créditos gratis contados en el COGS (Levie
  [AISS 12 @0:22:44]; YC [SS 24 @0:06:00] [SS 29 @0:18:01]).
- [ ] **Pilotos** pocos, que conviertan; no contados como ARR (Heller [AISS 05 @0:28:20]; YC [SS 16 @0:06:43]).
- [ ] Plan de **adopción** después de la firma (forward deployed engineers, entrenamiento) (Heller [AISS 05 @0:28:53];
  Nadella [AISS 07 @0:13:03]).

### Checklist: ¿la empresa trabaja como nativa de IA? (consejo de YC, SS 15, más visión de Garry Tan)
- [ ] Reuniones grabadas, pocas DMs, todo deja artefacto; un agente puede leer Linear, Slack, feedback y ventas
  [SS 15 @0:02:20] [SS 15 @0:02:52].
- [ ] Specs y tests escritos por humanos; agentes implementan hasta pasar [SS 15 @0:04:32].
- [ ] El fundador usa los agentes él mismo y no delega la estrategia de IA [SS 15 @0:07:50] [SS 15 @0:08:56].
- [ ] Factura de API "incómodamente alta" antes que más gente [SS 15 @0:08:23].
- [ ] Tareas repetidas convertidas en skills o routines; nada se pide dos veces (Garry Tan [SS26 07 @0:27:08]; Cherny
  [SS26 14 @0:27:34]).
- [ ] Contexto propio (biblioteca de markdown) en un repo que controla el fundador [SS26 07 @0:25:09] [SS26 07 @0:32:35].

### Señales
**Bien hecho**
- Demo que se mide en nueves y evals, no en vistas ("count your nines before you count your demo views") [SS26 08 @0:14:43].
- Uso sostenido después del "wow" inicial (Perplexity) [AISS 09 @0:09:13]; gente que se enoja cuando no le das acceso
  (OpenClaw) [SS26 05 @0:04:40]; usuarios que mandan feedback largo ("product market pull") [AISS 17 @0:11:24].
- Cada modelo nuevo hace el producto mejor sin reescribirlo [SS 16 @0:03:25] [AISS 13 @0:13:56].
- Ingresos que crecen más rápido que la gente (Emergent, Legora) [SS26 07 @0:22:31] [SS 16 @0:06:11].

**Mal hecho o no hecho**
- "Funciona en la demo" al 60-70% sin evals [AISS 05 @0:15:20].
- El modelo general ya hace ~20% de la tarea [SS26 10 @0:28:26].
- El producto es un chatbot pegado ("pixie dust") [AISS 15 @0:08:43]; o un clon de ChatGPT [AISS 03 @0:13:52].
- ARR hecho de pilotos [AISS 05 @0:28:20]; humanos tapando huecos del producto; ingresos que crecen igual que la gente
  [SS 16 @0:03:25] [SS 16 @0:06:11].
- Todo optimizado para un solo modelo o proveedor [SS26 05 @0:18:42].
- Diffs enormes que nadie revisa en partes críticas; cero tests [AISS 01 @0:22:57] [SS 14 @0:07:06].
- Hojas de ruta de 9 a 24 meses en un mercado que cambia cada 3 [AISS 17 @0:09:46] [AISS 04 @0:01:04].

### Qué hacer después (acciones concretas de los videos)
- **Si no sabés cómo trabaja el cliente**: "go undercover" una semana en ese trabajo, o almuerzos pagados con
  profesionales (Legora) y pegarte a un cliente grande [AISS 07 @0:13:36] [SS26 01 @0:05:16].
- **Si la idea es vaga**: escribí la versión que un ingeniero pueda construir y armá un prototipo en días; probala con 3
  amigos y 3-10 desconocidos en un café (Ng) [AISS 04 @0:05:02] [AISS 04 @0:19:15].
- **Si no sabés si el modelo ya lo hace**: dale al modelo más nuevo la tarea real, un poco más difícil de lo que creés,
  con forma de verificar, y mirá dónde se traba (Cherny; Dean) [SS26 14 @0:14:55] [SS26 10 @0:27:45].
- **Si no tenés evals**: una docena de casos reales esta semana, gradables, con set de reserva; meta 100 por prompt
  (Heller) [AISS 05 @0:18:39].
- **Si dependés de un modelo**: armá la capa para cambiar de proveedor y corré las evals contra 2-3 modelos (Ng;
  Junestrand) [AISS 04 @0:37:16] [SS26 01 @0:34:02].
- **Si querés tu propia IA de trabajo (Garry Tan)**: esta noche un harness; este fin de semana la biblioteca; la tarea
  semanal que más odiás como primera skill; volverla recurrente; "skillify" todo [SS26 07 @0:24:28] a [SS26 07 @0:27:52].
- **Si vas a poner precio**: calculá el costo humano actual y tu costo por unidad; poné el precio en el medio con parte
  recurrente; preguntale al cliente "how would you rather pay for this?" [AISS 12 @0:21:07] [AISS 05 @0:26:09].
- **Si el producto toca el mundo físico o algo crítico**: definí cuántos nueves necesitás y construí la evaluación antes
  que la tecnología; involucrá al regulador temprano si no hay enemigo atrincherado [SS26 08 @0:11:48]
  [SS26 08 @0:43:08] [SS26 12 @0:29:24].
- **Si te paraliza el miedo a que te copie un laboratorio**: elegí por qué querés ser conocido, construí lo que el modelo
  hace 0-1%, y "just build it" [AISS 09 @0:34:48] [SS26 10 @0:28:26] [AISS 05 @0:39:10].

### Qué diría cada uno (atajos para "¿qué diría X?")
- **Karpathy**: "¿dónde está tu slider de autonomía y cómo audita el humano rápido?"
- **Altman**: "no hagas lo que hacen todos ni nuestro asistente; tenés una ventana antes de necesitar foso; nunca hubo
  mejor momento".
- **Ng**: "¿es concreta? Prototipá en días; tu cuello de botella es saber qué construir".
- **Heller**: "¿qué trabajo pagado reemplazás o asistís, y dónde están tus evals?"
- **Levie**: "¿qué sustantivo o verbo sin incumbente resolvés, y cuánto software hay sobre tus tokens?"
- **Nadella**: "¿cambiaste el flujo de trabajo o solo automatizaste el viejo? ¿qué permisos tiene tu agente?"
- **Dean**: "¿el modelo general hace esto 0-1% o 20%?"
- **Cherny**: "borrá el prompt, dale una tarea difícil y forma de verificar".
- **Garry Tan**: "¿es tuyo el contexto? Skillify todo".
- **Dolgov**: "¿cuántos nueves necesitás? La demo es el 1%".
- **Collison**: "¿qué problema concreto y fácil de explicar? El miedo a los laboratorios está exagerado".
- **Wang**: "¿qué creés que nadie más cree? Lo escaso es la visión".
- **Huang**: "¿cuál es tu perspectiva única? How hard can it be?"

---

## Huecos

> **Hueco:** casi nada de esto es método de YC. Los únicos videos de socios de YC sobre IA son SS 03 (cualidades de una
> idea), SS 14 (vibe coding), SS 15 (empresa nativa de IA), SS 16 (servicios nativos de IA) y SS 17 (dev tools). Todo lo
> de AISS y SS26 es visión de invitados o de Garry Tan como persona.

> **Hueco:** no hay diapositivas. Faltan los gráficos de Karpathy (Model Atlas, mapa de GitHub), las leyes de escala y la
> tendencia de METR de Kaplan, los gráficos de ARC de Chollet, las ablaciones de Finn (2025 y 2026, sin números), los
> datos de seguridad de Waymo y las preguntas en pantalla de Fischer.

> **Hueco:** los videos no explican: qué es el incidente "Hugging Face" de SS26 13 ni el "momento Mythos" de SS26 02; la
> "lethal trifecta" (SS26 14); la quinta capa de la "five layer cake" de Huang; cómo funciona el resolver de GBrain o la
> promoción a memoria caliente/fría (SS26 07); cómo arma Waymo el crítico; cómo hace PI la memoria de video eficiente;
> el contenido del "Leya Product Manifesto"; *7 Powers* (Altman solo lo nombra) ni la "charla de defensibilidad" que
> Altman propone dar y no da.

> **Hueco:** Fischer (AISS 15) deja abiertas a propósito casi todas sus 19 preguntas: no hay respuesta en los videos a
> si gana el retrofit o lo nativo, si se commoditiza el software, ni cómo deben ser la UI o la neutralidad de tokens.

> **Hueco:** identificación dudosa de entrevistadores: AISS 09 (socio de YC sin nombre), AISS 14 y SS26 10 y 14
> (probablemente Diana Hu, sin confirmar), AISS 17 (socio de YC sin nombre), SS 16 (orador de YC sin nombre). Los
> atribuí como "socio de YC".

> **Hueco:** cifras inconsistentes o dudosas en las transcripciones: Altman dice que tres meses de trabajo de YC hoy se
> hacen en "seven minutes", "17 seconds" o "17 minutes" [SS26 13 @0:01:10] [SS26 13 @0:07:29] [SS26 13 @0:29:54]; Waymo
> "previene una lesión grave every eight days" (parece baja) [SS26 08 @0:47:09]; Levie da la ventana como "two or three
> years" y "four years" [AISS 12 @0:32:30] [AISS 12 @0:33:06]; los "90.000x" de inferencia de Garry Tan
> [SS26 13 @0:33:56]; la productividad "10 times that in the middle of the range" de Garry Tan [SS26 07 @0:08:53]; el
> 10% semanal de Cursor y el 80% del batch los da la entrevistadora, no Truell [AISS 14 @0:19:39].

> **Hueco:** nombres de modelos y productos de 2026 (Opus 5, Fable, Sonnet 5, Muse Spark, Alpamayo, dynamic workflows,
> routines, Claude Tag) vienen de whisper y no se verificaron fuera de los videos.

> **Hueco:** ningún video da números de retención, churn o NDR propios de productos de IA, ni un benchmark de margen
> bruto de empresas de IA más allá de los rangos de Levie (2x tokens contra 80-90%) y SS 16 (50%+ en servicios).
