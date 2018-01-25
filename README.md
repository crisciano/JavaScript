## Sinopse
Documentação de javaScript nativo

## Exemplo de código

javaScript...

```javascript
var d = document;
<!-- element é o elemento class selecionado -->
var exemplo = d.querySelector(element);
<!-- element é id do elemento selecionado -->
var exemplo = d.getElementById(element);
<!-- elemento de uma lista de itens -->
var exemplo = exemplo.querySelectorAll(element)
<!-- alterar textos -->
exemplo.innerText = texto;
<!-- alterar o placehoder do input -->
exemplo.placeholder = 'texto';
<!-- alterar atributo -->
exemplo.setAttribute('type', 'email');
<!-- toggle classes -->
exemplo.classList.toggle('hidden');
<!-- remover classe css -->
exemplo.classList.remove('ativo');
<!-- adicionar classe css -->
exemplo.classList.add('ativo');
<!-- alterar style css -->
exemplo.style.height = ''
exemplo.style.width = ''
exemplo.style.padding = ''
exemplo.style.left = ''
exemplo.style.right = ''
<!-- pegar o valor style css -->
exemplo.style.height
exemplo.style.width
exemplo.style.padding
exemplo.style.left
exemplo.style.right
<!-- pegar o comprimento do elemento -->
exemplo.offsetWidth;
<!-- pega a altura do elemento -->
exemplo.offsetHeight;
<!-- element e o atribudo ao qual se quer o valor -->
exemplo.getAttribute(element)
<!-- pega o elemento filho -->
exemplo.children
<!-- pega o tamanho do elemento -->
exemplo.length
<!-- alterar a img de background -->
exemplo.style.backgroundImage = url('img/img.jpg');
<!-- pega o scroll no eixo y -->
window.pageYOffset;
<!-- pega o scroll no eixo x -->
window.pageXOffset;
<!-- adicionar um click no elemento -->
exemplo.addEventListener('click', function(){});
<!-- pega o eventos de scroll -->
window.addEventListner('scroll' function(){}, false)
```
