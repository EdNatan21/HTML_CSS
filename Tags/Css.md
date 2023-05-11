## Texto :
* Color = altera a cor de primeiro plano de um texto.
* Text-transform = Aplicar transformações ao texto:
    - Capitalize: A primeira letra de cada palavra em maiúscula.
    - None: Remove todas as transformações.
    - Uppercase: deixa todas as letras em maiúscula.
    - Lowercase: deixa todas as letras em minúscula.
* Text-decoration = Aplicar decorações ao texto:
    - None: Remove todas as decorações.
    - Underline: aplica uma linha abaixo do texto.
    - Overline: aplica uma linha sobre o texto.
    - Line-through: risca o texto.
* Text-shadow = Aplicar efeitos de sombra ao texto:
    - (distância horizontal da sombra "px", deslocamento vertical "px", solidez "px", Cor da sombra).
* Text-align = Controlar como o texto será alinhado dentro do elemento:
    - Left: justifica o texto a esquerda.
    - Right: justifica o texto a direita.
    - Justify: ajusta o espaço entre as palavras para que o texto ocupe todo o espaço disponível em uma linha.
* Vertical-align = Alinhamento vertical
	- (Top,Middle,Bottom)
* Font = Fonte:
    - Font-family: Aplicamos uma fonte ao texto.
    - Font-size: Altera o tamanho do texto.
    - Font-weight:  alterar o peso de um texto.
    - Font-Variant: Variantes de fonte.
* Line-height:  Altura da linha de um texto.
* Letter-spacing: Controlar o espaço entre as letras.
* Word-spacing: Controlar o espaço entre as palavras de um texto.
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Box Model:
* Box-sizing = Valor da propriedade:
    - Content-box: O valor padrão da box-sizing, definidos por height e width.
    - Border-box: Define que a altura e largura de um elemento deve levar em consideração também a sua borda e        preenchimento.
* Width: Largura.
* Height: Altura.
    - Max-W/H: Controla quanto ele poderá crescer.
    - Min-W/H: Controla quanto ele poderá encolher.
* Padding: Controla a área de preenchimento de um elemento:
    - (Top,Right,Bottom,Left)
* Margin: Controla a área de margem de um elemento:
    - (Top,Right,Bottom,Left)
* Border: Define o estilo da borda de um elemento:
    - (Largura,Estilo,Cor)
* Border-width: Determinar a largura da borda:
    - (Top,Right,Bottom,Left) / (Thin,Medium,Thick)
* Border-style: Determinamos como a borda do elemento será apresentada:
    - (Solid "Sólida",Dotted "Pontilhada",Dashed "As duas")
* Border-Collapse: define se as bordas da tabela devem ser recolhidas em uma única borda ou ser separado. 
    - (Seperate,Collapse)
* Display: flex; 
    - flex-wrap: wrap;
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Background:
* Background color: Atribuir cor ao fundo do elemento.
* Background-image: Mudar fundo de elemento escolhido.
	- Url = colocar uma imagem de fundo
	- linear-gradient = Fazer um degradê
* Background-repeat = Repetirá a imagem até que ela preencha todo o espaço disponível:
    - (Repeat-x/Repeat-y,no-repeat)
* Background-position = Determinar o quando essa imagem se deslocará em relação a essa posição inicial:
    - (X/Y) = (Px/Top,Left,Bottom)
* Background-size = Permite realizar pequenas modificações na imagem de um elemento:
    - (Contain/Cover)
* Background-attachment = Permite controlar como uma imagem se comporta em relação a barra de rolagem da página ou do   elemento no qual ela está contida:
    - (Scroll,Fixed,Local)
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Overflow:
* Overflow = Conteúdos muito grandes possam caber dentro de uma página através do uso de barras de rolagem:
    - Visible: Mostra todo conteúdo que for colocado dentro do elemento.
    - Hidden: É utilizado quando queremos esconder a parte de um elemento para que ele não passe do tamanho determinado.
    - Scroll: Tem o mesmo comportamento do hidden, ocultando o conteúdo no limite do tamanho definido, porém, ele adiciona - também uma barra de rolagem, permitindo acesso ao restante do conteúdo.
    - Auto: Por sua vez, tem o mesmo comportamento do scroll: a única mudança é que o scroll só será adicionado caso seja necessário.
* Overflow-x = Aplicar o overflow apenas na horizontal.
* Overflow-y = Aplicar o overflow apenas na vertical.
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Import:
* !important = Esta regra substituirá todos os estilos que já foram aplicados no elemento referente a propriedade que a regra está sendo adicionada.
* @FontFace = especifica uma fonte personalizada com a qual exibir texto.
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## List:
* Line-height = Define o espaçamento entre as linhas (itens) da lista. (%)
* list-style-type = Define o tipo de marcador que vai aparecer na lista. (Circle,Disc,Square)
* list-style-position = Alterar posicão
* Columns = Dividir em colunas
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Position:
* Float = A propriedade é usada para posicionamento e formatação de conteúdo:
    - (left,right,none,inherit)
* Position = Posicionamento:
    - (Relative,Absolute,Sticky)
    - Top / Left - Caso a posição for absoluta
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Transform:
* A propriedade aplica uma transformação 2D ou 3D a um elemento.
* Esta propriedade permite que você gire, escala, movimento, inclinação, etc., elementos.
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Pseudo-Classe:
* :Hover = possibilita um elemento ter o seu estilo alterado através da ação do usuário, quando o próprio passa o cursor do mouse sobre o elemento.
	- Cursor: Mudar o tipo do cursor 
	- (Pointer)
* nth-child- O seletor corresponde a cada elemento que é o n-ésimofilho de seu pai.
	(n/odd/even)
* ::-webkit-scrollbar = Retira a tela de rolagem
* :focus-within = Esse seletor é útil, para tomar um exemplo comum, para destacar um contêiner.
* Para formatar um input no css precisa colocar "[]" ex:
 form > input[type=submit]
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Inline and Block
* Block-Level:
    - address       div         footer      ul
    - article       dl          form        video
    - aside         dt          h1 - h6     tfoot
    - blockquote    fieldset    header      table
    - canvas        figcaption  hr          section
    - dd            figure      li      
    - main          nav         noscript
    - ol            p           pre

* Inline-Level:
    - a             abbr        acronym     b
    - bdo           big         br          buttom
    - cite          code        dfn         em
    - i             img         input       kbd
    - label         map         object      output
    - q             samp        script      select
    - small         span        strong      sub
    - sup           textarea    time        tt
    - var
