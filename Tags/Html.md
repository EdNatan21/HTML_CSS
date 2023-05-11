## Tags de Layout:
* h1: até >h6> Define do cabeçalho 1 até o cabeçalho 6;
* head: Define uma informação sobre o documento. (Não aceita mais elementos Child como filho);
* hr: Define uma regra horizontal. (Tem o mesmo nível que um parágrafo, mas também é utilizado para fazer separações e quebras de linha);
* html: Define um documento html;
* body: Define o corpo da página;
* main: Essa tags representam o conteúdo principal do seu corpo;
* div: Define uma seção no documento;
* article: Define um artigo;
* aside: Define o conteúdo além do conteúdo da página;
* embed: Define o conteúdo interativo ou plugin externo;
* figcaption: Define o caption de uma imagem;
* figure: Define um grupo de média e seus captions;
* footer: Define o rodapé de uma página;
* header: Define o cabeçalho de uma página;
* nav: Define os links de navegação;
* section: Define uma área ou seção;
* wbr: Define uma possível quebra de linha;
* br: Quebra de linha.;
* menu: Define uma lista de "menus";
* p: Define um parágrafo;
* title: Define um título do documento:
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Tags de Media:
* audio: Define o conteúdo de som;
* source: Define recursos de mídia;
* video: Define um vídeo;
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Tags de Aplicativos Web:
* canvas: Define gráficos;
* command: Define um botão de comando;
* output: Define os tipos de saída (outputs);
* progress: Define o progresso de uma tarefa qualquer;
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Outras:
* dialog: Define uma conversa ou pessoas falando;
* hgroup: Define informações sobre uma determinada área do documento;
* keygen: Define a key (chave) do formulário;
* mark: Define a marcação de um texto;
* meter: Define a medição dentro de um intervalo pré-definido;
* summary: Define o cabeçalho de dados “detalhe”;
* time: Define uma data ou hora;
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Link:
* link Define uma referência;
    - media (screen "tela",all "tudo")
* a :  pode ser utilizada para criar alguns tipos diferentes de links.
    - href = onde colocamos o endereço do link.
    - target = Esse atributo indica para o navegador onde o link deverá ser aberto. (_self,_blank,).
    - rel = Esse atributo é muito utilizado para fins de SEO, juntamente do valor (nofollow).
    - _blank = É utilizado para abrir links em uma nova aba.
    - _self =  É o valor padrão, e vai abrir o link na página atual.
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Tabelas:
* table: Define uma tabela;
    - cellspacing = Define um espaço externo entre as células
    - cellpadding = Define um espaço interno nas células
* tbody: Define o corpo da tabela;
* td: significa dados da tabela.
* tr: significa linha de tabela.
* tfoot: Define o rodapé da tabela;
* th: significa cabeçalho de tabela:
	Scope (Row,Col)
* thead: Define o cabeçalho da tabela;
    - Col = Especifica propriedades de coluna para cada coluna dentro de um elemento <colgroup>
    - Colspan = Expansão em coluna
    - Rol = Especifica propriedades de uma mesma linha
    - Rowspan = Expansão em linha
    - Colgroup = Especifica um grupo de uma ou mais colunas em uma tabela para formatação	
    - (Tag) Colgroup = Classifica uma coluna com "class"
    - (Span) = define mais de uma coluna
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Formulário:
* form: usado para criar um formulário HTML para entrada do usuário.
    - Autocomplete = sugestão de preenchimento
    - Action = define o local (uma URL) em que os dados recolhidos do formulário devem ser enviados.
    - method = metodo de envio (get,post)
