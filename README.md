# MAR Câmeras — landing page

Landing page cinematográfica (rolagem guiada) da MAR Câmeras, Segurança Eletrônica.

- Site estático: `index.html` + `assets/` (GSAP, ScrollTrigger e Lenis locais, fontes locais, quadros WebP).
- Publicação: Dokploy (Build Type Dockerfile, porta 80) ou Hostinger (ver `COMO-PUBLICAR.txt`).
- Antes de publicar: preencher o bloco `CONFIG` no fim do `index.html` (região, razão social, CNPJ), conferir o domínio nas tags canonical/og e remover a tarja "Em desenvolvimento".
- Teste local: `python -m http.server` na raiz e abrir `http://localhost:8000/`. Abrir o arquivo direto cai no modo estático. `?sem-movimento=1` força o modo estático.
