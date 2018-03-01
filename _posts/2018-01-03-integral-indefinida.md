Antiderivada e Integral definida
================
Thiago de Paula Oliveira
1 de Março de 2018

No cálculo I, você demanda um grande período de tempo para aprender sobre derivadas. O processo de encontrar a derivada de uma função é denominado "diferenciação". Esse processo nasceu a partir de problemas relacionados a encontrar a curva tangente e a problemas relacionados a velocidade de um objeto. Ambos envolvendo o cálculo de algum tipo de limite, sendo esse tipo especial de limite denominado derivada, o qual pode ser interpretado como uma taxa de variação. O gráfico da função da primeira derivada mostra o quão rápido e onde a função é crescente e/ou o quão rápido e onde ela é decrescente.

A integração, por sua vez, nasceu a partir de problemas relacionados a área sob uma curva. Da mesma forma, a integração também é um tipo especial de limite. Seja *f*(*x*) uma função definida num intervalo \[*a*, *b*\], nós dividimos esse intervalo em *n* subintervalos de tamanhos iguais $\\Delta x=\\frac{b-a}{n}$, resultando em nos pontos *x*<sub>0</sub> = *a*, *x*<sub>1</sub>, *x*<sub>2</sub>, …, *x*<sub>*n*</sub> = *b* desse subintervalo. Seja *x*<sub>1</sub><sup>\*</sup>, *x*<sub>2</sub><sup>\*</sup>, …, *x*<sub>*n*</sub><sup>\*</sup> qualquer pontos amostrados nesse intervalo, então *x*<sub>*i*</sub><sup>\*</sup> está no *i*-ésimo subintervalo \[*x*<sub>*i* − 1</sub>, *x*<sub>*i*</sub>\], *i* = 1, 2, …, *n*. Então a integral definida de *f* no intervalo \[*a*, *b*\] é
$$\\int\_{a}^{b}f(x)\\mbox{ } dx=\\lim\_{n \\rightarrow \\infty} \\sum\_{i=1}^{n}f\\left(x\_{i}^{\*}\\right)\\Delta x,$$
 desde que esse limite exista. Se esse limite existir, então dizemos que *f* é integrável no intervalo \[*a*, *b*\].

é igual ao limite do somatório de cada um dos valores que a função *f*(*x*) assume multiplicado por uma taxa de variação *Δ**x*.
