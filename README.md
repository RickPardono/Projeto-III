# SISTEMA DE RECOMENDAÇÃO DE LIVROS


![image](https://github.com/RickPardono/Sistema-de-recomenda-o-de-livros/assets/124527157/748b923d-14e0-45cd-aedb-1fc54d7fc296)



O objetivo geral deste projeto é desenvolver um sistema de recomendação de livros utilizando a técnica de filtragem colaborativa baseada no algoritmo KNN. Para atingir o objetivo geral temos como objetivos específicos:

- Coletar, preparar e analisar dados sobre livros, usuários e classificações;

- Implementar o algoritmo KNN para gerar recomendações personalizadas;

- Avaliar a eficiência do sistema de recomendação por meio de métricas de qualidade.

A base de dados escolhida para o projeto foi extraída do repositório Kaggle em 04/03/24. Os dados são públicos, não sensíveis e foram coletados em sites de vendas de livros. Podem ser  acessados pelo link: https://www.kaggle.com/datasets/rxsraghavagrawal/book-recommender-system/data.
O conjunto de dados apresenta 3 arquivos no formato csv:

- BX-Book-Ratings.csv : informações relacionadas às classificações dos livros pelos usuários como ID do usuário, ID do livro e classificação do livro;

- BX-Books.csv : informações relacionadas aos livros como ID, título, autor, ano de publicação, editor, imagem url pequena, imagem url média e imagem url grande;

- BX-Users.csv : informações relacionadas aos usuários como ID do usuário, localização e idade.
