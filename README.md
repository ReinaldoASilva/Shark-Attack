<<<<<<< HEAD

# Shark Attack

Analise de Dados - Shark Attack
Essa é uma pré analise dos dados do Shark Attack. A proposta de análise desses dados é para entender um pouco o porque do crescimento dos ataques ao logo dos anos. Lembrando que os dados aqui analisados são de 1543 a 2018 o que nos da uma certa consistência em nossa análise. 
---
Deixo o pedaço  de uma matéria do "O Globo" sobre os ataques em especial sobre 2015, que foi o ano que teve o maior pico de ataques!

"- Primeiro passo para iniciar o projeto é instalar as bibliotecas.

- Nessa primeira análise após a importação é necessário ver os dados das colunas pra ver se existem linhas vazias, valores nulos, caracteres especiais ou demais coisas pra poder ver o que nos espera.

- Transformamos os valores nulos em zero para uma formatação melhor

- A primeira coluna analisada foi a "Date" e podemos ver que tem vários tipos de data, então nosso trabalho será deixar as datas no mesmo formato."
fonte: https://oglobo.globo.com/brasil/sustentabilidade/relatorio-mostra-numero-recorde-de-98-ataques-de-tubarao-em-2015-18771426
---

----------------------------------------------------------------------------- Primeira Etapa -----------------------------------------------------------------------
---
 Nessa primeira etapa eu instalei o 'numpy' e o 'pandas' para preparar o ambiente de visualização do arquivo Shark Attack que iremos trabalhar.
=======
##  Shark Attack 🦈
>>>>>>> b5b6392269961af532806b56079cbcf42d5fd94c

</span>


<div align="center">
<img src="https://wallpaperaccess.com/full/1341530.jpg" />
</div>
----------------
  
🚀 Project Shark Attack - Qual foi o ano que mais teve ataques?

🚀 Project status(On-Hold) ⚠️

🚀 Paragraph with introduction/ objective of project

➡️ A proposta de análise desses dados é para entender um pouco o porque do crescimento dos ataques ao logo dos anos. Lembrando que os dados aqui analisados são de 1543 a 2018 o que nos da uma certa consistência para os resultados da nossa análise. 

Abaixo  👇🏽 achei interessante colocar parte de uma matéria do site o Globo que nos fala um pouco sobre o crescente ataques de tubarões.

'''Ano após ano, o número de incidentes no mundo pode variar bastante. Em 2014, foram 72. Em 2013, 75. Com 88 casos, o ano de 2000 foi o segundo com mais registros. Entretanto, de acordo com o cientista George Burgess, curador do Isaf, que contabilizou ataques registrados desde 1581, há uma curva crescente na frequência de episódios nas últimas décadas. Isto não significa, diz ele, que a população de tubarões está aumentando. O que cresce é o número de Homo sapiens se aventurando no mar, assim como o tempo que as pessoas passam em águas salgadas.

— A frequência de encontros entre humanos e tubarões está diretamente ligada à soma de tempo que as pessoas passam no mar ao redor do mundo. Uma vez que a população humana continua crescendo e que o interesse por atividades marinhas está em alta, temos que esperar um aumento no número de ataques — explica o cientista, que integra o Programa de Pesquisas sobre Tubarão do museu na Flórida.

Dos 98 ataques de 2015, seis resultaram em morte das vítimas. O biólogo Marcelo Szpilman, diretor-presidente do Aquário Marinho do Rio (AquaRio), com inauguração prevista para este ano, explica que 90% dos casos ocorrem devido a erros de identificação por parte do peixe, que confunde a pessoa com animais como focas e tartarugas, suas vítimas preferenciais.

— Em alguns locais, como o Recife, a água turva confunde ainda mais o tubarão, que pode morder uma pessoa por engano e depois ir embora, ao perceber que não é uma de suas presas preferidas — comenta Szpilman.

Foi, provavelmente, o que aconteceu com o surfista Mick Fanning, em julho do ano passado. Durante a final de um campeonato mundial transmitida via internet ao vivo de Jeffrey´s Bay, na África do Sul, um tubarão branco mordeu a cordinha que prendia a perna do australiano à prancha. Os dois se embolaram, mas o atleta se desvencilhou sem sofrer qualquer dano além de um susto inesquecível. '''

