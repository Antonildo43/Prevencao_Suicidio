##Projeto Prevenção de Suicídio

Neste projeto trabalho com um tema relevante para a sociedade e ao mesmo tempo demonstrarei minhas habilidades em Machine Learning. Para esta tarefa, utilizo um conjunto de dados disponibilizado publicamente no Kaggle, extraido de postagens dos subreddits "SuicideWatch" e "depression" da plataforma Reddit. O Reddit é uma plataforma preferida por pessoas com problemas emocionais, por isso fornece pistas significativas para o suicídio.

As postagens foram coletadas usando a API Pushshift. Todas as postagens feitas para "SuicideWatch" foram coletadas de 16 de dezembro de 2008 (criação) até 2 de janeiro de 2021 , enquanto as postagens de "depression" foram coletadas de 1 de janeiro de 2009 a 2 de janeiro de 2021.

Créditos para Nikhileswar Komati por coletar e disponibilizar as informações na plataforma Kaggle.

Para realizar este trabalho utilizei a seguinte estratégia:

1. Extrair os dados dos textos das postegens e aprender as word embeddings.
2. Extrair conjuntos randômicos de documentos dos word embeddings já treinados.
3. Preparar os dados para os modelos de treinamento e avaliação doc2Vec
4. Construir o vocabulário através de um modelo doc2vec - Distributed Bag of Words (DBOW)
5. Aplicar um modelo de Regressão Logística para classificação
6. Apresentar ao modelo dados não envolvidos no processo de treinamento e teste para validar a capacidade do modelo classificar corretamente as postagens.
