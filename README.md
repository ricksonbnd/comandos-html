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

1. `<br>` quebra de texto
1. `<i>`*italico*`<i>`
1. `<strong>` **negrito** `</strong>`
1. `<u>` sublinhado `</u>` sublinhado
1. `<sup>` sobrescrito `<sup>` sobrescrito
1. `<input/>` Abre uma caixa de do tipo de input, precisa definir um atributo do `type="name"`
1. `<img/>` mostra uma imagem, precisa definir um url ou diretorio com o atributo `src="name"`
1. `<a>` texto descritivo `</a>`ancarando a algum lugar, usado com `href="link"` vai criar um hyperlink
1. `<form>` cria um formulario, utiliza atributos.
1. `<button>` cria um botão, utiliza atributos.
1. `<label>`nome`</label>` serve para dar um nome para algo em seguida.

### ATRUBITOS

O Java Scrip (JS) tem a capacidade de ler o html e ler certo identificador como `id` e modificar seu valor via linha de código.

1. `id="nameText"` é um identificador para o JS.
1. `style="nameText"` é um identificador para CSS para formatar os atributos.
1. `class="nameText"` é um modificador global, para mudar tudo que tiver esse idenficador.
1. `type="nameText"` modificador dentro input. Podendo ser tipo `text` para abrir caixa de texto. `number` para abrir um input numerico. `color` para abrir um input de cor.
1. `src="nameText"` define um URL ou diretorio.
1. `width="number"` define um tamanho para o comando.
1. `href="http://link.com"` define um link para ser acessado com `<a>`
1. `target="_targetName"` utilizando com o comando `<a>` o _name define como a página será aberta. `self` para abrir na mesma página. `_blank` para uma nova aba.
1. `title="nameText"` define um texto de tooltip o texto "nameText"
1. `name="nameText"` associa um nome ao name passa ser identificado atráves de JS.
1. `value="valueName"` determina um valor pré-selecionado para alguma váriavel. Pode ser um texto, cor, número, etc.
1. `checked` determina o valor true a alguma checkbox ou radio.

## TAG ESPECIFICAS

### TAG `<FORM>`

É para trabalhar formularios no lado client-side. Onde o usuário preenche campos.
Trabalha com a o comando `<imput>` e os atribulos `type="text"` `type="number"` `"type="password"`. É necessário associar um `name=name` para trabalhar com JS.

`action="URLname"` é para onde o form vai ser enviado.

`<button>` é um comando que cria um botão para o usuario executar/enviar o código

`method="methodName"` é um atributo do `<form>` para definir o metodo que as informações iram ser enviadas, também muda o texto da URL, podendo esconder os dados inseridos.

`target="targetName` pode-se utilizar os atributos de target para forçar abrir a página em nova janela, em uma nova aba ou na mesma página.

`autocomplete="on/off"` atributo para reutilizar as informações preenchidas anteriormente. Esse atributo pode sobreescrever o recurso do navegador autopreencher nativo. Defina entre `on` ou `off`. Grava brevemente, util quando aperta o comando "voltar" apos ter enviado.

`onsubmit="eventName"` define um evento para executar ao dar o submit no formulario, é acessada através de JS.

## TAG `<INPUT>`

Há vários tipos de `input`, alguns funcionam em certos navegadores e entros não. Embora haja conveção entre os navegadores não há 100% de contabilidade entre eles.

`<input type="text">` Campo texto que comprende letras, números e caracteres especiais.

`<input type="number">` Campo para números. Pode adiciona o atributo `min="numberMin"`, `max="numberMax"` ou `step="number"` de quanto em quanto número ira váriar por click.

`<input type="button">` cria um botão. Utilizando atributo `value="textName"` escreve um texto dentro do botão. Ele tem a mesma função que a tag `<button>`

`<input type="range">` cria um campo scroll, pode adicionar atributo `min`, `max` e `value`.

`<input type="color">` abre um campo de cor.

`<input type="email">` abre um campo para email. Os navegadores apresentaram mensagem de erro nativas para caso não digite o @ no campo.

`<input type="url">` abre um campo para url. Parecido como email, os navegadores vão apresentar erro caso não apresente caracteristicas como "https://"

`<input type="date">` abre um campo para data. Cada navegador terá um calendário nativo para apresentar para o usuário.

`<input type="week">` abre um campo para semana, mas não tem compabilidade com todos navegadores, é muito pouco usada.

`<input type="month">` abre um campo para mês.

`<input type="checkbox">` cria uma caixa de seleção.

`<input type="radio">` cria opção de seleção onde só uma das opções pode ser selecionada.  É necessário possuir o atributo `name="nameText"` para funcionar.

`<input type="hidden">` cria uma campo escondido, não aparece para o usuário, mas a informação é enviada para o servidor.

`<input type="file">` campo de enviar arquivos. Pode usar o atributo `multiple` para permitir o envio de vários arquivos ao mesmo tempo.

`<input type="search">` abre um campo texto para busca. Possui um "x" na caixa para limpar o texto. Não funciona em todos navegadores.

## ATRIBUTO `CHECKBOX` E `RADIO`

Esse atributo de botão deve ser trabalhado com certo cuidado para ser útil. O `checkbox` deve ter um `name="nameText[]"` de forma de matrix para quando poder enviar uma matrix das opções escolhidas para o serve-side. Cada checkbox deve ter um `value` que diferencia de outros checkbox

O atributo `radio` deve ter um `name="nameText"` com `nameText` iguais entre as seleções pois as opções da seleção de `radio` operam na função "um ou o outro", para assim quando uma das opções for marcada, a outra é desselecionada. E apresentar um `value` que será enviado para server-side.
