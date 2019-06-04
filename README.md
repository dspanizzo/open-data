# Open-Data

Uma série de python notebooks para auxiliar no desenvolvimento de programas para preparação de fontes de dados abertas.

## Processo

O processo de preparação dos dados está dividido em quatro etapas:

1. Coletar: Cria as pastas para armazenar e gerenciar o processo de preparação dos dados, estabelece as conexões com a fonte de dados ou API e faz a aquisição dos dados.
2. Limpar: Os dados adquiridos são convertidos para UTF-8 e caracteres especiais são removidos ou substituídos.
3. Organizar: Após a limpeza, os dados são estruturados em formato tabular (quando aplicável) e as colunas recebem novos nomes conforme as regras do dicionário de dados (em definição).
4. Padronizar: Ao final são aplicadas as transformações necessárias para padronizar as estruturas de dados e lidar com campos em branco.

Seguindo a lógica destas quatro etapas, cada uma das fontes de dados coletada possui a seguinte estrutura de arquivos e pastas:

- data
  - 01-collected
  - 02-cleaned
  - 03-organized
  - 04-standardized
  
- scripts
  - 01-data-collector.ipynb
  - 02-data-cleaner.ipynb
  - 03-data-organizer.ipynb
  - 04-data-standardizer.ipynb
