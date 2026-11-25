> Conversación completa exportada del proyecto «Campañas publicitarias» de claude.ai el 25 nov 2026. Solo lectura: lo nuevo va en ficha.md, historial.md y campanas/.

# Migración de proyecto a markdown

- Chat de claude.ai: https://claude.ai/chat/07595c69-721a-465c-bdfb-37d1f116605e
- Creado: 2026-11-25T11:14:23.949394Z · Actualizado: 2026-11-25T11:29:43.876490Z
- Mensajes: 6

---

## Mili · 2026-11-25 11:14

Voy a migrar todo este proyecto a un repositorio de archivos markdown. Exporta TODO lo que sabes de este proyecto (instrucciones del proyecto, archivos de conocimiento y lo relevante de las conversaciones) sin resumir de más ni inventar nada. Si algo no está claro, márcalo con [REVISAR].

Devuélvelo en bloques de código markdown, uno por archivo, con la ruta como título, en este orden:

1. _general/instrucciones-proyecto.md — las instrucciones del proyecto, literales.
2. _general/metodologia.md — cómo planteamos las campañas: estructura, nomenclatura, checklist, criterios de optimización.
3. Por cada cliente:
   - clientes/<cliente-en-minusculas-con-guiones>/ficha.md — negocio, oferta/productos, público, tono, plataformas y cuentas (solo nombres e IDs, nunca contraseñas ni tokens), presupuesto habitual, KPIs.
   - clientes/<cliente>/campanas/AAAA-MM-<nombre>.md — una por campaña: objetivo, fechas, plataforma, presupuesto, segmentación, creatividades y copys, resultados, aprendizajes, estado.
   - clientes/<cliente>/historial.md — cambios y resultados por fecha.

Empieza con una lista de los archivos que vas a generar. Si no cabe todo en una respuesta, para al final de un archivo y escribe «SIGUE» para que te pida la continuación.


---

## Claude · 2026-11-25 11:18

Voy a reunir el documento de estado, la memoria del proyecto y los chats de cada cliente antes de generar los archivos.

_Herramientas: Projects, Projects, memory__memory_read, claude_ai__recent_chats, claude_ai__recent_chats, claude_ai__read_conversation, claude_ai__read_conversation, claude_ai__read_conversation, claude_ai__read_conversation, claude_ai__read_conversation, memory__memory_read, claude_ai__read_conversation, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search, claude_ai__conversation_search_

Voy a generar el export en varias respuestas. He tomado los datos de las instrucciones del proyecto, del documento «Estado de campañas (21 nov 2026)», de los 11 chats del proyecto y de lo guardado sobre cada cliente. Lo que no está claro o se contradice va marcado con [REVISAR].

**Archivos que voy a generar**

```
_general/instrucciones-proyecto.md
_general/metodologia.md

clientes/medfiles-ai/ficha.md
clientes/medfiles-ai/campanas/2026-11-v6-fxm-winners-cp-usa.md
clientes/medfiles-ai/campanas/2026-11-retargeting-black-friday.md
clientes/medfiles-ai/historial.md

clientes/karama-candle/ficha.md
clientes/karama-candle/campanas/2026-09-v1-form-talleres.md
clientes/karama-candle/campanas/2026-09-v2-form-landing-velas.md
clientes/karama-candle/campanas/2026-11-v2-form-landing-recipientes.md
clientes/karama-candle/campanas/2026-11-v3-form-landing-velas.md
clientes/karama-candle/historial.md

clientes/dtributos/ficha.md
clientes/dtributos/campanas/2026-11-v2-dextremo.md
clientes/dtributos/campanas/2026-11-v1-david-bisbal.md
clientes/dtributos/campanas/2026-11-v1-delcanto.md
clientes/dtributos/campanas/2026-11-v2-la-otra-oreja.md
clientes/dtributos/campanas/2026-11-v1-depereza.md
clientes/dtributos/campanas/2026-11-v1-depereza-delcanto.md
clientes/dtributos/campanas/2026-11-gira-4t-2026.md
clientes/dtributos/historial.md

clientes/irb-real-estate/ficha.md
clientes/irb-real-estate/campanas/2026-11-v1-form-landing-captacion.md
clientes/irb-real-estate/campanas/2026-11-v2-captacion-form-nativo.md
clientes/irb-real-estate/campanas/2026-11-v1-form-landing-casa-valldoreix.md
clientes/irb-real-estate/campanas/2026-11-v1-whatsapp-captacion.md
clientes/irb-real-estate/historial.md

clientes/par-servicios-inmobiliarios/ficha.md
clientes/par-servicios-inmobiliarios/campanas/2026-11-v1-captacion.md
clientes/par-servicios-inmobiliarios/historial.md

clientes/mar-chancosa/ficha.md
clientes/mar-chancosa/campanas/2026-10-google-ads-tienda.md
clientes/mar-chancosa/campanas/2026-11-microlineas-2026-11.md
clientes/mar-chancosa/campanas/2026-11-nexaleads-microlineas.md
clientes/mar-chancosa/campanas/2026-11-extensiones.md
clientes/mar-chancosa/campanas/2026-11-stop-and-grow.md
clientes/mar-chancosa/campanas/2026-11-balayage.md
clientes/mar-chancosa/historial.md

clientes/icon/ficha.md
clientes/icon/campanas/2026-11-black-month.md
clientes/icon/campanas/2026-11-india-v2.md
clientes/icon/campanas/2026-11-v1-retargeting-black-month-nov.md
clientes/icon/campanas/2026-11-google-pmax-gmcnuevo-campana-ganadora.md
clientes/icon/historial.md

clientes/tourbillon-bricks/ficha.md
clientes/tourbillon-bricks/campanas/2026-11-c1-bfcm26-prospeccion.md
clientes/tourbillon-bricks/campanas/2026-11-c2-bfcm26-testing.md
clientes/tourbillon-bricks/campanas/2026-11-c3-bfcm26-retargeting.md
clientes/tourbillon-bricks/campanas/2026-11-google-bfcm26-pmax-usa-uk.md
clientes/tourbillon-bricks/historial.md

clientes/owa-academy/ficha.md
clientes/owa-academy/campanas/2026-10-v1-octubre-lead-magnet.md
clientes/owa-academy/campanas/2026-04-webinar.md
clientes/owa-academy/historial.md

clientes/kruceros-com/ficha.md
clientes/kruceros-com/campanas/2026-11-meta-campanas-activas.md
clientes/kruceros-com/campanas/2026-11-chatgpt-ads-test.md
clientes/kruceros-com/campanas/google-ads-pmax-branding.md
clientes/kruceros-com/historial.md
```

En Kruceros he juntado las 11 campañas de Meta en un solo archivo. De cada una solo tengo una fila de cifras, así que no daban para un archivo propio. Si las quieres separadas, las separo.

---

### _general/instrucciones-proyecto.md

```markdown
# Instrucciones del proyecto «Campañas publicitarias»

## Descripción del proyecto
Seguimiento diario de las campañas de Meta Ads y Google Ads de los clientes de Femax Media: un chat por cliente con su estado y próximo paso.

## Instrucciones (literales)
Este proyecto sirve para hacer el seguimiento diario de las campañas publicitarias (Meta Ads y Google Ads) de los clientes de Femax Media. Hay un chat por cliente; el archivo de contexto "Estado de campañas" recoge el estado de cada uno a 21 nov 2026 y su próximo paso.

En cada revisión de un cliente:
1. Consulta su cuenta publicitaria con datos reales (no de memoria) y compárala con el estado y los pendientes de ese chat.
2. Da conclusiones claras: qué funciona, qué no y por qué, con cifras.
3. Propón cambios numerados, ordenados por impacto.
4. Aplica cambios solo cuando te lo pida. Déjalos en borrador para que yo publique, salvo que te diga que publiques tú.
5. Termina siempre con un bloque "ESTADO ACTUAL": qué hay activo, presupuestos, decisiones tomadas y próximo paso con fecha.

Reglas generales: no superar el presupuesto acordado con cada cliente; quitar Audience Network salvo que diga lo contrario; antes de juzgar una campaña nueva, darle unos 7 días; en captación de leads importa más la calidad (lo que diga el cliente) que el coste por lead. No programes recordatorios ni cambios si no te lo pido.
```

### _general/metodologia.md

