# Campañas publicitarias — Femax Media

Este repositorio es el proyecto «Campañas publicitarias» de claude.ai pasado a Claude Code. Sirve para hacer el seguimiento diario de las campañas publicitarias (Meta Ads y Google Ads) de los clientes de Femax Media. Hay una carpeta por cliente, igual que antes había un chat por cliente.

Responde siempre en **español**.

## Instrucciones del proyecto (las mismas que en claude.ai)

En cada revisión de un cliente:
1. Consulta su cuenta publicitaria con datos reales (no de memoria) y compárala con el estado y los pendientes de su carpeta.
2. Da conclusiones claras: qué funciona, qué no y por qué, con cifras.
3. Propón cambios numerados, ordenados por impacto.
4. Aplica cambios solo cuando Mili lo pida. Déjalos en borrador para que ella publique, salvo que diga que publiques tú.
5. Termina siempre con un bloque **«ESTADO ACTUAL»**: qué hay activo, presupuestos, decisiones tomadas y próximo paso con fecha.

Reglas generales: no superar el presupuesto acordado con cada cliente; quitar Audience Network salvo que Mili diga lo contrario; antes de juzgar una campaña nueva, darle unos 7 días; en captación de leads importa más la calidad (lo que diga el cliente) que el coste por lead. No programes recordatorios ni cambios si no te lo pide.

## Cómo está organizado

```
CLAUDE.md                               este archivo (se carga solo al abrir Claude Code aquí)
_general/
  instrucciones-proyecto.md             instrucciones originales de claude.ai, literales
  estado-de-campanas-2026-11-21.md      archivo de contexto del proyecto («Estado de campañas»)
  metodologia.md                        nomenclatura, estructura, checklist y umbrales por cliente
  conversaciones/                       chats generales del proyecto (integrar Claude en Femax OS, migración)
_plantillas/                            plantillas de ficha y de campaña
clientes/<cliente>/
  ficha.md                              negocio, cuentas (IDs), presupuesto, KPIs, tono
  historial.md                          log por fecha + último «ESTADO ACTUAL»
  campanas/AAAA-MM-<nombre>.md          una por campaña
  conversaciones/claude-ai.md           el chat completo de claude.ai de ese cliente (solo lectura)
```

Clientes: dtributos, icon, irb-real-estate, karama-candle, kruceros-com, mar-chancosa, medfiles-ai, owa-academy, par-servicios-inmobiliarios, tourbillon-bricks.

## Al empezar con un cliente

Lee, en este orden: `clientes/<cliente>/historial.md` (sobre todo el último «ESTADO ACTUAL»), `ficha.md`, las campañas activas de `campanas/` y, si hace falta más contexto, `conversaciones/claude-ai.md`. Para criterios generales, `_general/metodologia.md`.

El comando `/revisar <cliente>` hace la revisión completa siguiendo estas instrucciones.

## Al terminar una revisión

- En `historial.md`, añade una entrada `## AAAA-MM-DD` con puntos justo antes del bloque «ESTADO ACTUAL» (las fechas van en orden, la más reciente abajo) y sustituye ese bloque por el nuevo.
- Actualiza `ficha.md` y los archivos de `campanas/` si cambian presupuestos, estados o IDs. Campaña nueva → copia `_plantillas/campana.md` a `campanas/AAAA-MM-<nombre>.md`.
- Las conversaciones de `conversaciones/` no se editan: son el archivo histórico de claude.ai.
- Guarda en GitHub: `git add -A && git commit -m "<Cliente>: <qué cambió>" && git push`.

## Contexto que había en la memoria del proyecto

- Mili quiere poder hacer estas mismas consultas desde Femax OS (os.femaxmedia.com) para que su equipo también pueda hacerlas. Tiene el plan Max de Claude.
- Javi es el editor de vídeo de Tourbillon Bricks; Mili le pasa qué vídeos funcionan usando los títulos de los archivos en Drive.

## Reglas del repo

- **Nunca secretos:** ni contraseñas, ni tokens, ni claves API, ni datos de pago. De las cuentas, solo nombre e ID.
- No inventar datos: si algo no está claro, márcalo con `[REVISAR]`.
- Nombres de carpetas y archivos en minúsculas, sin tildes, con guiones.
- Este repo es privado. No mezclarlo con `femax-os`, que se publica en os.femaxmedia.com.
