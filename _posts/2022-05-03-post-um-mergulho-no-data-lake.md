---
title: "Um mergulho no Data Lake"
author: Leandro Daniel
header:
  image: "/assets/images/deeployer-website-headers-library.png"
  caption: "Photo credit: [**Gabriel Sollmann**](https://unsplash.com/@gabons)"
categories:
  - data science
tags: 
  - data science 101
  - pt-br
---

Você que está acompanhando este blog sabe que, até aqui, falamos sobre [o que é Data Science](https://deeployer.com.br/data%20science/post-o-que-e-data-science/) e apresentamos alguns dos [desafios das fontes de dados](https://deeployer.com.br/data%20science/post-os-desafios-das-fontes-de-dados/). Caso não tenha lido os posts anteriores, recomendo que invista ao menos 4 minutos para leitura do segundo, pois será bem proveitosa para o assunto deste post.😄

Vamos tomar como ponto de partida dois dos quatro itens citados no post anterior: `volume dos dados disponibilizados` e `variedade de formatos de dados`. Ambos trazem a necessidade de uma solução de ingestão e armazenamento de dados compatíveis com os processos e necessidades de projetos de Data Science. E para este tipo de solução, uma das opções mais utilizadas é o **Data Lake**.

# Mas o que é um Data Lake?

Chamamos de Data Lake um repositório de armazenamento capaz de abrigar uma quantidade de dados muito grande com a característica de manter seu formato nativo e bruto, também chamado de _raw data_. As tecnologias disponíveis para os Data Lakes são otimizadas para um dimensionamento de terabytes ou mesmo petabytes de dados - conhecido como o conceito de Big Data.

Os dados de um Data Lake tem origem em fontes de dados heterogêneas e podem ser estruturados, semi-estruturados ou não estruturados, mas sempre preservando seu estado e formatos originais, não transformados ou tratados. 

Uma boa solução de Data Lake deve compreender tanto o processamento quanto o armazenamento dos dados, possuir tolerância a falhas, escalabilidade (virtualmente) infinita e capacidade de ingestão com alta taxa de transferência com vários formatos e tamanhos.

Como vantagens de um data lake, podemos destacar:

- Os dados são mantidos e nunca descartados, uma vez que são armazenados no formato bruto;
- A partir do _raw data_ os consumidores dos dados podem criar suas próprias consultas e processos de limpeza e tratamento dos dados;
- Diferente de outras abordagens a tecnologias mais tradicionais de armazenamento de dados, como um _Data Warehouse_, um Data Lake pode armazenar dados não estruturados e semi-estruturados.

<img src="https://deeployer.com.br/assets/images/post-data-lake.png" />

Um data lake, portanto, pode ser uma boa opção de solução para resolver o problema de `volume dos dados disponibilizados`, uma vez que sua arquitetura e infraestrutura são pensadas para acomodar grandes volumes. Por fim, o problema da `variedade de formatos de dados` também é atendido levando em consideração a natureza heterogênea de armazenamento do _raw data_ de um data lake.

# Mergulhando no Data Lake

Uma vez que a solução foi definida, é importante estar ciente que a manutenção de um data lake traz consigo alguns tópicos e desafios importantes. 

Um deles, é com relação a governança adequada, seja para avaliar questões de privacidade e controle de acesso ou ainda para definir os _ownerships_ dos processos envolvidos. Em outras palavras, quem é o proprietário (ownership) de um determinado domínio?

A falta de um esquema ou metadados descritvos podem tornar os dados difíceis de serem consumidos e consultados. Isso também pode impactar na consistência semântica nos dados, gerando desafios particulares na execução de análises de dados em consumidores que não sejam altamente especializados no domínio do dado. Ainda relacionado a poucas informações sobre os dados de origem, a qualidade também pode ser difícil de ser garantida após o dado ser transferido para o Data Lake. Como efeito colateral indesesável, e possivelmente o mais danoso para a empresa, um data lake pode se tornar uma "lixeira de dados" que nunca serão analisados ou dos quais não são extraídas informações.

A [Deeployer](mailto:contato@deeployer.com) é uma empresa com um time multidisciplinar de cientistas de dados preparada para atender a todas as suas necessidades de Data Science. 

Entre em [contato](https://deeployer.com/contact/) conosco e nos diga como podemos ajudar a sua empresa a crescer.

Até o próximo post!

## Referências utilizadas neste post:
- **Dados estruturados**, to-do.
- **Dados semi-estruturados**, to-do.
- **Dados não estruturados**, to-do.
- **Nome**, to-do.
