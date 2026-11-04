# eduardoborgonha.github.io

Meu portfolio: https://eduardoborgonha.github.io (EN) · https://eduardoborgonha.github.io/fr/ (FR)

## Estrutura

```
index.html        → página em inglês (todo o conteúdo)
fr/index.html     → página em francês (mesma estrutura, texto traduzido)
style.css         → visual (cores, fontes, layout), compartilhado pelas duas
assets/           → foto, CV em PDF, imagens dos projetos
```

## Como editar

- **Texto:** edite `index.html` e depois a mesma parte em `fr/index.html`.
  Cada seção começa com um comentário (`<!-- PROJECTS -->`, `<!-- CONTACT -->`...) para facilitar a busca.
- **Novo projeto:** copie um bloco `<article class="project"> ... </article>` inteiro, cole onde quiser na lista e troque o texto.
- **Nova experiência ou formação:** copie um `<li> ... </li>` dentro de `<ul class="entries">`.
- **Cores e fonte:** ficam no topo do `style.css`, em `:root`. A fonte (Archivo, do Google Fonts) é carregada no `<head>` de cada página.
- **Trocar o CV:** substitua `assets/cv-eduardo-fr.pdf` por um arquivo com o mesmo nome, ou adicione outro e atualize o link do botão.

## Ver antes de publicar

No VS Code, com a extensão **Live Server**: botão direito em `index.html` → **Open with Live Server**.
O navegador atualiza sozinho cada vez que você salva.

## Publicar

```
git add .
git commit -m "descreva a mudança"
git push
```

Em 1–2 minutos o site está atualizado.
