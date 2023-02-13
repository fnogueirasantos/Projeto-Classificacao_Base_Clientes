
# Classificando Base de Clientes com Algoritimo K-means

Criar um modelo de clusterização para aplicar a base de clientes.

Problema de negócio: Uma empresa de e-commerce possui uma base de 1000 cclientes cadastrados e deseja realizar um agrupamento para facilitar a comunicação, divulgação e estratégias de venda de acordo com a similiridade.

Os dados recebidos contém as seguintes variáveis:

* client_id = número de identificação do cliente
* registration_date = Data de cadastro do cliente
* Life_time = Tempo que o cliente está base em dias
* scoring_program = Pontuação do programa de fidelidade
* annual_contract = Contrato anual do cliente

O objetivo é entregar um relatório consolidado com cada cliente classficado.




## Conclusões

Foi elaborado 4 modelos utilizando o algorotimo K-means. 2 Modelos com 3 clusters e 2 com 4 clusters.

Foi realizado o tratamento de outliers e a substituição dos valores encontrados com base na regra do cut-off.

Sem dúvidas os modelos com tratamento de outliers ficaram mais balanceados e a área de negócio deve ajustar na escolha de utilização de 3 ou 4 clusters, porém conforme o gráfico de teste dos valores de k, indicamos a utilização de 3 clusters.


