# DOM

    - Document Object Model
    - Estruturas de um arquivo na web
    - Representa documentos HTML ou XML
    - Interface de programação
    - É essencial para o JS entender o modelo de páginas web

## Para que serve?

    - Alterar a estrutura
    - Alterar o estilo
    - Alterar  conteúdo

## Como ?

    - Disponibilizando API ( Application Programming Interface)
    - Rotinas e padrões estabelecidos
    - Métodos (funções)
    - Arvore de elementos
    - Seletores
    - Objetos (nós)

## Exemplo HTML

    <html>
        <head></head>
        <body></body>
    </html>

## Exemplo Objeto

    objeto = {
        html: {
            head:{
            body:{
                h1: {

                }
            }
            }
        }
    }

## DOM x JS

    - O DOM pode ser usado por outra linguagens
    - Sem o DOM o JS não teria noção da página

### Vantagens de usar o JS

    - Código é executado por navegadores
    - Tornar as paginas dinamicas
    - Evitar requisições desnecessarias (PERFORMANCE)
    - Reagir rapidamente a ações dos usuários
    - SPA ( Single Page Applications)

### Desvantagens de usar o JS ( PURO - Vanilla)

    - Código é executado por navegadores
    - O conteudo NÂO fica visivel para indexadores de busca ( )
    - Alterações em tempo de execução não ficam salvas no documento

### Exemplos 
    Seleciona o objeto e disponibiliza (métodos / funções).callback

    - document.getElementById (id)
    - document.getElementsByTagName('div')
    - document.createElement('div')
    - parentNode.AppendChild (node) // html.appendChild ('body')
    - element.innerHTML (seleciona objeto ou parametro)
    - element.style (seleciona atributos)
    - element.setAttribute('define atributo'). value
    - element.getAttribute('busca atributo')
    - element.addEventListener(observa a informação e atribui funções)
    - window.location [mostra URL da pagina]
    - widow.onload 
    - console.log(exibir funções no console)
    - window.scrollTo(x , y)

### Referências

    - DOM: https://dom.spec.whatwg.org/
    - Tecnologias - JS: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript
    