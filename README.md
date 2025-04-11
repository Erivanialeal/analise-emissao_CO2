# an-lise_emiss-o_CO2
Analise de Dados de Emissões de CO2.

## Objetivo:
Esse projeto de análise de dados tem como objetivo identificar os países que mais produziram e os que menos produziram CO2, além de explorar os fatores que influenciam negativamente o aumento ou contribuem para a diminuição da emissão de CO2. As análises serão simples e têm como propósito principal a prática de conceitos básicos dessa área, sendo este o meu primeiro contato com as bibliotecas pandas e matplotlib. Este projeto também visa aprimorar minha capacidade de estruturar e organizar arquivos de dados.

## Descrição dos conjuntos de Dados:
## Etapas da Análise:
 📂 2. Carregamento dos Dados:
  * Os Dados ultilizados nesse projeto foram obtidos de forma pública, no momento não me recordo o site exato de onde os dados foram baixados,mas os arquivos estão incluido na pasta `data`/`raw` deste repositório.
  Formato dos dados: .cvs
  Localização dos arquivos: .data/raw
  Script de carregamento: o carregamento dos dados é feito com a biblioteca pandas, conforme o exemplo abaixo:
  `import pandas as pd`
`df = pd.read_csv(r'C:\Users\eriva\OneDrive\Desktop\analise-emissao_CO2\data\raw\annual-co2-emissions-per-country.csv')`


🔎 3. Análise Exploratória:
 Nessa etapa foi feita uma análise premilinardos dados com objetivo de entender suas caractrísticas.
 df.head(): Indentifica as primeiras 5 linhas do DataFrame.
 df.info(): Ver o DataFrame como um todo, ex: colunas tipos de dados e memoria ultilizada.
 df.describe():Fornece uma análise estatístico de todas as colunas númericas
 df.isnull().sum(): Conta o número de evalores nulos em uma coluna númerica
 df['Code'].unique(): Retorna os valores nulos de uma unica coluna

📊 4. Visualização de Dados:

🔄 5. Limpeza de Dados:

📈 6. Análises Avançadas:

🏁 7. Conclusões:

## Ferramentas e Bibliotecas:
## Primeiras Observações:
Este DataFrame contem dados historicos sobre emissões anuais de CO2, Abaixo estão as principais características e insights iniciais:

* Estrutura do DataFrame.
    * Número total de registros: 29136
    * Número total de colunas: 4
    * Colunas disponíveis: 
        Entity: Nome dos país.
        Code: Codigo do país.
        Year: Ano da medição das emissões.
        Annual CO₂ emissions: Emissões anuais de CO₂, em valores numéricos.


