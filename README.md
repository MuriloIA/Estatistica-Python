# <center>Medidas de Posição ou Medidas de Tendência Central</center>

Medidas de posição são medidas estatísticas que nos permitem representar de forma resumida um conjunto de dados relacionados a um determinado fenômeno.

##  Medidas de Posição Para Dados Não Agrupados  🐏

### Média

Seja $X$ a variável de estudo, $x_i$ representa o valor observado na n-ésima unidade experimental e $\bar{X}$ é a sua média. Quando os dados são não agrupados a sua média é dada pela soma de todos os elementos dividido pelo número de elementos.

### $$\frac{1}{n}\sum_{i=1}^nx_i$$

### Mediana

A mediana ($M_e$ ou $M_d$) de uma variável $X$ é dada pelo valor que divide o conjunto de dados ao meio, ou seja, é o valor (do próprio conjunto ou teórico) que tem antes e depois de si igual quantidade de dados.

### $$M_d(X) = X_{(\frac{n + 1}{2})}, ímpar$$

### $$M_d(X) = \frac{X_{(\frac{n}{2})}+X_{(\frac{n}{2}+1)}}{2}, par$$

### Moda 

A moda $M_o$ de uma variável $X$ é o valor que mais se repete no conjunto de dados.

$M_o$ - valor que maior $f_i$

## Medidas de Posição Para Dados Agrupados Sem Intervalo de Classe  🐝

### Média

Seja $X$ a variável em estudo, $x_i$ representa o valor observado da variável na n-ésima experimental e $\bar{X}$ é a sua média.

### $$\bar{X} = \frac{\sum f_ix_i}{\sum fi}$$

### Mediana

A mediana ($M_e$) de uma variável $X$ é dada pelo valor que divide o conjunto de dados ao meio, ou seja, é o valor (do próprio conjunto ou teórico) que tem antes e depois de si igual quantidade de dados. No caso de dados agrupados sem intervalo de classe, precisamos calcular a frequência acumulada ($F_ac$) e o valor $\frac{n}{2}$ o qual divide o conjunto de dados ao meio. Busca-se o valor $\frac{n}{2}$ na $F_ac$ e determina-se qual é a classe que representa a mediana.

### Moda

A moda ($M_o$) de uma variável $X$ é dado pelo valor que apresenta a maior frequência absoluta, ou seja, é o valor que mais se repete no conjunto de dados.

## Medidas de Posição Para Dados Agrupados Com Intervalo de Classe  🦇

### Média

Para dados agrupados com intervalos de classe é necessário calcular para cada classe o ponto médio dado por $x_i = \frac{l_i+l_s}{2}$ e depois pode-se proceder da mesma forma para dados agrupados sem intervalo de classe.

$$\bar{X} = \frac{\sum x_if_i}{\sum f_i}$$

# Mediana

Busca-se o valor $\frac{n}{2}$ na $F_{ac}$ e determina-se qual é a classe que representa a mediana. Após ser determinada a classe que contém a mediana, aplica-se a seguinte equação:

### $$M_e(X) = l_{iMe} + \left[\frac{\frac{n}{2} - \sum f_{iant}}{f_{iMe}}\right]h$$

onde:

- $l_{iMe}$ - Limite inferior da classe que contém a mediana.

- $\sum f_{iant}$ - Soma das frequências anteriores à classe da mediana.

- $f_{iMe}$ - Frequência da classe que contém a mediana.

- $h$ - Amplitude do intervalo de classe.

### Moda

A moda ($M_o$) de uma variável $X$ é dado pelo valor que apresenta maior frequência absoluta, ou seja, é o valor que mais se repete no conjunto de dados. Desta forma determina-se a classe com maior frequência e aplica-se a fórmula abaixo:

### $$M_o(X) = l_{iMo} + \left[\frac{\Delta_1}{\Delta_1 + \Delta_2}\right]h$$

onde:

- $l_{iMo}$ - Limite inferior da classe que contém a moda.

- $\Delta_1 = f_{iMo} - f_{iant}$ - Frequência da classe da moda menos a frequência da classe anterior a da moda.

- $\Delta_2 = f_{iMo} - f_{ipos}$ - Frequência da classe da moda menos a frequência da classe posterior a da moda.

- $h$ - Amplitude do intervalo de classe.<br><br>

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

Na estatística, a variância de uma variável aleatória é a medida da sua dispersão estatística, indicando "o quão longe" em geral os seus valores se encontram do valor esperado. A obtênção dessa medida se dá pela fórmula:

#### $\sigma^2(x) = \frac{\sum_{i=1}^N(x_i - \bar{x})^2}{N}$ (Variância Populacional)

<br>

#### $\sigma^2(x) = \frac{\sum_{i=1}^N(x_i - \bar{x})^2}{N-1}$ (Variância Amostral)

## Desvio Padrão

A variância é uma medida muito últil, porem quando à usamos associada à alguma uniadde de medida, como por exemplo, metros ($m$), segundos ($s$) ou massa ($kg$), elevamos essas unidades ao quadrado e isso dificulta a interpretação dos resultados, para esses casos utilizamos uma outra medida de dispersão chamada de *desvio padrão*, expressa pela seguinte fórmula:

#### $\sigma(x) = \sqrt{\frac{\sum_{i=1}^N(x_i - \bar{x})^2}{N}}$ (Desvio Padrão Populacional)

<br>

#### $S = \sqrt{\frac{\sum_{i=1}^N(x_i - \bar{x})^2}{N - 1}}$ (Desvio Padrão Amostral)<br><br>

## Coeficiente de Variação ou Desvio Padrão Relativo
