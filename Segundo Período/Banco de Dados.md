# Banco de Dados I

## Aula de Introdução

> Gerenciar Banco de Dados é como trabalhar na fundação de um projeto.

Banco de Dados I 
- Organização e lógica de armazenamento de dados
Banco de Dados II
- Desempenho

> Dados são armazenados porque precisam ser usados e por isso precisam ser organizados.

### Assuntos

- Modelagem de dados
- c
- c
- c

## modelagem de BD

### → O que é modelagem de Banco de dados?

Modelagem de Banco de Dados é o processo de criar um **modelo** ou **estrutura lógica** de como os dados serão armazenados, acessados e gerenciados. Ela envolve, representar entidades, seus atributos e relacionamentos para organizar os dados de forma eficiente.

### → Principais modelos de Banco de dados

 > Modelo Conceitual:

* Representação inicial dos dados que foca em entidades (objetor importante, como cliente, produto) e relacionamento entre eles

*  Ferramenta comum: Diagrama de entidade Relacionamento

> Modelo Logico:
 
Detalhamento do modelo conceitual para ser implementado em um sistema de banco de dados.
Nesse nível, definimos chaves primários, chaves estrangeiros tipos de dados, entre outros.

> Modelo Físico

* Representação física do banco de como de será implementado dador, mostrando no sistema, incluindo. tabelas, índices e outros detalhes técnicos.

### → Componentes da Modelagem:

> Entidades:

- Objetos ou conceitos sobre os quais armazenamos os dados (ex: Cliente, Pedido)

>  Atributos:

- Característicos dos entidades (ex: Nome do cliente, Dato do pedido)

> Relacionamentos: 

- Conexões entre entidades (ex: Um cliente pode fazer vários pedidos)

>Cardinalidade :

- Determina a quantidade de ocorrências em um relacionamento. (ex: Um para muitos, muito para muito).

### → Normalização:

* Processo de organização dos dados um tabelas para eliminar redundâncias e melhores relações na integridade dos dados.


## MODELO CONCEITUAL


![[Pasted image 20241002094042.png]]
								**(Figura 1.0)** 

- As tabelas do nosso bando de dados são representados pelo retângulo das entidades exemplificadas na figura 1.0. 

- Nosso relacionamento entre as Entidades é representado pelo losango na figura 1.0.

- Nossos Atributos são representados por essa bolinhas ligadas a cada entidade.

- Tendo como um dos nossos atributos um Chave primaria. 

- Como nossa cardinalidade, temos os números expressos ao lado de cada entidade                (Exemplo: (1,1) , (0,N))

→ OBS: É importante ser retratado que a cardinalidade nesse Diagrama de ER(Entidade e Relacionamento) é **(1,n)**.

→ Dica: Para descobrirmos a Cardinalidade do Diagrama de ER, devemos nós atenuar ao termo após a virgula em cada entidade. No exemplo acima temos (1,1) e (0,n), com isso há uma cardinalidade do diagrama de **(1,n)**.

## Outros Exemplos: 

![[Pasted image 20241002100223.png]]
								**(Figura 2.0)** 

→ Dica: Para descobrirmos a Cardinalidade do Diagrama de ER, devemos nós atenuar ao dois termos após a virgula em cada entidade. No exemplo assim temos (1,n) e (1,n), com isso temos uma cardinalidade do diagrama de **(n,n)**.

Outros Exemplos: 

![[Pasted image 20241002100338.png]]
								**(Figura 3.0)** 
								
→ Dica: Para descobrirmos a Cardinalidade do Diagrama de ER, devemos nós atenuar ao dois termos após a virgula em cada entidade. No exemplo assim temos (1,1) e (1,1), com isso temos uma cardinalidade do diagrama de **(1,1)**.


## MODELO LOGICO

- Antes de termos conhecimento de como passamos de um modelo conceitual para um modelo logico temos que ter noção sobre Mapeamento de Cardinalidades.

## → Mapeamento

- (1:N) → O lado N recebe a FK (Chave Estrangeira)
- N:N → Criar uma Nova Tabela que recebe a chave primaria das outras duas tabelas analisadas
- (1:N) → União das Tabelas Analisadas

## → Representação do modelo Logico 

- Tendo aprendido e memorizado o Mapeamento das Cardinalidades vamos passar do modelo Conceitual para o modelo Lógico:

- (1:N) → O lado N recebe a FK (Chave Estrangeira) com o Exemplo da figura (1.0)

![[Pasted image 20241002101052.png]]


- N:N → Criar uma Nova Tabela que recebe a chave primaria das outras duas tabelas analisadas com o Exemplo da Figura (2.0)

![[Pasted image 20241002101206.png]]


- (1:N) → União das Tabelas Analisadas com o Exemplo da figura (3.0)

![[Pasted image 20241002101307.png]]