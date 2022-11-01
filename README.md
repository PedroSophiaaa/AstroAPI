<h1 align="center">Previsão de temperatura</h1>
<h2 align="center">Um estudo acima do comportamento climático de diversas regiões do globo</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/106617753/186216937-2f85a810-e537-4528-b7f2-cd966ed4784a.png", width=720px> </p>

<h2>Descrição</h2>
O projeto tem como objetivo prever três características climáticas em qualquer latitude do globo (utilizando a API fornecida pelo site WeatherStack), fixa a uma longitude de 20°, com base nos dados fornecidos por um limitado número de estações meteorológicas dispostas latitudinalmente.
Torna-se possível dispor graficamente e aplicar uma regressão polinomial para descrever o comportamento da temperatura, sensação térmica e descrição do clima, para que seja possível prever a determinada característica de maneira precisa.

O projeto foi elaborado por 4 estudantes do curso de Bacharelado em Ciência e Tecnologia, da ILUM - Escola de ciências, sendo eles:
- Pedro Henrique Sophia;
- João Pedro Aroucha de Brito;
- Pedro Thomazelli Ferreira;
- Victor Puntel Rui.

<h2>O processo</h2>

<h3>Bloco 1</h3>

- Coleta dos dados, de modo a selecionar aqueles que mais se adequassem à realização da previsão;
- Preparação dos dados, que consiste no mensuramento, caracterização e filtragem, de modo a definir um melhor conjunto para o modelo;
- Análise dos dados, seguida de uma discussão para concluir se os dados escolhidos resultaram como esperado;
- Análise sobre as estatísticas descritivas dos dados, a fim de encontrar a covariância das diferentes features - características que terão influência na previsão do modelo.

<h3>Bloco 2</h3>

- Divisão dos dados em treino e teste, para o desenvolvimento de uma baseline;
- Identificação e escolha dos hiperparâmetros, para que fosse possível fazer um modelo de "k" vizinhos mais próximos, fazendo sua avaliação e estudando seu desempenho;
- Execução da regressão linear, primeiramente sem normalização, seguido pelo modelo normalizado, além da avaliação de ambos;
- Escolha dos hiperparâmetros de acordo com a intuição, treinando um modelo de árvore de decisão, com base no dataset de treino, seguida pela avaliação;
- Alteração da complexidade do modelo, etudando seu desempenho de acordo com isso;
- Esboço da árvore de decisão;
- Agora, identifica-se os hiperparâmetros para o modelo de floresta aleatória, seguida pela avaliação do mesmo, mudando sua complexidade, tal qual foi feito anteriormente;
- Escolha do melhor hiperparâmetro;
- Comparação do desempenho dos modelos obtidos;
- Escolha de um algoritmo para sua classificação, hiperparâmetros, usando intuição, para terinamento do modelo e, por fim, avaliação do desempenho.

<h3>Bloco 3</h3>

- Redução de dimensionalidade e aplicação de PCA (análise de componente principal);
- Clustering, para encontrar grupos semelhantes;
- Detecção de outliers para melhor entendimento dos resultados obtidos, utilizando as técnicas:
  - LOF;
  - Insolation Forest.

<h3>Bloco 4</h3>

⚠️ Projeto em andamento ⚠️

<h2>Resultados</h2>
