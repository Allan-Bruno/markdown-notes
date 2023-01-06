
# Maior que ( > )
  Usado para comparar 2 objetos, normalmente usado em valores (lenghts, números etc). Resposta geralmente é dada em booleano

  Ex.:
	console.log(10 > 5) // true
	console.log(10 > 10) // false


## Maior que ou igual a ( >=)
  Mesmo objetivo da anterior, pórem se qualquer um dos objetos for verdadeiro, a expressão inteira é considerada verdadeira.

  Ex.:
    console.log(10 >= 10) // true
    console.log(10 >= 11) // false


# Menor que ( < )
  Mesma lógica de maior que porém para menor que o objeto em questão
	  console.log(11 < 9) // false
	  console.log(11 < 12) // true


## Menor que ou igual a ( <= )
  Mesma lógica de maior que ou igual porém para menor que o objeto em questão
	  console.log(11 <= 11) // true
	  console.log(11 <= 9) // false


# Igualdade ( == )
 Pode ser usado para comparar os valores e retornar um booleano
 Ex.:
	 let num1 = 10;
	 let num2 = 11;
	 console.log(num1 == num2) // false

Não se recomenda usar esse comparador, pois informações de tipos diferentes podem se igualar

## Igualdade estrita ( === )
  * Considera valor e tipo
  É o comparador indicado, pois como citado acima, considera o valor dos itens e seu tipo
  
# Diferente ( != )
Chega a diferença do valor mas não checa o tipo

## Diferente estrito ( !== )
  * Considera valor e tipo
 Mesma lógica de igualdade estrita, porém voltado para a diferença