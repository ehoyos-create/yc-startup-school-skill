# Equipo, cultura y gestión

> Al principio contratá lo menos posible, nunca a alguien mediocre, y tratá cada contratación como una venta que hace
> el fundador (con proceso, volumen, velocidad y referencias que aprietan). La cultura son los valores y las acciones
> que se sostienen cuando ya no estás en cada decisión: escribila antes de contratar y repetila siempre. Hacia las ~25
> personas tu trabajo pasa de construir el producto a construir la compañía: estructura simple, delegación real,
> feedback, bandas, equity generosa, ritmos y despedir rápido y con dignidad.

Fuentes base: SS 33 (contratar ingenieros y AEs), SS 30 (KPIs, solo lo de priorizar y operar); HTSS 02 (equipo y
ejecución, Sam Altman), HTSS 07 (Kevin Hale, solo cultura de Wufoo), HTSS 09 (frase de Ron Conway y Marc Andreessen),
HTSS 10 (cultura, Brian Chesky y Alfred Lin), HTSS 11 (contratar y cultura, Collison y Silbermann), HTSS 13 (Reid
Hoffman), HTSS 14 (operar, Keith Rabois), HTSS 15 (gestionar, Ben Horowitz), HTSS 18 (empleados y despidos, Nathoo y
Levy), HTSS 19 (etapa posterior, Sam Altman). Además: SS 09, SS 15, SS 16, SS 17, SS 18, SS 24; AISS 03, 04, 05, 06,
07, 10, 12, 14, 17; SS26 01, 03, 06, 07, 11, 12, 15.

Cruces: cofundadores, reparto de equity entre fundadores y vesting de fundadores están en
`02-fundadores-y-cofundadores.md`; KPIs y metas en `07-metricas-retencion-y-crecimiento.md`; ventas y vendedores en
`06-ventas-y-pricing.md`; opciones, 409A y SAFE en `08-fondeo-y-yc.md`; IA y organización en `10-ia-y-el-futuro.md`.
Acá se toca lo que sirve para armar, dirigir y hacer crecer el equipo.

Época: HTSS es de 2014 (Silicon Valley, ley laboral de EE. UU. de entonces); SS 33 es de ~2025 (Juicebox, Work at a
Startup); AISS es de 2025; SS26 es de 2026. Lo que choca por la IA (tamaño de equipo, ingresos por persona, cómo
evaluar ingenieros) se marca en cada lugar.

---

## Principios

### A. Cuándo contratar (y cuándo no)

1. Al principio, contratá solo por necesidad desesperada: "only hire when you have a desperate need to" (contratá
   solo cuando lo necesites desesperadamente), y "You should be proud of how few employees you can have" (deberías
   estar orgulloso de lo pocos empleados que tenés) (Sam Altman, YC) [HTSS 02 @0:07:35] [HTSS 02 @0:08:07]. Más tarde
   hay que aprender a contratar rápido y escalar [HTSS 02 @0:08:07].
2. Medir el éxito por número de empleados es un error (Altman) [HTSS 02 @0:07:03]. Rabois lo convierte en métrica:
   (cosas hechas con éxito) / (personas en el equipo), contra el "empire building" [HTSS 14 @0:41:28].
3. Más gente no es más velocidad: "most people, most great people even, are actually ammunition. But what you need in
   your company are barrels" (la mayoría de la gente, incluso la muy buena, es munición; lo que necesitás son
   barriles) (Keith Rabois) [HTSS 14 @0:14:29] [HTSS 14 @0:15:03]. "No necesitás más ingenieros hasta tener más
   barriles" [HTSS 14 @0:40:55].
4. En la etapa de MVP, contratar desconocidos te frena (más de un mes para encontrar a alguien bueno, entorno caótico)
   y te hace perder insights del producto si no lo construyen los fundadores; se puede contratar algo después (Diana
   Hu, YC) [SS 09 @0:09:34]. El escalado de ingeniería, la cultura de ingeniería y las contrataciones van después del
   PMF ("big engineering pants") [SS 09 @0:25:40] [SS 09 @0:26:14].
5. En dev tools, no contrates hasta convencerte de que es la idea correcta (Nicolas Dessaigne, YC) [SS 17 @0:15:24].
6. No contrates un equipo de ventas hasta saber vender vos: "You should not hire a sales team until you know how to do
   sales yourself" [SS 18 @0:03:47]. "If you aren't able to sell your product yourself at first chances are you're not
   going to be able to hire somebody else to do it for you" (Pete Koomen, YC) [SS 23 @0:01:07]. Ver capítulo 06.
7. Visión contraria (después del arranque): contratar demasiado poco también cuesta. Michael Truell (Cursor): con
   cuatro fundadores muy buenos ingenieros llegaron lejos sin contratar, pero "we hired a lot less than we probably
   should have" [AISS 14 @0:23:29] [AISS 14 @0:24:01]. Dylan Field (Figma): "I should have scaled the team faster"
   [AISS 17 @0:09:14]. Son visiones de oradores (no método de YC) y hablan de la etapa con producto y capital.
8. La cultura no paga en el corto plazo: te obliga a contratar lento y a decidir con deliberación; si quisieras
   vender la compañía en un año, el consejo sería ignorarla y contratar rápido (Brian Chesky) [HTSS 10 @0:27:52]
   [HTSS 10 @0:28:25].
9. No contrates "para los próximos tres features": cada contratación es ADN [HTSS 10 @0:18:32].
10. Con IA (visión de oradores 2025-2026): "Maximizing token usage, not headcount" (maximizar el uso de tokens, no la
    cantidad de empleados) y "you should be willing to run an uncomfortably high API bill" (Diana Hu) [SS 15 @0:08:23];
    empresas con ingresos por persona inéditos, como Emergent con 15 personas al pasar USD 15 M anualizados (Garry Tan)
    [SS26 07 @0:22:31]. En contra o en matiz: Blake Scholl dice que Boom necesita más ingenieros de software, no menos
    [SS26 12 @0:41:25], y Jensen Huang que la IA no destruye empleos [SS26 15 @0:31:55].

### B. La vara: a quién contratar

1. "If you compromise and hire someone mediocre, you will always regret it" (si transás y contratás a alguien
   mediocre, siempre te vas a arrepentir) (Altman) [HTSS 02 @0:11:54]. Un solo empleado mediocre entre los primeros 5
   a menudo mata la startup [HTSS 02 @0:11:54] [HTSS 02 @0:12:26].
2. La pregunta para cada contratación temprana: "Will I bet the future of this company on this single hire?"
   (¿apostaría el futuro de la empresa a esta sola contratación?) [HTSS 02 @0:12:26].
3. Tres preguntas de Altman: ¿es inteligente?, ¿hace que las cosas pasen?, ¿quiero pasar mucho tiempo con esta
   persona? Si las tres dan sí, "I almost never regret the hire" [HTSS 02 @0:14:36] [HTSS 02 @0:15:07].
4. "Hire for slope, not y intercept" (contratá por la pendiente, no por la ordenada al origen), frase que Altman
   atribuye a "PB" (Paul Buchheit): mirá lo que construyeron, su velocidad y cómo resuelven problemas, no el CV
   [AISS 03 @0:31:18] [AISS 03 @0:31:51]. Junestrand llegó a lo mismo por error: "looking for fancy logos on resumes
   or what we like to call Y-intercepts" fue un patrón que tuvieron que desaprender, porque alguien con alto punto de
   partida y poca pendiente "is going to have a really hard time working in a company that is scaling exponentially"
   [SS26 01 @0:17:50].
5. La experiencia importa para quien va a dirigir una organización grande; para la mayoría de las primeras
   contrataciones, no: ir por aptitud y creencia en la misión (Altman) [HTSS 02 @0:14:03] [HTSS 02 @0:14:36]. No
   empieces con un ejecutivo senior eminente como primera contratación: "young scrappy but clearly… get stuff done"
   [AISS 03 @0:30:45] [AISS 03 @0:31:18]. Pero al escalar, el miedo a contratar senior es uno de los cuatro errores
   del fundador que se vuelve gerente (ver Frameworks, F6) [HTSS 19 @0:03:52].
6. Pensá como inversor de valor: buscá capital humano subvaluado; no persigas a tus amigos brillantes de Facebook y
   Google, ya están "descubiertos" (Patrick Collison, probable) [HTSS 11 @0:09:55]. Podés relajar una restricción:
   que sean talentosos, o que sea evidente que lo son; ellos relajaron lo segundo (John Collison) [HTSS 11 @0:09:19].
   Diana Hu: buscar "the misfits" que Google pasó por alto [SS 09 @0:10:08]. Paffenholz: los no obvios en papel
   (contribuidores de GitHub, perfiles de Twitter, sin universidad top o empresa top) [SS 33 @0:31:11]
   [SS 33 @0:31:43].
7. Contratá a quien querés trabajar todos los días: Zuckerberg (citado por Altman) contrata gente con la que (A)
   pasaría tiempo socialmente y (B) a la que se sentiría cómodo reportando si se invirtieran los roles
   [HTSS 02 @0:17:47]. "Animal test" de Paul Graham: tenés que poder describir a cada empleado como "an animal at what
   they do" (una bestia en lo que hace) [HTSS 02 @0:17:16].
8. Diversidad de orígenes, no de valores ni de visión: "You want diversity of ... background age you don't want
   diversity of values" (Chesky) [HTSS 10 @0:18:32]; "diversity of backgrounds but you don't want diversity of vision"
   (Altman) [HTSS 19 @0:37:04]. Altman pide diversidad temprana: el error típico son los primeros 15 o 20 ingenieros
   todos hombres [HTSS 19 @0:14:45].
9. Desconfiá de quien busca certezas: si alguien cree que tenés una bola de cristal y que el éxito es seguro, no lo
   contrates: "didn't pass a basic intelligence test about uncertainty" (Ben Silbermann) [HTSS 11 @0:45:44]. El que
   duda entre McKinsey y tu startup probablemente no funcione (Altman) [HTSS 02 @0:16:44]. Quien busca "la certeza de
   Google más las ventajas de una startup" no sirve [HTSS 11 @0:46:49]. Quien pone su mejor deseo en siete empresas
   sin relación busca una experiencia, no un objetivo [HTSS 11 @0:47:22].
10. Contratar usuarios apasionados del producto es una ventaja injusta en la etapa de "patito feo" (John Collison)
    [HTSS 11 @0:49:31] [HTSS 11 @0:50:04]; pero la regla "solo contratá usuarios diarios" sirve para una API y no
    necesariamente para Pinterest (Silbermann) [HTSS 11 @0:48:26].
11. "The one thing I've never been able to teach somebody else is to care when they just didn't care" (lo único que
    nunca pude enseñar es a que a alguien le importe) y "Knowledge is changeable, passion is not" (Blake Scholl, Boom)
    [SS26 12 @0:31:31] [SS26 12 @0:32:45].
12. Armá un equipo tan talentoso que te incomode un poco (Chesky) [HTSS 10 @0:13:38].

### C. Contratar es vender, y lo hace el fundador

1. Las primeras contrataciones definen cultura, velocidad y futuro: "they will be shaping how you run your business"
   (David Paffenholz, Juicebox) [SS 33 @0:00:34]. "No batch of 10 people will have as great an influence" (ningún
   otro grupo de 10 tendrá tanta influencia) (John Collison, probable) [HTSS 11 @0:08:12]. Cada uno de los primeros 10
   trae otros 10: contratar 10 es "actually kind of hiring 100 people" [HTSS 11 @0:04:25].
2. Dale a contratar la misma atención que a tu primer proceso outbound de ventas [SS 33 @0:08:39]. "The number one
   thing we see founders do wrong is in the first call, they're just interviewing the candidate rather than selling
   the company … you should flip that order" (el error número uno: en la primera llamada entrevistan en vez de vender
   la empresa; hay que invertir el orden) [SS 33 @0:24:16].
3. "Your main advantage is speed throughout the whole process" (tu ventaja principal es la velocidad en todo el
   proceso): 7 días, 10 días, máximo 2 semanas [SS 33 @0:24:49].
4. Todo el outreach sale de los fundadores: "ideally all outreach always comes from the founders"; cuanto más senior
   quien escribe, mejor respuesta [SS 33 @0:35:29]. Harj Taggar (YC): "the recruiters can never sell the company as
   effectively as the founders" [SS 33 @0:27:29].
5. Contratar no es "ordering off the dollar menu" en LinkedIn; son conversaciones largas con conocidos y amigos de
   amigos (John Collison) [HTSS 11 @0:08:12] [HTSS 11 @0:08:47]. Las grandes tech se construyeron con referidos
   personales para al menos los primeros 100 empleados (Altman) [HTSS 02 @0:13:30].
6. No blanquees los riesgos: contá por qué es una oportunidad increíble y "lay out in gory detail why it's going to be
   hard" (detallá con crudeza por qué será difícil); los correctos se autoseleccionan (Silbermann) [HTSS 11 @0:17:58]
   [HTSS 11 @0:18:29].
7. Tené un buen elevator pitch no solo para inversores: todo el que conocés puede ser un recluta dentro de 6 a 12
   meses (John Collison) [HTSS 11 @0:13:41]. Contratar "is a repeated game" (es un juego repetido): el que hoy dice
   que no puede entrar en 6 meses; los fundadores elite reclutan siempre, desde el día uno (Paffenholz y Harj)
   [SS 33 @0:39:47] [SS 33 @0:40:19].
8. No elijas algo demasiado nicho: cuesta contratar; "build a rocket that goes to Mars" suena imposible pero atrae
   gente (Patrick Collison, probable) [HTSS 11 @0:14:13] [HTSS 11 @0:14:46].
9. "You need to become a really good storyteller in order to drive interest and to get people on your team" (Max
   Junestrand, Legora) [SS26 01 @0:12:17]; la historia se vende a vos mismo, a los empleados (competir con los
   laboratorios por talento), a los inversores y a los clientes [SS26 01 @0:48:15] [SS26 01 @0:48:59].
10. Reclutar es lo difícil: "Raising venture capital is the easiest thing a startup founder is ever going to do",
    comparado con reclutar al ingeniero número 20 o vender a enterprise (Marc Andreessen) [HTSS 09 @0:10:15].
11. En modo contratación es tu prioridad número 1: dedicás 0% o 25% del tiempo; los libros dicen 50% pero quienes lo
    dicen rara vez llegan al 10% (Altman) [HTSS 02 @0:10:18] [HTSS 02 @0:11:22]. Rabois coincide en ~25% si reclutar
    es la prioridad 1, y advierte que casi nunca coincide con el calendario real [HTSS 14 @0:43:34] [HTSS 14 @0:44:05].
12. Decidir rápido: "Procrastination is the devil in startups … If it's decisions to hire, decisions to fire, you got
    to make those quickly" (Ron Conway) [HTSS 09 @0:05:04].

### D. Cultura

1. "Everything in a startup gets modeled after the founders. Whatever the founders do becomes the culture" (todo en
   una startup se modela según los fundadores; lo que hacen se vuelve la cultura) (Altman) [HTSS 02 @0:29:40]. Los
   fundadores son padres y la compañía el hijo: si los padres son disfuncionales, el hijo también (Chesky)
   [HTSS 10 @0:14:12]. "If you take your foot off the gas, so will they" (si sacás el pie del acelerador, ellos
   también) (Dustin Moskovitz) [HTSS 01 @0:34:42].
2. Escribí los valores antes de contratar a nadie (Airbnb) [HTSS 10 @0:17:26]; Altman lo recomienda [HTSS 02 @0:08:38]
   y lo repite para la etapa posterior: "if you write this down it will become law in the company", "one of the
   highest leverage things you can do" [HTSS 19 @0:07:41] [HTSS 19 @0:08:15] [HTSS 19 @0:08:48].
3. La cultura es un marco para decidir: "the key to culture is it's a rule, it's a framework for making decisions"
   (Rabois) [HTSS 14 @0:46:15]; "the resolution to a bandwidth problem" (la solución a un problema de ancho de banda),
   los invariantes que se mantienen cuando ya no estás en cada decisión (Patrick Collison, probable)
   [HTSS 11 @0:02:48] [HTSS 11 @0:03:20].
4. "People think culture is like architecture when it's a lot more like gardening" (la cultura es jardinería, no
   arquitectura) (Silbermann) [HTSS 11 @0:05:28].
5. "There's no such thing as a good or bad culture it's either a strong or weak culture" (no hay cultura buena o mala,
   solo fuerte o débil) (Chesky) [HTSS 10 @0:33:51]. "Building a strong company culture is the best guarantee to
   attract and keep the best people" (Junestrand) [SS26 01 @0:21:09].
6. Valores únicos, no genéricos: "integridad" u "honestidad" todos deberían tenerlas; los principios que no cambian
   son los que "make you you" (te hacen ser vos), 3 a 6 cosas únicas (Chesky) [HTSS 10 @0:16:53]. Lin: elegir valores
   genéricos sin profundidad es un error [HTSS 10 @0:06:35] [HTSS 10 @0:07:05].
7. La cultura es un hábito diario, como el fitness; si no, terminás en una dieta de choque que no funciona (Alfred Lin)
   [HTSS 10 @0:10:53]. Es "motherhood and apple pie": todos dicen quererla y pocos la vuelven hábito
   [HTSS 10 @0:10:20].
8. Contratá y despedí según los valores, y repetilos sin parar (Chesky) [HTSS 10 @0:28:58]. Cada contratación tiene
   que subir la vara ("raising the bar") [HTSS 10 @0:29:31].