* input: Um elemento pode ser exibido em de muitas maneiras, dependendo do atributo:
    - input type="text" = Exibe um campo de entrada de texto de linha única.
    - input type="color" = Exibe um campo de cor a ser escolhido.
    - input type="range" = define um controle para inserir um número cujo valor exato não é importante.
    - input type="rádio" = Exibe um botão de opção (para selecionar uma das muitas opções).
    - input type="caixa de seleção" = Exibe uma caixa de seleção (para selecionar zero ou mais de muitas opções).
    - input type="submit" = Exibe um botão de envio (para enviar o formulário).
    - input type="button" = Exibe um botão clicável.
    - input type="Password" = Exibe um campo de entrada para senha.
    - input type="Reset" = Exibe um botão para limpar.
    - input type="file" = Define um campo de seleção de arquivo e um Botão "Procurar" para uploads de arquivos.
    - input type="checkbox" - Define uma caixa de seleção.
        - id = Variável recomendada Html e JavaScript
        - name = Variável recomendada  Php
        - required = força usuário a preencher o campo em vazio
        - minlength = Mínimo de caracteres que podem ser digitadas
        - maxlength = Máximo de caracteres que podem ser digitadas
        - size = Número de caracteres a serem mostrados(muda o tamanho da caixa)
        - placeholder = Exibe uma mensagem dentro da caixa
        - min = Valor minímo aceito
        - max = valor máximo aceito
        - step = Exibe um valor inicial
        - moth = Exibe uma data à ser preenchida
        - value = Preenche o campo vazio com um valor
        - autocomplete = Especifica se um campo de entrada deve ou não ter o preenchimento automático habilitado.
        - checked = deixa a opção já marcada.
        - list = define um id de lista.
