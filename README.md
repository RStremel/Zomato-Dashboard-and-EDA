# Zomato - Dashboard e Análise de Dados 🍅

# 1. O problema de negócio

A Zomato é um serviço de busca de restaurantes para quem quer sair para jantar, buscar comida ou pedir em casa, e atua em países como Índia, Brasil, Estados Unidos e diversos outros ao redor do mundo.

Em um contexto fictício, o recém-contratado CEO da Zomato solicitou uma análise completa dos dados da empresa para entender melhor o negócio e conseguir tomar as melhores decisões estratégicas, alavancando ainda mais a marca.

Para atender à demanda, foi realizada uma análise descritiva, respondendo diversas questões quantitativas e qualitativas referentes às cidades e países onde se encontram os restaurantes cadastrados, além dos tipos de culinária que são oferecidos.

Em seguida, foi criado um dashboard, dividido em quatro visões (Países, Cidades, Culinária e Restaurantes), contendo gráficos interativos e filtros ajustáveis para a melhor compreensão dos dados pelos stakeholders.

# 2. As estratégias da solução

Com os dados coletados da plataforma [Kaggle](https://www.kaggle.com/datasets/akashram/zomato-restaurants-autoupdated-dataset?resource=download&select=zomato.csv), que, por sua vez, foram coletados atráves da Zomato API Analysis, inicialmente foi desenvolvida uma análise descritiva através de um notebook respondendo à algumas perguntas categorizadas em quatro visões:

1. Visão Geral
2. Visão Países
3. Visão Cidades
4. Visão Tipos de Culinária
5. Visão Restaurantes

Da mesma forma, e seguindo o mesmo padrão na divisão de categorias, foi desenvolvido um dashboard com filtros customizáveis, ilustrando, em gráficos e tabelas, as respostas às questões respondidas no notebook, além de outras informações.

O conteúdo de cada página é o seguinte:

**2.1 Visão Geral**

- Descrição inicial sobre os dados utilizados
- Total de Restaurantes
- Total de Países
- Total de Cidades
- Total de Culinárias
- Total de Avaliações

**2.2 Visão Países**

- Quantidade de Restaurantes por País
- Quantidade de Culinárias Distintas por País
- Preço Médio para Dois por País, em Reais
- Distribuição de Categorias de Preço por País
- Os Países com as Melhores e Piores Notas Médias

**2.3 Visão Cidades**

- Quantidade de Restaurantes por Cidade
- Preço Médio para Dois por Cidade, em Reais
- Quantidade de Culinárias Distintas por Cidade
- As Cidades com as Melhores e Piores Notas Médias

**2.4 Visão Culinária**

- Tipos de Culinária Mais Comuns
- As Culinárias com as Melhores e Piores Notas Médias
- As Culinárias com os Maiores e Menores Preços Médios para Dois, em Reais

**2.5 Visão Restaurantes**

- Os 10 Restaurantes com Mais Avaliações
- Os Restaurantes com os Maiores e Menores Preços Médios para Dois, em Reais