9. Las historias de fundación se vuelven los valores que repiten los 1.000 empleados (Chesky) [HTSS 10 @0:22:50].
10. Misioneros vs mercenarios: "missionaries would outlast mercenaries" (los misioneros duran más) (Chesky)
    [HTSS 10 @0:31:40]. Airbnb busca a quien busca una vocación, no un trabajo (los dos albañiles: "estoy construyendo
    un muro" / "estoy construyendo una catedral") [HTSS 10 @0:22:18] [HTSS 10 @0:22:50].
11. Cultura y marca son dos caras de la misma moneda: lo que pasa adentro termina saliendo (Chesky) [HTSS 10 @0:32:47].
12. Las culturas de startup se heredan como "oral traditions" (tradiciones orales); conviene trabajar antes en una
    empresa con una cultura excelente que respetes (Max Hodak, Science) [SS26 06 @0:30:10] [SS26 06 @0:30:46]. Altman
    advierte contra dejar la cultura en "random oral tradition" sin escribirla [HTSS 19 @0:08:15].
13. Los detalles son cultura: "The Score Takes Care of Itself" (Bill Walsh, citado por Rabois): si todos los detalles
    están bien, el resultado es un subproducto [HTSS 14 @0:28:28]; la filosofía del detalle se instala al principio y
    después se autoperpetúa en la contratación y en cada líder [HTSS 14 @0:45:43] [HTSS 14 @0:46:15]. "You don't buy
    people shitty computers if you don't want them to write shitty code" (Altman) [HTSS 02 @0:37:52].
14. Toda buena startup es un culto: creés que sos mejor que todos y que tenés una forma especial de hacer las cosas
    (Rabois citando a Peter Thiel); por eso nunca compartas oficina [HTSS 14 @0:34:28].
15. "Let your team get all the credit for everything good that happens, and you take responsibility for the bad stuff"
    (Altman) [HTSS 02 @0:21:02].

### E. Gestionar y operar

1. Forjar una empresa es más difícil que forjar un producto: "people are irrational" (Rabois) [HTSS 14 @0:00:00]. La
   meta: "build a company that idiots can run because eventually they will" (Warren Buffett, citado por Rabois)
   [HTSS 14 @0:01:03].
2. El trabajo del líder: "maximize the output of an organization" (Andy Grove, vía Rabois) [HTSS 14 @0:01:37]. Medí
   output, no input; no confundas movimiento con progreso [HTSS 14 @0:02:10].
3. Antes del PMF, el trabajo número uno es el producto; hacia los 25 empleados "your main job shifts from building a
   great product to building a great company and it stays there for the rest of your time" (Altman), "probably the
   biggest shift in being a founder that ever happens" [HTSS 19 @0:03:19]. Chesky: fase 1 construir el producto, fase
   2 "building the company that builds the product" [HTSS 10 @0:14:43]. Junestrand: "building product is one thing,
   but building a company is a very different thing" [SS26 01 @0:17:08].
4. "When lack of structure fails it fails all at once" (cuando la falta de estructura falla, falla toda de golpe):
   todo plano funciona hasta 20-25 empleados y lo que anda de 0 a 20 "is disastrous at 30" (Altman)
   [HTSS 19 @0:01:07] [HTSS 19 @0:01:40]. "Management structure is not where I would recommend trying to innovate"
   (no innoves en la estructura de management; innová en producto y modelo de negocio) [HTSS 19 @0:02:12].
5. Delegar sin abdicar: sobredelegar y microgestionar son "both sins" (ambos pecados) (Rabois) [HTSS 14 @0:09:04]
   [HTSS 14 @0:09:36]. "You don't get to make their decisions, but you do get to choose the decision makers" (no
   tomás sus decisiones, pero elegís a quienes deciden) (Altman) [HTSS 02 @0:23:44].
6. Ninguna decisión sobre una persona es solo sobre esa persona: "when you're making a critical decision you have to
   understand how it's going to be interpreted from all points of view, not just your point of view and not just the
   person you're talking to, but the people who aren't in the room" (Ben Horowitz) [HTSS 15 @0:01:41]. Es "the easiest
   thing to say and the most difficult to master" [HTSS 15 @0:00:34].
7. Alineación es "the single word that matters most … to keep the company productive as it grows" (la palabra que más
   importa para que la empresa siga productiva al crecer) (Altman) [HTSS 19 @0:16:51]. La productividad cae "with the
   square of the number of employees" si no hacés nada [HTSS 19 @0:16:20]. "It's your job to align the team" (Satya
   Nadella) [AISS 07 @0:32:36]. La comunicación es lo que se rompe al escalar (Junestrand) [SS26 01 @0:42:08].
8. "The best founders repeat these goals over and over, far more often than they think they should need to" (los
   mejores fundadores repiten las metas muchísimo más de lo que creen necesario) y "You can't be focused without really
   great communication" (Altman) [HTSS 02 @0:33:29] [HTSS 02 @0:34:02].
9. Foco: "The trick to great execution is to say no a lot"; "You're saying no 97 times out of 100" (Altman)
   [HTSS 02 @0:32:23]. Una sola cosa por persona: si no, la gente resuelve problemas B+ en vez de A+ (Thiel en PayPal,
   contado por Rabois) [HTSS 14 @0:19:22] [HTSS 14 @0:19:54]. "Be brutal at saying no to things" (Junestrand)
   [SS26 01 @0:56:23].
10. "Always keep momentum" es "this prime directive for managing a startup" (Altman) [HTSS 02 @0:41:36]; "Save the
    vision speeches for when the company is winning" y "Sales fix everything in a startup" [HTSS 02 @0:42:40].
11. "Indecisiveness is a startup killer" y "bias towards action" (Altman) [HTSS 02 @0:38:23]. "Action produces
    information" (la acción produce información): cuando estás trabado, empezá a hacer cosas (Hodak)
    [SS26 06 @0:22:24].
12. La velocidad la decide la infraestructura interna: "rate of iteration separates success from failure" y la
    infraestructura (compras, contratación, gasto, presupuesto, evaluaciones) determina la velocidad (Hodak)
    [SS26 06 @0:18:42] [SS26 06 @0:19:17]. "Amateurs talk strategy, professionals talk logistics" [SS26 06 @0:01:53].
    Las deep tech casi nunca fracasan porque la tecnología no funciona, sino porque no construyen los sistemas para
    gestionar la organización [SS26 06 @0:19:17] [SS26 06 @0:19:56].
13. "You cannot delegate your judgment" (no podés delegar tu juicio), y tu juicio tiene que ser "differentiatedly
    good": copiar arrastra al promedio y "average ... is not good enough" (Hodak) [SS26 06 @0:20:33].
14. "Continue to be run by great products and not process for its own sake" (Altman) [HTSS 19 @0:18:29]. Al principio
    todo debería sentirse un desastre; mucho proceso y previsibilidad indica que no innovás rápido (Rabois)
    [HTSS 14 @0:02:41]. "The single hardest thing in business is building a company that does repeatable innovation"
    (Altman) [HTSS 19 @0:20:40].
15. Como CEO "there is no excuse": sos responsable de todo, sobre todo cuando sale mal (Rabois) [HTSS 14 @0:09:04].
    "You cannot hire a COO and have them do this while you go off to conferences" (poner la vara de ejecución no se
    delega) (Altman) [HTSS 02 @0:29:40].
16. Adaptá la empresa a vos: "you're going to build an F1 racer, but you're going to build it in a way that you can
    drive. You should adapt the car to you"; no hace falta cambiar tu personalidad al volverte CEO (Jensen Huang)
    [SS26 15 @0:17:00]. Visión de orador.
17. Ser CEO es un juego por etapas ("mini games"): "I need to re-qualify for the job as CEO of Legora. Every quarter"
    (Junestrand, con Gustaf Alströmer citando al fundador de Dropbox) [SS26 01 @0:53:44] [SS26 01 @0:54:20].

### F. Compensación, equity y retención

1. Equity para empleados: "as a rough guideline, you should aim to give 10% of the company to the first 10
   employees", ganado en 4 años (Altman) [HTSS 02 @0:18:20]. Los fundadores son "very stingy with equity to employees
   and very generous with equity to investors. And I think this is totally backwards" [HTSS 02 @0:18:53].
2. En la etapa posterior: pensá en dar 3 a 5% de la compañía por año durante los próximos 10 años, con refresher
   grants; las compañías donde mejor les va a los inversores "end up giving a lot of stock out to employees year
   after year" (Altman) [HTSS 19 @0:11:30]. "Investors will always give you bad advice" sobre la equity de empleados
   (no YC, pero la mayoría): son cortoplacistas [HTSS 19 @0:10:59].
3. "You never want an employee in a place where they vested three out of their four years of stock and they start
   thinking about leaving": adelantate a los vesting schedules (Altman) [HTSS 19 @0:12:03].
4. "Someday everyone will find out everyone else's comp" (algún día todos sabrán lo que gana cada uno): bandas por
   nivel y reglas claras para pasar de una a otra (Altman) [HTSS 19 @0:09:56] [HTSS 19 @0:10:28]. Horowitz: nada es
   confidencial, el que recibe un aumento lo festeja y los demás lo notan [HTSS 15 @0:12:09].
5. Nada de aumentos a pedido ni fuera de ciclo: "you have to be formal to save your own culture" (tenés que ser formal
   para salvar tu cultura) (Horowitz) [HTSS 15 @0:12:43] [HTSS 15 @0:13:15]; dar aumentos a quien los pide "is called
   encouraging behavior" [HTSS 15 @0:12:43].
6. Retener: que se sientan valorados y tratados con justicia (equity grande); no decirles cada día que lo hacen mal;
   darles el crédito, no microgestionar, sumarles áreas de responsabilidad; one-on-ones y feedback claro (Altman)
   [HTSS 02 @0:19:59] [HTSS 02 @0:20:31] [HTSS 02 @0:21:02] [HTSS 02 @0:21:34]. Motivan "autonomy, mastery, and
   purpose" (Dan Pink, citado por Altman) [HTSS 02 @0:21:34].
7. Retener a alguien por las esposas doradas produce "an employee who's worse than not having an employee"
   (Horowitz) [HTSS 15 @0:23:39].
8. Pagar en acciones no alcanza: empleados y fundadores cobran al menos el salario mínimo; "working for free is
   against the law" (Kirsty Nathoo y Carolynn Levy, YC; ley de EE. UU. de 2014) [HTSS 18 @0:32:26] [HTSS 18 @0:37:59].
9. Si el AE gana mucho porque la empresa vende, es buena señal: "they should be making a lot of money if your company
   is succeeding" (Paffenholz) [SS 33 @0:14:02]. Ratio 5:1 entre ARR nuevo y compensación total del vendedor: ver
   capítulo 06 [SS 24 @0:11:28].

### G. Despedir

1. "Fire fast when it's not working out. It's better for the company. It's also better for the employee"; "every
   first-time founder waits too long" (todo fundador primerizo espera demasiado) (Altman) [HTSS 02 @0:22:07].
2. Criterio: no uno o dos errores (ahí, ser cariñoso y trabajar en equipo), sino que tome sistemáticamente las
   decisiones opuestas a las que tomarías, por semanas o un mes (Altman) [HTSS 02 @0:23:13] [HTSS 02 @0:23:44].
   Despedí también a quien crea política interna y a quien es persistentemente negativo [HTSS 02 @0:22:40].
3. "There is only downside to procrastination": un empleado tóxico hace que se vayan los buenos (Levy)
   [HTSS 18 @0:40:43]. "You're not a real founder until you've had to fire somebody" (dicho de alguien de YC)
   [HTSS 18 @0:40:09].
4. Si alguien no encaja, se lo debés a la empresa y a él: decirle cómo mejorar y, si no funciona, despedirlo
   (Silbermann) [HTSS 11 @0:15:49]. Dar feedback pronto: "when you have employees that's kind of what you owe them"
   (John Collison) [HTSS 11 @0:27:08] [HTSS 11 @0:28:12].
5. "You can take somebody's job, you have to take their job, but you don't have to take their dignity" (podés
   quitarle el trabajo, tenés que hacerlo, pero no la dignidad), lección de Bill Campbell (Horowitz)
   [HTSS 15 @0:39:10]. Al despedir, la causa número uno es tu error de contratación [HTSS 15 @0:38:36].

### H. La psicología del líder

