# Mapa de Dividendos — Fundos Imobiliários

Visualização institucional, **puramente informativa**, dos dividendos pagos por Fundos de Investimento Imobiliário (FIIs) listados na B3.

**Acesse**: https://renanbarretoj.github.io/fii-mapa-dividendos/

## O que mostra

Para cada um dos ~360 FIIs com pagamentos regulares:

- Última data-ex e data de pagamento
- Dia típico do mês (moda + intervalo p25–p75) para data-ex e pagamento
- DY mês (último provento / preço atual) e DY 12m acumulado
- Desconto/Ágio sobre o Valor Patrimonial (P/VPA)
- Coeficiente de recovery (β) — sensibilidade do preço ao tamanho do dividendo
- Frequência de pagamento (Mensal regular, Quase mensal, Irregular)
- Variação 3m / 6m / 12m e volume médio diário em R$

Filtros por setor, frequência, volume mínimo e faixa de DY.

## Sem recomendações

Documento **puramente informativo**. Não constitui recomendação de compra, venda ou manutenção de ativos.
Decisões de investimento são de responsabilidade exclusiva do leitor.

## Dados e atualização

- **Astecha** — provedora dos dados (PROVENTO, COTACAO, FUNDO_B3, INFORME_MENSAL_FII via Snowflake)
- **RX Asset** — curadoria e apresentação

Atualizado periodicamente conforme novos eventos são anunciados e os informes mensais da CVM são publicados.
