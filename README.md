# HTML RESUMO

Instalar Live Server no Visual Studio

Iniciar com o comando `html:5`. Abrindo um arquivo html e escreva `html:5` e aperte "ENTER", assim o arquivo é configurado nos padroes de html 5.

Tecla F12 no Google Chrome para abrir as ferramentas de desenvolvedor.

A pagina **index.html** é a página principal, por convenção.

Para fazer previw das modificações, click com lado direito do mouse em cima do arquivo no Visual Studio e click em "Abrir com Live Server".

Nem todas tags tem tags de fechamento como `<input type="text   />`

## PRINCIPAIS TAGS

Melhores referencias para html no site [w3schools.com](w3schools.com)

1. O que tiver entre `<html>` e `</html>` são vai ser executado como html.
1. O que tiver entre `<head>` e `</head>` são configurações que vão ser carregadas primeiro.
1. `<title>` O titulo do arquivo. `<title>` Titulo que aparecar na aba. O titulo do arquivo, fica na parte `<head>`.
1. O que tiver entre `<body>` e `</body>` são o que vai aparecer para o usuario.
1. `<h1>` e `</h1>`  é uma tag de título, assim como `<h2>` e `<h3>` para subtitulos, e assim por diante.
1. `<p>` e `</p>` é um paragrafo.
1. `<blockquote>` e `</blockquote>` para citações.
1. `<ol>` e `</ol>` lista ordenada de `<li>`, com marcadores númericos
1. `<ul>` e `</ul>` lista não ordenada de `<li>`, os marcadores são bolinhas.
1. `<li>` e `</li>` lista index

### COMANDOS HTML

1. `<i>`*italico*`<i>`
1. `<strong>` **negrito** `</strong>`
1. `<u>` sublinhado `</u>` sublinhado
1. `<sup>` sobrescrito `<sup>` sobrescrito
1. `<input/>` Abre uma caixa de do tipo de input, precisa definir um atributo do `type="name"`
1. `<img/>` mostra uma imagem, precisa definir um url ou diretorio com o atributo `src="name"`
1. `<a>` texto descritivo `</a>`ancarando a algum lugar, usado com `href="link"` vai criar um hyperlink

### ATRUBITOS

O Java Scrip (JS) tem a capacidade de ler o html e ler certo identificador como `id` e modificar seu valor via linha de código.

1. `id="name"` é um identificador para o JS.
1. `style="name"` é um identificador para CSS para formatar os atributos.
1. `class="name"` é um modificador global, para mudar tudo que tiver esse idenficador.
1. `type="name"` modificador dentro input. Podendo ser tipo `text` para abrir caixa de texto. `number` para abrir um input numerico. `color` para abrir um input de cor.
1. `src="name"` define um URL ou diretorio.
1. `width="number"` define um tamanho para o comando.
1. `href="http://link.com"` define um link para ser acessado com `<a>`
1. `target="_name"` utilizando com o comando `<a>` o _name define como a página será aberta. `self` para abrir na mesma página. `_blank` para uma nova aba.
1. `title="name"` define um texto de tooltip o texto "name"
