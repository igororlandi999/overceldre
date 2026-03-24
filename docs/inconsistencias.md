# Inconsistências Encontradas

## 2026-03-17
### Divergência entre planilha e Bling
- Sintoma: valores de entradas/saídas não batem
- Hipótese: critérios diferentes entre caixa e competência
- Impacto: alto
- Status: aberto

### Campo de tabela de preço não existe na API v3
- Sintoma: não vem idListaPreco
- Solução atual: inferência por SKU + preço
- Impacto: médio
- Status: resolvido parcialmente

### Risco de truncamento histórico
- Sintoma: ausência de from date no Apps Script cortava histórico
- Impacto: alto
- Status: resolvido