```markdown
# Metodología de campañas — Femax Media

Recopilado de las instrucciones del proyecto y de lo que se ha hecho y decidido en los chats de cada cliente (nov 2026). Donde algo es práctica observada y no una regla dicha expresamente, se indica.

## 1. Organización del proyecto
- Un chat por cliente activo, con el mismo nombre que el cliente tiene en Femax OS. En el proyecto solo están los chats de los clientes activos. GymxTherapy todavía no tiene chat.
- Punto de partida común: documento «Estado de campañas (21 nov 2026)».
- Cada chat se inició con un «📌 BRIEF ACTUALIZADO (21 nov 2026)» del cliente. Después se añadieron «📌 AÑADIDO AL BRIEF» y «📌 CORRECCIÓN AL BRIEF» con información sacada de chats antiguos.
- Todas las clientas llevan Meta Ads; algunas también Google Ads o ChatGPT Ads.
- 24 nov 2026: Mili quiere poder hacer estas mismas consultas desde Femax OS (os.femaxmedia.com) para que también las haga su equipo. Propuesta en el chat «Integrar Claude en app propia»: guardar el «ESTADO ACTUAL» de cada revisión en Supabase y más adelante montar un chat propio. Sin decisión cerrada. [REVISAR]
- Reparto de herramientas propuesto en ese chat (propuesta de Claude, no decisión confirmada): revisiones de campañas en este proyecto; edición de vídeo, imágenes en serie y desarrollo de Femax OS en Claude Code; estáticas y propuestas editables en Claude Design. [REVISAR]
- 25 nov 2026: el proyecto se migra a markdown en el repo privado de GitHub `femaxmedia/femax-campanas`, con clon local en el Mac para Claude Code. No va en `femax-os` porque ese repo se publica en os.femaxmedia.com.

## 2. Flujo de cada revisión
1. Leer el estado y los pendientes del chat o archivo del cliente.
2. Consultar la cuenta con datos reales (conector de Meta Ads; Google Ads por el conector o por el navegador de la app de Claude, donde está iniciada la sesión de Google).
3. Conclusiones con cifras: qué funciona, qué no y por qué.
4. Cambios propuestos, numerados por impacto.
5. Aplicar solo cuando Mili lo pida, en borrador. Mili publica, salvo que diga lo contrario.
6. Cuando Mili publica, comprobar que no quedan borradores pendientes y que los cambios están como se acordaron.
7. Cerrar siempre con «ESTADO ACTUAL»: qué hay activo, presupuestos, decisiones tomadas y próximo paso con fecha.

## 3. Reglas generales (de las instrucciones)
- No superar el presupuesto acordado con cada cliente.
- Quitar Audience Network salvo que Mili diga lo contrario.
- Dar unos 7 días a una campaña nueva antes de juzgarla.
- En captación de leads importa más la calidad (lo que diga el cliente) que el coste por lead.
- No programar recordatorios ni cambios sin que Mili lo pida.

## 4. Nomenclatura (práctica observada)
Las campañas no siguen un formato único. Estos son los patrones que se repiten:
- **Campañas:** versión + objetivo/destino + producto o zona, separados por « | ».
  - `V.1 | FORM | LANDING` (IRB), `V.2 | CAPTACIÓN | FORM NATIVO` (IRB), `V.1 | CAPTACIÓN` (PAR), `V.3 | FORM | LANDING | VELAS` (Karama), `V.6 | [FxM] WINNERS | CP | USA` (MedFiles), `V.1 | [FxM] RETARGETING | BLACK MONTH | NOV` (ICON), `C1 · BFCM26 PROSPECCIÓN` (Tourbillon), `BFCM26 | PMax | USA+UK` (Tourbillon, Google), `[LEADS][Balayage][CBO]` (Mar Chancosa).
  - `[FxM]` = Femax Media. Para versiones nuevas de la misma campaña se sube el número (V.1 → V.2).
- **Conjuntos:** zona + destino (+ versión).
  - `BARCELONA | FORM NATIVO`, `BARCELONA | LANDING | FORMULARIO`, `MADRID | FORMULARIO NATIVO V5`, `BILBAO | TALLERES VELAS`, `AB | USA`, `BF | USA`, `CARRITO 60D + SEGUIDORES 180D | EXCL. COMPRAS 60D`, `V.2 | [Women][18-50][Valencia][+30km]`.
- **Anuncios:** `AD N` (vídeo), `IMG N` (estática), `VID N | …`, con sufijos de oferta o versión: `IMG 1 | BF`, `IMG 2 | BM | CHAMPÚS`, `AD 4 | CAPTACIÓN | V2 (post nuevo)`, `[3x2] BF27 - 4_v1`, `AD6_2026_MECHAS`, `IMG 4 | POST ORIGINAL`.
- **UTM (ejemplo de Mar Chancosa):** `utm_source=FacebookAds&utm_medium=PaidMedia&utm_campaign=[LEADS][Balayage][CBO]&utm_term=[Women][18-50][Valencia][+30km]&utm_content=AD6_2026+MECHAS`. [REVISAR: no sé si es un estándar para todos los clientes]

## 5. Estructura habitual (práctica observada)
- **Captación de leads (servicios):** una campaña con objetivo leads y uno o dos conjuntos por destino (formulario nativo de Meta y/o landing con formulario). Cuando la landing no convierte, se concentra todo en un único conjunto de formulario nativo (IRB V.2, PAR V5).
- **Inmobiliarias:** categoría especial de anuncios «Vivienda» (HOUSING, España). Eso obliga a radios mínimos (IRB: Barcelona +25 km en compradores; luego +30 km) y encarece el CPM (PAR ~37 €).
- **Presupuestos pequeños (15–20 €/día):** no abrir campañas nuevas. Meter las creatividades nuevas en un conjunto nuevo dentro de la campaña que ya funciona, para no repartir el presupuesto ni empezar el aprendizaje de cero (MedFiles, Karama).
- **Presupuesto a nivel de campaña (CBO):** si un conjunto nuevo no recibe gasto porque el histórico se lo lleva el ganador, se le pone un gasto mínimo diario (MedFiles: 60 % para `BF | USA`).
- **Retargeting:** campaña aparte y pequeña (4–5 $/día en MedFiles; 5 €/día en ICON), con mensaje de oferta y excluyendo a quien ya compró o se registró.
- **Ecommerce:** prospección, testing y retargeting separados (Tourbillon C1/C2/C3). Ofertas en anuncios etiquetados por oferta ([20], [3x2]).
- **Publicaciones existentes:** para no perder likes y comentarios, reutilizar la publicación original de un anuncio ganador («Usar publicación existente»). Si un anuncio acumula malos comentarios, se crea una publicación nueva con la misma creatividad (IRB AD 4 V2).

## 6. Checklist antes de publicar (práctica observada)
- [ ] Ubicaciones: solo Facebook e Instagram (sin Audience Network ni Threads), salvo excepción acordada.
- [ ] Presupuesto dentro de lo acordado con el cliente (sumar todas las campañas activas).
- [ ] Segmentación: zona, edad y sexo como estaban, salvo cambio decidido. Revisar si Advantage+ Audience está activado o no.
- [ ] Destino correcto (formulario nativo concreto o URL de la landing con UTM).
- [ ] Píxel o conversión: comprobar con un envío de prueba que se registra el evento («Lead», «Registro completado», «Compra»).
- [ ] Creatividades: formatos 4:5 y 9:16; comprobar el recorte en stories y reels.
- [ ] Sin títulos duplicados ni errores en el borrador (MedFiles IMG 1 | BF tenía dos títulos iguales).
- [ ] En vídeos con comentarios negativos: quitar «Comentarios relevantes» a mano en el Administrador (por API no se puede).
- [ ] Publicar solo lo que toca: revisar «Revisar y publicar» para no sacar borradores de otras campañas.
- [ ] Al relanzar: publicar la nueva antes de pausar la antigua, para no dejar horas sin anuncios activos.
- [ ] Comprobar que el lead entra donde debe (Google Sheets, GHL/LeadConnector, ActiveCampaign).
- [ ] Algunas cuentas (MedFiles) piden la aprobación de otra persona con permisos antes de publicar anuncios.

## 7. Criterios de optimización
- **Esperar:** unos 7 días antes de juzgar una campaña o conjunto nuevo. No tocar nada en ese periodo, porque cada cambio reinicia el aprendizaje. No juzgar el primer día de una publicación por la tarde.
- **Pausar anuncios:** cuando superan el umbral de coste del cliente con un gasto razonable (Karama > 8 €/lead; MedFiles > 10 $/registro en BF; Tourbillon > 90 € sin ventas).
- **Escalar:** subidas del 20–25 % cada día o cada pocos días, para no tumbar el aprendizaje (ICON Black Month 38 → 45 → 54 → 65 €).
- **Fatiga:** vigilar la frecuencia en públicos pequeños (Karama, 5 km en Bilbao: frecuencia ~3,6). Ampliar el radio o renovar las creatividades.
- **Audience Network:** infla los clics sin leads (IRB y PAR). Si se mantiene por excepción (ICON, 1,4 % del gasto antes de Black Friday), revisarlo después.
- **Destinos:** comparar formulario nativo y landing por coste por lead y por la calidad que valora el cliente. Los cambios de destino en Mar Chancosa se hablan antes con Daniel.
- **Ecommerce:** ROAS por anuncio frente al mínimo del cliente. El ROAS «real» se calcula con los pedidos de WooCommerce por origen, porque los píxeles infravaloran las ventas (ICON/Mar Chancosa).
- **Presupuesto mensual cerrado (PAR):** calcular el diario con lo que queda del mes y dejar margen, porque Meta puede gastar algo más que el diario.

## 8. Umbrales por cliente (resumen)
| Cliente | Métrica | Verde | Naranja / límite |
|---|---|---|---|
| MedFiles | Coste por registro (Meta) | < 8 $ | BF: apagar > 10 $ |
| MedFiles | Coste por suscripción (Google) | ~4 $ | — |
| Karama | CPL | < 5 € | 6–8 €; apagar > 8 € |
| OWA | CPL | < 3 € | 4–6 € naranja; más, alarmante |
| Kruceros | CPL | — | ningún lead > 2 € |
| Tourbillon | ROAS por anuncio | ≥ 2,26 | > 90 € sin ventas → pausa |
| ICON / Mar Chancosa | ROAS | ≥ 4 (ICON quiere 4,5) | — |
| IRB | Criterio para subir (1 dic) | ≥ 5 leads buenos/semana (~35 €/lead) | < 3 leads → revisar anuncios |
| DTributos | CPL conjunta DEPEREZA + DELCANTO | ~10 € | si no baja → pausar |

## 9. Fechas
[REVISAR] Algunos chats y el documento de estado ponen el día de la semana mal: el 24 nov 2026 es martes (no lunes), el 1 dic 2026 es martes (no lunes) y el 26 nov es jueves (no miércoles). Se han copiado tal cual donde aparecen.
```

---

### clientes/medfiles-ai/ficha.md

```markdown
# MedFiles.ai — ficha

## Negocio
- App de MedFiles.ai para centralizar historiales médicos (y también pólizas de seguro).
- Dueño: Manu (Manuel Guerra-Mondragón).
- En un chat se le llamó por error «MailerFine». [REVISAR: confirmar que «MailerFine» siempre se refiere a MedFiles]

## Oferta / productos
- Prueba gratis (registro) y suscripción, con plan anual.
- Black Friday 2026: 50 % de descuento en el plan anual. En Meta se sigue buscando el registro gratis.

## Público
- Meta: USA (conjuntos «AB | USA» y «BF | USA»). Más detalle de la segmentación: [REVISAR]

## Tono
- Con Manu: hablarle directamente (no en tercera persona), destacar los beneficios para él y para MedFiles, no nombrar otras empresas ni clientes y no hacer estimaciones sin base.
- Guiones orgánicos: los graba Manu a cámara, deben sonar improvisados, storytelling viral, temas de salud generales; sin el tema de «preguntarle a la IA». CTA «start your free trial».

## Plataformas y cuentas
- Meta: «Medfiles.ai + Ads» — 1277401451109459 (en dólares). Business ID 2380159649082029.
- Otras cuentas Meta del negocio, vacías y sin gasto: 2052270648658517 y 1498605165279583. [REVISAR: confirmar que son de MedFiles]
- Google Ads: Femax la lleva. ID de cuenta: [REVISAR]
- Web y landing: medfiles.ai/en

## Presupuesto habitual
- Meta: 15–20 $/día (confirmado por Mili: dólares).

## KPIs
- Meta: coste por registro («Registro completado») por debajo de 8 $.
- Google: unos 4 $ por suscripción está bien.

## Notas
- Oct 2026: Mili decidió separar las creatividades de móvil (las ganadoras) en una campaña propia y el resto en otra.
- Las fechas de fin de campaña las pone Mili a mano.
- Pendiente de confirmar con Manu si el pago de la suscripción se registra como evento (si es así, el retargeting podría optimizar a pago). [REVISAR]
```

### clientes/medfiles-ai/campanas/2026-11-v6-fxm-winners-cp-usa.md

```markdown
# V.6 | [FxM] WINNERS | CP | USA

- **Plataforma:** Meta Ads — cuenta 1277401451109459
- **ID de campaña:** 120251591458360676
- **Objetivo:** registros gratis (prueba). Evento «Registro completado».
- **Fechas:** inicio [REVISAR]; sin fecha de fin (la pone Mili).
- **Presupuesto:** a nivel de campaña. 10 $/día hasta el 23 nov; 15 $/día desde el 23 nov.
- **Estado:** activa (a 24 nov 2026).

## Conjuntos
### AB | USA (ganadores)
- Anuncios activos:
  - IMG 4 | POST ORIGINAL — usa la publicación del IMG 4 histórico (228 registros a 4,35 $).
  - IMG 12 — 14 registros a 10,36 $.
  - IMG 7 — 4 registros a 10,95 $.
  - IMG 5 — casi sin gasto; se deja activo por decisión de Mili.
- IMG 4 duplicado antiguo: apagado.

### BF | USA (Black Friday) — ID 120252026732520676
- Misma segmentación que AB | USA. [REVISAR: detalle de la segmentación]
- 5 anuncios: IMG 1 | BF, IMG 2 | BF, IMG 4 | BF, IMG 5 | BF, IMG 7 | BF. Imagen de Black Friday, texto con la oferta y destino https://medfiles.ai/en
- Títulos de IMG 1 | BF: «Black Friday: Up to 50% Off» y «Free Account, No Card Required» (el segundo se cambió porque estaba duplicado).
- 24 nov: gasto mínimo diario medio del 60 % del presupuesto de la campaña (~9 $/día de 15 $). Mili lo publicó; no he podido ver en pantalla el 60 % aplicado. [REVISAR]

## Creatividades y copys
- Creatividades de Black Friday adaptadas por Mili. Copy completo: [REVISAR]

## Resultados
- Últimos 30 días (hasta ~21 nov): 22 registros por 271 $ → ~12,33 $/registro.
- 7 días antes de los cambios: ~70 $ y 3 registros → ~23 $/registro. Empeoró porque los ganadores estaban apagados (IMG 12 e IMG 7).
- 23 nov (un día): IMG 4 | POST ORIGINAL 15,96 $ y 1 registro; IMG 12 2,03 $ y 0; IMG 7 0,90 $ y 0; los 5 BF juntos 0,43 $ y 0.

## Aprendizajes
- Con presupuesto de campaña, Meta da casi todo al ganador histórico y un conjunto nuevo no recibe gasto. Hace falta un gasto mínimo para forzar la entrega del conjunto BF.
- Encender otra vez los ganadores apagados era la palanca principal para bajar el coste por registro.

## Próximo paso
- Jueves 26 nov: coste por registro de cada anuncio BF frente a los ganadores; apagar los BF que pasen de 10 $ con gasto suficiente. Si BF funciona, subirle el gasto para el fin de semana de Black Friday.
```

### clientes/medfiles-ai/campanas/2026-11-retargeting-black-friday.md

```markdown
# Retargeting Black Friday (planificada, no creada)

- **Plataforma:** Meta Ads — cuenta 1277401451109459
- **Estado:** pendiente. No está creada a 24 nov 2026.
- **Objetivo:** registro gratis (como captación). Se planteó optimizar a pago si se registra el evento de suscripción. [REVISAR]
- **Presupuesto previsto:** 4–5 $/día (total del cliente 15–20 $/día).
- **Segmentación prevista:**
  - Visitas a la web de los últimos 30 días.
  - Interacción con IG/FB de los últimos 60 días.
  - Si se puede: quien empezó la prueba gratis y no pagó.
  - Excluir a los ya registrados o suscritos.
- **Creatividades:** solo de Black Friday; mensaje directo a la oferta («50% en el plan anual, solo hasta X»).
- **Bloqueo:** faltan los públicos personalizados de visitantes web (30 días) y de interacción IG/FB (60 días).
- **Alternativa:** si los públicos salen muy pequeños, ir como un conjunto más dentro de la V.6.
```

### clientes/medfiles-ai/historial.md

```markdown
# MedFiles.ai — historial

## Oct 2026
- Mili separa las creatividades de móvil (ganadoras) en una campaña propia y el resto en otra.

## ~20–21 nov 2026
- Revisión en el Administrador (la cuenta aún no salía en el conector): solo activa la V.6 a 10 $/día; 22 campañas apagadas. 30 días: 22 registros a 12,33 $. 7 días: ~23 $/registro.
- Detectado: IMG 12 e IMG 7 apagados; borrador pendiente con error en un anuncio.
- Propuesta para Black Friday: sin campaña de captación nueva; conjunto «BF | USA» dentro de la V.6 (14–15 $/día) + retargeting aparte de 4–5 $/día.
- Mili confirma el presupuesto: 15–20 $/día (en dólares).
- Se encienden los ganadores. Queda así: IMG 4 | POST ORIGINAL, IMG 12, IMG 7 e IMG 5 activos; IMG 4 antiguo apagado.
- 21 nov: la cuenta ya se ve en el conector de Meta.

## 23 nov 2026
- Mili tiene las creatividades de BF y la oferta ya está activa.
- Borrador preparado: V.6 de 10 a 15 $/día; conjunto BF | USA activado con 5 anuncios BF hacia medfiles.ai/en; corregido el título duplicado de IMG 1 | BF.
- Mili publica. Sin borradores pendientes. Anuncios BF «En proceso» (revisión de Meta). La cuenta pide la aprobación de otra persona con permisos.

## 24 nov 2026
- Datos del 23 nov: los anuncios BF, aprobados, solo gastaron 0,43 $ en total; IMG 4 original se lleva casi todo.
- Borrador: gasto mínimo diario medio del 60 % para BF | USA (~9 $/día). Mili lo publica; sin borradores pendientes. No he podido ver en pantalla que el 60 % esté aplicado. [REVISAR]

## ESTADO ACTUAL (24 nov 2026)
- **Activo:** V.6 a 15 $/día con AB | USA (ganadores) y BF | USA (5 anuncios BF, mínimo del 60 %).
- **Pendiente:** públicos para el retargeting; que medfiles.ai/en mencione la oferta.
- **Próximo paso:** jueves 26 nov — coste por registro de cada anuncio BF; apagar los que pasen de 10 $ con gasto suficiente; si BF funciona, subirle el gasto para el fin de semana de BF.
```

