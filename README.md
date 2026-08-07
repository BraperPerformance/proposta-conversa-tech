# Braper — Central do Cliente · Conversa.Tech

Portal de proposta comercial da Braper para a Conversa.Tech.

Site estático de arquivo único (`index.html`), sem dependências, sem build.

## Estrutura

- `index.html` — login, Central do Cliente e a proposta em slides (logos embutidos em base64)
- `vercel.json` — headers de privacidade (noindex, sem cache, sem iframe)

## Fluxo

1. Tela de login (nome livre + senha única)
2. Central do Cliente com o card da proposta
3. Proposta em 8 slides com modo claro/escuro

## Publicação

Qualquer host estático serve. Na Vercel: importar o repositório, framework "Other", sem comando de build, diretório de saída raiz.

## Observações

- A senha é verificada no navegador e serve como barreira de conveniência para uma proposta com validade de 15 dias, não como segurança forte. Não usar este modelo para conteúdo sensível.
- Proposta preparada em 07/08/2026, válida até 22/08/2026.

Desenvolvido pela Braper · mídia e performance © 2026
