# Cardápio de pães artesanais

Cardápio estático de oito páginas, baseado no catálogo de referência. Preserva cores, navegação por arraste, setas, som opcional e ampliação. As artes não incluem preços, sugestão de revenda, ganho ou margem.

## Abrir localmente

Execute `python3 -m http.server 3000` nesta pasta e abra http://localhost:3000.

## GitHub e Vercel

1. Crie um repositório no GitHub e envie o conteúdo desta pasta, mantendo `index.html` na raiz.
2. Na Vercel, escolha **Add New → Project** e importe esse repositório.
3. Framework Preset: **Other**. Root Directory: raiz do repositório. Build Command: vazio. Output Directory: `.`.
4. Clique em **Deploy**. Novos commits no repositório serão publicados automaticamente pela integração da Vercel.

Não há dependências, banco de dados ou chaves de API. `vercel.json` já configura a publicação estática.

## Arquivos

- `index.html`: estrutura e controles.
- `style.css`: visual e adaptação à tela.
- `app.js`: efeito de virar página, navegação e ampliação.
- `assets/page-0.jpg` a `page-7.jpg`: capa e sete produtos, já sem os blocos financeiros.
