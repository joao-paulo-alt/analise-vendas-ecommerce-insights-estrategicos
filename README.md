# <Título do projeto>

O projeto "Análise de Vendas eCommerce: Insights Estratégicos" tem como objetivo realizar uma análise aprofundada sobre as vendas de produtos eletrônicos em plataformas de comércio eletrônico. Utilizando um conjunto de dados de vendas, o projeto aplica técnicas de análise de dados e aprendizado de máquina para extrair insights valiosos sobre os padrões de compra, segmentação de clientes, identificação de fraudes e otimização de vendas. O foco é gerar recomendações estratégicas para aumentar a eficiência operacional e as vendas das lojas de produtos eletrônicos.

<picture>
  <img src="https://github.com/joao-paulo-alt/analise-vendas-ecommerce-insights-estrategicos/tree/master/docs/e-commerce.jpg" 
       alt="Análise de Vendas em E-commerce: Insights Estratégicos" 
       width="600" 
       style="display: block; margin: auto;">
</picture>

## Desenvolvedores
 - João Paulo Ferreira (https://github.com/joao-paulo-alt)

## Justificativa
O mercado de comércio eletrônico de produtos eletrônicos é altamente competitivo e dinâmico, onde as lojas precisam não apenas entender os comportamentos de compra dos clientes, mas também identificar padrões de fraude e otimizar suas operações. Este projeto visa proporcionar soluções práticas para os seguintes desafios:

1. **Aumento das Vendas**: Identificar os produtos mais vendidos, os grupos de clientes mais engajados e as promoções que têm maior impacto nas vendas, visando estratégias de marketing mais eficazes.
2. **Detecção de Fraudes**: Aplicar técnicas de aprendizado de máquina para identificar transações fraudulentas ou suspeitas, reduzindo o risco de perdas financeiras e protegendo a integridade da plataforma.
3. **Segmentação de Clientes**: Compreender as características e preferências dos diferentes grupos de clientes para personalizar ofertas, campanhas e melhorar a experiência de compra.
4. **Otimização de Estratégias Comerciais**: Baseado na análise de dados, o projeto fornecerá recomendações para otimizar preços, estoque e campanhas promocionais, maximizando a rentabilidade da loja.

## Estrutura dos Dados
*As variáveis principais incluem*:
* order_id: Identificador único da transação de venda.
* product_id: Identificador único do produto vendido.
* product_name: Nome do produto vendido.
* category: Categoria do produto (ex: smartphones, laptops, etc.).
* sales_amount: Valor da venda (preço pago pelo produto).
* quantity: Quantidade de unidades vendidas na transação.
* order_date: Data da realização da venda.
* payment_method: Método de pagamento utilizado (ex: cartão de crédito, PayPal, etc.).
* customer_id: Identificador único do cliente que realizou a compra.

*Outras variáveis incluem*:
* name: Nome do cliente.
* email: Endereço de e-mail do cliente.
* age: Idade do cliente.
* location: Localização do cliente (cidade, estado, país).

## Metodologia
O projeto será desenvolvido utilizando a metodologia CRISP-DM, seguindo os seguintes passos:

1. Entendimento de negócio
2. Entendimento de dados
3. Preparação dos dados
4. Modelagem

## Resultados Esperados
O projeto tem como objetivo analisar os dados de vendas de um eCommerce para gerar insights estratégicos que ajudem a otimizar as vendas e melhorar a segurança. Espera-se identificar padrões de vendas, como produtos mais populares e sazonalidade, para ajustar estratégias de marketing e gerenciamento de estoque. Também será realizada a segmentação de clientes, permitindo a personalização de ofertas e o aumento do engajamento. O projeto incluirá a implementação de modelos para detectar transações fraudulentas, reduzir perdas e otimizar as estratégias de precificação e controle de estoque. Por fim, serão fornecidas recomendações estratégicas baseadas nas análises realizadas, visando melhorar a eficiência operacional e aumentar a rentabilidade do eCommerce.

### Organização de diretórios


```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```
