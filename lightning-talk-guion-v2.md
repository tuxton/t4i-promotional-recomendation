# Tech4Impact — Versión DEVS
## Guion completo · Público joven · 10 minutos

---

## ESTRATEGIA: Por qué esta versión gana con developers

### El diagnóstico de audiencia
Los developers jóvenes que buscan trabajo y aprenden sobre AI tienen tres motivadores concretos:
1. **"¿Esto es técnicamente interesante?"** — quieren ver arquitectura real, no slides de PowerPoint corporativo
2. **"¿Puedo replicarlo?"** — si entienden cómo está construido, la charla les da valor concreto
3. **"¿Quiero trabajar ahí?"** — están evaluando empleadores en tiempo real

La decisión de diseño más importante fue **correr el eje de negocio → ingeniería**. El CTS no les importa. El Two-Tower Model sí.

### La apuesta central
El recomendador de charlas que armamos no es solo un demo — es la charla siendo lo que predica. Mostramos un motor de recomendación *usando un motor de recomendación en vivo*. Eso es meta, es memorable, y es imposible de olvidar.

### Por qué el hook de MCP funciona
MCP es un término que muchos escucharon en 2025 pero pocos vieron en producción real. Abrir con "¿cuántos lo tienen corriendo en producción, sobre infra propia?" establece autoridad sin arrogancia. No es "somos los mejores" — es una pregunta que hace que la sala sienta la diferencia antes de que la expliquemos.

### Por qué los tres demos (Martín / Ana / Carlos)
La secuencia está diseñada para subir en sorpresa:
- Martín (positivo esperado) → la audiencia entiende el concepto
- Ana (positivo inesperado) → "nunca vio nada relevante y ahora sí"
- Carlos (negativo = la bomba) → nadie espera que la personalización sea NO mostrar nada

El tercer demo es el que la sala no olvida. Rompe el frame de "personalización = más cosas". Personalización también es proteger el catálogo de quien no lo merece.

### Por qué explicar el Two-Tower
Para developers, ver que NaranjaX construyó un Two-Tower Model — el mismo patrón de YouTube y Spotify — con dataset propio, sobre Snowflake, expuesto via MCP, es una señal de seniority técnico del equipo. No es aspiracional: es un lugar donde se hacen cosas del nivel de las big tech, pero en el contexto local.

### El cierre como invitación
No cierra con "gracias". Cierra con una invitación a trabajar ahí. Para la audiencia target, eso es más valioso que cualquier estadística.

---

## SLIDES — Descripción slide a slide

### Slide 1 — NEGRO / SILENCIO
**Qué hay:** Pantalla completamente negra. Nada.
**Por qué:** Gastón entra y habla antes de que aparezca el primer slide. El silencio y la pantalla negra generan tensión. La audiencia enfoca en él, no en la pantalla.

### Slide 2 — El hook de MCP
**Qué hay:** Fondo oscuro. Texto grande centrado:
> "¿Cuántos lo tienen corriendo en producción?"
Debajo, en pequeño: `Model Context Protocol`
**Por qué:** La pregunta queda visible mientras la audiencia procesa. Refuerza el gancho verbal.

### Slide 3 — La pantalla de promos genéricas
**Qué hay:** Screenshot de la app de NaranjaX con 6 promos genéricas. Sin texto. Quizás un sutil círculo rojo sobre las promos que nadie miraría.
**Por qué:** Una imagen vale más que explicar el problema. La audiencia lo reconoce inmediatamente — todos tienen apps financieras con el mismo problema.

### Slide 4 — MARTÍN.
**Qué hay:** Solo la palabra "MARTÍN." en tipografía grande, blanca, sobre fondo oscuro. Nada más.
**Por qué:** Técnica Takahashi. Una palabra fuerza a la audiencia a escuchar al speaker para entender el contexto. El slide no compite con la narrativa — la sirve.

### Slide 5 — ANA.
**Qué hay:** Solo "ANA." — misma tipografía.
**Por qué:** Igual. La audiencia ya entendió el patrón: cada nombre introduce una historia.

### Slide 6 — CARLOS.
**Qué hay:** Solo "CARLOS." — misma tipografía. Opcionalmente, en un tono levemente diferente (gris en vez de blanco) para anticipar que algo es distinto.
**Por qué:** La diferencia sutil prepara a la audiencia para que el demo sea distinto. Cuando dicen "Carlos no recibe nada", el gris cobra sentido retroactivo.

