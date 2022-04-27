# Learning Week - Dia 2

Atualmente me encontro revisando algumas coisas básicas do JavaScript seguindo o cronograma de um curso pago. Como o evento começou no meio, continuarei anotando de onde parei.

## Trocando valores de váriaveis em sequência

Apesar de ser um assunto que acredita ser pouco usado, até o momento não sabia da possibilidade:

No caso de ser necessário a troca de múltiplos valores de variáveis pode ser usado o seguinte método.

Ex.: Existem as variáveis A, B e C; todas com seus respectivos valores, agora troque a ordem das variáveis sem as declarar novamente.

```
let varA = 'A'; // Agora precisa ser B
let varB = 'B'; // Agora precisa ser C
let varC = 'C'; // Agora precisa ser A
```

Sendo assim é possível a utilização de colchetes ( [] ) para a resolução do problema:

```
let varA = 'A';
let varB = 'B';
let varC = 'C';

[varA, varB, varC] = [varB, varC, varA]
```
Sendo assim agora as variáveis possuem os valores desejados e não precisaram ser declaradas novamente.

OBS.: É importante ressaltar que os valores no segundo colchete precisam ser em ordem com os valores que vão ser mudados.

