# Week 1 - Notes
**Adenotas:** Notas escritas primeiramente em português, ao decorrer do curso, criarei notas também em inglês e mais no futuro em francês, apenas para efeito de treinar os dois idiomas.

## Notação usada no curso.

> m   = Número de variavéis(features) para treino

> x's = "input" variable. | feature

> y's = "output" variable | "target" variable

> (x, y) = Um único exemplo de treino do nossa *dateset*

> ![formula](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/CodeCogsEqn2.gif) = inésimo exemplo de treino, ondeo *i* é a posição no vetor de treino.

## Função custo e Hipótese.

Problema hipotético para contextualizar os conceitos: Encontrar o melhor preço de um apartamento dado o tamanho (m²) do mesmo.

A variável *x* é chamada de *input* ou *feature*. Em nosso exemplo, seria a área do apartamento que estamos tentando prever.

A variável *y* é chamada de *output* ou *target*, que é o que estamos tentando prever. Em nosso exemplo, seria o preço do apartamento.

Históricamente, *hipótese* (hypothesis) é o nome  dado a função lienar usada para fazermos a predição de *Y* (target). 



*Theta 0* e *Theta 1* são os parâmetros do nosso *modelo*.  


> Theta 0 controls the horizontal inclination of the straight line 

> Theta 1 controls the inclination of the straight line

Having a dataset for training, what we want to do is to come up with values for the parameters theta 0 and theta 1, so that straight line of the function somehow fits the data well. Like this:

<div style="text-align:center"><img src ="https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/straight_line_fit.PNG" /></div>

### Cost Function Intuition  

**Hypothesis** = ![Hypothesis](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/CodeCogsEqn.gif)

**Parameters** = ![Parameters](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/theta_0_theta_1.gif)

**Cost Function** = ![Cost Function](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/costa_function.gif)

**Goal** = Minimize ![Theta0_Theta1](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/theta_0_theta_1.gif) using  ![J_Function](https://github.com/akliemke/dailylog/blob/master/2018/MLCoursera/Week%201/images/J_function.gif)


## Linear Regression and Gradient Descent




### Math Functions generate in [CodeCogs Latex Editora](https://www.codecogs.com/latex/eqneditor.php)

> **Cost Function Syntax:** J(\theta_0, \theta_1) = \frac{1}{2m} \sum_{i=1}^m(h_\theta(x^{(i)})- y^{(i)})^2 

### Bibliography
