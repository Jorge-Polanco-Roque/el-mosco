# ぷかぷか / EL MOSCO — una crisis existencial en 6 actos

> Experiencia web narrativa e interactiva. Estética adorable (Ketakuma: blobs
> pastel, Londrina Solid, cursor de manita, contornos cómic) al servicio de un
> texto existencial y descarnado. **El contraste ES la obra.** Lo tierno dice lo
> insoportable. Nadie sospecha del peluche que te susurra que vas a morir.

---

## Detonante

Un mosco cruza una carretera sin razón. Una camioneta pasa. El mosco deja de
existir. El universo no parpadea. Ese microsegundo — una muerte absoluta,
absurda, sin testigos ni sentido — detona en quien mira la pregunta que
llevaba dentro: *si esa vida no significó nada, ¿qué hace distinta la mía?*

La página **es** esa reflexión, convertida en juego. Avanzas cumpliendo retos.
Cada reto encarna, mecánicamente, una etapa de la crisis. La mecánica no ilustra
la idea: la *hace sentir en el cuerpo*.

---

## Los 6 actos (reto → verdad)

**ACTO 0 · EL DETONANTE — la carretera**
Un punto diminuto (el mosco) vaga por una línea-carretera. Una luz cálida enorme
(la camioneta) se acerca.
- Reto: `SÁLVALO` — toca al mosco antes de que llegue la luz.
- Es imposible: errático, la luz siempre gana. 3 intentos.
- Verdad: *"Un instante antes zumbaba. Un instante después: nada. ¿Y si tú fueras el mosco?"*

**ACTO 1 · LA INSIGNIFICANCIA — el enjambre**
La cámara se aleja; la carretera es un punto. Cientos de puntos idénticos, cada
uno seguro de ser el centro.
- Reto: `ENCUÉNTRATE` — toca el punto que eres tú.
- Cualquiera que toques: "ese no eras tú". Todos iguales.
- Verdad: *"Ninguno era especial. Tampoco tú. Y sin embargo, aquí sigues mirando."*

**ACTO 2 · EL ABSURDO — Sísifo**
Un blob quiere caer al valle. Lo empujas cuesta arriba; la gravedad lo devuelve.
- Reto: `LLÉVALO A LA CIMA` — sostén el esfuerzo pese a la caída.
- Se puede "ganar" solo con voluntad terca; ese es el truco.
- Verdad (Camus): *"La lucha hacia las cumbres basta para llenar un corazón."*

**ACTO 3 · EL VÉRTIGO DE LA LIBERTAD — la elección**
Varias puertas-blob brillan. Elegir una desvanece las demás para siempre.
- Reto: `ELIGE` — solo una. Las otras no vuelven.
- Verdad: *"Cada sí es mil noes. No sabrás qué había detrás de las otras. Eso es vivir."*

**ACTO 4 · SER-PARA-LA-MUERTE — el latido**
Un blob (tú) se apaga solo, cada vez más rápido. Tocarlo lo reaviva.
- Reto: `MANTENLO VIVO` — es insostenible por diseño.
- Verdad (Heidegger): *"La muerte no es el enemigo. Es el marco. Sin el borde, el dibujo no existe."*

**ACTO 5 · LA REVUELTA — crear sentido**
Vuelve el mundo-juguete, vacío. Ahora tú creas: cada toque nace un blob; se
conectan en una constelación tuya.
- Reto: `CONSTRUYE ALGO` — deja tu marca.
- Cierre: *"El sentido no se encuentra. Se fabrica."* →
  **"Hay que imaginar al mosco feliz."** — y a ti también.

---

## Tono de escritura
Segunda persona, íntimo, en voz baja. Frases cortas, golpe seco. Español con
acentos correctos. Nunca explica el chiste; deja el silencio. La ternura visual
carga el peso; el texto no necesita gritar.

## Estética (tokens de Ketakuma vía skillui)
- Fondo lavanda `#e9edf8` → vira a más frío/oscuro conforme cae la noche del ánimo.
- Pastel: `#faf56c #9984e8 #df48ef #b3d4fc #007aff #96aee6`, tinta `#272727`.
- Tipografía display **Londrina Solid**. Cursor de manita SVG. Contorno cómic
  (hull invertido `BackSide`). Cel-shading plano (`MeshToonMaterial`).

## Técnica
- Un solo archivo `existencia.html`, `three.js` vía importmap CDN (continuidad de estilo).
- Máquina de estados por acto: `enter() / update(dt) / onPointer()`. Un `<canvas>`,
  cámara fija. Capa HTML para narración (caption inferior) y banner de reto (superior).
- Helpers reutilizados del demo: `makeBlob()`, outline, cursor, paleta.
- Transición entre actos: fundido a lavanda. `R` para revivir desde el final.
- Fidelidad honesta: reinterpretación de estilo, no copia de assets de Ketakuma.

## Criterio de "hecho"
Se recorre de principio a fin, cada reto avanza, el texto aterriza, y el contraste
tierno/abismal se siente. Si el peluche no te deja un nudo en la garganta, faltó.
