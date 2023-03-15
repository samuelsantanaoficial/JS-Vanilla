# Javascript | JS Vanilla


# Caixas de diálogos e alerta
- imprime texto no console
~~~javascript
console.log("texto");
~~~
- caixa de diálogo de alerta
~~~javascript
alert("texto!");
~~~
- caixa de diálago com interação (confirmar / cancelar)
~~~javascript
confirm("texto?");
~~~
- caixa de diálogo para usuário digitar alguma coisa
~~~javascript
prompt("Digite seu Texto:");
prompt("Text","Placeholder");
~~~


# Variáveis
- padrão mas que vaza dos escopos
~~~javascript
var variavel;
~~~
- padrão que não vaza dos escopos
~~~javascript
let variavel;
~~~
- que não pode ser ser alterado o valor
~~~javascript
const variavel = 2023;
~~~


# Literais / Tipos
- Inteiro:
~~~javascript
let num = 12;
~~~
- Real:
~~~javascript
let num = 10.25;
~~~
- Booleanos:
~~~javascript
let a = true;
let b = false;
~~~
- String:
~~~javascript
let texto1 = "texto";
let texto2 = "A";
let texto2 = "Texto, texto texto (...)";
~~~
- Array:
~~~javascript
let array1 = [1, 2, 3, 4, 5];
let array2 = ["a", "b", "c"];
let array3 = ["texto1", "texto2", "texto3"];
let array4 = ["1", 2, "texto", "A", "Uma frase (...)"];

//é possível guardar um array dentro de outro:
let array5 = [["1","2","3"],["4","5","6"],["7","8","9"]];
~~~
- Objeto:
~~~javascript
let obj = {
    propriedade1: "texto",
    propriedade1: 27,
    propriedade3: "B",
    array4: ["7","8","9"],
    funcao1: myFunction1(){
        //code
    }
    funcao1: myFunction1(){
        //code
    }
}
~~~


# Operadores
Operador |Operação          |Exemplo
---------| -----------------|-------
\>	     |Maior que	        |(a > b)
<	     |Menor que	        |(a < b)
\>=	     |Maior ou igual a	|(a >= b)
<=	     |Menor ou igual a	|(a <= b)
==	     |Igual a	        |(a == b)
!=	     |Diferente de	    |(a !== b)
===	     |Idêntico a	    |(a === b)
!==	     |Não idêntico a	|(a !== b)
&&	     |E/and	            |(a && b)
ll	     |Ou/or	            |(a ll b)


# Estruturas condicionais
- if
~~~javascript
if (idade > 18){
    console.log("é de maior de idade");
} else if (idade == 18){
    console.log("tem exatamente 18 anos de idade");
} else {
    console.log("é menor de idade");
}
~~~
- switch
~~~javascript
switch (num) {
    case 0:
        console.log("Janeiro");
        breack;
    case 1:
        console.log("Fevereiro");
        breack;
    case 2:
        console.log("Março");
        breack;
    default:
        console.log("Mês Inválido");
        break;
}
~~~


# Funções
~~~javascript

~~~
