## Um pouco sobre o trabalho.

Esse foi um projeto executado na disciplina de Construção de Software para Web em que cada aluno teria que fazer uma pagina de um site de acolhimento à refugiadas ucrânianas.

#### Como foi avaliado...

O professor Ricardo Mendes levou em conta a corretude e qualidade do HTML, CSS e JS, e tambem a Responsividade do site!
Cada um valendo 25% da nota do projeto.

## Explicação do JavaScript

O uso do JavaScript nesse projeto foi de maneira bem simples porem eficiente.

### Criando as constantes e chamando classes

>    window.onload = function (){
>    const menu = document.querySelector('.menu')
>    const header = document.querySelector('header')
>    const nav = document.querySelector('nav')

Essa parte do código eu uso o window.onload pra renderizar a pagina e dizer que quando a pagina for carregada eu vou chamar a função que contem essas constantes que vão puxar essas classes do meu css.

### Adicionando o click 

Nessa etapa do código eu digo que quando meu menu for clicado ele vai puxar as classes e então executalas utilizando o toggle como forma de click para que não ocorra um bug e funcione normalmente como um toggle realmente, em que vc clica e desclica. Ou seja quando a classe está "on" ela estiliza os componentes do nosso togle.

>    menu.onclick = (e) =>{
>        header.classList.toggle('on')
>        nav.classList.toggle('on')
>    }
>}
