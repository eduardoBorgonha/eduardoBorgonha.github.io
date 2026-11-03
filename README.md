# eduardoborgonha.github.io

Meu portfolio: https://eduardoborgonha.github.io (EN) · https://eduardoborgonha.github.io/fr/ (FR)

## Estrutura

```
index.html        → página em inglês (todo o conteúdo)
fr/index.html     → página em francês (mesma estrutura, texto traduzido)
style.css         → visual (cores, fontes, layout) — compartilhado pelas duas
assets/           → foto, CV em PDF, imagens dos projetos
```

## Como editar

- **Texto:** edite `index.html` e depois a mesma parte em `fr/index.html`.
  Cada seção começa com um comentário (`<!-- PROJECTS -->`, `<!-- CONTACT -->`...) para facilitar achar.
- **Novo projeto:** copie um bloco `<article class="card"> ... </article>` inteiro, cole abaixo e troque o texto.
  Para destacar um projeto, use `class="card featured"`.
- **Cores:** estão no topo do `style.css`, em `:root` (modo claro) e logo abaixo (modo escuro).
- **Trocar o CV:** substitua `assets/cv-eduardo-fr.pdf` por um arquivo com o mesmo nome, ou adicione outro e atualize o link no botão "CV".

## Ver antes de publicar

No VS Code, instale a extensão **Live Server**, clique com o botão direito em `index.html` → **Open with Live Server**.
O navegador atualiza sozinho a cada vez que você salva.

## Publicar

```
git add .
git commit -m "descreva a mudança"
git push
```

Em 1–2 minutos o site está atualizado.
