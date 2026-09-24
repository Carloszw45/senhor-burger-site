# Senhor Burger — Asset Map

Este arquivo é a fonte de verdade para os assets visuais usados no Stitch.

## Convenção

- **Asset ID**: identificador estável usado em SITE.md, prompts do Stitch e código final.
- **Status**: `APPROVED`, `PROVISIONAL`, `REFERENCE ONLY`, `PENDING` ou `REJECTED`.
- **Public URL**: preenchida somente quando o arquivo correspondente estiver publicado no GitHub.
- **Uso**: posição exata do asset na experiência.

---

## 01 — Brand

### `brand-logo`
- Arquivo alvo: `stitch-assets/01-brand/logo-senhor-burger.png`
- Status: `PENDING UPLOAD`
- Uso: footer e momentos institucionais com espaço suficiente para o selo completo.
- Header: manter identificador textual quando o selo circular comprometer legibilidade.
- Public URL: `PENDING`

---

## 02 — Hero

### `hero-main`
- Arquivo alvo: `stitch-assets/02-hero/hero-main.png`
- Status: `PENDING UPLOAD`
- Uso: imagem protagonista do hero da Home.
- Desktop: grande composição editorial; `cover`; produto como foco principal.
- Mobile: crop vertical/intencional; produto visível cedo no viewport.
- Public URL: `PENDING`

---

## 03 — Featured Products

### `product-fat-family`
- Arquivo alvo: `stitch-assets/03-products/fat-family.png`
- Status: `PENDING UPLOAD`
- Uso: primeiro produto da seção `ESCOLHA PELO DESEJO`.
- Prioridade: maior presença visual da seção.
- Public URL: `PENDING`

### `product-big-elvis`
- Arquivo alvo: `stitch-assets/03-products/big-elvis.png`
- Status: `PENDING UPLOAD`
- Uso: segundo produto da seção `ESCOLHA PELO DESEJO`.
- Public URL: `PENDING`

### `product-smash-joplin`
- Arquivo alvo: `stitch-assets/03-products/smash-joplin.png`
- Status: `PENDING UPLOAD`
- Uso: terceiro produto da seção `ESCOLHA PELO DESEJO`.
- Public URL: `PENDING`

### `product-veggie-marley`
- Arquivo alvo: `stitch-assets/03-products/veggie-marley.png`
- Status: `PENDING UPLOAD`
- Uso: quarto produto da seção `ESCOLHA PELO DESEJO`.
- Public URL: `PENDING`

---

## 04 — Environment

### `environment-main`
- Arquivo alvo: `stitch-assets/04-environment/environment-main.png`
- Status: `PENDING`
- Uso: seção `A Casa`.
- Desktop: imagem ampla/horizontal com forte presença.
- Mobile: crop específico sem reduzir a imagem a um card pequeno.
- Public URL: `PENDING`

---

## 05 — Final CTA

### `final-product`
- Arquivo alvo: `stitch-assets/05-final-cta/final-product.png`
- Status: `PENDING`
- Uso: seção escura de conversão final.
- Direção: close forte de produto; não repetir exatamente o hero.
- Public URL: `PENDING`

---

## 06 — Supporting Assets

Assets opcionais, não obrigatórios na primeira versão:

- `support-nirvana-melt`
- `support-angus-marilyn`
- `shake-pistache`
- `shake-bacon`
- `shake-crocante`
- `shake-nesquik`
- `shake-ninho`
- `food-coxa-creme`

Status atual: `PENDING / OPTIONAL`.

Não criar novas seções apenas porque esses arquivos existem.

---

## Regra de integração com Stitch

Quando `Public URL` estiver preenchida:

1. usar exatamente o Asset ID correspondente;
2. usar exatamente a URL pública registrada;
3. não substituir por imagem gerada, stock ou outro asset do projeto;
4. não reutilizar uma imagem de produto em outro produto;
5. preservar as regras de crop e hierarquia definidas aqui e no DESIGN.md.

## Regra de atualização

Sempre que um asset for publicado, substituído, aprovado ou rejeitado:

1. atualizar este arquivo;
2. atualizar `assets.json` quando existir;
3. manter SITE.md e prompts do Stitch sincronizados;
4. não alterar silenciosamente Asset IDs permanentes.
