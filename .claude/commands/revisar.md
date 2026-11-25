---
description: Revisión de campañas de un cliente (como en el proyecto de claude.ai)
argument-hint: <cliente> (p. ej. karama-candle, icon, irb-real-estate)
---

Haz la revisión diaria de campañas del cliente **$ARGUMENTS**.

1. Lee `clientes/$ARGUMENTS/historial.md` (sobre todo el último «ESTADO ACTUAL»), `clientes/$ARGUMENTS/ficha.md` y las campañas activas de `clientes/$ARGUMENTS/campanas/`. Si necesitas más contexto, consulta `clientes/$ARGUMENTS/conversaciones/claude-ai.md`. Si el nombre no coincide exactamente con una carpeta de `clientes/`, usa la que más se parezca.
2. Consulta su cuenta publicitaria con datos reales (no de memoria) y compárala con el estado y los pendientes.
3. Da conclusiones claras: qué funciona, qué no y por qué, con cifras.
4. Propón cambios numerados, ordenados por impacto. No apliques nada sin que te lo pida; si lo pido, déjalo en borrador.
5. Termina con un bloque «ESTADO ACTUAL»: qué hay activo, presupuestos, decisiones tomadas y próximo paso con fecha.
6. Actualiza `historial.md` (entrada con la fecha de hoy antes del bloque «ESTADO ACTUAL», y sustituye ese bloque) y, si cambió algo, `ficha.md` y `campanas/`. Después haz commit y push con un mensaje como «<Cliente>: revisión AAAA-MM-DD».

Reglas: no superar el presupuesto acordado; quitar Audience Network salvo que diga lo contrario; dar unos 7 días a una campaña nueva antes de juzgarla; en captación de leads importa más la calidad que el coste por lead.
