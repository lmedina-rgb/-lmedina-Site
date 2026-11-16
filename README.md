# Site — Prof. Dr. Liosber Medina García

Site pessoal e acadêmico estático (HTML + CSS, sem build).

- `index.html` — conteúdo
- `styles.css` — estilos (tema claro/escuro automático)
- `vercel.json` — configuração do Vercel

## Publicar no Vercel

1. Envie este repositório para o GitHub.
2. Em [vercel.com/new](https://vercel.com/new), importe o repositório.
3. Framework Preset: **Other**. Deixe Build Command e Output Directory vazios.
4. Clique em **Deploy**.

Ou, pela linha de comando: `npx vercel --prod` na pasta do projeto.

## Atualizar conteúdo

Para adicionar uma publicação, copie um bloco `<li data-tags="...">` em `index.html`.
As tags aceitas pelos filtros são `pav`, `geo`, `geot` e `mob`.
