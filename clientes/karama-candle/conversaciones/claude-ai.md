> Conversación completa exportada del proyecto «Campañas publicitarias» de claude.ai el 25 nov 2026. Solo lectura: lo nuevo va en ficha.md, historial.md y campanas/.

# Karama Candle

- Chat de claude.ai: https://claude.ai/chat/58330ec5-46f1-4fbe-99b0-97bbfc41fbba
- Creado: 2026-11-21T07:42:55.252198Z · Actualizado: 2026-11-21T20:35:03.997591Z
- Mensajes: 4

---

## Mili · 2026-11-21 07:42

Necesito que mires el administrador de Karama Candle, veas todas las campañas que hemos hecho para talleres, ¿vale? De velas y de recipientes. Hay dos activas y necesito que me las optimices, y si hay que publicar una tercera, una tercera. En verdad, nosotros tenemos como mucho 20 euros al día de presupuesto.


---

## Claude · 2026-11-21 07:45

Voy a revisar la cuenta de Karama Candle en Meta Ads, analizar las campañas de talleres (velas y recipientes) y proponerte las optimizaciones dentro de los 20 €/día.

_Herramientas: memory__memory_read, ToolSearch, Meta_Ads__ads_get_ad_accounts, Meta_Ads__ads_get_ad_entities, Meta_Ads__ads_get_ad_entities, Meta_Ads__ads_get_ad_entities, Meta_Ads__ads_get_creatives, ToolSearch, Meta_Ads__ads_get_dataset_stats, Meta_Ads__ads_get_dataset_stats, Meta_Ads__ads_get_ad_entities, ToolSearch, Meta_Ads__ads_update_entity, Meta_Ads__ads_update_entity, Meta_Ads__ads_update_entity, Meta_Ads__ads_update_entity, ToolSearch, Meta_Ads__offer_report_

He revisado la cuenta y he dejado preparados los cambios en las dos campañas activas. **Todavía no están publicados**: la conexión los guarda como borrador en el administrador de Meta. Tienes que entrar y darle a **Publicar**. Hasta entonces sigues gastando 25 €/día.

## Cómo están las campañas de talleres

| Campaña | Desde | Gasto | Visitas a la landing | Leads | Coste por lead |
|---|---|---|---|---|---|
| V.1 Form Talleres (formulario de Meta) | sep | 291,69 € | — | 251 | 1,16 € |
| V.2 Landing Velas (pausada) | 30 sep | 436,33 € | 1.706 | 68 | 6,42 € |
| **V.3 Landing Velas (activa)** | 20 nov | 9,84 € | 21 | 0 | — |
| **V.2 Landing Recipientes (activa)** | 18 nov | 27,57 € | 53 | 0 | — |

Lo que veo:

1. **El presupuesto superaba tu límite.** Velas estaba a 15 €/día y Recipientes a 10 €/día, 25 € en total.
2. **El público de Bilbao se estaba agotando.** Las campañas apuntaban solo a 5 km alrededor del Guggenheim, a mujeres. La V.2 de Velas ya había llegado a 37.000 personas, que han visto el anuncio unas 3,6 veces cada una. En los últimos 14 días el lead le salía a unos 12 €, cuando antes estaba en 5 €.
3. **El anuncio que mejor funcionaba no está en la campaña nueva.** "IMG 2" de la V.2 de Velas trajo 50 leads a 5,18 €. En la V.3 hay un "IMG 2" con la misma imagen, pero es una publicación nueva y no tiene los likes ni los comentarios de la antigua. Además, "IMG 1" se está llevando el 70 % del gasto.
4. **Recipientes lleva 53 visitas y 0 leads atribuidos.** El píxel sí registra leads en formrecipientes.karamacandle.com: 15 el 17 de noviembre (antes de lanzar, así que probablemente pruebas) y 5 el 20. O la atribución va con retraso o esos leads llegaron por orgánico. Mira en el Sheet o en GHL si entraron leads reales el 20.

Las dos campañas activas son muy nuevas (1 y 3 días) y todavía están aprendiendo. Por eso no he pausado ningún anuncio, aún es pronto para juzgarlos.

## Lo que he dejado listo para publicar

- **Velas:** baja de 15 a 12 €/día y el radio pasa de 5 a 20 km.
- **Recipientes:** baja de 10 a 8 €/día y el radio pasa de 5 a 20 km.
- **Total: 20 €/día.**

Con 20 km entra todo el Gran Bilbao: Getxo, Barakaldo, Basauri y alrededores. He mantenido el resto de la segmentación: solo mujeres de 18 a 65 años y la audiencia Advantage+ desactivada, como la teníais.

## Te recomiendo no lanzar una tercera campaña

Con 20 €/día, una tercera dejaría las tres a unos 6-7 €/día. Ninguna tendría datos suficientes para que Meta aprenda. Mejor estas dos:

