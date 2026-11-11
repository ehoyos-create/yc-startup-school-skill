# Fuentes y calidad

> Qué hay, qué falta y en qué no confiar a ciegas. El detalle de cada hueco está en la sección "Huecos" del capítulo
> correspondiente.

## Inventario

| Curso | Videos | Horas | Extractos | Cita | Subtítulos |
|---|---|---|---|---|---|
| Startup School (YC, charlas de socios) | 33 | 12,5 | ss-1-2, ss-3, ss-4, ss-5-6 | `[SS NN]` | YouTube (manuales o automáticos); 5 con whisper (SS 04, 13, 22, 27, 29) |
| How to Start a Startup (Stanford 2014) | 19 | 15,4 | htss-a, htss-b, htss-c, htss-d | `[HTSS NN]` | YouTube; 3 con whisper (HTSS 05, 07, 09) |
| AI Startup School (2025) | 17 | 11,4 | aiss-a, aiss-b, aiss-c | `[AISS NN]` | YouTube; 1 con whisper (AISS 01) |
| Startup School 2026 | 15 | 11,6 | ss26-a, ss26-b, ss26-c | `[SS26 NN]` | todos con whisper |

Total: 84 videos, ≈ 51 h. Los videos son públicos en YouTube (lista con enlaces en `../FUENTES.md`). Los subtítulos se
bajaron con `yt-dlp`; cuando YouTube no los dio (error 429 o sin subtítulos), se bajó solo el audio a un temporal y se
transcribió en la Mac con whisper (large-v3-turbo). Las transcripciones no se
publican en este repo (son de YC); para verificar una cita, abrí el video en el minuto citado.

**Numeración.** Es propia de esta wiki, no la del evento. Startup School está agrupado en 6 módulos temáticos
(01 Idea · 02 Cofundadores y equipo · 03 Construir y lanzar · 04 Primeros clientes y ventas · 05 Retención y métricas ·
06 Fondeo, YC y contratación): SS 01-04, 05-09, 10-17, 18-25, 26-30, 31-33. HTSS sigue el número de clase de 2014.

## Lo que falta

- **HTSS:** la clase 19 original está borrada de YouTube; la numeración salta (HTSS 19 de esta wiki es "Later Stage
  Advice", la última clase de Sam Altman). Hay referencias a una clase anterior ("Tyler… last lecture") que no está.
- **Diapositivas:** no hay OCR (los videos no se bajan). Todo lo que estaba solo en pantalla falta: gráficos de
  curvas y cohortes, los mails de ejemplo de SS 18, la tabla del top 100 de YC por modelo de negocio (SS 25), los
  mensajes de LinkedIn de SS 10, las láminas finales de Susan Kare (SS26 03), los gráficos de Kaplan, Jumper y Chollet,
  las diapositivas de Hosain Rahman (HTSS 17).
- **Guías externas** que los videos citan y no explican: ensayos de Paul Graham ("Do Things That Don't Scale", "How to
  Get Startup Ideas", "Schlep Blindness"), las guías de YC sobre SAFE y fondeo, la guía de los 9 modelos de negocio
  de SS 25, *7 Powers*.

## Calidad de las transcripciones

- **Subtítulos automáticos** (la mayoría de SS, HTSS y AISS): sin puntuación y con nombres mal escritos ("Hodge tiger"
  = Harj Taggar, "Dustin movitz" = Moskovitz, "Chimoth" = Chamath). Cada extracto tiene su tabla de correcciones; la
  tabla única está en `13-glosario.md`.
- **SS 08 (Dalton Caldwell, términos clave):** el subtítulo parece una retraducción automática ("seeding round",
  "simple future equity agreement"); sus frases literales en inglés no son confiables.
- **Whisper:** no marca quién habla. Alucinó (repite una frase) en SS26 12 @0:06:36 a 0:08:13 (video del vuelo del
  XB-1) y en SS26 04 @0:15:58 a 0:16:33 (números de throughput de Physical Intelligence).
- **Oradores inferidos** (no dicen su nombre en el audio): SS 03 "John" sin apellido; SS 04 probablemente Francois
  Chaubard; SS 11 Michael Seibel; SS 12 Kat Mañalac; SS 16 sin identificar; SS 19 "Max" sin apellido; SS 20 Tom
  Blomfield; SS 22 la fundadora de OneSchema; SS 28 Tom Blomfield; entrevistadores de AISS 09, AISS 14, AISS 17, SS26 10
  y SS26 14; Garry Tan en AISS 02, SS26 11 y SS26 15 por contexto. Ver `11-oradores.md`.

## Cifras dudosas o errores de los oradores

- SS 07 @0:07:13: "a token amount of equity 5% to 2%" casi seguro es 0,5% a 2%.
- SS 18 @0:15:49: 5% de 250 aperturas da 12,5 respuestas, no "about 20".
- SS 24: "$149.99" es casi seguro 14.999 USD; "$22,000 a month" debería ser unos 2.000.
- SS 28: "más del 50% de los registros orgánicos" debía decir pagos (lo aclara la recapitulación @0:20:31).
- SS 29: la cifra de GTV de Monzo (500 billones) es imposible.
- SS26 08: "500 trips per week" es casi seguro unos 500.000.
- HTSS 07: Kevin Hale fecha la venta de Wufoo en 2013 (fue 2011). HTSS 06: G. I. Taylor no ganó el Nobel.
- AISS 06 @0:14:45: Fei-Fei Li dice "300 to 500 million years" para el lenguaje; probablemente 300.000 a 500.000.
- SS26 13: Altman da "7 minutos", "17 segundos" y "17 minutos" para lo mismo.

## Época y jurisdicción

- HTSS es de 2014: lo legal y contable es de EE. UU. (Delaware, 83(b), payroll, salario mínimo de San Francisco) y
  hay cifras y prácticas viejas (co-founder dating "really bad" en 2014, YC Co-Founder Matching después).
- AISS es de junio de 2025 y SS26 de 2026: modelos, precios y herramientas (Sonnet 3.7, GPT-4.1 en SS 14, Opus 5 en
  SS26 14) cambian rápido; el propio Tom Blomfield avisa que sus consejos de herramientas pueden caducar en meses.
- Nada cubre incorporar u operar desde Colombia o Latinoamérica (SAS, vesting local). Si el fundador lo pregunta, decirlo.

## Lo de los oradores no es "el método de YC"

AISS y SS26 son charlas y entrevistas de fundadores e investigadores: opiniones y predicciones personales. Los
socios de YC en SS y Sam Altman o Paul Graham en HTSS dan consejo de YC. La wiki marca la diferencia en cada capítulo.

## Cobertura de la wiki

Los capítulos 02 a 07 se escribieron antes de que estuviera el extracto `ss26-b` (SS26 06 a 10: Hodak, Garry Tan,
Dolgov, Collison, Jeff Dean). Lo de esos videos entró leyendo las transcripciones directo, sobre todo Collison
(SS26 09) y Dolgov (SS26 08); puede faltar algo de Hodak, Garry Tan o Jeff Dean en esos capítulos. Los capítulos
01 y 08 a 14 sí usaron los 14 extractos. Para esos cinco oradores, la fuente más completa es `10-ia-y-el-futuro.md`
y `11-oradores.md`.
