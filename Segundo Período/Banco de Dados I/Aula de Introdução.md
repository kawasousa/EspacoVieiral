# Aula de Introdução

> Gerenciar Banco de Dados é como trabalhar na fundação de um projeto.

Banco de Dados I 
- Organização e lógica de armazenamento de dados
Banco de Dados II
- Desempenho

> Dados são armazenados porque precisam ser usados e por isso precisam ser organizados.
## Assuntos
- Modelagem de Banco de Dados
- Normalização
- Algebra Relacional
- SQL - Linguagem de Consulta Estruturada

- A parte prática da matéria será feita em [PostgreSQL](https://www.postgresql.org)
## BD Relacionais vs BD Não Relacionais
Banco de Dados SQL (relacionais) usam linguagens que se comunicam com banco de dados a partir de ordenamentos e instruções.

Banco de Dados NoSQL (não relacionais) são usados em contextos em que a facilidade de implementação não são prioridade e a rigidez de dados é um problema.

## Sistema Gerenciador de Banco de Dados (SGBD)
### Do banco de dados ao usuário
Bancos de dados podem ser acessados diretamente por aplicações, recebendo instruções e devolvendo informações. Essa relação, porém, limita o fluxo de dados por não permitir que múltiplas aplicações façam requisições ao mesmo tempo. Numa relação Aplicação-BD, dados são alterados e a falta de um gerenciador pode gerar dados inconsistentes.
A partir dessa 
### O que é um SGBD
SGBD é 
### Responsabilidades de um SGBD
- Acesso concorrente - Múltiplas aplicações acessando o mesmo dado ao mesmo tempo.
- Tolerância a falha - Evitar que informações erradas surjam no caso de parada do sistema ou erro na sequência de instruções.
- Controle de acesso - Todas as aplicações estão sujeitas às mesmas regras
## Detalhes e Considerações
### Links e Referências
[Guia SGBD - fiveacts](https://www.fiveacts.com.br/sgbd)

[O que é Database Clustering- HarperDB](https://www.harperdb.io/post/what-is-database-clustering#:~:text=Clustering%20with%20HarperDB-,What%20is%20a%20database%20cluster%3F,database%20server%20called%20the%20master.)

[Sobre o PostgreSQL - PostgreSQL](https://www.postgresql.org/about/)

[Instalando o PostegreSQL e criando um banco de dados - Canal Hashtag Programação](https://youtu.be/L_2l8XTCPAE?si=26VFnS2mN6-xplWL)