- **Añadir a la V.3 de Velas la publicación antigua de "IMG 2"**, con sus likes y comentarios. No puedo crear anuncios desde aquí: en el administrador, crea un anuncio con "Usar publicación existente" y elige la de "Crea tus propias velas en Bilbao" del 19 de noviembre.
- **Decidir entre landing y formulario de Meta.** Con el formulario de Meta, los leads os salían a ~1 €, frente a 5-6 € con la landing. Si la calidad de aquellos leads no era tan mala, una versión de Velas con formulario dentro de la misma campaña puede ayudar a llenar las fechas de Navidad. Esto lo decides tú, porque sabes qué leads acababan comprando.

Dejaría pasar 4 o 5 días con los cambios publicados antes de pausar ningún anuncio.


---

## Mili · 2026-11-21 20:34

KARAMA CANDLE

📌 BRIEF ACTUALIZADO (21 nov 2026) — contexto de este cliente con todo lo revisado hoy y los últimos días. Tómalo como base para todo lo que hablemos en este chat a partir de ahora. Responde solo con 'Entendido' y las 3 prioridades inmediatas.

**Cliente:** Karama Candle (Bilbao), talleres de velas y de recipientes. Contactos: Rosario y Asier.
**Qué lleva Femax:** Meta Ads, landings y web de experiencias, el sistema de reservas con Stripe y Vercel, email en GHL, orgánico de Instagram (calendario mensual ORG_MM_AAAA) y prospección B2B (empresas y ayuntamientos).

**Cuentas e infraestructura:**
- Meta: 26051144467865567
- Píxel [FxM] TALLERES 1640004717538673
- Backend Vercel "karama-stripe-backend" (repo alejandrofemaxmedia-svg/karama-stripe-backend). Las plazas se configuran en api/_plazas.js.

**Reglas:**
- Presupuesto Meta total de 15 a 20 €/día.
- Lead ideal por debajo de 5 €; de 6 a 8 € es naranja.
- Objetivo: que se agoten los talleres.

**Decisión del 21 nov:**
- Meta se centra solo en los talleres de velas. Recipientes queda pausado.
- Recipientes gastó 21,70 € con 46 visitas y 0 leads reales. Se arreglaron un 404 en /recipientes-registro y el disparo del Lead, que ahora se lanza en la landing al enviar.
- Anuncio nuevo: reel de la creadora Maider subido directamente.

**Estado Meta, últimos 7 días:** "V.3 FORM LANDING VELAS" con 5,90 € gastados y aún sin leads (recién arrancada).

**Plazas y fechas:**
- Velas: 9, 15 y 24 de enero, 18 plazas cada uno.
- Recipientes: 17 y 23 de enero, 15 plazas cada uno.
- Cambios recientes: 7 nov con 2 plazas liberadas; 21 nov con 3 plazas de "Colaboración"; 26 dic con 1 plaza reservada aparte para Jennifer; recipientes del 28 nov limitado a 15.
- Los códigos de regalo KARAMA-XXXXXX (cupón Stripe 3WAdb77B, compartido entre velas y recipientes) solo valen para 1 plaza.

**Automatizaciones activas:**
- Email de reseña cada día a las 17:00 (cron de Vercel /api/resenas) a quienes asistieron en los últimos 3 días, con enlace a la reseña de Google.
- Newsletter a la base de datos: email 1 enviado y email 2 programado.
- Campaña a ayuntamientos de Bizkaia: 112 contactos, email de Rosario con el dossier adjunto, envío el martes a las 9:00 todos de una vez.

**Pendientes:**
1. Ver el CPL del reel de Maider.
2. Optimizar la velocidad del checkout (unos 11 s).
3. Respuestas de los ayuntamientos.
4. Calendario orgánico (a Rosario hay que tirar de ella para que grabe).


---

## Claude · 2026-11-21 20:35

Entendido.

1. **Ajustar la campaña de velas.** Esta mañana dejé en borrador el conjunto de Velas a 12 €/día con radio de 20 km, pero si ahora es la única campaña, 12 € se queda por debajo de vuestros 15-20 €. Propongo subirlo a 15-20 € y quitar Audience Network, que sigue activo. El borrador de Recipientes (8 €/día y 20 km) ya no hace falta porque está pausado; habría que descartarlo antes de publicar. Cuando me digas, hago los cambios.
2. **Ver cuánto cuesta cada lead del reel de Maider y de la V.3 de Velas.** Hay que confirmar que los leads ya se registran bien con el arreglo del píxel. Para juzgarlas les daría hasta el 27-28 de noviembre.
3. **Bajar los 11 s que tarda en cargar el checkout.** Con el objetivo de agotar los talleres de enero, ahora mismo es donde más plazas se pueden perder.