* label: A tag define um rótulo para muitos elementos de formulário.
* fieldset: Define um conjunto de campos (fieldset).
* legend: Define um título para os campos (fields).
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Media Query:
* link: padrão
* Media = tipo de media que o css será direcionado 
    Media type:
    - All: Para todos os dispositivos.
    - Braille: Para dispositivos táteis.
    - Embossed: Para dispositivos que imprimem em braile.
    - Handheld: Para dispositivos portáteis, geralmente com telas pequenas e banda limitada.
    - Print: Para impressão em papel.
    - Projection: Para apresentações como PPS.
    - Screen: Para monitores ou dispositivos com telas coloridas e resolução adequada.
    - Speech: Para sintetizadores de voz. As CSS 2 tem uma especificação de CSS chamada Aural, onde podemos formatar a voz dos sintetizadores.
    -  Tty: Para dispositivos que possuem uma grade fixa para exibição de caracteres, tais como: Teletypes, Terminais e também dispositivos portáteis com display limitados.
    - Tv: Para dispositivos como televisores, ou seja, com baixa resolução, quantidade de cores e scroll limitados.
    Media Feature
    - and (orientation:xxxx)
    - portrait - modo retrato
    - landscape - modo paisagem
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Lista:
* ul: Define uma lista desordenada:
* ol: Define uma lista ordenada:
* li: Define os itens da lista:
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Botão:
* button: Define um botão de comando.
    - Autofocus: Esse atributo especifica que um botão deve obter foco automático quando a página for carregada.
    - Disable: Esse atributo especifica que um botão será desabilitado, ou seja, o usuário não poderá interagir com o botão.
    - Form: Esse atributo especifica a qual formulário o botão pertence.
    - Formaction: Esse atributo especifica para onde enviar os dados do formulário quando este é submetido pelo botão.
    - Formenctype: Esse atributo especifica como os dados de um formulário devem ser codificados antes de enviá-los para um servidor. Possíveis valores:
        - (application/x-www-form-urlencoded:) Valor padrão se o atributo não for especificado;
        - (multipart/form-data:)Valor padrão se o atributo não for especificado;
        - (text/plain:)Valor padrão se o atributo não for especificado;
    - Formmethod: Esse atributo especifica o método HTTP que o navegador usará para enviar o formulário. Possíveis valores:
        - (post) Envia os dados obtidos do formulário para o servidor;
        - (get) Anexa os dados do formulário a URL.
    - Formvalidate: Esse atributo especifica que os dados do formulário não é para ser validado quando submetido.
    - Formtarget: Esse atributo é um nome ou palavra-chave indicando onde exibir a resposta que é recebida após o envio do formulário. Possíveis valores:
        - (_self) Carrega a resposta no mesmo contexto de navegação como atual;
        - (_blank) Carrega a resposta em um contexto de navegação sem nome;
        - (_parent) Carrega a resposta no contexto de navegação pai do atual;
        - (_top) Carrega a resposta para todo o contexto de navegação no nível superior.
    - Name: Esse atributo especifica um nome para o botão.
    - Type: Esse atributo especifica um tipo para o botão.
    - Value: Esse atributo especifica um valor inicial para o botão.
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Iframe:
* iframe: É um elemento HTML que serve para acrescentar conteúdos de outra página web na página atual;
    - Allowfullscreen: Este atributo dá a permissão de utilizar o <iframe> em tela cheia.
    - frameborder:Esse atributo é utilizado para modificar a borda padrão do elemento.
    - height: Altura.
    - Width: Largura.
    - Marinheight: Esse atributo é utilizado para alterar a distância das margens superiores e inferiores do <iframe>.
    - Marginwidth: Esse atributo é utilizado para alterar a distância das margens laterais direita e esquerda do <iframe>.
    - Name: Definir um nome.
    - Scrolling: Esse atributo serve para habilitar ou desabilitar a barra de rolagem no elemento <iframe>. Seguintes valores:
        - (yes) serve para exibir a barra de rolagem.
        - (no) serve para esconder a barra de rolagem.
        - (auto)a barra de rolagem é exibida conforme a necessidade do elemento.
    - Sandbox: Esse atributo é utilizado para habilitar uma série de restrições para oferecer segurança à página. Valores:
        - (allow-same-origin) Permite que o conteúdo acessado pelo iframe seja tratado como sendo da mesma origem da página atual.
        - (allow-top-navigation) Permite a navegação na página acessada no iframe para nível superior.
        - (allow-forms) Permite que o <iframe> submeta formulários inseridos nele.
        - (allow-popups) Permite a abertura de pop-ups.
        - (allow-scripts) Permite a execução de scripts.
        - (allow-pointer-lock) Permite a utilização de eventos baseados no movimento do mouse (API Pointer Lock).
    - Src: Esse atributo é utilizado para definir o URL da página que será incorporada.
    - Srdoc: Esse atributo é utilizado para escrever código HTML dentro do elemento <iframe>.
  	- Referrerpolicy: Outro atributo para segurança no iframe.
        - (no-referrer)
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Outras:
* <!----> = Define um comentário;
* abbr = Define uma abreviação
* address = Define um endereço. (Passa a ser tratado como uma seção);
* area = Define uma área dentro de um mapa de imagem;
* b = Define um texto em negrito; (Possui o mesmo nível semântico que um SPAN, e também o estilo de negrito no texto. Contudo, ele não dá nenhuma importância para o texto marcado com ele.)
* base = Define uma base URL para todos os links da página;
* bdo = Define a direção do texto apresentado;
* blockquote =  Define uma citação longa;
* caption = Define o "caption" de uma tabela;
* cite = Define uma citação;
* code = Define o código texto do computador;
* dd = Define uma descrição de definição;
* del = Define um texto deletado;
* dfn = Define um termo de definição;
* dl = Define uma lista de definição;
* dt = Define um termo de definição;
* em = Define um texto em ênfase;
* i = Define um texto em itálico; (Possui o mesmo nível semântico que um SPAN. O texto continua sendo itálico e para usuários de leitores de tela, a voz utilizada é modificada para indicar ênfase. É de grande valor e utilidade para marcar, termos técnicos, termos em outras linguagens etc.)
* img = Define uma imagem;
* ins = Define um texto inserido;
* kbd = Define um texto do teclado;
* map = Define uma imagem de mapa;
* meta = Define informações meta;
* noscript = Define uma seção noscript;
* object = Define um objeto incorporado;
* param = Define um parâmetro para determinado objeto;
* pre = Define um texto pré-formatado;
* q = Define uma citação curta;
* s = Define um texto que não é mais correto.
* samp = Define um código de amostra;
* script = Define um script;
* small = Define um pequeno texto;
* span = Define uma seção no documento em linha;  
* strong = Define um texto forte (similar ao negrito);
* sub = Define um texto subscrito;
* sup = Define um texto sobrescrito;
* var = Define uma variável