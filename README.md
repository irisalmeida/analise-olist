
# Análise de Dados do E-commerce Brasileiro (Olist)

Este projeto realiza uma análise exploratória e preditiva com base no [dataset público do Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), que contém dados de pedidos de e-commerce no Brasil entre 2016 e 2018.

## 🔧 Como executar

1. Faça o download do dataset no [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
2. Coloque os arquivos CSV em uma pasta chamada `olist`
3. Abra e execute o notebook `analise_olist.ipynb` no Google Colab ou Jupyter
4. Todas as bibliotecas necessárias estão listadas no próprio notebook

## 📊 Principais análises

* Evolução mensal dos pedidos e sazonalidade
* Fatores que afetam a satisfação do cliente
* Análise de atraso de entrega com modelo preditivo
* Segmentação de clientes com KMeans
* Mapa de calor de vendas por estado
* Dashboard de desempenho dos vendedores

## 📈 Resultados principais

* **Tendência de crescimento nas vendas** entre 2017 e 2018, com um pico acentuado em **novembro de 2017**, indicando influência da **Black Friday**.
* **Clientes recorrentes são minoria**, sugerindo oportunidade de campanhas de fidelização.
* **Tempo de entrega tem impacto direto nas avaliações dos clientes**. Entregas mais longas tendem a gerar notas mais baixas.
* **O modelo preditivo de atraso** (Random Forest) teve desempenho razoável, com destaque para o **recall nos atrasos**, importante para evitar insatisfação.
* A **segmentação de clientes via KMeans** revelou perfis distintos:

  * **Cluster 0**: novos, satisfeitos → investir em recompra
  * **Cluster 1**: lentidão e insatisfação → focar em logística e recuperação
  * **Cluster 2**: clientes fiéis → fortalecer fidelização
  * **Cluster 3**: ticket alto e única compra → oferecer suporte premium
* Algumas **categorias de produto têm avaliação melhor que outras**, sugerindo que tipo de produto impacta na satisfação.
* O **dashboard de vendedores** mostrou que a maioria entrega em até 20 dias, com média de avaliação acima de 4. Alguns vendedores com muitos pedidos mantêm excelente avaliação e prazo, sendo bons exemplos de alta performance.
* Há **indícios claros de sazonalidade**, com vendas maiores no final do ano e queda no início do ano seguinte.


## 📁 Arquivo

* `analise_olist.ipynb`: notebook com todo o código, análises e visualizações

---

