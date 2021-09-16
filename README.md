# Churn-Telecom

# <p align="center"> <b> Previsão de churn  para telecom</b>
  
  
##  Sobre o case: </br> </br> 

O conjunto de dados inclui informações sobre:

Clientes que saíram no último mês - a coluna é chamada de churn<br>
Serviços que cada cliente assinou - telefone, várias linhas, internet, segurança online, backup online, proteção de dispositivo, suporte técnico e streaming de TV e filmes<br>
Informações da conta do cliente - há quanto tempo ele é cliente, contrato, forma de pagamento, faturamento sem papel, cobranças mensais e cobranças totais<br>
Informações demográficas sobre clientes - sexo, faixa etária e se eles têm parceiros e dependentes

Pasta contém 3 datasets, 

1 - EDA - mostrando a exploração dos dados <br>
2 - Baseline - fazendo testes em diferentes modelos <br>
3 - Modelo finalizado <br>
  
A lógica usada:


<b> 1- Entender o problema </b> -</br>
<b> 2- Import dos dados</b> </br>
     
    -Importação das bibliotecas
    -Importação do dataset
    
<b> 3 - EDA - Análise dos dados</b> <br>

     -Análise dos dados estatísticos 
     -Entendimento das features
     -Análise por feature
     -Exploração com o cruzamento de features
     -Analisar quem são os clientes que cancelaram a assinatura
     -Correlação das variáveis
   
   
   <b> 5 - Tratamento dos dados </b> <br>   
    - Análise de dados faltantes ou NAN
    -Outliers
    -Erros de digitação
    -Correção dos Dtypes
    -Feature Engenering 
     
<b> 5 - Montagem do pipeline </b> <br>   
   
     -Balanceamneto da variável target
     -Encoding das features categóricas
     -Normalização dos dados
     -Separação dos datasets de treino e teste
     
     
<b> 6 - Treinamento do modelo </b> <br>  

      -Treinamento do modelo usando o pipeline

<b> 7 - Teste e avaliação do modelo </b> <br>

 
      -Avaliação da acurácia 
      -Observação das métricas
          -Accuracy
          -Precision
          -Recall
         
      -Teste e validação do modelo
