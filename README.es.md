<div align="center">

# 🪰 Un mosco y una camioneta

### *una crisis existencial en 6 actos*

**Una historia interactiva tierna y brutal.** Estética kawaii pastel como caballo de Troya del abismo.
Avanzas cumpliendo retos — cada uno te hace *sentir* en las manos una etapa de la crisis.

<br>

[![three.js](https://img.shields.io/badge/three.js-r160-000000?style=flat-square&logo=three.js&logoColor=white)](https://threejs.org)
[![Web Audio](https://img.shields.io/badge/Web%20Audio-chiptune-df48ef?style=flat-square)](https://developer.mozilla.org/docs/Web/API/Web_Audio_API)
[![Sin build](https://img.shields.io/badge/build-ninguno-9984e8?style=flat-square)]()
[![Licencia: MIT](https://img.shields.io/badge/licencia-MIT-007aff?style=flat-square)](LICENSE)

<br>

**🌐 Léelo en tu idioma**

[English](README.md) · **Español** · [Português](README.pt.md) · [日本語](README.ja.md) · [Français](README.fr.md) · [中文](README.zh.md)

</div>

---

> *Un instante antes zumbaba. Un instante después: nada. El universo no parpadeó.*

Un mosco cruza una carretera sin razón. Una camioneta pasa. El mosco deja de existir.
Ese microsegundo — una muerte absoluta, absurda, sin testigos ni sentido — detona la
pregunta que todos llevamos dentro: **si esa vida no significó nada, ¿qué hace distinta la mía?**

Este proyecto *es* esa reflexión, convertida en juego. La ternura del arte carga el peso
para que el texto no tenga que gritar. **El contraste es la obra.**

---

## 🎭 Los seis actos

Cada reto encarna su idea *en la mecánica* — el sentido no se explica, se juega.

| # | Acto | Reto | La verdad que aterriza |
|:-:|------|------|------------------------|
| 0 | **El detonante** | Salva al mosco antes de que llegue la luz | Imposible por diseño. *«¿Y si tú fueras el mosco?»* |
| 1 | **La insignificancia** | Encuéntrate *a ti* entre cientos de puntos idénticos | *«Ninguno era especial. Tampoco tú. Y sin embargo, aquí sigues mirando.»* |
| 2 | **El absurdo** | Lleva la piedra a la cima (siempre vuelve a caer) | Camus: *«La lucha hacia las cumbres basta para llenar un corazón.»* |
| 3 | **El vértigo de la libertad** | Elige una puerta — las demás desaparecen para siempre | *«Cada sí es mil noes. Eso es vivir.»* |
| 4 | **Ser-para-la-muerte** | Mantenlo vivo (se apaga más rápido de lo que puedes sostener) | Heidegger: *«La muerte no es el enemigo. Es el marco.»* |
| 5 | **La revuelta** | Construye algo — deja tu marca | *«El sentido no se encuentra. Se fabrica.»* → **«Hay que imaginar al mosco feliz.»** |

---

## ✨ Características

- **Estética tierna-brutal** — blobs pastel flotantes, contornos cómic, cursor de manita, 3D cel-shaded.
- **Seis mecánicas interactivas** — cada acto es un mini-juego simbólico distinto.
- **Banda sonora chiptune adaptativa** — sintetizada en vivo en La menor. Un filtro pasa-bajos
  se cierra conforme desciendes: brillante al inicio, ahogado en *la muerte*, luminoso otra vez en *la revuelta*.
- **Diseño de sonido reactivo** — el **zap** del mosco, **risers** de tensión en cada transición
  y **SFX de selección aleatorios** para que nada se repita.
- **Cero build, cero assets, cero rastreo** — un único archivo HTML autocontenido.

## 🎮 Controles

| Entrada | Acción |
|---------|--------|
| **Clic / toque** | Avanzar · interactuar · elegir |
| **Arrastrar** | Empujar la piedra (Acto 2) |
| **M** | Silenciar / activar la música |
| **R** | Revivir — reiniciar desde el final |

## 🛠️ Tecnología

- **[three.js](https://threejs.org)** (r160) — cel-shading con `MeshToonMaterial`, contornos cómic por hull invertido.
- **Web Audio API** — un pequeño motor chiptune en vivo (osciladores, filtros, SFX procedurales). Sin archivos de audio.
- **JS + HTML/CSS vanilla** — una máquina de estados en un solo archivo. Sin framework, sin bundler.

## 🚀 Ejecutar en local

Sin paso de build. Cualquier servidor estático sirve:

```bash
git clone https://github.com/Jorge-Polanco-Roque/el-mosco.git
cd el-mosco
python3 -m http.server 8000
# abre http://localhost:8000
```

> La música arranca en tu primer clic (política de autoplay del navegador).

## 📁 Estructura del proyecto

```
el-mosco/
├── index.html          # ← la experiencia (6 actos, música, SFX)
├── demo/
│   └── toy-world.html  # el sandbox lúdico del que nació
├── docs/
│   └── CONCEPT.md       # documento de diseño artístico y técnico
└── README*.md           # esto, en 6 idiomas
```

## 🌱 Origen y créditos

- **Estilo visual** extraído por ingeniería inversa del maravilloso [ketakuma.com](https://ketakuma.com)
  con [skillui](https://www.npmjs.com/package/skillui) (extracción estática de tokens de diseño).
  Es una *reinterpretación del estilo*, no una copia de assets.
- **Filosofía** en los márgenes: Albert Camus (*El mito de Sísifo*), Martin Heidegger
  (*ser-para-la-muerte*), Søren Kierkegaard y Jean-Paul Sartre (el vértigo de la libertad).
- **Tipografía**: [Londrina Solid](https://fonts.google.com/specimen/Londrina+Solid).

## 📄 Licencia

[MIT](LICENSE) — haz algo con ello. De eso trata justamente el Acto 5.

<div align="center">
<br>

*El sentido no se encuentra. Se fabrica.*

**Hay que imaginar al mosco feliz — y a ti también.**

</div>
