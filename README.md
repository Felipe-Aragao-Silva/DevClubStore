# 🛍️ DevClub Store

Uma landing page de e-commerce futurista com carrossel de produtos animado, construída com HTML, CSS e JavaScript puro.

![DevClub Store Preview](./img/preview.png)

---

## ✨ Funcionalidades

- **Carrossel automático** — troca de produto a cada 5 segundos
- **Navegação manual** — botões de seta para navegar entre os produtos
- **Animações de entrada** — cada elemento do slide entra com transição suave
- **Indicadores visuais** — número do slide atual e dots de navegação
- **Efeito pulse** — gradiente animado no fundo da página
- **Hover nos links** — underline animado no menu de navegação
- **Hover no botão** — gradiente muda suavemente ao passar o mouse

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estrutura da página |
| CSS3 | Estilização, animações e layout com Flexbox |
| JavaScript (ES6+) | Lógica do carrossel e manipulação do DOM |
| Google Fonts | Fontes *Montserrat* e *Orbitron* |

---

## 📁 Estrutura de Pastas

```
devclub-store/
├── index.html
├── style.css
├── script.js
└── img/
    ├── apple-watch.png
    ├── air-pods.png
    └── vision-pro.png
```

---

## 🎨 Conceitos de CSS Aplicados

- `box-sizing: border-box` — padding e borda incluídos na largura total
- `overflow: hidden` — desativa o scroll da página
- `position: fixed` — header sempre visível no topo
- `@keyframes` + `animation` — animação de pulse no fundo
- `::before` (pseudo-elemento) — efeito de hover no botão e underline no menu
- `transition` — suaviza todas as animações de entrada e hover
- `z-index` — controle de camadas entre os elementos
- `radial-gradient` + `linear-gradient` — fundos e botões com gradiente

---

## ⚙️ Conceitos de JavaScript Aplicados

- `const` vs `let` — variáveis constantes e mutáveis
- `querySelectorAll` — selecionar múltiplos elementos
- `classList.add / remove` — alternar classes CSS via JS
- `setInterval` — executa o avanço automático do carrossel
- `addEventListener` — escuta cliques nos botões de navegação
- `String.padStart` — formata o número do indicador como `01`, `02`, `03`

---

## 🚀 Produtos em Destaque

| # | Produto | Categoria |
|---|---------|-----------|
| 01 | Apple Watch Series 10 | Novo Lançamento |
| 02 | AirPods Max | Som Premium |
| 03 | Vision Pro | Alta Performance |

---

## 👨‍💻 Autor

Desenvolvido durante os estudos de **Front-End** na [DevClub](https://devclub.com.br).
