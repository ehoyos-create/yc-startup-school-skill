# YC Startup School · skill para Claude

Un coach de startups con la mirada de Y Combinator. Es una
[skill de Claude](https://docs.claude.com/en/docs/claude-code/skills) que responde con lo que dicen los
**84 videos públicos de YC** (≈ 51 horas), con cita al video y al minuto, en lugar de responder de memoria.

| Curso | Videos | Código de cita | Quién habla |
|---|---|---|---|
| Startup School | 33 | `[SS 10 @0:05:30]` | Los socios de YC: Seibel, Taggar, Caldwell, Friedman, Blomfield, Diana Hu… |
| How to Start a Startup (Stanford 2014) | 19 | `[HTSS 03]` | Sam Altman, Paul Graham, Peter Thiel, Andreessen, Chesky, los Collison… |
| AI Startup School (2025) | 17 | `[AISS 01]` | Karpathy, Altman, Andrew Ng, Musk, Nadella, Fei-Fei Li, Chollet… |
| Startup School 2026 | 15 | `[SS26 07]` | Garry Tan, Patrick Collison, Jeff Dean, Boris Cherny, Altman… |

Lista completa con enlaces: [FUENTES.md](FUENTES.md).

> **English summary.** A Claude skill that coaches founders using only what Y Combinator says in its 84 free YouTube
> videos (Startup School, Stanford's How to Start a Startup 2014, AI Startup School 2025, Startup School 2026). It
> reviews ideas, user-interview scripts, MVPs, launches, cold emails, pricing, metrics, fundraising and YC
> applications, citing the video and minute behind each piece of advice. The knowledge base is in Spanish; Claude
> answers in your language. Install it with the steps below.

## Qué hace

- **Evalúa** una idea, un guion de entrevista, un MVP, un lanzamiento, un cold email, un precio, tus métricas, una
  ronda, tu aplicación a YC o un plan de contratación, con veredicto, lo que falta y el siguiente paso.
- **Responde "¿qué diría…?"** Paul Graham, Sam Altman, Michael Seibel, Peter Thiel, Garry Tan y unos 80 oradores
  más, cada uno con una cita real.
- **Separa** el consejo de YC (los socios) de la opinión de un invitado, y avisa la época (2014, 2025, 2026) cuando un
  consejo viejo choca con uno nuevo.
- **Dice qué no sabe**: si los videos no cubren algo (por ejemplo, lo legal fuera de EE. UU.), lo dice en vez de
  inventar.

Ejemplos de pedidos y de respuestas: [CASOS-DE-USO.md](CASOS-DE-USO.md).

## Instalación

### Claude Code

```bash
git clone https://github.com/ehoyos-create/yc-startup-school-skill.git ~/.claude/skills/yc-startup-school
```

Abrí una sesión nueva de Claude Code. La skill se activa sola cuando el pedido encaja; también la podés llamar con
`/yc-startup-school`. Para actualizarla: `git -C ~/.claude/skills/yc-startup-school pull`.

Solo para un proyecto: cloná en `.claude/skills/yc-startup-school` dentro del proyecto.

### Claude.ai o la app de escritorio

1. Bajá el repo como ZIP (botón **Code → Download ZIP**) y descomprimilo.
2. Renombrá la carpeta a `yc-startup-school` y volvé a comprimirla (el ZIP tiene que tener la carpeta con
   `SKILL.md` adentro).
3. En Claude: **Settings → Capabilities → Skills → Upload skill** y subí el ZIP.

### API de Claude o Agent SDK

La carpeta sigue el formato estándar de skills (`SKILL.md` con frontmatter más archivos de apoyo). Subila con la API
de Skills o ponela en `.claude/skills/` del proyecto del agente. Ver la
[documentación de skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview).

## Cómo usarla

Pedile cosas concretas y pasale el material original (el mail, las notas, los números):

```
Revisá mi idea con la mirada de YC: un copiloto de IA para contadores pymes en México.
Armame el guion para mis primeras 10 entrevistas con usuarios.
Este es mi cold email a CTOs, ¿qué le cambiarías? <pegá el mail>
Tengo esta retención por cohorte, ¿hay product-market fit? <pegá la tabla>
¿Cuánto debería levantar y con qué cap? Tengo 8 mil USD de MRR creciendo 15% mensual.
¿Qué diría Paul Graham de que mi cofundador trabaje medio tiempo?
Revisá mi aplicación a YC.
```

La respuesta trae el veredicto primero, después lo que falta y el siguiente paso, con las citas
(`[SS 02 @0:12:40]`) para que puedas ir al video.

## Cómo está armada

```
SKILL.md          instrucciones para Claude: qué leer y cómo responder
FUENTES.md        los 84 videos con enlace y duración
CASOS-DE-USO.md   ejemplos de pedidos y respuestas
wiki/
  rapida/         13 fichas de ≤ 10 KB: lo que Claude lee primero
  00-indice.md    índice de la wiki
  01 a 14         capítulos completos (≈ 2 MB): reglas, ideas, usuarios, ventas, métricas, fondeo, equipo, IA,
                  oradores, casos, glosario y la guía del agente
  99-fuentes-y-calidad.md   qué falta y en qué no confiar a ciegas
  MAPA.md         rangos de líneas de cada sección, para leer solo lo necesario
```

Claude lee primero la ficha rápida del tema (pocos tokens). Solo baja al capítulo, y solo a la sección que necesita,
cuando la ficha no alcanza. Así una consulta típica gasta entre 10 y 30 KB de contexto, no 2 MB.

**De dónde sale.** Se bajaron los subtítulos de YouTube de cada video, y donde no había, se transcribió el audio
con whisper. Después se resumió cada bloque de videos en extractos con cita al minuto y, de ahí, se escribieron los
capítulos y las fichas. La wiki marca **Hueco** donde los videos no explican algo y **[Visión]** donde es la opinión
de un orador.

## Límites

- **Solo lo que dicen los videos.** No incluye los ensayos de Paul Graham ni las guías escritas de YC salvo lo que se
  dice en cámara.
- **Sin diapositivas**: lo que estaba solo en pantalla (gráficos, tablas, mails de ejemplo) no está.
- **Lo legal y fiscal es de EE. UU.**, y mucho de 2014 (Delaware, 83(b)). Nada sobre incorporar u operar desde
  Latinoamérica u otros países. No es asesoría legal, contable ni de inversión.
- **Consejos que caducan**: modelos, precios y herramientas de IA de 2025 y 2026 cambian rápido.
- **Algunos oradores no dicen su nombre** en el video; la identificación es inferida y está marcada.
- Detalle completo: [wiki/99-fuentes-y-calidad.md](wiki/99-fuentes-y-calidad.md).

## Aviso

Proyecto personal, sin relación con Y Combinator. "Y Combinator", "YC" y "Startup School" son marcas de sus dueños.
Los videos son de YC y están gratis en su canal de YouTube; este repo no trae los videos ni las transcripciones,
solo notas, resúmenes y citas cortas con su fuente. Si sos de YC y querés que algo cambie, abrí un issue.

## Licencia

Las notas y la estructura de la wiki: [CC BY-NC 4.0](LICENSE). Podés usarla, copiarla y adaptarla citando este repo,
sin fines comerciales. Las citas de los videos siguen siendo de sus autores.
