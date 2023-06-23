# Novo Modelo Portal da Transparência

Pretende-se apresentar aqui um novo modelo para a construção do novo Portal da Transparência do Estado de Minas Gerais - PdT.
Este modelo será composto pela divisão do mesmo em dois sistemas distintos, mas interligados, a saber:

  - Uma API (Interface de Programação de Aplicações) responsável pela disponibilização dos dados; e
  - Uma interface de usuário (front-end) **open-source** responsável por consumir os dados fornecidos pela API e criar vizualizações inteligentes e interativas.

<figure markdown>
  <p class="p-center">Comunicação entre API e interface de usuário</p>
  ![comunicacao_entre_dois_sistemas](/assets/images/comunicacao_entre_dois_softwares.png){ align=center }
  <figcaption><a href='https://www.programmers.com.br/blog/niveis-de-maturidade-de-uma-api-rest/'>Níveis de maturidade de uma API REST</a></figcaption>
</figure>

Mais à frente será apresentado algumas das vantagens em se adotar a abordagem open-source para interface do usuário (front-end) do novo Portal. Também serão apresentadas propostas de condução da evolução do projeto após seu lançamento inicial, considerando as contribuições que o código pode receber ao longo do tempo.

### Construindo da API para disponibilização dos dados

A primeira etapa do modelo é a construção da API, sendo este o sistema que permitirá a comunicação entre a interface do usuário e os dados.
Modelo amplamente utilizado para construção de sistemas web, inclusive pelo Governo Federal Brasileiro, como pode ser constatado no seu [Catálogo Online de APIS](https://www.gov.br/conecta/catalogo/apis/) e em reportagens recentes[^1] demonstrando a expansão das APIs fornecidas pelo Governo Federal para bases de dados grandes e importantes como o [CadÚnico](https://www.gov.br/conecta/catalogo/apis/cadunico-servicos).

Por ser PRODEMGE a detentora dos sistemas transacionais, bem como de suas bases de dados, do Estado de Minas Gerais acredita-se que o modelo ideal para construção desta API seja via contratação da mesma.

### Construindo a interface gráfica em um modelo Open-Source

A segunda etapa do modelo basea-se na construção da interface do usuário (front-end) adotando o modelo open-source.
Algumas das vantagens em se adotar o modelo open-source:

  - Ganhos de escala durante o processo de identificação e correção de erros.
  Ao disponibilizar o código-fonte do projeto para outros entes da federação, mais olhos estarão analisando o código em busca de erros e vulnerabilidades.
  Dessa forma, bugs e falhas de segurança podem ser identificados e reportados de maneira mais ágil.
  **A comunidade também pode contribuir ativamente com correções e soluções alternativas de problemas, o que acelera o processo de resolução dos mesmos e reduzem os custos de desenvolvimento**.
  - **Melhoria contínua do software**, tento em vista a colaboração/revisão constante do código por parte da comunidade.
  A diversidade de perspectivas e experiências pode levar a descobertas inovadoras e à implementação de boas práticas de desenvolvimento.
  - Flexibilidade.
  As equipes de desenvolvimento porão adaptar o código-fonte existente de acordo com suas necessidades específicas, evitando a reinvenção da roda e economizando tempo e esforço não só para o Governo do Estado de Minas Gerais mas para qualquer ente que utilize o código-fonte do projeto.

Vale lembrar que o modelo open-source é o adotado pelo maior projeto de portais de dados abertos do mundo, o CKAN, inclusive utilizado pelo Governo de Minas Gerais no seu portal de dados abertos.

##### Organização da Equipe e Acompanhamento do Projeto

Para garantir o acompanhamento adequado da evolução do projeto e o gerenciamento das contribuições recebidas, é importante estabelecer uma estrutura organizacional clara e eficiente. Recomenda-se a criação de um time responsável pelo desenvolvimento e manutenção do Portal da Transparência, composto por desenvolvedores internos e externos.

Esse time pode ser dividido em diferentes funções, como:

Líder de projeto: Responsável pela coordenação geral do projeto, estabelecendo metas, prazos e prioridades, além de gerenciar as contribuições recebidas.

Desenvolvedores principais: Responsáveis pela implementação das funcionalidades principais do Portal da Transparência, trabalhando em estreita colaboração com a equipe externa de desenvolvedores.

Equipe externa de desenvolvedores: Composta pelos colaboradores da comunidade open-source que desejam contribuir para o projeto. Esses desenvolvedores podem ser atribuídos a tarefas específicas, como correção de bugs, implementação de novos recursos ou revisão do código existente.

Revisores de código: Encarregados de revisar as contribuições feitas pela comunidade, garantindo a qualidade, consistência e aderência aos padrões de desenvolvimento estabelecidos.

Gerente de qualidade: Responsável por coordenar os testes e garantir que o software seja lançado com a menor quantidade possível de erros e bugs.

Conclusão

A construção de um Portal da Transparência utilizando um modelo open-source traz inúmeras vantagens. A transparência e o controle oferecidos pelo acesso ao código-fonte, juntamente com as contribuições da comunidade de desenvolvedores, resultam em um sistema mais robusto, seguro e confiável. Além disso, a possibilidade de escalar o projeto durante a identificação e correção de bugs, bem como a flexibilidade e personalização proporcionadas pelo modelo open-source, são fatores determinantes para o sucesso do empreendimento. Com uma equipe

[^1]: [Governo lança API do CadÚnico com dados de 94 milhões de pessoas](https://www.convergenciadigital.com.br/Gestao/Governo-lanca-API-do-CadUnico-com-dados-de-94-milhoes-de-pessoas-63459.html) de 15/06/2023.
