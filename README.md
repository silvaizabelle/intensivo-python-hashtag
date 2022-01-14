# Intensivão Python - Hashtag Treinamentos :chart_with_upwards_trend:

Curso online e intensivo de introdução à linguagem Python, ministrada por João do canal de Youtube [Hashtag Treinamentos](https://www.youtube.com/c/HashtagTreinamentos).

### Cronograma

- 10/01 - Automação de Sistemas e Processos com Python - 2 horas
- 11/01 - Análise de Dados com Python - 2 horas
- 12/01 - Web Scraping - 2 horas
- 13/01 - Introdução à projetos de Ciência de Dados e Inteligência Artificial - 2 horas

Total: 8 horas


## Aula 1 - Automação de Sistemas e Processos com Python

### :round_pushpin: Desafio

1. Todos os dias, o nosso sistema atualiza as vendas do dia anterior. O seu trabalho diário, como analista, é enviar um e-mail para a diretoria, assim que começar a trabalhar, com o faturamento e a quantidade de produtos vendidos no dia anterior
2. Para resolver isso, vamos usar o pyautogui, uma biblioteca de *automação de comandos do mouse e do teclado*
- Comandos pyautogui: [https://pyautogui.readthedocs.io/en/latest/quickstart.html](https://pyautogui.readthedocs.io/en/latest/quickstart.html)

### :bulb: O que aprendemos?
Automatizar um processo repetitivo por meio da biblioteca pyautogui e pyperclip, responsáveis por controlar mouse e teclado. Por meio do script, entramos em uma pasta do Google Drive, importamos um conjunto de dados xls, calculamos a soma do faturamento e quantidade de produtos vendidos por meio da função .sum do _pandas_, seguido de envio automático do e-mail com dados referentes à planilha baixada.

### :mag: Como resolvemos esse desafio?
Você pode ver o código [aqui](https://github.com/silvaizabelle/intensivo-python-hashtag/blob/main/aula-1-automacao.ipynb).

_

## Aula 2 - Análise de Dados em Python

### :round_pushpin: Desafio:

1. Você trabalha em uma empresa de telecom e tem clientes de vários serviços diferentes, entre os principais: internet e telefone.
2. O problema é que, analisando o histórico dos clientes dos últimos anos, você percebeu que a empresa está com Churn de mais de 26% dos clientes.
3. Isso representa uma perda de milhões para a empresa.
4. O que a empresa precisa fazer para resolver isso?

- Link Original do Kaggle: [https://www.kaggle.com/radmirzosimov/telecom-users-dataset](https://www.kaggle.com/radmirzosimov/telecom-users-dataset)

### :bulb: O que aprendemos?
Analisar e tratar conjunto de dados exportados do excel, por meio da biblioteca _pandas_, utilizando as funções _drop_ e _dropna_. Além disso, aprendemos a explorar os dados por meio de tabelas descritivas e plotar gráficos comparativos, por meio da biblioteca _plotly_, para retirada de insights sobre problemas da empresa. Por fim, sugerimos ações a partir da análise dos dados tratados.

### :mag: Como resolvemos esse desafio?
Você pode ver o código aqui.

## Aula 3 - Automação Web (web scraping) e Busca de informações com Python

### :round_pushpin: Desafio
1. Trabalhamos em uma importadora e o preço dos nossos produtos é vinculado a cotação de:
    - Dólar
    - Euro
    - Ouro
2. Precisamos pegar na internet, de forma automática, a cotação desses 3 itens e saber quanto devemos cobrar pelos nossos produtos, considerando uma margem de contribuição que temos na nossa base de dados.

### :bulb: O que aprendemos?
Coletar/extrair informações de páginas (web scraping) por meio da biblioteca _selenium_. Pesquisar os valores no google, inspecionar os elementos e indicar a localização no código. Exportar uma planilha slx e alterar os valores, para aqueles que procuramos. Por fim, transformar as colunas para receber os valores atualiados.  Assim, todas as vezes que rodarmos o código, os valores serão atualizados e salvos na planilha sem precisarmos abrir o arquivo excel.

### :mag: Como resolvemos esse desafio?
Você pode ver o código aqui.


## Aula 4 - Projeto Ciência de Dados - Previsão de Vendas

### :round_pushpin: Desafio

1. Nosso desafio é conseguir prever as vendas que vamos ter em determinado período com base nos gastos em anúncios nas 3 grandes redes que a empresa Hashtag investe: TV, Jornal e Rádio

### :bulb: O que aprendemos?

Criar um projeto de ciência de dados: entendendo o problema, o contexto e a atuação da empresa solicitante; extraindo e ajustando os dados, explorando os dados e compreendendo a correlação entre as variáveis (estatística básica). 

Após a compreensão da correlação entre as variáveis, modelamos nossa base de dados e a separamos em duas (ou quatro se considerarmos x e y): treino e teste. A base de treino serve para treinar a maquina, para que ela consiga entender os resultados a partir dos investimentos, para depois conseguir prever quais serão os resultados alcançados. A base de teste serve para que comparemos os resultados com o treino. 

O python tem bibliotecas especializadas em machine learning, então importamos o sklearn, uma biblioteca que treina o algoritmo para fazer previsões. Dentro dos modelos de previsão testamos regressão linear e árvore de decisões. No final entendemos que a correlação com o modelo de decisão era maior, por isso mais confiável.

Por fim, compreendemos que o valor investido em TV resultava em mais vendas.

### :mag: Como resolvemos esse desafio?
Você pode ver o código aqui.

_______________________________________


Izabelle Pereira da Silva
[LinkedIn](https://www.linkedin.com/in/silvaizabelle/) | [Github](https://github.com/silvaizabelle) 
