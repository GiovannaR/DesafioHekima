# Random Forest 

## Sobre a base de dados:
<b>Base de Dados:</b> Titanic: Machine Learning from Disaster

<b>Link da base de dados:</b> https://www.kaggle.com/c/titanic/data


A base de dados é distribuída entre as informações dos passageiros usadas para treinamento contidas no arquivo <i>train.csv</i> do modelo de aprendizado de máquina e as usadas para testar o mesmo modelo contidas no arquivo <i>test.csv</i>. No entanto, o uso do arquivo de teste não será necessário, pois os testes serão feitos por meio dos <i>Out-Of-Bag</i> que é muito utilizado com o <i>Random Forest</i>.


## Sobre o <i>Random Forest</i>:
O <i>Random Forest</i> é um método muito usado no aprendizado de máquina. Esse método baseia-se na formação de diversas bases de dados, que são combinações da original, para serem usadas nas árvores de decisão formadas com variáveis escolhidas aleatoriamente. A previsão final é feita com base na maioria dos “votos” dessas árvores. No entanto, nessas combinações da base de dados original alguns dados não são incluídos no treinamento, esses são chamados de <i>Out-Of-Bags</i> e são usados para fazer o teste da qualidade do modelo. 

<b>Vantagens do <i>Random Forest</i>:</b>
<ul>
  <li>Alta acurácia e flexibilidade.</li>
  <li>Mantém a acurácia mesmo com muitos dados faltando.</li>
  <li>Mesmo com um grande número de dados, a variância não aumenta em grande quantidade.</li>
  <li>O processo de combinar vários resultados de várias árvores ajuda a superar o problema de sobreajuste. Esse problema ocorre quando o excesso de dados faz com que o modelo encontre resultados não condizentes com o esperado e correto.
</li>
</ul>

<b>Desvantagens do <i>Random Forest</i>:</b>
<ul>
  <li>Complexo e consume muito tempo.</li>
  <li>Requer mais recursos computacionais e é de difícil interpretação.</li>
  <li>Não é indicado para identificar eventos raros.</li>
</ul>







  