---

### clientes/karama-candle/ficha.md

```markdown
# Karama Candle — ficha

## Negocio
- Talleres de velas y de recipientes en Bilbao. También tienda online en Shopify.
- Contactos: Rosario (titular; recibe los informes) y Asier (pareja de Rosario).

## Oferta / productos
- Talleres de velas: 9, 15 y 24 de enero, 18 plazas cada uno.
- Talleres de recipientes: 17 y 23 de enero, 15 plazas cada uno.
- Códigos de regalo KARAMA-XXXXXX (cupón de Stripe 3WAdb77B, compartido entre velas y recipientes), válidos para 1 plaza.
- Cambios de plazas: 7 nov, 2 plazas liberadas; 21 nov, 3 plazas de «Colaboración»; 26 dic, 1 plaza reservada aparte para Jennifer; recipientes del 28 nov limitado a 15.
- Objetivo: que se agoten los talleres.

## Público
- Mujeres de 18 a 65 años en Bilbao. Histórico: 5 km alrededor del Guggenheim (se satura). El 21 nov se propuso ampliar a 20 km (Gran Bilbao).

## Tono
- Reels: imitando una referencia que da Mili, con textos en los colores de su brandbook (rosa suave, crema, marrón) y tiempo suficiente para leerlos.
- Copy del vídeo UGC: «¿Buscas un plan diferente en Bilbao?» / «El plan perfecto en Bilbao».

## Plataformas y cuentas
- Meta: karamacandle — 26051144467865567
- Píxel: [FxM] TALLERES — 1640004717538673
- Landings: form.karamacandle.com (velas), formrecipientes.karamacandle.com (recipientes), /recipientes-registro.
- Backend de reservas en Vercel «karama-stripe-backend» (repo alejandrofemaxmedia-svg/karama-stripe-backend); plazas en api/_plazas.js; panel de plazas en Vercel enlazado en Notion.
- Email en GHL; leads en Google Sheet o GHL. [REVISAR: dónde entran los leads de cada destino]

## Presupuesto habitual
- Meta: 15–20 €/día en total (tope 20 €/día).

## KPIs
- CPL ideal < 5 €; 6–8 € naranja.
- Plazas vendidas por taller.

## Otros servicios de Femax
- Landings y web de experiencias, sistema de reservas con Stripe y Vercel, email en GHL (reseñas, newsletter, recordatorios), orgánico de Instagram (calendario ORG_MM_AAAA) y prospección B2B (empresas y ayuntamientos de Bizkaia).
```

### clientes/karama-candle/campanas/2026-09-v1-form-talleres.md

```markdown
# V.1 Form Talleres (formulario de Meta)

- **Plataforma:** Meta Ads — cuenta 26051144467865567
- **Objetivo:** leads con formulario instantáneo de Meta.
- **Fechas:** desde septiembre 2026. Fin: [REVISAR]
- **Presupuesto:** [REVISAR]
- **Segmentación:** [REVISAR]
- **Resultados (acumulado a 21 nov):** 291,69 € de gasto, 251 leads, 1,16 € por lead.
- **Aprendizajes:** el formulario de Meta daba leads a ~1 €, frente a 5–6 € con la landing. Queda por valorar la calidad (qué leads acababan comprando); lo decide Mili.
- **Estado:** no activa a 21 nov. [REVISAR: pausada o terminada]
```

### clientes/karama-candle/campanas/2026-09-v2-form-landing-velas.md

```markdown
# V.2 | FORM | LANDING | VELAS

- **Plataforma:** Meta Ads — cuenta 26051144467865567
- **Objetivo:** leads en landing (form.karamacandle.com).
- **Fechas:** desde el 30 sep 2026; pausada [REVISAR: fecha exacta].
- **Segmentación:** mujeres de 18 a 65 años, 5 km alrededor del Guggenheim.
- **Resultados acumulados (a 21 nov):** 436,33 €, 1.706 visitas a la landing, 68 leads, 6,42 € por lead.
- **Últimos 30 días (según el documento de estado):** 31 leads a 9,44 €.
- **Últimos 14 días antes del 21 nov:** ~12 € por lead (antes estaba en ~5 €).
- **Alcance:** 37.000 personas, frecuencia ~3,6.
- **Mejor anuncio:** IMG 2 — 50 leads a 5,18 € (dato del chat del 21 nov). El documento de estado dice «19 leads a 8,14 € en la V.2». [REVISAR: las dos cifras no coinciden; puede que sean periodos distintos]
- **Aprendizajes:** un público de 5 km se satura (frecuencia alta, coste en aumento).
- **Estado:** pausada.
```

### clientes/karama-candle/campanas/2026-11-v2-form-landing-recipientes.md

```markdown
# V.2 | FORM | LANDING | RECIPIENTES

- **Plataforma:** Meta Ads — cuenta 26051144467865567
- **ID de campaña:** 120250393473060467 · **ID de conjunto:** 120250393473110467 [REVISAR: confirmar que corresponden a recipientes]
- **Objetivo:** leads en la landing de recipientes (formrecipientes.karamacandle.com).
- **Fechas:** desde el 18 nov 2026; pausada el 21 nov.
- **Presupuesto:** 10 €/día. Hubo un borrador a 8 €/día con 20 km que quedó sin uso y había que descartarlo. [REVISAR: confirmar que se descartó]
- **Segmentación:** mujeres de 18 a 65 años, 5 km alrededor del Guggenheim.
- **Resultados:**
  - Chat del 21 nov: 27,57 €, 53 visitas, 0 leads atribuidos.
  - Brief del 21 nov: 21,70 €, 46 visitas, 0 leads reales.
  - Documento de estado: 25 € y 50 visitas, 0 leads.
  - El píxel registró leads en formrecipientes.karamacandle.com: 15 el 17 nov (antes de lanzar, seguramente pruebas) y 5 el 20 nov. [REVISAR: si fueron leads reales u orgánicos]
- **Problemas detectados y arreglados:** 404 en /recipientes-registro; el evento Lead ahora se dispara en la landing al enviar.
- **Decisión (21 nov):** Meta se centra solo en velas; recipientes pausada. Revisar la landing y el formulario de recipientes antes de relanzar.
- **Estado:** pausada.
```

### clientes/karama-candle/campanas/2026-11-v3-form-landing-velas.md

```markdown
# V.3 | FORM | LANDING | VELAS

- **Plataforma:** Meta Ads — cuenta 26051144467865567
- **ID de campaña:** 120250855852150467 · **Conjunto «BILBAO | TALLERES VELAS»:** 120250855852230467
- **Objetivo:** leads en landing — form.karamacandle.com. Píxel [FxM] TALLERES.
- **Fechas:** desde el 20 nov 2026.
- **Presupuesto:** 15 €/día al inicio. El 21 nov por la mañana quedó un borrador a 12 €/día con 20 km. Según el documento de estado (21 nov), 18 €/día. [REVISAR: confirmar el presupuesto publicado]
- **Segmentación (documento de estado):** mujeres de 18 a 65 años a 5 km del Guggenheim, solo Facebook e Instagram. El borrador del 21 nov proponía 20 km (Gran Bilbao), sin Advantage+ Audience. [REVISAR: radio publicado]

## Creatividades
- IMG 1 (se llevaba el 70 % del gasto el 21 nov).
- IMG 2: misma imagen que el IMG 2 ganador de la V.2, pero en una publicación nueva, sin likes ni comentarios. Se recomendó añadir la publicación antigua («Crea tus propias velas en Bilbao», 19 nov) con «Usar publicación existente». [REVISAR: si se hizo]
- IMG 3.
- IMG 4 Navidad.
- VID 1 | COLABORACIÓN: reel UGC de la creadora Maider subido directamente. Texto propio «¿Buscas un plan diferente en Bilbao?», título «El plan perfecto en Bilbao», sin extensiones de catálogo.

## Resultados
- A 21 nov: 9,84 €, 21 visitas, 0 leads (brief: 5,90 € y 0 leads; recién arrancada).

## Próximo paso
- Mié 26 – jue 27 nov [REVISAR: el 26 es jueves]: revisar el coste por lead de cada anuncio y apagar los que pasen de 8 € con gasto razonable. No tocar antes.
- Ver el CPL del reel de Maider y confirmar que los leads se registran bien tras el arreglo del píxel.

## Estado
- Activa.
```

### clientes/karama-candle/historial.md

```markdown
# Karama Candle — historial

## Sep 2026
- V.1 Form Talleres (formulario de Meta): 251 leads a 1,16 €.
- 30 sep: V.2 Landing Velas.

## 18 nov 2026
- Lanzada V.2 Landing Recipientes a 10 €/día.

## 20 nov 2026
- Lanzada V.3 Landing Velas a 15 €/día.

## 21 nov 2026
- Revisión: el presupuesto total (25 €/día) superaba el tope de 20 €; el público de 5 km estaba saturado (V.2 velas: 37.000 personas, frecuencia 3,6, CPL ~12 € en 14 días); el IMG 2 ganador no está con su publicación original en la V.3; recipientes con 0 leads atribuidos.
- Borradores: velas a 12 €/día y 20 km; recipientes a 8 €/día y 20 km (Advantage+ Audience desactivado, mujeres de 18 a 65 años).
- Recomendación: no lanzar una tercera campaña; añadir la publicación antigua del IMG 2; valorar el formulario de Meta para Navidad (lo decide Mili).
- Decisión de Mili: Meta solo en velas; recipientes pausada; reel de Maider como anuncio nuevo. Se arreglan el 404 en /recipientes-registro y el disparo del Lead.
- Prioridades: subir velas a 15–20 €/día y quitar Audience Network; descartar el borrador de recipientes; bajar los 11 s de carga del checkout.
- Documento de estado: V.3 a 18 €/día, solo FB e IG, 5 km, con IMG 1–4 y VID 1 | COLABORACIÓN. [REVISAR: no coincide con el borrador de 12 € y 20 km; vale lo que esté publicado]

## ESTADO ACTUAL (21 nov 2026, según el documento de estado)
- **Activa:** V.3 | FORM | LANDING | VELAS, conjunto BILBAO | TALLERES VELAS, 18 €/día, solo FB e IG.
- **Pausada:** V.2 | FORM | LANDING | RECIPIENTES.
- **Próximo paso:** 26–27 nov, revisar el CPL de cada anuncio y apagar los que pasen de 8 € con gasto razonable.
- **Pendientes fuera de Meta:** velocidad del checkout (~11 s), respuestas de los ayuntamientos (112 contactos), calendario orgánico.
```

---

### clientes/dtributos/ficha.md

```markdown
# DTributos (La Noche del Pop) — ficha

## Negocio
- Tributos musicales. El portfolio empresarial y la cuenta publicitaria se llaman «La Noche del Pop».
- Tributos: DEPEREZA, DELCANTO, DEXTREMO, DAVID BISBAL, LA OTRA OREJA.

## Oferta
- Contratación de los tributos (campañas para conseguir contrataciones). [REVISAR: público objetivo, p. ej. ayuntamientos o empresas de eventos]

## Público
- [REVISAR]

## Tono
- Los copies son iguales entre tributos, adaptados a cada uno.

## Plataformas y cuentas
- Meta: La Noche del Pop — 848182694140313
- También existen DELCANTO PUBLICIDAD (1138243897935131) y LA OTRA OREJA (495960313583148).
- Leads: formulario instantáneo → Google Sheet «LEADS - DTRIBUTOS», una pestaña por tributo.

## Presupuesto habitual
- 10 €/día por campaña (6 campañas, ~60 €/día). Tope acordado con el cliente: [REVISAR]

## KPIs
- CPL por tributo, y sobre todo la calidad de los leads en el Sheet.

## Forma de trabajar
- Mili deja las campañas en borrador y las publica ella.
```

### clientes/dtributos/campanas/2026-11-v2-dextremo.md

```markdown
# V.2 DEXTREMO

- **Plataforma:** Meta Ads — 848182694140313
- **Objetivo:** leads de contratación (formulario instantáneo → Sheet, pestaña DEXTREMO).
- **Presupuesto:** 10 €/día. Propuesto subir a 13 €/día (lo aplica Mili). [REVISAR: si se aplicó]
- **Resultados (7 días a 21 nov):** 70,51 €, 17 leads, 4,15 € por lead. La mejor con diferencia.
- **Aprendizajes:** usarla como referencia de creativo y copy para BISBAL, DELCANTO y LA OTRA OREJA. Falta ver qué anuncio y texto concretos funcionan. [REVISAR]
- **Estado:** activa.
```

### clientes/dtributos/campanas/2026-11-v1-david-bisbal.md

