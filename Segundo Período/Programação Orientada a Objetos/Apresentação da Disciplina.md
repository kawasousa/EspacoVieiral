# Apresentação da disciplina
Temas que o professor gosta de abordar:
- Aplicações Financeiras;
- Rede Social;
- Jogos de RPG.

## Trabalho final:
Uma pequena rede social.

## Porque estudar novos paradigmas
- Maior habilidade de projetar novas linguagens;
- Abstrair melhor os problemas.

## Abstração (Simplificação)
- Definir apenas elementos essenciais para um sistema;
- Definir níveis de complexidade dos elementos;
- Ignorar aspectos irrelevantes.
### Exemplo
Sintetizar um veículo a apenas seus dados importantes para aplicação, como chassi, nome do dono, modelo, etc.

## Organização da classe

Declaração de classe
```ts
class NomeDaClasse{
	atributo1: string;
	atributo2: number;

	metodo1(){
		return this.atributo1;
	}

	metodo2(parametro: number){
		this.atributo2 = parametro;
	}
}
```

Instanciando um objeto
```ts
var objeto = new NomeDaClasse();
objeto.atributo2 = 0;
objeto.metodo2(1);
var variavel = objeto.metodo1()
```
