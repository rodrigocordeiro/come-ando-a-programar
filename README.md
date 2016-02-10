Começando a programar


classe

elementos HTML pode ter uma ou mais classes, separadas por espaços. Você pode estilizar elementos usando CSS selecionando-as com as suas classes.

Exemplo

< Div  class = "big-caixa amarela-box" > Esta é uma grande caixa amarela. </ Div >
identidade

Um elemento HTML pode ter um atributo id para identificá-lo. elementos de identificação deve ser sempre exclusivo para esse único elemento, e cada elemento nunca deve ter mais de um ID.

Exemplo

< Div  id = "my-box" > Esta é minha caixa! Coloque seu texto em alguma outra caixa. </ Div >
href

Ligações dizer ao navegador onde ir usando um atributo href, que armazena uma URL.

Exemplo

< A  href = "http://google.com" > Google it! </ A >
formatação básica

Você pode facilmente formatar o texto a ser negrito, itálico ou sublinhado usando tags de formatação simples.

Exemplo

Este texto é < b > negrito </ b > , < i > itálico </ i > e < u > sublinhou </ u > .
Corpo

O corpo é o recipiente para todo o conteúdo de uma página. Vem depois do <head> tag, no geral <html> tag.

Exemplo

< Html > 
  < head > 
    < title > Um exemplo da tag body </ title > 
  </ head > 
  < corpo >
    Isto está dentro do corpo!
  </ Corpo > 
</ html >
Leia mais

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body
Uso

Quase todo o conteúdo pertence dentro da tag body. As principais exceções são script e estilo tags, bem como a tag título da página. Como você pode ver neste exemplo, há um título, uma imagem e um link tudo dentro da tag body. A marca de cabeça contém apenas os arquivos externos e o título da página.

Exemplo

< Html > 
  < head > 
    < title > My homepage </ title > 
    < link  rel = "stylesheet"  type = "text/css"  href = "homepage.css" /> 
    < script  type = "text/javascript"  src = "homepage.js" ></ Roteiro > 
  </ head > 
  < corpo > 
    < h1 > ! Olá, este é um retrato de meu gato </ h1 > 
    < img  src = "cat.jpg" /> 
    < a  href = "mailto: cat @ Codecademy. com " > Enviar meu gato </ a > 
  </ corpo > 
</ html >
crianças

Um elemento que é um descendente imediato de um outro elemento ou aninhado dentro de outro elemento é chamado uma criança. Estes tornam-se útil quando se usa criança seletores CSS e pseudo-elementos.

Exemplo

< Ul  id = "pai" > 
  < li  id = "criança" > Eu sou um filho da mãe! </ Li > 
</ ul >
Comentários

Comentários HTML são por vezes usados ​​em código para explicar partes do markup. Eles são semelhantes aos comentários em outras línguas. Os usuários não ver os comentários no seu browser.

Sintaxe

<! - Este é um comentário HTML! ->
div

Um recipiente de nível de bloco (ou "divisão" da página web) para o conteúdo sem significado semântico.

Sintaxe

< Div > Este é um elemento div. </ Div >
Cabeça

Tag que envolve conteúdos importantes que é invisível para o usuário, mas é importante para o browser. Elementos dentro dessa tag contêm metadados sobre a página e links para folhas de estilo, os scripts, etc.

< Html > 
    < head > 
    </ head > 
    < corpo > 
    </ corpo > 
</ html >
cabeçalhos

Rubrica elementos como <h1> , <h2> , <h3> , ... permitem que você use seis níveis de cabeçalhos de documentos, que vão do maior ao menor, quebrando o documento em seções lógicas. Por exemplo, a palavra «posições» acima é envolto em um <h2> tag.

Sintaxe

< H1 > Este é um cabeçalho! </ H1 >
regras horizontais

Esta tag cria uma linha preta um pixel de espessura que vai a todo o caminho através do seu recipiente. Ele pode ser denominado para olhar de forma diferente com CSS.

Exemplo

Este texto é dividido
 < hr >
... A partir deste texto!
Leia mais

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hr
HTML

O que é HTML?

HTML significa Hyper Text Markup Language. É a linguagem utilizada para criar todos os sites.

Leia mais

http://www.w3.org/wiki/HTML/Training/What_is_HTML
<html> tag

Todos os arquivos HTML viver dentro de uma tag HTML-over arqueando. Esta é a etiqueta de base, que define um documento HTML.

Sintaxe

< Html >
  O resto da sua página web vai aqui!
</ Html >
Leia mais

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html
hiperlinks

Hiperlinks (ou simplesmente links) levar o usuário para outra página Web quando eles clique sobre ele. O atributo mais comum usado com links é href, que informa ao navegador onde o link vai.

