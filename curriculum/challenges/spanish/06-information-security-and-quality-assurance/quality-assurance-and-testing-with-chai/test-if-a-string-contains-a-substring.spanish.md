---
id: 587d824d367417b2b2512c53
title: Test if a String Contains a Substring
challengeType: 2
videoUrl: ''
localeTitle: Probar si una cadena contiene una subcadena
---

## Description
<section id="description"> Como recordatorio, este proyecto se está construyendo sobre el siguiente proyecto de inicio en <a href="https://glitch.com/#!/import/github/freeCodeCamp/boilerplate-mochachai/">Glitch</a> , o clonado desde <a href="https://github.com/freeCodeCamp/boilerplate-mochachai/">GitHub</a> . #include (en #notInclude) también funciona para cadenas! Afirma que la cadena real contiene la subcadena esperada </section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Todas las pruebas deben pasar
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=13").then(data => { assert.equal(data.state,"passed"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: Elija la aserción correcta - incluir vs. noIncluir
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=13").then(data => {  assert.equal(data.assertions[0].method, "include", "\"Arrow\" contains \"row\"..."); }, xhr => { throw new Error(xhr.responseText); })'
  - text: Elija la aserción correcta - incluir vs. noIncluir
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=13").then(data => {  assert.equal(data.assertions[1].method, "notInclude", "... a \"dart\" doesn\"t contain a \"queue\""); }, xhr => { throw new Error(xhr.responseText); })'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
