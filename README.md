# IAII_SistemasEspecialistas

Este código cria um sistema simples para recomendar serviços de streaming 
baseado nas preferências do usuário de tipo de conteúdo e custo.

A base de conhecimento do sistema inclui uma lista de serviços de streaming
organizados por tipo de conteúdo que oferece (por exemplo, documentários, 
séries ou filmes) e preço (por exemplo, moderado ou acessível). O sistema 
pode organizar e identificar rapidamente os serviços que atendem a critérios
específicos graças a essa estrutura.

Em seguida, o código estabelece regras de recomendação. Cada regra estabelece
um requisito que combina um tipo de conteúdo e um nível de preço, e conecta 
esses requisitos a uma lista de serviços de streaming recomendados. Por exemplo,
se a condição for "Documentários" e o preço for "Acessível", os serviços como 
"Discovery Plus" e "HBO MAX" podem ser recomendados.

Por fim, as entradas interativas ajudam o programa principal a coletar as preferências
do usuário. O sistema cria uma lista de serviços de streaming recomendados com base no
tipo de conteúdo que o usuário prefere e no orçamento. O sistema informa ao usuário que
não há recomendações disponíveis para essas configurações se nenhuma regra atender às 
preferências especificadas.