Fonte/ [O Globo](https://oglobo.globo.com/brasil/sustentabilidade/relatorio-mostra-numero-recorde-de-98-ataques-de-tubarao-em-2015-18771426) 

List with methods, ex:
+ Importando bibliotecas
  + Pandas<img width="398" alt="image" src="https://user-images.githubusercontent.com/109931715/199508406-4a62171b-8ae0-4cf2-bfe8-0e437a8da9fc.png">

  + Numpy
  + Re
  + Date Time
  + Matplotlib
+ Importando a base do Arquivo
+ Visualizando a Base
  + Set.option
  + Shape 25.723 Linhas e 24 Colunas
  + type
+ Informações da Base
  + Info
  + Columns
  + Duplicated
+ Quantidade de Valores Vazios
  + Isnull.sum - Em média de 20 mil por corlunas
+ Removendo Valores Nulos
  +Dropna - 
+ Eliminando Colunas com Valores Nulos
  + Drop - Eliminei 6 Colunas
+ Examinar A coluna Date
  + Set -
  + Len
+ Renomear Colunas
  + Rename
+ Remover os Dados antes da Coluna
  + Errors
+ Criar Novas Colunas
+ Trocar Elementos floats por Int64
  + Astype
+ Reordenar as Colunas
+ Trocar Valor 0 por n/a
  + Replace
+ Visualizar os Valores Unicos
  + Unique
+ Visualizar os Valores por Colunas
  + Groupby
  + Count
  + Reset index
+ Visualizar Ataques por Ano
  + Groupby
  + Count
  + Reset index
  + px
+ Visualizar Ataques por Vintênio
  + Groupby
  + Count
  + Reset index
  + px
 + Visualizar Ataques por Grupos
  + Groupby
  + Count
  + Reset index
  + px
 
 #### Conclusão 
 ➡️ Com a visualização de todos esses dados e informações pude concluir que os ataques de tubarão está relacionado a duas questões que diretamente não  está ligado diretamente com o animal e sim com o ser humano. Todo esse crescimento esponencial de casos tem haver com a "invasão" do ser humano ao seu habitat, tanto para exploração quanto para a atividade. Como o animal não consegue distinguir o ser humano de sua presa ele acaba atacando, infelizmente em alguns casos isso acaba se tornando fatal, ou como muita das vezes as sequelas são permanentes. Mesmo as praias tendo alertas de ataques de tubarão o ser humano acaba se expondo ao perigo de forma consciente. O maior pico de ataque de tubarões foi em 2015 e o vintênio foi de 2000 a 2019.

<<<<<<< HEAD
---------------------------------------------------------------------------------------- Qual foi o ano que teve mais ataque de tubarões? --------------------------------------------------------------------------------------------


=======


#### Ataques por Mês
![texto](https://github.com/ReinaldoASilva/Shark-Attack/blob/70b1755f0a646207937b1e7086c2d8541cc097b7/Captura%20de%20Tela%202022-11-02%20a%CC%80s%2010.48.17.png)

#### Ataques por Ano
![texto](https://github.com/ReinaldoASilva/Shark-Attack/blob/main/porano.jpge.png)

#### Ataques por Vintênio
![texto](https://github.com/ReinaldoASilva/Shark-Attack/blob/main/porvintenio.jpge.png)

#### Contato
[Linkedin](https://www.linkedin.com/in/reinaldo-silva-15856558/)  / [Medium](https://medium.com/@reinaldo.silva) / [YouTube](https://www.youtube.com/channel/UCELBXwJnsu9QlTSONJy6w8w) / [GitHub](https://github.com/ReinaldoASilva) / [Kaggle](https://www.kaggle.com/reinaldoasilva)

>>>>>>> b5b6392269961af532806b56079cbcf42d5fd94c
