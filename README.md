# Brendagnasc.github.io

Site pessoal de Brenda Gabrielle Alves Nascimento, estudante de Ciência da Computação na UFOP.

**Site:** https://brendagnasc.github.io/

## 🎮 Jogos

Todos os jogos estão reunidos em **https://brendagnasc.github.io/jogos/** e rodam direto no navegador.

| Jogo | Demo | Código | Tecnologias |
|---|---|---|---|
| 📸 Puzzle Cam | [Jogar](https://brendagnasc.github.io/Puzzle_Cam/) | [Puzzle_Cam](https://github.com/Brendagnasc/Puzzle_Cam) | JavaScript, MediaPipe Hands, Canvas |
| 🧩 Quebra-Cabeças | [Jogar](https://brendagnasc.github.io/quebra-cabecas/) | [quebra-cabecas](https://github.com/Brendagnasc/quebra-cabecas) | C, GTK3, WebAssembly |
| 🔢 2048 | [Jogar](https://brendagnasc.github.io/jogo-2048/) | [jogo-2048](https://github.com/Brendagnasc/jogo-2048) | C++17, SDL2, WebAssembly |

Os jogos em C e C++ usam o código original, compilado para WebAssembly com
Emscripten. Cada repositório publica a própria demo pelo GitHub Pages.

### Adicionar um jogo ao menu

Acrescente um item na lista `JOGOS` em [`jogos/index.html`](jogos/index.html):

```js
{
  nome: "Nome do jogo",
  descricao: "Uma ou duas frases sobre o jogo.",
  capa: "🎲",
  cor: "linear-gradient(135deg, #1f2937, #111827)",
  tags: ["Linguagem", "Biblioteca"],
  demo: "https://brendagnasc.github.io/repositorio/",
  codigo: "https://github.com/Brendagnasc/repositorio"
}
```

## Estrutura

- `index.html` — página principal (currículo), com HTML e Tailwind CSS
- `jogos/index.html` — menu de jogos

## Contato

- GitHub: [@Brendagnasc](https://github.com/Brendagnasc)
- LinkedIn: [brenda-gabrielle](https://linkedin.com/in/brenda-gabrielle-85242a416)
