# Rebsversary 🖤

Página de aniversário emo para a Rebeca (29 anos): glitch, neon, chuva de 🖤, bolo para soprar,
Top 8 no estilo MySpace e personagens passeando pela tela (Sonic, Shadow, Tails, Gojo, Iggy, Zero Two, Katarina, LeBlanc, Ahri).

## Como abrir

Abra o `index.html` no navegador, ou publique pelo GitHub Pages (Settings → Pages → branch `main`, pasta `/`).

## Como personalizar

Tudo fica no objeto `CONFIG`, no fim do `index.html`:

- `nome`, `idade`, `mensagem`, `assinatura`
- `foto`: coloque `foto.jpg` na raiz
- `spotify` e `primeiraDe`: a playlist e o artista da primeira música
- `gifs`: GIFs sem fundo em `gifs/` ou links diretos (veja `gifs/LEIA-ME.txt`)

O player da página toca a playlist em ordem aleatória por um embed do Spotify invisível (iFrame API),
sempre começando por `CONFIG.primeiraDe`. As faixas e capas ficam na lista `FAIXAS`, logo abaixo do `CONFIG`.

`votacao.html` e `falas.html` servem para escolher GIFs, recados e falas e exportar um JSON.
