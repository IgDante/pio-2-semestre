# PIO - Lógica de Programação


### Hello world

JavaScript

<aside>
💡 `**console.log(“Hello world”)**`

</aside>

Console

<aside>
⚠️ `**Hello World**`

</aside>

---

### Criação de variáveis

<aside>
⚠️ `**const`    /* Variável constante. */**

</aside>

<aside>
⚠️ `**let`       /* Pode ser atualizada. */**

</aside>

- **Exemplo:**
    
    ```jsx
    const nome = "Mariana"     /* Tipo string */
    const idade = 18           /* Tipo number */
    ```
    

---

### Operadores aritméticos

- [ ]  Sinais.
- **Exemplo:**
    
    
    JavaScript:
    
    ```jsx
    const x = 5;
    const y = 6;
    let resultado = x+y;
    console.log(resultado);
    ```
    
    ```jsx
    const x = 5;
    const y = 6;
    let resultado = x*y;
    console.log(resultado);
    ```
    
    ```jsx
    const x = 5;
    const y = 6;
    let resultado = x%y;
    console.log(resultado);
    ```
    
    Console:
    
    ```jsx
    11
    ```
    
    ```jsx
    30
    ```
    
    ```jsx
    5
    ```
    
- **Tabela:**
    
    
    | Nome | Operador encurtado | Significado |
    | --- | --- | --- |
    | Atribuição | x = y | x = y |
    | Atribuição de adição | x += y | x = x + y |
    | Atribuição de subtração | x -= y | x = x - y |
    | Atribuição de multiplicação | x *= y | x = x * y |
    | Atribuição de divisão | x /= y | x = x / y |
    | Atribuição de resto | x %= y | x = x % y |
    | Atribuição exponencial | x **= y | x = x ** y |
    | Atribuição bit-a-bit por deslocamento á esquerda | x <<= y | x = x << y |
    | Atribuição bit-a-bit por deslocamento á direita | x >>= y | x = x >> y |
    | Atribuiçãode bit-a-bit deslocamento á direita não assinado | x >>>= y | x = x >>> y |
    | Atribuição AND bit-a-bit | x &= y | x = x & y |
    | Atribuição XOR bit-a-bit | x ^= y | x = x ^ y |
    | Atribuição OR bit-a-bit | x |= y | x = x | y |

---

### Operadores de comparação

- [ ]  Valores e variáveis.
- [ ]  Verdadeiro ou Falso.
- **Exemplo**
    
    
    JavaScript:
    
    Console:
    
    ```jsx
    const idade1 = 18;
    const idade2 = 20;
    
    /* Idade 1 é menor que a idade 2? */
    ```
    
    ```jsx
    const idade1 = 18;
    const idade2 = 20;
    
    /* idade 1 é maior que a idade 2? */
    ```
    
    ```jsx
    **True**
    ```
    
    ```jsx
    **False**
    ```
    
- **Tabela**
    
    
    | Operador | Descrição | Exemplos que retornam verdadeiro |
    | --- | --- | --- |
    | Igual (==) | Retorna verdadeiro caso os operandos sejam iguais. | 3 == var1 "3" == var1 3 == '3' |
    | Não igual (!=) | Retorna verdadeiro caso os operandos não sejam iguais. | var1 != 4 var2 != "3" |
    | Estritamente igual (===) | Retorna verdadeiro caso os operandos sejam iguais e do mesmo tipo. Veja também Object.is e igualdade em JS (en-US). | 3 === var1 |
    | Estritamente não igual (!==) | Retorna verdadeiro caso os operandos não sejam iguais e/ou não sejam do mesmo tipo. | var1 !== "3" 3 !== '3' |
    | Maior que (>) | Retorna verdadeiro caso o operando da esquerda seja maior que o da direita. | var2 > var1 "12" > 2 |
    | Maior que ou igual (>=) | Retorna verdadeiro caso o operando da esquerda seja maior ou igual ao da direita. | var2 >= var1 var1 >= 3 |
    | Menor que (<) | Retorna verdadeiro caso o operando da esquerda seja menor que o da direita. | var1 < var2 "12" < "2" |
    | Menor que ou igual (<=) | Retorna verdadeiro caso o operando da esquerda seja menor ou igual ao da direita. | var1 <= var2 var2 <= 5 |

---

### **Condicional**

- [ ]  If(Se) … Else(Senão).

<aside>
💡 `**if(condição) {Afirmação1} else {Afirmação2}**`

</aside>

JavaScript: 

Console:

```jsx
const idade = 18;

if (idade => 18) {
console.log("Pode entrar")
} else {
console.log("Não pode entrar")
}

/* Como a idade minima é de 18 
anos ele pode entrar */
```

```jsx
**Pode entar**
```

- [ ]  Múltiplas condicionais.

<aside>
💡 `**if(condição) {Afirmação1} else if {Afirmação2} else if {Afirmação3} else {Afirmação4}**`

</aside>

---

### Loop

- [ ]  For.

<aside>
💡 `**for[expressaoinicial]; [condiçao]; [incremento]; [declaraçao]**`

</aside>

- Exemplo:
    
    
    JavaScript:
    
    Console:
    
    ```jsx
    for(i = 0; i <= 1000; i++){
        if(i % 2 == 0)}
    
    /* Imprime na tela somente 
    números pares de 0 a 1000 */
    ```
    
    ```jsx
    **0
    2
    4
    ...
    1000**
    ```
    

---

### Objeto Global

- [ ]  Array.
- [ ]  Objetos.

<aside>
💡 `**var nomeArray = [element0, element1, ..., elementN]**`

</aside>

---

## Links

### Repositório:

![qrcode_38504868_0346082b0b2ff14356725aaa958265b5 (3).png](qrcode_38504868_0346082b0b2ff14356725aaa958265b5_(3).png)

[IgDante - Overview](https://github.com/IgDante)

### RocketPay:

![qrcode_38504868_0346082b0b2ff14356725aaa958265b5 (2).png](qrcode_38504868_0346082b0b2ff14356725aaa958265b5_(2).png)

[Rocketpay](https://explorer-lab-01-delta-one.vercel.app/)
