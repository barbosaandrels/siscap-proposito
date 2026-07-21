# SISCAP — Sistema de Captação Territorial

Site institucional/comercial do SISCAP, produto da **PROPÓSITO — Inteligência Estratégica**: landing page com formulário de autocomplete de cidades, cálculo automático de região (e bairro na capital), automação via Google Sheets/Apps Script e roteamento para grupos de WhatsApp por região.

Este material usa um exemplo **fictício** ("Renata Salgado", estado "Serra Clara") para fins de prospecção comercial com outros candidatos — não representa nenhum candidato ou campanha real.

## Estrutura

- `site/index.html` — página publicada. Este arquivo (e a pasta `site/`) deve ser configurado como diretório de build no Cloudflare Pages.
- `site/assets/og-image.png` — imagem de compartilhamento (Open Graph/Twitter Card) usada na prévia de link no WhatsApp e redes sociais.

## Pendências antes de publicar/prospectar oficialmente

1. **Foto do exemplo** — a seção do hero usa uma ilustração abstrata (avatar) no lugar de uma foto real, já que se trata de um exemplo fictício. Se for substituída por uma imagem gerada por IA, manter a informação de que a imagem é gerada por IA visível na página.
2. **Botão "Solicitar proposta"** — já aponta para o WhatsApp `https://wa.me/5551994671877` (número não exibido como texto na página).
3. **Domínio** — publicado inicialmente no subdomínio padrão do Cloudflare Pages (`*.pages.dev`); atualizar as URLs absolutas nas meta tags Open Graph/Twitter em `site/index.html` caso um domínio próprio seja configurado depois.
