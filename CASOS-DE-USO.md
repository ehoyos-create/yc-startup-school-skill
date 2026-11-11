# Casos de uso

Pedidos típicos, qué lee Claude para responderlos y cómo se ve la respuesta. Las respuestas de ejemplo están
resumidas; las reales traen más citas y la corrección completa.

Todas las revisiones siguen el mismo formato:

```
Veredicto: bien / corregir / no así, en una línea, con la razón principal.
Qué está bien: 1-3 puntos con cita.
Qué falta o falla: 1-3 puntos, cada uno con la regla, quién lo dice [YC]/[Visión] y la cita.
La corrección concreta: el texto reescrito, el número o el plan.
Siguiente paso: una acción con fecha.
Ojo: contradicción entre oradores, época o hueco que cambie la respuesta.
```

`[YC]` es consejo de los socios de YC; `[Visión]` es la opinión de un invitado (Musk, Thiel, Karpathy…).

---

## 1. Evaluar una idea

> Revisá mi idea con la mirada de YC: un copiloto de IA que les hace la conciliación bancaria a contadores de pymes.

**Lee:** `rapida/revision.md`, `rapida/ideas.md` (y `rapida/ia.md` porque es de IA).

**Cómo responde:** pide primero la etapa, si conocés el problema de primera mano y qué evidencia tenés. Después pasa
la idea por las 10 preguntas de Jared Friedman [SS 02] en una tabla (sí / no / no sé + evidencia), empezando por
founder-market fit. Suma el "why now" y el checklist de ideas de IA: ¿reemplaza trabajo que hoy alguien cobra?, ¿la
borra la próxima versión de un modelo grande? Cierra con "Siguiente paso: 10 conversaciones con contadores esta
semana, empezando por cómo hacen la conciliación hoy".

## 2. Guion de entrevistas con usuarios

> Armame el guion para mis primeras 10 entrevistas con usuarios.

**Lee:** `rapida/usuarios-y-mvp.md`.

**Cómo responde:** un guion que arranca con "Tell me how you do X today", cubre las seis preguntas de Gustaf
Alströmer [SS 10 @0:05:57] (qué es lo más difícil, por qué, con qué frecuencia, por qué importa, qué hacen hoy para
resolverlo) y pide ver el comportamiento (la pantalla, la planilla) y no presenta la idea hasta el final. Lista aparte las preguntas que
hay que evitar ("¿usarías…?", "¿pagarías…?"). Plan: 5 a 10 entrevistas por grupo, grabadas con permiso, y la síntesis.

## 3. Revisar un cold email

> Este es mi cold email a CTOs de fintech, ¿qué le cambiarías? *(pega el mail)*

**Lee:** `rapida/ventas-y-pricing.md`.

**Cómo responde:** primero el targeting (¿la persona tiene el problema, presupuesto y autoridad?) y después una tabla
con los 7 principios de Aaron Epstein [SS 21 @0:20:53] (objetivo concreto, humano, personalizado, corto, con
credibilidad, sobre el lector y no sobre vos, CTA claro), cada uno cumple / no cumple. Marca lo que suena a LLM, el largo
(ideal < 75 palabras) y el cierre ("Does this sound interesting?" → "Got 20 minutes to hop on a call this week?"
[SS 22 @0:05:31]). Devuelve el mail reescrito y un plan de 2 a 4 follow-ups.

## 4. Poner precio a un producto B2B

> Vendo un SaaS a clínicas, cobro 49 USD al mes. ¿Está bien?

**Lee:** `rapida/ventas-y-pricing.md`.

**Cómo responde:** arma la ecuación de valor con el champion (cuánto ahorra o gana la clínica por mes) y propone un
precio del 25 al 50% de ese valor [SS 24]. Revisa el margen bruto (80 a 90%, contando tokens y nube como costo) y
cambia el piloto gratis por un contrato pago con opción de salida. Si cobrás de menos, lo dice con la cita
[SS 18 @0:13:37].

