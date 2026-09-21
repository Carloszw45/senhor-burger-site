# AUDITORIA INCREMENTAL — SENHOR BURGER

## Estado-base

- Projeto: Senhor Burger — site experiência
- Versão publicada: protótipo v0.1
- Commit-base: —
- URL: ver ESTADO_ATUAL_SENHOR_BURGER.md
- Regra: um problema por ciclo/conversa.
- Após cada correção: publicar imediatamente; depois reiniciar validação do zero.

## Estados

- `PENDENTE`: identificado, ainda não tratado.
- `EM_CORRECAO`: único problema ativo.
- `PUBLICADO`: correção está no repositório/site; validação ainda em andamento.
- `VALIDADO`: correção publicada e certificada pelo protocolo.
- `REABERTO`: regressão ou refinamento adicional do mesmo item.

## Fila

| ID | Área | Problema / objetivo | Estado | Commit(s) | Validação / evidências |
|---|---|---|---|---|---|
| SB-001 | Assets | Imagens provisórias de IA contêm marca d'água ("AI生成") — substituir por fotos reais do cliente antes da publicação final | PENDENTE | — | — |
| SB-002 | Conteúdo | Horário completo de funcionamento não confirmado (terça fechado? horário por dia) | PENDENTE | — | — |
| SB-003 | Links | URL exata da loja no MenuDino não confirmada (usado link genérico app.menudino.com) | PENDENTE | — | — |
| SB-004 | Motion | Feedback do cliente: protótipo 'seco, sem transições fluidas' — v0.3: motor com inércia (lerp 0.085), Viajante persistente (um objeto/uma timeline), atmosfera global, parallax em camadas | PUBLICADO | 57924b1 | auditoria Playwright v0.3: 0 erros console; probe Viajante scale=1.000; screenshots hero/cena2/cena3/footer aprovados; pendente validação humana do cliente |

## Procedimento por item

1. Selecionar primeiro item não validado.
2. Trabalhar somente nele.
3. Corrigir.
4. Publicar imediatamente.
5. Atualizar cache-busting se necessário e publicar.
6. Zerar validação.
7. Revisar HTML/CSS/JS/integração — passagem 1.
8. Revisar HTML/CSS/JS/integração — passagem 2.
9. Auditar visualmente duas vezes, cada auditoria com ↓ ↑ ↓ ↑.
10. Se houver erro ligado ao item: corrigir → publicar → zerar → voltar ao passo 7.
11. Depois de zero erros, fazer certificação final extra: +2 revisões de código +2 auditorias visuais.
12. Registrar commits e evidências.
13. Marcar `VALIDADO`.
14. Encerrar o ciclo.

## Novos problemas encontrados

(nenhum ainda — preencher durante as auditorias do protótipo)