### Slide 7 — "No creamos promos. Las matcheamos."
**Qué hay:** Frase centrada, tipografía grande. Debajo en pequeño: "La promo ya existe. Lo que faltaba era saber a quién."
**Por qué:** Este es el insight central de la charla. Tiene que vivir solo en un slide para que se grabe. No compartir pantalla con arquitectura ni logos.

### Slide 8 — El diagrama Two-Tower
**Qué hay:** El diagrama de las dos torres (Torre de Usuario | Torre de Promo → Dot Product → Score). Limpio, sobre fondo oscuro. Sin bullets ni texto explicativo extra — solo las cajas y las flechas.
**Por qué:** Para developers este es el slide más valioso. Les da el vocabulario y la arquitectura. Tienen que poder fotografiarlo y entenderlo solos después.

### Slide 9 — El stack
**Qué hay:** Logos o nombres de tecnologías en tipografía grande, organizados en dos columnas:
```
Snowflake         AWS Lambda
DynamoDB          MCP / Khatu
Wiru (CI/CD)      Slack Bolt
```
Debajo, en tipografía pequeña: **"Todo construido acá adentro."**
**Por qué:** Para un dev junior esto es una lista de tecnologías que quiere aprender o que ya conoce y le genera respeto. El "todo acá adentro" es el diferencial frente a shops que compran SaaS.

### Slide 10 — Demo en vivo / Recomendador
**Qué hay:** El browser abierto con la app del recomendador de charlas (el que construimos). O una captura del QR que los asistentes ya escanearon.
**Por qué:** El demo tiene que ser visible para la sala. Si proyectan el recomendador en vivo, la pantalla tiene que mostrar el resultado de alguien real. El "antes vs después" con un nombre real de la audiencia es el momento más poderoso.

### Slide 11 — Tres palabras: Promos → Productos → Asistente
**Qué hay:** Las tres palabras conectadas por flechas. Nada más.
**Por qué:** La visión tiene que ser simple para ser memorable. Tres palabras que escalan. Un dev las puede repetir en una conversación después.

### Slide 12 — NEGRO / SILENCIO
**Qué hay:** Pantalla negra nuevamente.
**Por qué:** El cierre va de memoria, de frente, sin competencia visual. La última imagen que la audiencia ve es la cara del speaker, no un slide de "gracias".

---

## GUION COMPLETO — Minuto a minuto

---

### [00:00 — 00:30] HOOK
**Speaker: GASTÓN**
**Slide: negro**

*[Camina al centro. Pausa de 2 segundos. No saluda todavía.]*

> "¿Cuántos de ustedes escucharon hablar de MCP este año?"

*[Pausa. Mira la sala. Deja que levanten la mano.]*

> "¿Cuántos lo tienen corriendo en producción, integrado a un motor de recomendación propio, sobre infra propia?"

*[Pausa más larga. Silencio.]*

> "Nosotros sí. Diez minutos."

*[Slide 2 aparece.]*

---

**DECISIÓN DE DIRECCIÓN:** No agradecer al evento. No presentarse con cargo y apellido. Entrar directo. Los primeros 30 segundos definen si la sala decide prestar atención o no. Un "buenas tardes, soy Gastón Duarte, IT Director de NaranjaX" desperdicia esos 30 segundos.

---

### [00:30 — 01:30] EL PROBLEMA
**Speaker: GASTÓN**
**Slide: screenshot de promos genéricas**

> "Esto es lo que ve hoy la mayoría de los usuarios de NaranjaX cuando abren la app. Seis promos. Ninguna diseñada para ellos."

> "El problema no es de UX. El problema es de sistema. Tenemos datos — consumos, transacciones, geolocalización, historial. Lo que no teníamos era la capa que conecta esa data con la oferta correcta."

> "Y peor: le estábamos dando beneficios a clientes que no los merecían. Morosos. Clientes que no nos rendían. Cada promo mal asignada es CTS puro. El modelo anterior no discriminaba. Regalaba."

> "Eso es lo que rompimos."

---

**DECISIÓN DE DIRECCIÓN:** Una sola imagen, sin texto explicativo. El screenshot hace el trabajo. Para devs, ver la pantalla de la app es suficiente — entienden el problema instantáneamente. No necesitan bullets.

---

### [01:30 — 02:30] QUÉ ES MCP
**Speaker: GASTÓN**
**Slide: diagrama de 3 cajas (App/Bot → MCP/Khatu → Motor/Snowflake)**

> "Antes de contarles cómo lo resolvimos, necesito que entendamos una pieza que para mí cambió todo."

> "MCP — Model Context Protocol — es un estándar abierto que le permite a un modelo de lenguaje hablar con herramientas externas de forma estructurada. En vez de hardcodear cada integración, definís un protocolo y el LLM sabe cómo usarlo."

