# dashboard-xbox

[English](README.en.md) · **Português (Brasil)**

[![Excel](https://img.shields.io/badge/Excel-xlsx-217346?style=flat-square&logo=microsoftexcel)](#) [![MIT License](https://img.shields.io/badge/License-MIT-f4c430?style=flat-square)](LICENSE)

## O que é

**Dashboard de vendas do Xbox Game Pass feito em Excel** (desafio de organização e visualização de dados): transforma uma base de vendas bruta em KPIs, tabelas de cálculo (SUMIFS/participação) e um painel visual. É um arquivo `.xlsx` com 5 abas: Parâmetros, Base de Dados, Cálculos, Dashboard e Instruções.

## Status

Arquivo Excel concluído (desafio). Indicado para abrir no Excel/LibreOffice/Google Sheets.

## Funcionalidades

- **Aba Parâmetros**: planos e preços (Core/Standard/Ultimate, mensal/trimestral/anual), add-ons (EA Play, Minecraft Pass, Call of Duty Pass), metas e premissas configuráveis.
- **Aba Base de Dados**: 1.200 vendas com ID, data, plano, ciclo, região, canal, add-ons, tipo (novo/renovação), quantidade, receita, custo e lucro.
- **Aba Cálculos**: receita por plano, por região, participação e agregados (SUMIFS).
- **Aba Dashboard**: KPIs (Receita Total, Assinantes, Lucro Total, ARPU, Ticket Médio, Margem), atingimento de meta e visão analítica com gráficos.
- **Aba Instruções**: como usar e o que alterar com segurança.

### KPIs (a partir da base, verificados pelo agente no arquivo)

| KPI | Valor |
|-----|-------|
| Receita total | R$ 1.155.626,77 |
| Assinantes | 21.915 |
| Lucro total | R$ 892.646,77 |
| ARPU | R$ 52,73 |
| Ticket médio | R$ 963,02 |
| Margem de lucro | 77,2% |

## Estrutura do repositório

```
dashboard-xbox/
├── Dashboard_Xbox_Professional.xlsx   # o dashboard (5 abas)
├── contexto.txt                        # briefing/desafio
└── README · LICENSE
```

## Como usar

1. Abra `Dashboard_Xbox_Professional.xlsx` no Excel/LibreOffice/Google Sheets.
2. Use a aba 'Instruções' para orientação.
3. Edite apenas as células amarelas da aba 'Parâmetros' (as demais são automáticas).

## Testes e qualidade

Não há código/testes automatizados — é um arquivo Excel. A validação foi feita abrindo o arquivo e conferindo as abas, os cálculos e os KPIs (ver tabela acima).

## Processo de desenvolvimento

Projeto individual de Kelvin Oliveira, construído com agentes de IA orquestrados e revisado pelo autor. A modelagem das abas, os cálculos e a revisão são do autor.

## Licença e autor

MIT — Copyright (c) 2026 Kelvin Rebelo de Oliveira.

**Autor**: [Kelvin Oliveira](https://github.com/KelvinOliveiraCode) · [Portfólio](https://kelvinoliveiracode.github.io/portfolio/)
