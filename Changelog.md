# Changelog

Todas as mudanças relevantes ao projeto serão documentadas neste arquivo.

Este arquivo segue [este](https://keepachangelog.com/en/1.0.0/) formato de Changelog do "Keep a Changelog", e a semântica de versionamento utilizada é apresentada [aqui](https://semver.org/spec/v2.0.0.html).

## [não_lançado]

## [1.0.0] - 2023-02-22

### Adicionado 
- Arquivo de Changelog indicando as primeiras alterações do projeto.
- Arquivo base CSV "la-haute-borne-data-2013-2016.csv", baixado diretamente do [site](https://opendata-renewables.engie.com/explore/dataset/d543716b-368d-4c53-8fb1-55addbe8d3ad/information) da "La Haute Borne Data".

### Alterado
- Conversão do arquivo base de CSV para parquet, uma vez que o arquivo CSV levava 30s para leitura com o pandas.

### Removido
- Arquivo base em CSV.