```markdown
# V.1 DAVID BISBAL

- **Plataforma:** Meta Ads — 848182694140313
- **Objetivo:** leads de contratación (formulario instantáneo → Sheet).
- **Presupuesto:** 10 €/día.
- **Resultados (7 días a 21 nov):** 66,29 €, 9 leads, 7,37 € por lead.
- **Estado:** activa.
```

### clientes/dtributos/campanas/2026-11-v1-delcanto.md

```markdown
# V.1 DELCANTO

- **Plataforma:** Meta Ads — 848182694140313
- **Objetivo:** leads de contratación (formulario instantáneo → Sheet).
- **Presupuesto:** 10 €/día.
- **Resultados (7 días a 21 nov):** 70,86 €, 9 leads, 7,87 € por lead.
- **Nota:** si la conjunta DEPEREZA + DELCANTO no baja de ~10 €/lead, se queda DELCANTO sola.
- **Estado:** activa.
```

### clientes/dtributos/campanas/2026-11-v2-la-otra-oreja.md

```markdown
# V.2 LA OTRA OREJA

- **Plataforma:** Meta Ads — 848182694140313
- **Objetivo:** leads de contratación (formulario instantáneo → Sheet).
- **Presupuesto:** 10 €/día.
- **Resultados (7 días a 21 nov):** 70,18 €, 8 leads, 8,77 € por lead.
- **Estado:** activa.
```

### clientes/dtributos/campanas/2026-11-v1-depereza.md

```markdown
# V.1 DEPEREZA

- **Plataforma:** Meta Ads — 848182694140313
- **Objetivo:** leads de contratación (formulario instantáneo → Sheet).
- **Presupuesto:** 10 €/día.
- **Resultados (7 días a 21 nov):** 66,71 €, 2 leads, 33,36 € por lead. La peor.
- **Decisión propuesta:** pausarla porque se solapa con la conjunta DEPEREZA + DELCANTO. Libera 10 €/día. Lo aplica Mili. [REVISAR: si se pausó]
- **Estado:** activa a 21 nov; pausa pendiente.
```

### clientes/dtributos/campanas/2026-11-v1-depereza-delcanto.md

```markdown
# V.1 DEPEREZA + DELCANTO (conjunta)

- **Plataforma:** Meta Ads — 848182694140313
- **Objetivo:** leads de contratación (formulario instantáneo → Sheet).
- **Fechas:** publicada el 19 nov 2026.
- **Presupuesto:** 10 €/día.
- **Resultados (a 21 nov):** 13,81 €, 1 lead, 13,81 € por lead. Aún en aprendizaje.
- **Próximo paso:** miércoles 26 nov [REVISAR: el 26 es jueves]: si no baja de ~10 €/lead, pausarla y quedarse con DELCANTO sola.
- **Estado:** activa.
```

### clientes/dtributos/campanas/2026-11-gira-4t-2026.md

```markdown
# GIRA 4T 2026

- **Plataforma:** Meta Ads — 848182694140313
- **Objetivo:** visitas al perfil.
- **Resultados (7 días a 21 nov):** 3,53 €, 33 visitas, 0,11 € por visita.
- **Problema:** tiene conjuntos con fechas ya pasadas.
- **Decisión propuesta:** pausarla (lo aplica Mili). [REVISAR: si se pausó]
- **Estado:** activa a 21 nov; pausa pendiente.
```

### clientes/dtributos/historial.md

```markdown
# DTributos (La Noche del Pop) — historial

## 19 nov 2026
- Publicada V.1 DEPEREZA + DELCANTO a 10 €/día.

## 21 nov 2026
- 7 días: ~362 € y 46 leads. DEXTREMO 17 a 4,15 €; BISBAL 9 a 7,37 €; DELCANTO 9 a 7,87 €; LA OTRA OREJA 8 a 8,77 €; DEPEREZA + DELCANTO 1 a 13,81 €; DEPEREZA 2 a 33,36 €; GIRA 4T 33 visitas a 0,11 €.
- Propuesto (lo aplica Mili): pausar V.1 DEPEREZA, subir DEXTREMO a 13 €/día, pausar GIRA 4T.
- Prioridades: revisar la calidad de los leads en el Sheet pestaña por pestaña antes de escalar DEXTREMO; usar DEXTREMO como referencia de copy y creativo.
- No consta si Mili aplicó los cambios. [REVISAR]

## ESTADO ACTUAL (21 nov 2026)
- **Activo:** 6 campañas de contratación a 10 €/día (+ GIRA 4T, pendiente de pausar).
- **Decisiones pendientes de aplicar por Mili:** pausar DEPEREZA, DEXTREMO a 13 €, pausar GIRA 4T.
- **Próximo paso:** 26 nov, revisar la conjunta DEPEREZA + DELCANTO (≤ ~10 €/lead o se pausa).
```

SIGUE


---

## Mili · 2026-11-25 11:21

SIGUE


---

## Claude · 2026-11-25 11:23

### clientes/irb-real-estate/ficha.md

```markdown
# IRB Real Estate (Íñigo Raventós) — ficha

## Negocio
- Íñigo Raventós, IRB Real Estate. Inmobiliario de alto valor en Sant Gervasi, Sant Cugat y la zona alta de Barcelona. Más de 20 años gestionando patrimonio inmobiliario (según el copy de sus anuncios).
- Cliente de Femax Media desde octubre de 2026, con 1.250 €/mes + IVA y un plan de 180 días sin permanencia.
- Web: inigoraventos.com. Landing de propietarios: propietarios.irbrealestate.com.

## Oferta / servicios
- Captación de propietarios que quieren vender (prioridad), compradores (proyectos concretos, p. ej. Casa Valldoreix), inversión, financiación advisory y cambio de vivienda.

## Público
- Propietarios en Barcelona y Sant Cugat, de perfil alto.
- Meta en categoría especial «Vivienda»: Barcelona +17 km (V.1), +25 km (compradores) y +30 km (V.2).

## Tono
- Se le llama «asesor», no «agente». Tono no agresivo, sin dar datos de mercado que no sepamos.
- Anuncios de captación: segmentar desde el primer segundo, de 30 a 40 s, con CTA de rellenar el formulario. Música de lujo, muy baja y sin beats.
- Copy base de captación: «¿Estás pensando en vender tu propiedad en Barcelona o Sant Cugat? … Soy Íñigo Raventós y llevo más de 20 años gestionando patrimonio inmobiliario de alto valor… Rellena el formulario y hablamos de cómo vender tu propiedad.» Título: «Vende tu propiedad en Barcelona». Descripción: «Prepara hoy la venta de tu casa».

## Plataformas y cuentas
- Meta: IRB Real estate Company — 1431318505076377
- Página de Facebook 1424067984116743 · Instagram 17841437935237047
- Píxel de compradores: «IRB | WEB | Compradores Valldoreix» (ID: [REVISAR])
- Formulario nativo: «FxM | V.1 | CAPTACIÓN»
- GHL contratado como capa de captación. Su CRM Inmovilla no se usa en el proyecto.

## Presupuesto habitual
- Meta: 50 €/día en la V.1 (25 + 25). Desde el 24 nov, 25 €/día en la V.2, con la idea de subir si funciona. Tope acordado: [REVISAR]

## KPIs
- Leads de propietarios y su calidad según Íñigo.
- Criterio para el 1 dic: 5 o más leads buenos por semana (~35 €/lead) → subir a 35–50 €/día. Menos de 3 → revisar los anuncios.

## Pendientes generales
- Meta marca la cuenta sin método de pago: verificar la facturación. [REVISAR: si se ha resuelto]
```

### clientes/irb-real-estate/campanas/2026-11-v1-form-landing-captacion.md

```markdown
# V.1 | FORM | LANDING (captación de vendedores)

- **Plataforma:** Meta Ads — 1431318505076377
- **ID de campaña:** 120255739592970166
- **Objetivo:** leads de propietarios (categoría Vivienda).
- **Fechas:** desde el 17 nov 2026; pausada el 24 nov, al publicar la V.2.
- **Segmentación:** Barcelona +17 km (personas que viven allí o han estado hace poco). Solo Facebook e Instagram desde el 21 nov: se quitó Audience Network porque inflaba los clics, y con él desapareció Threads en la landing.

## Conjuntos
- **BARCELONA | FORM NATIVO:** 25 €/día. El 24 nov figuraba a 35 €/día. [REVISAR: cuándo cambió]
  - Anuncios: AD 4, AD 5, AD 6, IMG 1 Comparativa, IMG 2 Se vende casa, IMG 3. [REVISAR: lista exacta de estáticas]
- **BARCELONA | LANDING | FORMULARIO** (ID 120255739593060166): 25 €/día, luego 15 €/día. [REVISAR]
  - Anuncios: AD 4 | CAPTACIÓN | V2 (post nuevo), publicado el 21 nov porque el AD 4 original tenía malos comentarios. También AD 5, AD 6, AD 7 e IMG 1.
  - Destino: https://propietarios.irbrealestate.com/pgina-principal (CTA «Más información»).

## Resultados
- 17–21 nov: 8 leads (4 por formulario y 4 por landing), unos 21,5 € por lead en los dos destinos.
- AD 4 del formulario: 4 leads a 14,17 € según el documento de estado; en el chat del 24 nov, «4 leads a 19 €». [REVISAR]
- 21–24 nov: 0 leads con unos 159 € gastados. El último lead entró el 20 nov.
- Formulario: las estáticas suman unos 38 € sin leads. IMG 2 se llevó 30 € con un CTR del 1,5 %; IMG 1 tiene un CTR del 4,1 % con poco gasto. AD 6 gastó unos 7 € y AD 7 unos 21 €, ninguno con leads.

## Aprendizajes
- Audience Network traía clics de poca calidad.
- En el formulario solo los vídeos han traído leads.
- Íñigo dice que los leads son buenos, pero hace falta más volumen y a menor coste.
- Los cambios frecuentes pueden haber influido en el parón del fin de semana del 22–23 nov.

## Pendiente que quedó
- Quitar «Comentarios relevantes» en el AD 4 del formulario nativo (a mano).

## Estado
- Pausada (24 nov 2026).
```

### clientes/irb-real-estate/campanas/2026-11-v2-captacion-form-nativo.md

```markdown
# V.2 | CAPTACIÓN | FORM NATIVO

- **Plataforma:** Meta Ads — 1431318505076377
- **ID de campaña:** 120255877144810166
- **Objetivo:** OUTCOME_LEADS, categoría especial HOUSING (España).
- **Fechas:** publicada el 24 nov 2026 hacia las 19:00. Sin fecha de fin.
- **Presupuesto:** 25 €/día. El borrador empezó a 50 €/día; se preparó una subida a 35 € que se quitó del borrador por decisión de Mili («puedo empezar con 25, la idea es que entren un par al día y si es así subimos»).
- **Segmentación:** Barcelona +30 km (el borrador inicial tenía +25 km), público Advantage+ activado, solo Facebook e Instagram.
- **Destino:** formulario nativo «FxM | V.1 | CAPTACIÓN», el mismo que funcionaba en la V.1. No se cambia a uno de «más volumen» para no bajar la calidad.
- **Anuncios:** AD 4, AD 5, AD 6 (vídeos) e IMG 1 Comparativa (estática). La IMG 2 «Se vende casa» se cambió por el AD 6 porque fue la que peor lo hizo. El AD 7 queda fuera.
- **Pendiente manual:** quitar «Comentarios relevantes» en el AD 4 y el AD 5 (por API no se puede en vídeos). [REVISAR: si se hizo]

## Expectativa
- Con 25 €/día y leads a 20–40 €, lo realista es 1 lead al día o menos.

## Criterio de decisión
- Jueves 27 nov: mirar la entrega, sin tocar nada.
- Lunes 1 dic [REVISAR: el 1 dic es martes]: con 5 o más leads en la semana (~35 €/lead o menos) y buenos para Íñigo, subir a 35–50 €/día. Con menos de 3, revisar los anuncios antes de meter más presupuesto.
- Para más adelante: tener 1 o 2 vídeos nuevos de Íñigo a cámara con ganchos distintos (p. ej. «si tu casa lleva meses en el portal…»).

## Estado
- Activa. Anuncios en revisión a 24 nov. Sin cambios pendientes.
```

### clientes/irb-real-estate/campanas/2026-11-v1-form-landing-casa-valldoreix.md

```markdown
# V.1 | FORM | LANDING | CASA VALLDOREIX (compradores)

- **Plataforma:** Meta Ads — 1431318505076377
- **Objetivo:** leads de compradores para la Casa Valldoreix (categoría Vivienda).
- **Estado:** en BORRADOR, lista y sin errores. Sin fecha de publicación.
- **Presupuesto:** 25 €/día.
- **Segmentación:** Barcelona +25 km (mínimo por la categoría Vivienda). Sin in-stream, porque la imagen es vertical.
- **Píxel:** «IRB | WEB | Compradores Valldoreix».
- **Anuncios:** incluye «IMG 2 | COMPRADORES» (borrador; no publicar). Resto: [REVISAR]
- **Antes de publicar:** hacer un envío de prueba y comprobar que el píxel registra «Lead».
```

### clientes/irb-real-estate/campanas/2026-11-v1-whatsapp-captacion.md