Sintaxe

< A  href = "URL este link vai para" > texto Link </ a >
Exemplo

O texto a seguir é < a  href = "http://google.com" > vai para o Google </ a > .
imagens

A tag img incorpora uma imagem para o HTML. Sempre com o atributo 'src', que informa ao navegador onde encontrar a imagem. Note que o <img /> tag é auto-fechamento, e você pode fazer referência tanto locais

Sintaxe

< Img  src = 'mylocalimage.jpg' />
Quebras de linha

Esta tag é usada em um bloco de texto para forçar uma quebra de linha. Isso é para ser usado para coisas que são um único parágrafo, mas onde essa formatação é necessária, como poemas ou endereços. Para separar parágrafos, separar cada parágrafo em um elemento separado em vez disso. O elemento resultando em uma página web será algo como:

Exemplo

< P > Algum texto < br /> que se estende por duas linhas </ p >
ligações

elementos de ligação são usados ​​para conectar o documento a um recurso relacionado (muito diferente de hiperlinks, que levá-lo para outra página da web quando você clicar sobre eles). Os links são exibidos apenas na seção head de um documento para que eles não alteram o conteúdo, mas apenas a apresentação. As ligações são mais comumente usado para conectar-se a uma folha de estilo, roteiro, favicon, ou formato alternativo da página, como um feed RSS ou PDF.

exampl

< Link de  tipo = "text / css"  rel = "stylesheet"  href = "styles.css" />
listas

HTML suporta dois tipos de listas: listas ordenadas e listas não ordenadas. Dentro de listas de cada item da lista individual tem a sua própria marca.

Listas não ordenadas

listas não ordenadas são apenas lista cujos itens são indicados com pontos de bala.

Exemplo

Lista de compras

< Ul > 
  < li > Saboneteira </ li > 
  < li > Kitty Litter </ li > 
  < li > Molho de tomate </ li > 
</ ul >
Leia mais

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol
Listas ordenadas

objectos de listas ordenadas são indicadas com números.

Exemplo

Minha lista numerada

< Ol > 
  < li > Primeiro item! </ Li > 
  < li > Segundo item! </ Li > 
  < li > Última artigo! </ Li > 
</ ol >
Leia mais

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li
parágrafos

<P>

Uma das marcas mais comuns em HTML - denota um parágrafo de texto. Muitas vezes tem outros elementos aninhados dentro dele, como <img /> , <a> , <strong> e <em> .

Sintaxe

< P > Este é o texto do parágrafo! </ P >
formatação semântica

Essas marcas são semelhantes às tags de formatação mencionadas anteriormente que caíram em desuso. A diferença é que essas marcas têm valor semântico (significado). <Em> é usado para algo que você deseja enfatizar e <strong> é usado para algo que é importante. Com estes dois elementos, você pode transmitir o nível de ênfase ou importância, com o assentamento. Quanto mais vezes que o elemento ninho dentro de si mesmo, quanto maior a magnitude do texto que ele contém.

Exemplo

< P > < strong > < strong > Aviso: </ strong > ácido pode causar queimaduras graves </ strong >  </ p >
tabelas

Um elemento para mostrar a informação em linhas e colunas. Suporta cabeçalhos e rodapés para colunas de rotulagem. Divide as informações em linhas (indicado pelo tag tr) que contêm células (indicado pelo tag td).

Exemplo

< Tabela > 
  < thead > 
    < tr > 
      < th > item </ th > 
      < th > Preço </ th > 
    </ tr > 
  </ thead >

  < Tbody > 
    < tr > 
      < td > Banana </ td > 
      < td > $ 56,75 </ td > 
    </ tr > 
    < tr > 
      < td > Iogurte </ td > 
      < td > $ 12,99 </ td > 
    </ tr > 
  < / tbody >

  < Tfoot > 
    < tr > 
      < td > total </ td > 
      < td > $ 69,74 </ td > 
    </ tr > 
  </ tfoot > 
</ mesa >
Tag & Elements

Tags são etiquetas básicas que definem e peças separadas de sua marcação em elementos. Eles são compostos de uma palavra-chave entre colchetes angulares <> . Conteúdo vai entre duas marcas e o fechamento é prefixado com uma barra (Nota: existem algumas tags HTML de fecho automático, como tags de imagem). As tags também têm atributos, que são

Sintaxe

< Tag  atributo = "valor" > conteúdo </ tag  palavra-chave >
Título

Este tag informa ao navegador o que mostrar como o título da página na parte superior e diz motores de busca o que o título do seu site é. Ele vai para dentro <head> tags. Tente e faça seus títulos de página descritiva, mas não excessivamente detalhada.

Exemplo

< Title > HTML Glossário </ title >
