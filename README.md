# ifood---case-tecnico
Case Técnico de Data Analysis - iFood

# Instruções de Execução – Notebook Databricks
## Visão Geral
Este notebook tem como objetivo analisar os resultados da campanha de cupons com foco na retenção de clientes.

## Pré-requisitos
Antes de executar o notebook, certifique-se de que:
- Você tem acesso ao workspace do Databricks.
- Um cluster está criado e ativo.
- O notebook foi importado para seu workspace.

## Etapas de Execução

1. **Acesse o notebook**  
   Link direto: [Abrir notebook no Databricks](https://dbc-24762493-8a34.cloud.databricks.com/editor/notebooks/307249932367585?o=635955167482653)

2. **Conectar o notebook a um cluster ativo**  
   No topo da interface, selecione um cluster disponível no menu suspenso.

3. **Importar o arquivo ‘ab_test_ref.csv’**  
   Antes de executar o Notebook, importar o arquivo ‘ab_test_ref.csv’, em anexo, através do Catalog. 
  No Catalog, clique no botão “+” no canto superior esquerdo, próximo a engrenagem, e arraste o arquivo para criar a tabela com o nome ‘workspace.default.ab_test_ref’.

4. **Execute as células sequencialmente**  
   - Para executar célula por célula: clique na célula e pressione `Shift + Enter`.
   - Para executar tudo de uma vez: clique em `Executar tudo` no topo do notebook.

5. **Acompanhe os resultados**  
   As tabelas gerados mostrarão os indicadores de retenção, uso de cupons e segmentações analisadas.

## Saídas Esperadas
- Tabela com os resultados comparativos entre os grupos do teste A/B.
- Indicadores necessários para análise e para a criação do Excel ‘Memória de Cálculo – Análise.xlsx’

## Última atualização
Junho de 2025