> "Nosotros corremos el MCP sobre Khatu — nuestra plataforma de GenAI services. Lo que hace es exponer el motor de recomendación como una herramienta consumible desde cualquier canal."

> "Una sola capa de inteligencia. Muchos canales. Sin duplicar lógica. Sin vendor lock-in."

*[Pausa de un segundo.]*

> "Ese es el insight de arquitectura. Ahora déjenme mostrarles qué produce."

---

**DECISIÓN DE DIRECCIÓN:** Esta sección es un regalo para la audiencia. Muchos devs saben qué es MCP en abstracto pero no lo vieron aplicado a un motor de recomendación real. Posicionamos a NaranjaX como el lugar donde eso ya existe en producción.

---

### [02:30 — 04:30] LOS TRES DEMOS
**Speaker: GASTÓN**

#### Demo 1
**Slide: MARTÍN.**

> "Martín compra en supermercado los jueves. Siempre. Tres semanas seguidas. El motor detecta el patrón sobre Snowflake. Valida que Martín es un buen cliente — no moroso, nos rinde. Y el jueves a las 8 AM, antes de que salga de su casa, recibe reintegro en su super habitual."

> "La promo ya existía en nuestro catálogo. Lo que faltaba era saber que era para él. El motor hizo el match. La data decidió."

#### Demo 2
**Slide: ANA.**

> "Ana entra a la app cada semana. Nunca había una promo que le hiciera sentido — así que nunca la usaba. El motor detecta que frecuenta estaciones de servicio en ruta. Tenemos un convenio con esa red. El viernes a las 3 PM Ana ve por primera vez algo que la mueve a hacer click."

> "Primera conversión. No porque cambiamos la UI. Porque le hablamos a ella."

#### Demo 3
**Slide: CARLOS.**

> "Carlos tiene deuda. El motor lo sabe. Carlos no recibe nada."

*[Pausa larga. Dejar que baje.]*

> "Eso también es personalización."

---

**DECISIÓN DE DIRECCIÓN:** La secuencia sube en impacto. El tercero rompe la expectativa — la audiencia espera un tercer ejemplo positivo. El silencio después de "Carlos no recibe nada" es el momento más valioso de la charla. No llenarlo.

---

### [04:30 — 05:00] EL INSIGHT CENTRAL
**Speaker: GISELLE**
**Slide: "No creamos promos. Las matcheamos."**

> "Somos una fintech. No somos Facebook. No tenemos inventario infinito de cualquier cosa. Nuestro valor está en nuestra red de comercios — la adquirencia, los convenios open loop."

> "El motor no inventa. Conecta. La promo ya existe. El cliente ya existe. La pregunta era: ¿quién merece cuál?"

> "Eso es lo que resolvimos."

---

**DECISIÓN DE DIRECCIÓN:** Giselle toma la posta en este momento porque es la arquitecta del modelo. Su voz en el insight central establece la autoridad técnica del equipo de Data. No es "el IT Director explicando lo que hizo Data" — es Data explicándolo directamente.

---

### [05:00 — 06:30] EL MODELO — TWO-TOWER
**Speaker: GISELLE**
**Slide: diagrama Two-Tower**

> "Quiero mostrarles cómo está construido el motor. Porque la arquitectura tiene algo elegante que vale la pena entender."

> "Se llama Two-Tower Model. Lo usan YouTube para recomendar videos, Spotify para canciones. Es el gold standard para recomendaciones a escala."

> "La idea: entrenás dos redes neuronales en paralelo. Una aprende a representar usuarios — consume historial transaccional, comportamiento en app, score crediticio. La otra aprende a representar promos — categoría, comercio, condiciones, la red de adquirencia."

> "Cada red produce un embedding: un vector de números — 64 dimensiones — que es la huella digital de ese usuario o de esa promo en un espacio matemático."

> "Las dos redes están entrenadas para proyectar al mismo espacio. Si el vector de un usuario y el de una promo son similares — si su dot product es alto — esa promo es relevante para ese usuario. No por reglas. Por geometría aprendida de millones de transacciones reales."

> "Y la magia operacional: los embeddings de las promos se pre-computan offline en Snowflake. Cuando un usuario abre la app, lo único que calculás en tiempo real es su vector — y buscás las promos más cercanas. Nearest neighbor search. Milisegundos."

> "Ahí es donde entra el MCP: el resultado llega como tool call al modelo de lenguaje, que decide qué mostrar, cuándo, en qué canal."

---

