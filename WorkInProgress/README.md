# 208_PersonalizandoBancoDadosIndicesProcedures
Personalizando o Banco de Dados com Índices e Procedures

[**](https://web.dio.me/track/formacao-sql-db-specialist)

##### Personalizando o Banco de Dados com Índices e Procedures

**

[**](https://web.dio.me/lab/personalizando-o-banco-de-dados-com-indices-e-procedures/learning/ceef74fb-017c-49ee-8d3c-3bbcde4337ab)[**](https://web.dio.me/lab/personalizando-o-banco-de-dados-com-indices-e-procedures/learning/b6a20d7f-7457-4ae1-9fb0-952eacaa8a88)

<iframe id="ytc8" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" title="Personalizando o Banco de Dados com Índices e Procedures" width="100%" height="100%" src="https://www.youtube.com/embed/8Vfzo8AUEmY?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-16="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



00:10

 

12:47







normal

auto

- CONTEÚDOS
- INFORMAÇÕES

- [Personalizando o Banco de Dados com Índices e Procedures](https://web.dio.me/lab/personalizando-o-banco-de-dados-com-indices-e-procedures/learning/ceef74fb-017c-49ee-8d3c-3bbcde4337ab)
- [Entendendo o Desafio](https://web.dio.me/lab/personalizando-o-banco-de-dados-com-indices-e-procedures/learning/b6a20d7f-7457-4ae1-9fb0-952eacaa8a88)



#####  Personalizando o Banco de Dados com Índices e Procedures

**

[**](https://web.dio.me/lab/personalizando-o-banco-de-dados-com-indices-e-procedures/learning/ceef74fb-017c-49ee-8d3c-3bbcde4337ab)[**](https://web.dio.me/lab/personalizando-o-banco-de-dados-com-indices-e-procedures/learning/undefined)

**Parte 1 – Criando** **índices** **em Banco de Dados** 

Criação de índices para consultas para o cenário de company com as perguntas (queries sql) para recuperar recuperação de informações. Sendo assim, dentro do script será criado os índices com base na consulta SQL. 

O que será levado em consideração para criação dos índices? 

1. Quais os dados mais acessados 

1. Quais os dados mais relevantes no contexto 

Lembre-se da função do índice... ele impacta diretamente na velocidade da buca pelas informações no SGBD. Crie apenas aqueles que são importantes. Sendo assim, adicione um README dentro do repositório do Github explicando os motivos que o levaram a criar tais índices. Para que outras pessoas possam se espelhar em seu trabalho, crie uma breve descrição do projeto. 

 

A criação do índice pode ser criada via ALTER TABLE ou CREATE Statement, como segue o exemplo: 

- ALTER TABLE customer ADD UNIQUE index_email(email); 
- CREATE INDEX index_ativo_hash ON exemplo(ativo) USING HASH; 

 

Perguntas: 

- Qual o departamento com maior número de pessoas? 
- Quais são os departamentos por cidade? 
- Relação de empregrados por departamento 

 



Entregável: 

- Crie as queries para responder essas perguntas 
- Crie o índice para cada tabela envolvida (de acordo com a necessidade) 
- Tipo de indice utilizado e motivo da escolha (via comentário no script ou readme) 

 

**Parte 2 - Utilização de procedures para manipulação de dados em Banco de Dados** 

Objetivo: 

Criar uma procedure que possua as instruções de inserção, remoção e atualização de dados no banco de dados. As instruções devem estar dentro de esrtuturas condicionais (como CASE ou IF). 

Além das variáveis de recebimento das informações, a procedure deverá possuir uma variável de controle. Essa variável de controle irá determinar a ação a ser executada. Ex: opção 1 – select, 2 – update, 3 – delete. 

 

Sendo assim, altere a procedure abaixo para receber as informações supracitadas. 

 

Entregável: 

Script SQL com a procedure criada e chamada para manipular os dados de universidade e e-commerce. Podem ser criados dois arquivos distintos, assim como a utilização do mesmo script para criação das procedures. Fique atento para selecionar o banco de dados antes da criação da procedure. 

 

E agora... Finalizou seu desafio ? 

Adicione o link do github com o projeto e submeta para avaliação.



#####  Personalizando o Banco de Dados com Índices e Procedures

**

[**](https://web.dio.me/lab/personalizando-o-banco-de-dados-com-indices-e-procedures/learning/ceef74fb-017c-49ee-8d3c-3bbcde4337ab)[**](https://web.dio.me/lab/personalizando-o-banco-de-dados-com-indices-e-procedures/learning/undefined)

**Parte 1 – Criando** **índices** **em Banco de Dados** 

Criação de índices para consultas para o cenário de company com as perguntas (queries sql) para recuperar recuperação de informações. Sendo assim, dentro do script será criado os índices com base na consulta SQL. 

O que será levado em consideração para criação dos índices? 

1. Quais os dados mais acessados 

1. Quais os dados mais relevantes no contexto 

Lembre-se da função do índice... ele impacta diretamente na velocidade da buca pelas informações no SGBD. Crie apenas aqueles que são importantes. Sendo assim, adicione um README dentro do repositório do Github explicando os motivos que o levaram a criar tais índices. Para que outras pessoas possam se espelhar em seu trabalho, crie uma breve descrição do projeto. 

 

A criação do índice pode ser criada via ALTER TABLE ou CREATE Statement, como segue o exemplo: 

- ALTER TABLE customer ADD UNIQUE index_email(email); 
- CREATE INDEX index_ativo_hash ON exemplo(ativo) USING HASH; 

 

Perguntas: 

- Qual o departamento com maior número de pessoas? 
- Quais são os departamentos por cidade? 
- Relação de empregrados por departamento 

 



Entregável: 

- Crie as queries para responder essas perguntas 
- Crie o índice para cada tabela envolvida (de acordo com a necessidade) 
- Tipo de indice utilizado e motivo da escolha (via comentário no script ou readme) 

 

**Parte 2 - Utilização de procedures para manipulação de dados em Banco de Dados** 

Objetivo: 

Criar uma procedure que possua as instruções de inserção, remoção e atualização de dados no banco de dados. As instruções devem estar dentro de esrtuturas condicionais (como CASE ou IF). 

Além das variáveis de recebimento das informações, a procedure deverá possuir uma variável de controle. Essa variável de controle irá determinar a ação a ser executada. Ex: opção 1 – select, 2 – update, 3 – delete. 

 

Sendo assim, altere a procedure abaixo para receber as informações supracitadas. 

 

Entregável: 

Script SQL com a procedure criada e chamada para manipular os dados de universidade e e-commerce. Podem ser criados dois arquivos distintos, assim como a utilização do mesmo script para criação das procedures. Fique atento para selecionar o banco de dados antes da criação da procedure. 

 

E agora... Finalizou seu desafio ? 

Adicione o link do github com o projeto e submeta para avaliação.
