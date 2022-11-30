# <center>Medidas de Dispersão</center>

## Introdução 🩼

O resumo de um conjunto de dados por uma única medida representativa de posição central esconde toda a informação sobre a variabilidade dos dados. Para obtermos informações sobre a variabilidade dos dados, utilizamos outras medidas estatísticas chamadas de medidas de dispersão.

As medidas de dispersão são medidas estatísticas que tentam quantificar a dispersão dos dados em relação a sua média ou mediana. As medidas de dispersão são: *desvio médio absoluto* ou apenas *desvio médio*, *variância*, *desvio padrão* e *coeficiente de variação* ou *desvio padrão relativo*.

**Algumas observações em relação aos símbolos utilizados**

- $\sigma^2$ ↦ População (Variância)

- $S^2$ ↦ Amostra (Variância)

- $\sigma$ ↦ População (Desvio Padrão)

- $S$ ↦ Amostra (Desvio Padrão)

## Desvio Médio Absoluto ou Desvio Médio

Em estatística, o desvio médio ou desvio médio absoluto dos elementos de um conjunto de dados é a diferença absoluta entre os elementos do conjunto de observações e o ponto do qual o desvio é medido, mais frequentemente a mediana ou algumas vezes a média. 

### $$dm(X) = \frac{\sum_{i=1}^n|x_i - \bar{x}|}{n}$$

## Variância ⚗️

Na estatística, a variância de uma variável aleatória é uma medida da sua dispersão estatística, indicando "o quão longe" em geral os seus valores se encontram do valor esperado. A obtênção dessa medida estatística se da pela seguinte fórmula:

### $$\sigma^2 = \frac{\sum_{i=1}^N(x_i - \bar{x})^2}{N}$$

### $$S^2 = \frac{\sum_{i=1}^N(x_i - \bar{x})^2}{N-1}$$

## Desvio Padrão 🦊

A variância é uma medida estatística muito útil, porem quando usamos o cálculo associado à alguma unidade de medida, como por exemplo metros ($m$), segundos ($s$) ou massa ($kg$), elevamos essas unidades ao quadrado e isso dificulta a interpretação dos resultados. Para esses casos utilizamos outra medida estatística chamada de desvio padrão, dada pela seguinte fórmula:

### $$\sigma = \sqrt{\frac{\sum_{i=1}^N(x_i - \bar{x})^2}{N}}$$

### $$S = \sqrt{\frac{\sum_{i=1}^N(x_i - \bar{x})^2}{N-1}}$$

## Coeficiente de Variação 🐐

O coeficiente de variação ou desvio padrão relativo é uma medida relativa de variabilidade que permite a comparação da dispersão de duas características diferentes. É utilizada para comparar em termos relativos o grau de concentração dos dados em torno da média de séries distintas.

### $$C_v = \frac{\sigma}{\bar{X}}$$

### $$C_v = \frac{S}{\bar{X}}$$
