# Machine Learning - Ensaio de Algoritmos

## Data Science Project - Ensaio de Algoritmos de Machine Learning

<div align='center'>

![algorithms_essay](https://github.com/caiomichelan/machine_learning-algorithms_essay/assets/104601836/5810a6c6-ff04-4b3d-b962-4b9c2ae0718b)

</div>

# 1. Problema do Negócio
<p align='justify'>Uma grande empresa do ramo de Consultoria de Análise e Ciência de Dados fornece serviços para grandes empresas do Brasil, Estados Unidos e Holanda.</p>
<p align='justify'>Seu principal diferencial no mercado é o alto retorno financeiro às empresas clientes devido à performance de seus algoritmos de Machine Learning. Os executivos da empresa acreditam que a expertise no treinamento e ajuste fino dos parâmetros dos algoritmos, tarefa realizada pelos Cientistas de Dados, é o principal motivo dos ótimos resultados entregues aos clientes.</p>
<p align='justify'>A fim de continuar oferecendo produtos de qualidade que agregam valor ao cliente, foi solicitado que a equipe de dados realize testes e validações em algoritmos de Machine Learning que a empresa pretende dar um foco maior em suas implementações, visando entender melhor sobre seu funcionamento, aumentar a experiência na aplicação dos mesmos e avaliar os cenários e suas respectivas performances de modo a identificar a melhor escolha a cada situação e problema a ser resolvido.</p>
<p align='justify'>Desta forma, foi dado o desafio de ensaio, testes e avaliação de algoritmos de Classificação, Regressão e Clusterização a fim de adquirir aprendizado sobre o funcionamento de cada algoritmo e disseminar o conhecimento entre todas as equipes envolvidas na área.</p>

# 2. Premissas do Negócio
<p align='justify'>Para maior assertividade nos resultados, foram considerados dados pré processados, sendo dados de treino, teste e validação.</p>

# 3. Estratégia da Solução
<p align='justify'>Apesar dos dados já estarem previamente processados e não haver necessidade de análises robustas para entendimento dos mesmos, foi utilizada a metodologia CRISP-DM no desenvolvimento do projeto, através das seguintes etapas:</p>
<p align='justify'>- Business Understanding: Definição dos objetivos do projeto e entender as necessidades do negócio e identificar os problemas a serem solucionados e as oportunidades a serem exploradas. Nesta etapa foi avaliado que o objetivo principal do projeto se tratava de um estudo com testes de avaliação de algoritmos de Machine Learning a fim de adquirir conhecimento sobre os mesmos.</p>
<p align='justify'>- Data Understanding: Coleta, descrição e exploração dos dados relevantes para o projeto, bem como avaliação da qualidade, consistência e confiabilidade destes dados. Para este projeto não houve necessidade de implementação desta etapa, já que o propósito principal é a validação e aprendizado sobre os algoritmos e, como premissa, os dados já estavam prontos para processamento.</p>
<p align='justify'>- Data Preparation: Limpeza, transformação e formatação dos dados para a análise, bem como tratativa de dados ausentes, inconsistentes ou outliers e seleção das variáveis relevantes para o modelo de Machine Learning. Assim como na etapa anterior, não houve implementação desta etapa devido à premissa de negócio para este projeto.</p>
<p align='justify'>- Modelling: Escolha e aplicação de técnicas de Machine Learning adequadas ao problema, juntamente com treinamento e avaliação de diferentes modelos para seleção do melhor desempenho. Também consiste na otimização dos parâmetros dos modelos para obter a melhor performance. Realizada a definição e treinamento dos modelos de Classificação, Regressão e Clusterização com base nos dados propostos.</p>
<p align='justify'>- Evaluation: Validação dos modelos em um conjunto de dados de teste independente. Nesta etapa foram avaliados todos os modelos definidos e treinados na etapa anterior afim de adquirir conhecimento, avaliar suas performances e concluir o estudo sobre a aplicação e implementação dos mesmos nos conjuntos de dados pré definidos.</p>
<p align='justify'>- Deployment: Implementação do modelo de Machine Learning na aplicação real, bem como monitoramento de seu desempenho em produção e realização de ajustes quando necessário. Esta etapa não foi implementada devido ao objetivo principal do projeto.</p>
<p align='justify'>Algorimos utilizados neste projeto:</p>
<p align='justify'>- Classificação: K-Nearest Neighbors (KNN) / Decision Tree Classifier / Random Forest Classifier / Logistic Regression.</p>
<p align='justify'>- Regressão: Linear Regression / Decision Tree Regressor / Random Forest Regressor / Polynomial Regression / Linear Regression Lasso / Linear Regression Ridge / Linear Regression Elastic Net / Linear Regression RANSAC / Polynomial Regression Lasso / Polynomial Regression Ridge / Polynomial Regression Elastic Net / Polynomial Regression RANSAC.</p>
<p align='justify'>- Clusterização: K-Means / Affinity Propagation.</p>
<p align='justify'>É importante ressaltar que algumas etapas do método CRISP-DM não foram efetivamente consideradas neste projeto, já que a premissa indica que os dados estavam prontos para aplicação dos modelos de Machine Learning. Nos próximos passos deverão ser realizadas análises mais robustas com este método, a fim de obter possíveis insights que auxiliarão no entendimento dos resultados obtidos.</p>

# 4. Insights de Dados
<p align='justify'>Alguns insights obtidos através dos testes de validação:</p>
<p align='justify'>- Algoritmos de Classificação: Para todos os algoritmos testados, os resultados entre os dados de Validação e Teste se apresentaram em conformidade, com valores bem próximos, comprovando a eficácia dos modelos produzidos.</p>
<p align='justify'>- Algoritmos de Regressão: Considerando a gama de algoritmos testados, também foi observado que os dados de Validação e Teste apresentaram uma certa correlação nas métricas de performance, indicando que os modelos se provaram eficazes frente aos dados utilizados no projeto.</p>
<p align='justify'>- Algoritmos de Clusterização: Avaliando os dois algoritmos testados, foi notada uma diferença considerável no número de clusters indicado para cada um. Enquanto o K-Means considerou 8 clusters como ideais ao modelo, o Affinity Propagation considerou apenas 4 clusters. Para este caso será realizada uma análise mais aprofundada nos próximos passos, a fim de validar qual algoritmo apresenta melhor eficácia frente aos dados considerados.</p>

# 5. Produto Final
<p align='justify'>Com base nos dados previamente processados, foram desenvolvidos diversos modelos de Machine Learning considerando algoritmos de Classificação, Regressão e Clusterização, com o objetivo de estudar e avaliar suas respectivas performances frente a cada modelo utilizado, identificar padrões e futuramente fornecer à equipe de negócio insights relevantes através da implementação destes modelos.</p>

# 6. Conclusão
<p align='justify'>O objetivo do projeto foi desenvolver um estudo com o ensaio de diversos modelos de Machine Learning voltados a Classificação, Regressão e Clusterização em dados previamente processados.</p>
<p align='justify'>Com a implementação dos modelos propostos, foi validada a possibilidade de utilização destes para a resolução dos problemas de negócio da organização.</p>
<p align='justify'>Com base nos resultados apresentados, foi possível entender o funcionamento dos algoritmos utilizados e observar uma correlação entre os dados de Validação e Teste nos algoritmos de Classificação e Regressão de maneira apartada, avaliando suas performances e fornecendo insights para atuação da equipe de negócio quanto às suas regras, bem como prover conhecimento aos cientistas de dados sobre sua utilização e otimização de parâmetros em próximas etapas.</p>

# 7. Próximos Passos
<p align='justify'>Como próximos passos serão definidas análise mais robustas do método CRISP-DM, já que para este projeto suas principais etapas de análise não foram consideradas devido à premissa de negócio.</p>
<p align='justify'>Também será realizada uma análise mais aprofundada sobre os algoritmos de Clusterização para identificar o melhor modelo indicado, bem como o motivo da diferença apresentada nos resultados obtidos.</p>
<p align='justify'>Por fim será definido um cronograma de testes a todos os algoritmos considerados no projeto com a implementação de técnicas de Fine Tuning, que consistem em refinar e otimizar os modelos pré treinados, para possivelmente obter melhores resultados.</p>
