# ESTADO ATUAL — SENHOR BURGER

## PROJETO EM ANDAMENTO

Nome: Senhor Burger — site institucional/experiência
Cliente: Senhor Burger (hamburgueria artesanal, Contagem/MG)
Nicho: Hamburgueria artesanal / delivery / refeição no local
Tipo: Cliente real
Repositório GitHub: a criar (infraestrutura atual: HTML/CSS/JS vanilla — NÃO migrar para Tailwind/daisyUI, conforme fonte 10)
Branch principal: main
URL pública: https://carloszw45.github.io/senhor-burger-site/ (GitHub Pages — decisão do cliente, Ciclo 2)
URL de produção: a definir

---

## FASE ATUAL

Protótipo v0.2 — redesign completo da coreografia de motion após feedback do cliente ('site seco, sem transições fluidas'). Em auditoria visual.

Pesquisa ✓ → Estratégia ✓ → Conceito ✓ → Arquitetura ✓ → **Protótipo** → Aprovação → Desenvolvimento → Refinamento → QA → Publicação

---

## OBJETIVO PRINCIPAL

Conversão desejada: pedido online (WhatsApp) ou visita ao restaurante
CTA principal: "Pedir agora" → wa.me/5531975667577 (mensagem pré-preenchida)
CTAs secundários: "Ver cardápio completo" (app.menudino.com) · "Como chegar" (Google Maps, código 5VF4+G9)
Público/contextos prioritários: famílias e grupos do bairro Nova Contagem/região; pedidos delivery no entorno; happy hour (chopp 2x1)

---

## FATOS VERIFICADOS (fontes: Google Maps fornecido pelo usuário, Instagram/Facebook públicos, agregadores)

- Nome: Senhor Burger — hamburgueria artesanal
- Nota Google: 4,7 com 1.276 avaliações
- Faixa de preço: R$ 40–60 por pessoa (informado por 85 pessoas no Google)
- Endereço: R. VP-1, 2454 — Nova Contagem, Contagem/MG, 32050-602 (ao lado do Supermercado Nova, segundo Facebook)
- Telefone/WhatsApp: (31) 97566-7577
- Funcionamento: abre às 18h; às segundas abre 18h–00h; terça-feira fechado (restaurants-us.com e wheree.com) — CONFIRMAR horário completo
- Destaques do Google: "Mais pedidos: Hambúrguer Artesanal" e rótulo "Melhor Hambúrguer da Região"
- Itens citados em fontes públicas: Hambúrguer Artesanal, Angus Marilyn, Beef Burger, batata rústica (Potato Wedges)
- Serviços: refeição no local, para viagem, entrega sem contato, delivery próprio 40–50 min (MenuDino), aceita reservas
- Ambiente: acessível (cadeirante), familiar, LGBTQ+ friendly, Wi-Fi, estacionamento, cerveja/chopp, vinho, sobremesa, opções vegetarianas
- Promoções públicas recentes: chopp 2x1 (happy hour), lanche gourmet R$ 29,90 (promoção de rede, confirmar vigência)
- Espaço reformado recentemente (avaliação de cliente, um mês atrás)
- Instagram: @senhor_burger · Facebook: SenhorBurgerHamburgueria
- Reviews reais fornecidas pelo usuário: Alinne Gomes, Isaque Pride, Duda Games play Craft
- Equipe elogiada pelo nome em reviews (ex.: Ryan)
- Selo Google: "Empresa que acolhe a comunidade LGBTQ+"
- Concorrentes próximos (Google): Ateliê do Hamburguer (4,6/43), Sr. Hambúrguer (4,5/216), Luiz Burguer (4,7/46), Gordo Buguer (1,0/1), Chris-Burguer e Pizzaria (3,1/11)

## HIPÓTESES / PONTOS A VALIDAR

- Horário completo de funcionamento (terça fechado? até que horas cada dia?)
- Vigência atual das promoções (chopp 2x1, lanche R$ 29,90)
- Fotos reais do ambiente e dos pratos (substituir assets de IA)
- Autorização comercial das fotos do Instagram/Google para uso final
- Itens e preços exatos do cardápio (MenuDino bloqueou acesso automatizado)

---

## CONCEITO

Frase-conceito: **"Tratamento de senhor: o hambúrguer no centro da mesa, você na melhor cadeira."**
Direção artística: "Noite de bairro elevada a ritual" — brasa, queijo derretido, madeira, luz âmbar baixa, hospitalidade que chama pelo nome. A marca "Senhor" tratada como título de nobreza do hambúrguer.
Sensação desejada: aconchego noturno + orgulho artesanal + fome imediata.
Princípios visuais:
- Paleta: Carvão #100D0A · Creme envelhecido #F2E7D5 · Âmbar queijo #E9A13B · Brasa #C8502E (acento mínimo)
- Tipografia: Fraunces (serifada display, eixo "soft" — ar de selo/título) + Archivo (grotesca funcional)
- Motivo autoral: selo circular + serifas; círculo âmbar como elemento de continuidade entre cenas
- Fotografia: escura, luz âmbar dramática, editorial
- Movimento: scroll-driven, stateless (função do progresso), transform/opacity apenas

---

## ESTRUTURA / STORYTELLING (arquitetura aprovada para protótipo)

