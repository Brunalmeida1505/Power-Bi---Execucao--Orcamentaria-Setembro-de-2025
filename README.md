# Projeto Power BI -- Execução Orçamentária

## 📌 Visão Geral

Este projeto em Power BI tem como objetivo analisar a **Execução
Orçamentária Funcional** do mês de **Setembro**, permitindo uma
visualização clara e interativa dos gastos, funções, subfunções e demais
classificações orçamentárias.

O dashboard foi desenvolvido para apoiar a **tomada de decisão**,
oferecendo indicadores visuais, filtros dinâmicos e análises
comparativas.

------------------------------------------------------------------------

## 🎯 Objetivos do Projeto

-   Monitorar a execução do orçamento por função e subfunção\
-   Identificar áreas com maior consumo de recursos\
-   Facilitar a análise gerencial através de visualizações interativas\
-   Apoiar o controle e a transparência dos gastos públicos/empresariais

------------------------------------------------------------------------

## 🗂️ Fonte de Dados

Os dados utilizados neste projeto são provenientes de dados abertos do
Governo de Goiás - Base de dados estruturada com informações de:
 - Função - Subfunção - Programa - Ação - Valores
orçados e executados - Mês de referência (Setembro/25)

------------------------------------------------------------------------

## 🔄 Processo de Tratamento de Dados (ETL)

No Power Query, foram realizadas as seguintes etapas: - Limpeza de dados
(remoção de linhas e colunas desnecessárias) - Padronização de nomes de
campos - Conversão de tipos de dados - Criação de colunas calculadas
auxiliares - Tratamento de valores nulos ou inconsistentes

------------------------------------------------------------------------

## 🧮 Modelagem de Dados

O modelo de dados foi estruturado para: - Facilitar a criação de medidas
em DAX - Garantir bom desempenho nas análises - Permitir filtros
eficientes entre tabelas - Organizar dimensões (Função, Subfunção,
Programa, etc.) e fatos (Valores)

------------------------------------------------------------------------

## 📊 Principais Métricas (DAX)

Exemplos de indicadores utilizados: - Total Orçado - Total Executado -
Percentual de Execução - Diferença entre Orçado x Executado - Ranking de
Funções por Gasto

------------------------------------------------------------------------

## 📈 Visualizações do Dashboard

O relatório contém: - Cartões com indicadores principais (KPIs) -
Gráficos de barras e colunas para comparação por função/subfunção -
Tabelas detalhadas para análise analítica - Segmentadores (filtros)
por: - Função - Subfunção - Período - Programa

------------------------------------------------------------------------

## 🧭 Como Utilizar o Relatório

1.  Abra o arquivo `.pbix` no Power BI Desktop\
2.  Utilize os filtros laterais para refinar a análise\
3.  Clique nos gráficos para aplicar filtros cruzados\
4.  Analise os indicadores principais no topo do dashboard\
5.  Explore os detalhes nas tabelas e gráficos complementares

------------------------------------------------------------------------

## 🚀 Benefícios do Projeto

-   Visão clara da execução orçamentária
-   Apoio à gestão e ao planejamento financeiro
-   Identificação rápida de desvios e excessos de gastos
-   Base para relatórios gerenciais e prestação de contas

------------------------------------------------------------------------

## 🛠️ Tecnologias Utilizadas

-   Power BI Desktop
-   Power Query (ETL)
-   DAX para medidas e cálculos
-   Fonte de dados em formato estruturado (Excel/CSV/BD)

------------------------------------------------------------------------

## 📌 Observações Finais

Este projeto pode ser expandido para incluir: - Comparação entre meses -
Análise histórica - Projeções orçamentárias - Integração com outras
bases de dados

------------------------------------------------------------------------

📄 **Autor:** Bruna Almeida\
📅 **Projeto:** Execução Orçamentária -- Setembro