```markdown
# V.1 | WHATSAPP | CAPTACIÓN (descartada)

- **Plataforma:** Meta Ads — 1431318505076377
- **Objetivo:** tráfico o conversaciones a WhatsApp con mensaje ya escrito.
- **Presupuesto previsto:** 15 €/día (con la V.2 a 35 €, 50 €/día en total).
- **Anuncios:** vídeos AD 4 y AD 5.
- **Pendiente antes de publicar (no llegó a hacerse):** confirmar quién responde el WhatsApp, Íñigo o el agente. Si no se responde en pocos minutos, se pierde la conversación.
- **Estado:** descartada el 24 nov 2026 (~19:30) y borrada del borrador. Decisión: solo formulario nativo; landing y WhatsApp fuera.
```

### clientes/irb-real-estate/historial.md

```markdown
# IRB Real Estate — historial

## Oct 2026
- Empieza con Femax (1.250 €/mes + IVA, plan de 180 días).

## Semana del 17 nov 2026
- Arranca la V.1 | FORM | LANDING (captación de propietarios): 2 conjuntos a 25 €/día, Barcelona +17 km.

## 21 nov 2026
- Revisión: unos 21,5 €/lead en los dos destinos (8 leads). Audience Network inflaba los clics.
- En borrador, y publicado por Mili: Audience Network fuera de los dos conjuntos (y Threads de la landing). Nuevo anuncio «AD 4 | CAPTACIÓN | V2 (post nuevo)» en la landing; el AD 4 antiguo sigue pausado.
- Compradores Casa Valldoreix: en borrador, sin fecha.

## 24 nov 2026
- 0 leads desde el 21 nov, con unos 159 € gastados. Íñigo: leads buenos, pero hace falta más flujo y menos coste.
- Se monta la V.2 | CAPTACIÓN | FORM NATIVO (un conjunto, formulario nativo). Se ajustan los anuncios a AD 4, AD 5, AD 6 e IMG 1.
- Se prepara y luego se descarta una campaña de WhatsApp (15 €/día).
- Publicada la V.2 hacia las 19:00; pausada la V.1. Presupuesto final: 25 €/día (subida a 35 € quitada del borrador).

## ESTADO ACTUAL (24 nov 2026, 19:40)
- **V.1 | FORM | LANDING:** pausada.
- **V.2 | CAPTACIÓN | FORM NATIVO:** activa, 25 €/día, Barcelona +30 km, FB e IG, formulario «FxM | V.1 | CAPTACIÓN», anuncios AD 4, AD 5, AD 6 e IMG 1 en revisión. Sin cambios pendientes.
- **Casa Valldoreix:** en borrador (no publicar «IMG 2 | COMPRADORES»).
- **Decisiones tomadas:** empezar con 25 €/día y subir si funciona; solo formulario nativo; no tocar nada en unos 7 días.
- **Próximos pasos:** jueves 27 nov, mirar la entrega sin tocar nada. Lunes 1 dic [REVISAR: martes], con 5 o más leads buenos subir a 35–50 €/día; con menos de 3, revisar los anuncios.
- **Pendiente:** facturación (método de pago); quitar «Comentarios relevantes» en el AD 4 y el AD 5.
```

---

### clientes/par-servicios-inmobiliarios/ficha.md

```markdown
# PAR Servicios Inmobiliarios — ficha

## Negocio
- Inmobiliaria en Madrid (parinmobiliaria.com). Contacto: Santi (Santiago).
- Viene de una experiencia muy mala con otra agencia: hay que cualificar el 100 % de los leads.

## Oferta / servicios
- Busca sobre todo captar propietarios que quieren vender.
- Femax lleva: Meta Ads con formulario nativo, orgánico (guiones), agente IA y flujo en GHL. El WhatsApp de PAR se está conectando a GHL; Santiago ya fue aceptado como persona física en Meta.
- Hay una landing de propietarios en GHL con el píxel conectado.

## Público
- Propietarios de la Comunidad de Madrid, de 18 a 65 años (categoría Vivienda).

## Tono y creatividades
- Santi graba los vídeos y Mili los edita. Cierre con 2 s del logo de PAR solo, sin texto debajo.
- Título de los anuncios de captación: «Vende tu propiedad en Madrid».

## Plataformas y cuentas
- Meta: PAR Servicios Inmobiliarios SL — 1332723982387464
- Formulario nativo del V5 / AD 5: 2908047022910772
- GHL: los leads entran por LeadConnector. [REVISAR: confirmado para el V5]

## Presupuesto habitual
- Noviembre 2026: máximo 500 € en el mes. Diciembre: por cuadrar con Santi (si siguen siendo 500 €/mes, unos 16 €/día).

## KPIs
- Coste por lead (referencia del sector en Madrid según Meta: 11,47 €), volumen y, sobre todo, la calidad que valora Santi.
- CPM alto por la categoría Vivienda (~37 €, frente a una media de 11,80 €).
```

### clientes/par-servicios-inmobiliarios/campanas/2026-11-v1-captacion.md

```markdown
# V.1 | CAPTACIÓN (propietarios)

- **Plataforma:** Meta Ads — 1332723982387464
- **Objetivo:** leads de propietarios (categoría Vivienda).
- **Fechas:** desde el 17 nov 2026 aprox. [REVISAR]
- **Segmentación:** Comunidad de Madrid (región 1019), 18–65 años, personas que viven allí o han estado hace poco. Solo Facebook e Instagram desde el 21 nov.

## Conjuntos
### MADRID | FORMULARIO NATIVO V4 (ID 52646408446932)
- 20 €/día, 25 €/día desde el 21 nov. Pausado el 24 nov al publicar el V5.
- Anuncios: AD 5 (ganador), IMG 1, IMG 2.

### MADRID | LANDING | FORMULARIO (ID 52646391034332)
- 20 €/día, 15 €/día desde el 21 nov. Advantage+ Audience activado. Pausado por Mili el 24 nov.
- Anuncios: IMG 1, IMG 2, IMG 3 (el AD 5 de este conjunto, pausado).

### MADRID | FORMULARIO NATIVO V5
- Creado el 24 nov. 25 €/día; Mili lo pasa a 33 €/día. [REVISAR: confirmar que lo publicó]
- Comunidad de Madrid, 18–65, Advantage+ activado (para intentar bajar el CPM), solo FB e IG.
- Formulario 2908047022910772.
- Anuncios: AD 5 (vídeo), AD 7 (vídeo) e IMG 1, todos con el mismo texto y el título «Vende tu propiedad en Madrid». Mili habló de «el 4 y el 7»; en la cuenta no hay AD 4, son el AD 5 y el AD 7.

## Resultados
- 17–21 nov: formulario 66 €, 5 leads, 13,20 €/lead. Landing 56 €, 1 lead, ~56 €/lead: Audience Network se llevó 12,39 € y 163 de 181 clics sin leads; en FB e IG, 1 lead por ~43 €.
- Anuncios 17–21 nov: AD 5, 3 leads a 13,61 €; IMG 1 (formulario), 1 lead a 7,91 €; IMG 1 (landing), 29 € y 1 lead; IMG 3, 0,01 €.
- A 24 nov: AD 5 lleva 12 de los 14 leads, a 10,42 €. AD 7 sacó 1 lead a 21,21 € antes de pausarse. Landing, 58,71 €/lead.
- Gasto de la cuenta en noviembre a 24 nov: 289,07 €.

## Aprendizajes
- El formulario nativo convierte mucho mejor que la landing.
- Audience Network se llevaba los clics de la landing sin leads.
- Santi dice que los leads son de buena calidad: la prioridad pasa a ser más volumen sin pasarse del presupuesto.
- Mejor crear un conjunto nuevo que volver a publicar la campaña entera, para no reiniciar lo que funciona.

## Pendientes
- Confirmar en GHL que los leads del V5 entran por LeadConnector.
- Revisar el recorte de la IMG 1 en stories y reels.
- Pedir vídeos nuevos a Santi.
- Confirmar el píxel duplicado y la política de privacidad del formulario V2. [REVISAR: de dónde viene este pendiente]

## Estado (24 nov 2026)
- Activo solo el V5. V4 y landing pausados.
```

### clientes/par-servicios-inmobiliarios/historial.md

```markdown
# PAR Servicios Inmobiliarios — historial

## ~17 nov 2026
- Arranca la V.1 | CAPTACIÓN con dos conjuntos a 20 €/día (formulario V4 y landing).

## 21 nov 2026
- Revisión de 5 días: formulario 13,20 €/lead; landing ~56 €/lead (Audience Network). CPM ~37 €.
- Cambios en borrador, publicados por Mili: Audience Network fuera de los dos conjuntos (y Threads de la landing); formulario de 20 a 25 €/día y landing de 20 a 15 €/día (total 40 €/día).

## 24 nov 2026
- Santi: leads de buena calidad. La prioridad es el volumen.
- Mili pausa la landing.
- Idea de Mili: un conjunto nuevo con 2 vídeos y 1 imagen a ~25 €/día en toda la Comunidad de Madrid, con solo eso activo.
- Se crea el «MADRID | FORMULARIO NATIVO V5» (AD 5, AD 7, IMG 1) a 25 €/día. Se pausa el V4. El V5 queda activo, con los anuncios en revisión.
- Presupuesto de noviembre: máximo 500 €; quedan ~211 € para 6 días. Recomendado 33 €/día (cierre ~487 €). Mili lo cambia ella a 33 €.

## ESTADO ACTUAL (24 nov 2026)
- **Activo:** MADRID | FORMULARIO NATIVO V5, de 25 a 33 €/día (lo cambia Mili), AD 5, AD 7 e IMG 1 con el formulario 2908047022910772, en revisión.
- **Pausado:** V4 de formulario y landing.
- **Presupuesto de noviembre:** máximo 500 €; gastado 289,07 €; a 33 €/día cerraría en ~487 €.
- **Decisiones tomadas:** solo el V5; no tocar nada hasta la revisión.
- **Pendiente:** GHL/LeadConnector; recorte de la IMG 1.
- **Próximo paso:** 25 nov, confirmar que los anuncios están aprobados. Lunes 1 dic [REVISAR: martes], revisar coste por lead, volumen y la calidad según Santi, y fijar el presupuesto de diciembre.
```

---

### clientes/mar-chancosa/ficha.md

```markdown
# Mar Chancosa — ficha

## Negocio
- Cosmética y peluquería en Valencia. Tienda WooCommerce: marchancosa.com.
- Va junto con ICON (mismo contacto, Daniel, peluqueria@marchancosa.com). Mili los trata casi como un solo cliente.
- Tarifa conjunta ICON + Mar Chancosa: 1.800 €/mes sin IVA. El ROAS real incluye la inversión en plataformas más la tarifa.

## Oferta / productos (peluquería, Meta)
- **Microlíneas:** tratamiento de volumen para mujeres (no es peluca). CTA: estudio capilar gratuito en Valencia.
- **Extensiones de cabello natural:** CTA de diagnóstico gratuito.
- **Stop&Grow.** [REVISAR: qué es exactamente]
- **Balayage / mechas con Método BRA:** CTA de diagnóstico o estudio de color gratuito.
- Tienda online (Google Ads, pausada).

## Público
- Mujeres en Valencia (p. ej. Balayage: 18–50, Valencia +30 km). Stop&Grow pasó a solo mujeres el 24 nov.

## Tono y ganchos ganadores
- Microlíneas: antes/después «en solo una hora» (caso real) y «si eres mujer y quieres más volumen sin pelucas».
- Extensiones: «si eres de Valencia y piensas que las extensiones no quedan bien».
- Balayage: el titular «Estudio Gratuito» funciona mejor que «Diagnóstico Gratuito».
- Vídeos: animaciones con fondo de cristal y subtítulos en la misma tipografía que las fotos de la marca.
- Copy de estáticas: atacar dolores concretos, sin el gancho «de esto a esto».

## Plataformas y cuentas
- Meta (peluquería): 755939785026517 · Página 216665365025222 · Instagram 17841400044956661
- Google Merchant Center: «Mar Chancosa» 5822744780 (mismo login que ICON)
- Google Ads de la tienda: ID [REVISAR]

## Presupuesto habitual
- Meta (24 nov): Nexaleads Microlíneas 18 €/día, Extensiones 20 €/día, Stop&Grow 15 €/día, Balayage 10 €/día. Microlíneas 2026.11: [REVISAR]. Tope total: [REVISAR]

## KPIs
- Peluquería: coste por lead. Media de anunciantes parecidos según Meta: ~5,71 €.
- Tienda: ROAS ≥ 4 (objetivo a medio plazo).

## Reglas
- No cambiar destinos ni formularios sin hablarlo antes con Daniel (con un texto corto).

## Contradicción a revisar
- [REVISAR] En la memoria constaba «Meta Ads no se lo lleva Femax» para Mar Chancosa, pero en el chat del proyecto Femax gestiona la cuenta de Meta de la peluquería (755939785026517). Probablemente lo primero se refería a la tienda online.
```

### clientes/mar-chancosa/campanas/2026-10-google-ads-tienda.md

```markdown
# Google Ads — tienda online marchancosa.com

- **Plataforma:** Google Ads (cuenta: [REVISAR]); Merchant Center 5822744780
- **Objetivo:** ventas en la tienda (ROAS ≥ 4).
- **Resultados:** 14–30 sep 2026 (corregido a 21–30 sep en el informe): gasto 364,14 €, valor de conversión 532,46 €. ROAS total 1–15 oct (Google + Meta + orgánico, con la tarifa prorrateada al 50 % con ICON): 2,61. [REVISAR: cifras de informes, no de la cuenta]
- **Decisión (oct 2026):** pausada, porque a corto plazo no iba a llegar a ROAS 4. Es una marca menos conocida que ICON y Google tarda en aprender.
- **Opciones:** reactivarla a medio o largo plazo, o pasar su presupuesto al Black Friday de ICON. Sin decidir. [REVISAR]
- **Estado:** pausada desde oct 2026.
```