Cena 01 — ABERTURA (150vh): "SENHOR BURGER" gigante sobre o burger; selo "Melhor Hambúrguer da Região" (rótulo real do Google). O queijo derretido expande em glow âmbar na base.
Cena 02 — PROVA (120vh, fundo âmbar): nasce do derretido da cena 01. "4,7" gigante + "1.276 avaliações" + 3 reviews reais com atribuição.
Cena 03 — OS CLÁSSICOS (300vh, 3 estados): Angus Marilyn → Hambúrguer Artesanal → Beef Burger + Batata Rústica. Disco âmbar (mão contínua do selo/nota) vira tábua sob o prato. CTA cardápio MenuDino.
Cena 04 — A CASA (130vh): foto do ambiente; "Reformado para receber melhor." + conveniências verificadas (Wi-Fi, acessível, família, LGBTQ+, estacionamento, cerveja).
Cena 05 — DELIVERY & HAPPY HOUR (130vh): "Bateu a fome em casa?" delivery 40–50 min + chopp 2x1 + CTA WhatsApp.
Cena 06 — FECHAMENTO (100vh): endereço, horários, telefone, Instagram, mapa, selo final.

## TRANSIÇÕES

01 → 02: o queijo derretido (âmbar) expande da base do burger e vira o fundo da cena de prova.
Elemento de origem: glow âmbar / cor do queijo. Transformação: expansão de cor. Chegada: fundo âmbar da prova.

02 → 03: o disco circular da nota/selo desloca-se para baixo e vira a tábua âmbar sob o primeiro prato.
Elemento de origem: círculo âmbar da cena 02. Transformação: translação + assentamento. Chegada: tábua sob o Angus Marilyn.

03 → 04: a foto do último prato escurece e o ambiente acende por trás (crossfade guiado pelo scroll).
04 → 05: o brilho âmbar do ambiente vira o foco noturno do delivery.
05 → 06: o caminho do entregador (linha tracejada) vira a rota do mapa.

---

## ASSETS

Disponíveis/aprovados: nenhuma foto real aprovada ainda
Provisórios: 4 imagens geradas por IA (burger hero, burger bacon/onion, wedges, ambiente) — COM MARCA D'ÁGUA, substituir antes da publicação final
Pendentes: fotos reais de pratos, ambiente e equipe
Direitos/autorizações a confirmar: fotos do Instagram/Google do cliente

---

## CONTEÚDO

Textos aprovados: provisórios (protótipo)
Dados/reviews a validar: atribuições Alinne Gomes, Isaque Pride, Duda (fornecidas pelo usuário, preservar sentido)

---

## IMPLEMENTADO

Protótipo v0.2 (HTML/CSS/JS vanilla): 6 cenas com coreografia stateless expandida — letras de SENHOR levantam na saída da cena 1; queijo→glow âmbar→cena 2; contadores animados (4,7 / 1.276); vírgula do 4,7 -> disco-tábua sob o prato (handoff posicional no seam 02→03); prato com dono único e revelação circular; tábua expande como iris revelando o ambiente (03→04); bloom de neon (04→05); rota tracejada com ponto viajante (05→06); brasas flutuantes; marquee; nav esconde/mostra; rail de cenas; reveals de linha/palavra em stagger; efeitos hover. Responsivo + prefers-reduced-motion.

## EM DESENVOLVIMENTO

Aguardando aprovação do protótipo.

## FILA DE AUDITORIA

Arquivo: AUDITORIA_INCREMENTAL.md — vazia (protótipo em primeira auditoria)

## PROBLEMAS CONHECIDOS

- Assets de IA com marca d'Água (provisório por definição)
- Horário de funcionamento completo não confirmado
- Link do cardápio MenuDino genérico (app.menudino.com) — confirmar URL exata da loja

## NÃO FAZER / SOLUÇÕES REJEITADAS

- Não migrar para Tailwind/daisyUI (fonte 10 — regra específica do projeto)
- Não inventar preços, pesos de blend, anos de fundação ou prêmios
- Não usar reviews fabricados

## ÚLTIMA DECISÃO IMPORTANTE

Data: 2026-09-21 (Ciclo 3)
Decisão 1: Infraestrutura = GitHub repo + GitHub Pages (instrução explícita do cliente; substitui deploy_website da plataforma). Repo: Carloszw45/senhor-burger-site
Decisão 2: v0.2 redesenha a coreografia de motion inteira — transições nascem de OBJETOS/PALAVRAS da cena anterior (letras, vírgula→tábua, iris, neon, rota), não de fades genéricos. Motivo: feedback do cliente de que v0.1 estava "seco, só scroll".
Decisão 3: imagens PNG 1,7MB otimizadas para JPG progressivo ~120-160KB (performance é parte do design).

## PRÓXIMO PASSO EXATO

1. Usuário aprova ou pede ajustes no protótipo
2. Após aprovação: Desenvolvimento final com assets reais + GitHub
3. Rodar protocolo completo de auditoria (2 revisões de código + 2 auditorias visuais + certificação final extra)

## RESUMO PARA NOVO CHAT

Projeto Senhor Burger (hamburgueria, Nova Contagem/MG). Fase: PROTÓTIPO aguardando aprovação. Conceito: "Tratamento de senhor" — carvão/creme/âmbar, Fraunces+Archivo, 6 cenas com transições contextuais (queijo→âmbar→tábua). Conversão: WhatsApp (31) 97566-7577. Assets de IA são provisórios. Não migrar para Tailwind. Próximo passo: aprovação do usuário → desenvolvimento final + protocolo de auditoria completo.
