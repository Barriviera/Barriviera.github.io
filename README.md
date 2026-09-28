# Portfólio: Pedro Barriviera

Site-currículo interativo (HTML/CSS/JS puro, um arquivo só), PT/EN.

## Estrutura
```
index.html                        ← site inteiro (dados no topo do <script>)
curriculo-pedro-barriviera.pdf    ← botão "Baixar currículo"
img/                              ← fotos dos projetos
```

## Projetos no site
| Projeto | Fotos (img/) |
|---|---|
| Coletor de esporos (PFC) | `coletor-*.jpg` (10) |
| Fenotipagem RGB + profundidade | `feno-*.jpg` (6) |
| Microscópio automatizado (Squid) | `micro-*.jpg` (4) |
| PCB unificada RS-422/485 → UART | `pcb-1.jpg` · **faltam** `pcb-layout.jpg` e `pcb-layout-2.jpg` |
| Logger de tensão e corrente | `logger-*.jpg` + gráfico do coletor |
| JobGrid | `jobgrid-1.jpg`, `jobgrid-2.jpg` |
| AQUA VIGIA (SESI) | `aqua-*.jpg` (5) |
| Camiseta háptica (SESI) | `camisa-*.jpg` (3) |
| Estação de celulares (SESI) | `celulares-*.jpg` (3) · pode adicionar fotos da parte elétrica |
| Foto de perfil | **falta** `perfil.jpg` (quadrada, ~400×400) |

Nomes de empresa foram removidos do texto e borrados nas fotos (marca d'água e logos).
Foto sem arquivo → aparece um placeholder com o nome esperado.

## Editar projetos
No `index.html`, procure `const PROJECTS = [`. Cada projeto tem título, resumo, descrição, `stats` (números de destaque), "o que eu fiz", tags, fotos e links, em `pt` e `en`.
- `draft:true` mostra o selo **✎ a preencher**. Apague quando completar.
- `tags` ligam o projeto aos chips de Competências (ids em `const SKILLS`).

## Publicar no GitHub Pages
1. Crie um repositório **`Barriviera.github.io`** (fica em `https://barriviera.github.io/`).
2. Suba estes arquivos na raiz.
3. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
