# Análise Temporal de Vazão Hídrica

Este repositório contém o código para a análise temporal de dados de vazão de estações fluviométricas, utilizando o teste de Mann-Kendall para detectar tendências e a identificação de eventos extremos com base no percentil 95.

## Objetivo

Este estudo visa analisar séries temporais de vazão hídrica ao longo de várias estações de monitoramento, identificando tendências e eventos extremos que possam impactar a gestão de recursos hídricos.

## Estrutura do Código

1. **Instalação de Pacotes Necessários**: O código utiliza os pacotes `pymannkendall`, `tqdm` e `matplotlib`.
2. **Carregamento dos Dados**: Os dados de vazão são carregados de arquivos CSV.
3. **Pré-processamento**: O código realiza interpolação linear para preencher falhas nos dados.
4. **Teste de Mann-Kendall**: Aplica o teste de Mann-Kendall para detectar tendências.
5. **Geração de Gráficos**: Os gráficos são gerados e exibidos diretamente no Google Colab, com as informações do teste de Mann-Kendall.

## Instruções para Execução

1. Suba seus arquivos CSV contendo as séries temporais de vazão para o Google Drive.
2. Certifique-se de que o caminho de entrada (`INPUT_DIR_LOCAL`) esteja configurado corretamente.
3. Execute o código no **Google Colab**.
4. Verifique os gráficos gerados diretamente no Colab ou baixe os resultados da pasta `OUTPUT_DIR_LOCAL` no Google Drive.

## Requisitos

- Python 3.x
- Bibliotecas: `pymannkendall`, `tqdm`, `matplotlib`, `pandas`, `numpy`

## Licença

Este código está disponível sob a [Licença MIT](LICENSE).
