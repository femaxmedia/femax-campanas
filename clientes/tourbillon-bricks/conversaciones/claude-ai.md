> Conversación completa exportada del proyecto «Campañas publicitarias» de claude.ai el 25 nov 2026. Solo lectura: lo nuevo va en ficha.md, historial.md y campanas/.

# Tourbillon Bricks

- Chat de claude.ai: https://claude.ai/chat/1f73a825-474a-4629-9e25-446125e8ba92
- Creado: 2026-11-20T14:51:50.035604Z · Actualizado: 2026-11-25T07:10:28.714336Z
- Mensajes: 46

---

## Mili · 2026-11-20 14:51

Métete en el perfil de Chrome de Merchant Center y luego métete en Tourbillon Bricks también. Eh, Y mira por cómo, dime la mejor manera de solucionar el problema que nos está dando y que no nos deja publicar los productos, ¿vale? El count interface este que pone, prevent all from showing all countries. Dime cómo podemos solucionarlo, qué opciones tenemos, etcétera.


---

## Claude · 2026-11-20 14:53

Voy a revisar Merchant Center en tu pestaña, entrar en la cuenta de Tourbillon Bricks y ver qué está bloqueando los productos.

_Herramientas: claude-device__chrome_computer, memory__memory_read_

Ya estás dentro de Tourbillon Bricks SL. El problema es **"Counterfeit"** (falsificación). Miro los productos y la web para ver qué lo dispara.

_Herramientas: claude-device__chrome_navigate, claude-device__chrome_get_page_text, claude-device__chrome_navigate, claude-device__chrome_javascript_tool, claude-device__chrome_javascript_tool, claude-device__chrome_javascript_tool, claude-device__chrome_browser_batch, claude-device__chrome_navigate, WebSearch_

Ya lo he visto. Te lo resumo claro: **no es un fallo técnico, es un problema de marca registrada**, y pedir revisión tal como está ahora casi seguro que no va a funcionar.

## Qué está pasando

El aviso es **"Counterfeit"** (falsificación) y bloquea toda la cuenta en todos los países. Google lo detectó de forma automática, y he visto por qué:

- **Los títulos usan nombres de modelos registrados**: Royal Oak (Audemars Piguet), Nautilus (Patek Philippe), y Daytona, Submariner, GMT‑Master II, Yacht‑Master y Deepsea (Rolex). Pasa en casi los 34 productos.
- **Los apodos también son marcas de otros**: Tiffany & Co, Pepsi, Coke, Starbucks, Kermit, Hulk, Captain America, Bruce Wayne, Cookie Monster, Smurf.
- **Las fotos reproducen la esfera original**: en la del Submariner Black la esfera pone "SUBMARINER" y "Superlative Chronometer Officially Certified", y hay una corona dorada en la base. Esto es lo más grave, porque Google considera falsificación cualquier producto con una marca o logo idéntico o casi indistinguible del de otra empresa.
- Las descripciones dicen "homage" e "inspired by", y eso refuerza la lectura de que imita la marca.

**Por qué es serio:** Google trata la falsificación como una infracción "egregious" (muy grave), así que suspende la cuenta al momento y sin aviso previo. Además, solo reactivan cuentas en casos muy justificados, así que la revisión tiene que ser completa y honesta. Y ojo con los intentos: con la cuenta suspendida tienes 2 peticiones de revisión antes de entrar en un periodo de espera. **No le deis a "Request review" todavía.**

## Opciones

**1. Adaptar el catálogo a Google (la que te recomiendo)**
- Poner nombres propios a todos los productos, en títulos, descripciones, URLs y texto alternativo de las imágenes. Por ejemplo "Diver Black" o "Ocean GMT Red/Blue" en lugar de Submariner o GMT Pepsi. Fuera también los apodos que son marcas de otros.
- Hacer fotos o renders nuevos sin textos ni logos de Rolex, AP o Patek en la esfera, ni la corona en la base. Es lo más importante.
- Los cambios tienen que estar **también en la web**, no solo en el feed, porque Google revisa la página del producto.
- Añadir un aviso del tipo "Producto de construcción original, sin relación con ninguna marca relojera".
- Con todo hecho, pedir **una** revisión explicando qué se ha cambiado.
- Aun así hay riesgo: la política también prohíbe productos que imitan rasgos de la marca para pasar por originales. Si la forma del reloj sigue siendo idéntica, podrían volver a marcarlo.

**2. Mandar a Google solo lo que cumple**
Excluir del canal de Google en Shopify los productos problemáticos. Ahora mismo solo quedarían la Gift Card y el Mystery Watch, así que solo sirve como apaño. **Lo que no hay que hacer** es poner nombres neutros solo en el feed y dejar la web igual: Google lo ve como engaño y empeora la situación.

**3. Recurrir diciendo que no es falsificación**
Se puede argumentar que es un juguete de construcción y no un reloj. Pero con esas fotos y esos nombres las probabilidades son muy bajas, y gastarías uno de los 2 intentos.

**Lo que no hay que hacer nunca:** abrir otra cuenta de Merchant Center. Google lo considera saltarse sus sistemas, otra infracción grave, y suspende también las cuentas nuevas.

## Para comentar con el cliente
- Esto no afecta solo a Google. Meta también tiene políticas de propiedad intelectual, y Rolex o AP podrían denunciar los anuncios igualmente. No soy abogado: si el negocio depende de estos nombres, conviene que lo consulten con alguien de propiedad industrial.
- Hay otro aviso menor: **no hay cuenta de Google Ads vinculada**. Tiene arreglo fácil, pero no sirve de nada hasta que se resuelva lo de la falsificación.

Si queréis ir por la opción 1, puedo prepararos una tabla con los 34 productos: el nombre actual, un nombre nuevo propuesto y qué hay que cambiar en cada foto.


---

## Mili · 2026-11-20 14:56

No vamos a poder cambiar los productos en la web, ni los nombres, ni las fotos, porque nuestros productos son así, son Rolex, perdón, son relojes de lujo, pero no son réplicas del reloj, son construcciones de ladrillo que hacen esos relojes de lujo. Entonces, eh, ¿hay alguna manera de hacerlo sin cambiar las cosas en la web?


---

## Claude · 2026-11-20 14:56

Siendo sincera: **sin tocar nada de la web hay muy poco margen.** Además, el argumento de que no es una réplica sino un modelo de ladrillos no cambia lo que mira Google.

**Por qué no basta con que sea de ladrillos**

La política de falsificaciones no exige que el producto sea un reloj falso. Lo que mira es si el producto lleva una marca o un logo idéntico al de otra empresa sin su permiso. Las piezas llevan "SUBMARINER" y la corona de Rolex, y se venden con los nombres de los modelos. Para Google eso es suficiente, sea un reloj, una funda o un juguete de construcción. Por eso las marcas como LEGO que hacen coches de Porsche o Ferrari tienen licencia oficial.

**Lo que se puede intentar sin cambiar la web**

1. **Pedir revisión argumentando que es otro tipo de producto.** Es la única vía directa. Hay que explicar que es un kit de construcción decorativo y no un reloj, que no se puede llevar puesto ni funciona, que nadie lo compra pensando que es un Rolex auténtico y que el precio no tiene nada que ver con el del original. Si lo hacéis, añadid en la web un aviso de "sin relación con Rolex, Audemars Piguet ni Patek Philippe". Eso no cambia los productos y ayuda. Siendo realistas, las probabilidades son bajas y solo tenéis 2 intentos antes del periodo de espera. Antes de gastar uno, yo hablaría con el soporte de Merchant Center por chat o teléfono para ver qué dicen de este caso.

2. **Si no sale, aceptar que Shopping no es el canal para este catálogo** y centrar la inversión donde ya os funciona: Meta Ads, email y el resto.

**Lo que no os recomiendo**

- **Cambiar solo el feed** (nombres neutros en Google y la web igual). Google compara el feed con la página del producto. Si no coinciden, lo considera engaño y la cuenta se complica aún más.
- **Abrir otra cuenta de Merchant Center.** Cuenta como saltarse los sistemas y suelen tumbar también la nueva.
- **Pasar a anuncios de búsqueda usando "Rolex" en el texto.** Google Ads aplica la misma política de falsificaciones, y una infracción ahí puede costaros también la cuenta de Ads.

**Un aviso para el cliente:** esto no lo decide solo Google. Rolex, AP y Patek pueden denunciar directamente en Meta, en Shopify o por la vía legal, y eso no depende de que el producto sea de ladrillos. No soy abogado. Si toda la marca gira en torno a estos modelos, merece la pena que lo consulten con un especialista en propiedad industrial, aunque solo sea para saber cuánto riesgo están asumiendo.

Si queréis ir a por la revisión, puedo redactaros el texto de la apelación y el aviso para la web.


---

## Mili · 2026-11-20 15:05

_Archivo: Captura de pantalla 2026-11-20 a las 16.03.53.png_

que les pogo a soporte para que me puedan ayudar


---

## Claude · 2026-11-20 15:05

Ese campo admite como mucho 100 caracteres, así que ahí solo va un resumen. Lo importante lo explicas después, en el chat o la llamada.

**Para el campo "Tell us what we can help with"** (95 caracteres):

> Account suspended for Counterfeit. We sell brick building kits, not watches. How can we comply?

Si prefieres que te atiendan en español:

