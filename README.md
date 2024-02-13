## Pre-requisitos
Para criação e utilização de um serviço cognitive search, são necessários a criação e configuração de 3 serviços:
- **Azure AI Search**;
  - Prove o mecanismo de indexação dos arquivos utilizados como insumo para análise AI e também mecanismo de consulta/query.
- **Azure AI Service**;
   - O serviço em si que prove outros serviços mecanismos para análise de sentimento,. identificação de termos chaves, analise de imagens, etc.
- **Azure Storage Account**;
  - Repositório que serve tanto para ser uma origem dos arquivos como também armazenamento dos resultados de pesquisa realizada pelo serviço de AI.

![image](https://github.com/philipp-moreira/dio-ai900-cognitive-search/assets/17642499/08f5d244-a3b4-4307-b485-0c1396dbeb01)

## Utilização

Através do serviço de Ai Search
![image](https://github.com/philipp-moreira/dio-ai900-cognitive-search/assets/17642499/66fdd90e-47ec-4922-9340-f0a85a870bab)

Podemos ter acesso ao mecanismo de pesquisa/query, através da opção [Search Explorer]
![image](https://github.com/philipp-moreira/dio-ai900-cognitive-search/assets/17642499/8cdb26b7-f7c3-4d27-98d2-7a22c9422b21)

Neste tela temos a opção de realizar pesquisas de duas formas:
![image](https://github.com/philipp-moreira/dio-ai900-cognitive-search/assets/17642499/f6d3a915-9a1d-476f-b94e-8489b2e048df)

- Através de Query View
  ![image](https://github.com/philipp-moreira/dio-ai900-cognitive-search/assets/17642499/da260565-cc2d-45bb-a251-a5903b9dd63f)

- Através de Json View
  ![image](https://github.com/philipp-moreira/dio-ai900-cognitive-search/assets/17642499/06112884-c972-4d2f-b2d7-b6d32be47c15)

Todas as consultas serão implicitamente aremazenadas no serviço de storage account

Tanto nos conteiners
![image](https://github.com/philipp-moreira/dio-ai900-cognitive-search/assets/17642499/0916f42e-9e66-40ab-91b9-82ff75e6d1c7)

Como também na seção de tables, com a ressalva que aqui fica mais visivel a configuração de indexadores configurados no serviço de AI Search,
onde podemos observar, por exemplo a indexação por termos chaves, entidades, etc.
![image](https://github.com/philipp-moreira/dio-ai900-cognitive-search/assets/17642499/48452fb3-32aa-4f3c-951c-260fcd9a448f)
