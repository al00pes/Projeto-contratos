# Análise de Processos de Contratação

## Descrição

Este projeto tem como objetivo realizar uma análise de processos de contratação realizados pelo setor de **Purchasing**. A análise foi conduzida utilizando **Python** para manipulação e tratamento dos dados, e o **Power BI** foi utilizado para a construção de um dashboard interativo. 

Os dados fornecidos continham as seguintes informações:

- **Código do Projeto**
- **Área**
- **Data de Publicação ao Mercado**
- **Data de Avaliação Técnica**
- **Data de Avaliação Comercial**
- **Data de Premiação**
- **Data de Assinatura de Contrato**
- **Budget** (orçamento estimado)
- **Valor Fechado** (valor final acordado)
- **Saving** (economia gerada)

## Ferramentas Utilizadas

- **Python**: Para realizar o tratamento, limpeza e análise dos dados.
- **Power BI**: Para a criação de um dashboard que apresenta visualmente os principais insights e KPIs extraídos dos dados.

## Etapas do Projeto

1. **Importação e Limpeza de Dados**: 
   - A base de dados foi carregada utilizando bibliotecas como `pandas` e `numpy` para garantir a manipulação eficiente.
   - Foram tratadas inconsistências como valores ausentes e formatos inadequados de data.

2. **Análise de Dados**:
   - Foram calculados KPIs importantes como a diferença entre o **Budget** e o **Valor Fechado** para determinar o **Saving** gerado em cada processo de contratação.
   - Também foi feita uma análise das datas para medir o tempo de execução de cada fase do processo (da publicação ao mercado até a assinatura do contrato).

3. **Visualização dos Dados**:
   - O dashboard no Power BI apresenta métricas como:
     - Total de **Saving** gerado
     - Comparação entre **Budget** e **Valor Fechado** por área
     - Tempo médio de conclusão dos processos de contratação
   - Gráficos interativos permitem uma visão detalhada por área ou projeto.

## Conclusão

Este projeto demonstrou como é possível utilizar **Python** para manipulação eficiente de dados e **Power BI** para construir dashboards dinâmicos,
permitindo uma visualização clara e acessível dos resultados da análise de processos de contratação.
