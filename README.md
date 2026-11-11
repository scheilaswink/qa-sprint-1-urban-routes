# Testes de regressão — Urban Routes

Projeto da Sprint 1 do curso de QA Engineer da TripleTen: execução de testes de regressão no **Urban Routes**, aplicativo web de mapas e rotas, e documentação dos bugs encontrados.

## Objetivo

Garantir que a nova versão do Urban Routes não introduziu regressões nas funcionalidades principais do mapa: navegação, zoom, busca de endereços, modos de visualização (Mapa, Relevo, Satélite, Street View, tela cheia) e exibição de objetos.

## O que foi feito

- Execução de **24 casos de teste** de regressão já escritos.
- Registro do resultado de cada caso (Aprovado / Reprovado).
- Escrita de **9 relatórios de bug** para os casos reprovados, com título, etapas para reprodução, resultado esperado, resultado real e prioridade.

## Resultados

| Indicador | Total |
|---|---|
| Casos de teste executados | 24 |
| Aprovados | 15 |
| Reprovados | 9 |
| Bugs de prioridade Alta | 6 |
| Bugs de prioridade Média | 1 |
| Bugs de prioridade Baixa | 2 |

### Principais bugs encontrados

- A lista de estações de metrô não aparece ao pesquisar "Subway" no campo "Para" (Alta).
- O pino de endereço não aparece depois de preencher os campos "De" e "Para" (Alta).
- As informações do aplicativo não aparecem ao clicar no logotipo do Urban Routes (Alta).
- O nível de zoom muda ao ativar o modo de tela cheia (Média).
- Títulos de áreas do mapa são clicáveis quando não deveriam ser (Baixa).

## Arquivos

- [`casos-de-teste-e-bugs-urban-routes.xlsx`](casos-de-teste-e-bugs-urban-routes.xlsx): planilha com duas abas:
  - **Casos de teste**: ID, nome, pré-condição, etapas, resultado esperado, status e ID do bug.
  - **Relatórios de bug**: ID, título, etapas para reprodução, resultado esperado, resultado real e prioridade.

## O que aprendi

Neste primeiro projeto aprendi habilidades essenciais para testar interfaces manualmente:

- **Teste de fumaça:** testar novos recursos de software.
- **Teste de regressão:** garantir que as alterações no software não criem novos erros.
- **Relatório de bugs:** criar relatórios completos que descrevem problemas no software, com etapas para reprodução, resultado esperado, resultado real e prioridade.