> Cuenta suspendida por Counterfeit. Vendemos kits de bloques, no relojes. ¿Cómo podemos cumplir?

Después dale a **Next**, en *Contact options* elige **chat o llamada** (mejor que email) y cuando te atiendan, explícalo así:

> Hola. Nuestra cuenta de Merchant Center (ID 5910804902, TourBillon Bricks SL) tiene un aviso de "Counterfeit" que bloquea todos los productos.
>
> Lo que vendemos son kits de construcción de bloques (tipo LEGO) que reproducen relojes de lujo como objeto decorativo y de colección. No son relojes, no funcionan, no se pueden llevar puestos y no se venden como productos originales de ninguna marca relojera. El precio y la descripción lo dejan claro.
>
> Antes de pedir la revisión queremos saber exactamente qué tenemos que cumplir:
> 1. ¿Basta con añadir en la web un aviso claro de que no tenemos relación con las marcas?
> 2. ¿El problema son los nombres de los modelos en los títulos, los textos de las esferas en las fotos, o ambos?
> 3. ¿Hay alguna forma de que este tipo de producto (réplica a escala en bloques) sea aceptable en Shopping?
>
> No queremos gastar un intento de revisión sin saber qué cambiar.

Antes de la llamada, ten en cuenta esto:
- **Pide que no te abran la revisión ellos.** Si te ofrecen enviarla, contesta que primero quieres saber qué hay que cambiar. Ya sabes que solo hay 2 intentos.
- **Apunta el número de caso** y, si puedes, pide la respuesta por escrito.
- Si te dicen que hay que quitar los nombres o los logos de las fotos, ya tendréis la confirmación oficial para hablarlo con el cliente.


---

## Mili · 2026-11-20 15:06

Métete y mira los documentos que me ha facilitado por si algo puede ayudar.


---

## Claude · 2026-11-20 15:07

_Herramientas: claude-device__chrome_computer, claude-device__chrome_javascript_tool, WebFetch, WebFetch, WebFetch, claude-device__chrome_find, claude-device__chrome_browser_batch, claude-device__chrome_browser_batch, WebSearch_

He revisado la ayuda que te sale en el panel y las opciones de la pantalla. Hay tres cosas que sí os pueden servir sin tocar los productos de la web.

**1. Google recomienda poner un aviso, y no hace falta tocar los productos**
En las buenas prácticas de su política, si mencionas otra marca sin ser socio autorizado, sugieren "considerar un aviso" en la web y en los listados. Lo añadiría antes de pedir la revisión, en el pie de página, en cada ficha de producto y en las descripciones del feed. Por ejemplo: *"Tourbillon Bricks crea modelos de construcción decorativos. No tenemos relación con Rolex, Audemars Piguet ni Patek Philippe, ni contamos con su respaldo. Los nombres se usan solo como referencia."* Así demostráis que no intentáis hacer pasar el producto por el original, que es justo lo que castiga la política. Que sea suficiente no está garantizado, porque también prohíben productos no auténticos que lleven etiquetas o logos de la marca, y las esferas los llevan.

**2. Puedes recurrir directamente diciendo que no estás de acuerdo**
En "Request review" hay dos opciones: *"I fixed the issue"* y *"I disagree with the issue"*. Vuestro caso es la segunda. En la apelación puede que te pidan un motivo o que subas documentación. Yo subiría fotos del producto montado y de la caja, el aviso de la web y una explicación de que son kits de construcción. Una precisión sobre lo que te dije antes: Google no da un número fijo de intentos. Solo dice que hay varias oportunidades antes de un periodo de espera, y que cada revisión fallida puede alargar esa espera. Así que conviene mandarla una vez y bien preparada. Las revisiones suelen tardar unos 7 días laborables.

**3. Hay una apelación externa, por estar en la UE**
Abajo, en "Show additional options", aparece la opción de apelación externa, con tu Reference ID (5910804902) y el Routing ID (RDAX). Funciona por la normativa europea de servicios digitales (DSA): si Google rechaza tu recurso, puedes llevar el caso a un organismo independiente certificado. Por ejemplo, ADR Center está certificado según el artículo 21 de la DSA y gestiona casos de suspensiones de Merchant Center. Para abrir el caso piden el Reference ID que aparece en la notificación. Lo malo es que su decisión no es vinculante y Google dice que no está obligado a cumplirla. Aun así, es una revisión hecha por personas, y en un caso como el vuestro, que es discutible, puede ayudar.

**El orden que yo seguiría:**
1. Llamar o escribir hoy al soporte con el texto que te pasé y preguntarles en concreto si el aviso de la web es suficiente.
2. Añadir el aviso en la web y en el feed.
3. Pedir la revisión con *"I disagree with the issue"*, adjuntando fotos y la explicación.
4. Si la rechazan, ir a la apelación externa.

Si quieres, te escribo ya la apelación completa en inglés y el aviso para la web en inglés y en español.


---

## Mili · 2026-11-20 15:11

Vale, prepárame un documento explicando esto, ¿vale? Eh, Y bueno, primero vamos a intentar llamar a escribir a soporte. ¿Cómo puedo hacerlo?


---

## Claude · 2026-11-20 15:12

Primero te explico cómo contactar con soporte, y mientras tanto te monto el documento.

**Cómo contactar con soporte de Merchant Center** (ya lo tienes abierto en el panel de Ayuda de la derecha):

1. **Paso 1 – "What can we help with?"**: deja seleccionada la cuenta de Google Ads *Tourbillo 976-675-6378*, pega este texto y dale a **Next**:
   > Account suspended for Counterfeit. We sell brick building kits, not watches. How can we comply?
2. **Paso 2 – Resources**: te enseña artículos de ayuda. Dale a **Next step** sin abrir ninguno.
3. **Paso 3 – Contact options**: elige **Chat** si te aparece, porque es lo más rápido y queda por escrito. Si no, **Request a call**. El email déjalo como último recurso.

Si cierras el panel, vuelves a abrirlo desde el icono **?** de arriba a la derecha → **Contact us** / **Get support**.

El horario de atención en español suele ser de lunes a viernes por la mañana y a primera hora de la tarde. Si hoy no te sale el chat, prueba el lunes por la mañana. Cuando te atiendan, pega el mensaje largo que te pasé, pide el **número de caso** y **no dejes que te envíen la revisión** hasta que te digan qué hay que cambiar.

_Herramientas: ToolSearch, claude-artifacts__list_types, Claude_Docs__guide, Skill, Claude_Docs__batch_