### clientes/mar-chancosa/campanas/2026-11-microlineas-2026-11.md

```markdown
# Microlíneas 2026.11 (formulario de Meta)

- **Plataforma:** Meta Ads — 755939785026517
- **Objetivo:** leads (estudio capilar gratuito en Valencia) con formulario de Meta.
- **Presupuesto:** [REVISAR]
- **Resultados (30 días a 24 nov):** 990 €, 216 leads, 4,59 €/lead. CTR > 4 %.
- **Creatividades:** antes/después «en solo una hora»; «si eres mujer y quieres más volumen sin pelucas». Nuevo vídeo AD2, editado por Mili, añadido el 24 nov.
- **Pendiente:** estáticas de Alex (previstas para el 24 nov). Decidir si se quita Audience Network.
- **Estado:** activa.
```

### clientes/mar-chancosa/campanas/2026-11-nexaleads-microlineas.md

```markdown
# Nexaleads Microlíneas (formulario de Meta)

- **Plataforma:** Meta Ads — 755939785026517
- **Objetivo:** leads de Microlíneas con formulario de Meta.
- **Presupuesto:** 18 €/día.
- **Resultados (30 días a 24 nov):** 520 €, 133 leads, 3,91 €/lead.
- **Nota:** [REVISAR: qué es «Nexaleads» y en qué se diferencia de Microlíneas 2026.11]
- **Estado:** activa.
```

### clientes/mar-chancosa/campanas/2026-11-extensiones.md

```markdown
# Extensiones (landing)

- **Plataforma:** Meta Ads — 755939785026517
- **Objetivo:** leads en landing (diagnóstico gratuito de extensiones naturales).
- **Presupuesto:** 20 €/día.
- **Resultados (30 días a 24 nov):** 459 €, 35 leads, 13,10 €/lead (una de las dos que «van regular»). CTR del anuncio 1,9 %. La landing convierte en torno al 6 % (483 visitas, 30 leads; cálculo de Claude).
- **Anuncios:**
  - «MC Extensiones 3.1.1»: 30 de los 35 leads a 11,81 €. Estaba pausado y se reactivó el 24 nov.
  - «MC Extensiones 3.1.2»: 5,88 €, 0 leads, CPM de 12 €.
  - Estáticas nuevas: ~21 €/lead con poquísimo gasto.
  - Nuevos vídeos AD4 y AD5, editados por Mili (24 nov).
- **Hook ganador:** «si eres de Valencia y piensas que las extensiones no quedan bien».
- **Pendiente:** respuesta de Daniel a una prueba con formulario de Meta. Estáticas de Alex para el viernes 27 nov.
- **Estado:** activa.
```

### clientes/mar-chancosa/campanas/2026-11-stop-and-grow.md

```markdown
# Stop&Grow (landing)

- **Plataforma:** Meta Ads — 755939785026517
- **Objetivo:** leads en landing.
- **Presupuesto:** 15 €/día.
- **Segmentación:** el 24 nov se dejó en borrador el cambio del público a mujeres. Después figura como «mujeres». [REVISAR: confirmar que se publicó]
- **Resultados (30 días a 24 nov):** 348 €, 35 leads, 9,95 €/lead. La landing convierte en torno al 5,7 %.
- **Anuncios:**
  - «AD 4.1.3»: 34 de los 35 leads a 9,83 €. Estaba pausado y se reactivó el 24 nov.
  - Dos anuncios que estaban activos: ~14 € entre los dos y 1 lead.
  - Nuevo vídeo AD8, editado por Mili (24 nov).
- **Estado:** activa.
```

### clientes/mar-chancosa/campanas/2026-11-balayage.md

```markdown
# [LEADS][Balayage][CBO]

- **Plataforma:** Meta Ads — 755939785026517
- **ID de campaña:** 120236515131310318
- **Objetivo:** leads en la landing https://marchancosa.com/mechas-balayage/ (diagnóstico o estudio de color gratuito). CTA «Solicitar cita» (REQUEST_TIME).
- **Presupuesto:** 10 €/día (CBO).
- **Conjunto:** «V.2 | [Women][18-50][Valencia][+30km]» (Balayage V.2).
- **Radio:** en el chat consta «El nombre dice +50 km, pero el radio real es de 10 km; lo he dejado en 10 km porque es lo que estaba funcionando». [REVISAR: a qué conjunto se refiere y cuál es el radio real]
- **Resultados (30 días a 24 nov):** 117 €, 12 leads, 9,75 €/lead.
- **Histórico de titulares:** «Estudio Gratuito», 67 leads a 9,38 €; «Diagnóstico Gratuito», ~22 €/lead.
- **Anuncios:**
  - AD 1 y AD 3, activos. AD 3 es el mejor anuncio. Se quitó un cambio de vídeo que tenía pendiente.
  - AD6_2026_MECHAS (ID 120250480440140318), en borrador, sin errores. Vídeo de mechas de Mili.
    - Texto: «¿Tus mechas se ven rayadas, amarillentas o con la raíz marcada a las pocas semanas? Con el Método BRA hacemos un balayage a tu medida: transiciones suaves, tonos que favorecen a tu piel y una raíz que crece de forma natural, cuidando tu pelo en todo el proceso. Las mechas que no parecen mechas. Reserva tu diagnóstico de color gratuito en nuestro salón de Valencia.»
    - Titular: «Estudio de color gratuito en Valencia» (antes «Método BRA»).
    - Descripción: «Balayage con Método BRA, sin raíz marcada».
    - UTM: utm_source=FacebookAds, utm_medium=PaidMedia, utm_campaign=[LEADS][Balayage][CBO], utm_term=[Women][18-50][Valencia][+30km], utm_content=AD6_2026 MECHAS.
- **Otros:** se eliminó un duplicado con errores.
- **Pendiente:** que Mili publique el AD6 [REVISAR: si está publicado]. Decidir si se quita Audience Network.
- **Estado:** activa.
```

### clientes/mar-chancosa/historial.md

```markdown
# Mar Chancosa — historial

## Sep 2026
- Google Ads de la tienda (21–30 sep): 364,14 € de gasto y 532,46 € de valor de conversión (datos del informe).

## Oct 2026
- 1–15 oct: ROAS total de 2,61 (con la tarifa prorrateada).
- Se pausa Google Ads de la tienda (no llegaba a ROAS 4 a corto plazo).

## 24 nov 2026 (martes)
- Revisión de la peluquería (30 días): Microlíneas 2026.11 a 4,59 €/lead, Nexaleads a 3,91 €, Extensiones a 13,10 €, Stop&Grow a 9,95 € y Balayage a 9,75 €. Las dos que van regular tenían pausados justo sus anuncios ganadores.
- Cambios: reactivados «MC Extensiones 3.1.1» y «AD 4.1.3»; Stop&Grow a mujeres (borrador); no se tocan destinos ni formularios.
- Mili edita 4 vídeos y los sube. Se crean AD2 (Microlíneas), AD4 y AD5 (Extensiones) y AD8 (Stop&Grow).
- Balayage: AD6_2026_MECHAS en borrador. Se eliminan el duplicado con errores y el cambio de vídeo pendiente del AD 3.

## 25 nov 2026
- AD6: titular cambiado a «Estudio de color gratuito en Valencia» y descripción «Balayage con Método BRA, sin raíz marcada». Guardado en borrador sin errores, listo para publicar.

## ESTADO ACTUAL (25 nov 2026)
- **Activo:** Microlíneas 2026.11 (formulario) con AD2; Nexaleads Microlíneas (18 €/día); Extensiones (20 €/día) con AD4 y AD5; Stop&Grow (15 €/día, mujeres) con AD8; Balayage V.2 (10 €/día) con AD 1 y AD 3.
- **En borrador:** AD6_2026_MECHAS en Balayage (único borrador de la cuenta).
- **Google Ads de la tienda:** pausado.
- **Pendiente:** publicar el AD6; decidir sobre Audience Network en Microlíneas y Balayage; estáticas de Alex (Microlíneas el 24, Extensiones el viernes 27); respuesta de Daniel a la prueba con formulario en Extensiones.
- **Próximo paso:** lunes 1 dic [REVISAR: martes], comparar los vídeos nuevos (AD2, AD4, AD5, AD6, AD8) con los anuncios actuales.
```

SIGUE


---

## Mili · 2026-11-25 11:27

SIGUE


---

## Claude · 2026-11-25 11:29

### clientes/icon/ficha.md

```markdown
# ICON Cuidado del Cabello — ficha

## Negocio
- Marca de cuidado del cabello con tienda WooCommerce: iconcuidadodelcabello.com.
- Contacto: Daniel (peluqueria@marchancosa.com), el mismo que Mar Chancosa.
- Tarifa conjunta con Mar Chancosa: 1.800 €/mes sin IVA. En los cálculos de ROAS total se reparte al 50 %.
- La web la va a rehacer un equipo externo (Mili recomendó Niche Beauty como referencia de estilo).

## Oferta / productos
- Champús y tratamientos capilares, entre ellos ICON Anti-Frizz (landing de venta directa).
- La gama Organic no entra en campañas ni feeds de Google: lleva CBD y Google no deja anunciarla.
- Black Friday 2026: campaña «Black Month» en Meta. El email de apoyo lo lleva un equipo externo (Abalola).

## Público
- Meta: mujeres. Hay un conjunto «V.6 AB MUJERES 37-58» con fatiga creativa (20 nov). [REVISAR: de qué campaña es]
- En Meta, Instagram vende más del doble que Facebook (ROAS 6,64 frente a 2,77; dato del 24 nov).

## Tono y creatividades
- Funciona mejor el formato «media mujer».
- El copy ataca problemas concretos del pelo (nada de «de esto a esto»). Gancho histórico: la humedad.
- Las variantes se hacen en 4:5 y 9:16. Las estáticas las hace Alex.
- Informes: tono positivo y simple (cuánto ha invertido y cuánto ha ganado). Formato PDF con la estructura del informe de ICON.

## Plataformas y cuentas
- Meta: 2264984720966986
- Google Ads: iconcuidadodelcabello — 901-588-9803 (2 campañas Performance Max)
- Merchant Center: «Icon cuidado del cabello» — 5818135048. No confundir con «Mar Chancosa», 5822744780.
- Email: Klaviyo (lleva el envío Abalola).

## Presupuesto habitual
- Meta, a 24 nov: Black Month de 38 a 45 €/día, India V.2 a 30 €/día (se pausa) y Retargeting a 5 €/día. Tope: no pasar del gasto total que había, unos 73 €/día.
- Google: [REVISAR]

## KPIs
- ROAS ≥ 4 (el cliente quiere 4,5), calculado con los pedidos reales de WooCommerce, porque el píxel no mide bien.
- Método del ROAS real de Google: pedidos de WooCommerce con origen «Fuente: Google» o «Google Shopping», con IVA, entre el gasto de Google Ads del mismo periodo. Sin orgánico, sin tarifa, sin pedidos cancelados ni en espera.
- Atribución en los informes: Femax se atribuye Google Ads, Meta Ads y SEO/orgánico. Desde nov 2026 también los pedidos de Klaviyo si la clienta llegó por Meta, Google Ads o SEO (último toque en 24 h; si no, primer toque).
- Códigos de origen en WooCommerce: G/GS Google, FB/IG Meta, OG orgánico, K Klaviyo, D directo.
```

### clientes/icon/campanas/2026-11-black-month.md

```markdown
# Black Month (V.2) — Black Friday ICON

- **Plataforma:** Meta Ads — 2264984720966986
- **Nombre exacto:** [REVISAR] (en los chats: «Black Month», «Black Month V.2»)
- **Objetivo:** ventas (compras).
- **Fechas:** noviembre 2026; en marcha a 20 nov. Fin: [REVISAR]
- **Presupuesto:**
  - 20 nov: 38 €/día.
  - 24 nov, decidido: 45 €/día.
  - Escalado previsto: miércoles 25 a 54 € y jueves 26 a 65 €. Antes se había propuesto 48 → 58 → 68 €; quedó 45 → 54 → 65 €.
- **Ubicaciones:** Audience Network se mantiene (1,4 % del gasto; 95 clics y 770 impresiones, un CTR del 12 %, probablemente clics accidentales). Se revisa después de Black Friday; si con más presupuesto pasa del 5 % del gasto, se quita.

## Creatividades
- «IMG 2 | BM | CHAMPÚS»: 13 compras, ROAS 5,36. Es el que vende, no se pausa.
- El IMG 3 de India también está en Black Month.
- Encargadas a Alex: 3 variantes de «CHAMPÚS» en 4:5 y 9:16, para el miércoles 25 a las 14:00.

## Resultados (20–23 nov, días completos)
- 139,45 € de gasto, 15 compras, 713,80 € en ventas, ROAS 5,12.
- 22 y 23 nov: 11 compras y 549 € con 71 € de gasto (ROAS 7,74).
- Fuente: píxel. [REVISAR: contrastar con los pedidos de Fb e Ig en WooCommerce]

## Estado
- Activa.
```

