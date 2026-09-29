# TATUDONA - Landing Page Lis Mainá

Este é o projeto da landing page para a marca "Tatudona" da tatuadora Lis Mainá.
O design foi construído seguindo a estética editorial, urbana e underground solicitada, utilizando alto contraste, tipografia expressiva e blocos marcantes.

## Estrutura do Projeto

tatudona/
├── index.html        # Estrutura principal da página (utiliza Tailwind via CDN)
├── css/
│   └── style.css     # Estilos complementares (animações, grid assimétrico, ruído)
├── js/
│   └── script.js     # Interatividade (menu mobile, acordeão de FAQ)
└── assets/
    ├── images/       # Pastas prontas para receber as imagens reais
    │   ├── hero/
    │   ├── portfolio/
    │   ├── flashes/
    │   └── artist/
    ├── logos/
    └── icons/

## Instruções para Edição (Para Lis / Desenvolvedor)

### 1. Substituir Imagens
As imagens atuais no HTML apontam para URLs do *Unsplash* como placeholders. Para colocar as imagens reais:
1. Coloque a foto desejada na pasta correta (ex: `assets/images/portfolio/tattoo-01.webp`).
2. Abra o arquivo `index.html`.
3. Busque a tag `<img>` correspondente e altere o `src`:
   `<img src="assets/images/portfolio/tattoo-01.webp" alt="...">`

### 2. Substituir Informações Reais (Placeholders)
Abra o `index.html` e procure por textos entre chaves ou identificados como placeholders. Você precisa atualizar:
- `[INSERIR CIDADE]`
- `[ESTILO 1]`, `[ESTILO 2]` (Nas seções Filtros e Especialidades)
- `[INSERIR TEXTO PESSOAL FORNECIDO PELA ARTISTA]` (Na seção Sobre Mim)
- `[INSERIR LOCALIZAÇÃO REAL / ESTÚDIO]` (No FAQ)
- `[INSERIR POLÍTICA DE PREÇOS REAL DA LIS]` (No FAQ)
- `[LINK DO WHATSAPP]` (Ex: https://wa.me/5521999999999)
- `[LINK DO INSTA]` (Ex: https://instagram.com/lismaina)
- `[EMAIL]`

### 3. Publicação (Deploy)
Como o site é estático (apenas HTML/CSS/JS), ele pode ser publicado gratuitamente em plataformas como:
- **GitHub Pages**
- **Vercel**
- **Netlify**
- **Cloudflare Pages**
Basta fazer o upload ou conectar o repositório da pasta `tatudona/`.
