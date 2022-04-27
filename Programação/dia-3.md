# Learning Week - Dia 3

Continuei revisando o básico do JavaScript. Aqui está um resumo dos tópicos que achei mais importantes para serem anotados:

## Pegar elementos específicos de um determinado objeto

Supondo que há um objeto em JavaScript com 2 itens listados nele:

```
let aObject = {
age: 22,
name: "Chris"
}
```

Caso seja necessário pegar algum dos itens individualmente, faz-se a seguinte linha de código:

```
// Será feito com um console log para ilustrar

console.log(aObject.age/name)
```

O mesmo pode ser feito com uma string, nesse caso, vamos pegar uma letra específica:

```
let aString = "A Sample Text"

console.log(aString[9])
```

Fazendo isso o console apresentará a letra "T", no log.

