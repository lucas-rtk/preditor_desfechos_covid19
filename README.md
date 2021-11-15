# Sumário
- [Contexto](https://github.com/lucas-rtk/preditor_desfechos_covid19#Contexto)
- [Técnicas](https://github.com/lucas-rtk/preditor_desfechos_covid19#Técnicas)
- [Ferramentas](https://github.com/lucas-rtk/preditor_desfechos_covid19#Ferramentas)
- [Iniciando o Jupyter Notebook](https://github.com/lucas-rtk/preditor_desfechos_covid19#Iniciando-o-Jupyter-Notebook)
- [Arquitetura do modelo](https://github.com/lucas-rtk/preditor_desfechos_covid19#Arquitetura-do-modelo)
- [Matriz de confusão](https://github.com/lucas-rtk/preditor_desfechos_covid19#Matriz-de-confusão)
- [Métricas de validação](https://github.com/lucas-rtk/preditor_desfechos_covid19#Métricas-de-validação)

# Contexto
Este repositório contém o modelo de Machine Learning e os scripts para tratamentos dos dados para o meu trabalho de conclusão da Unisinos. O processo se inicia com a união dos dados clínicos e laboratoriais reais de pacientes internados com COVID-19 no Hospital Getúlio Vargas de Sapucaia do Sul coletados no ano de 2020. Durante a união, os dados são filtrados para utilizamos apenas os primeiros 20 dias de coletas de cada paciente e é aplicada a técnica de OneHotEncoding para as características multivaloradas. Feito isto, é realizada a definição dos hiperparâmetros através do algoritmo GridSearch. Por fim, o modelo final é validado através de diversas métricas. O modelo final atingiu uma acurácia de 89,65% na predição do desfecho de pacientes após 20 dias de internação.

# Técnicas
- **OneHotEnconding**: Transformação de características multivaloradas em diversas características binárias.
- **Validação cruzada**: Técnica que divide o conjunto de dados completo em subconjuntos para validação dos modelos gerados.
- **GridSearch**: Técnica de validação dos hiperparâmetros do modelo para encontrar a melhor configuração para determinado conjunto de dados.

# Ferramentas
- **Python**: Linguagem de desenvolvimento utilizada.
- **Jupyter Notebook**: IDE para desenvolvimento e validação do modelo.
- **SKLearn**: Biblioteca para utilização dos algoritmos de Machine Learning.

# Iniciando o Jupyter Notebook
```
Jupyter notebook
```

# Arquitetura do modelo
![Arquitetura do modelo](/imagens/Arquitetura_modelo.png)

# Matriz de confusão
![matriz de confusão](/imagens/matriz_confusao.png)

# Métricas de validação
![Métricas de validação](/imagens/metricas.png)