### clientes/icon/campanas/2026-11-india-v2.md

```markdown
# India V.2

- **Plataforma:** Meta Ads — 2264984720966986
- **Objetivo:** ventas.
- **Presupuesto:** 30 €/día.
- **Resultados (20–23 nov):** 117,32 €, 7 compras, 270,90 €, ROAS 2,31 (cuenta también las compras por visualización). ROAS de 2,63 el 22 nov y de 1,20 el 23.
- **Decisiones:**
  - 20 nov: pausarla.
  - 22 nov: se mantiene activa.
  - 24 nov: pausarla. Su presupuesto lo absorbe Black Month poco a poco.
- **Borrador relacionado:** «India consolidada» a 15 €/día. Recomendado descartarla y borrarla desde Ads Manager. [REVISAR: si se borró]
- **Estado:** pausa decidida el 24 nov. [REVISAR: confirmar que está aplicada]
```

### clientes/icon/campanas/2026-11-v1-retargeting-black-month-nov.md

```markdown
# V.1 | [FxM] RETARGETING | BLACK MONTH | NOV

- **Plataforma:** Meta Ads — 2264984720966986
- **Objetivo:** ventas (retargeting).
- **Fechas:** publicada el 22 nov 2026 a las 9:23.
- **Presupuesto:** 5 €/día. Se deja así hasta Black Friday, porque el público es pequeño.
- **Conjunto:** «CARRITO 60D + SEGUIDORES 180D | EXCL. COMPRAS 60D».
- **Anuncios:** «Así de fácil», «Favoritos» y «Champús».
- **Resultados (22–23 nov):** 10,44 €, 0 compras.
- **Estado:** activa.
```

### clientes/icon/campanas/2026-11-google-pmax-gmcnuevo-campana-ganadora.md

```markdown
# Google Ads — «campaña ganadora» sobre PMAX.GMCNUEVO

- **Plataforma:** Google Ads — 901-588-9803
- **Campaña base:** PMAX.GMCNUEVO (ID 24003369565)
- **Objetivo:** ventas con ROAS ≥ 4, construida con los datos históricos de Google Ads.
- **Estado:** en pausa hasta que Mili la revise y la lance ella.
- **Nota (21 nov):** decidir esa semana si se lanza para Black Friday, porque PMax necesita días de aprendizaje. [REVISAR: si se lanzó]

## Histórico de ROAS real de Google (pedidos de WooCommerce)
- 1–30 oct 2026: 6,94 (7.953,28 € en 130 pedidos / 1.146,43 € de gasto). Google Ads marcaba 3,76.
- 1–9 nov 2026: 5,74 (2.082,53 € en 36 pedidos / 362,70 €). Google Ads marcaba 3,89.
- Google Ads registra más o menos la mitad de los pedidos reales.
- ROAS total 1–15 oct (Google + Meta + orgánico, con la tarifa prorrateada al 50 %): ICON 4,34; Mar Chancosa 2,61; las dos juntas 3,65. Meta ICON en ese periodo: 2,95.
- Sep 2026 (informe): Google Ads 668,31 € de gasto, 58 conversiones, 3.949,26 € de valor; Meta 562 € de gasto.
- Oct 2025 frente a oct 2026: +33 % de facturación en ICON. La búsqueda orgánica bajó mientras subía Google Ads, posible canibalización de búsquedas de marca.
```

### clientes/icon/historial.md

```markdown
# ICON — historial

## Sep–oct 2026
- Informe de septiembre (HTML/PDF) y de octubre, con el ROAS real calculado con los pedidos de WooCommerce y la tarifa incluida.
- Octubre: el panel de Google Ads registraba muy por debajo de las ventas reales.

## Nov 2026 (informes)
- Se corrige la atribución de Klaviyo: había 32 pedidos no pagados o abandonados (~2.229 €) en los datos de Klaviyo. Se rehace con la exportación verificada de WooCommerce.
- En los informes no se compara con «lo que marca el panel de Google o Meta»: solo ventas reales. Si se suman dos tiendas, decirlo.

## 20 nov 2026
- Decisiones: Black Month a 38 €/día; pausar India V.2; retargeting en borrador a 5 € e India consolidada a 15 €.
- Fatiga creativa en «V.6 AB MUJERES 37-58».

## 22 nov 2026
- Publicado el retargeting (5 €/día, 9:23). India V.2 se queda activa (cambia lo decidido el 20). India consolidada sigue en borrador.
- Total activo: ~73 €/día.

## 24 nov 2026
- Datos del 20 al 23 nov: Black Month ROAS 5,12; India ROAS 2,31.
- Decisión: pausar India; Black Month a 45 € (luego 54 y 65 €); Audience Network se mantiene; 3 variantes de CHAMPÚS encargadas a Alex.

## ESTADO ACTUAL (24 nov 2026)
- **Activo:** Black Month a 45 €/día (desde 38) y Retargeting a 5 €/día. India V.2 pasa a pausa.
- **En borrador:** India consolidada (por borrar).
- **Google:** campaña ganadora sobre PMAX.GMCNUEVO en pausa. [REVISAR]
- **Encargado a Alex:** 3 variantes de «CHAMPÚS» en 4:5 y 9:16, para el miércoles 25 a las 14:00.
- **Próximo paso:** miércoles 25, Black Month a 54 € y subir las variantes. Jueves 26, a 65 €, y mantenerlo hasta el lunes 30. Después de Black Friday, revisar el peso de Audience Network.
```

---

### clientes/tourbillon-bricks/ficha.md

```markdown
# Tourbillon Bricks — ficha

## Negocio
- Relojes de lujo construidos en bricks (no son réplicas). Tienda Shopify: tourbillonbricks.com.
- Caso de éxito que cita Mili: de 591 €/mes a 38.000 €. También citó «de 650 a más de 100.000 € en 9 meses». [REVISAR: qué métrica es]

## Oferta (Black Friday / Cyber Week 2026)
- Fases del 19 oct al 9 dic. Black Friday el 27 nov; Cyber Monday el 30 nov.
- Ofertas: 20 % de descuento y 3x2 (compras 2 y te llevas la tercera gratis; automático en el carrito). El 3x2 se usa desde hace tiempo.

## Público
- Por país: USA y UK (Google BF: los mismos países que Meta). Bases de fans de Lego y bricks para el email.

## Tono y creatividades
- Textos en inglés; fotos reales. Referencia principal de estilo: minibricks.
- Editor de vídeo: Javi. Mili le pasa qué vídeos funcionan, por el título del archivo en Drive.
- Fotos de producto: https://drive.google.com/drive/folders/1zSXNqusBXgvigbUhHRl3cZGXikCdjNuR

## Plataformas y cuentas
- Meta: 2237541826642480
- Google Ads: 243-011-6841
- Merchant Center: 5910804902 (Tourbillon Bricks SL)
- Shopify: app Google & YouTube conectada a la 243-011-6841.
- Email: maquetado en GHL.

## Presupuesto habitual
- Meta, estructura BF (19 nov): prospección USA 230 €/día y UK 190 €/día; testing 40 €; retargeting de 40 a 70 €.
- Google: PMax BF a 100 €/día (en pausa).

## KPIs
- ROAS mínimo de 2,26, mirado por anuncio (antes se usaba 2,5–3).
- Un anuncio que gasta más de 90 € sin ventas se pausa.

## Reglas
- No se cambian en la web ni los nombres ni las fotos de los productos por el tema de «Counterfeit».
- Las tareas se reparten en reunión con el cliente.
- Documento de estructura de campañas: https://claude.ai/artifact/PH9rURNdpeYg6NXVfb27AB
```

### clientes/tourbillon-bricks/campanas/2026-11-c1-bfcm26-prospeccion.md

```markdown
# C1 · BFCM26 PROSPECCIÓN

- **Plataforma:** Meta Ads — 2237541826642480
- **Objetivo:** compras. Prospección en USA y UK.
- **Presupuesto:** USA 230 €/día y UK 190 €/día según la estructura del 19 nov. [REVISAR: si se mantiene]
- **Anuncios mencionados:** LOWEST PRICE B, 3x2 THE PIECES, BF_VENTA_4, BF_VENTA_5. Etiquetas de oferta [20] y [3x2].
- **Resultados:**
  - 7 días a ~21 nov: 610,04 €, 9 compras, 67,78 €/compra, ROAS 1,45.
  - 20–23 nov: ROAS 1,79. El 23 nov, ROAS 0,38, sobre todo por LOWEST PRICE B.
- **Decisiones:**
  - 23 nov: cambiar BF_VENTA_5 por «BF27 - 5 (fix)» cuando se suba el vídeo.
  - 24 nov: no tocar nada. BF27 - 5 (fix) queda listo, sin subir.
- **Próximo paso (25 nov):** si sigue por debajo de 2,26, mover presupuesto a 3x2 THE PIECES y BF_VENTA_4; decidir sobre LOWEST PRICE B, si entra BF27 - 5 y si «[3x2] BF27 - 4» pasa a C1 antes del 27.
- **Estado:** activa, por debajo del ROAS mínimo.
```

### clientes/tourbillon-bricks/campanas/2026-11-c2-bfcm26-testing.md

```markdown
# C2 · BFCM26 TESTING (UK)

- **Plataforma:** Meta Ads — 2237541826642480
- **Objetivo:** compras; testing de creatividades en UK.
- **Presupuesto:** 40 €/día (estructura del 19 nov).
- **Resultados:**
  - 7 días a ~21 nov: 47,84 €, 0 compras.
  - 20–23 nov: ROAS 2,55.
- **Anuncio nuevo:** «[3x2] BF27 - 4_v1», con el copy «Buy 2, get 1 free», el vídeo corregido «BF27 - 4 (fix)» y destino a la página principal. El 23 nov estaba listo para publicar. [REVISAR: si se publicó]
- **Regla:** si lleva un ROAS de 2,26 o más el 25 nov, duplicarlo en C1 (USA y UK) antes del 27.
- **Estado:** activa.
```

### clientes/tourbillon-bricks/campanas/2026-11-c3-bfcm26-retargeting.md

```markdown
# C3 · BFCM26 RETARGETING (USA+UK)

- **Plataforma:** Meta Ads — 2237541826642480
- **Objetivo:** compras (retargeting).
- **Presupuesto:** de 40 a 70 €/día (estructura del 19 nov). Prioridad del 21 nov: subirlo hacia los 70 €/día para la semana de BF. [REVISAR: si se subió]
- **Resultados:**
  - 7 días a ~21 nov: 50,61 €, 2 compras, 25,31 €/compra, ROAS 3,77.
  - 20–23 nov: ROAS 3,03.
- **Creatividades:** tener listos [20] y [3x2] para el 27 y el 30 de noviembre.
- **Estado:** activa.
```

### clientes/tourbillon-bricks/campanas/2026-11-google-bfcm26-pmax-usa-uk.md

```markdown
# BFCM26 | PMax | USA+UK (Google)

- **Plataforma:** Google Ads — 243-011-6841 · Merchant Center 5910804902
- **ID de campaña:** 24530566064
- **Objetivo:** compras en Black Friday/Cyber Monday en USA y UK.
- **Presupuesto:** 100 €/día.
- **Recursos:** 13 imágenes, 6 vídeos y 8 temas de búsqueda.
- **Estado:** EN PAUSA y sin gasto.

## Condiciones para reactivarla
1. Productos de USA y UK aprobados en Merchant Center (de «limitados» a aprobados).
2. Conversión de compra activa («Google Shopping App Purchase»; basta con una venta en la web).
3. Anuncios revisados (no se revisan hasta reactivar la campaña).

## Situación de Merchant Center
- Antes del 21 nov: bloqueo por «Counterfeit». Plan: contactar con soporte y luego apelar una sola vez, con un documento previo para el cliente. Se vio también la cuenta de Google Ads suspendida. [REVISAR]
- 21 nov (corrección): el bloqueo por «Counterfeit» ya no aparece. Merchant Center y YouTube vinculados a Google Ads; medición de conversiones y conversiones mejoradas en verde. Corregido el envío a USA y UK (la moneda no coincidía con el feed). Promo 3x2 creada para USA (aprobada por política, pendiente de revisión de producto) y para UK (guardada).
- 23–25 nov: 792 productos, 0 aprobados, 792 «limitados». Los de USD y GBP siguen en «Pending initial review» para USA, UK y Emiratos. La cuenta no tiene problemas. Los clics gratuitos subieron de 26 a 126 (se muestran en otros países). El aviso de «Mismatched currency» de otros feeds no bloquea nada.
- 25 nov: la conversión «Compra» sigue en «Requiere atención» con 0 compras, aunque Meta ha atribuido ventas desde el 20. Posible fallo en la medición de compras de Google.

## Próximo paso
- 25 nov: contactar con el soporte de Merchant Center para que agilicen la revisión de los productos USD y GBP por Black Friday, y comentarles lo de las conversiones. Revisar en Shopify la app Google & YouTube → Conversiones, o hacer un pedido de prueba.
- Jueves 26: volver a comprobar los productos.
```

### clientes/tourbillon-bricks/historial.md

