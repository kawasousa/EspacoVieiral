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
SGBD é uma classificação de programas que define um sistema responsável por gravar, relacionar e manipular dados para o funcionamento de um programa.
### Responsabilidades de um SGBD
- Acesso concorrente - Múltiplas aplicações acessando o mesmo dado ao mesmo tempo.
- Tolerância a falha - Evitar que informações erradas surjam no caso de parada do sistema ou erro na sequência de instruções.
- Controle de acesso - Todas as aplicações estão sujeitas às mesmas regras

### Pra que serve um SGBD
- Criar relação entre tabelas
	- Assim, pode-se obter informações relevantes sobre os dados armazenados.
- Eliminar e copiar arquivos
	- Evitar redundâncias e armazenamento de dados obsoletos.
- Efetuar consultas em tabelas
- Deixar a vida do programador mais fácil
	Todo sistema gerenciador de banco de dados pode ser substituído por uma aplicação dedicada àquele banco de dados. Isso, porém, é mais custoso à equipe de programação.

### Tipos de SGBD
- Relacionais
	Cuja função é conectar dado de diferentes origens
- Não Relacionais
	A estrutura de dados não é previamente definida
- Hierárquico
	Formato mais antigo onde os dados são organizados em uma disposição piramidal
- De Rede
	Cada dado-filho pode ter mais de um dado-pai e a estrutura de dados se assemelha a uma teia de aranha
- Orientado a Objetos
	Modelo mais avançado em que diferentes tipos de dados se mesclam, sendo, por isso, mais caro de implementar
## Detalhes e Considerações
### Links e Referências
[Guia SGBD - fiveacts](https://www.fiveacts.com.br/sgbd)

[O que é Database Clustering- HarperDB](https://www.harperdb.io/post/what-is-database-clustering#:~:text=Clustering%20with%20HarperDB-,What%20is%20a%20database%20cluster%3F,database%20server%20called%20the%20master.)

[Sobre o PostgreSQL - PostgreSQL](https://www.postgresql.org/about/)

[Instalando o PostegreSQL e criando um banco de dados - Canal Hashtag Programação](https://youtu.be/L_2l8XTCPAE?si=26VFnS2mN6-xplWL)
