<div align="center">

# 🪰 Um mosquito e uma caminhonete

### *uma crise existencial em 6 atos*

**[▶ Jogar online](https://jorge-polanco-roque.github.io/el-mosco/)**

**Uma história interativa fofa e brutal.** Estética kawaii pastel como cavalo de Troia do abismo.
Você avança cumprindo desafios — cada um faz você *sentir* nas mãos uma etapa da crise.

<br>

[![three.js](https://img.shields.io/badge/three.js-r160-000000?style=flat-square&logo=three.js&logoColor=white)](https://threejs.org)
[![Web Audio](https://img.shields.io/badge/Web%20Audio-chiptune-df48ef?style=flat-square)](https://developer.mozilla.org/docs/Web/API/Web_Audio_API)
[![Sem build](https://img.shields.io/badge/build-nenhum-9984e8?style=flat-square)]()
[![Licença: MIT](https://img.shields.io/badge/licença-MIT-007aff?style=flat-square)](LICENSE)

<br>

**🌐 Leia no seu idioma**

[English](README.md) · [Español](README.es.md) · **Português** · [日本語](README.ja.md) · [Français](README.fr.md) · [中文](README.zh.md)

</div>

---

> *Um instante antes zumbia. Um instante depois: nada. O universo não piscou.*

Um mosquito atravessa uma rodovia sem razão. Uma caminhonete passa. O mosquito deixa de existir.
Esse microssegundo — uma morte absoluta, absurda, sem testemunhas e sem sentido — detona a
pergunta que todos carregamos: **se aquela vida não significou nada, o que torna a minha diferente?**

Este projeto *é* essa reflexão, transformada em jogo. A ternura da arte carrega o peso
para que o texto não precise gritar. **O contraste é a obra.**

---

## 🎭 Os seis atos

Cada desafio encarna sua ideia *na mecânica* — o sentido não é explicado, é jogado.

| # | Ato | Desafio | A verdade que aterrissa |
|:-:|-----|---------|-------------------------|
| 0 | **O detonador** | Salve o mosquito antes que a luz chegue | Impossível por design. *«E se você fosse o mosquito?»* |
| 1 | **A insignificância** | Encontre *você* entre centenas de pontos idênticos | *«Nenhum era especial. Você também não. E, mesmo assim, aqui está você, ainda olhando.»* |
| 2 | **O absurdo** | Leve a pedra ao cume (ela sempre rola de volta) | Camus: *«A própria luta em direção aos cumes basta para encher um coração.»* |
| 3 | **A vertigem da liberdade** | Escolha uma porta — as outras desaparecem para sempre | *«Cada sim é mil nãos. É isso que é viver.»* |
| 4 | **Ser-para-a-morte** | Mantenha-o vivo (apaga mais rápido do que você consegue sustentar) | Heidegger: *«A morte não é o inimigo. É a moldura.»* |
| 5 | **A revolta** | Construa algo — deixe sua marca | *«O sentido não se encontra. Fabrica-se.»* → **«É preciso imaginar o mosquito feliz.»** |

---

## ✨ Recursos

- **Estética fofa-brutal** — blobs pastel flutuantes, contornos de quadrinhos, cursor de mãozinha, 3D cel-shaded.
- **Seis mecânicas interativas** — cada ato é um minijogo simbólico distinto.
- **Trilha chiptune adaptativa** — sintetizada ao vivo em Lá menor. Um filtro passa-baixa
  se fecha conforme você desce: brilhante no início, sufocado na *morte*, luminoso de novo na *revolta*.
- **Sound design reativo** — o **zap** do mosquito, **risers** de tensão em cada transição
  e **SFX de seleção aleatórios** para que nada se repita.
- **Zero build, zero assets, zero rastreamento** — um único arquivo HTML autocontido.

## 🎮 Controles

| Entrada | Ação |
|---------|------|
| **Clique / toque** | Avançar · interagir · escolher |
| **Arrastar** | Empurrar a pedra (Ato 2) |
| **M** | Silenciar / ativar a música |
| **R** | Reviver — recomeçar do fim |

## 🛠️ Tecnologia

- **[three.js](https://threejs.org)** (r160) — cel-shading com `MeshToonMaterial`, contornos de quadrinhos por hull invertido.
- **Web Audio API** — um pequeno motor chiptune ao vivo (osciladores, filtros, SFX procedurais). Sem arquivos de áudio.
- **JS + HTML/CSS vanilla** — uma máquina de estados em um único arquivo. Sem framework, sem bundler.

## 🚀 Executar localmente

Sem etapa de build. Qualquer servidor estático funciona:

```bash
git clone https://github.com/Jorge-Polanco-Roque/el-mosco.git
cd el-mosco
python3 -m http.server 8000
# abra http://localhost:8000
```

> A música começa no seu primeiro clique (política de autoplay do navegador).

## 📁 Estrutura do projeto

```
el-mosco/
├── index.html          # ← a experiência (6 atos, música, SFX)
├── demo/
│   └── toy-world.html  # o sandbox lúdico do qual nasceu
├── docs/
│   └── CONCEPT.md       # documento de design artístico e técnico
└── README*.md           # isto, em 6 idiomas
```

## 🌱 Origem e créditos

- **Estilo visual** obtido por engenharia reversa do maravilhoso [ketakuma.com](https://ketakuma.com)
  com [skillui](https://www.npmjs.com/package/skillui) (extração estática de tokens de design).
  É uma *reinterpretação de estilo*, não uma cópia de assets.
- **Filosofia** nas margens: Albert Camus (*O Mito de Sísifo*), Martin Heidegger
  (*ser-para-a-morte*), Søren Kierkegaard e Jean-Paul Sartre (a vertigem da liberdade).
- **Tipografia**: [Londrina Solid](https://fonts.google.com/specimen/Londrina+Solid).

## 📄 Licença

[MIT](LICENSE) — faça algo com isso. É justamente disso que trata o Ato 5.

<div align="center">
<br>

*O sentido não se encontra. Fabrica-se.*

**É preciso imaginar o mosquito feliz — e você também.**

</div>
