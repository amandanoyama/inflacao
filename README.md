# Análise de Inflação — IPCA

Dashboard interativo de núcleos e componentes estruturais do IPCA, voltado a apresentações executivas no mercado financeiro.

## Conteúdo

| Arquivo | Descrição |
|---|---|
| `dashboard.html` | Dashboard single-file (HTML + Plotly.js via CDN). Abrir diretamente no navegador. |
| `ipca15 dessaz.xlsx` | Base de dados mensal do IPCA-15 dessazonalizado. |

## Séries analisadas

A partir de **janeiro de 2013**, em variação interanual (%):

1. Média dos 5 núcleos
2. EX3 Serviços
3. Alimentação no domicílio
4. Produtos industriais
5. Preços Administrados

## Como abrir

Basta dar duplo clique em `dashboard.html` ou abrir o arquivo em qualquer navegador moderno. Não requer instalação ou servidor local — a única dependência externa é a CDN do Plotly.js, carregada automaticamente.

## Funcionalidades

- KPI cards com o último dado disponível de cada série
- Tooltips em português com data por extenso e valor em duas casas decimais
- Crosshair vertical sincronizado para leitura de pontos de virada
- Zoom, pan, reset de visualização e exportação para PNG
- Layout responsivo (2 colunas em desktop, 1 coluna em telas menores)
