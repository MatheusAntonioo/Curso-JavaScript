# Operadores

- Soma - `+`
- Subtração - `-`
- Multiplicação - `*`
- Divisão - `/`

## Precedência

Primeiro tudo que está dentro dos `()`

Depois o que for de `Multiplicação` e `Divisão`

E por último `Adição` e `Subtração`

# Atribuições

```javascript
let num = 0
num + 1        //adiciona um valor na variável
num++          //adiciona mais um no valor da variável (pode ser - também)
++num          // também adiciona um na variável, mas é mais usado dentro da função

// +=, -=, *=, /=
// é uma forma mais limpa de adicionar, subtrair, multiplicar e dividir 

let num = 0

num += 2 // adiciona 2 na variável
num *= 2 // multiplica a variável por dois
```

# Comparações

Servem para comparar dois valores e/ou variáveis.

- Igual - `==`
- Diferente - `!=`
- Menor - `<`
- Menor igual - `<=`
- Maior - `>`
- Maior igual - `>=`

Uma comparação sempre retornará verdadeiro ou falso:

```javascript
1 > 2
1 == 1
"A" == "A"
"A" < "B"
```

Para variáveis:

```javascript
const idade = 16
const limite = 18

idade >= limite
```

# Comparação estrita (idêntico)

O JavaScript tenta converter dados, por isso o uso do `==` pode ocasionar problemas.

Ex:

```javascript
"1" == 1
1 == true
null == undefined
```

Para solucionar este problema utilizamos a comparação estrita (idêntico).

```javascript
"1" === 1
1 === true
null === undefined
null !== undefined
```

# Falsy and Truthy

Ref.:

- https://developer.mozilla.org/en-US/docs/Glossary/Falsy
- https://developer.mozilla.org/en-US/docs/Glossary/Truthy

O valor é considerado falso quando:

```
false
0
-0
0n
""
''
``
null
undefined
NaA
```

O valor é considerado verdadeiro quando:

```
true
{}
[]
1
1.2
"0"
"false"
-1
-1.2
Infinity
-Infinity
```

# Operadores Lógicos

- E - `&&`
- OU - `||`
- Não - `!`