**DECISIÓN DE DIRECCIÓN:** Esta es la sección más larga y la que más le importa a la audiencia developer. Giselle puede ir al diagrama, señalar las cajas, hacer la explicación más visual. No apurarse acá — es el centro técnico de la charla.

---

### [06:30 — 07:30] STACK + BUILT IN-HOUSE
**Speaker: GASTÓN**
**Slide: stack**

> "El motor de recomendación corre sobre Snowflake — desarrollo 100% del equipo de Data de NaranjaX. Giselle y su equipo construyeron el modelo desde cero."

> "Desde IT armamos el MCP sobre Khatu para que ese motor llegue a cualquier canal sin que cada equipo tenga que integrarse por separado."

> "AWS Lambdas para cómputo. DynamoDB para estado y caché. CI/CD con Wiru. Todo nuestro."

*[Señalar a Giselle]*

> "Giselle construyó el cerebro. Nosotros construimos los nervios."

---

**DECISIÓN DE DIRECCIÓN:** La frase "Giselle construyó el cerebro, nosotros construimos los nervios" es la que mejor resume la colaboración Data+IT. Es concreta, memorable, y muestra que hay dos equipos distintos trabajando juntos — algo raro y valorado.

---

### [07:30 — 08:30] EL DEMO EN VIVO + DÓNDE ESTAMOS
**Speaker: GASTÓN**
**Slide: el recomendador de charlas en pantalla**

> "Les prometí que iban a ver el motor funcionando. Pero no con datos de prueba."

> "Antes de empezar le pedimos a algunos de ustedes que dejaran su perfil. Lo que voy a hacer ahora es pasarle su perfil al sistema — en vivo — y ver qué charla del evento les recomienda."

*[Demo en vivo con 2-3 perfiles de la audiencia. Mostrar el resultado. Señalar los scores y las razones.]*

> "Mismo evento. Mismas charlas. Distinta persona — distinta recomendación. Eso es exactamente lo que hacemos con las promos de NaranjaX."

*[Slide: timeline de roadmap]*

> "Dogfooding: hecho. Family & Friends: hecho. Producción: viene."

> "El Slack bot ya corre hoy. Si alguno quiere verlo después de la charla, con gusto."

---

**DECISIÓN DE DIRECCIÓN:** El demo en vivo es el momento de mayor riesgo y mayor recompensa. Si funciona bien, la audiencia sale hablando de eso. Tener 3-4 perfiles pre-cargados como backup por si el wifi falla.

---

### [08:30 — 10:00] VISIÓN + CIERRE
**Speaker: GISELLE [visión] → GASTÓN [cierre]**
**Slide: "Promos → Productos → Asistente" → negro**

**GISELLE:**
> "Esto hoy es promos. Pero el recommendation engine + MCP que construimos no es para promos."

> "Es la base para recomendar productos financieros en el momento de mayor propensión. Seguros contextuales cuando el cliente está más expuesto. Un asistente conversacional que tiene contexto real de quién sos como cliente de NaranjaX."

> "La plataforma ya existe. Lo que viene es qué más construimos sobre ella."

*[Transición a Gastón. Slides apagados.]*

**GASTÓN:**
*[De frente. Sin mirar pantalla.]*

> "Si están en sus primeros años como devs y están pensando dónde quieren laburar: busquen un lugar donde te dejen construir cosas propias. Donde el equipo de Data y el equipo de IT se sienten juntos a resolver un problema real con tecnología que todavía muy poca gente está usando en producción."

> "Eso es lo que estamos haciendo en NaranjaX. Y esto que les mostramos hoy es solo el primer layer."

*[Pausa de tres segundos. Sin sonrisa forzada.]*

> "Gracias."

---

**DECISIÓN DE DIRECCIÓN:** Giselle cierra la visión técnica. Gastón cierra el mensaje humano. La división no es arbitraria — el último que habla es el que la audiencia recuerda. Gastón cierra con la invitación a trabajar ahí, que es el mensaje más importante para esta audiencia.

El "gracias" sin agradecer al evento y sin pedir aplausos es intencional. Para. La audiencia aplaude sola. Es más poderoso.

---

## CHECKLIST PRE-CHARLA

- [ ] Demo en vivo testeado con wifi del venue
- [ ] 4 perfiles de backup pre-cargados offline
- [ ] QR del recomendador visible en el slide de demo
- [ ] Transiciones Giselle↔Gastón ensayadas (sin "le doy la palabra a...")
- [ ] Cierre de Gastón de memoria — sin mirar pantalla
- [ ] Demo de Carlos ensayado con la pausa
- [ ] Cronometrado completo: 9:30 o menos
