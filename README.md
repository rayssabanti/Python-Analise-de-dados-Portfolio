# Portfolio - Análise de Dados utilizando Python
 
### :pushpin:	 Objetivo 
Tem como objetivo aplicar as habilidades de limpeza e análise de correlações dos dados de Filmes utilizando os conceitos de DataScience.

### :twisted_rightwards_arrows: Disponibilização dos Dados 
Os dados foram disponibilizados pelo [Kaggle](https://www.kaggle.com/datasets/danielgrijalvas/movies) em formato CSV. 

### :bookmark: Importação das bibliotecas
* Pandas
* Seaborn
* Numpy 
* Matplotlib
* Pyplot 
* Math
* re
* datetime
### :bookmark: Importação dos dados 
![image](https://user-images.githubusercontent.com/61653788/169074942-5885aceb-3036-4c05-a9bc-2893610fcbd1.png)
### :wastebasket:	Limpeza dos Dados
####  :card_file_box:	 Buscando as colunas com nulos e preenchendo com 0 (caso existam)
Com um for, busquei casos nulos em todas as colunas e caso encontrasse alterei para 0 

![image](https://user-images.githubusercontent.com/61653788/169075202-ba4bbd52-15de-472b-9c76-bded3cdfff31.png)

Foram encontrados casos nas colunas:
* rating 
* released 
* score 
* votes 
* writer 
* star 
* country
* budget 
* gross 
* company 
* runtime 
 #### Verificando os tipos das colunas 
 Percebi que algumas colunas numéricas não estavam no tipo certo, então realizei a alteração:
 ![image](https://user-images.githubusercontent.com/61653788/169075884-f59f3e0b-685b-47d8-a8dd-7754aed2d18c.png)
 #### Correção nas colunas RELEASED E YEAR 
* Existem casos onde a coluna Year tem anos diferentes da Released, foi identificado que a Year pode conter o ano de liberação do teaser e que a Released seria o gabarito.
* Extração do ano da coluna Released
* Existem alguns casos na released que o ano não está preenchido, necessário correção.
* Comparação com a Year

![image](https://user-images.githubusercontent.com/61653788/169076737-8b4d3b62-b428-429f-8c92-66d0f7bc9cca.png)

 #### Extraindo os meses da coluna Released
 ![image](https://user-images.githubusercontent.com/61653788/169077388-04cabcc1-3a3b-4af6-b7b9-36d80cc53ea5.png)
 
Transformando os meses em números para facilitar a análise.
![image](https://user-images.githubusercontent.com/61653788/169077863-3ea15c8c-e511-4182-9dbb-771704598d05.png)
![image](https://user-images.githubusercontent.com/61653788/169077931-4e72e9f9-b629-4a47-bbe3-a6a2920bf313.png)


### :bookmark: Análise de Correlações :hammer_and_wrench:	






