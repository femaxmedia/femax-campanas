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
