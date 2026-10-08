# janainacarvalho

Páginas públicas da psicóloga Janaína de Souza Carvalho, no GitHub Pages.

- `anamnese/`: link do formulário "Antes da nossa primeira conversa". Mostra a prévia própria no WhatsApp e redireciona para o Tally (`tally.so/r/zxa8jE`).
- `index.html`: página inicial do site (apresentação, serviços, como funciona a avaliação, sobre, contato). As imagens de `img/` são geradas por `site/gerar_imagens.py` no `jana-projetos`.
- `avaliacao-neuropsicologica/`: página sobre a avaliação neuropsicológica (quando procurar, etapas, perguntas frequentes), com dados estruturados.
- `estilo.css`: estilo comum das páginas do site.
- `fontes/`: Cormorant Garamond e Montserrat (subconjunto latino, WOFF2 variável, licença OFL ao lado), servidas pelo próprio site em vez do Google Fonts, para a página abrir mais rápido.
- As páginas usam as imagens `img/*.webp`; os PNG e JPG ficam para a prévia de link e para quem já os linkou.
- `robots.txt` e `sitemap.xml`: para os buscadores. Página nova entra no `sitemap.xml`.
- `assinatura/`: assinatura de e-mail da Jana (logo em `logo.png`, gerada por `link-anamnese/gerar_assinatura.py` no `jana-projetos`) e botão para copiar e colar no Gmail.
- `previa-anamnese.jpg`: imagem da prévia, gerada por `link-anamnese/gerar_previa.py` no repositório privado `jana-projetos`.

Domínio próprio: `carvalhopsi.com` (DNS na Cloudflare, só DNS, sem proxy). O endereço antigo `petronio2nd.github.io/janainacarvalho` redireciona para ele.
