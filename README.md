<h1 align="center">Previsão de temperatura</h1>
<h2 align="center">Um estudo acima do comportamento climático de diversas regiões do globo</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/106617753/186216937-2f85a810-e537-4528-b7f2-cd966ed4784a.png", width=720px> </p>

<h2>Descrição</h2>
O projeto tem como objetivo prever três características climáticas em qualquer latitude do globo (utilizando a API fornecida pelo site WeatherStack), fixa a uma longitude de 20°, com base nos dados fornecidos por um limitado número de estações meteorológicas dispostas latitudinalmente.
Torna-se possível dispor graficamente e aplicar métodos de regressão para descrever o comportamento da temperatura, sensação térmica e descrição do clima da maneira mais precisa possível.

O projeto foi elaborado por 4 estudantes do curso de Bacharelado em Ciência e Tecnologia, da ILUM - Escola de ciências, sendo eles:
- Pedro Henrique Sophia;
- João Pedro Aroucha de Brito;
- Pedro Thomazelli Ferreira;
- Victor Puntel Rui.

<h2>Links importantes</h2>
<li><a href = "NoteBook_Resultado.ipynb"> Notebook com os melhores resultados;</a></li>
<li><a href = "Notebooks"> Pasta com os notebooks parciais utilizados no desenvolvimento do trabalho;</a></li>
<li><a href = "Dados Real.zip"> Dados utilizados para a execução do código.</a></li>

<h2>O processo</h2>

O projeto desenvolvido pode ser visto como dividido em algumas etapas. Primeiro, houve a coleta dos dados, de modo a serem escolhidos aqueles que mais se adequassem ao projeto. Além disso, foram preparados os dados, feito o mensuramento, caracterização e filtragem dos mesmos, definindo o melhor conjunto a ser usado. A partir disso, foi feita análise para determinar se os dados escolhidos apresentariam os resultados esperados, seguida de uma outra análise para determinar as features a serem usadas.

Agora, nessa segunda etapa, a primeira coisa a ser feita era desenvolver uma baseline,o que foi feito a partir da divisão de dados em treino e teste; feito isso, escolhemos os autoparâmetros a serem usados, fazendo o modelo de "k" vizinhos. Com isso, feito, seguimos para a execução da regressão linear, que foi feita com e sem normalização dos dados, possibilitando uma melhor avaliação dos dados. Então, escolhendo hiperparâmetros por intuição, buscamos treinar o modelo de árvore de decisão, que foi avaliado na sequência, sendo feito o esboço da árvore de decisão. Após as avaliações feitas e a mudança da complexidade dos modelos, foi possível determinar o melhor hiperparâmetro a ser usado, que em seguida foi comparado com os demais modelos já existentes. Por fim, escolhemos um algoritmo para a classificação dos hiperparâmetros. usando, novamente, intuição, seguido da avaliação desse.

Para a terceira etapa, fizemos,primeiramente, a redução de dimensionalidade e aplicação de PCA (análise de componente principal), seguido do clustering, buscando encontrar grupos semelhantes. Com isso em mãos, fizemos a detecçõa de outliers, visando o melhor entendimento dos resultados obtidos, com as técnicas de LOF e Isolation Forest.

Finalmente, na última etapa, foram feitos os outliers, achando dados que distoam muito da curva encointrada, sendo avaliados depois.

<h2>Conclusão</h2>
Em conclusão, o trabalho desenvolvido para a matéria de Aprendizado de Maquina para previsao de temperatura e sensação térmica teve sucesso acima do esperado. Foram destacados possíveis modelos e métodos que podem ser utilizados para previsão destes dois objetivos a partir dos dados passados. No desenvolvimento do projeto, os alunos conseguiram fazer previsões moderadas com vários dos modelos, destancando-se dentre eles alguns modelos que foram de extrema importância para a continuação do projeto e para que fosse possível fazer previsões muito próximas da realidade.

