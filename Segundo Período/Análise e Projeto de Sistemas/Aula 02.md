# Aula 02 - 11/10/24

# UML (Unified Modeling Language)

> É uma linguagem utilizada para a modelagem de projetos usando diagramas

## Diagrama de Casos de Uso

> Identifica as principais funcionalidades do sistema e a interação dessas funcionalidades com o usuário. Não se aprofunda nos detalhes técnicos que dizem como o sistema faz. Pode ser usando no **Documento de Requisitos**

## Elementos dos Casos de Uso
* Descrevem como os usuarios interagem com o sistema

### Atores

> Representam os papeis desempenhados por elementos externos ao sistema.
> São aqueles que **interagem com o sistema**.

### Caso de Uso

> Representa uma funcionalidade do sistema (requisito funcional).
> É Iniciado por um ator (um caso de uso é sempre um verbo).

### Relacionamentos

* Associação: Indica que há uma interação entre um caso de uso e um ator. Um ator pode se comunicar com vários casos de uso. Não se usa seta na representação.
* Generalização: É quando um ator 'herda' um comportamento de outro ator. Ex: um gerente faz o papel de atendente quando o atendente não está.
* Generalização de Casos de Uso: O caso de uso filho herda o comportamento e significado do caso de uso pai. O caso de uso filho pode incluir ou sobrescrever o comportamento do caso de uso pai.
* Dependência:
	- Extends
	- Inclusão: Caso de Uso necessário para que outro caso de uso seja realizado com sucesso
## Fronteira do Sistema

> É a área de atuação de um sistema.