```markdown
# Tourbillon Bricks — historial

## 19 oct 2026
- Empiezan las fases de BF/Cyber Week (hasta el 9 dic).

## 19 nov 2026
- Estructura de Meta para BF: prospección USA 230 € y UK 190 €; testing 40 €; retargeting de 40 a 70 €.

## ~21 nov 2026
- 7 días: C1 ROAS 1,45; C2 0 compras; C3 ROAS 3,77. Total ~708 € y 11 compras.
- Google: creada BFCM26 | PMax | USA+UK, en pausa. Bloqueo por «Counterfeit» resuelto según la corrección del brief. Envío USA/UK corregido; promo 3x2.

## 22–23 nov 2026
- Merchant Center: productos USD/GBP en «Pending initial review».
- Meta: «[3x2] BF27 - 4_v1» en borrador en C2 (UK) con el vídeo corregido. Decidido cambiar BF_VENTA_5 por BF27 - 5 (fix) en C1.

## 24 nov 2026
- 20–23 nov: C1 ROAS 1,79 (0,38 el 23 nov); C2 2,55; C3 3,03.
- Mili: hoy no se cambia nada.

## 25 nov 2026
- Google sigue sin poder publicarse: productos sin aprobar y 0 compras registradas en la conversión de compra.

## ESTADO ACTUAL (25 nov 2026)
- **Google:** PMax `BFCM26 | PMax | USA+UK` en pausa y sin gasto. Productos USD/GBP en «Pending initial review» (0 aprobados). Conversión de compra a 0, posiblemente porque no se registran las compras.
- **Meta:** sin cambios desde el 24. C1, C2 y C3 activas.
- **Decisión:** no reactivar la PMax hasta que los productos estén aprobados.
- **Próximo paso:** hoy, contactar con soporte de Merchant Center, revisar la medición de compras en la app Google & YouTube de Shopify y hacer la revisión de C1 que quedó pendiente para el 25. Jueves 26, volver a comprobar los productos.
```

---

### clientes/owa-academy/ficha.md

```markdown
# OWA Academy (OWA Formación) — ficha

## Negocio
- Formación para profesionales de la salud. Submarca OWA Formación (azul marino + coral), distinta de OWA Entrenamiento.

## Oferta
- Lead magnet: PDF «Suelo Pélvico y Entrenamiento de Fuerza en el Embarazo», de Lidia Romero-Gallardo.
- Certificación básica (leads de Meta «Certificación básica»).
- Webinar (campaña de abril).

## Público
- Profesionales de la salud. Al presentarlo como caso de éxito, hablar de profesionales de la salud, no solo de suelo pélvico.

## Plataformas y cuentas
- Meta: 10201914070951066
- Landing y página de gracias en ActiveCampaign (owacademy.ac-page.com), con píxel y evento Lead en la gracias. El formulario pregunta «¿Has realizado alguna formación en OWA?» (Sí/No).
- Envío del PDF por Apps Script desde info@ de OWA (cuenta de OWA). El Sheet de leads está en la cuenta de la agencia.
- ActiveCampaign:
  - Listas «Guía Suelo Pélvico», «Certificación básica» y «Profesionales OWA».
  - Etiquetas «Lead Magnet», «Certificación básica» y «Profesionales de la salud».
- GHL: automatización de WhatsApp en curso (plantilla, recordatorio a las 24 h y segundo recordatorio; faltan las plantillas aprobadas y el webhook).

## Presupuesto habitual
- [REVISAR] (~68 € en 7 días a 21 nov). Límite acordado con OWA: [REVISAR]

## KPIs
- CPL por debajo de 3 € es muy bueno; de 4 a 6 € es naranja; más es alarmante.
- Que los leads entren bien en ActiveCampaign.
```

### clientes/owa-academy/campanas/2026-10-v1-octubre-lead-magnet.md

```markdown
# V.1 [OCTUBRE] LEAD MAGNET

- **Plataforma:** Meta Ads — 10201914070951066
- **Objetivo:** leads para el lead magnet (landing en ActiveCampaign + gracias con píxel).
- **Fechas:** desde octubre 2026. [REVISAR: fecha exacta]
- **Presupuesto:** [REVISAR]
- **Segmentación y creatividades:** [REVISAR]
- **Resultados (7 días a 21 nov):** 68,04 €, 24 leads, CPL 2,84 € (en verde).
- **Próximos pasos (21 nov):** mantener el CPL por debajo de 3 €; valorar subir el presupuesto poco a poco sin pasar el límite acordado; comprobar que los leads nuevos entran en «Profesionales OWA».
- **Estado:** activa.
```

### clientes/owa-academy/campanas/2026-04-webinar.md

```markdown
# Campaña de webinar (abril)

- **Plataforma:** Meta Ads — 10201914070951066
- **Nombre exacto, objetivo y resultados:** [REVISAR]
- **Estado (21 nov 2026):** activa pero sin gasto. [REVISAR: si conviene apagarla]
```

### clientes/owa-academy/historial.md

```markdown
# OWA Academy — historial

## 23 oct 2026
- Importación manual en CSV a ActiveCampaign: listas «Guía Suelo Pélvico» (lead magnet) y «Certificación básica» (leads de Meta, por lotes).

## 26 oct 2026
- Plan de automatización de WhatsApp en GHL (plantilla y recordatorios a las 24 h). Pendientes: plantillas, WhatsApp conectado y webhook.

## 13 nov 2026
- Mili quiere que todos los leads nuevos del lead magnet entren además en la lista «Profesionales OWA».

## 21 nov 2026
- 7 días: V.1 [OCTUBRE] LEAD MAGNET con 68,04 €, 24 leads y CPL de 2,84 €. Webinar de abril activo sin gasto.

## ESTADO ACTUAL (21 nov 2026)
- **Activo:** V.1 [OCTUBRE] LEAD MAGNET (CPL 2,84 €). Webinar de abril activo sin gasto.
- **Prioridades:** 1) comprobar que los leads nuevos entran en «Profesionales OWA»; 2) terminar el flujo de WhatsApp en GHL (plantillas, webhook, prueba de los recordatorios de 24 h); 3) mantener el CPL por debajo de 3 € y valorar subir el presupuesto poco a poco.
- No ha habido revisión con datos de la cuenta desde el 21 nov.
```

---

### clientes/kruceros-com/ficha.md

```markdown
# Kruceros.com — ficha

## Negocio
- Agencia de cruceros (kruceros.com), con Kruceros Valencia.
- Contactos: Carlos (por WhatsApp) y Adrián Parra (dueño; admin completo en GHL).
- Asesores en GHL (7): Gema Álvarez, Cristina Begué, Laura Solís, Marian Valtuille, Lidia Giner, Henry Medina, Yeray Montesdeoca.

## Oferta
- Cruceros, con campañas distintas para cada crucero en Meta y Google.
- Expansión a Miami (MSC): formar a una primera asesora y lanzar campañas de captación de asesores allí. Femax prepara el estudio.

## Público
- [REVISAR] (Valencia en Meta; ChatGPT Ads con landing propia)

## Tono y estilo
- Escribir siempre «kruceros.com» y «krucero/krucerista/kruceristas» con K, en primera persona del plural, tuteando.
- Todas las creatividades nuevas llevan el logo de Valencia.

## Plataformas y cuentas
- Meta: 300315382488327 (también existe «Kruceros y viajes», 1660894892046682)
- ChatGPT Ads: adacct_6aa2cc96f60c81938a5136520e4d89f7
- Google Ads: PMax y BRANDING (ID de cuenta: [REVISAR])
- GHL: subcuenta de Kruceros (propiedad de Femax). WhatsApp y Meta Ads conectados. Reparto aleatorio de leads entre asesores, SLA de 16 h laborables (8:30–20:30, sin noches, fines de semana ni festivos). Si el asesor no responde, se reasigna a otro.
- Clientify se mantiene hasta marzo (~50.000 contactos por migrar).
- Landing de ChatGPT Ads: tucrucero.kruceros.com.
- Agente que recoge contactos en Instagram y Facebook.

## Presupuesto habitual
- Meta: unos 1.276 € en 7 días (a 21 nov), en 11 campañas.
- ChatGPT Ads: test de 600 €.
- Google: [REVISAR]

## KPIs y reglas
- Ningún lead de Meta debe pasar de 2 €.
- Octubre 2026 fue el mejor mes histórico y hay que mantenerlo. Comparar siempre con la semana anterior.
- Las campañas se van pasando a formularios de GHL.
- No se tocan los workflows activos de GHL; los cambios se prueban en borradores nuevos.
- Informes cada 15 días con el funnel completo por asesor y por origen.
```

### clientes/kruceros-com/campanas/2026-11-meta-campanas-activas.md

```markdown
# Meta Ads — campañas activas (Kruceros Valencia)

Un archivo para las 11 campañas: de cada una solo hay datos de los 7 días a 21 nov 2026. Objetivo, presupuesto, segmentación y creatividades de cada una: [REVISAR]

- **Plataforma:** Meta Ads — 300315382488327
- **Objetivo:** leads (formularios; se van pasando a formularios de GHL).
- **Total 7 días (a 21 nov):** ~1.276 € de gasto, ~2.066 leads, CPL medio de ~0,62 €. Todas por debajo de 2 €.

| Campaña | Gasto | Leads | CPL | Nota |
|---|---|---|---|---|
| BLACK-FRIDAY FORM CLIENTIFY | 101 € | 421 | 0,24 € | |
| VLC_12-28_FA | 219 € | 449 | 0,49 € | |
| FN FORM | 79 € | 234 | 0,34 € | |
| VLC_30_JC | 133 € | 202 | 0,66 € | |
| V.2 FIN DE AÑO 28-12 | 18 € | 29 | 0,62 € | |
| IG FORM | 103 € | 119 | 0,87 € | |
| CAR (11-26) | 171 € | 182 | 0,94 € | |
| ME FORM CLIENTIFY | 106 € | 109 | 0,97 € | |
| UH FORM | 102 € | 105 | 0,97 € | |
| VLC_SEN | 137 € | 123 | 1,11 € | vigilar (se acerca a 1 €+) |
| CAR_AINF (11-23) | 108 € | 93 | 1,16 € | vigilar |

- **Próximo paso (21 nov):** vigilar VLC_SEN y CAR_AINF cada día frente a la semana anterior y actuar antes de que se acerquen a 2 €.
- **Estado:** activas.
```

### clientes/kruceros-com/campanas/2026-11-chatgpt-ads-test.md

```markdown
# ChatGPT Ads — test

- **Plataforma:** ChatGPT Ads (OpenAI) — adacct_6aa2cc96f60c81938a5136520e4d89f7
- **Objetivo:** leads. Landing tucrucero.kruceros.com con formulario y oportunidad en GHL para medir.
- **Fechas:** del 11 nov al 9 dic 2026.
- **Presupuesto:** 600 € en total.
- **Segmentación y creatividades:** [REVISAR]
- **Resultados:** [REVISAR] (a 21 nov, a mitad de camino; sin datos en el chat).
- **Próximo paso:** medir en GHL las oportunidades que llegan desde tucrucero.kruceros.com y su calidad frente a lo gastado.
- **Estado:** activa.
```

### clientes/kruceros-com/campanas/google-ads-pmax-branding.md

```markdown
# Google Ads — PMax y BRANDING

- **Plataforma:** Google Ads (cuenta: [REVISAR])
- **Campañas:** PMax y BRANDING (y campañas por crucero, según el caso de éxito).
- **Fechas, presupuesto, segmentación y resultados:** [REVISAR] (no hay datos en los chats del proyecto).
- **Estado:** [REVISAR]
```

### clientes/kruceros-com/historial.md

```markdown
# Kruceros.com — historial

## Sep 2026
- WhatsApp contratado y Meta Ads conectado en la subcuenta GHL.

## Oct 2026
- Definido el SLA de asesores (16 h laborables, reasignación aleatoria).
- Mejor mes histórico.
- Campañas de Meta de Valencia pasando a formularios de GHL; regla del logo de Valencia.
- Propuesta de test de ChatGPT Ads para Adri.
- Plan de expansión a Miami (MSC).

## 11 nov 2026
- Arranca el test de ChatGPT Ads (600 €, hasta el 9 dic).

## 21 nov 2026
- 7 días: 11 campañas, ~1.276 €, ~2.066 leads, CPL de ~0,62 €.

## ESTADO ACTUAL (21 nov 2026)
- **Activo:** 11 campañas de Meta (todas por debajo de 2 €/lead) y el test de ChatGPT Ads.
- **Prioridades:** 1) vigilar VLC_SEN (1,11 €) y CAR_AINF (1,16 €); 2) medir ChatGPT Ads en GHL; 3) que el consumo de créditos de la subcuenta GHL lo pague Kruceros y no la agencia (hablarlo con Adrián).
- **Otros pendientes:** estudio de Miami; informes cada 15 días.
- No ha habido revisión con datos de la cuenta desde el 21 nov.
```

---

Con esto ya tienes los 62 archivos de la lista.

- **Qué revisar primero:** busca «[REVISAR]» en el repo. Lo más importante:
  - Los presupuestos que publicaste tú y que no he podido confirmar: Karama V.3, PAR a 33 €, IRB 35/15 en la V.1.
  - Si aplicaste los cambios propuestos en DTributos.
  - La contradicción de Meta en Mar Chancosa.
  - Las fechas con el día de la semana mal: el 24 nov y el 1 dic de 2026 son martes, no lunes.
- **Sin revisar desde el 21 nov:** Kruceros, OWA y DTributos solo tienen el brief inicial, sin datos de la cuenta posteriores. Antes de dar sus fichas por buenas, conviene hacerles una revisión.
