# matheusgfsilva.github.io

Site pessoal de Matheus Gomes, publicado com GitHub Pages.

## Como publicar

1. No GitHub, crie um repositório público chamado exatamente `Matheusgfsilva.github.io`.
2. Envie o conteúdo desta pasta para ele (pela página do repositório: "Add file" > "Upload files", arrastando tudo; ou com `git`).
3. Em Settings > Pages, confira se a fonte é "Deploy from a branch", branch `main`, pasta `/ (root)`.
4. Em um ou dois minutos o site estará em https://matheusgfsilva.github.io

## Como atualizar

- **Foto:** coloque uma foto sua em `images/foto.jpg`. Sem ela, aparece um quadro com as iniciais.
- **Textos:** tudo está em `index.html`. Cada trecho existe em duas versões, marcadas com `data-lang="pt"` e `data-lang="en"`; edite as duas.
- **Novidades:** copie um bloco `news-item` e mantenha a ordem do mais recente para o mais antigo.
- **Currículos:** os PDFs ficam em `docs/`. Os arquivos-fonte LaTeX estão em `docs/latex/`. Para editar, envie os três `.tex` ao [Overleaf](https://www.overleaf.com), compile o PT e o EN e substitua os PDFs em `docs/` mantendo os mesmos nomes.
