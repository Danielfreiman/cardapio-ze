# Cardápio do Zé do Açaí

Cardápio digital mobile first, apenas para consulta, com identidade roxa e creme, busca por produtos e categorias e aviso de pedidos no caixa.

## Abrir

Abra `dist/index.html` no navegador. Para servir localmente, execute `python -m http.server 8000 --directory dist` e acesse `http://localhost:8000`.

## Hospedagem

Site estático, sem instalação ou etapa de build. Configure `dist` como diretório de publicação na hospedagem escolhida.

## Editar

- `dist/index.html`: estrutura, categorias de açaí e avisos.
- `dist/data.js`: produtos, descrições, preços e imagens.
- `dist/app.js`: busca, tamanhos e complementos.
- `dist/style.css` e `dist/menu-theme.css`: layout responsivo e cores.
- `dist/assets`: logo, mascote, fotos e PDF original.

A fonte Poppins é carregada pelo Google Fonts, com fonte alternativa quando indisponível. As fotos transparentes foram tratadas individualmente com IA; alguns detalhes foram reconstruídos. Os recortes originais estão preservados nos arquivos WebP.
