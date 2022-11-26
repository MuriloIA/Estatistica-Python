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

- $h$ - Amplitude do intervalo de classe.
