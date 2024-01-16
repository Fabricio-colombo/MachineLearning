Projeto Python IA: Inteligência Artificial e Previsões

Bem-vindo ao projeto Python IA: Inteligência Artificial e Previsões. Neste projeto, desenvolvemos um modelo para determinar o score de crédito dos clientes de um banco. O objetivo é criar um sistema capaz de analisar informações dos clientes e classificar automaticamente o score de crédito como Ruim, Ok ou Bom.

Estrutura do Projeto
clientes.csv: Arquivo contendo dados históricos dos clientes, utilizado para treinar o modelo.
ia.ipynb: Notebook Jupyter com o código principal do projeto.
inicial.ipynb: Notebook Jupyter com códigos iniciais e experimentações.
novos_clientes.csv: Arquivo contendo dados de novos clientes para os quais faremos previsões.

O projeto de Inteligência Artificial tem como objetivo desenvolver um modelo de previsão de crédito para um banco. Utilizando dados históricos de clientes presentes no arquivo "clientes.csv", realizamos a preparação e treinamento do modelo com o auxílio das bibliotecas Pandas e Scikit-Learn. Implementamos algoritmos como RandomForestClassifier e KNeighborsClassifier, alcançando uma acurácia de aproximadamente 82.51% e 73.24%, respectivamente. O pré-processamento envolveu a codificação de variáveis categóricas e a separação dos dados em conjuntos de treino e teste. Além disso, fizemos previsões para novos clientes contidos no arquivo "novos_clientes.csv". Ao analisar a importância das features, destacamos que a "divida_total" e o "mix_credito" são fatores significativos no processo de decisão do modelo. Este projeto representa uma aplicação prática de I.A. no setor financeiro, proporcionando uma ferramenta valiosa para avaliação automática de crédito.
