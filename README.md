# Sistema de Recomendação de Livros e-LYTER


![image](https://github.com/RickPardono/Sistema-de-recomenda-o-de-livros/assets/124527157/748b923d-14e0-45cd-aedb-1fc54d7fc296)



O objetivo geral desse projeto é desenvolver um Sistema de Recomendação de livros utilizando técnica de filtragem colaborativa e algoritmo Singular Value Decomposition (SVD).  Para atingir o objetivo geral temos como objetivos específicos:

- Coletar, preparar e analisar dados sobre livros, usuários e classificações;

- Dividir os dados em conjunto de treinamento e teste;

- Realizar a validação cruzada e otimização de parâmetros com GridSearchCV para avaliar o desempenho do modelo em diferentes divisões de dados usando as métricas de desempenho Root Mean Square Error (RMSE) e Mean Absolute Error (MAE);

- Treinar o modelo usando o conjunto de treinamento;

- Verificar a precisão das previsões usando o conjunto de teste e as métricas de desempenho RMSE e MAE;

- Implementar o Sistema de Recomendação.

A base de dados escolhida para o projeto foi extraída do Github em 04/03/24. Os dados são públicos, não sensíveis e foram coletados em sites de resenhas e vendas de livros. Podem ser acessados pelo link: https://github.com/zygmuntz/goodbooks-10k.
O conjunto de dados apresenta 3 arquivos no formato csv:

- books.csv : informações sobre o ID do livro, ID na plataforma Goodreads, ID no site Best Reads, ID do livro em Banco de Dados central, número de versões, International Standard Book Number (ISBN), nome(s) do(s) autor(es), nome do livro original, nome do livro, código do idioma, média das avaliações, número total de avaliações, número de resenhas escritas do livro, número de avaliações de nota 1 a 5, url da imagem da capa, url da imagem da capa do livro em tamanho menor;

- ratings.csv : informações relacionadas ao ID do usuário, ID do livro e avaliação do livro pelo usuário.

O modelo SVD final apresentou resultados significativamente superiores aos modelos comparativos, como o KNN e o próprio SVD configurado com os parâmetros básicos.

