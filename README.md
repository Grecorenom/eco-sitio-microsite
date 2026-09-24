# Microsite — Eco-Sítio La Querência (reserva direta)

Landing page única para captar reservas da unidade-piloto (casa na árvore),
encaminhando o visitante direto para o WhatsApp — sem taxa de OTA.

## Estrutura
```
microsite/
├── index.html      # página única (sem dependências externas, ~11 KB)
└── assets/
    └── hero.jpg    # foto principal (FOTO SUA AQUI)
```

## Preencher antes de publicar (3 campos)
1. **WhatsApp** — já configurado com o número 5594992094196 (verifique se está correto).
   Aparece 3 vezes no `index.html`: botão principal, rodapé, botão flutuante.
2. **Diária** — procure por `[PREENCHER: R$ ___]` no bloco de reserva.
   Sugestão: publicar a partir da primeira diária real medida na piloto
   (pode ficar "sob consulta" no começo — não é um problema, é padrão).
3. **Foto do hero** — coloque uma imagem real da casa na árvore em
   `assets/hero.jpg` (retrato ou paisagem, mínimo 1600px de largura).
   Sem a foto, a página mostra um fundo verde sólido (funciona, mas
   perde muito em conversão).

## Publicar (opções)
- **GitHub Pages** (recomendado — grátis, já com repositório):
  em github.com → repositório `eco-sitio-microsite` → Settings → Pages →
  deploy from branch `main`, pasta `/`. URL:
  `https://Grecorenom.github.io/eco-sitio-microsite/`
- **Cloudflare Pages / Netlify**: arrastar a pasta inteira; dá URL em 1 min.
- Depois de no ar, colocar a URL nos posts do Instagram e na bio do WhatsApp.

## Próximos passos sugeridos
- [ ] Preencher os 3 campos acima
- [ ] Substituir o hero por foto real
- [ ] Criar conta no Google Business (mapas) com a URL — aparece em buscas locais
- [ ] Gerar 3 variações de texto para Instagram/Ads (posso fazer via HF)
