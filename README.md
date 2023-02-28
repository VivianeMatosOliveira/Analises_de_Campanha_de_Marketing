
<center><img src= 'https://www.datanami.com/wp-content/uploads/2018/09/data_science_shutterstock_shutterstock_Trueffelpix.jpg' width = "500">

# Mini Projeto: Análises de Campanha de Marketing
Os dados analisados nesse mini projeto representam informações sobre clientes e campanhas de Marketing realizadas por uma empresa.

Visa entregar aos tomadores de decisão uma visão completa sobre o perfil dos clientes, os padrões de compra e a efetividade das campanhas de Marketing.

Os dados foram analisados considerando 4 visões, sendo elas:

*  Visão do Cliente

*  Visão do Comportamento de Compra do Cliente

*  Visão da Performance das Campanhas de Marketing

*  Visão dos Padrões de Compra no Ponto de Venda (País)


# Conceito de Marketing

Marketing  é  o  processo  de  planejar  e  executar  a  concepção,  preço,  promoção  e distribuição de ideias, bens e serviços para criar trocas que satisfaçam objetivos individuais e organizacionais.
É uma das funções mais importantes em uma empresa e é responsável por atrair e  manter  clientes.  Ele  envolve  pesquisa  de  mercado,  análise  de  concorrência,  definição  de estratégias e planejamento de campanhas publicitárias.

O marketing é crucial para as empresas por vários motivos. Alguns deles incluem:

* **Atrair  novos  clientes**:  O  marketing  ajuda  as  empresas  a  encontrar  novos  clientes potenciais atravésde campanhas publicitárias e estratégias de captação.

* **Aumentar as vendas**: O marketing ajuda as empresas a aumentar suas vendas ao criar campanhas publicitárias e promoções atraentes que estimulam os clientes a comprar.

* **Criar conscientização da marca**: O marketing ajuda as empresas a construir amarca e aumentar a conscientização dela entre o público-alvo.

* **Manter os clientes existentes**: O marketing também ajuda as empresas a manter seus clientes existentes através de estratégias de fidelização e retenção do cliente.

* **Entender  o  mercado**:  O  marketing  também  ajuda  as  empresas  a  entender  as necessidades e desejos de seus clientes, bem como as tendências do mercado, o que é crucial para a sobrevivência e crescimento a longo prazo.

Existem muitos indicadores de Marketing diferentes que as empresas podem usar para medir o sucesso de suas estratégias e campanhas.

Alguns dos principais indicadores incluem:

* **Taxa de conversão**: A proporção de visitantes do site que realizam uma ação desejada, como comprar um produto ou preencher um formulário de contato.
* **Taxa  de  retenção  do  cliente**: A proporção de clientes que compram de uma empresa novamente.
* **Custo por aquisição de cliente (CAC)**:O custo total de adquirir um novo cliente, incluindo despesas com publicidade e marketing.
* **Retorno sobre investimento (ROI)**:O lucro ou prejuízo obtido em relação ao investimento feito em uma campanha de marketing.
* **Conscientização da marca**: A medida da familiaridade e reconhecimento da marca entre o público-alvo.
* **Engajamento**:A medida da interação dos usuários com conteúdo, campanhas e canais de marketing.
* **Net  Promoter  Score  (NPS)**:Uma  medida  da  lealdade  dos  clientes,  baseada  em  sua disposição para recomendar uma empresa ou produto para outras pessoas.
* **Tráfego do website**: Número de visitas no website.

Esses  indicadores  devem  ser  monitorados  regularmente  para  ajudar  as  empresas  a entender  o  sucesso  de  suas  estratégias  e  campanhas  de  marketing  e  fazer  ajustes  onde necessário. Além disso é importante compreender o perfil dos clientes, o comportamento de gastos e os padrões de compra de acordo com diferentes métricas.

**Fonte** (Data Science Academy)


# Base de Dados
A base de dados consiste em um arquivo CSV com a estrutura abaixo:

*Dicionário de dados*

**ID** : identificador único do cliente

**Ano Nascimento** : ano de nascimento do cliente

**Escolaridade**: escolaridade do cliente - Mestrado, Doutorado, Curso Superior, Segundo Grau, Primeiro Grau

**Estado Civil**: Solteiro, Casado, Divorciado

**Salario Anual**: Total de salário anual

**Filhos em Casa**: quantidade de filhos que residem na casa

**Adolescentes em Casa**: quantidade de adolescentes que residem na casa

**Data Cadastro**: Data de cadastro do cliente

**Dias Desde Ultima Compra**: Total de dias corridos desde a última compra

**Gasto com Eletronicos**: quantidade de gastos com produtos classificados como eletrônicos

**Gasto com Brinquedos**: quantidade de gastos com produtos classificados como brinquedos

**Gasto com Moveis**: quantidade de gastos com produtos classificados como móveis

**Gasto com Utilidades**: quantidade de gastos com produtos classificados como utilidades

**Gasto com Alimentos**: quantidade de gastos com produtos classificados como alimentos

**Gasto com Vestuario**: quantidade de gastos com produtos classificados como vestuário

**Numero de Compras com Desconto**: total de compras realizadas com desconto

**Numero de Compras na Web**: total de compras realizadas na web

**Numero de Compras via Catalogo**: total de compras realizadas via catálogo

**Numero de Compras na Loja**: total de compras realizadas em loja fisica

**Numero Visitas WebSite Mes**: total de visitas no website

**Compra na Campanha 1**: realizou compras na campanha 1 ( 0 - Não / 1- Sim)

**Compra na Campanha 2**: realizou compras realizadas na campanha 2 ( 0 - Não / 1- Sim)

**Compra na Campanha 3**: realizou compras realizadas na campanha 3 ( 0 - Não / 1- Sim)

**Compra na Campanha 4**: realizou compras realizadas na campanha 4 ( 0 - Não / 1- Sim)

**Compra na Campanha 5**: realizou compras realizadas na campanha 5 ( 0 - Não / 1- Sim)

**Comprou** : houve compra em pelo menos uma das campanhas ( 0 - Não / 1- Sim)

**País**: País onde ocorreu a venda


# Ferramentas Utilizadas no Projeto
* Power BI para o desenvolvimento do Dashboard
* Google Colab para as etapas de exploração e tratamento dos dados, utilizando a linguagem Python.


# Tratamento dos Dados
Converter a variável "comprou" de numerica para categórica

Exclusão de valores nulos presentes na variável Salario Anual

Exclusão de outlaiers - variável Salário Anual - valor aparentemente errado 

# Métricas Analisadas
**Visão Cliente**
1. Total de Clientes Cadastrados
2. Média Salarial dos Clientes
3. Total de Compras em Loja Física
4. Total de Compras na Web
5. Total de Compras com Desconto
6. Total de Clientes por Escolaridade
7. Total de Clientes por Estado Civil
8. Segmentação das Análises por país

**Visão do Comportamento de Compra do Cliente**

1. Total de Gasto por Salário Anual
2. Total de Gasto por Filhos em Casa
3. Total de Gasto por Adolescentes em Casa
4. Total Gasto por Escolaridade por Estado Civil

**Visão da Performance das Campanhas de Marketing**

1. Total de Compras do cliente

# Link do Dashboard

