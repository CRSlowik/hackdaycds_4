# Previsão de Cancelamento de Reservas em Hotéis
Este projeto tem como objetivo central a previsão de cancelamentos de reservas em hotéis, fazendo uso de técnicas avançadas de aprendizado de máquina. O repositório contém o código que guia desde o pré-processamento dos dados até a modelagem, permitindo realizar previsões precisas sobre cancelamentos futuros. A finalidade principal é oferecer à administração hoteleira insights preditivos para embasar decisões informadas.
      <p align="center"><strong><a href="https://www.kaggle.com/competitions/cdshackdays4?rvi=1">Mais detalhes </a></strong></p>

## Introdução
A rede hoteleira "Costa del Data Hotel", uma instituição tradicional na Espanha, confronta-se com uma inesperada onda de cancelamentos de reservas pós-pandemia de Covid-19. Nesse contexto, a empresa busca aproveitar a ciência de dados para compreender a fundo esse fenômeno e antecipar cancelamentos com precisão. O projeto concentra-se em desenvolver um modelo preditivo que possibilite à equipe de marketing direcionar estratégias a públicos específicos, minimizando perdas financeiras decorrentes de cancelamentos.

## Preparação dos Dados e Modelagem
O projeto se desenrola em duas etapas principais:
* Preparação dos Dados e Modelagem: Iniciamos carregando e pré-processando os dados de reservas de hotéis. Isso inclui lidar com valores ausentes, codificar variáveis categóricas e realizar transformações nas características dos dados. O objetivo é criar um conjunto de dados otimizado para alimentar os modelos de aprendizado de máquina.
* Modelagem: Nesta etapa, concentramos nossos esforços na construção e treinamento de três modelos de classificação: XGBoost, ExtraTrees e RandomForest. Cada modelo é treinado com base nos dados processados e é avaliado utilizando a métrica F1-score em um conjunto de validação. O modelo com o melhor desempenho será selecionado como nosso modelo final.

## Resultados e Conquistas
Após a conclusão das etapas de modelagem e avaliação, examinamos os resultados com detalhes significativos. O modelo com a pontuação F1-score mais alta é escolhido como nosso modelo final. Essa escolha permite que a equipe tome decisões informadas sobre cancelamentos de reservas, ajudando a adaptar as estratégias operacionais e financeiras do hotel. Ao oferecer previsões mais precisas, buscamos minimizar os impactos negativos dos cancelamentos e melhorar a eficácia das operações.
