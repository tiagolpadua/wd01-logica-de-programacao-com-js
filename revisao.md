# Revisao

## Dia 1

- Existem diversas linguagens que nos permitem "instruir" o computador
- HTML / CSS / JavaScript sao as linguagens utilizadas nos navegadores

### HTML
- TAGs <tag> </tag>
- h1..h4
- strong
- br
- script

### JavaScript
- alert
- document.write
- Math - round - floor - ceil
- Strings (sequencias de caracteres) - Number - números
- var - permite guardar um valor para ser reutilizado
- .toFixed

> var x;
> x = "foo";
> typeof x;
< "string"
Tipagem inferida

> x = 3;
> typeof x;
< "number"
Tipagem dinamica

7.toString();
var x = 7;
x.toString();

> x = true;
> typeof x;
< "boolean"

> Number.
> String.
> Boolean.

> var x = "a" / 3
> x
< NaN
> typeof x
< "number"
> x == NaN
< false
> isNaN(x)
< true

"foo".length
"foo"[0]

Math.PI


### Chrome
- Developer tools
- Console do JavaScript

## Dia 2
```js
function soma(a, b) {
    var resultado = a + b;
    return resultado;
}

console.log(soma(1, 2));

// Comentário de uma linha

/*
   Comentário de
   várias linhas
*/
```

- jsfiddle.net
- github
- prompt

## Dia 3
- if - uma estrutura de decisão

```js
if (numero == 3) {
    alert("Número é o 3");
} else {
    alert("Número não o 3");
}
```
- parseInt - convertendo texto em número
```js
var x = parseInt("3");
```
- > < <= >= == !=
- && e || 
- recursão - quando uma função chama ela mesma