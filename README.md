# IA do Zero (curso)

**Os primeiros pedidos de quem nunca usou IA, com o porquê de cada um.**
Curso INEMA.CLUB PRO no formato v5 (página única, dark editorial, público 40+ leigo), em 4 aulas curtas, companheiro do kit
[IA do Zero](https://inematds.github.io/ia-do-zero/guia/) (20 pedidos por situação + 10 dicas).

- Página: https://inematds.github.io/ia-do-zero-curso/
- Landing: `landing.html` · Curso: `curso.html` (trilha + 4 aulas como views, roteamento por hash)
- Capa: `capa/capa.png`

## As 4 aulas

1. **A IA responde ao que você diz, não ao que você quer** — as três partes de um pedido
2. **O chat na prática: quatro coisas que importam** — os botões, três versões, ajustar sem recomeçar
3. **Confie, mas confira** — número, prazo e promessa; nunca colar dado real
4. **O seu kit: cinco pedidos que são seus** — montar, testar e guardar o próprio kit

Tudo self-contained: `curso.html` + `assets/aula.css` + `assets/curso.js`. Abre em `file://`, sem build, sem backend.
Progresso e cartões ficam no `localStorage` do navegador (chave `iadozero-v5`).