1. "The number one role of a CEO is managing your own psychology" (cita de Horowitz que Moskovitz suscribe: "it's
   absolutely true") [HTSS 01 @0:31:56]. Como CEO el juego real es "who do I disappoint the least" [HTSS 01 @0:33:39].
2. La psicología del fundador "gets worse not better" al crecer: los altos son más altos y los bajos más bajos
   (Altman) [HTSS 19 @0:26:07] [HTSS 19 @0:26:42]. Hasta el PMF es un sprint; después, una maratón [HTSS 19 @0:13:08].
   Tomá vacaciones; fundadores que pasan 3 o 4 años sin más de un día libre se queman [HTSS 19 @0:28:23].
3. "The thing that kills startups at some level is the founders giving up" (Altman) [HTSS 19 @0:30:01].
4. Enfocate en lo que podés hacer, no en lo que te pasó (Horowitz) [HTSS 15 @0:41:26]. Cuando algo importante no lo
   pensaste: "pause" y decí que lo vas a pensar desde todas las perspectivas [HTSS 15 @0:47:32] [HTSS 15 @0:48:05];
   no lo entierres ("the kimchi problem: the deeper you bury it the hotter it gets") [HTSS 15 @0:48:37].
5. Competir en equipo: celebrar las victorias, llorar juntos las derrotas y en seguida armar un plan; "solution mode
   rather than like blame mode" (Junestrand) [SS26 01 @0:43:28].

---

## Definiciones

- **Barril y munición** (Rabois): barril es quien puede llevar una idea desde la concepción hasta el lanzamiento y
  arrastrar gente con él; munición es el resto, aun si es excelente. Es específico de cada cultura [HTSS 14 @0:15:03]
  [HTSS 14 @0:15:36].
- **Task relevant maturity** (Andy Grove, vía Rabois): "basically has this person ever done this before" (¿esta
  persona ya hizo esto antes?) [HTSS 14 @0:09:36].
- **Problema A+ vs B+** (Rabois): A+ es de alto impacto y difícil, sin solución obvia al despertar; B+ es el que sabés
  resolver [HTSS 14 @0:19:54].
- **Pairing metrics / pairing indicators** (Rabois): "if you measure one thing and only one thing the company tends to
  optimize to that": medí también su opuesta y hacé responsable al equipo de ambas [HTSS 14 @0:24:46].
- **Minimal viable transparency** (Rabois): las tácticas de transparencia que se leen y oyen; cree que se puede ir
  mucho más lejos [HTSS 14 @0:23:42].
- **Cultura** (cuatro versiones):
  - Alfred Lin: "every day blank and blank of each member of the team in pursuit of our company blank" = los valores
    centrales y las acciones de cada miembro del equipo, todos los días, en persecución de la misión
    [HTSS 10 @0:01:41] [HTSS 10 @0:02:13].
  - Chesky: "a shared way of doing things" [HTSS 10 @0:16:21]; "the principles and the beliefs you have inside the
    company" [HTSS 10 @0:32:47].
  - Patrick Collison (probable): "the resolution to a bandwidth problem", los invariantes [HTSS 11 @0:02:48].
  - Rabois: "a rule, it's a framework for making decisions" [HTSS 14 @0:46:15].
- **Marca** (Chesky): "the promise outside the company that everyone identifies with" [HTSS 10 @0:32:47].
- **Misioneros vs mercenarios** (Chesky): los que están por las creencias vs los que están para ganar mucha plata
  rápido [HTSS 10 @0:31:40].
- **Job vs calling** (Chesky): trabajo vs vocación; parábola de los dos albañiles [HTSS 10 @0:22:18].
- **Persona 10x** (Patrick Collison, probable): no sabe qué significa "10x"; la versión intuitiva es "is this person
  probably the best out of all of their friends at what they do", "is this the best engineer this engineer knows"
  [HTSS 11 @0:20:39] [HTSS 11 @0:21:12].
- **Referenciar** (Silbermann): "asking people who have real material work experience for their honest opinion"
  [HTSS 11 @0:22:16].
- **Startup** (Patrick Collison, citando a alguien que no recuerda): una organización que todavía no está atascada en
  los problemas principal-agente de las grandes empresas [HTSS 11 @0:34:13] [HTSS 11 @0:34:47].
- **Y-intercept vs slope** (Altman/Buchheit; Junestrand): punto de partida (logos del CV) vs pendiente (velocidad de
  mejora) [AISS 03 @0:31:51] [SS26 01 @0:17:50].
- **Judgment, horsepower, agency** (Hodak): juicio ("if we throw you into a complex, vaguely defined situation, will you
  tend to make good decisions or will you create diplomatic incidents?"), potencia (competencia técnica básica y
  capacidad demostrada de aprender) y agencia ("are you effective at causing the world to look like you wish it
  were?") [SS26 06 @0:12:59].
- **Eigenreviews** (Hodak): evaluación de desempeño por grafo de votos ponderados por centralidad de vector propio
  [SS26 06 @0:16:52] [SS26 06 @0:17:27].
- **Sourcing** (Paffenholz): "proactively finding candidates rather than waiting for applicants who come to you"
  [SS 33 @0:08:06].
- **Reply rate vs interested rate** (Paffenholz): tasa de respuesta total vs tasa de respuestas interesadas en el rol;
  la dorada es la segunda [SS 33 @0:18:21] [SS 33 @0:18:52].
- **Reclutador in-house / por contrato / por contingencia** (Paffenholz): ver Frameworks, F4 [SS 33 @0:40:51].
- **Work at a Startup**: bolsa de trabajo de YC para sus compañías [SS 33 @0:07:02].
- **Empleado vs contratista** (Nathoo): ver Frameworks, F13 [HTSS 18 @0:36:20].
- **Founder breakup** (Levy): que a un fundador le pidan irse; como los fundadores son empleados, "your co-founders
  are firing you" [HTSS 18 @0:33:30].
- **Hero mode** (Altman): liderar con el ejemplo llevado al extremo (el jefe de soporte que hace 18 a 20 horas por día
  de tickets) [HTSS 19 @0:04:24].
- **Refresher grants, pyramid vesting, continuous forward vesting** (Altman): ver Frameworks, F9 [HTSS 19 @0:12:03].
- **Encouraging behavior** (Horowitz): si das aumentos a quien los pide, vas a tener mucha gente pidiendo aumentos
  [HTSS 15 @0:12:43].
- **Kimchi problem** (Horowitz): "the deeper you bury it the hotter it gets" [HTSS 15 @0:48:37].
- **Calendar audit** (Rabois): registrar en qué se va el tiempo y compararlo con las prioridades [HTSS 14 @0:37:10].
- **DRI** (directly responsible individual, Jack Dorsey citado por Diana Hu): "one person, one outcome, no hiding"
  (una persona, un resultado, sin esconderse) [SS 15 @0:07:16].
- **Human middleware** (Diana Hu): mandos medios y coordinadores que solo enrutan información; "you should have almost
  no human middleware" [SS 15 @0:06:10].
- **Skill file y resolver** (Garry Tan): "a skill file is an employee it has one capability one job written down clearly
  enough that someone new could execute it"; "a resolver is an org chart a task comes in and it decides which markdown
  file or who handles it" [SS26 07 @0:21:14].
- **Talent density** (Alexandr Wang): concentración de gente talentosa; "compounds naturally" (más talento atrae más
  talento) [SS26 11 @0:14:15].
- **Jantelagen / ley de Jante** (Junestrand): norma cultural sueca de no creerte alguien [SS26 01 @0:20:00].
- **Dev advocate** (Dessaigne): rol de desarrollador en marketing, "a very ill defined role" [SS 17 @0:30:07].

---

## Frameworks (pasos completos)

### F1. Las cinco tareas del CEO de una startup temprana (Altman)
1. Fijar la visión. 2. Levantar plata. 3. Evangelizar la empresa (a candidatos, empleados, socios, prensa, clientes).
4. Contratar y gestionar al equipo. 5. **Poner la vara de ejecución** (la que nadie piensa y solo el CEO puede hacer)
[HTSS 02 @0:30:12] [HTSS 02 @0:30:46].
Versión de Chesky (tres cosas): (1) articular la visión, (2) desarrollar la estrategia, (3) contratar gente que encaje
en la cultura: "If you do those three things you basically have a company" [HTSS 10 @0:36:39] [HTSS 10 @0:37:10].
Ejecución = dos preguntas: "can you figure out what to do?" y "can you get it done?"; hacerlo = foco + intensidad
(Altman) [HTSS 02 @0:30:46] [HTSS 02 @0:31:19].

### F2. Las cuatro razones para que elijan tu startup y los tres destinos del talento (Paffenholz)
Tres destinos [SS 33 @0:02:13] [SS 33 @0:02:45] [SS 33 @0:03:18]:
1. **Big tech** (FAANG): compensación fuerte, empleo estable; ritmo más lento, menos impacto.
2. **Growth stage** (Stripe, OpenAI, Anthropic; en general Serie B en adelante): upside predecible, la acción
   difícilmente va a cero, buen sueldo; ritmo bastante rápido; mucha estructura, varias capas, sin trabajo directo con
   los fundadores, menos ownership.
3. **Tu startup**: dar forma a la cultura, el producto y la trayectoria; máxima varianza económica (los mayores grants
   y la mayor probabilidad de que valgan cero). El riesgo se parece al de un fundador.
Primero averiguá a cuál se inclina el candidato y por qué; si también entrevista en big tech, todavía no decidió y hay
que volver a venderle "por qué una startup" [SS 33 @0:03:50] [SS 33 @0:04:22].
Cuatro argumentos (elegí uno o dos según el candidato) [SS 33 @0:04:54] a [SS 33 @0:06:29]:
1. **Misión** (gente con conexión personal con el problema).
2. **Equity y upside** (incluso darle una calculadora de valor de las acciones).
3. **Problema interesante** (deep tech, desafíos técnicos grandes).
4. **Cultura y equipo** (sobre todo referidos que ya conocen a alguien adentro); "often missed" (muchas veces se
   olvida).
Complemento de Patrick Collison: el otro motivador es el desarrollo personal; en Google no cambiás la trayectoria, en
una startup podés medir tu impacto [HTSS 11 @0:47:22] [HTSS 11 @0:47:53]. Masad: la experiencia generalista decae
exponencialmente del fundador al empleado 100; aun ser el número 20 de una serie B te da más que una FAANG
[AISS 10 @0:34:26].

### F3. Tres fuentes de candidatos y el sourcing como ventas outbound (Paffenholz)
Fuentes [SS 33 @0:06:29] [SS 33 @0:07:02] [SS 33 @0:07:34]:
1. **Referidos**: gente que conocés, que trabajó con vos, que conoce tu equipo. Hay empresas que el primer día del
   nuevo empleado repasan con él cada una de sus conexiones (Altman lo cuenta de Facebook y Google: sacarle "every
   smart person you've ever met" [HTSS 02 @0:13:30]). Bono por referido de 10.000 a 20.000 dólares o más; aun así más
   barato que una agencia.
2. **Publicar el aviso**: Work at a Startup (si sos de YC; Juicebox hizo su primera contratación ahí), LinkedIn y otros
   job boards (mucho ruido, poca tasa de acierto). Lo controlable: un JD muy fácil de leer.
3. **Sourcing**: "the best candidates aren't applying" (los mejores no se postulan) [SS 33 @0:08:06]. Es outbound de
   ventas: top of funnel, prospección = sourcing, cold outreach = mails o DMs, seguir pipeline y conversión. Pasos
   [SS 33 @0:08:39] [SS 33 @0:09:12]: (1) **Search** (LinkedIn Recruiter, Juicebox); (2) **Engage** (campaña de varios
   pasos, varios fundadores al mismo candidato); (3) **Interview**; (4) **Close**.
Otras fuentes de los videos: Craigslist, charlas técnicas, bares, asados semanales en la oficina, el café de al lado
(Stripe reclutaba en Coupa Café) [HTSS 11 @0:12:36] [HTSS 11 @0:13:08]; "I just don't think there's any wrong place to
find people" (Silbermann) [HTSS 11 @0:12:36]; mirá fuera del Valle (Altman) [HTSS 02 @0:14:03]; las referencias son
"a tremendous source of new recruits" [HTSS 11 @0:23:54]; la mejor contratación viene de tu red y de la red que
produjo la startup, que debe ser el blanco de tu marketing inicial (Hodak) [SS26 06 @0:09:17]; comunidades (Slack,
open source, Discord) y DMs de Twitter si tenés presencia [SS 33 @0:12:23] [SS 33 @0:29:36].

### F4. Tres tipos de reclutador y cuándo (Paffenholz con Harj Taggar)
Decidí según cuántas contrataciones estás seguro de hacer en 6 a 12 meses [SS 33 @0:40:51]:
1. **In-house** (mayor compromiso): empleado full time, sueldo base más algo de equity, normalmente sin comisión
   [SS 33 @0:40:51] [SS 33 @0:41:24].
2. **Por contrato o embebido**: horas por semana, contrato de 3 o 6 meses, mes a mes o semana a semana; costo
   controlado [SS 33 @0:41:24] [SS 33 @0:41:56].
3. **Por contingencia** (el más flexible): 20-25% del sueldo o más para senior, "50.000 dólares o más por
   contratación"; se pueden usar varios a la vez [SS 33 @0:41:56] [SS 33 @0:42:28].
Cuándo: cada fundador puede llevar bien **una** búsqueda a la vez; con dos cofundadores, dos es la capacidad; con más
búsquedas que fundadores, reclutador [SS 33 @0:42:28] [SS 33 @0:43:00]. Altman (etapa posterior): recruiter full time
cuando las cosas funcionan, no antes (contratás demasiado rápido y implota) ni demasiado tarde [HTSS 19 @0:13:40].
Pinterest: la persona 14 o 15 fue una reclutadora profesional con experiencia en startups y Apple que enseñó a todos a
detectar talento y fit cultural de forma escalable [HTSS 11 @0:30:23].

### F5. El proceso de contratación de Science en cuatro pasos (Hodak, visión de orador)
"The minimum set of information that we need to make a full decision" [SS26 06 @0:14:59]. Regla previa: "a wrong
answer for sure is not having something that you do very religiously" (lo que seguro está mal es no tener un proceso
que sigas religiosamente) [SS26 06 @0:09:52]; nadie ni ningún grupo chico debe ser cuello de botella en la parte alta
del embudo [SS26 06 @0:11:43].
1. **Aplicación en software propio + votación de toda la empresa**: el sistema elige 7 u 8 empleados con antecedentes
   parecidos al candidato y les pide voto: "Known good / Strong yes / Yes / No / Strong no"; se resuelve en 24 o 48
   horas; pasa el 17% [SS26 06 @0:10:26] [SS26 06 @0:11:05] [SS26 06 @0:11:43] [SS26 06 @0:12:22].
2. **Phone screen** con un pool de entrevistadores de toda la empresa, no del equipo; busca **judgment, horsepower,
   agency**; pasa la mitad [SS26 06 @0:12:59].
3. **Homework "AI-resistant"**: que no se sature, techo muy alto, puntuable en 2 o 3 números para graficar y ver quién
   supera la frontera de Pareto, sin importar qué modelos use; si no se puede, llamadas técnicas o pruebas
   presenciales [SS26 06 @0:13:38].
4. **Entrevista completa** on-site, con al menos 25% de conversión a oferta; si no, se pierde demasiado tiempo
   [SS26 06 @0:14:16].
Como fundador, entrevistá a todos "for quite a while", y aun después promediá el juicio del equipo con votaciones
[SS26 06 @0:12:22].

### F6. Los cuatro errores de los fundadores que se vuelven gerentes (Altman)
1. **Miedo a contratar gente senior**: al principio es un error contratar senior; al escalar hay que traer ejecutivos
   que ya construyeron compañías; todos dicen después "wow I wish I had done that earlier" [HTSS 19 @0:03:52]
   [HTSS 19 @0:04:24].
2. **Hero mode**: salida: aceptar quedarse atrás dos o tres semanas para contratar (por ejemplo tres personas de
   soporte), y la próxima vez anticiparse según la tasa de crecimiento [HTSS 19 @0:04:24] [HTSS 19 @0:04:57]
   [HTSS 19 @0:05:29].
3. **Mala delegación**: "andá, investigá, traeme los datos, yo decido" no escala ni hace sentir bien. Lo que funciona:
   "you're really smart that's why I hired you … here's what I think but you make this decision I totally trust you"
   [HTSS 19 @0:05:29] [HTSS 19 @0:06:01] [HTSS 19 @0:06:32]. La delegación tipo Steve Jobs no sirve para el 99,9%
   [HTSS 19 @0:06:01] [HTSS 19 @0:06:32].
4. **Organización personal**: un sistema para saber qué tenés que hacer, qué hace cada uno y qué seguimiento darle
   [HTSS 19 @0:06:32] [HTSS 19 @0:07:07]. Los tres sistemas de Altman: una hoja con metas de 3 a 12 meses que mira cada
   día; una hoja por día con metas cortas (si algo es para dentro de una semana, avanza siete hojas y lo anota); una
   lista por persona (en qué trabaja, qué decirle, qué hablaron la última vez) [HTSS 19 @0:38:14].

### F7. Buen HR: las doce piezas (Altman, etapa posterior)
HR bueno "actually speeds you up" (te acelera); no es "TV sitcom HR" [HTSS 19 @0:08:48] [HTSS 19 @0:09:22].
1. Estructura clara (ver Cómo se hace, P13). 2. Un camino de carrera. 3. **Feedback de desempeño** frecuente, simple,
atado a salida si va mal y a compensación si va bien. 4. **Bandas de compensación** por nivel (ingeniero mid, senior)
y cómo se pasa de una a otra. 5. **Equity** generosa y continua, con refresher grants. 6. **Sistema de gestión de
opciones** (software, no Excel: errores con la planilla costaron "tens of millions of dollars"). 7. **Reglas de 50
empleados** (capacitación en acoso sexual y diversidad, y otras). 8. **Monitorear el burnout** (que toda la compañía se
queme a la vez es "often a company ending thing"). 9. **Proceso de contratación** con recruiter full time.
10. **Onboarding** con buddy. 11. **Diversidad** temprana. 12. **Plan para los empleados tempranos**
[HTSS 19 @0:09:22] a [HTSS 19 @0:15:17].

### F8. Ritmos de comunicación de una compañía que escala (Altman)
1. **Reunión de management semanal** con los reportes directos del CEO: "critical" [HTSS 19 @0:19:02].
2. **All hands** al menos una vez por mes, con resultados y roadmap [HTSS 19 @0:19:02] [HTSS 19 @0:19:35].
3. **Plan trimestral**: qué se hace en los próximos tres meses y cómo encaja en las metas del año [HTSS 19 @0:19:35].
4. **Offsites**: llevar a los mejores un fin de semana a una cabaña a hablar de "what do we want to be when we grow up";
   se hacen pocos y "everyone I know that does those thinks they're well worth the time" [HTSS 19 @0:19:35]
   [HTSS 19 @0:20:07].
Más: roadmap a 3, 6 o 12 meses según la etapa [HTSS 19 @0:16:51]; revisión semanal de métricas y all hands semanal en
la etapa temprana [HTSS 02 @0:33:29] [HTSS 02 @0:34:36]; KPI primario, cuello de botella y retros semanales (Divya, YC;
ver capítulo 07) [SS 30 @0:08:12] a [SS 30 @0:09:16].

### F9. Estructuras de vesting para empleados (Altman)
- Estándar de Silicon Valley: 4 años con cliff de 1 año (25% al año, el resto mensual) [HTSS 02 @0:26:26]
  [HTSS 18 @0:14:18] [HTSS 18 @0:14:51].
- **Grants grandes a seis años**: su preferida, "because I think these companies just take a while to build".
- **Pyramid vesting**: el grant se carga hacia el final (en el año 4 se consolida mucho más que en el 1).
- **Continuous forward vesting**: el grant se renueva automáticamente cada año por la misma cantidad de acciones.
[HTSS 19 @0:12:03] [HTSS 19 @0:12:36].

### F10. Las cuatro dimensiones de la cultura (Silbermann) y la definición en blanco (Lin)
Silbermann [HTSS 11 @0:00:33] [HTSS 11 @0:01:09]: 1. A quién contratamos y qué valoran. 2. Qué hacemos todos los días y
por qué. 3. Qué elegimos comunicar. 4. Qué elegimos celebrar (y su reverso, qué castigamos); dirigir por lo que se
celebra es "more exciting".
Lin [HTSS 10 @0:01:41] [HTSS 10 @0:02:13]: "every day ___ and ___ of each member of the team in pursuit of our
company ___". Primer blanco: supuestos, creencias, valores (el favorito: **core values**). Segundo: comportamientos (el
favorito: **acciones reales**). Tercero: metas grandes y audaces (la mejor: **la misión**).

### F11. Por qué importa la cultura: el acrónimo "help you move faster" (Lin)
Seis razones [HTSS 10 @0:02:45] [HTSS 10 @0:03:16]: 1. Primeros principios a los que volver cuando decidís. 2. Alinear
a la gente en los valores que importan. 3. Estabilidad a la que volver. 4. Confianza entre las personas. 5. Qué hacer
y, sobre todo, qué no hacer. 6. Retener a los empleados correctos (y saber a quién no). (El orden exacto de las letras
no se lee en voz.) Dato que da: las "100 Best Companies to Work For" de Fortune (1997 a 2003) rindieron ~11,8% en bolsa,
casi el doble del S&P 500 y del Russell 3000 (cifra dudosa en el subtítulo) [HTSS 10 @0:03:49] [HTSS 10 @0:04:21].

### F12. Cómo definir los valores centrales (Lin, método Zappos)
En orden [HTSS 10 @0:04:21] [HTSS 10 @0:04:54] [HTSS 10 @0:05:27]:
1. Empezá por el líder: ¿qué valores personales son los más importantes para vos?
2. ¿Cuáles son los más importantes para el negocio?
3. ¿Con qué tipo de gente te gusta trabajar y qué valores tiene?
4. ¿Con quién nunca te gustó trabajar? Lo opuesto de sus valores puede ser un valor tuyo.
5. Chequeo: los valores tienen que apoyar la misión; si no, falta algo.
6. Chequeo final: que sean **creíbles** y **únicamente atados a tu misión**.
7. Bajá a profundidad cada valor (un párrafo que explique qué significa); "honestidad" sola no sirve.
Mejores prácticas de Lin [HTSS 10 @0:09:16] a [HTSS 10 @0:10:53]: (1) incorporar la misión en los valores; (2)
pensarlos más fuerte, más hondo, más tiempo; (3) entrevistar por fit cultural y por creencia en la misión, no solo por
habilidad; (4) llevar la cultura de la entrevista a las evaluaciones de desempeño; (5) hacerla hábito diario.
Las dos partes de la cultura (Chesky) [HTSS 10 @0:16:53]: comportamientos y rituales (pueden cambiar) y principios que
no cambian (3 a 6, únicos).

### F13. Empleado vs contratista (Nathoo, ley de EE. UU., 2014)
| | Contratista | Empleado |
|---|---|---|
| Horario y lugar | los fija él | los fija la compañía |
| Trabajo | proyecto con resultado; el cómo es suyo | lo dirige la compañía |
| Equipo | propio | de la compañía |
| Decisiones del día a día y estrategia | ninguna | sí |
| Contrato | consulting agreement + asignación de IP | asignación de IP |
| Impuestos | no se retienen; los paga el individuo | la compañía retiene y paga |
| Formulario anual | 1099 | W-2 |
[HTSS 18 @0:36:20] [HTSS 18 @0:36:52] [HTSS 18 @0:37:25]. El IRS mira mucho esta clasificación y multa
[HTSS 18 @0:35:44]. (Las celdas vacías del extracto original se completaron por contraste; Nathoo no las enumera.)

### F14. Pirámide de las cinco disfunciones de un equipo (Patrick Lencioni, citada por Lin)
De la base a la punta [HTSS 10 @0:08:11] [HTSS 10 @0:08:43] [HTSS 10 @0:09:16]:
1. **Falta de confianza** → sin confianza no hay debate.
2. **Miedo al conflicto** → sin debate no sabés si llegaste a la respuesta correcta ("the blind leading the blind").
3. **Falta de compromiso**.
4. **Evitar la rendición de cuentas**.
5. **Falta de resultados**.
Uso: la compañía es una caja negra cuyo output son resultados; la cultura es uno de los inputs principales.

### F15. El líder como editor (Rabois, aprendido en Square)
"The best metaphor I've ever seen in like 14 years of running stuff"; cada empleado sabe si está escribiendo o
editando [HTSS 14 @0:03:12] [HTSS 14 @0:03:45].
1. **Simplificar**: llevar todo a una, dos o tres cosas con un marco que la gente repita sin pensar; "Don't accept the
   excuse of complexity" [HTSS 14 @0:03:45] [HTSS 14 @0:04:49].
2. **Hacer preguntas aclaratorias**, de básicas ("¿probamos 7 días a la semana o 6?") a fundamentales ("¿dónde está
   nuestra ventaja competitiva?"); cada paso eliminado mejora el rendimiento 30 a 50% según Andy Grove
   [HTSS 14 @0:04:49] a [HTSS 14 @0:06:24].
3. **Asignar recursos**, de arriba abajo o de abajo arriba (los empleados proponen sus iniciativas como periodistas sus
   historias) [HTSS 14 @0:06:24] [HTSS 14 @0:06:57].
4. **Usar cada vez menos tinta roja**: mide qué tan bien comunicás lo importante [HTSS 14 @0:06:57] [HTSS 14 @0:07:29].
5. **Asegurar una voz consistente** (como The Economist): web, PR, empaque, reclutamiento suenan a una persona
   [HTSS 14 @0:07:29] a [HTSS 14 @0:08:32].
6. **Delegar sin abdicar** [HTSS 14 @0:09:04] [HTSS 14 @0:09:36].

### F16. Delegar: task relevant maturity + matriz convicción por consecuencia (Rabois)
- Cuanto más hizo la persona esa misma tarea, más soga; cuanto más nueva, más instrucciones y monitoreo. Ningún
  ejecutivo debería tener un solo estilo de management; si en las referencias de un gerente la mitad dice
  "microgestiona" y la otra "me da mucha responsabilidad", es "a feature, not a bug" [HTSS 14 @0:09:36]
  [HTSS 14 @0:10:09] [HTSS 14 @0:10:40].
- Matriz (tomada de Thiel): ejes convicción (alta a baja) y consecuencia (catastrófica a baja). Baja consecuencia y
  baja convicción: delegá del todo, que se equivoquen y aprendan. Consecuencia dramática y convicción muy alta: decidís
  vos, explicando el porqué. Llevá la cuenta de cuántas veces imponés: cada "okay, you're the boss" gasta capital
  social [HTSS 14 @0:11:13] [HTSS 14 @0:11:44] [HTSS 14 @0:12:17] [HTSS 14 @0:12:49]. (Los cuadrantes mixtos no los
  explica.)
- Caso Kyle en Square (Inner Square): Rabois no creía en la idea, la dejó hacer, no generó valor masivo pero Kyle
  aprendió a filtrar ideas [HTSS 14 @0:12:49] [HTSS 14 @0:13:55].

### F17. Barriles y municiones: detectarlos y crecerlos (Rabois)
1. Empezá con responsabilidades chicas, incluso triviales, y expandí el alcance "until it breaks" (hasta que se rompa);
   ese nivel es su lugar [HTSS 14 @0:16:07] [HTSS 14 @0:17:12]. Caso: los smoothies de Square, meses de fracaso del
   office manager; un pasante lo resolvió la primera noche y recibió tareas más complejas [HTSS 14 @0:16:40].
2. En una oficina abierta, mirá a qué escritorios va la gente que no le reporta a esa persona: son tus barriles;
   promovelos rápido [HTSS 14 @0:17:45].
3. Trato: mucha equity, promoverlos, cena cada semana; son casi irremplazables [HTSS 14 @0:15:36].
4. Proporción: en ingeniería "roughly 1 to 10 to 20"; si sos el único barril con 50 ingenieros, "you might as well
   only have 10" [HTSS 14 @0:40:23] [HTSS 14 @0:40:55].
5. Curva de la persona vs curva de la empresa: "always track the individual slope of an employee and the company's
   growth rate"; si la empresa crece más rápido que lo que aprende la persona, no puede seguir en el rol
   [HTSS 14 @0:18:17] [HTSS 14 @0:18:50].

### F18. Herramientas de escala (Rabois)
1. **Dashboard** que dibuja el fundador en una pizarra (qué es el éxito y sus inputs clave); meta: cerca del 100% de los
   empleados lo usa cada día [HTSS 14 @0:21:00] [HTSS 14 @0:21:32] [HTSS 14 @0:22:04].
2. **Transparencia por etapas**: métricas para todos; repasar cada slide del deck de directorio con toda la empresa
   después de cada reunión (se puede quitar compensación); notas de cada reunión de más de dos personas a toda la
   empresa; salas con paredes de vidrio [HTSS 14 @0:22:37] [HTSS 14 @0:23:09] [HTSS 14 @0:23:42].
3. **Métricas de output**, que dicta el fundador [HTSS 14 @0:24:46].
4. **Métricas pareadas**: fraude medido solo por tasa de fraude trata a todos como sospechosos; medí también falsos
   positivos. Reclutadores: medir entrevistas sin calidad de contratación [HTSS 14 @0:24:46] [HTSS 14 @0:25:19]
   [HTSS 14 @0:25:50].
5. **Buscar anomalías** (los power sellers de eBay en PayPal) [HTSS 14 @0:25:50] [HTSS 14 @0:26:22].

### F19. One-on-ones (Rabois según Andy Grove; Altman)
- Uno cada dos semanas como canon, uno por semana puede ser ideal, nunca más espaciado que uno por mes; de ahí la regla
  de 5 a 7 reportes directos [HTSS 14 @0:39:18] [HTSS 14 @0:39:50].
- La agenda la arma el empleado ("mostly for the benefit of the employee"), con 3 o 4 temas enviados antes por email
  [HTSS 14 @0:39:50].
- Altman: one-on-ones y feedback claro para retener [HTSS 02 @0:21:34].

### F20. Ver la decisión con los ojos de toda la empresa (Horowitz), con sus cuatro casos
Método: listar perspectivas (la tuya, la de la persona afectada, la de los demás empleados) y recién decidir
[HTSS 15 @0:04:24] [HTSS 15 @0:08:41].
1. **Degradar o despedir al ejecutivo que se esfuerza pero no da la talla** (el de ventas que trabajaba de 6 a 22):
   degradarlo parecía "win-win" hasta pensar en su 1,5% de equity frente a ingenieros con 0,1% o 0,2%. Preguntas:
   "what is the equity package that this exec has?", "are you going to take the equity away?", "will people give him
   the same respect now that you've demoted him?". Define qué significa fallar en el trabajo mejor pagado
   [HTSS 15 @0:03:19] [HTSS 15 @0:05:59] [HTSS 15 @0:06:31] [HTSS 15 @0:07:35] [HTSS 15 @0:08:07].
2. **El excelente empleado que pide aumento**: no se da a pedido (proceso formal, ver P15) [HTSS 15 @0:08:41]
   [HTSS 15 @0:13:48].
3. **Opciones ejercitables a 10 años** (post de Sam Altman con la idea de Adam D'Angelo): dos declaraciones culturales
   posibles, (a) "máxima franqueza, tenés 10 años para ejercer" o (b) "valoramos a los que se quedan: no entres si te
   vas en 18 meses"; cuál elegir depende de tu cultura. Explicá la regla de 90 días al contratar [HTSS 15 @0:24:46]
   [HTSS 15 @0:25:21] [HTSS 15 @0:21:28].
4. **Toussaint Louverture**: prohibió el saqueo, hizo generales a los mejores oficiales vencidos para elevar la cultura,
   y dejó la tierra a los dueños obligándolos a pagar a sus trabajadores con impuestos más bajos. Lección: mirar desde
   todos los constituyentes, incluso los que odiás [HTSS 15 @0:29:46] a [HTSS 15 @0:36:22].

### F21. Equipos como "una startup de muchas startups" (Silbermann) y pods (Rahman)
- Equipos tan autónomos como se pueda; cada uno controla sus recursos, sabe qué es lo más importante y cómo se mide;
  si no, la complejidad de comunicación crece "geometrically". En Pinterest cada unidad tiene diseñador fuerte, líder
  de ingeniería fuerte, a menudo un escritor, a veces un community manager, anclados en un solo proyecto
  [HTSS 11 @0:28:47] [HTSS 11 @0:29:19] [HTSS 11 @0:29:51].
- Jawbone: cada tema lo tiene un pod con product experience, hardware, software y datos [HTSS 17 @0:18:27].

### F22. El horizonte temporal crece con la edad de la empresa (Patrick Collison, probable)
Después de un mes pensás un mes adelante; de un año, un año; de cuatro años, cuatro. Al principio solo podés
contratar gente productiva de inmediato; a los dos o tres años conviene invertir en gente prometedora que tardará uno
o dos años, y si no "you're probably being much too short term" [HTSS 11 @0:31:30] a [HTSS 11 @0:33:07]. Crecer la
plantilla 2x o 3x por año "is a very unnatural thing" [HTSS 11 @0:33:07].

### F23. La empresa nativa de IA: tres arquetipos de empleado (Diana Hu citando a Jack Dorsey, visión 2025-2026)
1. **IC** (constructor-operador): construye y opera; no solo ingenieros; todos llegan a las reuniones con prototipos,
   no con decks.
2. **DRI**: estrategia y resultados para el cliente; no es un gerente clásico.
3. **AI founder type**: sigue construyendo, entrena y lidera con el ejemplo; si sos el fundador, sos vos.
[SS 15 @0:07:16]. Contexto: "You should have almost no human middleware"; "Your company's velocity is only as fast as
its information flow"; empresa "consultable" (reuniones grabadas, agentes en todos los canales, dashboards de todo,
incluida contratación); "You cannot outsource your conviction on the power of these tools"; si mantenés el mismo
organigrama te perdés el cambio [SS 15 @0:02:20] [SS 15 @0:06:10] [SS 15 @0:06:44] [SS 15 @0:08:56].

### F24. Equipo de una empresa de servicios nativa de IA (SS 16, orador de YC no identificado)
Tres atributos de los mejores fundadores [SS 16 @0:04:33]: (1) **domain fluency** (experiencia directa o aprendida);
(2) **model fluency**; (3) **operational rigor** (varianza, throughput, tiempos de ciclo, SOPs: "The product is an
operation") [SS 16 @0:05:05]. Los humanos en el loop deben escalar no linealmente y disfrutar el software: son tus
usuarios [SS 16 @0:05:38]. Ejemplo: estudio jurídico nativo de IA con fundadores de Cooley y Fenwick y liderazgo técnico
de Casetext, con turnos para bajar tiempos de ciclo y atraer a los mejores abogados [SS 16 @0:05:05]. Chequeo de
honestidad: ¿usás humanos porque el trabajo necesita juicio o para tapar huecos del producto? [SS 16 @0:03:25].

---

## Cómo se hace: paso a paso (con guiones, plantillas y preguntas guía)

### P1. Decidir si contratar ahora
1. ¿Hay una necesidad desesperada que los fundadores no pueden cubrir? Si no, no contrates [HTSS 02 @0:08:07].
2. ¿Ya hay PMF o al menos la idea correcta? Antes de eso, los fundadores construyen [SS 09 @0:09:34] [SS 17 @0:15:24].
3. ¿Es un rol de ventas? Primero vendé vos y sabé cómo se ve lo bueno [SS 18 @0:03:47] [SS 18 @0:04:19].
4. ¿Sumaría un barril o más munición? Si no tenés barriles para dirigirla, no sumes munición [HTSS 14 @0:40:55].
5. ¿Lo podría hacer un agente o una herramienta propia? (visión 2025-2026: "token maxing" [SS 15 @0:08:23]; Kelsey de
   RR. HH. en Replit armó un organigrama conectado a ADP en 3 días [AISS 10 @0:17:18]).
6. ¿Escribiste los valores? Si no, escribilos antes (P10) [HTSS 10 @0:17:26].
7. Si contratás: entrás en modo contratación, prioridad 1, ~25% de tu tiempo, bloqueado en el calendario
   [HTSS 02 @0:11:22] [HTSS 14 @0:43:34].

### P2. Contratar a los primeros 10 (síntesis de HTSS 02 y HTSS 11)
1. Definí los 3 o 4 rasgos que valorás (ver Ejemplos: Pinterest y Stripe) [HTSS 11 @0:05:28] [HTSS 11 @0:10:28].
2. Buscá en todas partes y empezá por referidos (F3) [HTSS 11 @0:12:36] [HTSS 02 @0:13:30].
3. Apuntá a gente subvaluada o al inicio de su carrera (el diseñador de Stripe tenía 18 años y estaba en la secundaria
   en Suecia) [HTSS 11 @0:09:19].
4. Vendé la visión y contá los riesgos sin maquillaje [HTSS 11 @0:17:58].
5. Mejor que entrevistar: trabajar juntos en un proyecto de uno o dos días (Altman) [HTSS 02 @0:15:07]
   [HTSS 02 @0:15:40], idealmente una semana: "it's pretty hard to fake it for a week" (Patrick Collison, probable)
   [HTSS 11 @0:20:07] [HTSS 11 @0:20:39]. Stripe trajo al primer ingeniero en avión y programaron un fin de semana
   mirando por sobre su hombro [HTSS 11 @0:19:01]; para desarrollo de negocios, un proyecto sobre una alianza
   [HTSS 11 @0:19:35]. Wufoo, remoto: proyecto pago de ~1 mes, nada solo por entrevistas (Kevin Hale)
   [HTSS 07 @0:44:31].
6. Si entrevistás: preguntá por proyectos concretos que hizo, no acertijos [HTSS 02 @0:15:40]; entrevistá a tu manera,
   sin "cargo cult" de la pizarra (John Collison) [HTSS 11 @0:19:01].
7. Referencias que aprietan (P6) [HTSS 02 @0:16:12].
8. Pasá las tres preguntas, el animal test y "¿apostaría la empresa a esta contratación?" [HTSS 02 @0:12:26]
   [HTSS 02 @0:14:36] [HTSS 02 @0:17:16].
9. Equity generosa: ~10% para los primeros 10, en 4 años [HTSS 02 @0:18:20].
10. Onboarding con trabajo real el día 1 y feedback temprano (P12).

### P3. Sourcing y outreach (Paffenholz, SS 33)
**AEs** [SS 33 @0:10:16] [SS 33 @0:10:48] [SS 33 @0:11:20]:
1. Empresas de tu industria que vendan al mismo buyer persona y con tamaño de deal similar.
2. Señales de cumplimiento de cuota públicas en LinkedIn ("100% attainment in Q3", "140% for a full year"; ojo, los
   ciclos fiscales varían); señales consistentes: President's Club y ranking frente a otros AEs.
3. Promociones rápidas (SDR → AE → senior AE), mejor en la misma empresa y con el mismo jefe.
4. Experiencia en startup de ritmo rápido; más probable en Serie A a C que en pre-seed o seed.
**Ingenieros** [SS 33 @0:11:52] [SS 33 @0:12:23]:
1. Usá tus ventajas propias (Paffenholz es alemán: buscó alemanes que viven en la Bay Area).
2. Tecnologías específicas o contribuciones open source.
3. Gente que construyó proyectos propios parecidos a una startup, o que fue fundador.
4. Comunidades: Slack, open source, Discord (temáticamente relevante y auténtico para vos) [SS 33 @0:30:08].
5. No obvios en papel [SS 33 @0:31:11].
**Qué pitchear** [SS 33 @0:13:29] [SS 33 @0:14:02] [SS 33 @0:14:34]:
- AE: trayectoria (camino más rápido a enterprise, a manager, a VP de ventas); compensación alta si la empresa vende.
  Ejemplo: "el fundador ya cerró más de 400.000 dólares sin background de ventas" [SS 33 @0:24:16].
- Ingeniero: ownership, problemas difíciles que casi pueden elegir, equipo chico y autónomo; que escriba el fundador
  técnico (en Juicebox, Ishan, el CTO, hace todo el outreach de ingeniería) [SS 33 @0:15:06].
**La secuencia** [SS 33 @0:15:06] a [SS 33 @0:17:17]:
1. **Mail 1**: variables (nombre, empresa actual); legitimidad (clientes, momentum, crecimiento, ronda o prensa);
   corto, porque se lee en el celular; link de Calendly.
2. **Mail 2 (follow-up)**: agregar valor, otra razón por la que el rol es especial; volver a linkear el JD; call to
   action; y una salida: "Hey, it's not the right time for me".
3. **Paso 3, LinkedIn** (manual, por los términos de LinkedIn): conexión, referencia a los mensajes previos, link de
   agenda. Va tercero a propósito porque los dos primeros se automatizan.
4. **Mail final** (al menos uno): relinkear el JD, mencionar el mensaje de LinkedIn, o "My co-founder came across your
   profile again", "I just thought of another reason that this role could be a good fit for you", o algo de su
   background. Personalizar a mano pesa sobre todo acá.
Algunos clientes de Juicebox hacen 8 pasos [SS 33 @0:16:44].
**Canales**: default email (automatizable y medible); un solo mensaje responde mejor en LinkedIn o Twitter, pero la
secuencia de mails le gana; AEs responden más en LinkedIn, ingenieros por mail [SS 33 @0:34:26] [SS 33 @0:34:57]
[SS 33 @0:35:29].
**Para llegar a 40%+**: creatividad sobre a quién escribís (misma secundaria, empresa anterior en común) que se refleja
en el texto; ~5 minutos de personalización por mensaje; "no mil mails por día sin personalizar" (Harj)
[SS 33 @0:28:33] [SS 33 @0:29:05] [SS 33 @0:29:36].
**Hábito** [SS 33 @0:19:26] [SS 33 @0:19:58] [SS 33 @0:20:31]: 100 mails por semana programados de una vez (Paffenholz
los programa el domingo a la noche); meta de al menos 10 candidatos entrevistados por semana; si no llegás, subí a 150
o 200; todos los fundadores participan y el de agenda llena bloquea tiempo.
> **Hueco:** las plantillas de mail de SS 33 se muestran en pantalla y no se leen enteras [SS 33 @0:15:06].

### P4. Escribir el job description (Paffenholz y Harj)
1. Test: ¿te postularías vos leyéndolo? [SS 33 @0:07:34]
2. No corporativo ni "ChatGPT-written"; el estándar es bajo [SS 33 @0:36:02].
3. Corto: unos bullets de lo que importa [SS 33 @0:36:33].
4. 30% o más dedicado a por qué es un gran lugar para trabajar [SS 33 @0:36:33].
5. Opinionado: decí qué se sacrifica (Harj: "valoramos colaboración por encima de autonomía"); "I don't know if I've
   seen an example of something that's too opinionated" [SS 33 @0:37:04] [SS 33 @0:37:36]. Lo que importa es la tasa
   de interesados, no la de respuestas [SS 33 @0:38:10].
6. Misma voz que el resto de la empresa: la web de reclutamiento casi nunca tiene la calidad del funnel de conversión
   (Rabois) [HTSS 14 @0:38:15].

### P5. Entrevistas
**AE (Paffenholz)** [SS 33 @0:21:04] a [SS 33 @0:22:40]:
1. Ronda 1 (≈30 min o menos): **vender** (qué hacen, por qué te apasiona, visión, como un intro con inversor) y
   averiguar motivos: ¿por qué habla con vos? ¿con qué otras empresas? ¿está decidido por una startup?
2. Ronda 2 (evaluación): demo, de tu producto (si es PLG o fácil) o del de su empresa actual; vos hacés de cliente.
3. Final (on-site): muchos puntos de contacto (cafés con gente de go-to-market); en Juicebox, otro mock de demo con
   ambos cofundadores.
**SWE (Paffenholz)** [SS 33 @0:23:13] [SS 33 @0:23:44]:
1. Primera llamada: vender y averiguar motivaciones.
2. Case study: construir una web app en una llamada de 1 hora, diseñada para que no sea fácil hacer trampa.
3. Final on-site de casi un día (≈6 h): system design, proyecto sandbox, entrevista tradicional con cofundadores y algo
   casual (almuerzo, cafés).
**Ingenieros en la era de la IA (Hodak)**: nunca usaron LeetCode; evalúan menos programación y más pensamiento: "if we
give you a domain, how do you break it down? Can you understand the decomposition of the problem clearly?"; tarea
"AI-resistant" (F5) [SS26 06 @0:27:04] [SS26 06 @0:28:53]. Evidencia de capacidad excepcional: "some concrete fact" que
te separe de tu clase del secundario; idealmente ganar "legible competitive games" (ajedrez, Design Build Fly, Formula
SAE) [SS26 06 @0:26:16] [SS26 06 @0:27:04].
**Preguntas guía literales**:
- Altman: "Is this person smart? Do they get things done? Do I want to spend a lot of time around them?" (paráfrasis
  de sus tres preguntas) [HTSS 02 @0:14:36].
- Chesky: "If you had a year left to live would you take this job", luego cambiada a diez años porque con un año
  deberías estar con tu familia [HTSS 10 @0:21:46] [HTSS 10 @0:22:18]; "If you could hire anybody in the world would
  you hire the person sitting across from you" [HTSS 10 @0:29:31]; historias usando el producto y "would you bleed for
  the product" [HTSS 10 @0:21:46]; para el primer ingeniero, "do I want to work with one hundred or a thousand more
  people like this" [HTSS 10 @0:18:32].
- Hodak: juicio ("will you tend to make good decisions or will you create diplomatic incidents?") y agencia ("how does
  your life look or not like whatever ambitions you had? ... do you have specific ambitions for your life?")
  [SS26 06 @0:12:59].
- Altman (AISS): "what's the most impressive stuff you've done?" antes que el CV [AISS 03 @0:31:18].
- Silbermann (referencia anticipada, ver P6).
**Entrevistas de valores** separadas, hechas por gente de otra área para no sesgarse (Airbnb) [HTSS 10 @0:29:31].
**Contratar en un área que no conocés (Silbermann)** [HTSS 11 @0:16:22] a [HTSS 11 @0:17:26]: (1) hablá con gente "de
facto world class" en esa disciplina; (2) preguntales rasgos clave, preguntas que hacen, cómo los encuentran y "where is
that person working right now and what's her phone number"; (3) recién después entrevistá ("pre-calibration of that
really matters"); (4) armá un set de preguntas estándar que rota y medí si son buenos indicadores; (5) contale al
candidato qué será fácil y qué difícil. Scholl agrega la regla de Boom: si alguien ya lo hizo en el mundo, "you have to
go find one of those people, call them and ask them your advice. And you don't have to take it" [SS26 12 @0:43:18].
**Consenso**: contratar con todos en una sala funciona hasta ~15 personas (Susan Kare) [SS26 03 @0:48:20]; después,
votación estructurada (Hodak, F5).

### P6. Guion de referencias
- Al candidato, en la entrevista (Silbermann): "We both know [X] in common. I'm going to talk to him in a couple weeks.
  If I asked him what you're the best at, what you'd be most proud of, or what you were working to improve, what would
  he or she say?" Prueba autoconciencia y crea responsabilidad social [HTSS 11 @0:22:49].
- A la referencia (Altman): "Is this person in the top 5% of people you've ever worked with? What specifically did they
  do? Would you hire them again? Why aren't you trying to hire them again?"; "you really have to press on these
  reference calls" [HTSS 02 @0:16:12].
- A la referencia (Silbermann): "do you think this is the top 1% of people you've ever worked with, the top 5%, the
  top 10%"; fuerza escasez y da una referencia "materially different" [HTSS 11 @0:22:49] [HTSS 11 @0:23:21].
- John Collison: "where would you rank this person amongst the people you've worked with in this role"; apuntá a 15
  minutos; no dejes que digan "es genial" y corten; al final pedí nombres de otros candidatos [HTSS 11 @0:23:21]
  [HTSS 11 @0:23:54].
- Hoffman pregunta por adaptabilidad, "infinite learning curve" y problemas de ego [HTSS 13 @0:34:16]. Rabois:
  referencias contradictorias de un gerente ("microgestiona" / "me da responsabilidad") son buena señal
  [HTSS 14 @0:10:40].
- Altman: las referencias son lo que los fundadores más se saltean [HTSS 02 @0:15:40] [HTSS 02 @0:16:12].

### P7. Oferta y cierre (Paffenholz)
1. Movete en 7 a 14 días; big tech y growth stage son más lentos [SS 33 @0:24:49].
2. Sabé y comunicá el próximo paso; agendalo apenas tengas confianza [SS 33 @0:25:21].
3. Personalizá la oferta con los argumentos que le importan a ese candidato [SS 33 @0:25:21].
4. Pedí a otro fundador o a un inversor (por ejemplo un ángel) que le escriba reforzando la misma razón
   [SS 33 @0:25:54].
5. Si no sale la primera oferta, la próxima [SS 33 @0:25:54].
6. Cuánto pelear: como en enterprise, entendé qué quiere de verdad. Si quiere big tech por compensación o estabilidad,
   no pelees ni prometas estabilidad u horarios que no tenés; si confirmó varias veces que quiere startup, peleá duro
   contra la otra empresa. Harj: disciplina para soltar aunque estés atrasado y desesperado [SS 33 @0:38:42]
   [SS 33 @0:39:14].
7. Si dice que no, seguí la relación: los fundadores elite contrataron a alguien tras dos años de cafés
   [SS 33 @0:39:47] [SS 33 @0:40:19].
8. Pinterest y PayPal como ejemplos de pitch honesto: "Visa y MasterCard nos quieren matar y quizás hacemos algo
   ilegal, pero si salimos bien vas a redefinir los pagos" [HTSS 11 @0:17:58].

### P8. Contratar un empleado: lo legal mínimo (Nathoo, EE. UU., 2014)
1. Definí si es empleado o contratista (F13) [HTSS 18 @0:35:44].
2. Firmá la asignación de IP en el formato correcto; "If the company does not own that IP, there is no value in the
   company" [HTSS 18 @0:36:20] [HTSS 18 @0:43:31].
3. Pagá al menos el salario mínimo (en San Francisco ~2.000 dólares por mes entonces) [HTSS 18 @0:37:59].
4. Contratá workers' compensation insurance (Nueva York amenaza con multas de 50.000 dólares por no pagar 20 dólares
   por mes) [HTSS 18 @0:38:31].
5. Verificá que esté autorizado a trabajar en EE. UU. [HTSS 18 @0:38:31] [HTSS 18 @0:39:03].
6. "You absolutely must use a payroll service provider" (ZenPayroll, hoy Gusto); una compañía de YC no pagó payroll
   taxes durante 3 años: desastre caro, en casos extremos cárcel [HTSS 18 @0:32:58] [HTSS 18 @0:39:03].
> **Hueco:** los videos solo cubren ley de EE. UU. de 2014. Nada sobre contratar en Colombia u otros países, EOR, ni
> contratistas internacionales.

### P9. Equity para empleados
1. Temprano: ~10% para los primeros 10, vesting 4 años con cliff de 1 [HTSS 02 @0:18:20] [HTSS 02 @0:26:26].
2. Después: presupuestá 3 a 5% por año durante 10 años; refresher grants; elegí estructura (F9) [HTSS 19 @0:11:30]
   [HTSS 19 @0:12:03].
3. Software de gestión de opciones, no Excel [HTSS 19 @0:12:36].
4. Explicá al contratar la ventana para ejercer (90 días estándar en 2014) y decidí tu política como declaración
   cultural (F20, caso 3) [HTSS 15 @0:21:28] [HTSS 15 @0:24:46].
5. No hagas caso a inversores que pelean cada grant [HTSS 19 @0:10:59]; Altman pelea para darles menos a inversores y
   más a empleados [HTSS 02 @0:19:26].
6. Dilución anual por opciones en Silicon Valley: 6 a 8%, hasta 10% (Horowitz) [HTSS 15 @0:22:32] [HTSS 15 @0:23:06].

### P10. Escribir y usar los valores (Lin y Chesky)
1. Seguí F12 y bajá cada valor a un párrafo [HTSS 10 @0:05:27].
2. Escribilos antes de contratar a nadie (Airbnb los trabajó 6 a 7 meses desde enero de 2009) [HTSS 10 @0:17:26]
   [HTSS 10 @0:17:59].
3. Usalos para contratar y despedir; entrevistas de valores de otra área [HTSS 10 @0:28:58] [HTSS 10 @0:29:31].
4. Usá artefactos de la historia fundacional (Chesky saca una caja de cereal cuando alguien no es frugal o creativo)
   [HTSS 10 @0:26:42].
5. Repetí la visión en cada interacción: contratación, inversores, prensa, clases, emails a clientes [HTSS 10 @0:37:10].
6. Llevá la cultura a las evaluaciones de desempeño [HTSS 10 @0:09:49].
7. Extendé los valores a los partners (Superhost, convención de anfitriones) [HTSS 10 @0:38:47].
8. Un valor con filo autoselecciona: los de Legora son LFG (Lean in, Fight for excellence, Grow together, "Let's
   fucking go"); la grosería le dice rápido a un líder de entorno establecido "de qué se trata esto" [SS26 01 @0:19:15]
   [SS26 01 @0:20:00].
9. Cuando se pierde la alineación, escribí todo lo aprendido en un documento simple y compartilo (el "Product Manifesto"
   de Legora para 25 personas, que reemplazó la votación democrática de features: "too many chefs in the kitchen")
   [SS26 01 @0:15:16] [SS26 01 @0:15:55].

### P11. Contratar a escala (Altman, HTSS 19)
1. Recruiter full time cuando las cosas funcionan [HTSS 19 @0:13:40].
2. Anunciá cada oferta en una lista interna antes de hacerla, hasta los 300-400 empleados: "half the time" alguien sabe
   algo bueno o malo [HTSS 19 @0:14:13].
3. Programa de ramp-up: qué pasa la primera semana, cómo aprende todo, un buddy [HTSS 19 @0:14:13].
4. Hablá con los primeros 10 o 15 empleados sobre su camino: "sit them down and say I want to talk about … where you
   want to see your career go inside of this company"; no le des al primer ingeniero el puesto de VP solo por ser el
   primero, ni lo pierdas por no hablarlo [HTSS 19 @0:15:49] [HTSS 19 @0:16:20].
5. Junestrand: hasta ~500 personas entrevistó a todos los candidatos fuera de ingeniería; hoy de director para arriba,
   "y la cultura se encarga del resto"; onboarding de todos en Estocolmo para crear la misma vibra en cada oficina
   [SS26 01 @0:18:32] [SS26 01 @0:19:15] [SS26 01 @0:23:43].
6. Silbermann: dar oportunidades de liderazgo a la mayor cantidad posible, con vuelta atrás sin estigma a contribuidor
   individual; contratar de afuera solo donde la curva de aprendizaje es demasiado grande [HTSS 11 @0:40:12]
   [HTSS 11 @0:41:18]. Scholl: en cargos senior, promover desde adentro, gente que creció en tu cultura
   [SS26 12 @0:27:22]. PayPal: promové al mejor de cada disciplina y que aprenda a gestionar después; nadie se
   desmoraliza porque su jefe es mejor que él en su trabajo [HTSS 14 @0:36:05] [HTSS 14 @0:36:37].

### P12. Onboarding
1. Trabajo real rápido: ingenieros haciendo commit el primer día, gente de negocio en reuniones reales el primer día;
   Stripe es de la escuela "push people off the cliff" (John Collison, probable) [HTSS 11 @0:26:36] [HTSS 11 @0:27:08].
2. Feedback pronto, sobre todo de adaptación a la cultura [HTSS 11 @0:27:08] [HTSS 11 @0:28:12].
3. Pinterest al escalar: medir la experiencia desde el primer contacto hasta 30 días después (¿conoce el nombre de
   alguien?, ¿sabe quién es su jefe?, ¿se sentó con su equipo?, ¿conoce la arquitectura y las prioridades?); programa
   de una semana más programas por función; preguntar al nuevo al terminar y a los 30 días, y a pares y jefe. Si no
   está al día, "that team shouldn't be hiring any more people" [HTSS 11 @0:25:30] [HTSS 11 @0:26:03].
4. Conocer a la persona como persona: aspiraciones, estilo, cómo le gusta que la reconozcan, si es de mañana o de noche
   [HTSS 11 @0:26:36].
5. Recordar a dónde se quiere llegar: "someday we want to do for discovery what Google did for search"
   [HTSS 11 @0:24:58].
6. Buddy y ramp-up (Altman) [HTSS 19 @0:14:13].

### P13. Montar una estructura de management simple (Altman, hacia las 25 personas)
1. Cada empleado, exactamente un jefe conocido. 2. Cada jefe sabe quiénes le reportan. 3. Equipos con sentido.
4. Que se sepa cómo cambiar la estructura o contratar. 5. Nada de matrices circulares [HTSS 19 @0:01:40]
[HTSS 19 @0:02:12] [HTSS 19 @0:02:45].
6. Escribí el cómo y el porqué (la cultura) [HTSS 19 @0:07:41].
7. Sumá las piezas de HR (F7) y los ritmos (F8).
8. Test de alineación: preguntá a 10 empleados al azar cuáles son las tres metas principales. "100% of the time" el
   fundador dice que las saben y "100% of the time" no hay dos que coincidan en orden [HTSS 19 @0:17:24]
   [HTSS 19 @0:17:57].
9. Fundador técnico: con 2 a 5 personas todavía ~70% de tiempo programando; con 5 a 10, menos del 50%; con más de 10,
   probablemente nada: decidir si ser arquitecto o rol de gente (VP de ingeniería) (Diana Hu) [SS 09 @0:26:14]
   [SS 09 @0:26:47].

### P14. Pasar de contribuidor a manager y auditar tu tiempo (Rabois)
1. Auditoría de calendario de un mes: cuánto editás vs cuánto escribís [HTSS 14 @0:37:10].
2. Mentor que no sea tu jefe [HTSS 14 @0:37:42].
3. Para CEOs: escribí tus prioridades en papel, abrí el calendario y sumá horas a mano: "it never matches, like
   never"; reclutamiento es la que más falla [HTSS 14 @0:43:34] [HTSS 14 @0:44:05] [HTSS 14 @0:44:37].
4. La credibilidad del manager nuevo viene de ser excelente en su disciplina; no se aprende a gestionar leyendo, como no
   se aprende guitarra con un libro [HTSS 14 @0:36:05] [HTSS 14 @0:37:10]. El único libro que lo explica: *High Output
   Management* de Andy Grove [HTSS 14 @0:01:37].

### P15. Aumentos con proceso formal (Horowitz)
1. Cualquiera puede venir a contar su caso; no se le da en el momento [HTSS 15 @0:13:48].
2. Se habla con toda la gente con la que trabaja y se evalúa todo su trabajo [HTSS 15 @0:13:48].
3. Ciclo periódico (cada seis meses, o trimestral si la empresa se mueve rápido) [HTSS 15 @0:13:48] [HTSS 15 @0:14:19].
4. Se comunica si hay aumento y cuánto; nada fuera de ciclo [HTSS 15 @0:14:19].
5. Después del ciclo: "I'm not hearing it" [HTSS 15 @0:14:51].
Para qué: nadie tiene que estar en guardia ni temer quedar afuera por no ser amigo del jefe [HTSS 15 @0:15:23].
Transparencia de compensación por bandas (Rabois): todos igual, por disciplina o por experiencia; NeXT usaba dos bandas
(~85.000 y ~130.000 dólares traducidos a 2014) [HTSS 14 @0:32:49].

### P16. Evaluar desempeño
- Altman: feedback frecuente, simple, atado a salida o a compensación [HTSS 19 @0:09:22] [HTSS 19 @0:09:56].
- Hodak (eigenreviews) [SS26 06 @0:16:12] a [SS26 06 @0:18:04]: (1) cada 4 a 6 semanas se pregunta a colegas: "knowing
  how this person turned out, would you vote again today for their hire?"; (2) grafo de toda la empresa donde "your
  vote should be weighted more highly if everybody else has rated you highly"; (3) peso tipo centralidad de vector
  propio (como PageRank); (4) dropout de 1.000 iteraciones para detectar camarillas; (5) actualización casi continua con
  un mes de retraso; no es la única señal [SS26 06 @0:42:34]. Crítica a la 360 anual: disruptiva, no revela nada nuevo
  y refuerza lo que ya sabías y no actuaste porque despedir cuesta [SS26 06 @0:15:34] [SS26 06 @0:16:12]. La
  retroalimentación del mercado sobre tu contratación es "a very poorly behaved loss function"; la gerencia diseña
  "synthetic gradients" para saber antes [SS26 06 @0:15:34].
- Lin: llevar la cultura a las evaluaciones [HTSS 10 @0:09:49]. Rabois: nota anti empire building [HTSS 14 @0:41:28].

### P17. Despedir
**Criterio (Altman)**: ver Principios G2 [HTSS 02 @0:23:44].
**Cinco prácticas (Levy)** [HTSS 18 @0:40:43] a [HTSS 18 @0:41:47]:
1. Despedí rápido.
2. Comunicá con claridad, sin racionalizar ni pedir perdón: "We're letting you go. Not I'm so sorry, sales didn't take
   off this quarter"; cara a cara y, si se puede, con un tercero presente.
3. Pagá salarios y vacaciones acumuladas de inmediato (requisito legal).
4. Cortá accesos físicos y digitales, cambiá contraseñas (caso: un fundador al que querían echar retuvo la contraseña de
   GitHub).
5. Recomprá las acciones no consolidadas enseguida.
**Conversación (Horowitz)** [HTSS 15 @0:37:29] a [HTSS 15 @0:39:42]:
1. Con la persona: honesto; ni "you just suck" ni el "it's not you, it's me" meloso.
2. Empezá por lo real: "here's how we are and here's what I didn't recognize about us and about you".
3. Con la empresa: agradecé su trabajo, avisá que sigue su camino, no expliques detalles personales, preservá su
   dignidad; todos van a recibir llamadas de referencia sobre esa persona.
**Al cerrar la empresa (Altman)**: avisá temprano a inversores, no te quedes totalmente sin plata, ayudá a los
empleados a conseguir trabajo y pagá 2 a 4 semanas de indemnización [HTSS 19 @0:39:21] [HTSS 19 @0:39:54].
**Fundadores**: el CEO tiene que poder despedir fundadores (ver capítulo 02) [SS 07 @0:05:32] [SS 07 @0:06:05]; en una
ruptura con salarios impagos, el fundador despedido los usa como palanca para pedir aceleración de vesting
[HTSS 18 @0:34:03] [HTSS 18 @0:34:38].

### P18. Salir del hero mode y anticiparse (Altman)
1. Aceptá el costo: "we're going to get behind on tickets for two or 3 weeks" [HTSS 19 @0:04:57].
2. Contratá (por ejemplo tres personas de soporte) [HTSS 19 @0:05:29].
3. Calculá con la tasa de crecimiento cuánto dura y anticipate la próxima vez [HTSS 19 @0:05:29].

### P19. Recuperar el momentum del equipo (Altman)
1. No con discursos de visión: con victorias chicas [HTSS 02 @0:42:40].
2. Buscá dónde están (ventas) [HTSS 02 @0:43:13].
3. Si hay peleas, preguntá a los usuarios y hacé lo que digan; nombrá el problema: "Hey, stuff's not working right now.
   We don't actually hate each other. We just need to get back on track" [HTSS 02 @0:43:13] [HTSS 02 @0:43:45].
4. Ritmo operativo: lanzamientos regulares, métricas semanales con toda la empresa [HTSS 02 @0:44:16].

### P20. Montar la infraestructura interna (Hodak, empresa que no es solo software)
1. El problema no es cómo compra el fundador sino "how does your 17th employee buy things?" [SS26 06 @0:03:48].
2. Presupuestos antes que aprobación de cada compra: "Spending review has to come earlier" [SS26 06 @0:04:24]
   [SS26 06 @0:04:59].
3. Sistema de compras con personas cuyo trabajo es comprar y con métricas de velocidad [SS26 06 @0:04:59].
4. Atribución de costos: cuánto cuesta cada experimento; si nadie lo sabe, "experiments are free" (el equipo cree que
   "the $3,000 power supplies are free" después de una ronda grande) [SS26 06 @0:06:51] [SS26 06 @0:08:38].
5. Todo en un solo software propio (Helix); con vibe coding ya es barato construirlo [SS26 06 @0:07:27]
   [SS26 06 @0:37:29].

### P21. Cultura remota (Kevin Hale, Wufoo, 2014)
Semana de 4,5 días (viernes medio día para reuniones); un día de soporte por persona y tres protegidos para construir;
regla de 15 minutos para cualquier conversación, lo que no se resuelve va al viernes (el 90% nunca volvía); lista de
tareas en texto plano por persona en Dropbox, revisada el viernes; reparto de utilidades por desempeño; contratación
con proyecto pago de un mes y carta de ruptura escrita a mano en 15 minutos para medir tacto (90% del soporte es dar
malas noticias); todos hacen soporte, incluidos ingenieros y diseñadores; "King for a day": un sorteo da a una persona
48 horas de todos los recursos para construir lo que quiera, 1 o 2 veces por año [HTSS 07 @0:17:09]
[HTSS 07 @0:38:10] a [HTSS 07 @0:45:08]. Nunca tuvo que despedir a nadie [HTSS 07 @0:43:54]. Altman es escéptico de
los equipos remotos en general, y desaconseja cofundadores en ciudades distintas: "Don't do it" [HTSS 02 @0:28:02]
[HTSS 02 @0:28:34].

---

## Números y benchmarks

**Contratación**
| Número | Qué | Fuente |
|---|---|---|
| 0% o 25% | Tiempo del fundador en contratar (nunca 50%) | [HTSS 02 @0:11:22] [HTSS 14 @0:43:34] |
| 5 meses; 2 en el primer año | Airbnb hasta el primer empleado; contrataciones del primer año | [HTSS 02 @0:08:38] |
| 4-5 meses, miles de perfiles, cientos de entrevistas | Búsqueda del primer ingeniero de Airbnb | [HTSS 10 @0:17:26] |
| 300 | Empleados que entrevistó Chesky personalmente | [HTSS 10 @0:21:46] |
| ~500 | Hasta ahí Junestrand entrevistó a todos los no ingenieros | [SS26 01 @0:18:32] |
| 1 año | Lo que puede tomar reclutar a alguien muy bueno | [HTSS 02 @0:10:18] |
| > 1 mes | Encontrar a alguien bueno contratando desconocidos | [SS 09 @0:09:34] |
| primeros 5 | Un mediocre ahí a menudo mata la startup | [HTSS 02 @0:11:54] |
| 10 → 100; primeros 50 | Cada uno de los primeros 10 trae 10; la cultura la definen los primeros 10 y quizás 40 más | [HTSS 11 @0:04:25] [SS 33 @0:01:07] |
| ~40-50 | Primeros empleados de Airbnb que sienten que fueron parte de la fundación | [HTSS 02 @0:09:45] |
| 100 personas | Las grandes tech contrataron por referidos al menos hasta ahí | [HTSS 02 @0:13:30] |
| 10.000-20.000 USD+ | Bono por referido | [SS 33 @0:07:02] |
| 10-20% bien; 40%+ excelente | Tasa de respuesta de outreach | [SS 33 @0:18:21] |
| 10-18%; SWE ≈11% | Respuesta real de Juicebox según rol | [SS 33 @0:17:50] [SS 33 @0:18:21] |
| AE 9%, SWE 7%, community 11% | Tasa de interesados de Juicebox | [SS 33 @0:18:21] [SS 33 @0:18:52] |
| 100 mails/semana; 10 entrevistas/semana | Ritmo de sourcing (subir a 150-200 si no llegás) | [SS 33 @0:19:26] [SS 33 @0:19:58] |
| ~5 min | Personalización por mensaje para llegar a 40% | [SS 33 @0:28:33] |
| 20 o 5 interesados | Por contratación, según el rol | [SS 33 @0:37:36] [SS 33 @0:38:10] |
| 7-14 días | Proceso total recomendado | [SS 33 @0:24:49] |
| ≤30 min; 1 h; ~6 h | Primera entrevista AE; case study SWE; final SWE | [SS 33 @0:21:04] [SS 33 @0:23:13] [SS 33 @0:23:44] |
| 30%+ | Parte del JD que vende la empresa | [SS 33 @0:36:33] |
| 20-25%+; 50.000 USD+ | Reclutador por contingencia | [SS 33 @0:41:56] |
| 1 por fundador | Búsquedas en paralelo | [SS 33 @0:42:28] |
| 17%; 50%; ≥25% | Embudo de Science: aplicación → llamada → homework → oferta | [SS26 06 @0:12:22] [SS26 06 @0:12:59] [SS26 06 @0:14:16] |
| 7-8 votantes; 24-48 h | Votación de candidatos en Science | [SS26 06 @0:11:43] [SS26 06 @0:12:22] |
| ~15 personas | Límite de la contratación por consenso | [SS26 03 @0:48:20] |
| 15 min | Llamada de referencia | [HTSS 11 @0:23:54] |
| top 1/5/10% | Escala de la pregunta de referencia | [HTSS 11 @0:22:49] [HTSS 02 @0:16:12] |
| 20+ h | Con un finalista a CEO (o cofundador) antes de decidir | [HTSS 13 @0:47:45] |
| empleado 14-15 | Primera reclutadora de Pinterest | [HTSS 11 @0:30:23] |
| 300-400 | Hasta ahí anunciar cada oferta internamente | [HTSS 19 @0:14:13] |
| 15-20 | Primeros ingenieros todos hombres: error típico | [HTSS 19 @0:14:45] |
| ~1 M USD ARR | Primer vendedor en Algolia | [SS 17 @0:21:57] |
| Serie A | Dev advocates dedicados (Algolia) | [SS 17 @0:30:07] |
| cientos de empleados | Equipo de soporte dedicado en Algolia | [SS 17 @0:28:30] |
| 5:1 | ARR nuevo / compensación total del vendedor | [SS 24 @0:11:28] |

**Equity y compensación**
| Número | Qué | Fuente |
|---|---|---|
| 10% / 10 empleados / 4 años | Guía de equity temprana | [HTSS 02 @0:18:20] |
| 3-5% por año, 10 años | Equity a empleados en la etapa posterior | [HTSS 19 @0:11:30] |
| 4 años, cliff 1 año, 25% | Vesting estándar | [HTSS 02 @0:26:26] [HTSS 18 @0:14:18] |
| 6 años | Grants preferidos de Altman | [HTSS 19 @0:12:03] |
| 6-8%, hasta 10% | Dilución anual por opciones | [HTSS 15 @0:22:32] |
| ~10% | Rotación anual promedio (más en SF) | [HTSS 15 @0:22:32] |
| 1,5% vs 0,1-0,2% | Equity de un ejecutivo vs ingenieros (caso Horowitz) | [HTSS 15 @0:06:31] [HTSS 15 @0:07:03] |
| 90 días vs 10 años | Ventana para ejercer opciones (estándar vs propuesta de D'Angelo) | [HTSS 15 @0:16:28] [HTSS 15 @0:16:58] |
| 6 meses o trimestral | Ciclo de aumentos | [HTSS 15 @0:14:19] |
| 2 bandas | Compensación transparente de NeXT (~85.000 y ~130.000 USD) | [HTSS 14 @0:32:49] |
| decenas de millones | Lo que costaron errores en planillas de opciones | [HTSS 19 @0:12:36] |
| 2-4 semanas | Indemnización al cerrar | [HTSS 19 @0:39:54] |

**Gestión y escala**
| Número | Qué | Fuente |
|---|---|---|
| 20-25 personas; 12-24 meses | Donde todo plano deja de funcionar; ventana de la transición | [HTSS 19 @0:00:34] [HTSS 19 @0:01:07] |
| cuadrado de empleados | Cómo cae la productividad sin alineación | [HTSS 19 @0:16:20] |
| 10 al azar, 3 metas | Test de alineación | [HTSS 19 @0:17:24] |
| 50 empleados | Cambian reglas de HR | [HTSS 19 @0:13:08] |
| 5-7 | Reportes directos | [HTSS 14 @0:39:18] |
| cada 1-2 semanas, nunca > 1 mes | One-on-ones | [HTSS 14 @0:39:18] |
| 1 cada 10-20 | Barriles por munición en ingeniería | [HTSS 14 @0:40:55] |
| 30-50% | Mejora por cada paso eliminado (Grove) | [HTSS 14 @0:05:52] |
| ~100% | Empleados que deberían usar el dashboard cada día | [HTSS 14 @0:21:32] |
| 70% / < 50% / ~0% | Tiempo de código del fundador técnico con 2-5, 5-10 y > 10 personas | [SS 09 @0:26:14] |
| ~2 h más por día | Jornada real de un empleado de startup (Patrick Collison) | [HTSS 11 @0:45:11] |
| 2x-3x por año | Crecimiento de plantilla, "very unnatural" | [HTSS 11 @0:33:07] |
| ~50 | Personas en las que la transparencia por email de Stripe empezó a costar | [HTSS 11 @0:35:51] |
| 1:4-7 → 1:0,5 | PM por ingenieros histórico y lo que le propuso un equipo a Ng | [AISS 04 @0:16:58] [AISS 04 @0:17:38] |
| ~50% | Del burn de un Series A que es headcount (USD 20 M, 20 personas, ~USD 3 M al año) | [SS26 06 @0:08:02] [SS26 06 @0:08:38] |
| 15 personas / USD 15 M | Emergent al pasar ese ingreso anualizado | [SS26 07 @0:22:31] |
| 3 → 750+ personas | Legora; de 200 a 1.300 en un año (Vanta tardó cuatro) | [SS26 01 @0:02:24] [SS26 01 @0:55:42] |
| 50 personas | Equipo que construyó el XB-1 de Boom | [SS26 12 @0:11:43] |
| < 10 personas | Cursor a fines de 2023 | [AISS 14 @0:23:29] |

---

## Ejemplos y casos (empresa → qué hizo → lección)

- **Airbnb** → escribió los valores antes de contratar, tardó 5 meses en el primer empleado, Chesky entrevistó a los
  primeros 300, preguntaba si tomarían el trabajo con un año (luego diez) de vida; en una crisis temprana todos
  vivieron en la oficina lanzando producto cada día → la cultura se planta antes del primer empleado
  [HTSS 02 @0:08:38] [HTSS 02 @0:09:45] [HTSS 10 @0:17:26] [HTSS 10 @0:21:46].
- **Airbnb y el clon de los Samwer (Wimdu, 2011)** → con 40 empleados y USD 7 M levantados frente a un clon con USD 90 M
  que contrató 400 personas en 30 días, decidieron no comprarlo por cultura (misioneros vs mercenarios): "the best
  revenge ... was just to make them run the company long term"; hoy Europa es más del 50% de sus ingresos → la cultura
  sirve para decisiones difíciles [HTSS 10 @0:30:36] a [HTSS 10 @0:32:15].
- **Airbnb, valores "Champion the mission" y "Be a cereal entrepreneur"** → Sebastian, anfitrión de Londres, recibió
  llamadas de siete huéspedes antes que de su madre en los disturbios; las Obama O's financiaron la empresa → las
  historias de fundación se vuelven valores [HTSS 10 @0:19:04] a [HTSS 10 @0:26:42].
- **Zappos** → 37 valores propuestos por empleados reducidos a 10 en un año, escritos con ~100 empleados; Tony Hsieh
  lamentó no haberlo hecho antes; "Deliver WOW through service", "Be humble"; "Company first, then your department, then
  your team, then yourself" → escribí los valores temprano [HTSS 10 @0:05:27] a [HTSS 10 @0:08:11]
  [HTSS 10 @0:17:26].
- **Stripe, primeros 10** → buscaban genuinos y directos, que terminan cosas, a los que les importa muchísimo; el
  diseñador tenía 18 años y estaba en la secundaria en Suecia; reclutaban en Coupa Café; el segundo empleado fue
  sacado a cenar por sus amigos para disuadirlo y entró igual → contra eso competís al principio
  [HTSS 11 @0:07:38] [HTSS 11 @0:09:19] [HTSS 11 @0:10:59] [HTSS 11 @0:13:08].
- **Stripe, cuidado obsesivo** → cada error de API llegaba a todos y los llamaba por teléfono; copiaban a todos en cada
  email saliente; Patrick admite que "probably shouldn't have done them" → el detalle es cultura, con costo
  [HTSS 11 @0:11:32] [HTSS 11 @0:12:04].
- **Stripe, transparencia** → BCC de todo email, listas de correo, filtros de Gmail generados por un programa, Hackpad
  público, "spin-ups" de 30 minutos de cada líder; normas sobre qué es confidencial y cuándo meterse, porque con 170
  personas leyendo es fácil "get stage fright"; Emily, pasante: ~2.000 emails la primera semana, "net good"
  [HTSS 11 @0:35:20] a [HTSS 11 @0:38:33].
- **Pinterest** → primeros empleados con oficina horrible y sin sueldo, solo por las razones más puras; rasgos:
  trabajadores, alta integridad, bajo ego, creativos "quirky" ("excited about many disciplines and extraordinary at
  one"), ambiciosos sin arrogancia; reclutadora profesional como persona 14-15; equipos como "startup de muchas
  startups" [HTSS 11 @0:05:28] a [HTSS 11 @0:07:05] [HTSS 11 @0:28:47] [HTSS 11 @0:30:23].
- **PayPal (Rabois)** → Thiel exigía una sola cosa por persona y todos se rebelaron; los VP eran los mejores en su
  disciplina, sin general managers → foco y respeto técnico [HTSS 14 @0:19:22] [HTSS 14 @0:36:05].
- **Square** → smoothies a las 9 pm para el 20-30% que se quedaba de noche: meses de fracaso hasta que un pasante lo
  resolvió en una noche → expandí el alcance hasta que se rompa y promové a quien lo supera [HTSS 14 @0:16:07]
  [HTSS 14 @0:16:40] [HTSS 14 @0:17:12].
- **Bill Walsh y los 49ers** → tomó el peor equipo (2 y 14), escribió un memo de tres páginas para que la recepcionista
  atendiera el teléfono, ganó tres Super Bowls en 10 años → detalles [HTSS 14 @0:29:01] [HTSS 14 @0:29:34].
- **Roelof Botha (Sequoia) y YouTube** → "every time I go to one of my portfolio companies half the office is watching
  YouTube at lunch": buena señal; Rabois a veces decide al entrar a una oficina si invierte [HTSS 14 @0:35:00]
  [HTSS 14 @0:35:32].
- **Horowitz y el ejecutivo de ventas** → trabajaba de 6 a 22 pero no tenía el conocimiento; degradarlo con 1,5% de
  equity frente a ingenieros con 0,1% habría definido mal qué es fallar → pensá en los que no están en la sala
  [HTSS 15 @0:03:19] [HTSS 15 @0:05:59].
- **Sam Altman y las opciones a 10 años** → Horowitz explicó por qué existía la regla de 90 días (APB 25 hasta 2004) y
  Sam revisó en la sala su recomendación: "I'm actually revising my recommendation slightly" → la política de equity
  es una declaración cultural [HTSS 15 @0:18:42] [HTSS 15 @0:25:55].
- **Loopt (Altman)** → iban a perder su primer gran cliente; tomaron un avión, estaban a las 6 am en la oficina,
  rompieron el contrato con el competidor y cerraron una semana después: "Get on planes in marginal situations"
  [HTSS 02 @0:40:00] [HTSS 02 @0:40:31].
- **Fundador que rotó su equipo varias veces** → aprendió que "you shouldn't tell your employees they're [screwing] up
  every day unless you'd like them all to leave because they will" [HTSS 02 @0:20:31].
- **Batch de YC con cofundadores random** → 9 de ~75 sumaron uno entre la entrevista y el inicio; los 9 se desarmaron
  al año siguiente (ver capítulo 02) [HTSS 02 @0:03:47].
- **Juicebox** → primera contratación por Work at a Startup; Paffenholz buscó alemanes en la Bay Area; el CTO hace todo
  el outreach de ingeniería; intentaron llevar más de dos búsquedas a la vez y volvieron a una por cofundador; las
  primeras búsquedas tardaron más de un mes [SS 33 @0:07:02] [SS 33 @0:11:52] [SS 33 @0:15:06] [SS 33 @0:43:00].
- **Candidato que rechazó por estabilidad y entró 6 meses después**; **fundadores elite que contrataron tras dos años
  de cafés** → contratar es un juego repetido [SS 33 @0:39:47] [SS 33 @0:40:19].
- **Legora (Junestrand)** → desaprendió los "Y-intercepts"; su mejor vendedor tiene 23 años, vendió más de 10 M USD sin
  experiencia en ventas; valores LFG; onboarding de todos en Estocolmo; "blood smoke" ("seguimos dándole"); frenó ventas
  6 meses y alineó a 25 personas con un manifiesto; dejó de votar features → contratar por pendiente y alinear por
  escrito [SS26 01 @0:15:16] a [SS26 01 @0:23:43].
- **Legora y la ley de Jante** → la humildad sueca ayuda a que ganen las mejores ideas, pero "it's very hard to build one
  of the fastest growing enterprise companies in the world. If you think that you aren't somebody" [SS26 01 @0:20:34]
  [SS26 01 @0:21:09].
- **Science (Hodak)** → proceso de contratación propio con votación, homework resistente a IA, eigenreviews y Helix
  (todo es "a button somewhere in the software"); cultura de dos mitades (~30% transhumanistas, 70% clínicos y
  científicos; SpaceX hace 7-8 años: ~20% colonos marcianos y 80% ingenieros serios) → la infraestructura es velocidad
  [SS26 06 @0:07:27] [SS26 06 @0:52:04] [SS26 06 @0:52:41].
- **Boom (Scholl)** → 50 personas construyeron el XB-1; contrata talento joven, ambicioso, práctico, optimista, "not yet
  been destroyed" por la industria aeroespacial; promueve desde adentro; regla de llamar a quien ya lo hizo
  [SS26 12 @0:11:43] [SS26 12 @0:25:53] [SS26 12 @0:27:22] [SS26 12 @0:43:18].
- **Cursor (Truell)** → cuatro fundadores ingenieros, menos de 10 personas a fines de 2023, "missteps" con los
  primeros, contrataron menos de lo debido [AISS 14 @0:23:29] [AISS 14 @0:24:01].
- **Figma (Field)** → "I should have scaled the team faster" [AISS 17 @0:09:14].
- **Andrew Ng** → su CFO, jefa de talento, reclutadores y recepcionista saben programar y rinden mejor; sus marketers
  que programaban "were running circles around the ones that don't" [AISS 04 @0:15:26] [AISS 04 @0:40:32].
- **Replit (Masad)** → diseñador, ingeniero y PM "almost always in the same person"; Kelsey, de RR. HH., sin saber
  programar armó en 3 días un organigrama conectado a ADP; mandato de cada empleado: "make the business work"
  [AISS 10 @0:17:18] [AISS 10 @0:19:30] [AISS 10 @0:20:35].
- **Algolia (Dessaigne)** → primer vendedor cerca de USD 1 M de ARR, vendedores técnicos titulados "product
  specialists"; equipo de soporte dedicado recién con cientos de empleados, armado por su mejor engineering manager; "I
  don't know a single dev tool company that is happy with their CMO when they have a traditional marketing background"
  [SS 17 @0:21:57] [SS 17 @0:28:30].
- **Farza (SS 13)** → su primera contratación fue un cineasta para los videos de lanzamiento: ningún fundador quiere
  hacer videos todos los días [SS 13 @0:39:22].
- **Andreessen Horowitz** → todos los socios fueron fundadores o CEOs ("experience required") para ayudar al fundador
  inventor a volverse CEO [HTSS 15 @0:44:43] [HTSS 15 @0:45:16].
- **Google y Larry Page** → contrató un CEO profesional y Page volvió a ser CEO; Altman: "Never" contrates un CEO
  profesional; "if you don't want to be the long-term CEO of a company you probably shouldn't start one"
  [HTSS 19 @0:41:34] [HTSS 19 @0:42:06].

---

## Errores comunes

**Cuándo y cuántos**
- Contratar antes de la necesidad o antes del PMF; medir el éxito por número de empleados [HTSS 02 @0:07:03]
  [SS 09 @0:09:34].
- Contratar más gente esperando más velocidad sin más barriles [HTSS 14 @0:14:29] [HTSS 14 @0:40:23].
- Contratar vendedores antes de saber vender; tercerizar ventas [SS 18 @0:03:47] [SS 18 @0:19:35].
- Contratar dev advocates o un CMO tradicional demasiado temprano en dev tools [SS 17 @0:28:30] [SS 17 @0:30:07].
- Contratar un dev shop en vez de tener cofundador técnico (ver capítulo 02) [SS 06 @0:12:28].
- Contratar rápido "para los próximos tres features" [HTSS 10 @0:18:32].
- El extremo opuesto, ya con producto y capital: contratar muy poco y muy tarde (Truell, Field) [AISS 14 @0:24:01]
  [AISS 17 @0:09:14].
- Recruiter demasiado temprano o demasiado tarde [HTSS 19 @0:13:40].

**A quién**
- Transar con un mediocre; acertijos en entrevistas; saltarse referencias [HTSS 02 @0:11:54] [HTSS 02 @0:15:40].
- Contratar por logos del CV (Y-intercept) [SS26 01 @0:17:50]; indexar demasiado por universidad [SS 33 @0:31:43].
- Contratar como primer empleado a un ejecutivo senior eminente [AISS 03 @0:30:45]; y, al escalar, el error opuesto:
  miedo a traer senior [HTSS 19 @0:03:52].
- Perseguir talentos ya descubiertos por el mercado [HTSS 11 @0:09:55].
- Entrevistar solo por habilidad y no por fit cultural ni creencia en la misión [HTSS 10 @0:09:49]; diversidad de
  valores [HTSS 10 @0:18:32]; equipos homogéneos en los primeros 15-20 [HTSS 19 @0:14:45].
- Aprender qué es un buen candidato durante las entrevistas (caro) [HTSS 11 @0:16:54]; "cargo cult" de entrevistas
  ajenas [HTSS 11 @0:19:01].
- Referencias blandas: dejar que digan "es genial" y cortar [HTSS 11 @0:23:21].
- Contratar a quien busca certezas o "la certeza de Google más las ventajas de una startup" [HTSS 11 @0:45:44]
  [HTSS 11 @0:46:49].
- Aplicar sabiduría de libro que no encaja con tu caso [HTSS 11 @0:48:26] [HTSS 11 @0:48:59].

**Cómo**
- Entrevistar en vez de vender en la primera llamada (error número uno) [SS 33 @0:24:16].
- Outreach genérico copiado de los mails malos que uno recibe [SS 33 @0:27:29] [SS 33 @0:28:01]; medir solo la tasa de
  respuesta (puede subir por "dejá de escribirme") [SS 33 @0:18:52].
- Que un solo fundador lleve toda la contratación; más de una búsqueda por fundador [SS 33 @0:20:31] [SS 33 @0:43:00].
- Ofertas genéricas; procesos lentos [SS 33 @0:24:49] [SS 33 @0:25:21].
- JDs largos, corporativos, escritos por ChatGPT, sin vender la empresa, con valores genéricos para gustarle a todos
  [SS 33 @0:36:02] [SS 33 @0:37:04].
- Prometer a un candidato de big tech estabilidad u horarios que no tenés [SS 33 @0:39:14].
- Blanquear los riesgos o prometer certezas [HTSS 11 @0:46:18].
- No tener un proceso de contratación seguido religiosamente; una persona o grupo chico como cuello de botella;
  entrevistas finales con menos de 25% de conversión [SS26 06 @0:09:52] [SS26 06 @0:11:43] [SS26 06 @0:14:16].
- Clasificar mal empleados y contratistas; no tener workers' comp; no pagar payroll taxes; pagar solo en acciones
  [HTSS 18 @0:35:44] [HTSS 18 @0:38:31] [HTSS 18 @0:32:58] [HTSS 18 @0:37:59].

**Cultura**
- Esperar a tener 100 empleados para escribir los valores (lo que lamentó Tony Hsieh) [HTSS 10 @0:17:26]; dejar la
  cultura en "random oral tradition" [HTSS 19 @0:08:15].
- Valores genéricos (honestidad, integridad, servicio, teamwork) sin profundidad [HTSS 10 @0:06:35].
- Tratar la cultura como dieta de choque en vez de hábito [HTSS 10 @0:10:53].
- Perder la frugalidad tras levantar mucho [HTSS 10 @0:26:10].
- Tratar cultura, RR. HH., finanzas o fundraising como fines en sí, por leer posts de Medium e inversores: "I fell into
  this trap. Big mistake" (Jake Heller) [AISS 05 @0:34:16].
- Decidir el producto por votación democrática ("too many chefs in the kitchen") [SS26 01 @0:15:16].

**Gestión**
- Sin estructura después de los 25-30 empleados, o matriz circular [HTSS 19 @0:01:40] [HTSS 19 @0:02:45].
- Hero mode; mala delegación; sin sistema personal [HTSS 19 @0:04:24] a [HTSS 19 @0:07:07].
- Abdicar o microgestionar; un solo estilo de management para todos [HTSS 14 @0:09:36] [HTSS 14 @0:10:09].
- Decirle al equipo todos los días que lo hace mal [HTSS 02 @0:20:31].
- Una empresa entera resolviendo problemas B+ [HTSS 14 @0:20:27]; medir una sola métrica sin su par
  [HTSS 14 @0:24:46].
- Empire building: medir importancia por tamaño de equipo [HTSS 14 @0:41:28].
- Promover a "buenos gestores de personas" sin dominio de la disciplina [HTSS 14 @0:36:37].
- Prioridades declaradas que no coinciden con el calendario [HTSS 14 @0:44:05].
- Anunciar las metas una vez y creer que todos las recuerdan [HTSS 19 @0:17:57].
- Proceso que premia el proceso [HTSS 19 @0:19:02].
- Intentar recuperar momentum con discursos de visión [HTSS 02 @0:42:40].
- Dar tarjetas a todos y aprobar cada compra; no saber cuánto cuesta cada experimento [SS26 06 @0:03:48]
  [SS26 06 @0:08:38].
- Fundadores de pedigrí que "die on the vine" por no ejecutar la organización [SS26 06 @0:19:17].
- Mantener el mismo organigrama con la IA; delegar la estrategia de IA del fundador [SS 15 @0:06:44] [SS 15 @0:07:50].
- Cambiar tu personalidad al volverte CEO o adoptar técnicas de gestión que no te calzan (Huang) [SS26 15 @0:17:00].

**Compensación y salida**
- Ser tacaño con equity para empleados y generoso con inversores [HTSS 02 @0:18:53].
- Compensación negociada caso a caso; aumentos a pedido; creer que un aumento es confidencial [HTSS 19 @0:10:28]
  [HTSS 15 @0:12:09] [HTSS 15 @0:12:43].
- Opciones en Excel; dejar a alguien con 3 de 4 años consolidados sin refresher [HTSS 19 @0:12:03] [HTSS 19 @0:12:36].
- No explicar al contratar la regla de 90 días [HTSS 15 @0:21:28].
- Esperar demasiado para despedir [HTSS 02 @0:22:07] [HTSS 18 @0:40:43].
- Al despedir: humillar o ser meloso; disculparse; explicaciones confusas; no cortar accesos [HTSS 15 @0:38:02]
  [HTSS 18 @0:40:43] [HTSS 18 @0:41:47].
- Retener a alguien por las esposas doradas [HTSS 15 @0:23:39].
- Dejar que toda la compañía se queme a la vez [HTSS 19 @0:13:40].

---

## Qué dice cada orador (cuando difieren o aportan algo propio)

**Contradicciones y tensiones**
- **Contratar lento vs contratar más rápido.** YC temprano: lo mínimo, solo con necesidad desesperada (Altman)
  [HTSS 02 @0:08:07]; la cultura obliga a contratar lento (Chesky) [HTSS 10 @0:28:25]. Truell y Field, ya con producto
  y capital, se arrepienten de no haber escalado antes [AISS 14 @0:24:01] [AISS 17 @0:09:14]. Legora pasó de 200 a
  1.300 personas en un año [SS26 01 @0:55:42]. Se reconcilian por etapa: lento y con vara altísima antes del PMF;
  rápido y con proceso después (Altman: "Later, you need to learn how to hire fast and scale up") [HTSS 02 @0:08:07].
- **Gente senior.** Al principio "is usually a mistake" (Altman) [HTSS 19 @0:03:52] [AISS 03 @0:30:45]; al escalar,
  "I wish I had done that earlier" [HTSS 19 @0:04:24]. Scholl prefiere promover desde adentro también en cargos senior
  [SS26 12 @0:27:22]; Silbermann contrata de afuera solo donde la curva es demasiado grande [HTSS 11 @0:41:18].
- **Entrevistar vs trabajar juntos.** Altman: proyecto de uno o dos días [HTSS 02 @0:15:07]; Patrick Collison: una
  semana [HTSS 11 @0:20:07]; Hale: un mes pago [HTSS 07 @0:44:31]; Paffenholz: case study de 1 hora y on-site de 6 h
  [SS 33 @0:23:13]; Hodak: homework resistente a IA puntuado [SS26 06 @0:13:38]. Todos coinciden en evaluar trabajo
  real, no acertijos ni LeetCode.
- **Transparencia.** Stripe al extremo (todo email visible) [HTSS 11 @0:35:20]; Rabois propone ir más allá, hasta la
  compensación por bandas [HTSS 14 @0:23:42] [HTSS 14 @0:32:49]; Horowitz asume que la compensación se filtra y la
  protege con un proceso formal, sin publicarla [HTSS 15 @0:12:09] [HTSS 15 @0:13:48]; Altman: "someday everyone will
  find out" y por eso bandas [HTSS 19 @0:10:28].
- **Horas y balance.** Patrick Collison relativiza las jornadas extremas (~2 horas más por día para empleados; lo de no
  ver a la familia es "the startup version of fishing") [HTSS 11 @0:45:11]; Hoffman: "founders have no balance"
  [HTSS 13 @0:41:51]; Rabois: si ese esfuerzo no te resulta apetecible, no fundes [HTSS 14 @0:32:15]; Altman: "Startups
  are not the best choice for work-life balance", podés tener startup y familia pero no muchos hobbies
  [HTSS 02 @0:35:43] [HTSS 02 @0:36:15]; Junestrand celebra "blood smoke" [SS26 01 @0:23:43]; Steinberger propone "fun
  is velocity" tras quemarse [SS26 05 @0:22:49]; Hale: el modo crunch costó más de lo que dio [HTSS 07 @0:45:42]. Matiz:
  Patrick habla de empleados; Hoffman y Rabois de fundadores.
- **Contratar usuarios.** Ventaja injusta (John Collison) [HTSS 11 @0:49:31] vs regla que no sirve para todos
  (Silbermann) [HTSS 11 @0:48:26].
- **Diversidad vs contratar conocidos.** Altman: diversidad de orígenes, no de visión; gente que conocés, complementaria
  y alineada, no idéntica [HTSS 19 @0:36:30] [HTSS 19 @0:37:04].
- **Tamaño de equipo con IA.** Diana Hu: casi cero middleware humano, maximizar tokens no headcount [SS 15 @0:06:10]
  [SS 15 @0:08:23]; Masad: menos razones para contratar full time, equipos que se arman y desarman en días
  [AISS 10 @0:23:53] [AISS 10 @0:24:28]; Garry Tan: ingresos por persona inéditos [SS26 07 @0:22:31]; Altman (2026) cree que se verán
  startups de cuatro personas que automatizan una empresa entera con agentes [SS26 13 @0:10:56]. En contra: Levie cree
  que la IA crea empleo en startups y pymes [AISS 12 @0:14:05]; Scholl necesita más ingenieros [SS26 12 @0:41:25];
  Huang: +10% de empleos de software [SS26 15 @0:31:55]. Choca con el consejo de 2014 de que la velocidad la dan los
  barriles, no la cantidad: ambos dicen que más gente no es más velocidad.
- **Consenso.** Kare: hasta ~15 personas se contrata por consenso [SS26 03 @0:48:20]; Hodak lo escala con votación
  ponderada [SS26 06 @0:11:05]; Junestrand dejó de decidir el producto por votación [SS26 01 @0:15:16].
- **Opciones a 10 años.** Altman (post) vs Horowitz (depende de tu cultura); Altman revisó levemente en la sala
  [HTSS 15 @0:24:13] [HTSS 15 @0:25:55].
- **Empezar chico vs no ser nicho.** Patrick Collison advierte contra ideas nicho porque no atraen talento
  [HTSS 11 @0:14:46]; Levie recomienda una cuña chica con visión de expansión [HTSS 12 @0:35:57]; Silbermann pide
  recordar siempre la visión grande al equipo [HTSS 11 @0:24:58].

**Aportes propios**
- **Sam Altman (YC, 2014; OpenAI, 2025)**: tres preguntas, "bet the future", 10% a los primeros 10, despedir rápido,
  cuatro errores del fundador que se vuelve gerente, HR en doce piezas, ritmos, 3-5% por año, "hire for slope", nunca
  un CEO profesional.
- **Keith Rabois**: editor, barriles y municiones, task relevant maturity, matriz convicción por consecuencia, métricas
  pareadas, dashboard, auditoría de calendario, one-on-ones, detalles; "being a venture capitalist is more like being
  a psychologist" [HTSS 14 @0:42:31].
- **Ben Horowitz**: un solo concepto (los que no están en la sala), aumentos formales, despedir con dignidad, kimchi.
- **Brian Chesky y Alfred Lin**: cultura antes de contratar, valores únicos, tres problemas de la cultura, misioneros vs
  mercenarios, cultura y marca, el trabajo del CEO en tres cosas; Lencioni y "help you move faster".
- **Collison y Silbermann**: cultura como ancho de banda y jardinería, rasgos de los primeros 10, capital humano
  subvaluado, referencias con escasez, onboarding, horizonte temporal, transparencia escalada.
- **Reid Hoffman**: paradoja hacer vs delegar ("ambas, a veces 90% de una") [HTSS 13 @0:13:44] [HTSS 13 @0:17:00]; 20+
  horas con un candidato a CEO o cofundador hablando hasta "del divorcio" [HTSS 13 @0:47:45] [HTSS 13 @0:48:50];
  valora equipos que se discuten para llegar a la verdad (Levchin: "here are some things that are going to kill us")
  [HTSS 13 @0:37:01].
- **David Paffenholz y Harj Taggar**: reclutar = ventas outbound con métricas; es CEO de una herramienta de sourcing, y
  sus recomendaciones de flujo también venden su producto [SS 33 @0:32:49].
- **Max Hodak**: infraestructura = velocidad; proceso religioso; eigenreviews; "you cannot delegate your judgment".
- **Max Junestrand**: slope vs Y-intercept, LFG, minijuegos, recalificar como CEO cada trimestre, alinear con un
  manifiesto.
- **Diana Hu**: tiempo de código del fundador técnico por tamaño; empresa nativa de IA con IC, DRI y fundador de IA.
- **Blake Scholl**: no se enseña a que alguien le importe; promover desde adentro; llamar a quien ya lo hizo.
- **Jensen Huang**: adaptá el auto a vos; el CEO va al detalle para descomponer el problema y enseñarlo a la empresa
  [SS26 15 @0:13:46] [SS26 15 @0:17:00].
- **Alexandr Wang**: densidad de talento que se compone; la empresa como loops de retroalimentación operados por
  humanos (clientes → felicidad → gasto → contratar → clientes) que los agentes pueden operar [SS26 11 @0:14:15]
  [SS26 11 @0:27:30].
- **Garry Tan**: skill file = empleado, resolver = organigrama; "own your skills because if you don't your job becomes
  a skill file" (consejo al empleado, no al empleador) [SS26 07 @0:21:14] [SS26 07 @0:30:34].
- **Satya Nadella**: "It's your job to align the team" [AISS 07 @0:32:36]; el ingeniero pasa a arquitecto que revisa
  los change logs de los agentes [AISS 07 @0:22:26].
- **Fei-Fei Li**: contrata por "intellectual fearlessness" [AISS 06 @0:30:55].
- **Kevin Hale**: todos hacen soporte, remoto con reglas, King for a day.
- **Dustin Moskovitz**: el CEO maneja su psicología; el equipo copia tu energía.

---

## Para el agente

Usá esta sección cuando el fundador pregunte "¿a quién contrato primero?", "¿cuándo contrato?", "revisame este JD / este
mail a un candidato", "¿cómo entrevisto?", "¿cuánta equity le doy?", "¿cómo armo la cultura / los valores?", "¿cómo
organizo el equipo ahora que somos X?", "¿lo despido?", "¿qué diría Altman / Rabois / Horowitz?". Antes de responder,
preguntá (o deducí) tres cosas: etapa (pre-PMF, con PMF, ~25+ personas), rol (ingeniero, AE, operaciones, ejecutivo) y
país (los videos solo cubren ley de EE. UU.).

### Checklist 1: ¿contrato ahora?
- [ ] Hay una necesidad desesperada que los fundadores no pueden cubrir [HTSS 02 @0:08:07].
- [ ] Hay PMF o al menos convicción de que la idea es la correcta; si no, los fundadores construyen [SS 09 @0:09:34]
      [SS 17 @0:15:24].
- [ ] Si es ventas: el fundador ya vende de forma repetible y sabe cómo se ve lo bueno [SS 18 @0:03:47].
- [ ] El rol no lo cubre un agente o una herramienta propia (visión 2025-2026) [SS 15 @0:08:23].
- [ ] La persona sería un barril o hay un barril que la dirija [HTSS 14 @0:40:55].
- [ ] Los valores están escritos [HTSS 10 @0:17:26].
- [ ] El fundador tiene ~25% de su tiempo bloqueado en el calendario para contratar [HTSS 02 @0:11:22]
      [HTSS 14 @0:43:34].
Si falla alguno: no contrates todavía; decí cuál falta y qué hacer (escribir valores con F12, vender primero, etc.).

### Checklist 2: plan de contratación
- [ ] Rasgos definidos (3 o 4) y vara explícita: "¿apostaría la empresa a esta contratación?" [HTSS 02 @0:12:26].
- [ ] Fuentes: referidos primero (repasar la red de cada fundador y empleado), Work at a Startup si es YC, sourcing
      [SS 33 @0:06:29] [HTSS 02 @0:13:30].
- [ ] Una búsqueda por fundador como máximo [SS 33 @0:42:28].
- [ ] Ritmo: 100 mails por semana, 10 entrevistas por semana [SS 33 @0:19:26] [SS 33 @0:19:58].
- [ ] Proceso definido y seguido "religiosamente" (pasos, quién vota, plazos) [SS26 06 @0:09:52].
- [ ] Evaluación con trabajo real (proyecto, case study, homework), no acertijos [HTSS 02 @0:15:40] [SS 33 @0:23:13].
- [ ] Referencias con la pregunta de escasez [HTSS 02 @0:16:12] [HTSS 11 @0:22:49].
- [ ] Proceso de 7 a 14 días [SS 33 @0:24:49].
- [ ] Equity pensada de antemano (~10% para los primeros 10, 4 años, cliff de 1) [HTSS 02 @0:18:20].
- [ ] Métrica: tasa de interesados, no solo de respuesta [SS 33 @0:18:52].

### Checklist 3: revisar un JD
- [ ] ¿Te postularías leyéndolo? [SS 33 @0:07:34]
- [ ] Corto, en bullets [SS 33 @0:36:33].
- [ ] ≥30% vende la empresa (misión, problema, equity, equipo) [SS 33 @0:36:33].
- [ ] Opinionado: dice qué valoran y qué sacrifican [SS 33 @0:37:04].
- [ ] No suena corporativo ni a ChatGPT [SS 33 @0:36:02].
- [ ] Cuenta con crudeza por qué será difícil [HTSS 11 @0:17:58].
- [ ] Misma voz que el producto y la web [HTSS 14 @0:07:29] [HTSS 14 @0:38:15].

### Checklist 4: revisar un mail de outreach a un candidato
- [ ] Lo firma un fundador (el técnico si es ingeniero) [SS 33 @0:15:06] [SS 33 @0:35:29].
- [ ] Corto, se lee en el celular [SS 33 @0:15:06].
- [ ] Personalizado de verdad (algo en común, algo de su trabajo; ~5 minutos) [SS 33 @0:28:33].
- [ ] Legitimidad: clientes, crecimiento, ronda, prensa [SS 33 @0:15:06].
- [ ] Uno o dos de los cuatro argumentos, elegidos para esa persona [SS 33 @0:04:54].
- [ ] Pitch por rol: AE = trayectoria y compensación; ingeniero = ownership, problemas difíciles, equipo chico
      [SS 33 @0:13:29] [SS 33 @0:14:02].
- [ ] Call to action con link de agenda [SS 33 @0:15:06].
- [ ] Es parte de una secuencia (mail 2 con valor y salida, LinkedIn manual, mail final) [SS 33 @0:15:06] a
      [SS 33 @0:17:17].

### Checklist 5: diseñar o revisar una entrevista
- [ ] La primera llamada vende y averigua motivos (¿por qué startup?, ¿con quién más habla?) [SS 33 @0:21:04]
      [SS 33 @0:24:16].
- [ ] Hay una prueba de trabajo real y difícil de hacer con trampa o con IA [SS 33 @0:23:13] [SS26 06 @0:13:38].
- [ ] Se evalúan inteligencia, que hace que las cosas pasen, si querés pasar tiempo con la persona [HTSS 02 @0:14:36];
      o juicio, potencia y agencia [SS26 06 @0:12:59]; pendiente más que punto de partida [AISS 03 @0:31:51].
- [ ] Hay preguntas de valores, hechas por alguien de otra área [HTSS 10 @0:29:31].
- [ ] Hay señales de gusto por el riesgo y de comunicación [HTSS 02 @0:16:44].
- [ ] Si es un área que el fundador no domina, se pre-calibró con gente de primer nivel [HTSS 11 @0:16:22].

### Checklist 6: cultura y valores
- [ ] Escritos, 3 a 6, únicos (no "integridad"), cada uno con un párrafo [HTSS 10 @0:16:53] [HTSS 10 @0:05:27].
- [ ] Atados a la misión y creíbles [HTSS 10 @0:04:54].
- [ ] Se usan para contratar, evaluar y despedir [HTSS 10 @0:28:58] [HTSS 10 @0:09:49].
- [ ] Se repiten en todas partes; hay historias o artefactos que los encarnan [HTSS 10 @0:26:42] [HTSS 10 @0:37:10].
- [ ] Los fundadores los viven (todo se modela según ellos) [HTSS 02 @0:29:40].

### Checklist 7: equipo de ~20 a 50 personas
- [ ] Cada persona tiene exactamente un jefe conocido; no hay matrices [HTSS 19 @0:01:40] [HTSS 19 @0:02:45].
- [ ] Test de alineación: 10 personas al azar dicen las mismas tres metas en el mismo orden [HTSS 19 @0:17:24].
- [ ] Reunión semanal de management, all hands mensual, plan trimestral [HTSS 19 @0:19:02] [HTSS 19 @0:19:35].
- [ ] One-on-ones cada 1 o 2 semanas, 5 a 7 reportes por jefe [HTSS 14 @0:39:18].
- [ ] Feedback frecuente; bandas de compensación; aumentos por ciclo [HTSS 19 @0:09:22] [HTSS 15 @0:13:48].
- [ ] Equity continua con refresher grants y software de opciones [HTSS 19 @0:11:30] [HTSS 19 @0:12:36].
- [ ] Onboarding con buddy, trabajo real el día 1, medición a los 30 días [HTSS 19 @0:14:13] [HTSS 11 @0:26:03].
- [ ] Recruiter full time; cada oferta anunciada internamente [HTSS 19 @0:13:40] [HTSS 19 @0:14:13].
- [ ] Conversación de carrera con los primeros 10-15 [HTSS 19 @0:15:49].
- [ ] Dashboard que usa casi toda la empresa cada día, con métricas pareadas [HTSS 14 @0:21:32] [HTSS 14 @0:24:46].
- [ ] El fundador ya no está en hero mode y delega con confianza [HTSS 19 @0:04:24] [HTSS 19 @0:06:01].
- [ ] Hay ejecutivos senior donde el fundador no llega [HTSS 19 @0:03:52].
- [ ] Hay vigilancia del burnout [HTSS 19 @0:13:08].

### Checklist 8: ¿lo despido?
- [ ] No es uno o dos errores: toma sistemáticamente las decisiones opuestas por semanas o un mes, o crea política
      interna, o es persistentemente negativo [HTSS 02 @0:22:40] [HTSS 02 @0:23:44].
- [ ] Ya recibió feedback claro sobre cómo mejorar [HTSS 11 @0:15:49].
- [ ] Pensaste cómo lo leen los que no están en la sala (equity, respeto, qué significa fallar) [HTSS 15 @0:01:41]
      [HTSS 15 @0:07:35].
- [ ] Plan de ejecución: cara a cara con un tercero, mensaje claro sin disculpas, pago inmediato, accesos cortados,
      recompra de acciones no consolidadas, comunicación a la empresa preservando su dignidad [HTSS 18 @0:40:43] a
      [HTSS 18 @0:41:47] [HTSS 15 @0:39:10].
Si todo da sí y todavía duda: "every first-time founder waits too long" [HTSS 02 @0:22:07].

### Señales
**Bien hecho**
- Los fundadores dicen de cada empleado temprano que es "the very best in the world" en lo suyo [HTSS 02 @0:17:47].
- Los empleados van a pedir ayuda a ciertas personas que no son su jefe (barriles) [HTSS 14 @0:17:45].
- Tasa de interesados de outreach en 10-20% o más; procesos de 1-2 semanas [SS 33 @0:18:21] [SS 33 @0:24:49].
- Los nuevos son productivos en 30 días y saben las prioridades [HTSS 11 @0:25:30].
- Las referencias ubican al candidato en el top 5% sin dudar [HTSS 02 @0:16:12].
- Diez empleados al azar dicen las mismas tres metas [HTSS 19 @0:17:24].
- Cada mes hay menos tinta roja [HTSS 14 @0:06:57].
- Los valores aparecen en historias que cuentan los empleados [HTSS 10 @0:22:50].
**Mal hecho o no hecho**
- "Contratamos para crecer" sin barriles; métrica de éxito = cantidad de gente [HTSS 02 @0:07:03] [HTSS 14 @0:14:29].
- JD corporativo y largo; mails genéricos; el fundador no escribe ni entrevista [SS 33 @0:27:29] [SS 33 @0:36:02].
- Primera llamada que es un interrogatorio [SS 33 @0:24:16].
- Sin referencias o con referencias de "es genial" [HTSS 11 @0:23:21].
- Equity mínima a empleados y generosa a inversores [HTSS 02 @0:18:53].
- Aumentos negociados en el pasillo [HTSS 15 @0:12:43].
- El fundador responde todos los tickets o revisa todo (hero mode) [HTSS 19 @0:04:24].
- Más de 25 personas sin estructura ni ritmos [HTSS 19 @0:01:07].
- Alguien "en evaluación" por meses sin decisión [HTSS 02 @0:22:07].
- Nadie sabe cuánto cuesta cada experimento o compra [SS26 06 @0:06:51].

### Qué hacer después (acciones concretas de los videos)
- **No hay valores escritos** → correr el método de Lin (F12) con los fundadores esta semana y bajarlos a un párrafo
  cada uno [HTSS 10 @0:04:21].
- **No llegan candidatos** → armar la secuencia de 4 pasos, 100 mails por semana firmados por fundadores, medir
  interesados; si no llegás a 10 entrevistas por semana, subir volumen [SS 33 @0:19:26].
- **Los candidatos dicen que no** → revisar si en la primera llamada se vende; elegir el argumento correcto; acelerar
  a 7-14 días; pedir a un inversor que escriba; mantener la relación [SS 33 @0:24:16] [SS 33 @0:25:54]
  [SS 33 @0:39:47].
- **No sabe evaluar el rol** → hablar con 2 o 3 personas de primer nivel en esa disciplina antes de entrevistar
  [HTSS 11 @0:16:22].
- **Duda con un candidato** → trabajar juntos uno o dos días (o una semana) y hacer referencias con escasez
  [HTSS 02 @0:15:07] [HTSS 11 @0:20:07].
- **Equipo de ~25 y caos** → estructura simple (P13), ritmos (F8), escribir el cómo y el porqué, test de alineación
  [HTSS 19 @0:01:40] [HTSS 19 @0:07:41] [HTSS 19 @0:17:24].
- **Fundador desbordado** → auditoría de calendario de un mes; salir del hero mode contratando aunque se atrase 2-3
  semanas; delegar con "you make this decision, I totally trust you" [HTSS 14 @0:37:10] [HTSS 19 @0:04:57]
  [HTSS 19 @0:06:01].
- **Alguien pide aumento** → no darlo en el momento; montar un ciclo semestral o trimestral (P15) [HTSS 15 @0:13:48].
- **Hay que despedir** → aplicar P17 esta semana [HTSS 18 @0:40:43].
- **Equipo desmoralizado** → victorias chicas, nombrar el problema, ritmo operativo semanal [HTSS 02 @0:42:40] a
  [HTSS 02 @0:44:16].

### "¿A quién contrato primero?" (respuesta guía)
Lo que dicen los videos, en orden: (1) antes de contratar, que los fundadores construyan y vendan ellos mismos hasta
el PMF [SS 09 @0:09:34] [SS 18 @0:03:47]; (2) la primera contratación cubre una necesidad desesperada que los
fundadores no pueden cubrir, no un rol "de manual" [HTSS 02 @0:08:07]; (3) "young scrappy" que haga cosas, no un
ejecutivo senior [AISS 03 @0:30:45]; por pendiente, no por logos [AISS 03 @0:31:51] [SS26 01 @0:17:50]; (4) idealmente
alguien que ya conocés o que viene por referido, probado trabajando juntos [HTSS 02 @0:13:30] [HTSS 02 @0:15:07]; (5)
ventas recién cuando el fundador vende de forma repetible (Algolia: primer vendedor cerca de USD 1 M de ARR)
[SS 17 @0:21:57]. Ejemplos concretos de primeras contrataciones no obvias: un cineasta para videos (Farza)
[SS 13 @0:39:22], usuarios apasionados (Stripe) [HTSS 11 @0:50:04].

### "¿Qué diría...?"
- **Sam Altman**: "only hire when you have a desperate need"; "Will I bet the future of this company on this single
  hire?"; 10% a los primeros 10; "fire fast"; hacia las 25 personas tu trabajo es construir la compañía.
- **Keith Rabois**: ¿cuántos barriles tenés?; sé editor; expandí el alcance hasta que se rompa; medí output con
  métricas pareadas; auditá tu calendario.
- **Ben Horowitz**: ¿cómo lo leen los que no están en la sala?; formalizá los aumentos; despedí sin quitar la dignidad.
- **Brian Chesky**: escribí los valores antes de contratar; ¿tomaría el trabajo con diez años de vida?; misioneros, no
  mercenarios.
- **Patrick y John Collison**: buscá talento subvaluado; trabajá una semana juntos; empujalos del acantilado el día 1.
- **Max Hodak**: tené un proceso religioso; el promedio no alcanza; no delegues tu juicio.
- **David Paffenholz / Harj Taggar**: reclutar es ventas; vendé en la primera llamada; velocidad; juego repetido.

---

## Huecos

> **Hueco:** los videos no cubren contratación ni ley laboral fuera de EE. UU. (Colombia, Latinoamérica, EOR,
> contratistas internacionales, remoto entre países). HTSS 18 es ley de EE. UU. de 2014 [HTSS 18 @0:35:44].

> **Hueco:** no hay benchmarks de salarios ni rangos de equity por rol individual (cuánto a un primer ingeniero vs a un
> primer AE); solo la guía agregada de 10% para los primeros 10 y 3-5% por año [HTSS 02 @0:18:20] [HTSS 19 @0:11:30].

> **Hueco:** SS 33 muestra en pantalla las plantillas de mail, los criterios en Juicebox y las métricas de campañas; no
> están completos en el texto [SS 33 @0:15:06]. La frase "your response rate is roughly half of your interested rate"
> está invertida: por contexto, la tasa de interesados es más o menos la mitad de la de respuesta [SS 33 @0:18:52].
> Harj pidió "tres errores" y Paffenholz nombró dos [SS 33 @0:26:26] [SS 33 @0:27:29].

> **Hueco:** Rabois no explica los dos cuadrantes mixtos de la matriz convicción por consecuencia, y promete "another
> set of tactics" para pasar a manager que no da [HTSS 14 @0:11:44] [HTSS 14 @0:37:10].

> **Hueco:** Airbnb dice tener seis valores y solo nombra dos; Zappos diez y solo nombra dos; el acrónimo de Lin no se
> reconstruye letra por letra; la cifra de Fortune (11,8% u 11,08%) es dudosa [HTSS 10 @0:19:04] [HTSS 10 @0:05:27]
> [HTSS 10 @0:03:16] [HTSS 10 @0:04:21].

> **Hueco:** Altman nombra solo en parte las "reglas de 50 empleados" [HTSS 19 @0:13:08].

> **Hueco:** en HTSS 11 los turnos entre Patrick y John Collison se atribuyen por pistas y estilo; son probables, no
> seguros. El moderador no se nombra (casi seguro Sam Altman).

> **Hueco:** ningún video explica cómo armar un plan de compensación de vendedores más allá del ratio 5:1 (ver
> capítulo 06), ni cómo contratar al primer gerente de ventas.

> **Hueco:** los videos de IA (AISS, SS26) dan visiones sobre tamaño de equipo y roles, pero ningún proceso concreto de
> cómo evaluar a un ingeniero que trabaja con agentes, salvo Hodak (diseño, descomposición, homework resistente a IA)
> [SS26 06 @0:28:53].

> **Hueco:** Hodak ofrece un documento con los trucos de las eigenreviews que no está en el video
> [SS26 06 @0:18:04].
