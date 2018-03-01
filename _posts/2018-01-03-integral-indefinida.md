Antiderivada e Integral definida
================
Thiago de Paula Oliveira
1 de Março de 2018

No cálculo I, você demanda um grande período de tempo para aprender sobre derivadas. O processo de encontrar a derivada de uma função é denominado "diferenciação". Esse processo nasceu a partir de problemas relacionados a encontrar a curva tangente e a problemas relacionados a velocidade de um objeto. Ambos envolvendo o cálculo de algum tipo de limite, sendo esse tipo especial de limite denominado derivada, o qual pode ser interpretado como uma taxa de variação. O gráfico da função da primeira derivada mostra o quão rápido e onde a função é crescente e/ou o quão rápido e onde ela é decrescente.

A integração, por sua vez, nasceu a partir de problemas relacionados a área sob uma curva. Da mesma forma, a integração também é um tipo especial de limite. Seja <span class="inlinecode">*f*(*x*)</span> uma função definida num intervalo <span class="inlinecode">\[*a*, *b*\]</span>, nós dividimos esse intervalo em <span class="inlinecode">*n*
<div>
subintervalos de tamanhos iguais <span class="inlinecode">$\\Delta x=\\frac{b-a}{n}$</span>, resultando em nos pontos <span class="inlinecode">*x*<sub>0</sub> = *a*, *x*<sub>1</sub>, *x*<sub>2</sub>, …, *x*<sub>*n*</sub> = *b*</span> desse subintervalo. Seja <span class="inlinecode">*x*<sub>1</sub><sup>\*</sup>, *x*<sub>2</sub><sup>\*</sup>, …, *x*<sub>*n*</sub><sup>\*</sup></span> qualquer pontos amostrados nesse intervalo, então <span class="inlinecode">*x*<sub>*i*</sub><sup>\*</sup></span> está no <span class="inlinecode">*i*</span>-ésimo subintervalo <span class="inlinecode">\[*x*<sub>*i* − 1</sub>, *x*<sub>*i*</sub>\], *i* = 1, 2, …, *n*</span>. Então a integral definida de <span class="inlinecode">*f*</span> no intervalo <span class="inlinecode">\[*a*, *b*\]</span> é
<div>
$$\\int\_{a}^{b}f(x)\\mbox{ } dx=\\lim\_{n \\rightarrow \\infty} \\sum\_{i=1}^{n}f\\left(x\_{i}^{\*}\\right)\\Delta x,$$
<div>
desde que esse limite exista. Se esse limite existir, então dizemos que <span class="inlinecode">*f*</span> é integrável no intervalo <span class="inlinecode">\[*a*, *b*\]</span>.

é igual ao limite do somatório de cada um dos valores que a função *f*(*x*) assume multiplicado por uma taxa de variação *Δ**x*.