Esquema creado: [Tourbillon Bricks – Bloqueo en Google Merchant Center](https://claude.ai/artifact/7UBkEBEXkWFLHbP6nwPsAL). Ahora relleno el resumen.

_Herramientas: Claude_Docs__guide, Claude_Docs__update, Claude_Docs__update, Claude_Docs__update, Claude_Docs__update, Claude_Docs__update, Claude_Docs__update, Claude_Docs__update, Claude_Docs__update_

El documento ya está terminado: explica por qué Google bloquea los productos, las opciones que tenéis sin cambiar la web, un plan paso a paso y los textos listos para copiar (soporte, aviso de no afiliación y apelación). Puedes editarlo directamente o dejar comentarios: [Tourbillon Bricks – Bloqueo en Google Merchant Center](https://claude.ai/artifact/7UBkEBEXkWFLHbP6nwPsAL).


---

## Mili · 2026-11-20 15:47

como conecta el merchancenter a google ads


---

## Claude · 2026-11-20 15:47

_Herramientas: claude-device__chrome_browser_batch, claude-device__chrome_browser_batch, claude-device__chrome_browser_batch, claude-device__chrome_browser_batch_

Lo he mirado en la cuenta y hay un detalle importante: **Merchant Center ya tiene una cuenta de Google Ads vinculada, pero no es la que usáis.**

En *Settings → Access and services → Connected services* aparece:
- **Google Ads 243-011-6841**, en estado Active.
- **Google & YouTube app (Shopify)**, que es por donde entran los productos.

La cuenta de Google Ads que te sale en soporte es otra: **Tourbillo 976-675-6378**. Lo más probable es que la 243-011-6841 sea una cuenta de administrador (MCC) o una antigua. Por eso Merchant Center sigue mostrando el aviso de "No Google Ads account linked": no tiene enlazada ninguna cuenta de anuncios que pueda lanzar campañas.

**Cómo vincular la 976-675-6378:**

1. **En Merchant Center:** *Settings → Access and services →* pestaña **Discover services** → **Google Ads** → **Link account**. Elige la 976-675-6378 de la lista o escribe el ID, y envía la solicitud.
2. **En Google Ads** (cuenta 976-675-6378): *Herramientas → Gestor de datos* (Data manager) → **Google Merchant Center**. Te aparecerá la solicitud pendiente de TourBillon Bricks SL: dale a **Aprobar**.
   - Si en el paso 1 usas el mismo usuario y eres administradora en las dos cuentas, a veces se aprueba sola.
3. Vuelve a *Connected services* y comprueba que aparece la 976-675-6378 en estado **Active**.

**Otra forma:** como los productos entran por Shopify, también podéis conectar Google Ads desde la app *Google & YouTube* de Shopify (Ajustes → Google Ads → conectar cuenta). Hace lo mismo.

Dos avisos:
- **Vincularla ahora no hará que salgan anuncios de Shopping.** Los 792 productos siguen "Not approved" por el bloqueo de Counterfeit. Hasta que se levante, la vinculación solo deja todo preparado.
- Antes de desvincular la 243-011-6841, confirmad qué es. Si es la MCC de la agencia o del cliente, dejadla como está.

¿Quieres que mande yo la solicitud de vinculación desde Merchant Center a la 976-675-6378? La aprobación en Google Ads la tendrías que hacer tú.


---

## Mili · 2026-11-20 15:49

_Archivo: Captura de pantalla 2026-11-20 a las 16.49.09.png_

la cuenta es esta como le doy acceso a mi correo de mili


---

## Claude · 2026-11-20 15:49

Entonces la cuenta buena es la **243-011-6841**, que es justo la que ya está vinculada a Merchant Center. No hace falta vincular otra. Fíjate en que pone **"Configuración en curso"**: la cuenta no está activada del todo, y probablemente por eso Merchant Center sigue diciendo "No Google Ads account linked". Se arreglará cuando terminéis la configuración (datos de la empresa y facturación).

**Para darle acceso a tu correo en Google Ads** (desde esa misma sesión de tourbillonbricks@gmail.com):

1. Cierra el menú de la cuenta y, en la barra de la izquierda, entra en **Administración** (Administr…).
2. Ve a **Acceso y seguridad** → pestaña **Usuarios**.
3. Pulsa el botón azul **+**.
4. Escribe tu correo y elige el nivel de acceso **Administrador**, para poder gestionar todo y vincular cuentas.
5. Dale a **Enviar invitación**.
6. Abre tu correo, acepta la invitación y la cuenta te aparecerá en tu sesión de Google Ads.

**Si Femax tiene una cuenta de administrador (MCC)**, es mejor vincularla desde la MCC: *Cuentas → + → Vincular cuenta existente* con el ID 243-011-6841, y aceptar la solicitud desde la cuenta de Tourbillon. Así ves todos los clientes desde un solo sitio y el cliente puede quitarte el acceso cuando quiera sin tocar nada más.

**En Merchant Center**, si también quieres entrar con tu correo: *Settings → Access and services → People and access → Add person*, pones tu correo y le das rol de Admin.


---

## Mili · 2026-11-20 15:53

voy a volver a intentar pedirle yuda a soporte ahora que ya tengo conectada la cuenta que pongo aqui


---

## Claude · 2026-11-20 15:53

Ahora en el desplegable de cuenta de Google Ads elige la **243-011-6841 (Tourbillonbricks)**.

**En el campo corto** (máximo 100 caracteres):

> Account suspended for Counterfeit. We sell brick building kits, not watches. How can we comply?

Después: **Next → Next step → Chat** (o llamada si no hay chat).

**Cuando te atiendan, pega esto:**

> Hola. Nuestra cuenta de Merchant Center (ID 5910804902, TourBillon Bricks SL), vinculada a Google Ads 243-011-6841, tiene un aviso de "Counterfeit" que bloquea todos los productos.
>
> Vendemos kits de construcción de bloques que reproducen relojes de lujo como objeto decorativo y de colección. No son relojes, no funcionan, no se pueden llevar puestos y no se venden como productos originales de ninguna marca relojera.
>
> Antes de pedir la revisión queremos saber qué tenemos que cumplir:
> 1. ¿Basta con añadir un aviso claro de no afiliación en la web y en el feed?
> 2. ¿El problema son los nombres de los modelos, los textos de las esferas en las fotos, o ambos?
> 3. ¿Este tipo de producto (réplica a escala en bloques) puede ser aceptable en Shopping?
>
> No queremos gastar un intento de revisión sin saber qué cambiar.

Recuerda pedir el **número de caso** y no dejar que te envíen la revisión ellos. Si te dicen algo útil, pásamelo y lo añado al documento.


---

## Mili · 2026-11-20 15:54

Cuando le doy a Fix Your Serpent Account me lleva un link a Google Ads directamente. No me deja contactar con nadie.


---

## Claude · 2026-11-20 15:55

_Herramientas: claude-device__chrome_computer, claude-device__chrome_browser_batch, claude-device__chrome_browser_batch, claude-device__chrome_computer_

Ya veo por qué no te deja contactar con nadie. En el paso 3 aparece este aviso: **"The selected Google Ads customer ID is suspended"**. Es decir, **la cuenta de Google Ads 243-011-6841 también está suspendida**. Lo más probable es que sea por estar vinculada a un Merchant Center bloqueado por Counterfeit. Cuando la cuenta de Ads seleccionada está suspendida, Google no te deja abrir chat ni llamada: te manda directamente al solucionador de suspensiones.

Tienes dos caminos:

**1. Seguir el solucionador ("Fix your suspended account")**
Es el camino oficial. Te lleva a Google Ads y desde ahí aparece un formulario de apelación de la suspensión. En ese formulario puedes explicar el caso con el texto largo que te pasé. Antes de enviarlo, mira en Google Ads qué motivo de suspensión indica (aparece en el aviso rojo de arriba). Si es por "cuenta vinculada suspendida", Ads se reactivará sola cuando se resuelva lo de Merchant Center.

**2. Abrir el chat seleccionando otra cuenta de Google Ads**
En el desplegable del paso 1 te aparecen otras cuentas a las que tienes acceso. Si eliges una que no esté suspendida, normalmente sí te ofrece chat o llamada. Si lo haces, explica al principio del chat que la consulta es sobre el **Merchant Center 5910804902 (TourBillon Bricks SL)** y que la cuenta de Ads de Tourbillon está suspendida. Así el agente mira la cuenta correcta. Lo mejor es usar una cuenta de Femax si la tienes, no la de otro cliente.

Yo probaría primero la opción 2, porque necesitas hablar con alguien antes de gastar la apelación. Si no te ofrecen contacto, ve a la 1.

He actualizado contigo la situación, pero no el documento. ¿Quieres que añada que la cuenta de Google Ads también está suspendida?


---

## Mili · 2026-11-20 16:01

_Archivo: Captura de pantalla 2026-11-20 a las 17.00.24.png_

No quiero enviar nada sin querer, pero quería ver que, porque voy a preparar un documento con lo que necesitamos para enviar la apelación. Entonces, esto, para ello, aquí, ¿qué debería marcar? ¿Y qué le tengo que pedir al cliente para enviar bien la aprobación?


---

## Claude · 2026-11-20 16:01

Has hecho bien en no enviarlo. En el aviso azul pone que **solo puedes pedir la revisión por "no estar de acuerdo" una vez**. Si la rechazan, tienes que corregir el problema y esperar unos días antes de volver a pedirla. Así que esto se envía una sola vez y bien preparado.

## Qué marcar

Mirando cómo son los productos de verdad:

| Opción | ¿Encaja? |
| --- | --- |
| **My account meets the policy requirements** | **Sí. Es la que te recomiendo.** Es la opción general para defender que el producto no es una falsificación: es un kit de construcción y no se hace pasar por el original. |
| The product details… do not mention a brand… | **No.** Los títulos dicen Submariner, Daytona, Royal Oak… Sería falso. |
| I run… an official store for a brand | **No.** No son tienda oficial de ninguna marca. |
| My product details mention inspiration from a brand but do not use brand features | **Ahora no.** Las fotos llevan "SUBMARINER" en la esfera y la corona en la base, que son rasgos de la marca. Solo valdría si el cliente quitara eso de las fotos. |

Marcar una opción que no es cierta es peor que no recurrir. Google revisa la web, y si ve que la respuesta no coincide, el único intento se pierde y pierdes credibilidad para el siguiente.

## Qué pedirle al cliente

**Imprescindible**
1. **Fotos reales del producto**: montado, en su caja, las instrucciones y las piezas sueltas. Si puede ser, alguna con algo que dé la escala, como una mano o una mesa. Así se ve que es un kit de bloques y no un reloj.
2. **Ficha técnica**: número de piezas, medidas, material (plástico ABS) y la confirmación de que no funciona ni se puede llevar puesto.
3. **Registro de su marca "Tourbillon Bricks®"**: en la web usan ®, así que pídele el certificado de la OEPM o la EUIPO. Demuestra que venden con su propia marca.
4. **Que acepte poner el aviso de no afiliación** en el pie de la web, en las fichas de producto y en el feed. Tiene que estar publicado **antes** de enviar la apelación.
5. **Que quite de las descripciones las palabras "homage", "replica" e "inspired by"**. No cambia ni los nombres ni las fotos, y elimina términos que la política menciona directamente.

**Importante para saber el riesgo**
6. ¿Tienen **algún acuerdo o licencia** con alguna de las marcas? Si es así, cambia todo y hay que adjuntarlo.
7. ¿Han recibido alguna vez **avisos o reclamaciones** de Rolex, AP o Patek, o retiradas de anuncios en Meta, Amazon u otros sitios?
8. Que confirme que los **datos de la empresa coinciden** en la web y en Merchant Center: razón social, dirección, teléfono, email y políticas de devolución y envío.

**Aparte:** la cuenta de Google Ads 243-011-6841 también está suspendida. Eso tiene su propia apelación, que se hace después, cuando se resuelva lo de Merchant Center.

¿Quieres que añada una sección "Preparación de la apelación" al documento con esta tabla y la lista para el cliente? Así se la puedes reenviar tal cual.


---

## Mili · 2026-11-20 16:02

Vale, preparamos un documento con lo que necesitamos del cliente, también diciendo lo que tienen que poner en la web de las descripciones y eso. En plan, preparar un documento diciendo que vamos a apelar, pero que antes de apelar necesitamos tener toda esta información para subirla, etcétera.


---

## Claude · 2026-11-20 16:03

_Herramientas: Claude_Docs__batch_

Esquema listo: [Tourbillon Bricks – Preparación de la apelación](https://claude.ai/artifact/KpaFQq6UQjiGMfif9TFjUk). Ahora escribo la introducción.

_Herramientas: Claude_Docs__update, Claude_Docs__update, Claude_Docs__update, Claude_Docs__update, Claude_Docs__update_

He preparado el documento para el cliente: explica por qué vamos a apelar, qué documentación necesitamos que nos envíen, qué tienen que cambiar en la web y en las descripciones (con los textos ya escritos), las preguntas que deben responder y los próximos pasos.

Puedes revisarlo, editarlo o compartirlo: [Tourbillon Bricks – Preparación de la apelación](https://claude.ai/artifact/KpaFQq6UQjiGMfif9TFjUk)


---

## Mili · 2026-11-21 20:33

TOURBILLON BRICKS

📌 BRIEF ACTUALIZADO (21 nov 2026) — contexto de este cliente con todo lo revisado hoy y los últimos días. Tómalo como base para todo lo que hablemos en este chat a partir de ahora. Responde solo con 'Entendido' y las 3 prioridades inmediatas.

**Cliente:** Tourbillon Bricks (tourbillonbricks.com). Venden construcciones en bricks de relojes de lujo. No son réplicas.
**Qué lleva Femax:** Meta Ads (campañas por país), Google Ads, Google Merchant Center, email marketing en GHL (bases de fans de Lego/bricks, con el logo de Canva) y creatividades de ads.

**Cuentas:**
- Meta Ads: 2237541826642480
- Google Ads: 243-011-6841
- Fotos de producto en Drive: https://drive.google.com/drive/folders/1zSXNqusBXgvigbUhHRl3cZGXikCdjNuR

**Reglas de rendimiento:**
- ROAS mínimo 2,26, mirado por anuncio (antes se usaba 2,5–3).
- Un anuncio que gaste más de 90 € sin ventas se pausa.

**Black Friday / Cyber Week 2026:**
- Fases del 19 oct al 9 dic. Black Friday el 27 nov, Cyber Monday el 30 nov.
- Ofertas: 20% de descuento y 3x2 (compras 2 y te llevas la tercera gratis, automático en el carrito).
- Estructura Meta (chat del 19 nov): prospección USA 230 €/día y UK 190 €/día, testing 40 €, retargeting de 40 a 70 €. Anuncios [20] y [3x2].
- Documento de estructura: @https://claude.ai/artifact/PH9rURNdpeYg6NXVfb27AB

**Estado Meta, últimos 7 días:**

| Campaña | Gasto | Compras | Coste/compra | ROAS |
|---|---|---|---|---|
| C1 · BFCM26 PROSPECCIÓN | 610,04 € | 9 | 67,78 € | 1,45 |
| C2 · BFCM26 TESTING | 47,84 € | 0 | – | – |
| C3 · BFCM26 RETARGETING | 50,61 € | 2 | 25,31 € | 3,77 |
| **Total** | **≈708 €** | **11** | | |

- Prospección está por debajo del ROAS mínimo de 2,26. Hay que revisar los anuncios uno a uno y pausar los que pasen de 90 € sin ventas.

**Google:**
- La campaña de Black Friday (mismos países que Meta) está en pausa hasta que Merchant Center apruebe los productos.
- Merchant Center está bloqueado por "Counterfeit". Decisión: no se cambian ni nombres ni fotos en la web.
- Plan: primero contactar con el soporte de Google y después apelar. Antes, Mili prepara un documento para el cliente con la documentación y los cambios de descripción necesarios.

**Otros:**
- Panel/agente que genera creatividades estáticas (fotos reales, textos en inglés) y analiza la competencia. La referencia principal es minibricks.
- Las tareas se reparten en reunión con el cliente.

**Próximos pasos:**
1. Optimizar la prospección por anuncio antes del 27 nov.
2. Escalar el retargeting en la semana de BF.
3. Desbloquear Merchant Center.


---

## Claude · 2026-11-21 20:33

Entendido.

**Las 3 prioridades inmediatas:**

1. **Optimizar la prospección por anuncio antes del 27 nov.** C1 está en ROAS 1,45, por debajo del mínimo de 2,26. Hay que revisar los anuncios uno a uno, pausar los que pasen de 90 € sin ventas y pasar el presupuesto a los que estén por encima de 2,26.
2. **Escalar el retargeting para la semana de Black Friday.** C3 tiene un ROAS de 3,77 con solo 50 € gastados. Hay que subirlo hacia los 70 €/día y tener listos los anuncios [20] y [3x2] para el 27 y el 30 de noviembre.
3. **Desbloquear Merchant Center.** Enviar al cliente el documento de preparación de la apelación, conseguir su documentación y los cambios en la web, hablar con soporte y apelar una sola vez. Ojo: la cuenta de Google Ads 243-011-6841 también aparece suspendida, así que la campaña de Black Friday en Google tampoco podrá salir hasta que se resuelva.


---

## Mili · 2026-11-21 20:48

📌 CORRECCIÓN AL BRIEF — estado real de Google (21 nov), del chat "Campañas de Google para Tourbillon". Sustituye a lo que decía el brief sobre Google:

- El bloqueo por "Counterfeit" ya NO aparece en Merchant Center (sin problemas de cuenta).
- Merchant Center y YouTube vinculados a Google Ads; Shopify (app Google & YouTube) conectada a la cuenta 243-011-6841, con medición de conversiones y conversiones mejoradas en verde.
- Corregido el envío de USA y UK (la moneda no coincidía con el feed). Promo 3x2 creada en Merchant Center para USA (aprobada por política, pendiente de revisión de producto) y UK (guardada).
- Campaña creada: **BFCM26 | PMax | USA+UK** (ID 24530566064), 100 €/día, 13 imágenes, 6 vídeos y 8 temas de búsqueda. **Está en PAUSA** y sin gasto.

Para reactivarla tienen que cumplirse tres cosas:
1. Productos de USA y UK aprobados en Merchant Center (de "limitados" a aprobados).
2. La conversión "Google Shopping App Purchase" activa (basta con una venta en la web).
3. Anuncios revisados.

Próximo paso: revisar mañana (domingo 22) si se cumplen y, si sí, reactivarla y vigilarla. Black Friday es el 27. Para revisarlo se entra por el navegador de la app de Claude, que ya tiene la sesión de Google iniciada.

Responde solo "Anotado".


---

## Claude · 2026-11-21 20:48

Anotado.


---

## Mili · 2026-11-22 17:19

Revisa a ver si ya nos han aprobado el tema de productos en Google Ads para publicar campaña en Google de Turulla.


---

## Claude · 2026-11-22 17:24

Voy a abrir Google Ads y Merchant Center en el navegador de la app para comprobar las tres condiciones de la campaña PMax.

_Herramientas: Skill, ToolSearch, remote-devices__Claude_Browser__preview_start, remote-devices__Claude_Browser__get_page_text, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__find, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__find, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__find, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__get_page_text, remote-devices__Claude_Browser__find, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__javascript_tool, remote-devices__Claude_Browser__computer, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__find, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__find, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__javascript_tool, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__find, remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch_

Todavía no se puede activar. **Los productos siguen sin aprobar** y la campaña continúa en pausa. Esto es lo que he comprobado hoy en Merchant Center y Google Ads:

**1. Productos de USA y UK aprobados: ❌ todavía no**
- Hay 792 productos: 0 aprobados, 792 "limitados" y 0 rechazados.
- En los productos de USD y GBP aparece **"Pending initial review"**, que limita la visibilidad en USA, UK y Emiratos. Google aún no ha terminado la revisión inicial tras levantar el bloqueo. Es una espera, no hay nada que corregir.
- La cuenta está limpia: en *Setup and policy issues* pone "No issues for you to fix". Lo de Counterfeit sigue resuelto.
- El aviso de **"Mismatched currency"** sale en los 792 productos, pero no es un bloqueo real. Shopify crea un feed por moneda (CHF, CAD, AUD, JPY… 22 en total) y todos apuntan también a USA y UK. Google se queja de que un producto en francos suizos no casa con el envío de USA. El feed en USD solo da el aviso para UK y el feed en GBP solo para USA, así que cada país tiene su feed correcto. Se puede ignorar.

**2. Conversión de compra activa: ❌ todavía no**
- El objetivo "Compra" está en **"Requiere atención"**, con 0 compras registradas. Hace falta que entre una venta en la web para que se active.

**3. Anuncios revisados: ⏳ pendiente**
- La campaña está en pausa, con 0 impresiones y 0 €. Google suele revisar los anuncios de PMax del todo cuando los productos están aprobados.

**Un riesgo a tener en cuenta:** las URLs de los productos llevan marcas en el enlace, por ejemplo `/products/lego-rolex-gmt-master-ii-coke` o `/products/lego-audemars-piguet-ap-royal-oak-waffle-black`. Incluyen "Rolex", "Audemars Piguet" y también "LEGO", que es otra marca registrada. Ahora mismo no está bloqueando nada, pero el filtro automático de Counterfeit puede volver a saltar en la revisión. No lo cambiaría ahora, porque cambiar la URL de cada producto reinicia la revisión. Lo dejaría para después de Black Friday.

---

**ESTADO ACTUAL (22 nov 2026)**
- **Campaña:** BFCM26 | PMax | USA+UK (ID 24530566064), 100 €/día, **en pausa**, gasto 0 €.
- **Merchant Center:** sin problemas de cuenta. Los productos de USD y GBP están en revisión inicial ("Pending initial review"), con 0 aprobados. El aviso de moneda viene de los feeds de otras monedas de Shopify y no bloquea.
- **Conversiones:** "Compra" en "Requiere atención", sin ninguna venta registrada todavía.
- **Decisión:** no reactivar hasta que los productos de USD y GBP estén aprobados.
- **Próximo paso:** volver a revisar el **lunes 23 nov**. Si siguen pendientes, contactar con el soporte de Merchant Center para pedir que agilicen la revisión de cara al Black Friday del 27.


---

## Mili · 2026-11-23 06:29

_Archivo: BF27 - 4.mp4_

Tengo este nuevo vídeo que promociona la oferta de 3 relojes al precio de 2, o mejor dicho, por la compra de 2 relojes te llevas 1 gratis. ¿Lo pondrías en alguno de las 3 campañas? Si es así, prepáralo todo para que yo solo tenga que publicarlo.


---

## Claude · 2026-11-23 06:30

Voy a revisar el vídeo y el estado actual de las tres campañas de Meta para decidir dónde encaja y dejarlo preparado en borrador.

_Herramientas: Bash, ToolSearch, Bash, Read, Meta_Ads__ads_get_ad_entities, Meta_Ads__ads_get_creatives, Bash, Read, Bash, Read, Meta_Ads__ads_create_upload_url, Meta_Ads__ads_get_ad_videos, Meta_Ads__ads_creative_upload_media_

Sí, lo pondría. Ya tengo todo preparado, pero **necesito que subas el vídeo a la cuenta publicitaria** (desde aquí no puedo subir archivos directamente a Meta) y **hay una errata en el vídeo** que conviene corregir antes de publicar.

## ⚠️ Antes de nada: la errata
En el cierre (segundos 18 a 20) pone **"ONLY AVAIBLE AT"**. Debería poner **"ONLY AVAILABLE AT"**. Es justo el último texto que se ve antes de la URL, y en una marca que vende "lujo" se nota. Te recomiendo corregirlo y subir la versión arreglada.

## Dónde lo pondría

**C2 · TESTING, en el conjunto "UK | ABIERTO | TEST"**, como `[3x2] BF27 - 4_v1`.

Motivos, con los datos de los últimos 7 días:
- Es un vídeo nuevo, y C2 está para eso: ahí ya están probándose los otros vídeos BF27 ("LENTO_v2").
- El ángulo 3x2 está funcionando muy bien. En C1 USA, `[3x2] THE PIECES` tiene un **ROAS de 5,35** (62 €, 3 compras). En C2, `[3x2] LOWEST PRICE B` tiene un **ROAS de 6,98** (14,5 €, 1 compra).
- No lo metería directamente en C1 porque ahí ya hay 11 anuncios repartiéndose el presupuesto, y el que más gasta (`BF_VENTA_1` UK, 272 €) está en un ROAS de 1,66.

Black Friday es el jueves, así que no da tiempo a esperar los 7 días habituales. Si el miércoles 25 lleva un ROAS de 2,26 o más, lo duplicamos a C1 (USA y UK) para el BF.

**Texto del anuncio** (mismo estilo que los 3x2 que ya funcionan, adaptado al "compra 2 y llévate 1 gratis"):
- **Texto principal:**
  > Buy 2, get the 3rd FREE.
  >
  > Start your watch collection for less, or keep one and gift two to the watch lovers in your life. Your free piece is added automatically at checkout.
  >
  > Black Friday only, while stock lasts.
- **Título:** Buy 2, Get 1 FREE – Black Friday
- **Descripción:** Free Worldwide Shipping
- **Botón:** Shop Now → tourbillonbricks.com/collections/geneve
- **Página e Instagram:** los mismos de los anuncios actuales

## Lo que necesito de ti
Arriba te ha aparecido el **cuadro de subida de Meta**. Elige el vídeo (mejor ya corregido), pulsa **Continue** y envía el mensaje que se genera. Con eso creo el anuncio en borrador en C2 y te paso la vista previa para que solo tengas que publicarlo.

---

**ESTADO ACTUAL (23 nov 2026)**
- **Activo en Meta:** C1 Prospección (USA y UK), C2 Testing (UK), C3 Retargeting (USA+UK). Los 3x2 con mejor resultado de la semana son `[3x2] THE PIECES` USA (ROAS 5,35) y `[3x2] LOWEST PRICE B` en Testing (ROAS 6,98).
- **Nuevo vídeo BF27 - 4:** decidido para C2 Testing UK. Copy listo. Falta subir el vídeo y corregir "AVAIBLE".
- **Google:** campaña PMax en pausa a la espera de que se aprueben los productos de USD y GBP. Revisión hoy, 23 nov.
- **Próximo paso:** hoy, subir el vídeo y crear el borrador. Miércoles 25: decidir si pasa a C1 antes del Black Friday del 27.


---

## Mili · 2026-11-23 06:34

ya lo he subido a uno que se llama xxx en testingo para que lo pongamos a punto y publique


---

## Claude · 2026-11-23 06:35

_Herramientas: Meta_Ads__ads_get_ad_entities, Meta_Ads__ads_get_ad_entities, Meta_Ads__ads_get_ad_videos, ToolSearch, Meta_Ads__ads_update_entity, Meta_Ads__ads_get_ad_preview_

He dejado listo el anuncio que subiste como "xxx". Está en borrador y solo falta que lo publiques.

**Qué he cambiado:**
- **Nombre:** `[3x2] BF27 - 4_v1` (antes "xxx").
- **Ubicación:** C2 · TESTING → "UK | ABIERTO | TEST", donde lo habías puesto.
- **Texto:** el anuncio era un duplicado del `[20] BF27 LENTO_v2` y tenía el copy del 20% de descuento, más variantes de texto generadas por Meta también sobre el 20%. No encajaban con un vídeo del 3x2, así que lo he cambiado todo por:
  - **Texto principal:**
    > Buy 2, get the 3rd FREE.
    >
    > Start your watch collection for less, or keep one and gift two to the watch lovers in your life. Your free piece is added automatically at checkout.
    >
    > Black Friday only, while stock lasts.
  - **Título:** Buy 2, Get 1 FREE - Black Friday
  - **Descripción:** Free Worldwide Shipping
  - **Botón:** Shop Now → tourbillonbricks.com/collections/geneve
- Lo he dejado como un vídeo simple, igual que los demás anuncios 3x2. Al reemplazar el contenido se han quitado las mejoras automáticas que traía el duplicado, como el carrusel de productos del catálogo.
- No tiene errores de validación.

**Vista previa en Reels:** [ver anuncio](https://business.facebook.com/ads/api/preview_iframe.php?d=AQLUG93C2vpFFeO7ulG00IIMU0df9sYSU5FGPIxe0rYRckqNSlHXETHNCefkSCGbvZra0KiYi00E7aNoYmBq2zAUkQC07lDHfoBAhllzR1olai2IJVgDUZ_-87NUy9wJ3RuWMNzyx7UqN9Pm4M6SSJaOXfsfxZ1JfXJG-U8oYIRFtL7oAuRgVcNGI9oCGOqbMQpf5n2ftJkD6BjDsxjUrcAbuGkerFAI1zSCTUmLP15p2pECtAYymf5o_wujmPURWKVXJai2q7S1wfHf3g80Fqu58xMVMyLDZ08iCwRGHg4jUclrnBbPcNlVroTSfQ25aOAGCK8ahcmWpEQ3No4hTxCsHErp5gXxOtNRktqqe9SbJDVrjA7ngjZkJ6duhtTyn63OXTWg1x1KOeci6phrKda27WnzHEeiRCov7KC_o-c7kOXi2zdpGo4CyepwsgPsB_KJOLgcJYrGoj_MhxL1zhicTCIPWiOmrQbT0YQTvwoTjYHhinaDWE6DzyoqEqGTnEObMsTKa8PRBx1p7aURwgN-fUmnLEVsC-olJv3CDubJmrB003zdNPE1DFOLrRcBuUxSrr8B1L6oGdB3HDyU2FuJc5wZgSM4VLnnkpR1QUgCkxxTAQeX85KrVacDnD_4GdDbsLsAgu0mGKEgGCa1gi0-OV6Vdh4pY3qc3vfik-yAjIB1ASK50ns3q1e9X0zkiDfbeZibQcGs63RdOuOBbvhn7k3dNa0GfeAiGxPR7qB5_6bO2mfN6ucB4blph61H3jjMaVGRfvRzpP5iU42cHRCWVSpMWuiHobPH04D71ELraRJXEUtQL0AY07hdaW89posoLo2_GComigbOcY9L2XU8759g7360NiQ9VsTcPrNfaTa2cZJvfdhzxyzhwszABoUSLGmzuk8ArkP0S6t9Z2TzmpSb21uOt-uy_3LTjsn2RHwdsu_Qkg5KjTNvmZkjIoVvEB6eiErN5ClRNHoxIoTGz4p8qXwBfnZMl4oUi_LuFb_tPmKHQkYedM2LIu04cJ1Q_zt4gQwAi6zbRm_i3_OxiZ5clHvpM0Via1RBecGEAu0L9Vv3Hft4BXvHkMhqpt-Lz7pB-fQBWyyM9hpB_KBy5XWOLxEmjiVdpDFeRA32bx51X8DDXsDWcSWmLffTEDjfnvrYbUcEHEIrFV7EHmWlzZzwdaWT2cLyaB59-XI89I_qUeIIqlVogkDkNHBUE1IOiEzEIHCVpAFVTcI2nF0BtfdiF9JcITzaRufRlNuoHcwfvCHlHDrPnDVR6k22Vp8F3c5BgeFWUzAFR-lsYawC4PIGzOLLKzSoqx4p7t3jm0qMOqfvkxQmtpMbFyGHbMmuqTUyKyGRt3oDoFANbwXuBV7vTjWN8IpFr1nWT9Y_O2PdnNMbU_YMwRd37SSyc-pWRT-W8KxdHcVAeaorqq-_1ZKMRY_w3qr5GFbxS3wptZvg46YJAnsQtyAIo0312Oj6fWKRef2ti2cuF-eG2WKDtiDnwujdOxr7CbdVLOMDUe1zWIFbA0wbVixoCQKn3jR3v1ZtICeCm5bd7OVgJwn8LqTvtkdxKKGQPSbvJhVbekQamAduRoNIPuT0hhVNOk6aoLRiu0YrsnHwWPtJ1y5vuXELRixDapJX-kyqVjFlEzMArNkq6aXcjxR7-h8153s5Iij2ySxJzclD6M3f40qr90Cwr9ZAGm6EptBoZOyr_Q&t=AQIMMAQKGnL3NKZRPEA)

**⚠️ Ojo con la errata:** el vídeo que has subido es el mismo de antes (dura 20,18 s), así que al final sigue poniendo **"ONLY AVAIBLE AT"**. Si lo corriges, súbelo y lo cambio en el borrador. Si prefieres publicarlo así por tiempo, es decisión tuya.

**Para publicarlo:** abre el [borrador en Ads Manager](https://www.facebook.com/adsmanager/manage/ads/edit?act=2237541826642480&selected_ad_ids=120255327635140745&nav_source=ads_mcp&nav_entry_point=ads_mcp_text_draft_update) y pulsa **Publicar**. Si quieres, lo publico yo.

---

**ESTADO ACTUAL (23 nov 2026)**
- **Activo en Meta:** C1 Prospección (USA y UK), C2 Testing (UK), C3 Retargeting (USA+UK).
- **Nuevo:** `[3x2] BF27 - 4_v1` en borrador en C2 Testing UK, con el copy de "Buy 2, get 1 free". Pendiente de publicar y, si se puede, de corregir "AVAIBLE".
- **Google:** campaña PMax en pausa a la espera de que se aprueben los productos de USD y GBP. Revisión hoy, 23 nov.
- **Próximo paso:** hoy, publicar el anuncio. Miércoles 25: si lleva un ROAS de 2,26 o más, duplicarlo en C1 (USA y UK) antes del Black Friday del 27.


---

## Mili · 2026-11-23 06:36

corrigelo tu y dame el bueno


---

## Claude · 2026-11-23 06:38

_Herramientas: Bash, Read, Bash, Read, Bash, Bash, Bash, Read, Bash, Read, Bash, Read, SendUserFile_

Ya está corregido: te he enviado **BF27 - 4 (fix).mp4**.

**Qué he cambiado:**
- En el cierre (desde el segundo 18,45 hasta el final) ahora pone **"ONLY AVAILABLE AT"** en lugar de "ONLY AVAIBLE AT".
- He usado la misma posición, el mismo color crema, una tipografía muy parecida y el mismo ancho, para que no se note el cambio. La línea aparece en el mismo fotograma que antes y el texto erróneo ya no se ve en ningún momento.
- El resto del vídeo (imagen, audio, duración de 20,18 s y formato 1440×2560) no cambia.

**Para cambiarlo en el anuncio**, desde aquí no puedo subir vídeos directamente a Meta, así que:
1. Descarga **BF27 - 4 (fix).mp4**.
2. En el borrador `[3x2] BF27 - 4_v1` de Ads Manager, pulsa **Cambiar vídeo** y sube este archivo. El texto, el título y el enlace se mantienen.

También puedes subirlo a la biblioteca de la cuenta y decirme el nombre: yo lo cambio en el borrador y te aviso para que publiques.

---

**ESTADO ACTUAL (23 nov 2026)**
- **Activo en Meta:** C1 Prospección (USA y UK), C2 Testing (UK), C3 Retargeting (USA+UK).
- **Nuevo:** `[3x2] BF27 - 4_v1` en borrador en C2 Testing UK, con el copy de "Buy 2, get 1 free". El vídeo corregido está listo y falta cambiarlo en el borrador.
- **Google:** campaña PMax en pausa a la espera de que se aprueben los productos de USD y GBP. Revisión hoy, 23 nov.
- **Próximo paso:** hoy, cambiar el vídeo y publicar. Miércoles 25: si lleva un ROAS de 2,26 o más, duplicarlo en C1 (USA y UK) antes del Black Friday del 27.


---

## Mili · 2026-11-23 06:42

vale, ya está subido, asegúrate de que el destino sea la pagina principal de tourbillon y haya textos y demas


---

## Claude · 2026-11-23 06:43

_Herramientas: Meta_Ads__ads_get_ad_entities, Meta_Ads__ads_update_entity, Meta_Ads__ads_get_ad_videos, Meta_Ads__ads_get_ad_preview_

El anuncio ya está listo para publicar. Al cambiar el vídeo se había perdido el enlace: el botón había pasado a "See details" y no tenía URL, así que Meta no te habría dejado publicarlo. Ya está arreglado y el borrador no tiene errores.

**Cómo queda `[3x2] BF27 - 4_v1`:**
- **Vídeo:** *BF27 - 4 (fix).mp4* (20,18 s, ya procesado), la versión con "ONLY AVAILABLE AT".
- **Destino:** **https://tourbillonbricks.com/**, la página principal.
- **Botón:** Shop Now.
- **Texto principal:**
  > Buy 2, get the 3rd FREE.
  >
  > Start your watch collection for less, or keep one and gift two to the watch lovers in your life. Your free piece is added automatically at checkout.
  >
  > Black Friday only, while stock lasts.
- **Título:** Buy 2, Get 1 FREE - Black Friday
- **Descripción:** Free Worldwide Shipping
- **Ubicación:** C2 · TESTING → UK | ABIERTO | TEST
- **Página e Instagram:** los de Tourbillon Bricks.

**Vista previa en Reels:** [ver anuncio](https://business.facebook.com/ads/api/preview_iframe.php?d=AQIMquIlO08WezGTzUyHLXhPgd1oPMj7pV7lsfO4Z9d70ozUKQ43e7CwE9KCggAVNaFu_D93Jg4z5zDRp7_83EQ6NY6-fIAhy1ED2Ol_2pZZQw1gHGCjqSSmXzUrKInMr7tDEeXTNLnXsCBuY34xWmqeYPnlGcewbDwjBHStOcAwoua-n7SMAZXudwwS2_edtg5WA-0_OedcFXYDUzbSVjSS5efrvKykK3SuRM_f83apDeHpqRt015WEv1nwovOjQNCZwV36WpC2Qbpx6Pw6I00NS1oRGVe83Y9tM1sg-3wEwju-zXOt8HaT4Ca7tb6XBgtdGVX_5ZX6ND89JR9nm895l-bzNimHKeNFJ20wVifQZe04LhHr2KzsJAI94RBKzBV_wr3Ojvj9O7pWkGILusRhvakqZT2FiJms4e2Og0rgOQfTZkNN40R5x780VnW4bY_XgHMHPy1JkPMGedZLjGRhFyMT6ciw_3A8IaLxMCicvV--3fZ_Qpij_cYSEieXqpcikDx1fETIBi2Lsk6u8Xqa5ySVjfMfe_monMPVBZbF134lGDqrclb8D1kFffK-tToytXbmeNzeQJrhcteeyYiXBBnATEx5FB6-EXY3m8dmz2SX4U2DU-4G6jzWOKRoYXRHqDykUT3M-PFbLiAfl05BylA1yD_CFe35AzCabkrzAXVEayFQTi6G9nV_iOiQJqUaSu11fwWZ9yTXHv4GzsoxBEl2i9mWKYhGoWkR7ZtkcySAJTnAKViYWw3n2mMr0rmUU627jDaBmzhZyTKhNbnxCeNU9-N3ZqHODVVJ0heHNloWb2kvmSXY4ZCThAMjOLNQrnJF8H0io6788gJXn2q-Zxz6LLq6tOzjjvGefY-fXY8uAvHyCUkMrGAjNWeZ8DLtju6Uf3O79QOu-DfUOJC1goH2Wd5pkCf7bl0BYBAXdfZv-E4ZD-WAz6Z7V2BGuZ4ZD5Z18-NLnRArCifQJC5zP6iJIeUsa5LLjtFpovpYUd9W0biq9Qlp7jEb-3IBWoJpuB5EE4fQwncbiwo36PaFNPF6Q3x2ltJBvfH-17yJ7_WFmb_gK7e1wb2iLmnhqzyKQWx3N7HDU5fVizEIKyCOmeElf06uemUXkFLZmqAgft-LwJh0ZGxln4lwquqiKlf7C1ukuaAnuGRlICHsHnEw51Tgv9eKO9W3oqA9c2uAKozFoqCw3btAWqeJCLBIxDGGPeKTDdTsDDufhU4TOmZlnqbWZ8kBI8hLsF5EkNYCBCN3NugXyJ6cChlqDSCYoc7NM7soEhOps3uKsxQ3bWohSjPkqxu07R8ADG93Y5Kn8WPHH0DZ1qHFATG8g4ahc4py1QmhseWJVEJaFuIOcOuj8ZDpSNw7_dCsdt8aE4qtzOn-pL-4CSb8dvA0xov78nx-ltKg74Zu2hfTSdy1bQcxU6wj5NXLjHVKzi8GWNdnGdjlxYcULXLbu8az2mJGMicQjHi8tnO3Hlr9ZM1A-RY1_wHA7D9-Z3bwsYYi0XdOEa5tjNJ12zk0MEQQYLdkxf3CS5wQcKMy7W-h4nlhlHG9Bsm6AszMxWELUhfRFF7wle9PdIfnNra6KcjkNkxdCpUYwEQaBp9eezEF7yMD8zLzfC7SC0btxbuwgsFBEm_p-qui9Vp_3ZPKulx9wz8BalJSprcz_wq6KWAvHNvkZjMZ&t=AQKBhU1G6nvkeveSe5Y)

Un detalle: los otros anuncios 3x2 llevan a la colección **/collections/geneve** y este a la página principal, como pediste. Así podremos comparar qué destino convierte mejor.

**Para publicarlo:** [abrir el borrador en Ads Manager](https://www.facebook.com/adsmanager/manage/ads/edit?act=2237541826642480&selected_ad_ids=120255327635140745&nav_source=ads_mcp&nav_entry_point=ads_mcp_text_draft_update) y pulsar **Publicar**.

---

**ESTADO ACTUAL (23 nov 2026)**
- **Activo en Meta:** C1 Prospección (USA y UK), C2 Testing (UK), C3 Retargeting (USA+UK).
- **Nuevo:** `[3x2] BF27 - 4_v1` en C2 Testing UK, listo para publicar: vídeo corregido, copy de "Buy 2, get 1 free" y destino en la página principal.
- **Google:** campaña PMax en pausa a la espera de que se aprueben los productos de USD y GBP. Revisión hoy, 23 nov.
- **Próximo paso:** hoy, publicar. Miércoles 25: si lleva un ROAS de 2,26 o más, duplicarlo en C1 (USA y UK) antes del Black Friday del 27.


---

## Mili · 2026-11-23 06:43

Mira a ver si en Google nos han aprobado.


---

## Claude · 2026-11-23 06:44

_Herramientas: remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch_

Todavía no. Desde ayer no ha cambiado nada en Merchant Center:

- **Productos:** 792 en total, 0 aprobados, 792 "limitados", 0 rechazados.
- **Productos de USD y GBP** (los que necesita la campaña de USA y UK): siguen en **"Pending initial review"**, que limita la visibilidad en USA, UK y Emiratos.
- **Cuenta:** sin problemas ("No issues for you to fix"), así que no hay nada que corregir por nuestra parte. Es esperar a que Google termine la revisión.
- El aviso de "Mismatched currency" sigue saliendo por los feeds de otras monedas de Shopify. No bloquea nada.

La campaña **BFCM26 | PMax | USA+UK** sigue en pausa, como debe estar.

Lo que haría hoy: quedan 4 días para el Black Friday y la revisión inicial puede tardar varios días más. **Contactaría hoy con el soporte de Merchant Center** para pedirles que agilicen la revisión de los productos de USD y GBP por el Black Friday. La cuenta de Ads ya no está suspendida, así que debería dejarte abrir chat o llamada. Si quieres, te preparo el texto para el soporte.

---

**ESTADO ACTUAL (23 nov 2026)**
- **Meta:** C1, C2 y C3 activas. `[3x2] BF27 - 4_v1` listo en borrador en C2 Testing UK, pendiente de publicar.
- **Google:** PMax en pausa. Los productos de USD y GBP siguen en "Pending initial review" (0 aprobados). La cuenta no tiene problemas.
- **Decisión:** no reactivar la PMax hasta que los productos estén aprobados.
- **Próximo paso:** hoy, publicar el anuncio de Meta y contactar con el soporte de Merchant Center para agilizar la revisión. Martes 24: volver a revisar los productos. Miércoles 25: decidir si el 3x2 nuevo pasa a C1.


---

## Mili · 2026-11-23 16:43

Necesito escribirle un mensaje a Javi, que es el editor de Tourbillon Bricks, cuáles han funcionado mejor. Y pon los títulos que están en Drive, ¿vale? Para que él pueda saber cuáles son.


---

## Claude · 2026-11-23 16:44

Voy a sacar el rendimiento real de cada anuncio y emparejarlo con los nombres de los vídeos en Drive.

_Herramientas: Meta_Ads__ads_get_ad_entities, ToolSearch, Bash, Meta_Ads__ads_get_creatives, Meta_Ads__ads_get_ad_videos, Google_Drive__search_files, Google_Drive__search_files_

Aquí tienes el mensaje para Javi, listo para copiar. Los datos son de Meta del 1 al 23 de noviembre, sumando cada vídeo en todas las campañas donde se ha usado. Los nombres son los de los archivos en Drive.

---

> Hola Javi! Te paso cómo están funcionando los vídeos de Tourbillon en Meta este mes, para que sepas por dónde tirar en las próximas piezas 👇
>
> ✅ **Los que mejor funcionan**
>
> 1. **BF VENTA 4(1).mp4**: el mejor. 1.844 € invertidos, 37 ventas y un ROAS de 2,55 (cada venta nos cuesta unos 50 €). Funciona tanto con gente nueva como con quien ya conoce la marca.
> 2. **BF VENTA 1.mp4**: el que más vende. 5.300 € invertidos, 94 ventas y un ROAS de 2,02. Es el que más volumen aguanta.
> 3. **BF VENTA 5(2).mp4**: va bien. 533 €, 10 ventas y un ROAS de 2,05.
>
> 👀 **Prometedor:** el vídeo de **"The Pieces ➔ The Whole"** con la oferta 3x2 lleva un ROAS de 3,34 (100 €, 3 ventas). Todavía es poco gasto, pero pinta bien.
>
> ❌ **Los que no han funcionado**
> - **BF VENTA 2(1).mp4**: 1.288 € y un ROAS de 1,20.
> - **BF TB 5.mp4**: 286 € y un ROAS de 1,04.
> - **vid_13_oct26 (Programado 20-11-2026).mp4**: 252 € y un ROAS de 0,77.
> - **BF27 - 1 efectos.mp4**: 178 € y ninguna venta.
>
> ➖ **A medias:** **vid_10_oct26 (Programado 14-11-2026).mp4**, con 323 € y un ROAS de 1,66.
>
> ⏳ **Aún sin datos suficientes:** BF27 - 2 lento y BF27 - 4, que acaban de empezar.
>
> Para que te hagas una idea, el mínimo que buscamos es un ROAS de 2,26. Si puedes, haznos variaciones de **BF VENTA 4** y **BF VENTA 1** (otros ganchos al principio o el mismo vídeo con la oferta 3x2). Es lo que mejor está funcionando de cara al Black Friday. Gracias crack! 🙌

---

Dos cosas antes de enviarlo:
- **"The Pieces ➔ The Whole"**: en Meta el archivo se llama *"The Pieces ➔ The Whole (Programado 29-10-2026).mp4"*, pero no lo he encontrado en Drive con ese nombre. Si Javi lo tiene con otro nombre, cámbialo en el mensaje.
- **ROLEX COLLAB** (942 €, 19 ventas, ROAS de 1,93) lo he dejado fuera porque sus vídeos no tienen nombre en Meta y no sé cuál es en Drive. Si sabes cuál es, lo añado.


---

## Mili · 2026-11-24 07:20

_Archivo: BF 27 - 5.mp4_

Hemos hecho una segunda versión del 5 porque creemos que puede ser ganadora. Si lo crees conveniente, desactiva y activa este y desactiva el que crees que va a funcionar peor, ¿vale? Y de paso haz la revisión de tu revisión, que ayer no fue un buen día.


---

## Claude · 2026-11-24 07:22

Voy a revisar el vídeo nuevo, analizar cómo fue ayer y los últimos días por anuncio, y con eso decidir qué entra y qué sale.

_Herramientas: Bash, Meta_Ads__ads_get_ad_entities, Read, Meta_Ads__ads_get_ad_entities, Meta_Ads__ads_get_ad_entities, Bash, Bash, Read, Meta_Ads__ads_create_upload_url, SendUserFile, Meta_Ads__ads_creative_upload_media_

He revisado el vídeo nuevo y los datos de los últimos 4 días por anuncio. Ayer fue malo de verdad, pero no por el motivo que parece.

## 1. Revisión de ayer (23 nov)

| Campaña | Gasto | Compras | ROAS ayer | ROAS 20–23 nov |
|---|---|---|---|---|
| C1 Prospección | 428 € | 2 | **0,38** | 1,79 |
| C2 Testing | 39 € | 1 | 2,27 | 2,55 |
| C3 Retargeting | 43 € | 1 | 1,92 | 3,03 |

**Qué pasó:** el problema estuvo casi todo en C1. El anuncio `[20] LOWEST PRICE B` (el vídeo de BF VENTA 4) se llevó **254 € entre USA y UK y solo trajo 2 ventas**. El día antes, ese mismo anuncio hizo un ROAS de 1,47 en USA y de 3,91 en UK. No ha dejado de funcionar de repente, el día fue irregular:
- Las ventas de ayer todavía pueden aparecer en los próximos días, porque Meta atribuye compras hasta 7 días después del clic. El 0,38 seguramente subirá algo.
- Es probable que mucha gente esté esperando al jueves (Black Friday) para comprar. Es habitual que los días justo antes caigan.

**Lo que sí es real:** en los últimos 4 días C1 está en un **ROAS de 1,79, por debajo del mínimo de 2,26**. Por anuncio:

| Anuncio C1 | 20–23 nov | Compras | ROAS |
|---|---|---|---|
| [20] LOWEST PRICE B · USA | 520 € | 9 | 1,87 |
| [20] LOWEST PRICE B · UK | 430 € | 7 | 1,96 |
| BF_VENTA_1 · UK | 267 € | 5 | 1,69 |
| BF_VENTA_1 · USA (ya en pausa) | 230 € | 4 | 1,53 |
| [3x2] THE PIECES · USA | 112 € | 3 | **2,99** |
| BF_VENTA_4 · UK | 61 € | 2 | **3,09** |
| BF_VENTA_4 · USA | 55 € | 1 | 1,30 |
| BF_VENTA_5 · USA + UK | 41 € | 0 | – |

Ningún anuncio supera los 90 € sin ventas, así que la regla de pausa no obliga a parar ninguno. Lo que mejor rinde (3x2 THE PIECES, BF_VENTA_4 UK y RT REMINDER en C3, con un ROAS de 3,31) recibe poco presupuesto. Meta lo está concentrando en LOWEST PRICE B.

## 2. El vídeo nuevo (BF27 - 5)

Es la versión nueva del guion "lowest price" de BF VENTA 5. Tenía **la misma errata al final ("ONLY AVAIBLE AT")**, así que la he corregido igual que la del 4: te he enviado **BF27 - 5 (fix).mp4**.

**Mi decisión:** lo pondría en **C1 Prospección (USA y UK)** en lugar del `BF_VENTA_5` actual, y pausaría ese. Es el que peor va a funcionar: en 4 días Meta solo le ha dado 41 € y ninguna venta, y además es la versión antigua del mismo guion. Así cambiamos el 5 por su versión nueva sin añadir más anuncios a C1.

**Para hacerlo necesito el vídeo en la cuenta.** Desde aquí no puedo subirlo directamente, así que te he abierto el cuadro de subida de Meta. Elige *BF27 - 5 (fix).mp4*, pulsa **Continue** y envía el mensaje. En cuanto lo reciba:
1. Creo `BF_VENTA_5_v2` en USA | ABIERTO y en UK | ABIERTO, con el mismo copy de "lowest price" que el 5.
2. Lo activo.
3. Pauso los dos `BF_VENTA_5` antiguos.

## 3. Propuestas (por impacto)
1. **Cambiar el 5 por su versión nueva** (lo de arriba, pendiente de que subas el vídeo).
2. **No tocar presupuestos hoy.** Con el retraso en la atribución y la gente esperando al jueves, recortar ahora sería reaccionar a un mal día. Lo vuelvo a mirar mañana con los datos de ayer ya completos.
3. **Si mañana LOWEST PRICE B sigue por debajo de 1,5**, pausarlo en el país donde vaya peor para que el presupuesto pase a 3x2 THE PIECES y a BF_VENTA_4.

---

**ESTADO ACTUAL (24 nov 2026)**
- **Activo:** C1 Prospección (USA y UK), C2 Testing (UK) y C3 Retargeting (USA+UK), con los mismos presupuestos. `[3x2] BF27 - 4_v1` ya está activo en C2 (8,5 € gastados y sin datos todavía).
- **Resultados 20–23 nov:** C1 con un ROAS de 1,79, C2 con 2,55 y C3 con 3,03. El 23 nov fue un mal día en C1 (ROAS de 0,38).
- **Decisión:** cambiar `BF_VENTA_5` por `BF27 - 5 (fix)` en C1, en cuanto esté subido el vídeo.
- **Próximo paso:** hoy, subir el vídeo y hacer el cambio. Miércoles 25: revisar con los datos completos, decidir sobre LOWEST PRICE B y decidir si el `[3x2] BF27 - 4` pasa a C1 antes del Black Friday del 27.


---

## Mili · 2026-11-24 07:23

Bueno, de momento, si te parece, no cambiamos nada. Si me dices que eso, que todo va bien.


---

## Claude · 2026-11-24 07:23

De acuerdo, hoy no tocamos nada. Pero no te puedo decir que todo vaya bien, porque no es del todo así:

- **C2 Testing y C3 Retargeting van bien**: en los últimos 4 días tienen un ROAS de 2,55 y 3,03, por encima del mínimo de 2,26.
- **C1 Prospección no llega**: está en un ROAS de 1,79, y es donde va la mayor parte del presupuesto. Ayer cayó a 0,38, sobre todo por LOWEST PRICE B.

Aun así, esperar hoy es razonable. Las ventas de ayer todavía pueden aparecer en los próximos días, y antes del Black Friday es normal que la gente espere al jueves para comprar. Lo que no haría es dejarlo pasar de mañana: si C1 sigue por debajo, hay que mover presupuesto hacia lo que sí funciona antes del 27.

El vídeo **BF27 - 5 (fix)** queda listo para cuando quieras meterlo.

---

**ESTADO ACTUAL (24 nov 2026)**
- **Activo:** C1 Prospección (USA y UK), C2 Testing (UK) y C3 Retargeting (USA+UK), sin cambios en presupuestos ni anuncios.
- **Resultados 20–23 nov:** C1 con un ROAS de 1,79 (por debajo del mínimo), C2 con 2,55 y C3 con 3,03.
- **Decisión:** hoy no se cambia nada. El vídeo BF27 - 5 corregido está preparado y sin subir.
- **Próximo paso:** miércoles 25, revisar C1 con los datos ya completos. Si sigue por debajo de 2,26, mover presupuesto hacia 3x2 THE PIECES y BF_VENTA_4, decidir si entra BF27 - 5 y decidir si el `[3x2] BF27 - 4` pasa a C1 antes del Black Friday del 27.


---

## Mili · 2026-11-25 07:09

mira a ver si ya podemos publicar google ads


---

## Claude · 2026-11-25 07:10

_Herramientas: remote-devices__Claude_Browser__browser_batch, remote-devices__Claude_Browser__browser_batch_

Todavía no se puede publicar. Las tres condiciones siguen sin cumplirse:

**1. Productos de USA y UK aprobados: ❌ no**
- Sigue igual que el lunes: 792 productos, 0 aprobados y 792 "limitados". Los productos de USD y GBP siguen en **"Pending initial review"** para USA, UK y Emiratos.
- La cuenta sigue sin problemas. Los clics gratuitos han subido de 26 a 126, así que los productos sí se muestran en otros países, pero no en USA ni en UK.

**2. Conversión de compra activa: ❌ no, y esto es preocupante**
- "Compra" sigue en **"Requiere atención" con 0 compras registradas**. Pero en la web sí ha habido ventas estos días (Meta ha atribuido varias desde el 20). Si hubo pedidos y Google no ha registrado ninguno, lo más probable es que **la medición de compras de Google no esté funcionando**, no que falte una venta. Merece la pena revisar en Shopify la app *Google & YouTube* → Conversiones, o hacer un pedido de prueba.

**3. Anuncios revisados: ⏳** no se revisarán hasta que se reactive la campaña.

**Mi recomendación:** con el Black Friday en dos días, lo único que puede acelerar esto es **contactar hoy con el soporte de Merchant Center**. La revisión inicial lleva ya varios días. Pide expresamente que revisen los productos de los feeds USD y GBP por el Black Friday y comenta lo de las conversiones de compra. Si quieres, te preparo el mensaje para el soporte.

---

**ESTADO ACTUAL (25 nov 2026)**
- **Google:** PMax `BFCM26 | PMax | USA+UK` en pausa y sin gasto. Los productos de USD y GBP siguen en "Pending initial review" (0 aprobados) y la conversión de compra está a 0, posiblemente porque no se están registrando las compras.
- **Meta:** sin cambios desde ayer. C1, C2 y C3 activas.
- **Decisión:** no reactivar la PMax hasta que los productos estén aprobados.
- **Próximo paso:** hoy, contactar con el soporte de Merchant Center y revisar la medición de compras en la app Google & YouTube de Shopify. También hacer hoy la revisión de C1 en Meta que quedó pendiente para el 25. Jueves 26: volver a comprobar los productos.
