# Pesquisa-cognitiva-Azure
Passo a passo para realizar uma pesquisa cognitiva com Azure

Pesquisa cognitiva 


Para que a Azure Cognitive Search seja efetiva devemos 3 passos:

-Ingestão de dados
Incluir os dados que sua pesquisa será direcionada.

-Enriquecimento e índice de IA
Agrupar e vetorizar os dados para uma compreensão mais profunda

-Explorar dados
Os dados devem ser informados em formatos Json, com isso é possível realizar uma pesquisa em índices, dentro de aplicativos e criar visualização de dados.


1 - Criar novo Azure AI Search
2 - Select Pricing Tier - Basic, seguir com Review + create
4 - Criar um novo recurso AI + Machine Learning selecionar em Azure AI Services, seguir com Review + create
5 - Criar uma conta de armazenamento em Storage account seguir com Review + create
necessário predeterminar os tipos de armazenamento (containers, arquivos, tabelas, filas...)
6 - Importar os dados fazendo Upload, seleciona-los no Storage account
7 - Em AI Search temos o mecanismo de pesquisa, podemos utilizar vários filtros durante a busca.