## 5. Leer métricas y retención

> Esta es mi retención por cohorte semanal, ¿hay product-market fit? *(pega la tabla)*

**Lee:** `rapida/metricas.md`.

**Cómo responde:** hace la cuenta. Dice si la curva se aplana y en qué nivel, qué acción de valor conviene medir,
cuánto crecés por semana contra la referencia de 5 a 7% semanal, qué parte es orgánica y qué métricas son de vanidad
(registros, vistas, waitlist). Si no se aplana, el consejo es no gastar en growth todavía [HTSS 06 @0:05:59].

## 6. Levantar plata

> ¿Cuánto debería levantar y con qué cap? Tengo 8.000 USD de MRR creciendo 15% mensual.

**Lee:** `rapida/fondeo-y-yc.md`.

**Cómo responde:** qué riesgos pela esta ronda, cuánto necesitás para llegar al próximo hito, dilución objetivo de
10 a 20% y cómo funciona un SAFE con cap (con la cuenta hecha). Avisa que lo legal (Delaware, 83(b)) es de EE. UU. y
que no reemplaza a un abogado.

## 7. Revisar una aplicación a YC

> Revisá mi aplicación a YC. *(pega las respuestas)*

**Lee:** `rapida/fondeo-y-yc.md`.

**Cómo responde:** chequea que el lector pueda contestar las preguntas de Dalton Caldwell [SS 32]: quiénes son y cómo
se conocen, cuál es la idea, qué tienen hoy, qué evidencia hay de que la quieren, si son serios, qué es especial, y
que se pueda contar "a little story" [SS 32 @0:11:57]. Marca el riesgo más grande que ve YC (que no haya fundador
técnico), lo que suena a jerga y las afirmaciones sin evidencia. Devuelve las respuestas reescritas.

## 8. "¿Qué diría…?"

> ¿Qué diría Paul Graham de que mi cofundador trabaje medio tiempo?

**Lee:** `rapida/oradores.md` y `rapida/fundadores-y-equity.md`.

**Cómo responde:** `Paul Graham (HTSS, 2014) [YC]: idea + cita · Aplicado a tu caso · Ojo`. Si otro orador piensa
distinto (por ejemplo un socio de YC en Startup School), lo muestra en una línea y dice cuál usar. No inventa frases:
si PG no habló de eso en los videos, lo dice y ofrece al orador que sí.

## 9. Startup de IA

> ¿Tiene sentido un agente de IA para reclutamiento o me lo come OpenAI?

**Lee:** `rapida/ia.md`.

**Cómo responde:** separa lo que dice YC de las visiones de los invitados (Altman, Karpathy, Jeff Dean, Collison…),
con el año de cada una porque envejecen rápido. Revisa si reemplaza trabajo pagado, si la próxima versión de un modelo
lo vuelve gratis y dónde está la ventaja que no es solo técnica (datos, distribución, integración, confianza).

## 10. Primeras contrataciones

> Tengo 3 clientes pagos, ¿contrato un vendedor?

**Lee:** `rapida/equipo.md`.

**Cómo responde:** antes de contratar, el fundador vende hasta tener un proceso repetible [SS 18 @0:03:47]; pregunta
si hay product-market fit, si es una necesidad desesperada y si un agente lo puede cubrir. Si corresponde, cómo
reclutar (referidos probados, pendiente sobre logos) y cuánto equity.

---

## Lo que no hace

- **Asesoría legal, contable o de inversión.** Lo legal de los videos es de EE. UU. y en buena parte de 2014.
- **Inventar.** Si los videos no lo cubren, la respuesta dice "los videos no lo explican". Si Claude agrega algo
  propio, lo marca aparte como opinión.
- **Responder sobre otros contenidos de YC** (ensayos, guías escritas, la Library) que no se dicen en estos 84 videos.
