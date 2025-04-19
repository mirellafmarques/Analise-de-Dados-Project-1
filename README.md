# Analise-de-Dados-Project-1

Este projeto utilizou dados do Sistema Integrado de Atendimento ao Cidadão (SIAC 156), disponíveis no portal de dados abertos da Prefeitura de Curitiba: https://www.curitiba.pr.gov.br/dadosabertos/busca/.
Os dados foram filtrados por assunto (invasão), exportados em formato CSV e geocodificados em lote por meio do Google My Maps (com limite de 2.000 pontos). Em seguida, o arquivo foi baixado em formato KMZ.
Para convertê-lo para o formato GeoJSON, o seguinte processo foi realizado:
Reexportação dos dados do Google Earth para o formato KML;
Abertura do arquivo KML no QGIS utilizando a extensão KML Tools;
Exportação final para o formato GeoJSON via QGIS.

As bibliotecas utilizadas nesta análise foram:
Geopandas;
Folium; e
Matplotlib.

