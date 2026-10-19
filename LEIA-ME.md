# Calculadora de custo de impressão 3D (PWA)

Site instalável no celular, com cálculo de custo, preço de venda e compartilhamento do orçamento por WhatsApp e outros apps. Funciona offline depois do primeiro acesso.

## Arquivos
- `index.html`: o app inteiro (telas e cálculos)
- `manifest.webmanifest`: nome, cores e ícones do app instalado
- `sw.js`: faz o app funcionar offline
- `icons/`: ícones do app

## Como publicar (precisa de HTTPS; os serviços abaixo já oferecem)
1. Descompacte o .zip.
2. Envie a pasta para um serviço de hospedagem estática, por exemplo Netlify (arrastar e soltar a pasta), GitHub Pages, Vercel ou Cloudflare Pages.
3. Abra o endereço gerado no celular.

## Como instalar no celular
- **Android (Chrome):** toque em “Instalar app” na página, ou no menu ⋮ e em “Instalar app”.
- **iPhone (Safari):** toque em Compartilhar e depois em “Adicionar à Tela de Início”.

## Como atualizar depois
1. Edite o `index.html`.
2. Em `sw.js`, troque `calc3d-v1` por `calc3d-v2` (e assim por diante).
3. Envie os arquivos de novo para a hospedagem.

## Observações
- Os dados digitados ficam salvos só no aparelho. Limpar os dados do navegador apaga tudo.
- Os preços iniciais (filamento, energia, impressora) são exemplos: ajuste para a sua realidade.
