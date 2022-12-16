# Medidas Separatrizes

## Introdução  🎯

Tanto a média como o desvio padrão podem não ser medidas adequadas para representar um conjunto de dados, pois:

- (a) São afetados, de forma exagerada, por valores extremos.

- (b) Apenas com estes dois valores não temos ideia da simetria ou assimetria da distribuição dos dados.

Para contornar esses fatos, outras medidas precisam ser consideradas. Vimos que a mediana é um valor que deixa metade dos dados abaixo dele e metade acima. De modo geral, podemos definir uma medida chamada quantil de ordem $p$ ou p-quantil, indicado por $q(p)$, em que $p$ é uma proporção qualquer, $0 < p < 1$, talque $100\%$ das observações sejam menores do que $q(p)$.

**Indicamos, abaixo, alguns quantis e seus nomes particulares.**

- $q(0, 25) = q_1$: 1º Quartil = $25º$ Percentil

- $q(0, 50) = q_2$: Mediana = 2º Quartil = 50º Percentil

- $q(0, 75) = q_3$: 3º Quartil = 75º Percentil

- $q(0,95)$ = $95º$ Percentil

## Boxplot  🐊

As informações dos quatro números (Mínimo, 1º Quartil, Mediana, 3º Quartil e Máximo) podem ser traduzidas gratificamente num diagrama, que chamaremos de boxplot, também conhecido como "caixa-de-bigores".

<center><img src="img/boxplot.png" width=60%></center>

Para construir este diagrama, consideremos um retângulo em que estão representados a mediana e os quartis. A partir do retângulo, para cima, segue uma linha até o ponto mais remoto que não exceda $LS = q_3 + 1.5dq$, chamamo limite superior. De modo similar, da parte do retangulo, para baixo, segue uma linha até o ponto que seja menor que $LI = q_1 - 1.5dq$, chamado limite inferior. Os valores compreedidos entre esses dois limites são chamados de valores adjacentes. As observações que estiverem acima do limite superior ou abaixo do limite inferior estabelecidos serão chamados pontos exteriores e representadas por asteriscos. Essas são observações destoantes das demais e podem ou não ser o que chamamos de outilers ou valores atípicos.