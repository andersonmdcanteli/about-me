---
date: "2023-12-27T00:00:00Z"
external_link: ""
image:
  caption: Folder announcing the release of CAVS for researchers around the world
  focal_point: Smart
links:
- icon: fas fa-download
  icon_pack: fas
  name: Download
  url: http://www.prppg.ufpr.br/site/posalim/pb/aplicativos/

summary: A free software for analyzing adsorption data
tags:
- python
- adsorption
title: CAVS - adsorption evaluation
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

> The CAVS – adsorption evaluation software is an application developed to assist researchers working in the area of adsorption. Through a friendly interface, the application allows any user to evaluate their results in a simple and efficient way.

<br>

## About

The program was developed with simplicity and robustness as premises.

### Simplicity

We have always aimed to make the program simple and accessible for all researchers, especially those new to the field of adsorption. For this reason, most of the models used in the literature are already implemented in the software. The researcher's role is just to prepare the data for analysis, while CAVS - Adsorption Evaluation takes care of the rest.

This way, you can focus on what really matters: collecting and properly evaluating data.

### Robustness

There are several software available that perform regressions efficiently. There are also tutorials that explain step by step how to do it, as well as articles that detail the process. Therefore, creating an application that only performed regressions would be like “taking sand to the beach”.



### Problems

The vast majority of experimental adsorption data show nonlinear behavior. Data on adsorption kinetics and adsorption isotherms generally show exponential behavior. The fixed-bed data show sinusoidal behavior. Therefore, most of the models used are non-linear (Langmuir, Freundlich, Thomas, etc.).

However, when these models were developed, the computational expense to solve the system of equations of the least squares method was high. In many cases this made it impossible to adjust the model. Thus, it was common to linearize the model (and the data) to simplify the calculations and to be able to obtain an estimate of the model coefficients. However, this linearization comes with a price: it distorts the behavior of the data, especially for low concentrations. But of course, this price was low compared to the computational effort required to perform the nonlinear adjustment.

This is no longer true these days. The computational expense to solve the equation system is minimal, and few things justify the distortion caused by the linearization of the data. CAVS - adsorption evaluation solves this problem by adopting a non-linear regression method with all models included.



### Abuse of $R^2$

Regression results from different models are usually compared only by the coefficient of determination (
), which is an ineffective function for decision making in non-linear models, such as the vast majority of models evaluated in the area.

Proper evaluation of results must use appropriate methods that verify whether the model is statistically adequate to represent the data set. To address this problem, CAVS - Adsorption Evaluation offers a series of 5 tests to evaluate the regression result. These tests examine the regression as a whole, the model parameters as well as the residuals, checking whether the assumptions of the least squares method are supported. The results are presented with a simple “Yes” and “No”, for quick interpretation of the results. However, all estimated values for each test are described, allowing their use in publications.

To address the problem of excessive use of $R^2$ when comparing models, CAVS - Adsorption Evaluation uses information criteria. Using these criteria, the models are compared and then ranked, indicating the model most likely to be the best representation of the experimental data.

<br>

## Registration

{{< figure class="center" width="200" src="patent.png" alt="logo of a generic certificate">}}

CAVS - Adsorption Evaluation is registered with the [National Institute of Industrial Property](https://busca.inpi.gov.br/pePI/) (INPI) – the official government body responsible for Industrial Property rights in Brazil – under registration number BR512019001440-5.

<br>

## Powered by Python 3.7

{{< figure class="center" width="200" src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/community/logos/python-logo-only.png" alt="Python logo">}}


The application was developed entirely in Python and makes use of the main scientific libraries available (NumPy, SciPy and matplotlib), making the program fast and efficient.


<br>

## Why use CAVS?

- **It is free**: CAVS is and will always be FREE software!

- **Easy to use**: The program was developed to be simple!

- **Focus on what really matters!**: Using CAVS you have more time to obtain data and interpret it!

- **It was developed by adsorption researchers**: We understand your problems, because they are our problems too!


<br>


## Downloads
{style="text-align: center;"}

**993**
{style="text-align: center; font-size: 100px"}


total downloads until 07/07/2023*
{style="text-align: center;"}



{{< figure class="center" width="600" src="button.png" alt="CAVS" caption="[download](http://www.prppg.ufpr.br/site/posalim/pb/aplicativos/)">}}


<br>

## Acknowledgements

<br>


{{< figure class="center" width="300" src="https://memoria.cnpq.br/image/image_gallery?uuid=93be9ef0-6f46-4291-86ee-e0246da82a25&groupId=10157&t=1336081261854" alt="logo da Conselho Nacional de Desenvolvimento Científico e Tecnológico" caption="[Conselho Nacional de Desenvolvimento Científico e Tecnológico](https://www.gov.br/cnpq/pt-br)">}}

{{< figure class="center" width="200" src="https://www.gov.br/capes/pt-br/centrais-de-conteudo/logo-original-fundo-claro-png.png" alt="logo da Coordenação de Aperfeiçoamento de Pessoal de Nível Superior" caption="[Coordenação de Aperfeiçoamento de Pessoal de Nível Superior](https://www.gov.br/capes/en)">}}


{{< figure class="center" width="200" src="https://ufpr.br/wp-content/uploads/2022/12/ufpr_25_-1.png" alt="Federal university of Paraná logo's" caption="[Federal university of Paraná](https://ufpr.br/)">}}


{{< figure class="center" width="300" src="https://images.sympla.com.br/5cdac64eac2e5.jpg" alt="UFPR innovation agency logo's" caption="UFPR innovation agency">}}

{{< figure class="center" width="300" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNoi0uSVkW4he22QtnIQetbKVlxemjINa0FxQr4tTfIXh4MAeB2OTWUknpErOrvsA5bRg" alt="PPGEAL logo's" caption="[PPGEAL](https://www.prppg.ufpr.br/site/posalim/en/)">}}



{{< figure class="center" width="300" src="http://www.emultec.ufpr.br/img/site/logomarca_PQ.gif" alt="EMULTEC logo's" caption="EMULTEC">}}
