
Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados.
-----------------------------------------------------------------------------------------------------------------------------

Apresentação: Para entrarmos no assunto precisamos elucidar alguns conceitos para melhor entendimento.

O que são Bancos de Dados (BD's)?

 Para entendermos de forma mais simplória, podemos dar um exemplo de uma Agenda de contatos telefônicos que
possuímos nos celulares, o nome "Agenda",que é relacionado como guardavamos informações de números de 
contatos telefônicos antigamente, naqueles caderninhos que até hoje podemos encontrar em papelarias. 
Essas informações escritas nas agendas era uma forma de armazenarmos nossos contatos, assim podemos dizer
que a agenda fisica é um tipo banco de dados, onde as informações de contatos são os dados, e a agenda é o 
meio de armazenamento.
 Com a evolução tecnológica essas informações passaram a ser armazenadas digitalmemte em diversos tipos de meios 
fisicos, como cartões de memória, HD's(hard disk) e também em nuvem.

-----------------------------------------------------------------------------------------------------------------------------

Sistemas de Gerenciamento de Banco de Dados ( SGBD's)

 Hoje, com a geração de grande volume de dados, gerando uma grande demanda de se guardar cada vez mais 
informações de forma rápida, e também com acesso rapido e de facil consulta, surgiram os Sistemas de 
Gerenciamento de Banco de Dados(SGBD's).
 Como o nome mesmo ja diz, são sistemas que nos permitem armazenar, gerenciar e consultar os dados de forma mais rapida
e com acesso distribuído aos seus usuários. E com a vantagem de eliminarmos todo volume fisico de dados em papel, 
que eram de difícil acesso, consulta e gerenciamento. Os SGBD's são softwares(programas) que nos quais são
utilizados para armazenar e manipular os dados utilizando uma linguagem própria para realizar esses procedimentos
de armazenamento, consulta e gerenciamento e manipulação de dados através de linguagem procedural definida. 
A linguagem, se assim pode se chamar, é o Structured Query Language(SQL), porem cada SGBD pode possuir uma forma de 
definida de linguagem utilizando de palavras reservadas diferentes, mas com mesmo objetivo, armazenar, manipular, gerenciar 
e consultar dados. 
 Podemos dividir os SGBD's em dois tipos, os Bancos de Dados Relacionais (SQL) e os não relacionais, mais conhecido
como NoSQL(Not Only SQL).

-----------------------------------------------------------------------------------------------------------------------------

O que é um Banco de Dados Relacional?

Os BD's relacionais armazenam dados que possuem relacionamento entre si, são normalizados, não possuem duplicidade,
dando maior integridade dos dados armazenados, com scheema de dados rígido.
 Para entendermos, podemos dar o exemplo de uma oficina mecânica. Como criar um sistema de BD de uma oficina?
 Se pensarmos, uma oficina possui clientes, que consomem serviços, que geram ordens de serviço, dentro das ordens de serviço
possuem dados dos clientes, peças utilizadas. Os dados de clientes são armazenados em uma tabela separada, as ordens de serviço
e de peças também. O relacionamento entre essas tabelas se da através das informações em comum entre elas. Por exemplo,
uma ordem de serviço possui cliente, que é identificado através de seu CPF, uma ordem de serviço possui peças utilizadas
que é identificada através do código da peça. Dessa forma temos um relacionamento entre as tabelas de uma forma que os mesmos
dados nos quais elas se relacionam sejam os mesmos, havendo assim uma integridade dos dados armazenados.
Esses dados que formam os relacionamentos chamamos de chaves, que se dividem em chaves primarias e estrangeiras. As chaves 
primarias são as que identificam de forma universal aquela informação em sua tabela proncipal, impedidindo a duplicidade da
informação, por exemplo, o CPF da tabela de clientes é a chave primária, e o CPF na tabela de Ordem de serviço será a chave
estrangeira criando assim um relacionamento entre as tabelas.   

------------------------------------------------------------------------------------------------------------------------------

Bancos NoSQL

 Uma alternativa ao SQL, veio para atender necessidades e capacidades diferentes que BD relacional não conseguia atender.
 Não utiliza um esquema de tabelas com linhas e colunas como os Bancos relacionais.
 Não possui uma forma de estrutura bem definida e forma de armazenamento rígida em comparação ao SQL. 
 Possui uma gama maior de aplicabilidade.
 Permiti uma escabilidade maior de informações sendo utilizada para altos volumes de dados.
 Não substitui o BD Relacional, veio para atender o que o BD relacional não atendia. 

-------------------------------------------------------------------------------------------------------------------------------
 
Engenharia de dados

 O engenheiro de dados, prepara informações, desenvolve, armazena e disponiliza para consulta e manipulação os dados.
 É o profissional responsável por gerenciar, otimizar e monitorar a recuperação, armazenamento e distribuição de dados
em toda a organização.
 Mantém e contrói sistemas de armazenamento de dados que serão utilizados por outras áreas da empresa.
 O engenhheiro de dados trabalha com serviços de computação em nuvem, ferramentas Big Data, essencial para construir a base
de dados de um projeto.
 Responsável por processar e transformar os dados brutos de uma empresa, e a partir daí, disponibiliza-los, garantindo que 
outros profissionais possam usa-lo.
 É o engenheiro de dados que irá identificar qual tipo de Banco de dados será utilizado para o modelo de negócio a ser
aplicado. Após determinar qual BD usar, conhecer as ferramentas também é importante para poder aplica-la afim de atender
as necessidades que será exidada para gerenciamento, consultas e armazenamento dos dados.

























