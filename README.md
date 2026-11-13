# Lunarts Edições Musicais

Landing page estática da Lunarts (Roberto Luna), editora musical de direitos autorais em Natal/RN.

- `index.html`: página única com CSS e JavaScript embutidos, sem build.
- `assets/img`: fotos em WebP e imagem de compartilhamento.
- `assets/favicon`: ícones da aba.
- `vercel.json`: cache longo para `/assets`.

## Publicar

1. Suba esta pasta para um repositório no GitHub.
2. Na Vercel, clique em "Add New > Project", importe o repositório e mantenha o preset "Other" (sem comando de build).
3. Para usar `lunartsedicoes.com.br`, vá em Settings > Domains do projeto, adicione o domínio e siga os registros DNS que a Vercel mostrar no Registro.br.

Cada push na branch `main` publica uma nova versão automaticamente.
