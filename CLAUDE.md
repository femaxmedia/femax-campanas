# femax-campanas — instrucciones para Claude

Repositorio privado de Femax Media con la información de las campañas publicitarias de cada cliente. Sustituye al proyecto «Campañas publicitarias» de Claude.ai.

## Idioma
- Todo en **español** (archivos, commits, respuestas).

## Organización
```
CLAUDE.md                     este archivo
README.md                     cómo clonarlo en un Mac nuevo
_plantillas/cliente.md        plantilla de ficha de cliente
_plantillas/campana.md        plantilla de campaña
_general/instrucciones-proyecto.md   instrucciones originales del proyecto de Claude.ai
_general/metodologia.md       cómo trabaja Femax las campañas (estructura, nomenclatura, checklist)
clientes/<cliente>/ficha.md
clientes/<cliente>/campanas/AAAA-MM-<nombre>.md
clientes/<cliente>/historial.md
```

- Antes de trabajar en una campaña, lee `_general/instrucciones-proyecto.md`, `_general/metodologia.md` y la `ficha.md` del cliente.
- Nombres de carpeta y archivo: minúsculas, sin tildes, palabras separadas por guiones (`kruceros`, `icon-cuidado-del-cabello`).

## Cómo añadir
- **Cliente nuevo**: crea `clientes/<cliente>/`, copia `_plantillas/cliente.md` como `ficha.md` y crea un `historial.md` vacío con su título.
- **Campaña nueva**: copia `_plantillas/campana.md` a `clientes/<cliente>/campanas/AAAA-MM-<nombre>.md` (año y mes de inicio) y añade una línea en el `historial.md` del cliente.
- **Cambios y resultados**: siempre una entrada fechada en `historial.md` (`- AAAA-MM-DD: qué cambió / qué resultado`), la más reciente arriba. Actualiza también el bloque de resultados de la campaña.

## Reglas
- **Nunca secretos**: ni contraseñas, ni tokens, ni claves API, ni datos de pago. De las cuentas solo nombre e ID (ID de cuenta publicitaria, píxel, etc.).
- No inventar datos: si algo no está claro, márcalo con `[REVISAR]`.
- Commits en español, descriptivos (`Kruceros: añade campaña 2026-11 Miami`).
- No mezclar con `femax-os`: este repo es privado y no se publica.
