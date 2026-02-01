Análise Estatística e Modelagem Preditiva com Python

Este projeto aplica técnicas de análise estatística e machine learning para identificar quais fatores influenciam resultados de desempenho. O objetivo é demonstrar como dados podem apoiar a tomada de decisão baseada em evidências, especialmente em contextos de gestão de pessoas e performance.

🎯 Objetivo do Projeto

Analisar dados de perfil profissional e construir um modelo preditivo capaz de estimar a probabilidade de um resultado positivo de desempenho com base em variáveis como experiência, salário, treinamentos e nível de satisfação.

🗂 Descrição da Base de Dados

O conjunto de dados contém variáveis quantitativas relacionadas ao desenvolvimento profissional e desempenho:

Variável	Descrição
Idade	Idade do profissional
Salario	Salário mensal
Anos_Experiencia	Anos de experiência profissional
Treinamentos_Ano	Número de treinamentos realizados no ano
Nivel_Satisfacao	Nível de satisfação (escala)
Resultado	Variável alvo (0 = Sem resultado positivo, 1 = Resultado positivo)
🔎 Etapas do Projeto
1️⃣ Análise Exploratória de Dados (EDA)

Análise da distribuição das variáveis numéricas

Identificação de padrões e possíveis outliers

Visualizações com histogramas, boxplots e mapa de calor

2️⃣ Análise Estatística

Comparação entre grupos utilizando teste t

Análise de correlação para entender relações entre variáveis

3️⃣ Modelagem Preditiva

Divisão dos dados em treino e teste

Padronização das variáveis com StandardScaler

Treinamento do modelo com Regressão Logística

4️⃣ Avaliação do Modelo

O desempenho foi avaliado utilizando:

Matriz de Confusão

Acurácia

Precisão e Recall

Curva AUC-ROC

📈 Principais Insights

Variáveis como nível de satisfação e quantidade de treinamentos apresentaram relação relevante com os resultados de desempenho.

Os testes estatísticos indicaram que as diferenças entre os grupos não ocorreram por acaso.

O modelo de regressão logística demonstrou capacidade de identificar padrões que ajudam a prever resultados.

🛠 Tecnologias Utilizadas

Python

Pandas

NumPy

Matplotlib & Seaborn

SciPy (testes estatísticos)

Scikit-learn (machine learning)

🎓 Contexto de Aprendizado

Este projeto foi desenvolvido como parte da minha jornada de aprendizado no curso
“Understanding and Visualizing Data with Python” – University of Michigan, onde aprofundei conhecimentos em visualização, interpretação de dados e análise estatística aplicada.

🚀 Como Executar o Projeto

Clone este repositório

Instale as bibliotecas necessárias:

pip install pandas numpy matplotlib seaborn scipy scikit-learn


Abra o notebook:

jupyter notebook


Execute as células para reproduzir a análise e o modelo

👩🏻‍💻 Autora

Sarah Zanardi
Dados & Analytics | Business Intelligence | Estatística & Machine Learning

🔗 Projeto:
👉 https://github.com/SarahZanardi/Modelagem-Preditiva-Aplicada
