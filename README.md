# QUEIMADAS ![que01](https://github.com/user-attachments/assets/772e7629-ff78-43f8-99bb-5dfa81f705e7)

PROJETOS APRENDIZADO - Mapeamento de focos de incendios no brasil

Documentação: Análise e Visualização de Focos de Incêndio no Brasil  com enfaze em  Minas Gerais e São Paulo
Introdução
Esta documentação detalha o desenvolvimento de scripts em Python para análise e visualização de focos de incêndio nos estados de Minas Gerais e São Paulo. As ferramentas utilizadas incluem a biblioteca matplotlib para a criação de gráficos de dispersão e a biblioteca folium para a geração de mapas interativos.

Objetivo
O objetivo principal dos scripts é fornecer uma maneira simples e eficiente de visualizar a distribuição geográfica dos focos de incêndio em Minas Gerais e São Paulo, utilizando gráficos de dispersão e mapas interativos.

Estrutura dos Códigos
1. Importação de Bibliotecas
As bibliotecas utilizadas nos scripts são:

matplotlib.pyplot: Utilizada para a criação de gráficos de dispersão.
folium: Utilizada para a criação de mapas interativos.

2. Funções Desenvolvidas
2.1. Função plot_fire_data_mg(fire_data) e plot_fire_data_sp(fire_data)
Descrição:

As funções plot_fire_data_mg e plot_fire_data_sp são responsáveis por gerar um gráfico de dispersão que exibe a distribuição dos focos de incêndio nos estados de Minas Gerais e São Paulo, respectivamente.
Parâmetros:

fire_data: Um dicionário que contém uma lista de dicionários, onde cada dicionário representa um foco de incêndio com as chaves lat (latitude) e lon (longitude).
Funcionamento:

As funções iteram sobre os dados dos focos de incêndio, extraindo as coordenadas de latitude e longitude.
Em seguida, utiliza-se a função plt.scatter para criar o gráfico de dispersão.
O gráfico é configurado com um título, rótulos para os eixos, e uma grade para facilitar a visualização.

Descrição:

As funções generate_fire_map_mg e generate_fire_map_sp são responsáveis por gerar um mapa interativo que exibe os focos de incêndio nos estados de Minas Gerais e São Paulo, respectivamente.
Parâmetros:

fire_data: Um dicionário que contém uma lista de dicionários, onde cada dicionário representa um foco de incêndio com as chaves lat (latitude) e lon (longitude).
Funcionamento:

As funções centralizam o mapa nas coordenadas médias de cada estado e adicionam marcadores para cada foco de incêndio utilizando a função folium.CircleMarker.
Cada marcador inclui uma popup que exibe as coordenadas do ponto.

Considerações Finais
Os códigos desenvolvidos proporcionam uma maneira fácil e eficiente de visualizar focos de incêndio em Minas Gerais e São Paulo. A combinação de gráficos de dispersão e mapas interativos facilita a análise espacial e a tomada de decisões baseadas em dados geográficos.

Essas ferramentas podem ser expandidas e adaptadas para outros estados ou regiões, conforme necessário.
