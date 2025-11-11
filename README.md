# 📊 Dashboard de Análise de Vendas - Gatito Petshop

Este dashboard interativo foi desenvolvido durante o treinamento da Alura em **Power BI** para fornecer uma visão abrangente e detalhada das vendas da **Gatito Petshop**. Ele permite monitorar o faturamento total, a média de itens por venda e analisar o desempenho por localização, produto e gênero do cliente ao longo do tempo, facilitando a tomada de decisões estratégicas.

## 🚀 Demonstração Visual

Abaixo, você pode ver um *screenshot* do painel principal, exibindo as métricas e a distribuição de vendas:

-----

<img width="793" height="446" alt="image" src="https://github.com/user-attachments/assets/9e29417c-674d-45d8-b25e-52399f840d7c" />


## ✨ Principais Métricas e Análises

O painel centraliza as análises em quatro áreas principais:

### Indicadores-Chave de Performance (KPIs)

  * **Faturamento Total:** **R$ 2,03 Milhões** (acumulado no período analisado).
  * **Média de Pets :** **2,61** média dos animais atendidos.
  * **Total de Itens Vendidos (Soma de Quantidade):** **57 Mil** unidades.

### Insights Chave

  * **Foco Geográfico:** O faturamento é fortemente concentrado nos bairros de **Itaquera** (R$ 0,66 Mi) e **Guaianases** (R$ 0,63 Mi), indicando áreas prioritárias para marketing e logística.
  * **Distribuição por Gênero:** A divisão do faturamento por gênero é equilibrada (aprox. **55%** vs **45%**), sugerindo que as estratégias de produto atendem a ambos os públicos.
  * **Tendência Temporal:** O gráfico de faturamento pela data mostra uma **forte tendência de crescimento** até meados de 2022, com picos de R$ 126 Mil. A queda no final do período exige uma investigação aprofundada para entender as causas (sazonalidade, estoque, etc.).
  * **Segmentação de Produto:** A área lateral permite segmentar a análise rapidamente entre categorias principais (`Cachorrinho` e `Gato`) e aplicar filtros de ano, trimestre e mês.

## 🛠️ Tecnologias e Ferramentas

  * **Power BI Desktop:** Para desenvolvimento do modelo de dados e criação dos visuais.
  * **DAX (Data Analysis Expressions):** Utilizada para a criação de medidas e cálculos avançados (ex: Média de Pets, totalizações e filtros).
  * **Power Query (M):** Usado para a extração e transformação dos dados (ETL).
  * **Fonte de Dados:** Arquivos CSV de Vendas, Produtos e Clientes.

## ⚙️ Estrutura do Modelo

1.  **Transformação:** Limpeza de dados e padronização, remoção de colunas irrelevantes, mesclagem de tabelas, tratamento de datas
2.  **Modelagem (Diagrama Estrela/Floco):** O modelo é composto por uma Tabela Fato (Vendas) e tabelas de Dimensão (Clientes, Produtos), otimizando o desempenho das análises.

## 📄 Como Rodar o Projeto Localmente


1.  Instale o **Power BI Desktop** (download gratuito no site da Microsoft).
2.  Baixe o arquivo Gatitos.pbix deste repositório.
3.  Abra o arquivo.
4.  *Opcional:* Se os dados de origem não estiverem na pasta local, vá em `Transformar Dados` -\> `Configurações da Fonte de Dados` para reconfigurar a conexão.


*License: MIT License*
