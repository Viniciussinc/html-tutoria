# Aprendendo HTML

Este projeto é um site desenvolvido com o propósito de ensinar programação em HTML para iniciantes. Ele contém uma série de tutoriais, exemplos de código e exercícios práticos para ajudar os alunos a aprenderem os fundamentos do HTML.

## Conteúdo

- **Tutoriais:** Uma série de lições passo a passo para aprender HTML desde o básico até conceitos mais avançados.
- **Exemplos de Código:** Demonstração de diferentes elementos HTML e como eles podem ser usados.
- **Exercícios Práticos:** Desafios para praticar e solidificar o conhecimento adquirido.

## Acesso ao Site

O site está hospedado no GitHub Pages e pode ser acessado no seguinte link: https://viniciussinc.github.io/html-tutorial/

## Como Contribuir

Se você quiser contribuir para este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias, correções ou novos conteúdos. Sua contribuição é muito bem-vinda!
 
 
 Codigo Fonte:

```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tutorial de html</title>
    <link rel="stylesheet" href="estilo.css">
    <link rel=" icon" href="imagens/html-5_732212 (1).png" type="image/html.png">
</head>

<body>
    <h1 class="allign">Tutorial HTML</h1>
    <div class="content">
        <p>HTML é a linguagem de marcação padrão para páginas da Web. Com HTML você pode criar seu próprio site.</p>
        <h2>Exemplos básicos de HTML</h2>
        <hr>
        <p>Todos os documentos HTML devem começar com uma declaração de tipo de documento:
            <code>&lt;!DOCTYPE html&gt;</code>.
        </p>
        <p>O próprio documento HTML começa <code>&lt;html&gt;</code> e termina com <code>&lt;/html&gt;</code>.</p>
        <p>A parte visível do documento HTML está entre <code>&lt;body&gt;</code> e <code>&lt;/body&gt;</code>.</p>
        <h2>Exemplo:</h2>
        <p><code>&lt;!DOCTYPE html&gt;</code></p>
        <p><code>&lt;html&gt;</code></p>
        <p><code>&lt;body&gt;</code></p>
        <code>&lt;h1&gt;Isto é um cabeçalho &lt;/h1&gt;<br></code>
        <code>&lt;p &gt;isto é um paragrafo &lt;/p&gt;</code>
        <p><code>&lt;/body&gt;</code></p>
        <p><code>&lt;/html&gt;</code></p>
        <hr>
        <h1>A declaração <code>&lt;!DOCTYPE html&gt;</code></h1>
        <p> A <code>&lt;!DOCTYPE &gt;</code>declaração representa o tipo de documento e ajuda os navegadores a exibir as
            páginas da web corretamente.</p>
        <p>Deve aparecer apenas uma vez, no topo da página (antes de qualquer tag HTML).</p>
        <p>A <code>&lt;!DOCTYPE&gt;</code>declaração não diferencia maiúsculas de minúsculas.</p>
        <p>A <code>&lt;!DOCTYPE &gt;</code>declaração para HTML5 é:</p>
        <p><code>&lt;!DOCTYPE html&gt;</code></p>

        <hr>
        <h2>Cabeçalhos em HTML</h2>
        <p>Os títulos HTML são definidos com as tags <code>&lt;h1&gt;</code> ao <code>&lt; h6&gt;</code>.</p>
        <p><code>&lt;h1&gt;</code> define o titulo mais importante. <code>&lt;h6&gt;</code> define o titulo menos
            importante</p>
        <h2>Exemplo:</h2>
        <hr>
        <p><code>&lt;h1&gt;</code>isto e um titulo 1 <code>&lt;/h1&gt;</code></p>
        <p><code>&lt;h2&gt;</code>isto e um titulo 2 <code>&lt;/h2&gt;</code></p>
        <p><code>&lt;h3&gt;</code>isto e um titulo 3 <code>&lt;/h3&gt;</code></p>
        <hr>
        <h1>Paragrafos em HTML</h1>
        <p>Os paragrafos em html sao definidos com a <code>&lt;p&gt;</code> tag </p>
        <h2>Exemplo:</h2>
        <p><code>&lt;p&gt;</code>isto é um paragrafo <code>&lt;/p&gt;</code></p>
        <p><code>&lt;p&gt;</code>isto é um outro paragrafo <code>&lt;/p&gt;</code></p>
        <hr>
        <h1>Links em HTML</h1>
        <p>links sao definidos com a <code>&lt;a&gt;</code>tag</p>
        <h2>Exemplo:</h2>
        <p><code>&lt;a href ="https://www.pipoca.com &gt;</code></p>
        <p>O destino do link é especificado no href tributo.</p>
        <p>Os atributos são usados para fornecer informações adicionais sobre os elementos HTML.
            Você aprenderá mais sobre atributos em um capítulo posterior.</p>
        <hr>
        <h1>Imagens em HTML</h1>
        <p>as imagens são definidas com a tag <code>&lt;img&gt;</code>.</p>
        <p>o arquivo de origem deve ser fornecido com <code>src</code> o texto alternativo com <code>alt</code>
            <code>width</code> e <code>height</code> são fornecidos como atributos
        </p>
        <h2>Exemplo</h2>
        <p><code>&lt;img src = "pipoca.jpg" alt = "pipoca.com" width="150" height="142"&gt;</code></p>
        <hr>
        <h1>Como visualizar a fonte HTML.</h1>
        <p>Você já viu uma página da Web e se perguntou “Ei! Como eles fizeram isso?”</p>
        <h3>Como ver o codigo fonte em HTML:</h3>
        <p>Clique CTRL + U em uma página HTML ou clique com o botão direito na página e selecione “Exibir código-fonte
            da página”. Isso abrirá uma nova aba contendo o código-fonte HTML da página.</p>
        <h3>Inspecione um elemento HTML:</h3>
        <p>Clique com o botão direito em um elemento (ou em uma área em branco) e escolha "Inspecionar" para ver de que
            elementos são compostos (você verá o HTML e o CSS). Você também pode editar o HTML ou CSS dinamicamente no
            painel Elementos ou Estilos que é aberto.</p>
        <hr>
    </div>
    <div class="content">
        <hr>
        <h1>Elementos HTML </h1>
        <p>Um elemento html é definido por uma tag inicial, algum conteudo e uma tag final </p>
        <h2>Elementos HTML </h2>
        <p>O elemento html é tudo, desde a tag inicial até a tag final: </p>
        <p><code>&lt;tagname&gt;</code> O conteudo vai aqui <code>&lt;/tagname &gt;</code> </p>
        <h3>Exemplo de alguns elementos HTMl: </h3>
        <p><code>&lt;h1&gt;</code> Um titulo <code>&lt;/h1&gt;</code></p>
        <p><code>&lt;p&gt;</code> Um paragrafo <code>&lt;/p&gt;</code></p>
        <table>
            <thead>
                <tr>
                    <th>Tag de inicio </th>
                    <th>Conteudo do elemento </th>
                    <th>Tag de fechamento</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><code>&lt;h1&gt;</code></td>
                    <td>Titulo</td>
                    <td><code>&lt;/h1&gt;</code></td>
                </tr>
                <tr>
                    <td><code>&lt;p&gt;</code></td>
                    <td>Paragrafo</td>
                    <td><code>&lt;/p&gt;</code></td>
                </tr>
                <tr>
                    <td><code>&lt;br&gt;</code></td>
                    <td>Sem conteudo</td>
                    <td>Sem conteudo</td>
                </tr>
            </tbody>
        </table>
        <hr>
        <h1>Elementos HTML aninhados :</h1>
        <p>Os elementos Html podem ser aninhados, isso significa que os elementos podem conter outros elementos.</p>
        <p>Todos os documentos Html consistem em elementos Html aninhados. </p>
        <p>O Exemplo a seguir contem quatro elementos html <code>&lt;html&gt;</code> ,<code>&lt;body &gt;</code>,
            <code>&lt;h1&gt;</code> e por fim o elemento <code>&lt;p&gt;</code>.
        </p>
        <h2>Exemplo</h2>
        <hr>
        <p><code>&lt;!DOCTYPE html &gt;</code></p>
        <p><code>&lt;html&gt;</code></p>
        <p><code>&lt;body&gt;</code></p>
        <p><code>&lt;h1&gt;</code> Cabeçalho <code>&lt;/h1&gt;</code></p>
        <p><code>&lt;p&gt;</code>Paragrafo <code>&lt;/p&gt;</code></p>
        <p><code>&lt;/body&gt;</code></p>
        <p><code>&lt;/html&gt;</code></p>
        <hr>
        <h3>Exemplo Explicado</h3>
        <p>O <code>&lt;html&gt;</code> é o elemento raiz e define todo documento html.</p>
        <p>Possui uma tag inicial <code>&lt;html&gt;</code> e uma tag final <code>&lt;/html&gt;</code>. </p>
        <p>Então, dentro do <code>&lt;html&gt;</code> existe um elemento <code>&lt;body&gt;</code>. </p>
        <p>Onde o elemento deve nescessariamente estar dentro do elemento <code>&lt;html&gt;</code></p>
        <p>O elemento <code>&lt;body&gt;</code> define o corpo do documento.</p>
        <p>Possui uma tag inicial <code>&lt;body&gt;</code> e uma tag final <code>&lt;/body&gt;</code>.</p>
        <p>Então, dentro do <code>&lt;body&gt;</code> existem dois outros elementos o <code>&lt;h1&gt;</code> e
            <code>&lt; p &gt;</code>
        </p>
        <hr>
        <h1>Nunca pule uma tag final!</h1>
        <p>Alguns elementos HTML serão exibidos corretamente, mesmo se você esquecer a tag final</p>
        <h1>Elementos Vazios:</h1>
        <p>Elementos HTML sem conteúdo são chamados de elementos vazios.</p>
        <p>A tag <code>&lt;br&gt;</code>define uma quebra de linha e é um elemento vazio sem tag de fechamento :</p>
        <h2>Exemplo:</h2>
        <p><code>&lt;p&gt;</code> <code>&lt;br&gt;</code>isso é um paragrafo com uma quebra de linha </p>
        <h1>Html não diferencia maiúsculas de minúsculas</h1>
        <p>As tags HTML não diferenciam maiúsculas de minúsculas: <code>&lt;P&gt;</code> significa o mesmo que
            <code>&lt;p&gt;</code>.
        </p>
        <hr>
    </div>
    <div class="content">
        <h1>Atributos HTML</h1>
        <p>Os atributos HTML fornecem informações adicionais sobre os elementos html.</p>
        <h2>Atributos Html </h2>
        <ul>
            <li>Todos os elementos HTML podem ter <b>atributos</b></li>
            <li>Os atributos fornecem <b>informações adicionais sobre os elementos</b></li>
            <li>Os atributos são sempre especificados na <b>tag inicial</b></li>
            <li>Os atributos geralmente vêm em pares <b>nome/valor como: nome="valor"</b></li>

        </ul>
        <hr>
        <h1>O atributo href</h1>
        <p>A tag <code>&lt;a&gt;</code>define um hiperlink o <code>href</code>especifica uma URL para qual o link o
            leva.</p>
        <h2>Exemplo</h2>
        <p><code>&lt;a href ="https://www.Exemplo.com"&gt;visite o exemplo&lt;/a&gt;</code></p>
        <hr>
        <h1>O atributo src</h1>
        <p>A <code>&lt;img&gt;</code>é usada para incorporar uma imagem em uma página HTML. O srcatributo especifica o
            caminho para a imagem a ser exibida: </p>
        <h2>Exemplo</h2>
        <p><code>&lt;img src ="img_dog.jpg"&gt;</code></p>
        <p>Existem duas maneiras de especificar o URL no <code>src</code>:</p>
        <p>1. URL absoluta Links para uma imagem externa hospedada em outro site.</p>
        <p>Notas: Imagens externas podem estar protegidas por direitos autorais. Se você não obtiver permissão para
            usá-lo, poderá estar violando as leis de direitos autorais. Além disso, você não pode controlar imagens
            externas; ele pode ser removido ou alterado repentinamente.</p>
        <p>2. URL relativo - Links para uma imagem hospedada no site. Aqui, o URL não inclui o nome de domínio. Se o URL
            começar sem barra, será relativo à página atual. Exemplo: src="img_girl.jpg". Se o URL começar com uma
            barra, será relativo ao domínio. Exemplo: src="/images/img_girl.jpg".</p>
        <hr>
        <h1>Os atributos de largura e altura</h1>
        <p>A <code>&lt;img&gt;</code>também deve conter os atributos <code>width</code> e <code>height</code>que
            especificam a largura e a altura da imagem (em pixels)</p>
        <h2>Exemplo</h2>
        <p><code>&lt;img src c="img_dog.jpg" width="500" height="600"&gt;</code></p>
        <hr>
        <h1>O atributo alternativo</h1>
        <p><code>alt</code> O atributo obrigatório para a <code>&lt;img&gt;</code>tag especifica um texto alternativo
            para uma imagem, se a imagem por algum motivo não puder ser exibida. Isso pode ser devido a uma conexão
            lenta, a um erro no <code>src</code>atributo ou ao usuário usar um leitor de tela.</p>
        <h2>Exemplo</h2>
        <p><code>&lt;img src="img_dog.jpg" alt="cachorro de terno"&gt;</code></p>
        <hr>
        <h1>O atributo de estilo</h1>
        <p>O atribudo <code>style</code> é usado para adicionar estilos a um elemento, como cor, fonte, tamanho e muito
            mais.</p>
        <h2>Exemplo</h2>
        <p><code>&lt; p style="color:red;">paragrafo vermelho &lt;/p&gt;</code> </p>
        <hr>
        <h1>O atributo lang</h1>
        <p>Você deve sempre incluir o <code>lang</code> atributo dentro da <code>&lt;html&gt;</code> tag, para declarar
            o idioma da página web. O objetivo é ajudar os mecanismos de pesquisa e navegadores.

            O exemplo a seguir especifica o inglês como idioma:</p>
        <p><code>&lt;!DOCTYPE html&gt;</code></p>
        <p><code>&lt;html lang="en"&gt;</code></p>
        <p><code>&lt;body&gt;</code></p>
        <p>...</p>
        <p><code>&lt;/body&gt;</code></p>
        <p><code>&lt;/html&gt;</code></p>
        <hr>
        <h1>O atributo do título</h1>
        <p>O atributo<code>title</code>define algumas informações extras sobre um elemento.
            O valor do atributo title será exibido como uma dica de ferramenta quando você passar o mouse sobre o
            elemento: </p>
        <h2>Exemplo</h2>
        <p><code>&lt;p title="Eu sou uma ferramenta">Isso é um paragrafo.&lt;/p&gt;</code></p>
        <hr>
        <h1>Sugerimos: sempre use atributos em minúsculas</h1>
        <p>O padrão HTML não exige nomes de atributos em letras minúsculas.

            O atributo title (e todos os outros atributos) podem ser escritos em letras maiúsculas ou minúsculas, como
            title ou TITLE .</p>
        <h3>Sugerimos: sempre citar valores de atributos</h3>
        <p>O padrão HTML não exige aspas nos valores dos atributos.</p>
        <p>No entanto,recomendo citações em HTML e exige citações para tipos de documentos mais rígidos, como XHTML.</p>
        <h2>Bom:</h2>
        <p><code>&lt;a href="https://www.exemplo.com/html/">Visite o Tutorial html &lt;/a&gt;</code></p>
        <h2>Ruim:</h2>
        <p><code>&lt;a href=https://www.exemplo.com/html/>Visite o tutorial html&lt;/a&gt;</code></p>
        <hr>
        <h1>Aspas simples ou duplas?</h1>
        <p>Aspas duplas em torno de valores de atributos são as mais comuns em HTML, mas aspas simples também podem ser
            usadas.

            Em algumas situações, quando o próprio valor do atributo contém aspas duplas, é necessário utilizar aspas
            simples:</p>
        <p><code>&lt;p title='John "ShotGun" Nelson'&gt;</code></p>
        <p>ou vice e versa:</p>
        <p><code>&lt;p title="John 'ShotGun' Nelson"&gt;</code></p>
        <h3>Resumo do capítulo</h3>
        <ul>
            <li>Todos os elementos HTML podem ter <strong>atributos</strong></li>
            <li>O <code>href</code>atributo de <code>&lt;a&gt;</code>especifica o URL da página para a qual o link vai
            </li><br>
            <li>O <code>src</code>atributo de <code>&lt;img&gt;</code>especifica o caminho para a imagem a ser exibida
            </li><br>
            <li>Os atributos <code>width</code>e <code>height</code>fornecem o tamanho e largura para imagens
                <code>height&lt;img&gt;</code>.
            </li><br>
            <li>O <code>alt</code> atributo de <code>&lt;img&gt;</code>fornece um texto alternativo para uma imagem.
            </li><br>
            <li>O <code>style</code>atributo é usado para adicionar estilos a um elemento, como cor, fonte, tamanho e
                muito mais.</li><br>
            <li>O <code>lang</code>atributo da <code>&lt;html&gt;</code>tag declara o idioma da página da Web.</li><br>
            <li>O <code>title</code>atributo define algumas informações extras sobre um elemento.</li><br>

        </ul>


    </div>
    <div class="content">
        <h1>Cabeçalhos HTML</h1>
        <hr>
        <p>Os títulos HTML são títulos ou legendas que você deseja exibir em uma página da web.</p>
        <hr>
        <h2>Exemplo:</h2>
        <hr>
        <h1>Cabeçalho 1</h1>
        <h2>Cabeçalho 2</h2>
        <h3>Cabeçalho 3</h3>
        <h4>Cabeçalho 4</h4>
        <h5>Cabeçalho 5</h5>
        <h6>Cabeçalho 6</h6>
        <hr>
        <h1>Cabeçalhos HTML</h1>
        <p>Os títulos HTML são definidos com as tags <code>&lt;h1&gt;</code> ao <code>&lt;h6&gt;</code></p>
        <p>O <code>&lt;h1&gt;</code>define o título mais importante. <code>&lt;h6&gt;</code>define o título menos
            importante.</p>
        <h2>Exemplo:</h2>
        <p><code>&lt;h1&gt; Cabeçalho 1 &lt;/h1&gt;</code><br></p>
        <p><code>&lt;h2&gt; Cabeçalho 2 &lt;/h2&gt;</code><br></p>
        <p><code>&lt;h3&gt; Cabeçalho 3 &lt;/h3&gt;</code><br></p>
        <p><code>&lt;h4&gt; Cabeçalho 4 &lt;/h4&gt;</code><br></p>
        <p><code>&lt;h5&gt; Cabeçalho 5 &lt;/h5&gt;</code><br></p>
        <p><code>&lt;h6&gt; Cabeçalho 6 &lt;/h6&gt;</code><br></p>
        <hr>
        <h3>Os títulos são importantes</h3>
        <p>Os mecanismos de pesquisa usam os títulos para indexar a estrutura e o conteúdo das suas páginas da web.</p>
        <p>Os usuários costumam folhear uma página pelos títulos. É importante usar títulos para mostrar a estrutura do
            documento.</p>
        <p><code>&lt;h1&gt;</code>os títulos devem ser usados para os títulos principais, seguidos pelos
            <code>&lt;h2&gt;</code>títulos, depois pelos menos importantes <code>&lt;h3&gt;</code>e assim por diante
        </p>
        <hr>
        <h1>Títulos maiores</h1>
        <p>Cada título HTML possui um tamanho padrão. No entanto, você pode especificar o tamanho de qualquer título com
            o <code>style</code> atributo, usando a <code>fonts-size</code> propriedade CSS:</p>
        <h2>Exemplo:</h2>
        <p><code>&lt;h1 style="font-size:60px;"&gt;</code> cabeçalho 1 <code>&lt;/h1&gt;</code></p>
    </div>
    <div class="content">
        <h1>Parágrafos HTML</h1>
        <hr>
        <p>Um parágrafo sempre começa em uma nova linha e geralmente é um bloco de texto.</p>
        <hr>
        <h1>Parágrafos HTML</h1>
        <p>O elemento HTML <code>&lt;p&gt;</code> define um paragrafo.</p>
        <p>Um parágrafo sempre começa em uma nova linha e os navegadores adicionam automaticamente algum espaço em
            branco (uma margem) antes e depois de um parágrafo.</p>
        <h2>Exemplo:</h2>
        <p><code>&lt;p&gt;isso é um paragrafo &lt;/p&gt;</code></p>
        <p><code>&lt;p&gt;isso é outro paragrafo&lt;/p&gt;</code></p>
        <hr>
        <h1>Exibição HTML</h1>
        <p>Você não pode ter certeza de como o HTML será exibido.</p>
        <p>Telas grandes ou pequenas e janelas redimensionadas criarão resultados diferentes.</p>
        <p>Com HTML, você não pode alterar a exibição adicionando espaços ou linhas extras em seu código HTML.</p>
        <p>O navegador removerá automaticamente quaisquer espaços e linhas extras quando a página for exibida:</p>
        <h2>Exemplo</h2>
        <p><code>&lt;p&gt;Este parágrafo
            contém muitas linhas
            no código-fonte,
            mas o navegador
            ignora isso.&lt;/p&gt;</code></p><br>
        <p><code>&lt;p&gt;Este parágrafo
            contém muitos espaços
            no código-fonte,
            mas o navegador
            ignora isso.&lt;/p&gt;</code></p><br>
        <hr>
        <h1>Regras horizontais HTML</h1>
        <p>A <code>&lt;hr&gt;</code>tag define uma quebra temática em uma página HTML e geralmente é exibida como uma
            regra horizontal.</p>
        <p>O <code>&lt;hr&gt;</code>elemento é usado para separar o conteúdo (ou definir uma alteração) em uma página
            HTML:</p>
        <h2>Exemplo</h2>
        <hr>
        <p><code>&lt;h1&gt;Este é o título&lt;/h1&gt;</code></p>
        <p><code>&lt;p&gt;Este é um texto&lt;/p&gt;</code></p>
        <p><code>&lt;hr&gt;</code></p>
        <p><code>&lt;h2&gt;Este é o título 2&lt;/h2&gt;</code></p>
        <p><code>&lt;p&gt;Este e outro texto&lt;/p&gt;</code></p>
        <hr>
        <p>A <code>&lt;hr&gt;</code>tag é uma tag vazia, o que significa que não possui tag final.</p>
        <hr>
        <h1>Quebras de linha HTML</h1>
        <p>O elemento HTML <code>&lt;hr&gt;</code>define uma quebra de linha.</p>
        <p>Use <code>&lt;hr&gt;</code>se desejar uma quebra de linha (uma nova linha) sem iniciar um novo parágrafo:</p>
        <h2>Exemplo</h2>
        <hr>
        <p><code>&lt;p&gt;isso é &lt;hr&gt;um paragrafo &lt;br&gt;com uma quebra de linha &lt;/p&gt;</code></p>
        <p>A <code>&lt;br&gt;</code>é uma tag vazia, o que significa que não possui tag final.</p>
        <h2>O problema do poema</h2>
        <p>Este poema será exibido em uma única linha:</p>
        <h3>Exemplo</h3>
        <p><code>&lt;p&gt;</code>My Bonnie lies over the ocean.

            My Bonnie lies over the sea.

            My Bonnie lies over the ocean.

            Oh, bring back my Bonnie to me. <code>&lt;/p&gt;</code></p>
        <hr>
        <h2>Solução - O elemento HTML <code>&lt;pre&gt;</code></h2>
        <p>O elemento HTML <code>&lt;pre&gt;</code>define texto pré-formatado.</p>
        <p>O texto dentro de um <code>&lt;pre&gt;</code>elemento é exibido em uma fonte de largura fixa (geralmente
            Courier) e preserva espaços e quebras de linha:</p>
        <h3>Exemplo:</h3>
        <pre><code>&lt;pre&gt;</code>My Bonnie lies over the ocean.

                My Bonnie lies over the sea.
              
                My Bonnie lies over the ocean.
              
                Oh, bring back my Bonnie to me. <code>&lt;/pre&gt;</code></pre>

    </div>
    <div class="content">
        <h1>Estilos HTML</h1>
        <hr>
        <p>O atributo HTML <code>style</code> é usado para adicionar estilos a um elemento, como cor, fonte, tamanho e
            muito mais.</p>
        <h2>Exemplo:</h2>
        <p style="color: red;"><code>&lt;p style="color: red;</code> Eu sou vermelho <code>&lt;/p&gt;</code></p>
        <p style="color: blue;"><code>&lt;p style="color: blue;</code> Eu sou azul <code>&lt;/p&gt;</code></p>
        <p style="font-size: 50px;"><code>&lt;p style = "font-size: 50px;&gt;</code> Eu sou grande
            <code>&lt;/p&gt;</code>
        </p>
        <hr>
        <h2>O atributo de estilo HTML</h2>
        <p>Definir o estilo de um elemento HTML pode ser feito com o <code>style</code></p>
        <p>O atributo HTML <code>style</code>possui a seguinte sintaxe:</p>
        <p><code>&lt;tagname style ="property:value;"&gt;</code></p>
        <p>A propriedade é uma propriedade CSS. O valor é um valor CSS.</p>
        <hr>
        <h2>Cor de fundo</h2>
        <p> A <code>background-color</code>propriedade CSS define a cor de fundo de um elemento HTML.</p>
        <h3>Exemplo:</h3>
        <p>Defina a cor de fundo de uma página como azul claro:</p>
        <hr>
        <p><code>&lt; body style="background-color:powderblue;"&gt;</code></p>
        <p><code>&lt;h1&gt;</code>Isso é um Titulo <code>&lt;/h1&gt;</code></p>
        <p><code>&lt;p&gt;</code>Isso é um paragrafo <code>&lt;/p&gt;</code></p>
        <p><code>&lt;/body&gt;</code></p>
        <hr>
        <h3>Exemplo:</h3>
        <p>Defina a cor de fundo para dois elementos diferentes:</p>
        <p><code>&lt;body&gt;</code></p>
        <p><code>&lt;h1 style = "background-color:powderblue;"&gt;</code> isso é um paragrafo <code>&lt;/p&gt;</code>
        </p>
        <p><code>&lt;p style = "background-color:tomato;"&gt;</code> isso é um paragrafo <code>&lt;/p&gt;</code></p>
        <br>
        <p><code>&lt;/body&gt;</code></p>
        <hr>
        <h2>Cor do texto</h2>
        <p>A <code>color</code>propriedade CSS define a cor do texto para um elemento HTML:</p>
        <h3>Exemplo:</h3>
        <hr>
        <p><code>&lt;h1 style ="color:blue;"&gt;</code>Isso é um Titulo <code>&lt;/h1&gt;</code></p>
        <p><code>&lt;p style = "color:red;"&gt;</code>Isso é um pargrafo <code>&lt;/p&gt;</code></p>
        <hr>
        <h2>Fontes</h2>
        <p>A propriedade CSS <code>font-family</code> define a fonte a ser usada para um elemento HTML:</p>
        <h3>Exemplo:</h3>
        <hr>
        <p><code>&lt;h1 style= "font-font-family:verdana;"&gt;</code>Isso é um titulo <code>&lt;/h1&gt;</code></p>
        <p><code>&lt;p style = "font-family:courier;"&gt;</code>Isso é um paragrafo <code>&lt;/p&gt;</code> </p>
        <hr>
        <h2>Alinhamento de texto</h2>
        <p>A <code>text-allign</code>propriedade CSS define o alinhamento horizontal do texto para um elemento HTML:</p>
        <h3>Exemplo:</h3>
        <p><code>&lt;h1 style ="text-allign:center;"&gt;</code>Titulo centralizado <code>&lt;/h1&gt;</code></p>
        <p><code>&lt;p style ="text-allign:center;"&gt;</code>Paragrafo centralizado <code>&lt;/p&gt;</code></p>
        <hr>
        <h1>Resumo do capítulo</h1>
        <ul>
            <li>Use o <code>style</code> atributo para estilizar elementos HTML</li><br>
            <li>Use o <code>background-color</code>para cor de fundo</li><br>
            <li>Use o <code>color</code>para cores de texto</li><br>
            <li>Use o <code>font-family</code>para fontes de texto</li><br>
            <li>Usar a <code>font-size</code>para tamanhos de texto</li><br>
            <li>Use o <code>text-allign</code>para alinhamento de texto</li><br>
        </ul>

    </div>
    <div class="content">
        <h1>Formatação de texto HTML</h1>
        <hr>
        <p>HTML contém vários elementos para definir texto com um significado especial.</p>
        <hr>
        <h2>Exemplo:</h2>
        <p><b>Este texto está em negrito</b></p>
        <p><i>Este texto está em itálico</i></p>
        <p>Isso é um texto <sub> subescrito</sub> e <sup>subescrito</sup></p><br>
        <hr>
        <h2>Elementos de formatação HTML</h2>
        <p>Os elementos de formatação foram projetados para exibir tipos especiais de texto:</p>
        <ul>
            <li><code>&lt;b&gt;</code>-Texto em negrito</li><br>
            <li><code>&lt;strong&gt;</code>- Texto importante</li><br>
            <li><code>&lt;i&gt;</code>- Texto em itálico</li><br>
            <li><code>&lt;em&gt;</code>- Texto enfatizado</li><br>
            <li><code>&lt;mark&gt;</code>- Texto marcado</li><br>
            <li><code>&lt;small&gt;</code>- Texto menor</li><br>
            <li><code>&lt;del&gt;</code> - Texto excluído</li><br>
            <li><code>&lt;ins&gt;</code>- Texto inserido</li><br>
            <li><code>&lt;sub&gt;</code>- Texto subscrito</li><br>
            <li><code>&lt;sup&gt;</code>- Texto sobrescrito</li><br>

        </ul>
        <h1>Elementos HTML <code>&lt;b&gt;</code> e <code>&lt;strong&gt;</code></h1>
        <p>O <code>&lt;b&gt;</code>elemento HTML define texto em negrito, sem qualquer importância extra.</p>
        <h2>Exemplo:</h2>
        <hr>
        <p><code>&lt;b&gt;</code> isso é um codigo em negrito <code>&lt;/b&gt;</code></p>
        <p>O elemento HTML <code>&lt;strong&gt;</code>define texto de grande importância. O conteúdo interno normalmente
            é exibido em negrito.</p>
        <hr>
        <h2>Exemplo:</h2>
        <p><code>&lt;strong&gt;</code>Isso é um texto importante! <code>&lt;strong&gt;</code></p>
        <h2>Elementos Html <code>&lt;i&gt;</code>e <code>&lt;em&gt;</code>:</h2>
        <hr>
        <p>O elemento HTML <code>&lt;i&gt;</code>define uma parte do texto com uma voz ou humor alternativo. O conteúdo
            interno normalmente é exibido em itálico.</p>
        <p><strong>Dica:</strong>A <code>&lt;i&gt;</code>tag costuma ser usada para indicar um termo técnico, uma frase
            de outro idioma, um pensamento, o nome de um navio, etc.</p>
        <h2>Exemplo:</h3s>
            <hr>
            <p><code>&lt;i&gt;</code> Isso é um texto em italico <code>&lt;/i&gt;</code></p>
            <p>O elemento HTML <code>&lt;em&gt;</code>define o texto enfatizado. O conteúdo interno normalmente é
                exibido em itálico.</p>
            <p><strong>Dica:</strong>Um leitor de tela pronunciará as palavras <code>&lt;em&gt;</code>com ênfase, usando
                ênfase verbal.</p>
            <hr>
            <h2>Exemplo:</h2> <br>
            <p><code>&lt;em&gt;</code>Isso é texto ênfase <code>&lt;/eml&gt;</code></p>
            <hr>
            <h1>Elemento HTML <code>&lt;small&gt;</code></h1>
            <p>O elemento HTML <code>&lt;small&gt;</code>define um texto menor:</p>
            <h2>Exemplo:</h2>
            <p><code>&lt;small&gt;</code> isso é um texto pequeno <code>&lt;/small&gt;</code></p><br>
            <p><small>isto é um elemento <code>&lt;small&gt;</code></small></p>
            <hr>
            <h1>Elemento HTML <code>&lt;mark&gt;</code></h1>
            <p>O elemento HTML <code>&lt;mark&gt;</code>define o texto que deve ser marcado ou destacado:</p>
            <h2>Exemplo:</h2>
            <p><code>&lt;p&gt;</code>Não esqueça o <code>&lt;mark&gt;</code> Exemplo <code>&lt;/mark&gt;</code>
                <code>&lt;/p&gt;</code>
            </p>
            <p>Agora explicado em uma <mark>linha</mark></p>
            <hr>
            <h1>Elemento HTML <code>&lt;del&gt;</code></h1>
            <p>O elemento HTML <code>&lt;del&gt;</code>define o texto que foi excluído de um documento. Os navegadores
                geralmente traçam uma linha no texto excluído:</p>
            <p>My favorite color is <del>blue</del> red.</p>
            <hr>
            <h1>Elemento HTML <code>&lt;ins&gt;</code></h1>
            <p>O elemento HTML <code>&lt;ins&gt;</code>define um texto que foi inserido em um documento. Os navegadores
                geralmente sublinharão o texto inserido:</p>
            <h2>Exemplo:</h2>
            <p>Minha cor favorita é <del>azul</del> <ins>vermelho</ins>.</p>
            <p>Sendo assim o codigo do exemplo anterior:</p>
            <p> <code>&lt;p&gt;</code>Minha cor favorita é <code>&lt;del&gt;</code> azul <code>&lt;/del&gt;</code>
                <code>&lt;ins&gt;</code>vermelho <code>&lt;/ins&gt;</code> <code>&lt;/p&gt;</code>
            </p>
            <hr>
            <h1>Elementos <code>&lt;sub&gt;</code>Html</h1>
            <p>O elemento <code>&lt;sub&gt;</code>define o texto subscrito. O texto subscrito aparece meio caractere
                abaixo da linha normal e às vezes é renderizado em uma fonte menor. O texto subscrito pode ser usado
                para fórmulas químicas, como H 2 O:</p>
            <h2>Exemplo:</h2><br>
            <p>Isso é <sup>Um texto</sup> subscrito</p><br>
            <p>Sendo assim o codigo:</p>
            <p><code>&lt;p &gt;</code>Isso é <code>&lt;sup&gt;</code>Um texto <code>&lt;/sup&gt;</code>subscrito
                <code>&lt;/p&gt;</code>
            </p>

    </div>
    <div class="content">
        <h1>Cotação HTML e elementos de citação</h1>
        <p>Neste capítulo, examinaremos os elementos
            <code>&lt;blockquot&gt;</code>,<code>&lt;q&gt;</code>,<code>&lt;aabr&gt;</code>,
            <code>&lt;address&gt;</code>,<code>&lt;cite&gt;</code> e <code>&lt;bdo&gt;</code> html
        </p>
        <h2>HTML <code>&lt;blockquote&gt;</code> para citações</h2>
        <p>O elemento HTML <code>&lt;blockquot&gt;</code>define uma seção citada de outra fonte.</p>
        <p>Os navegadores geralmente recuam elementos <code>&lt;blockquote&gt;</code></p>
        <h3>Exemplo:</h3>
        <p>Here is a quote from WWF's website:</p>
        <blockquote cite="http://www.worldwildlife.org/who/index.html">
            For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation
            organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world
            to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they
            live.
        </blockquote> <br>
        <p>sendo o codigo <code>&lt;blockquote cite="http://www.worldwildlife.org/who/index.html"&gt; </code>For 60
            years, WWF has worked to help people and nature thrive. As the world's leading conservation organization,
            WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop
            and deliver innovative solutions that protect communities, wildlife, and the places in which they live.</p>
        <hr>
        <h2>HTML <code>&lt;q&gt;</code> para citações curtas.</h2>
        <p> a tag <code>&lt;q&gt;</code> define a citação curta.</p>
        <p>Os navegadores normalmente inserem aspas ao redor da citação.</p>
        <h3>Exemplo:</h3>
        <p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
        <p>Sendo assim o codigo :</p> <br>
        <p><code>&lt;p&gt;</code>WWF's goal is to: <code>&lt;q&gt;</code>Build a future where people live in harmony
            with nature. <code>&lt;/q&gt;</code> <code>&lt;/p&gt;</code></p>
        <hr>
        <h2>Html <code>&lt;adrres&gt;</code> para informações de contato</h2>
        <p>A tag <code>&lt;adress&gt;</code>define as informações de contato do autor/proprietário de um documento ou
            artigo.</p>
        <p>As informações de contato podem ser endereço de e-mail, URL, endereço físico, número de telefone,
            identificador de mídia social, etc.</p>
        <p>O texto no <code>&lt;adress&gt;</code>elemento geralmente é renderizado em itálico e os navegadores sempre
            adicionam uma quebra de linha antes e depois do elemento <code>&lt;adress&gt;</code>.</p>
        <h3>Exemplo:</h3> <br>
        <hr>
        <address>
            Written by John Doe.<br>
            Visit us at:<br>
            Example.com<br>
            Box 564, Disneyland<br>
            USA
        </address>
        <p>Sendo assim o codigo:</p><br>
        <hr>
        <p><code>&lt;address&gt;</code></p>
        <p>Written by John Doe. <code>&lt;br&gt;</code></p>
        <p>Visit us at: <code>&lt;br&gt;</code></p>
        <p>Example.com <code>&lt;br&gt;</code></p>
        <p>Box 564, Disneyland <code>&lt;br&gt;</code></p>
        <p>USA</p>
        <p><code>&lt;/addres&gt;</code></p>
        <hr>
        <h2>Html cite <code>¨&lt;cite&gt;</code>para título do trabalho</h2>
        <p>A <code>&lt;cite&gt;</code>tag HTML define o título de um trabalho criativo (por exemplo, um livro, um poema,
            uma música, um filme, uma pintura, uma escultura, etc.).</p>
        <p><b>Nota:</b>O nome de uma pessoa não é o título de uma obra.</p>
        <p>O texto no <code>&lt;cite&gt;</code>elemento geralmente é renderizado em itálico .</p>
        <h3>Exemplo:</h3> <br>
        <p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
        <p>Sendo assim o codigo:</p>
        <p><code>&lt;p&gt;</code> <code>&lt;cite&gt;</code>The Scream <code>&lt;/cite&gt;</code>by Edvard Munch. Painted
            in 1893. <code>&lt;/p&gt;</code> </p>
        <hr>
        <h2>Html <code>&lt;bdo&gt;</code>para substituição bidirecional</h2>
        <p>BDO significa Substituição bidirecional.</p>
        <p>A tag HTML <code>&lt;bdo&gt;</code>é usada para substituir a direção atual do texto</p>
        <h3>Exemplo:</h3>
        <bdo dir="rtl">This text will be written from right to left</bdo>
        <p>sendo assim o codigo:</p>
        <p><code>&lt;bdo dir ="rtl"&gt;</code>This text will be written from right to left <code>&lt;/bdo&gt;</code></p>
        <hr>

    </div>
    <div class="content">
        <h1>Comentários HTML</h1>
        <hr>
        <p>Os comentários HTML não são exibidos no navegador, mas podem ajudar a documentar seu código-fonte HTML.</p>
        <hr>
        <h2>Etiqueta de comentário HTML</h2>
        <p>Você pode adicionar comentários à sua fonte HTML usando a seguinte sintaxe:</p>
        <p><code>&lt;!-- escreva um comentario--&gt;</code></p><br>
        <p>Observe que há um ponto de exclamação (!) na tag inicial, mas não na tag final.</p>
        <p><b>Observação:</b> os comentários não são exibidos pelo navegador, mas podem ajudar a documentar seu
            código-fonte HTML.</p>
        <hr>
        <h2>Adicione comentários</h2>
        <p> Com comentários você pode colocar notificações e lembretes em seu código HTML:</p>
        <h3>Exemplo:</h3>
        <p><code>&lt;!--isso é um comentario--&gt;</code></p><br>
        <p><code>&lt;p&gt;</code> isso é um paragrafo <code>&lt;/p&gt;</code> </p><br>
        <p><code>&lt;!--adicione mais coisa depois--&gt;</code></p><br>
        <hr>
        <h2>Ocultar conteúdo</h2>
        <p>Os comentários podem ser usados para ocultar conteúdo.</p>
        <p>Isso pode ser útil se você ocultar o conteúdo temporariamente:</p>
        <h3>Exemplo:</h3>
        <p><code>&lt;p&gt;</code>Isso é um paragrafo <code>&lt;/p&gt;</code></p>
        <p><code>&lt;!--&lt;p&gt;isso é um outro paragrafo &lt;/p&gt;--&gt;</code></p>
        <p><code>&lt;p&gt;</code>Outro paragrafo <code>&lt;/p&gt;</code></p>
        <hr>
        <p>Você também pode ocultar mais de uma linha. Tudo entre o <code>&lt;!--</code> e o <code>--&gt;</code>ficará
            oculto na tela.</p>
        <h3>Exemplo:</h3>
        <p>Oculte uma seção do código HTML:</p>
        <p><code>&lt;p&gt;Isto é um paragrafo.</code> <code>&lt;/p&gt;</code></p>
        <p><code>&lt;!--&lt;p&gt;Olha esta imagem:&lt;/p&gt;</code></p>
        <p><code>&lt;img border="0" src="pic_trulli.jpg" alt="trulli"&gt;</code></p>
        <p><code>--&gt;</code></p>
        <p><code>&lt;p&gt;isso é um paragrafo &lt;/p&gt;</code></p>
        <p>Os comentários também são ótimos para depurar HTML, porque você pode comentar linhas de código HTML, uma de
            cada vez, para procurar erros.</p>
        <hr>
        <h2>Ocultar conteúdo embutido</h2>
        <p>Os comentários podem ser usados para ocultar partes no meio do código HTML.</p>
        <h3>Exemplo:</h3>
        <p>Ocultar uma parte de um parágrafo:</p>
        <code>&lt;p&gt;isso &lt;!--um grande texto--&gt;é um paragrafo&lt;/p&gt;</code>
    </div>
    <div class="content">
        <h1>Nomes de cores</h1>
        <p>Em HTML, uma cor pode ser especificada usando um nome de cor:</p>
        <h1 style="background-color:Tomato;">Tomato</h1>
        <h1 style="background-color:Orange;">Orange</h1>
        <h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
        <h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>
        <h1 style="background-color:Gray;">Gray</h1>
        <h1 style="background-color:SlateBlue;">SlateBlue</h1>
        <h1 style="background-color:Violet;">Violet</h1>
        <h1 style="background-color:LightGray;">LightGray</h1>
        <hr>
        <h1>Cor de fundo</h1>
        <p>Você pode definir a cor de fundo dos elementos HTML:</p>
        <h2>Exemplo:</h2>
        <h1 style="background-color:DodgerBlue;">Hello World</h1>
        <p style="background-color:Tomato;">Lorem ipsum...</p>
        <p>sedo assim o codigo:</p><br>
        <p><code>&lt;h1 style = "background-color:dodgerblue;"&gt;Hello World &lt;/h1&gt;</code></p>
        <p><code>&lt;p style="background-color:Tomato;"&gt;Lorem ipsum...&lt;/p&gt;</code></p>
        <hr>
        <h2>Cor do texto</h2>
        <p>Você pode definir a cor do texto:</p>
        <h3>Exemplo:</h3>
        <h1 style="color:Tomato;">Hello World</h1>
        <p style="color:DodgerBlue;">Lorem ipsum...</p>
        <p style="color:MediumSeaGreen;">Ut wisi enim...</p>
        <p>sendo aplicado a tag logo a frente do elemento ao qual você quer modificar
            <code>style="color:tag da cor;"&gt;</code>
        </p>
        <hr>
        <h2>Cor da borda</h2>
        <p>Você pode definir a cor das bordas:</p>
        <h3>Exemplo:</h3>
        <h1 style="border:2px solid Tomato;">Hello World</h1>
        <h1 style="border:2px solid DodgerBlue;">Hello World</h1>
        <h1 style="border:2px solid Violet;">Hello World</h1>
        <p>Sendo o codigo do exemplo:</p>
        <p><code>&lt;h1 style ="border:2px solidtomato;"&gt;HelloWorld&lt;/h1&gt;</code></p>
        <hr>
    </div>
    <div class="content">
        <h1>Cores HTML RGB e RGBA</h1>
        <hr>
        <p>Um valor de cor RGB representa fontes de luz VERMELHA, VERDE e AZUL.</p>
        <p>Um valor de cor RGBA é uma extensão de RGB com um canal Alfa (opacidade).</p>
        <hr>
        <h3>Valores de cores RGB</h3>
        <p>Em HTML, uma cor pode ser especificada como um valor RGB, usando esta fórmula:</p>
        <p><b> rgb( vermelho, verde , azul )</b></p>
        <p>Cada parâmetro (vermelho, verde e azul) define a intensidade da cor com um valor entre 0 e 255.</p>
        <p>Isso significa que existem 256 x 256 x 256 = 16777216 cores possíveis!</p>
        <p>Por exemplo, rgb(255, 0, 0) é exibido como vermelho, porque vermelho está definido com seu valor mais alto
            (255) e os outros dois (verde e azul) estão definidos como 0.</p>
        <p>Outro exemplo, rgb(0, 255, 0) é exibido como verde, porque o verde está definido com seu valor mais alto
            (255) e os outros dois (vermelho e azul) estão definidos como 0.</p>
        <p>Para exibir preto, defina todos os parâmetros de cor como 0, assim: rgb(0, 0, 0).</p>
        <p>Para exibir branco, defina todos os parâmetros de cor para 255, assim: rgb(255, 255, 255).</p>
        <p>Experimente misturar os valores RGB abaixo:</p>
        <h1 style="background-color:rgb(255, 0, 0);">rgb(255, 0, 0)</h1>
        <h1 style="background-color:rgb(0, 0, 255);">rgb(0, 0, 255)</h1>
        <h1 style="background-color:rgb(60, 179, 113);">rgb(60, 179, 113)</h1>
        <h1 style="background-color:rgb(238, 130, 238);">rgb(238, 130, 238)</h1>
        <h1 style="background-color:rgb(255, 165, 0);">rgb(255, 165, 0)</h1>
        <h1 style="background-color:rgb(106, 90, 205);">rgb(106, 90, 205)</h1>
        <p>sendo o codigo:</p>
        <p><code>&lt;h1 style="background-color:rgb &lpar;255,0,0&rpar; ; "&gt;rgb &lpar;255,0,0&rpar;&lt;/h1&gt;</code>
        </p>
        <p>Brinque um pouco com ele XD:</p>
        <hr>
        <h2>Tons de cinza</h2>
        <p>Os tons de cinza são frequentemente definidos usando valores iguais para todos os três parâmetros:</p>
        <h3>Exemplo:</h3>
        <h1 style="background-color:rgb(60, 60, 60);">rgb(60, 60, 60)</h1>
        <h1 style="background-color:rgb(100, 100, 100);">rgb(100, 100, 100)</h1>
        <h1 style="background-color:rgb(140, 140, 140);">rgb(140, 140, 140)</h1>
        <h1 style="background-color:rgb(180, 180, 180);">rgb(180, 180, 180)</h1>
        <h1 style="background-color:rgb(200, 200, 200);">rgb(200, 200, 200)</h1>
        <h1 style="background-color:rgb(240, 240, 240);">rgb(240, 240, 240)</h1>
        <hr>
        <h2>Valores de cores RGBA</h2>
        <p>Os valores de cores RGBA são uma extensão dos valores de cores RGB com um canal Alfa - que especifica a
            opacidade de uma cor.</p>
        <p>Um valor de cor RGBA é especificado com:</p>
        <p>rgba( vermelho, verde , azul, alfa )</p>
        <p>O parâmetro alfa é um número entre 0,0 (totalmente transparente) e 1,0 (nada transparente):

            Experimente misturar os valores RGBA abaixo:</p>
        <h1 style="background-color:rgba(255, 99, 71, 0);">rgba(255, 99, 71, 0)</h1>
        <h1 style="background-color:rgba(255, 99, 71, 0.2);">rgba(255, 99, 71, 0.2)</h1>
        <h1 style="background-color:rgba(255, 99, 71, 0.4);">rgba(255, 99, 71, 0.4)</h1>
        <h1 style="background-color:rgba(255, 99, 71, 0.6);">rgba(255, 99, 71, 0.6)</h1>
        <h1 style="background-color:rgba(255, 99, 71, 0.8);">rgba(255, 99, 71, 0.8)</h1>
        <h1 style="background-color:rgba(255, 99, 71, 1);">rgba(255, 99, 71, 1)</h1>



    </div>
    <div class="content">
        <h1>Cores HTML HEX</h1>
        <hr>
        <p>Uma cor hexadecimal é especificada com: #RRGGBB, onde os inteiros hexadecimais RR (vermelho), GG (verde) e BB
            (azul) especificam os componentes da cor.

        </p>
        <hr>
        <h2>Valores de cores HEX</h2>
        <p>Em HTML, uma cor pode ser especificada usando um valor hexadecimal no formato:</p>
        <p><b>#rrggbb</b></p>
        <p>Onde rr (vermelho), gg (verde) e bb (azul) são valores hexadecimais entre 00 e ff (o mesmo que decimal
            0-255).</p>
        <p>Por exemplo, #ff0000 é exibido em vermelho, porque o vermelho está definido com seu valor mais alto (ff) e os
            outros dois (verde e azul) estão definidos como 00.</p>
        <p>Outro exemplo, #00ff00 é exibido em verde, porque o verde está definido com seu valor mais alto (ff) e os
            outros dois (vermelho e azul) estão definidos como 00.</p>
        <p>Para exibir preto, defina todos os parâmetros de cor como 00, assim: #000000.</p>
        <p>Para exibir branco, defina todos os parâmetros de cor como ff, assim: #ffffff.</p>
        <p>Experimente misturar os valores HEX abaixo:</p>
        <h1 style="background-color:#ff0000;">#ff0000</h1>
        <h1 style="background-color:#0000ff;">#0000ff</h1>
        <h1 style="background-color:#3cb371;">#3cb371</h1>
        <h1 style="background-color:#ee82ee;">#ee82ee</h1>
        <h1 style="background-color:#ffa500;">#ffa500</h1>
        <h1 style="background-color:#6a5acd;">#6a5acd</h1>
        <p>Sendo o codigo :</p>
        <p><code>&lt;h1 style="background-color:#ff000;"&gt;#ff0000&lt;/h1&gt;</code></p>
        <p>Brinque um pouco com as casas hexadecimais citadas anteriormente.</p>
    </div>
    <div class="content">
        <h1>Estilos HTML - CSS</h1>
        <hr>
        <p>CSS significa Folhas de Estilo em Cascata.</p>
        <p>CSS economiza muito trabalho. Ele pode controlar o layout de várias páginas da web ao mesmo tempo.</p>
        <hr>
        <h2>O que é CSS?</h2>
        <p>Cascading Style Sheets (CSS) é usado para formatar o layout de uma página da web.</p>
        <p>Com CSS, você pode controlar a cor, a fonte, o tamanho do texto, o espaçamento entre os elementos, como os
            elementos são posicionados e dispostos, quais imagens ou cores de fundo devem ser usadas, diferentes
            exibições para diferentes dispositivos e tamanhos de tela, e muito mais!</p>
        <p><b>Dica:</b> A palavra <b> cascata </b>significa que um estilo aplicado a um elemento pai também será
            aplicado a todos os elementos filhos do pai. Portanto, se você definir a cor do corpo do texto como “azul”,
            todos os títulos, parágrafos e outros elementos de texto dentro do corpo também terão a mesma cor (a menos
            que você especifique outra coisa)!

        </p>
        <hr>
        <h2>Usando CSS</h2>
        <p>CSS pode ser adicionado a documentos HTML de 3 maneiras:</p>
        <ul>
            <li>Inline - usando o <code>&lt;style&gt;</code>atributo dentro dos elementos HTML</li><br>
            <li>Interno - usando um <code>&lt;style&gt;</code>elemento dentro da seão <code>&lt;head&gt;</code></li><br>
            <li>Externo - usando um <code>&lt;link&gt;</code>Elemento para vincular a um arquivo CSS externo</li><br>
        </ul>
        <p>A maneira mais comum de adicionar CSS é manter os estilos em arquivos CSS externos. Porém, neste tutorial
            usaremos estilos inline e internos, porque isso é mais fácil de demonstrar e mais fácil para você
            experimentar.</p>
        <hr>
        <h2>CSS embutido</h2>
        <p>m CSS embutido é usado para aplicar um estilo único a um único elemento HTML.</p>
        <p>Um CSS embutido usa o <code>&lt;style&gt;</code> atributo de um elemento HTML.</p>
        <p>O exemplo a seguir define a cor do texto do <code>&lt;h1&gt;</code>elemento como azul e a cor do texto do
            elemento<code>&lt;p&gt;</code>como vermelho:</p>
        <h3>Exemplo:</h3>
        <hr>
        <h1 style="color:blue;">Cabeçalho azul</h1>

        <p style="color:red;">Paragrafo vermelho.</p><br>

        <p>Sendo os codigos:</p>
        <p><code>&lt;h1 style ="color:blue;"&gt;Cabeçalho Azul&lt;/h1&gt;</code></p><br>
        <p><code>&lt;p style="color:red;"&gt;Paragrafo vermelho &lt;/p&gt;</code></p>
        <hr>
        <h2>CSS interno</h2>
        <p>Um CSS interno é usado para definir um estilo para uma única página HTML.</p>
        <p>Um CSS interno é definido na seção <code>&lt;head&gt;</code>de uma página HTML, dentro de um elemento
            <code>&lt;style&gt;</code>.
        </p>
        <p>O exemplo a seguir define a cor do texto de TODOS os elementos <code>&lt;h1&gt;</code>(nessa página) como
            azul e a cor do texto de TODOS os <code>&lt;p&gt;</code>como vermelho. Além disso, a página será exibida com
            uma cor de fundo "azul polvora": </p>
        <h3>Exemplo:</h3>
        <hr>
        <p><code>&lt;!DOCTYPE html&gt; </code></p>
        <p><code>&lt;html&gt;</code></p>
        <p><code>&lt;head&gt;</code></p>
        <p><code>&lt;style&gt;</code></p>
        <p><code>
    body {background-color: powderblue;}
    h1   {color: blue;}
    p    {color: red;}
</code></p>
        <p><code>&lt;/style&gt;</code></p>
        <p><code>&lt;body&gt;</code></p>
        <p><code>&lt;h1&gt;isso é um cabeçalho &lt;/h1&gt;</code></p>
        <p><code>&lt;p&gt; isso é um paragrafo &lt;/p&gt;</code></p>
        <p><code>&lt;/body&gt;</code></p>
        <p><code>&lt;/html&gt;</code></p>
        <hr>
        <h2>CSS externo</h2>
        <p>Uma folha de estilo externa é usada para definir o estilo de muitas páginas HTML.</p>
        <p>Para usar uma folha de estilo externa, adicione um link para ela na <code>&lt;head&gt;</code>seção de cada
            página HTML:</p>
        <h3>Exemplo:</h3><br>
        <hr>
        <p><code>&lt;!DOCTYPE html&gt;</code></p>
        <p><code>&lt;html&gt;</code></p>
        <p><code>&lt;head&gt;</code></p>
        <p><code>&lt;link rel = "stylesheet" href="styles.css"&gt;</code></p>
        <p><code>&lt;/head&gt;</code></p>
        <p><code>&lt;/body&gt;</code></p>
        <p><code>&lt;/html&gt;</code></p>
        <hr>
    </div>
    <div class="content">
        <h1>Links HTML</h1>
        <hr>
        <p>Links são encontrados em quase todas as páginas da web. Os links permitem que os usuários cliquem de uma
            página para outra.

        </p>
        <h2>Links HTML - Hiperlinks</h2>
        <p>Links HTML são hiperlinks.</p>
        <p>Você pode clicar em um link e ir para outro documento.</p>
        <p>Quando você move o mouse sobre um link, a seta do mouse se transforma em uma pequena mão.</p>
        <hr>
        <p> <b>Nota:</b>Um link não precisa ser texto. Um link pode ser uma imagem ou qualquer outro elemento HTML!</p>
        <hr>
        <h2>Links HTML - Sintaxe</h2>
        <p>A tag HTML <code>&lt;a&gt;</code>define um hiperlink. Possui a seguinte sintaxe:</p>
        <p><code>&lt; a href "url"&gt;texto link &lt;/a&gt;</code></p>
        <p>O atributo mais importante do <code>&lt;a&gt;</code>elemento é o <code>href</code>, que indica o destino do
            link.</p>
        <p>O texto do link é a parte que ficará visível ao leitor.</p>
        <p>Clicar no texto do link enviará o leitor ao endereço URL especificado.</p>
        <h3>Exemplo:</h3>
        <hr>
        <p><code>&lt;a href ="https://www.Google.com/"&gt;Visite google.com &lt;/a&gt;</code></p>
        <p>Por padrão, os links aparecerão da seguinte forma em todos os navegadores:</p>
        <ul>
            <li>Um link não visitado está sublinhado e azul</li>
            <li>Um link visitado está sublinhado e roxo</li>
            <li>Um link ativo está sublinhado e vermelho</li>


        </ul>
        <hr>
        <h2>Links HTML - O atributo de destino</h2>
        <p>Por padrão, a página vinculada será exibida na janela atual do navegador. Para alterar isso, você deve
            especificar outro destino para o link.</p>
        <p>O atributo <code>target</code> especifica onde abrir o documento vinculado.</p>
        <p>O atributo <code>target</code> pode ter um dos seguintes valores:</p>
        <ul>
            <li><code>_self</code> - Padrão. Abre o documento na mesma janela/aba em que foi clicado</li>
            <li><code>_blank</code> - Abre o documento em uma nova janela ou guia</li>
            <li><code>_parent</code> - Abre o documento no quadro pai</li>
            <li><code>_top</code> - Abre o documento em todo o corpo da janela</li>
        </ul>
        <h3>Exemplo:</h3>
        <p>Use <code>target="_blank"</code> para abrir o documento vinculado em uma nova janela ou guia do navegador:
        </p>
        <p><code>&lt;a href="https://www.google.com/" target="_blank"&gt;Visite o google.com&lt;/a&gt;</code></p>
        <a href="https://www.w3schools.com/">Visit W3Schools.com!</a>

        <hr>
        <h2>URLs absolutos versus URLs relativos</h2>
        <p>Ambos os exemplos acima usam um URL absoluto (um endereço da web completo) no atributo <code>href</code>.</p>
        <p>Um link local (um link para uma página dentro do mesmo site) é especificado com um <b>URL relativo </b> (sem
            a parte “https://www”):</p>
        <h3>Exemplo:</h3>
        <p>Url absoluto</p>
        <p><code>&lt;p&gt;&lt;a a href="https://www.google.com/"&gt;Google&lt;/a&gt;&lt;/p&gt;</code></p>
        <p>Url relativo</p>
        <p><code>&lt;p&gt;&lt;a href="html_images.asp"&gt;HTML Images&lt;/a&gt;&lt;/p&gt;</code></p>
        <hr>

        <hr>
        <h2>Links HTML - Use uma imagem como link</h2>
        <p>Para usar uma imagem como link, basta colocar a <code>&lt;img&gt;</code> tag dentro da <code>&lt;a&gt;</code>
            tag:</p>
        <h3>Exemplo:</h3>
        <p><code>&lt;a href="default.asp"&gt;</code></p>
        <p><code>&lt;img src ="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;"&gt;/code></p>
        <hr>
        
        <h2>Link para um endereço de e-mail</h2>
        <p>Use <code>mailto:</code> dentro do <code>href</code> atributo para criar um link que abra o programa de
            e-mail do usuário (para permitir que ele envie um novo e-mail):</p>
        <h3>Exemplo:</h3>
        <p><code>&lt;a href="mailto:someone@example.com"&gt;Enviar e-mail&lt;/a&gt;</code></p>
        <hr>

        <h2>Botão como um link</h2>
        <p>Para usar um botão HTML como link, você deve adicionar algum código JavaScript.</p>
        <p>JavaScript permite especificar o que acontece em determinados eventos, como o clique de um botão:</p>
        <h3>Exemplo:</h3>
        <p><code>&lt;button onclick="document.location='default.asp'"&gt;HTML Tutorial&lt;/button&gt;</code></p>
        <hr>

        <p>Por padrão, os links aparecerão da seguinte forma em todos os navegadores:</p>
        <ul>
            <li>Um link não visitado está sublinhado e azul</li>
            <li>Um link visitado está sublinhado e roxo</li>
            <li>Um link ativo está sublinhado e vermelho</li>
        </ul>
        <h3>Resumo do capítulo</h3>
        <ul>
            <li>Use a tag <code>&lt;a&gt;</code> para definir um link</li>
            <li>Use o <code>href</code> para definir o endereço do link</li>
            <li>Use o <code>target</code> para definir onde abrir o documento vinculado</li>
            <li>Use o <code>&lt;img&gt;</code> dentro do <code>&lt;a&gt;</code> para usar uma imagem como link</li>
            <li>Use o <code>mailto:</code> esquema dentro do <code>href</code> para criar um link que abre o programa de
                e-mail do usuário</li>
        </ul>


    </div>
    <div class="content">
        <H1>Favicon HTML</H1>
        <hr>
        <p>Um favicon é uma pequena imagem exibida ao lado do título da página na guia do navegador.</p>
        <hr>
        <h2>Como adicionar um favicon em HTML</h2>
        <p>Você pode usar qualquer imagem que desejar como favicon. Você também pode criar seu próprio favicon em sites
            como <a href="https://www.favicon.cc">https://www.favicon.cc</a></p>
        <p><b>Dica:</b>Um favicon é uma imagem pequena, portanto deve ser uma imagem simples com alto contraste.

        </p>
        <p>Para adicionar um favicon ao seu site, salve sua imagem de favicon no diretório raiz do seu servidor web ou
            crie uma pasta no diretório raiz chamada imagens e salve sua imagem de favicon nesta pasta. Um nome comum
            para uma imagem de favicon é “favicon.ico”.</p>
        <p>Em seguida, adicione um <code>&lt;link&gt;</code>elemento ao seu arquivo “index.html”, após o
            <code>&lt;title&gt;</code>assim:
        </p>
        <p>
        <pre>
    <code>
      &lt;!DOCTYPE html&gt;
      &lt;html&gt;
      &lt;head&gt;
        &lt;title&gt;My Page Title&lt;/title&gt;
        &lt;link rel="icon" type="image/x-icon" href="/images/favicon.ico"&gt;
      &lt;/head&gt;
      &lt;body&gt;
  
      &lt;h1&gt;This is a Heading&lt;/h1&gt;
      &lt;p&gt;This is a paragraph.&lt;/p&gt;
  
      &lt;/body&gt;
      &lt;/html&gt;
    </code>
  </pre>
        </p>
        <p>Agora salve o arquivo “index.html” e recarregue-o em seu navegador. A guia do seu navegador agora deve exibir
            a imagem do seu favicon à esquerda do título da página.</p>
        <h3>Resumo do capítulo</h3>
        <ul>
            <li>Use o <code>&lt;link&gt;</code>elemento HTML para inserir um favicon</li>
        </ul>

    </div>
    <div class="content">
        <h1>Tabelas HTML
        </h1>
        <hr>
        <p>As tabelas HTML permitem que os desenvolvedores da web organizem os dados em linhas e colunas.</p>
        <h3>Exemplo</h3>
        <h2>HTML Table</h2>

        <table>
            <tr>
                <th>Company</th>
                <th>Contact</th>
                <th>Country</th>
            </tr>
            <tr>
                <td>Alfreds Futterkiste</td>
                <td>Maria Anders</td>
                <td>Germany</td>
            </tr>
            <tr>
                <td>Centro comercial Moctezuma</td>
                <td>Francisco Chang</td>
                <td>Mexico</td>
            </tr>
            <tr>
                <td>Ernst Handel</td>
                <td>Roland Mendel</td>
                <td>Austria</td>
            </tr>
            <tr>
                <td>Island Trading</td>
                <td>Helen Bennett</td>
                <td>UK</td>
            </tr>
            <tr>
                <td>Laughing Bacchus Winecellars</td>
                <td>Yoshi Tannamuri</td>
                <td>Canada</td>
            </tr>
            <tr>
                <td>Magazzini Alimentari Riuniti</td>
                <td>Giovanni Rovelli</td>
                <td>Italy</td>
            </tr>
        </table>
        <p>Sendo assim o codigo para tal tabela:</p>
        <p>
        <pre><code>&lt;table&gt;
    &lt;tr&gt;
      &lt;th&gt;Company&lt;/th&gt;
      &lt;th&gt;Contact&lt;/th&gt;
      &lt;th&gt;Country&lt;/th&gt;
    &lt;/tr&gt;
    &lt;tr&gt;
      &lt;td&gt;Alfreds Futterkiste&lt;/td&gt;
      &lt;td&gt;Maria Anders&lt;/td&gt;
      &lt;td&gt;Germany&lt;/td&gt;
    &lt;/tr&gt;
    &lt;tr&gt;
      &lt;td&gt;Centro comercial Moctezuma&lt;/td&gt;
      &lt;td&gt;Francisco Chang&lt;/td&gt;
      &lt;td&gt;Mexico&lt;/td&gt;
    &lt;/tr&gt;
  &lt;/table&gt;
  </code></pre>
        </p>
        <hr>
        <h2>Células de tabela</h2>
        <p>Cada célula da tabela é definida por um <code>&lt;td&gt;</code>e uma <code>&lt;/td&gt;</code>tag.</p>
        <p>Tudo entre <code>&lt;td&gt;</code> e <code>&lt;/td&gt;</code> é o conteudo de uma tabela</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>&lt;table&gt;
    &lt;tr&gt;
      &lt;td&gt;Emil&lt;/td&gt;
      &lt;td&gt;Tobias&lt;/td&gt;
      &lt;td&gt;Linus&lt;/td&gt;
    &lt;/tr&gt;
  &lt;/table&gt;
  </code></pre>
        <hr>
        <h2>Linhas da tabela</h2>
        <p>Cada linha da tabela começa com um <code>&lt;tr&gt;</code>e termina com uma <code>&lt;/tr&gt;</code>tag.</p>
        <h3>Exemplo:</h3>
        <hr>
        <p>
        <pre><code>&lt;table&gt;
    &lt;tr&gt;
      &lt;td&gt;Emil&lt;/td&gt;
      &lt;td&gt;Tobias&lt;/td&gt;
      &lt;td&gt;Linus&lt;/td&gt;
    &lt;/tr&gt;
    &lt;tr&gt;
      &lt;td&gt;16&lt;/td&gt;
      &lt;td&gt;14&lt;/td&gt;
      &lt;td&gt;10&lt;/td&gt;
    &lt;/tr&gt;
  &lt;/table&gt;
  </code></pre>
        </p>
        <hr>
        <h2>Cabeçalhos de tabela</h2>
        <p>Às vezes você deseja que suas células sejam células de cabeçalho de tabela. Nesses casos, use a
            <code>&lt;th&gt;</code>tag em vez da <code>&lt;td&gt;</code> tag
        </p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>&lt;table&gt;
    &lt;tr&gt;
      &lt;th&gt;Person 1&lt;/th&gt;
      &lt;th&gt;Person 2&lt;/th&gt;
      &lt;th&gt;Person 3&lt;/th&gt;
    &lt;/tr&gt;
    &lt;tr&gt;
      &lt;td&gt;Emil&lt;/td&gt;
      &lt;td&gt;Tobias&lt;/td&gt;
      &lt;td&gt;Linus&lt;/td&gt;
    &lt;/tr&gt;
    &lt;tr&gt;
      &lt;td&gt;16&lt;/td&gt;
      &lt;td&gt;14&lt;/td&gt;
      &lt;td&gt;10&lt;/td&gt;
    &lt;/tr&gt;
  &lt;/table&gt;
  </code></pre>
        <hr>
        <h2>Aplicaçõe css em tabelas</h2>
        <p>Estilo de bordas e células: Você pode definir o estilo das bordas das células da tabela, como largura, cor e
            estilo (por exemplo, sólida, pontilhada, etc.), usando propriedades CSS como border, border-width,
            border-color e border-style.</p>
        <p>Espaçamento e preenchimento: As propriedades CSS padding e margin podem ser usadas para controlar o espaço
            dentro e ao redor das células da tabela, respectivamente. Isso pode ajudar a ajustar o espaçamento entre as
            células e as bordas da tabela.</p>
        <p>Estilo de texto e cores: Você pode definir o estilo do texto dentro das células da tabela, como cor, tamanho
            da fonte, alinhamento e estilo (negrito, itálico, etc.), usando propriedades CSS como color, font-size,
            text-align e font-weight.</p>
        <p>Estilo de fundo: É possível definir uma cor de fundo para as células da tabela usando a propriedade CSS
            background-color. Isso pode ajudar a destacar determinadas células ou linhas na tabela.</p>
        <p>Layout da tabela: CSS também pode ser usado para controlar o layout da tabela, como largura da tabela,
            largura das colunas, altura das linhas e alinhamento da tabela. Isso pode ser feito usando propriedades como
            width, height, table-layout e vertical-align</p>
        <p>Em suma todas Aplicações de css tambem influenciam as tabelas como foi aprendido até agora</p>

    </div>
    <div class="content">
        <h1>Listas HTML</h1>
        <hr>
        <p>As listas HTML permitem que os desenvolvedores da web agrupem um conjunto de itens relacionados em listas.
        </p>
        <hr>
        <h3>Exemplo:</h3>
        <h4>An Unordered HTML List</h4>

        <ul>
            <li>Coffee</li>
            <li>Tea</li>
            <li>Milk</li>
        </ul>

        <h2>An Ordered HTML List</h2>

        <ol>
            <li>Coffee</li>
            <li>Tea</li>
            <li>Milk</li>
        </ol>
        <hr>
        <h2>Lista HTML não ordenada
        </h2>
        <p>Uma lista não ordenada começa com a <code>&lt;ul&gt;</code>tag. Cada item da lista começa com a
            <code>&lt;li&gt;</code>tag.
        </p>
        <p>Os itens da lista serão marcados com marcadores (pequenos círculos pretos) por padrão:</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>&lt;ul&gt;
    &lt;li&gt;Coffee&lt;/li&gt;
    &lt;li&gt;Tea&lt;/li&gt;
    &lt;li&gt;Milk&lt;/li&gt;
  &lt;/ul&gt;
  </code></pre>
        <hr>
        <h2>Lista HTML ordenada</h2>
        <p>Uma lista ordenada começa com a <code>&lt;ol&gt;</code>tag. Cada item da lista começa com a
            <code>&lt;li&gt;</code> tag.
        </p>
        <p>Os itens da lista serão marcados com números por padrão:</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>&lt;ol&gt;
    &lt;li&gt;Coffee&lt;/li&gt;
    &lt;li&gt;Tea&lt;/li&gt;
    &lt;li&gt;Milk&lt;/li&gt;
  &lt;/ol&gt;
  </code></pre>
        <hr>
        <h2>Listas de descrição HTML</h2>
        <p>HTML também oferece suporte a listas de descrição.</p>
        <p>Uma lista de descrição é uma lista de termos, com uma descrição de cada termo.</p>
        <p>A <code>&lt;d1&gt;</code>tag define a lista de descrição, a <code>&lt;dt&gt;</code>tag define o termo (nome)
            e a <code>&lt;dd&gt;</code>tag descreve cada termo:</p>
        <h3>Exemplo:</h3>
        <hr>
        <p>
        <pre><code>&lt;ol&gt;
    &lt;li&gt;Coffee&lt;/li&gt;
    &lt;li&gt;Tea&lt;/li&gt;
    &lt;li&gt;Milk&lt;/li&gt;
  &lt;/ol&gt;
  </code></pre>
        </p>
        <hr>
        <h1>Listas ordenadas em HTML</h1>
        <hr>
        <p>A tag HTML <code>&lt;ol&gt;</code>define uma lista ordenada. Uma lista ordenada pode ser numérica ou
            alfabética</p>
        <h2>Lista HTML ordenada</h2>
        <p>Uma lista ordenada começa com a <code>&lt;ol&gt;</code>tag. Cada item da lista começa com a
            <code>&lt;li&gt;</code>tag.
        </p>
        <p>Os itens da lista serão marcados com números por padrão:</p>
        <h3>Exemplo:</h3>
        <hr>
        <p>
        <pre><code>&lt;ol&gt;
    &lt;li&gt;Coffee&lt;/li&gt;
    &lt;li&gt;Tea&lt;/li&gt;
    &lt;li&gt;Milk&lt;/li&gt;
  &lt;/ol&gt;
  </code></pre>
        </p>
        <hr>
        <p>Com este codigo ficando exatamente assim:</p>
        <ol>
            <li>Coffee</li>
            <li>Tea</li>
            <li>Milk</li>
        </ol>
        <hr>
        <h2>Lista HTML ordenada - O atributo Type</h2>
        <p>O <code>&lt;type&gt;</code>atributo da <code>&lt;ol&gt;</code>tag define o tipo de marcador do item da lista:
        </p>
        <table>
            <tbody>
                <tr>
                    <th>Tipo</th>
                    <th>Descrição</th>
                </tr>
                <tr>
                    <td>type="1"</td>
                    <td>A lista será enumerada com numeros inteiros (default)</td>
                </tr>
                <tr>
                    <td>type="A"</td>
                    <td>Os itens da lista serão numerados com letras maiúsculas</td>
                </tr>
                <tr>
                    <td>type="a"</td>
                    <td>Os itens da lista serão numerados com letras minúsculas</td>
                </tr>
                <tr>
                    <td>type="I"</td>
                    <td>Os itens da lista serão numerados com números romanos maiúsculos</td>
                </tr>
                <tr>
                    <td>type="i"</td>
                    <td>Os itens da lista serão numerados com números romanos minúsculo</td>
                </tr>
            </tbody>
        </table>
        <h2>Resumo do capitulo</h2>
        <ul>
            <li>Use o <code>&lt;ol&gt;</code>elemento HTML para definir uma lista ordenada</li><br>
            <li>Use o atributo HTML <code>type</code>para definir o tipo de numeração</li><br>
            <li>Use o <code>&lt;li&gt;</code>elemento HTML para definir um item de lista</li><br>

        </ul>




    </div>
    <div class="content">
        <h1>Bloco HTML e elementos embutidos</h1>
        <p>Cada elemento HTML possui um valor de exibição padrão, dependendo do tipo de elemento.</p>
        <p>Os dois valores de exibição mais comuns são bloco e embutido.</p>
        <hr>
        <h2>Elementos em nível de bloco</h2>
        <p>Um elemento em nível de bloco sempre começa em uma nova linha e os navegadores adicionam automaticamente
            algum espaço (uma margem) antes e depois do elemento.</p>
        <p>Um elemento de nível de bloco sempre ocupa toda a largura disponível (estende-se para a esquerda e para a
            direita tanto quanto possível).</p>
        <p>Dois elementos de bloco comumente usados são: <code>&lt;p&gt;</code> e <code>&lt;div&gt;</code>.</p>
        <p>O elemento <code>&lt;p&gt;</code>elemento define um parágrafo em um documento HTML.</p>
        <p>O elemento <code>&lt;div&gt;</code>define uma divisão ou seção em um documento HTML.</p>
        <p class="exemplo">O elemento <code>&lt;p&gt;</code>é um elemento de nível de bloco.</p>
        <p class="exemplo">O elemento <code>&lt;div&gt;</code> é um elemento de nível de bloco.</p>
        <hr>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>&lt;p&gt;Hello World&lt;/p&gt;
    &lt;div&gt;Hello World&lt;/div&gt;
    </code></pre>
        <hr>
        <p>Aqui estão os elementos de nível de bloco em HTML:</p>
        <pre><code>&lt;address&gt;&lt;/address&gt;
    &lt;article&gt;&lt;/article&gt;
    &lt;aside&gt;&lt;/aside&gt;
    &lt;blockquote&gt;&lt;/blockquote&gt;
    &lt;details&gt;&lt;/details&gt;
    &lt;dd&gt;&lt;/dd&gt;
    &lt;div&gt;&lt;/div&gt;
    &lt;dl&gt;&lt;/dl&gt;
    &lt;dt&gt;&lt;/dt&gt;
    &lt;fieldset&gt;&lt;/fieldset&gt;
    &lt;figcaption&gt;&lt;/figcaption&gt;
    &lt;figure&gt;&lt;/figure&gt;
    &lt;footer&gt;&lt;/footer&gt;
    &lt;form&gt;&lt;/form&gt;
    &lt;h1&gt;-&lt;h6&gt;&lt;/h6&gt;
    &lt;header&gt;&lt;/header&gt;
    &lt;hr&gt;&lt;/hr&gt;
    &lt;li&gt;&lt;/li&gt;
    &lt;main&gt;&lt;/main&gt;
    &lt;nav&gt;&lt;/nav&gt;
    &lt;noscript&gt;&lt;/noscript&gt;
    &lt;ol&gt;&lt;/ol&gt;
    &lt;p&gt;&lt;/p&gt;
    &lt;pre&gt;&lt;/pre&gt;
    &lt;section&gt;&lt;/section&gt;
    &lt;table&gt;&lt;/table&gt;
    &lt;tfoot&gt;&lt;/tfoot&gt;
    &lt;ul&gt;&lt;/ul&gt;
    &lt;video&gt;&lt;/video&gt;</code></pre>
        <hr>
        <h2>Elementos embutidos</h2>
        <p>Um elemento embutido não começa em uma nova linha.</p>
        <p>Um elemento embutido ocupa apenas a largura necessária.</p>
        <p>Este é um elemento <span class="exemplo"> <code>&lt;span&gt;</code>dentro de um parágrafo.</span></p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>&lt;span&gt;HelloWorld&lt;/span&gt;</code></pre>
        <hr>
        <hr>
        <h1>O elemento <code>&lt;div&gt;</code></h1>
        <p>O elemento <code>&lt;div&gt;é frequentemente usado como contêiner para outros elementos HTML.</code></p>
        <p>O elemento <code>&lt;div&gt; não possui atributos obrigatórios, mas <code>style</code> ,
            <code>class</code>e<code>id</code>são comuns.</code>
        </p>
        <p>Quando usado junto com CSS, o <code>&lt;div&gt;</code>elemento pode ser usado para estilizar blocos de
            conteúdo:</p>
        <h2>Exemplo:</h2>
        <p>
        <pre><code>&lt;div style="background-color:black;color:white;padding:20px;"&gt;
        &lt;h2&gt;London&lt;/h2&gt;
        &lt;p&gt;London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.&lt;/p&gt;
      &lt;/div&gt;
      </code></pre>
        </p>
        <P>
        <div style="background-color:rgb(163, 19, 19);color:white;padding:20px;">
            <h2>London</h2>
            <p>London is the capital city of England. It is the most populous city in the United Kingdom, with a
                metropolitan area of over 13 million inhabitants.</p>
        </div>
        </P>
        <p>Ficando assim.</p>
        <h3>Resumo do capítulo</h3>
        <ul>
            <li>Um elemento de nível de bloco sempre começa em uma nova linha e ocupa toda a largura disponível</li>
            <li>Um elemento embutido não começa em uma nova linha e ocupa apenas a largura necessária</li>
            <li>O elemento<code>&lt;div&gt;</code>é de nível de bloco e geralmente é usado como contêiner para outros
                elementos HTML</li>


        </ul>

    </div>
    <div class="content">
        <h1>Elemento HTML Div</h1>
        <p>O elemento <code>&lt;div&gt;</code>é usado como contêiner para outros elementos HTML.</p>
        <h2>O elemento <code>&lt;div&gt;</code></h2>
        <p>O elemento <code>&lt;div&gt;</code> é por padrão um elemento de bloco, o que significa que ocupa toda a
            largura disponível e vem com quebras de linha antes e depois.</p>
        <h3>Exemplo:</h3>
        <p>O elemento <code>&lt;div&gt;</code>é por padrão um elemento de bloco, o que significa que ocupa toda a
            largura disponível e vem com quebras de linha antes e depois.
        </p>
        <h3>Exemplo:</h3>
        <hr>
        <p>Um elemento <code>&lt;div&gt;</code>ocupa toda a largura disponível:</p>
        <p>Lorem Ipsum <code>&lt;div&gt;</code>Eu sou uma div <code>&lt;/div&gt;</code> dolor sit amet.</p>
        <h3>Resultado:</h3>
        <hr>
        <p>Lorem Ipsum
        <div class="exemplo">Eu sou uma div</div> dolor sit amet.</p>
        <p> o <code>&lt;div&gt;</code>não possui atributos nescessarios mas <code>style</code>,<code>class</code> e
            <code>id</code> são comuns.
        </p>
        <hr>
        <h3>Exemplo:</h3>
        <p>Um elemento <code>&lt;div&gt;</code> com elementos HTML:</p>
        <pre><code>&lt;div&gt;
    &lt;h2&gt;London&lt;/h2&gt;
    &lt;p&gt;London is the capital city of England.&lt;/p&gt;
    &lt;p&gt;London has over 13 million inhabitants.&lt;/p&gt;
  &lt;/div&gt;<br>
  </code></pre>
        <p><b>Resultado:</b></p>
        <div class="exemplo">
            <h2>London</h2>
            <p>London is the capital city of England.</p>
            <p>London has over 13 million inhabitants.</p>
        </div>
        <h1>Resumo:</h1>
        <p>O elemento <code>&lt;div&gt;</code> em suma é um elemento de bloco genérico usado em HTML para criar divisões
            ou seções em uma página da web. Ele não possui significado semântico específico e é frequentemente usado
            como um contêiner para agrupar e estilizar elementos relacionados em conjunto.</p>
        <p>No proprio elemento é possivel aplicar todas as informações aprendidas anteriormente de css.</p>

    </div>
    <div class="content">
        <h1>Atributo de classe HTML:</h1>
        <p>O atributo HTML <code>class</code>é usado para especificar uma classe para um elemento HTML.

            Vários elementos HTML podem compartilhar a mesma classe.

        </p>
        <h2>Usando o atributo class</h2>
        <p>O <code>class</code> atributo é frequentemente usado para apontar para um nome de classe em uma folha de
            estilo. Também pode ser usado por JavaScript para acessar e manipular elementos com o nome de classe
            específico.</p>
        <p>No exemplo a seguir temos três <code>&lt;div&gt;</code>elementos com um <code>class</code> atributo com o
            valor “cidade”. Todos os três <code>&lt;div&gt;</code>elementos serão estilizados igualmente de acordo com a
            <code>.city</code>definição de estilo na seção principal:
        </p>
        <h2>Exemplo:</h2>


        <div class="city">
            <h2>London</h2>
            <p>London is the capital of England.</p>
        </div>

        <div class="city">
            <h2>Paris</h2>
            <p>Paris is the capital of France.</p>
        </div>

        <div class="city">
            <h2>Tokyo</h2>
            <p>Tokyo is the capital of Japan.</p>
        </div>
        <p><b>Ficando assim o codigo:</b></p>
        <hr>
        <br>
        <pre><code>&lt;!DOCTYPE html&gt;
            &lt;html&gt;
            &lt;head&gt;
            &lt;style&gt;
            .city {
              background-color: tomato;
              color: white;
              border: 2px solid black;
              margin: 20px;
              padding: 20px;
            }
            &lt;/style&gt;
            &lt;/head&gt;
            &lt;body&gt;
            
            &lt;div class="city"&gt;
              &lt;h2&gt;London&lt;/h2&gt;
              &lt;p&gt;London is the capital of England.&lt;/p&gt;
            &lt;/div&gt;
            
            &lt;div class="city"&gt;
              &lt;h2&gt;Paris&lt;/h2&gt;
              &lt;p&gt;Paris is the capital of France.&lt;/p&gt;
            &lt;/div&gt;
            
            &lt;div class="city"&gt;
              &lt;h2&gt;Tokyo&lt;/h2&gt;
              &lt;p&gt;Tokyo is the capital of Japan.&lt;/p&gt;
            &lt;/div&gt;
            
            &lt;/body&gt;
            &lt;/html&gt;
            </code></pre>
        <hr>
        <h2>A sintaxe da classe:</h2>
        <p>Para criar uma classe; escreva um ponto final (.), seguido por um nome de classe. Em seguida, defina as
            propriedades CSS entre chaves {}:</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>
    &lt;!DOCTYPE html&gt;
    &lt;html&gt;
    &lt;head&gt;
    &lt;style&gt;
    .city {
      background-color: tomato;
      color: white;
      padding: 10px;
    }
    &lt;/style&gt;
    &lt;/head&gt;
    &lt;body&gt;
    
    &lt;h2 class="city"&gt;London&lt;/h2&gt;
    &lt;p&gt;London is the capital of England.&lt;/p&gt;
    
    &lt;h2 class="city"&gt;Paris&lt;/h2&gt;
    &lt;p&gt;Paris is the capital of France.&lt;/p&gt;
    
    &lt;h2 class="city"&gt;Tokyo&lt;/h2&gt;
    &lt;p&gt;Tokyo is the capital of Japan.&lt;/p&gt;
    
    &lt;/body&gt;
    &lt;/html&gt;
    </code></pre>
        <hr>

    </div>
    <div class="content">
        <h1>Atributo de identificação HTML.</h1>
        <p>O atributo HTML <code>&lt;id&gt;</code>é usado para especificar um ID exclusivo para um elemento HTML.</p>
        <p>Você não pode ter mais de um elemento com o mesmo id em um documento HTML.</p>
        <hr>
        <h2>Usando o atributo id</h2>
        <p>O atributo<code>id</code>especifica um ID exclusivo para um elemento HTML. O valor do idatributo deve ser
            exclusivo no documento HTML.</p>
        <p>O atributo <code>id</code>é usado para apontar para uma declaração de estilo específica em uma folha de
            estilos. Também é usado por JavaScript para acessar e manipular o elemento com o id específico.</p>
        <p>A sintaxe para id é: escreva um caractere hash (#), seguido por um nome de id. Em seguida, defina as
            propriedades CSS entre chaves {}.</p>
        <p>No exemplo a seguir temos um <code>&lt;h1&gt;</code>elemento que aponta para o nome do id “myHeader”. Este
        </p>
        <p><code>&lt;h1&gt;</code>elemento será estilizado de acordo com a <code>#myHeader</code>definição de estilo na
            seção head:</p>
        <H3>Exemplo:</H3>
        <hr>
        <h1 id="myHeader">My Header</h1>
        <hr>
        <p><b>Ficando assim o codigo:</b></p>
        <p>
        <pre><code>
    &lt;!DOCTYPE html&gt;
    &lt;html&gt;
    &lt;head&gt;
    &lt;style&gt;
    #myHeader {
      background-color: lightblue;
      color: black;
      padding: 40px;
      text-align: center;
    }
    &lt;/style&gt;
    &lt;/head&gt;
    &lt;body&gt;
    
    &lt;h1 id="myHeader"&gt;My Header&lt;/h1&gt;
    
    &lt;/body&gt;
    &lt;/html&gt;
    </code></pre>
        </p>
        <hr>
        <h2>Diferença entre classe e ID</h2>
        <p>Um nome de classe pode ser usado por vários elementos HTML, enquanto um nome de id deve ser usado apenas por
            um elemento HTML dentro da página</p>
        <hr>
        <h2>Marcadores HTML com ID e links</h2>
        <p>Os marcadores HTML são usados ​​para permitir que os leitores acessem partes específicas de uma página da
            web.</p>
        <p>Os marcadores podem ser úteis se a sua página for muito longa.</p>
        <p>Para usar um marcador, você deve primeiro criá-lo e depois adicionar um link a ele.</p>
        <p>Então, quando o link for clicado, a página rolará até o local com o marcador.</p>
        <hr>
        <h3>Exemplo:</h3>
        <p>Primeiro, crie um marcador com o <code>id</code> atributo:</p>
        <pre><code>
        &lt;h2 id="C4"&gt;Chapter 4&lt;/h2&gt;
        </code></pre>
        <p>Em seguida, adicione um link para o marcador ("Pular para o Capítulo 4"), na mesma página:

        </p>
        <hr>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>
            &lt;a href="#C4"&gt;Jump to Chapter 4&lt;/a&gt;
            </code></pre>
        <hr>
        <p>Ou adicione um link ao marcador ("Pular para o Capítulo 4"), de outra página:</p>
        <pre><code>
                &lt;a href="html_demo.html#C4"&gt;Jump to Chapter 4&lt;/a&gt;
                </code></pre>
        <p><b>Ficando assim:</b></p>
        <a href="html_demo.html#C4">Jump to Chapter 4</a>.
        <hr>
        <ul>
            <li>Resumo do Capítulo:</li>
            <li>O <code>id</code> atributo é usado para especificar um ID exclusivo para um elemento HTML.</li>
            <li>O valor do <code>id</code> atributo deve ser exclusivo no documento HTML.</li>
            <li>O <code>id</code> atributo é usado por CSS e JavaScript para estilizar/selecionar um elemento
                específico.</li>
            <li>O valor do <code>id</code> atributo diferencia maiúsculas de minúsculas.</li>
            <li>O <code>id</code> atributo também é usado para criar marcadores HTML.</li>

        </ul>


    </div>
    <div class="content">
        <h1>Iframes HTML</h1>
        <hr>
        <p>Um iframe HTML é usado para exibir uma página da web dentro de uma página da web.</p>
        <hr>
        <h2>Sintaxe HTML Iframe
        </h2>
        <p>A tag HTML <code>&lt;iframe&gt;</code> especifica um quadro embutido</p>
        <p>Um quadro embutido é usado para incorporar outro documento no documento HTML atual.</p>
        <h3>Sintaxe:</h3>
        <hr>
        <pre><code>
    &lt;iframe src="url" title="description"&gt;&lt;/iframe&gt;
    </code></pre>
        <p><b>ficando assim:</b></p>
        <iframe src="url" title="description"></iframe>
        <h2>Iframe - Definir Altura e Largura</h2>
        <hr>
        <p>Use os atributos <code>height</code> e <code>width</code>para especificar o tamanho do iframe.</p>
        <p>A altura e a largura são especificadas em pixels por padrão:</p>
        <hr>
        <pre><code>
        &lt;iframe src="demo_iframe.htm" height="200" width="300" title="Iframe Example"&gt;&lt;/iframe&gt;
        </code></pre>
        <hr>
        <p>Ou você pode adicionar o <code>style</code>e usar o CSS <code>height</code> e <code>width</code>as
            propriedades</p>
        <h3>Exemplo:</h3>
        <pre><code>
            &lt;iframe src="demo_iframe.htm" style="height:200px;width:300px;" title="Iframe Example"&gt;&lt;/iframe&gt;
            </code></pre>
        <hr>
        <h2>Iframe - Remover a borda</h2>
        <p>Por padrão, um iframe possui uma borda ao seu redor.</p>
        <p>Para remover a borda, adicione o <code>style</code> e use a propriedade<code>border</code>Css:</p>
        <hr>
        <pre><code>
                &lt;iframe src="demo_iframe.htm" style="border:none;" title="Iframe Example"&gt;&lt;/iframe&gt;
                </code></pre>
        <hr>
        <h2>Iframe – Alvo para um Link</h2>
        <p>um iframe pode ser usado como quadro de destino para um link.</p>
        <p>O atributo<code>target</code>do link deve referir-se ao <code>name</code>atributo do iframe</p>







    </div>
    <div class="content">
        <h1>HTMLJavaScript</h1>
        <hr>
        <p>JavaScript torna as páginas HTML mais dinâmicas e interativas.</p>
        <hr>
        <h1>JavaScript</h1>

        <button type="button" onclick="document.getElementById('demo').innerHTML = Date()">
            Mostre data e hora</button>

        <p id="demo"></p>
        <h2>A tag HTML <code>&lt;script&gt;</code></h2>
        <hr>
        <p>A tag HTML <code>&lt;script&gt;</code> é usada para definir um script do lado do cliente (JavaScript).</p>
        <p>O elemento <code>&lt;script&gt;</code> elemento contém instruções de script ou aponta para um arquivo de
            script externo por meio do atributo <code>src</code>.</p>
        <p>Os usos comuns do JavaScript são manipulação de imagens, validação de formulários e alterações dinâmicas de
            conteúdo.</p>
        <p>para selecionar um elemento HTML, o JavaScript geralmente usa o metodo
        <pre><code>
    document.getElementById()
    </code></pre>
        </p>
        <p>Este exemplo de JavaScript escreve "Olá JavaScript!" em um elemento HTML com id="demo":</p>
        <hr>
        <pre><code>
    &lt;script&gt;
    document.getElementById("demo").innerHTML = "Hello JavaScript!";
    &lt;/script&gt;
    </code></pre>
        <hr>
        <p><b>Ficando assim:</b></p>
        <h2>Use JavaScript para mudar um texto</h2>
        <p>seu exemplo escreve "Olá JavaScript!" em um elemento HTML com id="demo":</p>

        <p id="demo"></p>

        <script>
            document.getElementById("demo").innerHTML = "Hello JavaScript!";
        </script>
        <h2>Um gostinho de JavaScript</h2>
        <hr>
        <h3>Exemplo:</h3>
        <p>JavaScript pode alterar o conteúdo:</p>
        <h1>JavaScript</h1>

        <p>JavaScript pode mudar o conteudo de uma pagina </p>

        <button type="button" onclick="myFunction()">Click Me!</button>

        <p id="demo">demonstração</p>

        <script>
            function myFunction() {
                document.getElementById("demo").innerHTML = "Hello JavaScript!";
            }
        </script>
        <hr>
        <p><b>Sendo assim o codigo:</b></p>
        <pre><code>
    &lt;h1&gt;My First JavaScript&lt;/h1&gt;
    
    &lt;p&gt;JavaScript can change the content of an HTML element:&lt;/p&gt;
    
    &lt;button type="button" onclick="myFunction()"&gt;Click Me!&lt;/button&gt;
    
    &lt;p id="demo"&gt;This is a demonstration.&lt;/p&gt;
    
    &lt;script&gt;
    function myFunction() { 
      document.getElementById("demo").innerHTML = "Hello JavaScript!";
    }
    &lt;/script&gt;
    </code></pre>



    </div>
    <div class="content">
        <h1>Elementos Semânticos HTML</h1>
        <hr>
        <p>Elementos semânticos = elementos com significado.</p>
        <hr>
        <h2>O que são elementos semânticos?</h2>
        <p>Um elemento semântico descreve claramente seu significado tanto para o navegador quanto para o desenvolvedor.
        </p>
        <p>Exemplos de elementos <b>não semânticos</b> : <code>&lt;div&gt;</code> e <code>&lt;span&gt;</code> - Não diz
            nada sobre o seu conteúdo.</p>
        <p>Exemplos de elementos <b>semânticos</b>: <code>&lt;form&gt;</code>, <code>&lt;table&gt;</code> e
            <code>&lt;article&gt;</code>- Define claramente seu conteúdo.
        </p>
        <hr>
        <h2>Elementos Semânticos em HTML</h2>
        <p>Muitos sites contêm código HTML como:
        <pre><code>&lt;div id="nav"&gt;</code></pre>
        <pre><code>&lt;div class="header"&gt;</code></pre>
        <pre><code>&lt;div id="footer"&gt;</code></pre>

        para indicar navegação, cabeçalho e rodapé.</p>
        <p>Em HTML existem alguns elementos semânticos que podem ser usados ​​para definir diferentes partes de uma
            página web: </p>
        <ul>
            <li>
                <pre><code>&lt;article&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;aside&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;details&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;figcaption&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;figure&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;footer&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;header&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;main&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;mark&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;nav&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;section&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;summary&gt;</code></pre>
            </li>
            <li>
                <pre><code>&lt;time&gt;</code></pre>
            </li>
        </ul>
        <p>para indicar diferentes partes de uma página ou estruturação de conteúdo.</p>

        <h2>O Elemento HTML &lt;section&gt; </h2>
        <p>O elemento <code>&lt;section&gt;</code>define uma seção em um documento.</p>
        <p>Exemplos de onde um <code>&lt;section&gt;</code>elemento pode ser usado:</p>
        <ul>
            <li>Capítulos</li>
            <li>Introdução</li>
            <li>Novos itens</li>
            <li>Informações de contato</li>

        </ul>
        <hr>
        <h3>Exemplo:</h3>
        <section>
            <h1>WWF</h1>
            <p>O Fundo Mundial para a Natureza (WWF) é uma organização internacional que trabalha em questões relativas
                à conservação, pesquisa e restauração do meio ambiente, anteriormente denominada Fundo Mundial para a
                Vida Selvagem. A WWF foi fundada em 1961.</p>
        </section>

        <section>
            <h1>Símbolo do Panda da WWF</h1>
            <p>O Panda se tornou o símbolo do WWF. O conhecido logotipo do panda do WWF originou-se de um panda chamado
                Chi Chi que foi transferido do Zoológico de Pequim para o Zoológico de Londres no mesmo ano da criação
                do WWF.</p>
        </section>
        <hr>
        <p><b>Fincando assim o codigo:</b></p>
        <hr>
        <pre class="footer "><code >
        &lt;section&gt;
        &lt;h1&gt;WWF&lt;/h1&gt;
        &lt;p&gt;O Fundo Mundial para a Natureza (WWF) é uma organização internacional que trabalha em questões relacionadas à
        conservação, pesquisa e restauração do meio ambiente, anteriormente conhecida como Fundo Mundial para a Vida Selvagem. O
        WWF foi fundado em 1961.&lt;/p&gt;
        &lt;/section&gt;
        
        &lt;section&gt;
        &lt;h1&gt;Símbolo do Panda do WWF&lt;/h1&gt;
        &lt;p&gt;O Panda se tornou o símbolo do WWF. O conhecido logotipo do panda do WWF originou-se de um panda chamado Chi
        Chi que foi transferido do Zoológico de Pequim para o Zoológico de Londres no mesmo ano da fundação do WWF.&lt;/p&gt;
        &lt;/section&gt;
        </code></pre>

        <hr>
        <h2>Elemento HTML <code>&lt;article&gt;</code></h2>
        <p>O elemento <code>&lt;article&gt;</code> especifica conteúdo independente .</p>
        <p>Um artigo deve fazer sentido por si só e deve ser possível distribuí-lo independentemente do resto do site.
        </p>
        <p>Exemplos de onde o elemento <code>&lt;article&gt;</code>pode ser usado:</p>
        <ul>
            <li>Postagens no fórum</li>
            <li>Postagens no blog</li>
            <li>Comentários do usuário</li>
            <li>Cartões de produto</li>
            <li>Artigos de jornal</li>

        </ul>
        <hr>
        <h2>Aninhando o <code>&lt;article&gt;</code> em <code>&lt;section&gt;</code> ou vice-versa.</h2>
        <hr>
        <p>O elemento <code>&lt;article&gt;</code>especifica conteúdo independente</p>
        <p>O elemento <code>&lt;section&gt;</code>elemento define a seção em um documento.</p>
        <p>Podemos usar as definições para decidir como aninhar esses elementos? Não nós não podemos!</p>
        <p>Assim, você encontrará páginas HTML com <code>&lt;section&gt;</code>contendo elementos
            <code>&lt;article&gt;</code>e elementos<code>&lt;article&gt;</code>contendo elementos
            <code>&lt;section&gt;</code>
        </p>
        <hr>
        <h2>Elemento HTML &lt;header&gt;</h2>
        <p>O elemento <code>&lt;header&gt;</code>representa um contêiner para conteúdo introdutório ou um conjunto de
            links de navegação.</p>
        <p>Um elemento <code>&lt;header&gt;</code>normalmente contém:</p>
        <hr>
        <h3>Exemplo:</h3>
        <pre><code>
    &lt;article&gt;
      &lt;header&gt;
        &lt;h1&gt;O Que o WWF Faz?&lt;/h1&gt;
        &lt;p&gt;Missão do WWF:&lt;/p&gt;
      &lt;/header&gt;
      &lt;p&gt;A missão do WWF é deter a degradação do ambiente natural do nosso planeta
      e construir um futuro no qual os seres humanos vivam em harmonia com a natureza.&lt;/p&gt;
    &lt;/article&gt;
    </code></pre>
        <hr>
        <ul>
            <li>um ou mais elementos de título <code>&lt;h1&gt;</code> - <code>&lt;h6&gt;</code></li>
            <li>logotipo ou ícone</li>
            <li>informações de autoria</li>

        </ul>
        <hr>
        <h2>Elemento HTML &lt;footer&gt;</h2>
        <p>O elemento <code>&lt;footer&gt;</code>define um rodapé para um documento ou seção.</p>
        <p>Um elemento <code>&lt;footer&gt;</code>normalmente contém:</p>
        <ul>
            <li>informações de autoria</li>
            <li>Informações sobre direitos autorais</li>
            <li>informações de contato</li>
            <li>Mapa do site</li>
            <li>voltar ao topo links</li>
            <li>documentos relacionados</li>
        </ul>
        <p>Você pode ter vários elementos <code>&lt;footer&gt;</code> em um documento.</p>
        <h2>Elemento HTML &lt;nav&gt;</h2>
        <p>O elemento <code>&lt;nav&gt;</code> define um conjunto de links de navegação.</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>
    &lt;nav&gt;
      &lt;a href="/html/"&gt;HTML&lt;/a&gt; |
      &lt;a href="/css/"&gt;CSS&lt;/a&gt; |
      &lt;a href="/js/"&gt;JavaScript&lt;/a&gt; |
      &lt;a href="/jquery/"&gt;jQuery&lt;/a&gt;
    &lt;/nav&gt;
    </code></pre>
        <hr>
        <h2>Elemento HTML &lt;aside&gt;</h2>
        <p>O elemento <code>&lt;aside&gt;</code> define algum conteúdo além daquele em que está colocado (como uma barra
            lateral).</p>
        <p>O elemento <code>&lt;aside&gt;</code>deve estar indiretamente relacionado ao conteúdo circundante.</p>
        <h3>Exemplo:</h3>
        <hr>
        <p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a
            great summer together with my family!</p>

        <aside>
            <h4>Epcot Center</h4>
            <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international
                pavilions, award-winning fireworks and seasonal special events.</p>
        </aside>
        <hr>
        <p><b>Sendo assim o codigo</b></p>
        <pre><code>
    &lt;p&gt;Minha família e eu visitamos o Centro Epcot neste verão. O clima estava bom e o Epcot estava incrível! Eu tive
    um ótimo verão junto com minha família!&lt;/p&gt;
    
    &lt;aside&gt;
    &lt;h4&gt;Centro Epcot&lt;/h4&gt;
    &lt;p&gt;O Epcot é um parque temático no Walt Disney World Resort, apresentando atrações emocionantes, pavilhões
    internacionais, fogos de artifício premiados e eventos especiais sazonais.&lt;/p&gt;
    &lt;/aside&gt;
    </code></pre>
        <hr>
        <h2>Elementos HTML &lt;figure&gt; e &lt;figcaption&gt; </h2>
        <p>A tag <code>&lt;figure&gt;</code>especifica conteúdo independente, como ilustrações, diagramas, fotos,
            listagens de códigos, etc.</p>
        <p>A tag <code>&lt;figcaption&gt;</code>define a legenda para um <code>&lt;figuer&gt;</code>.O
            <code>&lt;figcaption&gt;</code>pode ser colocado como o primeiro ou o último filho de um
            <code>&lt;figure&gt;</code></p>
        <p>O <code>&lt;img&gt;</code>define a imagem/ilustração real. </p>




    </div>

    <div class="content">

        <h1>Guia de estilo HTML</h1>
        <hr>
        <p>Um código HTML consistente, limpo e organizado torna mais fácil para outras pessoas lerem e compreenderem seu
            código.

            Aqui estão algumas diretrizes e dicas para criar um bom código HTML.</p>

        <h2>Sempre declarar o tipo de documento</h2>
        <p>Sempre declare o tipo de documento como a primeira linha do seu documento.

            O tipo de documento correto para HTML é:</p>
        <pre><code>&lt;!DOCTYPE html &gt;</code></pre>
        <hr>
        <h2>Use nomes de elementos em letras minúsculas</h2>
        <p>HTML permite misturar letras maiúsculas e minúsculas nos nomes dos elementos.</p>
        <p>No entanto, recomendamos usar nomes de elementos em letras minúsculas porque:</p>
        <hr>
        <ul>
            <li>Misturar nomes maiúsculos e minúsculos parece ruim</li>
            <li>Os desenvolvedores normalmente usam nomes em minúsculas</li>
            <li>Letras minúsculas parecem mais limpas</li>
            <li>Letras minúsculas são mais fáceis de escrever</li>
        </ul>
        <hr>
        <h2>Fechar todos os elementos HTML</h2>
        <p>Em HTML, você não precisa fechar todos os elementos por exemplo, o elemento &lt;p&gt; .</p>
        <p>No entanto, recomendamos fortemente fechar todos os elementos HTML.</p>
        <h3>Use nomes de atributos em letras minúsculas</h3>
        <p>HTML permite misturar letras maiúsculas e minúsculas em nomes de atributos.</p>
        <p>No entanto, recomendamos usar nomes de atributos em letras minúsculas porque:</p>
        <hr>
        <ul>
            <li>Misturar nomes maiúsculos e minúsculos parece ruim</li>
            <li>Os desenvolvedores normalmente usam nomes em minúsculas</li>
            <li>Letras minúsculas parecem mais limpas</li>
            <li>Letras minúsculas são mais fáceis de escrever</li>



        </ul>
        <hr>
        <h3>Sempre citar valores de atributos</h3>
        <p>HTML permite valores de atributos sem aspas.</p>
        <p>No entanto, recomendamos citar valores de atributos porque:</p>
        <ul>
            <li>Os desenvolvedores normalmente citam valores de atributos</li>
            <li>Os valores citados são mais fáceis de ler</li>
            <li>Você DEVE usar aspas se o valor contiver espaços</li>

        </ul>
        <hr>

    </div>
    <div class="content">
        <h1>Entidades HTML</h1>
        <p>Caracteres reservados em HTML devem ser substituídos por entidades:

        </p>
        <hr>
        <ul>
            <li>&lt; (menor que) = &lt;</li>
            <li>&gt; (maior que) = &gt;</li>



        </ul>
        <hr>
        <h2>Entidades de caracteres HTML</h2>
        <p>Alguns caracteres são reservados em HTML.</p>
        <p>Se você usar os sinais de menor que &lt; ou maior que &gt; em seu texto HTML, o navegador poderá misturá-los
            com
            tags.</p>
        <p>Nomes ou números de entidades podem ser usados ​​para exibir caracteres HTML reservados.</p>
        <p>Os nomes das entidades são assim:</p>
        <hr>
        <p>&entity_name;</p>
        <hr>
        <h2>Espaço inquebrável</h2>
        <p>Uma entidade HTML comumente usada é o espaço inseparável: </p>
        <p>Um espaço ininterrupto é um espaço que não será dividido em uma nova linha.</p>
        <p>Duas palavras separadas por um espaço inseparável ficarão juntas (não serão divididas em uma nova linha).
            Isso é útil
            quando quebrar as palavras pode ser perturbador.</p>
        <p>Exemplos:</p>
        <ul>
            <li>§ 10
            </li>
            <li>10 km/h</li>
            <li>22h</li>
            <p>Outro uso comum do espaço ininterrupto é evitar que os navegadores trunquem espaços em páginas HTML.</p>
            <p>Se você escrever 10 espaços no seu texto, o navegador removerá 9 deles. Para adicionar espaços reais ao
                seu texto, você pode usar o entidade de personagem.</p>

        </ul>
    </div>
    <div class="content">
        <h1>Símbolos HTML</h1>
        <hr>
        <p>Símbolos ou letras que não estão presentes no teclado podem ser adicionados ao HTML usando entidades.</p>
        <h2>Entidades de símbolos HTML</h2>
        <p>As entidades HTML foram descritas no capítulo anterior.</p>
        <p>Muitos símbolos matemáticos, técnicos e monetários não estão presentes em um teclado normal.</p>
        <p>Para adicionar esses símbolos a uma página HTML, você pode usar o nome da entidade ou o número da entidade
            (uma referência decimal ou hexadecimal) para o símbolo:</p>
        <h3>Exemplo:</h3>
        <hr>
        <p>eu vou mostrar &euro;</p>
        <p>eu vou mostrar&#8364;</p>
        <p>eu vou mostrar &#x20AC;</p>
        <hr>
        <p><b>Sendo o codigo assim:</b></p>
        <hr>
        <pre><code>
    &lt;p&gt;Eu vou exibir &amp;euro;&lt;/p&gt;
    &lt;p&gt;Eu vou exibir &amp;#8364;&lt;/p&gt;
    &lt;p&gt;Eu vou exibir &amp;#x20AC;&lt;/p&gt;
    </code></pre>
        <hr>



    </div>
    <div class="content">
        <h1>Usando Emojis em HTML</h1>
        <p>Emojis são caracteres do conjunto de caracteres UTF-8: 😄 😍 💗

        </p>
        <h2>O que são emojis?</h2>
        <p>Emojis parecem imagens ou ícones, mas não são.

            São letras (caracteres) do conjunto de caracteres UTF-8 (Unicode).</p>
        <h2>O atributo HTML charset</h2>
        <p>Para exibir uma página HTML corretamente, um navegador da Web deve conhecer o conjunto de caracteres usado na
            página.</p>
        <p>Isso é especificado na <code>&lt;meta&gt;</code> tag :</p>
        <hr>
        <pre><code>
    &lt;meta charset="UTF-8"&gt;
    </code></pre>
        <hr>
        <h2>Caracteres UTF-8</h2>
        <p>Muitos caracteres UTF-8 não podem ser digitados em um teclado, mas sempre podem ser exibidos usando números
            (chamados de números de entidade):</p>
        <p>
        <ul>
            <li>A é 65</li>
            <li>B é 66</li>
            <li>C é 67</li>
        </ul>
        </p>
        <h2>Personagens emojis</h2>
        <p>Emojis também são caracteres do alfabeto UTF-8:</p>
        <ul>
            <li>😄 é 128516</li>
            <li>😍 é 128525</li>
            <li>💗 é 128151</li>

        </ul>

        <h3>Ficando assim :</h3>
        <hr>
        <pre><code>
    &lt;!DOCTYPE html&gt;
    &lt;html&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;body&gt;
    
    &lt;h1&gt;Meu Primeiro Emoji&lt;/h1&gt;
    
    &lt;p&gt;&amp;#128512;&lt;/p&gt;
    
    &lt;/body&gt;
    &lt;/html&gt;
    </code></pre>
        <hr>
    </div>
    <div class="content">
        <h1>Codificação HTML (conjuntos de caracteres)
        </h1>
        <hr>
        <p>Para exibir uma página HTML corretamente, um navegador da Web deve saber qual conjunto de caracteres usar.

        </p>
        <hr>
        <h2>O atributo HTML charset</h2>
        <p>O conjunto de caracteres é especificado na <code>&lt;meta&gt;</code>tag</p>
        <h3>Exemplo:</h3>
        <hr><code>&lt;meta charset"UTF-8"&gt;</code>
        <hr>
        <p>A especificação HTML5 incentiva os desenvolvedores web a usar o conjunto de caracteres UTF-8.</p>
        <p>UTF-8 cobre quase todos os caracteres e símbolos do mundo!</p>
        <h2>O conjunto de caracteres ASCII</h2>
        <p>ASCII foi o primeiro padrão de codificação de caracteres para a web. Definiu 128 caracteres diferentes que
            poderiam ser usados ​​na internet:</p>
        <ul>
            <li>Letras inglesas (AZ)</li>
            <li>Números (0-9)</li>
            <li>Caracteres especiais como ! $ + - ( ) @ &lt;,&gt;.</li>
        </ul>
        <hr>
        <h2>O conjunto de caracteres ANSI</h2>
        <p>ANSI (Windows-1252) era o conjunto de caracteres original do Windows:</p>
        <ul>
            <li>Idêntico ao ASCII para os primeiros 127 caracteres</li>
            <li>Caracteres especiais de 128 a 159</li>
            <li>Idêntico ao UTF-8 de 160 a 255</li>



        </ul>
        <h2>O conjunto de caracteres ISO-8859-1</h2>
        <p>ISO-8859-1 era o conjunto de caracteres padrão para HTML 4. Este conjunto de caracteres suportava 256 códigos
            de caracteres diferentes. HTML 4 também suporta UTF-8.</p>
        <hr>
        <ul>
            <li>Idêntico ao ASCII para os primeiros 127 caracteres</li>
            <li>Não usa os caracteres de 128 a 159</li>
            <li>Idêntico a ANSI e UTF-8 de 160 a 255</li>
            <h2>O conjunto de caracteres UTF-8</h2>
            <hr>
            <ul>
                <li>é idêntico ao ASCII para os valores de 0 a 127</li>
                <li>Não usa os caracteres de 128 a 159</li>
                <li>Idêntico ao ANSI e 8859-1 de 160 a 255</li>
                <li>Continua do valor 256 até 10.000 caracteres</li>

            </ul>

        </ul>





    </div>


    <div class="content">
        <h1>HTML Uniform Resource Locators
        </h1>
        <p>URL é outra palavra para endereço da web.</p>
        <p>Uma URL pode ser composta por palavras (por exemplo, w3schools.com) ou por um endereço de protocolo de
            Internet (IP) (por exemplo, 192.68.20.50).</p>
        <p>A maioria das pessoas insere o nome quando navega, porque os nomes são mais fáceis de lembrar do que os
            números.</p>
        <hr>
        <h2>URL - Localizador Uniforme de Recursos</h2>
        <p>Os navegadores da Web solicitam páginas de servidores da Web usando um URL.</p>
        <p>Um Uniform Resource Locator (URL) é usado para endereçar um documento (ou outros dados) na web.</p>
        <p>Um endereço da web como <b>https://www.google.com/html/default.asp </b>segue estas regras de sintaxe:</p>
        <code>scheme://prefix.domain:port/path/filename
</code>
        <p><b>Explicação:</b></p>
        <ul>
            <li>esquema - define o tipo de serviço de Internet (o mais comum é http ou https )</li>
            <li>prefixo - define um prefixo de domínio (o padrão para http é www )</li>
            <li>domínio - define o nome de domínio da Internet </li>
            <li>porta - define o número da porta no host o padrão para http é 80 </li>
            <li>path - define um caminho no servidor (se omitido: o diretório raiz do site)</li>
            <li>nome do arquivo - define o nome de um documento ou recurso</li>
            <hr>



        </ul>






    </div>
    <div class="content">
        <h1>Html x XHtml</h1>
        <hr>
        <p>XHTML é uma versão do HTML mais rígida e baseada em XML.</p>
        <hr>
        <h3>O que é XHTML?</h3>
        <ul>
            <li>XHTML significa E X tensible Hyper Text Markup Language</li>
            <li>XHTML é uma versão de HTML mais rígida e baseada em XML</li>
            <li>XHTML é HTML definido como um aplicativo XML</li>
            <li>XHTML é suportado por todos os principais navegadores</li>
        </ul>
        <h2>Por que XHTML?</h2>
        <p>XML é uma linguagem de marcação onde todos os documentos devem ser marcados corretamente (ser "bem
            formados").</p>
        <p>O XHTML foi desenvolvido para tornar o HTML mais extensível e flexível para trabalhar com outros formatos de
            dados (como XML). Além disso, os navegadores ignoram erros nas páginas HTML e tentam exibir o site mesmo que
            apresente alguns erros de marcação. Portanto, o XHTML vem com um tratamento de erros muito mais rígido.</p>
        <h3>As diferenças mais importantes do HTML</h3>
        <ul>
            <li><code>&lt;!DOCTYPE&gt;</code> é obrigatório</li>
            <li>O atributo xmlns em <CODE>&LT;html&gt;</CODE>é obrigatório</li>
            <li><code>&lt;html&gt;</code>, <code>&lt;head&gt;</code>,<code>&lt;title&gt;</code> e
                <code>&lt;body&gt;</code> são obrigatório</li>
            <li>Os elementos devem sempre estar adequadamente aninhados</li>
            <li>Os elementos devem estar sempre fechados</li>
            <li>Os elementos devem estar sempre em letras minúsculas</li>
            <li>Os nomes dos atributos devem estar sempre em letras minúsculas</li>
            <li>Os valores dos atributos devem sempre ser citados</li>
            <li>A minimização de atributos é proibida</li>


        </ul>



    </div>
    <div class="content">
        <h1>Formulários HTML</h1>
        <hr>
        <p>Um formulário HTML é usado para coletar a entrada do usuário. A entrada do usuário é geralmente enviada a um
            servidor para processamento.

        </p>
        <hr>
        <h2>O elemento &lt;form&gt;</h2>
        <p>O elemento HTML <code>&lt;form&gt;</code>é usado para criar um formulário HTML para entrada do usuário:</p>
        <p>O <code>&lt;form&gt;</code>é um contêiner para diferentes tipos de elementos de entrada, como: campos de
            texto, caixas de seleção, botões de opção, botões de envio, etc.</p>
        <p>Todos os diferentes elementos do formulário são abordados neste capítulo: Elementos do formulário HTML .

        </p>
        <h2>O elemento &lt;inpu&gt;</h2>
        <p>O elemento <code>&lt;input&gt;</code>é o elemento de formulário mais usado.</p>
        <p>Um <code>&lt;input&gt;</code>pode ser exibido de várias maneiras, dependendo do atributo
            <code>&lt;type&gt;</code>.</p>
        <h2>Campos de texto</h2>
        <p>Define <code>&lt;input type "text"&gt;</code>um campo de entrada de linha única para entrada de texto.</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>
    &lt;form&gt;
      &lt;label for="fname"&gt;Nome:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="fname" name="fname"&gt;&lt;br&gt;
      &lt;label for="lname"&gt;Sobrenome:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="lname" name="lname"&gt;
    &lt;/form&gt;
    </code></pre>
        <hr>
        <p><b>Ficando assim aplicado:</b></p>
        <form>
            <label for="fname">First name:</label><br>
            <input type="text" id="fname" name="fname"><br>
            <label for="lname">Last name:</label><br>
            <input type="text" id="lname" name="lname">
        </form>
        <hr>
        <h2>Botões do rádio</h2>
        <p>O <code>&lt;input type="radio"&gt;</code>define um botão de opção.</p>
        <p>Os botões de opção permitem que o usuário selecione UMA dentre um número limitado de opções.</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>
    &lt;p&gt;Escolha sua linguagem web favorita:&lt;/p&gt;
    
    &lt;form&gt;
      &lt;input type="radio" id="html" name="fav_language" value="HTML"&gt;
      &lt;label for="html"&gt;HTML&lt;/label&gt;&lt;br&gt;
      &lt;input type="radio" id="css" name="fav_language" value="CSS"&gt;
      &lt;label for="css"&gt;CSS&lt;/label&gt;&lt;br&gt;
      &lt;input type="radio" id="javascript" name="fav_language" value="JavaScript"&gt;
      &lt;label for="javascript"&gt;JavaScript&lt;/label&gt;
    &lt;/form&gt;
    </code></pre>
        <hr>
        <p><b>Ficando assim aplicado: </b></p>
        <p>Escolha sua linguagem web favorita:</p>

        <form>
            <input type="radio" id="html" name="fav_language" value="HTML">
            <label for="html">HTML</label><br>
            <input type="radio" id="css" name="fav_language" value="CSS">
            <label for="css">CSS</label><br>
            <input type="radio" id="javascript" name="fav_language" value="JavaScript">
            <label for="javascript">JavaScript</label>
        </form>
        <h2>Caixas de selção</h2>
        <p>O <code>&lt;input type ="checkbox"&gt;</code>define <b>uma caixa de seleção</b> .</p>
        <p>As caixas de seleção permitem que um usuário selecione ZERO ou MAIS opções de um número limitado de opções.
        </p>
        <h3>Exemplo:</h3>
        <pre><code>
    &lt;form&gt;
      &lt;input type="checkbox" id="vehicle1" name="vehicle1" value="Bike"&gt;
      &lt;label for="vehicle1"&gt; Eu tenho uma bicicleta&lt;/label&gt;&lt;br&gt;
      &lt;input type="checkbox" id="vehicle2" name="vehicle2" value="Car"&gt;
      &lt;label for="vehicle2"&gt; Eu tenho um carro&lt;/label&gt;&lt;br&gt;
      &lt;input type="checkbox" id="vehicle3" name="vehicle3" value="Boat"&gt;
      &lt;label for="vehicle3"&gt; Eu tenho um barco&lt;/label&gt;
    &lt;/form&gt;
    </code></pre>
        <p><b>Ficando assim aplicado:</b></p>
        <form>
            <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
            <label for="vehicle1"> Eu tenho uma bicicleta</label><br>
            <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
            <label for="vehicle2"> Eu tenho um carro</label><br>
            <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
            <label for="vehicle3"> Eu tenho um barco</label>
        </form>
        <h1>Atributos do formulário HTML</h1>
        <p>Este capítulo descreve os diferentes atributos do <code>&lt;form&gt;</code>elemento HTML.</p>
        <h2>O atributo de ação</h2>
        <p>O <code>action</code> define a ação a ser executada quando o formulário for enviado.</p>
        <p>Normalmente, os dados do formulário são enviados para um arquivo no servidor quando o usuário clica no botão
            enviar.</p>
        <p>No exemplo abaixo, os dados do formulário são enviados para um arquivo chamado “action_page.php”. Este
            arquivo contém um script do lado do servidor que trata os dados do formulário:</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>
    &lt;form action="/action_page.php"&gt;
      &lt;label for="fname"&gt;Nome:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="fname" name="fname" value="João"&gt;&lt;br&gt;
      &lt;label for="lname"&gt;Sobrenome:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="lname" name="lname" value="Silva"&gt;&lt;br&gt;&lt;br&gt;
      &lt;input type="submit" value="Enviar"&gt;
    &lt;/form&gt;
    </code></pre>
        <hr>
        <form action="/action_page.php">
            <label for="fname">First name:</label><br>
            <input type="text" id="fname" name="fname" value="John"><br>
            <label for="lname">Last name:</label><br>
            <input type="text" id="lname" name="lname" value="Doe"><br><br>
            <input type="submit" value="Submit">
        </form>
        <hr>
        <h2>O atributo alvo</h2>
        <p>O atributo <code>target</code> especifica onde exibir a resposta recebida após o envio do formulário.</p>
        <hr>
        <h2>O Atributo Método</h2>
        <p>O <code>method</code>atributo especifica o método HTTP a ser usado ao enviar os dados do formulário.</p>
        <p>Os dados do formulário podem ser enviados como variáveis ​​​​de URL com <code>method="get"</code>ou como
            pós-transação HTTP com <code>method="post"</code> </p>
        <p>O método HTTP padrão ao enviar dados de formulário é GET. </p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>
        &lt;form action="/action_page.php" method="get"&gt;
          &lt;label for="fname"&gt;Nome:&lt;/label&gt;&lt;br&gt;
          &lt;input type="text" id="fname" name="fname" value="João"&gt;&lt;br&gt;
          &lt;label for="lname"&gt;Sobrenome:&lt;/label&gt;&lt;br&gt;
          &lt;input type="text" id="lname" name="lname" value="Silva"&gt;&lt;br&gt;&lt;br&gt;
          &lt;input type="submit" value="Enviar"&gt;
        &lt;/form&gt;
        </code></pre>
        <hr>
        <p><b>Ficando assim:</b></p>
        <h2>The method Attribute</h2>

        <p>Este formulario usa o metodo GET</p>

        <form action="/action_page.php" target="_blank" method="get">
            <label for="fname">Primeiro nome:</label><br>
            <input type="text" id="fname" name="fname" value="John"><br>
            <label for="lname">Ultimo nome:</label><br>
            <input type="text" id="lname" name="lname" value="Doe"><br><br>
            <input type="submit" value="Submit">
        </form>

        <p>Depois de enviar aparecerá na barra de pesquisa</p>
        <hr>
        <h2>O atributo de preenchimento automático</h2>
        <p>O atributo <code>autocomplete</code> especifica se um formulário deve ter o preenchimento automático ativado
            ou desativado.</p>
        <p>Quando o preenchimento automático está ativado, o navegador completa automaticamente os valores com base nos
            valores inseridos anteriormente pelo usuário.</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>
    &lt;form action="/action_page.php" autocomplete="on"&gt;
      &lt;label for="fname"&gt;Primeiro nome:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="fname" name="fname" value="João"&gt;&lt;br&gt;
      &lt;label for="lname"&gt;Sobrenome:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="lname" name="lname" value="Silva"&gt;&lt;br&gt;&lt;br&gt;
      &lt;input type="submit" value="Enviar"&gt;
    &lt;/form&gt;
    </code></pre>
        <hr>
        <p></p>
        <h2>Elementos de formulário HTML</h2>
        <p>Este capítulo descreve todos os diferentes elementos do formulário HTML.

        </p>
        <h2>Os elementos HTML &lt;form&gt;</h2>
        <p>O elemento html <code>&lt;form&gt;</code>pode conter um ou mais dos seguintes elementos de formulário:</p>
        <ul>
            <li><code>&lt;input&gt;</code></li>
            <li><code>&lt;label&gt;</code></li>
            <li><code>&lt;select&gt;</code></li>
            <li><code>&lt;textarea&gt;</code></li>
            <li><code>&lt;button&gt;</code></li>
            <li><code>&lt;fieldset&gt;</code></li>
            <li><code>&lt;legend&gt;</code></li>
            <li><code>&lt;datalist&gt;</code></li>
            <li><code>&lt;output&gt;</code></li>
            <li><code>&lt;option&gt;</code></li>
            <li><code>&lt;optgropu&gt;</code></li>

        </ul>
        <h2>O elemento <code>&lt;input&gt;</code></h2>
        <p>Um dos elementos de formulário mais utilizados é o <code>&lt;input&gt;</code></p>
        <p>O Elemento<code>&lt;input&gt;</code>pode ser exibido de diversas maneiras, dependendo do typeatributo.</p>
        <h3>Exemplo:</h3>
        <pre><code>
        &lt;label for="fname"&gt;Nome:&lt;/label&gt;
        &lt;input type="text" id="fname" name="fname"&gt;
        </code></pre>
        <hr>

        <p>Todos os diferentes valores do <code>type</code>atributo são abordados no próximo capítulo: Tipos de entrada
            HTML .

        </p>
        <h2>O elemento <code>&lt;label&gt;</code></h2>
        <p>O <code>&lt;label&gt;</code>define um rótulo para vários elementos do formulário.</p>
        <p>O <code>&lt;label&gt;</code>é útil para usuários de leitores de tela, porque o leitor de tela lerá o rótulo
            em voz alta quando o usuário focar no elemento de entrada.</p>
        <p>O elemento <code>&lt;label&gt;</code>é útil para usuários de leitores de tela, porque o leitor de tela lerá o
            rótulo em voz alta quando o usuário focar no elemento de entrada.</p>
        <p>O elemento <code>&lt;label&gt;</code>também ajuda usuários que têm dificuldade em clicar em regiões muito
            pequenas (como botões de opção ou caixas de seleção) - porque quando o usuário clica no texto dentro do
            <code>&lt;label&gt;</code>, ele alterna o botão de opção/caixa de seleção.</p>
        <p>O <code>for</code> atributo da <code>&lt;label&gt;</code>tag deve ser igual ao idatributo do
            <code>&lt;input&gt;</code>elemento para uni-los.</p>
        <h2>O elemento <code>&lt;select&gt;</code></h2>
        <p>O <code>&lt;select&gt;</code>elemento define uma lista suspensa:</p>
        <h3>Exemplo:</h3>
        <hr>
        <pre><code>
            &lt;label for="cars"&gt;Escolha um carro:&lt;/label&gt;
            &lt;select id="cars" name="cars"&gt;
              &lt;option value="volvo"&gt;Volvo&lt;/option&gt;
              &lt;option value="saab"&gt;Saab&lt;/option&gt;
              &lt;option value="fiat"&gt;Fiat&lt;/option&gt;
              &lt;option value="audi"&gt;Audi&lt;/option&gt;
            &lt;/select&gt;
            </code></pre>
        <hr>
        <p><b>Ficando assim:</b></p>
        <hr>
        <h2>Selecione o elemento</h2>

        <p>O elemento selecionado define uma lista drop down</p>

        <form action="/action_page.php">
            <label for="cars">Escolha seu carro:</label>
            <select id="cars" name="cars">
                <option value="volvo">Volvo</option>
                <option value="saab">Saab</option>
                <option value="fiat">Fiat</option>
                <option value="audi">Audi</option>
            </select>
            <input type="submit">
            <h2>O elemento <code>&lt;button&gt;</code></h2>
            <p>O <code>&lt;button&gt;</code> define um botao clicável</p>
            <h3>Exemplo:</h3>
            <hr>
            <pre><code>
    &lt;h2&gt;O Elemento Botão&lt;/h2&gt;
    
    &lt;button type="button" onclick="alert('Olá Mundo!')"&gt;Clique em Mim!&lt;/button&gt;
    </code></pre>
            <hr>
            <p><b>Ficando assim:</b></p>


            <h2>Elemento botão</h2>

            <button type="button" onclick="alert('Hello World!')">Click Me!</button>
            <hr>
            <h1>Tipos de entrada HTML</h1>
            <p>Este capítulo descreve os diferentes tipos de elemento HTML <code>&lt;input&gt;</code>.</p>
            <h2>Tipos de entrada HTML</h2>
            <ul>
                <li>&lt;input type="button"&gt;</li>
                <li>&lt;input type="checkbox"&gt;</li>
                <li>&lt;input type="color"&gt;</li>
                <li>&lt;input type="date"&gt;</li>
                <li>&lt;input type="datetime-local"&gt;</li>
                <li>&lt;input type="email"&gt;</li>

            </ul>
            <hr>
            <h1>Texto do tipo <code>&lt;input&gt;</code></h1>
            <p><code>&lt;input type="text"&gt;</code>define um <b>campo de entrada de texto de linha unica </b></p>
            <hr>
            <h1>Senha do tipo de entrada</h1>
            <p><code>&lt;input type="password"&gt;</code>define um <b>campo de Senha</b></p>
            <h3>Exemplo:</h3>
            <hr>
            <pre><code>
    &lt;form&gt;
      &lt;label for="username"&gt;Username:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="username" name="username"&gt;&lt;br&gt;
      &lt;label for="pwd"&gt;Password:&lt;/label&gt;&lt;br&gt;
      &lt;input type="password" id="pwd" name="pwd"&gt;
    &lt;/form&gt;
    </code></pre>
            <hr>
            <p><b>Ficando assim:</b></p>
            <form>
                <label for="username">Username:</label><br>
                <input type="text" id="username" name="username"><br>
                <label for="pwd">Password:</label><br>
                <input type="password" id="pwd" name="pwd">
            </form>
            <hr>
            <h1>Enviar tipo de entrada</h1>
            <p><code>&lt;input type="submit"&gt;</code>define um botão para enviar dados do formulário para um
                manipulador de formulários .</p>
            <p>O manipulador de formulário normalmente é uma página de servidor com um script para processar dados de
                entrada.</p>
            <p>O manipulador de formulário é especificado no <code> action</code> atributo do formulário:</p>
            <h3>Exemplo:</h3>
            <hr>
            <pre><code>
    &lt;form action="/action_page.php"&gt;
      &lt;label for="fname"&gt;First name:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="fname" name="fname" value="John"&gt;&lt;br&gt;
      &lt;label for="lname"&gt;Last name:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="lname" name="lname" value="Doe"&gt;&lt;br&gt;&lt;br&gt;
      &lt;input type="submit" value="Submit"&gt;
    &lt;/form&gt;
    </code></pre>
            <hr>
            <h1>Redefinição do tipo de entrada</h1>
            <p><code>&lt;input type = "reset"&gt;</code>define um botão de redefinição que redefinirá todos os valores
                do formulário para seus valores padrão:</p>
            <hr>
            <pre><code>
    &lt;form action="/action_page.php"&gt;
      &lt;label for="fname"&gt;First name:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="fname" name="fname" value="John"&gt;&lt;br&gt;
      &lt;label for="lname"&gt;Last name:&lt;/label&gt;&lt;br&gt;
      &lt;input type="text" id="lname" name="lname" value="Doe"&gt;&lt;br&gt;&lt;br&gt;
      &lt;input type="submit" value="Submit"&gt;
      &lt;input type="reset" value="Reset"&gt;
    &lt;/form&gt;
    </code></pre>
            <hr>
            <p><b>Ficando assim:</b></p>
            <form action="/action_page.php">
                <label for="fname">Nome:</label><br>
                <input type="text" id="fname" name="fname" value="John"><br>
                <label for="lname">Sobrenome:</label><br>
                <input type="text" id="lname" name="lname" value="Doe"><br><br>
                <input type="submit" value="Submit">
                <input type="reset" value="Reset">
            </form>
            <hr>
            <h1>Tipo de entrada Rádio</h1>
            <p><code>&lt;input type="radio"&gt;</code>define um botão de opção .</p>
            <p>Os botões de opção permitem que um usuário selecione APENAS UMA dentre um número limitado de opções:</p>
            <h3>Exemplo:</h3>
            <hr>
            <pre><code>
    &lt;p&gt;Choose your favorite Web language:&lt;/p&gt;
    
    &lt;form&gt;
      &lt;input type="radio" id="html" name="fav_language" value="HTML"&gt;
      &lt;label for="html"&gt;HTML&lt;/label&gt;&lt;br&gt;
      &lt;input type="radio" id="css" name="fav_language" value="CSS"&gt;
      &lt;label for="css"&gt;CSS&lt;/label&gt;&lt;br&gt;
      &lt;input type="radio" id="javascript" name="fav_language" value="JavaScript"&gt;
      &lt;label for="javascript"&gt;JavaScript&lt;/label&gt;
    &lt;/form&gt;
    </code></pre>
            <hr>
            <p><b>Ficando assim:</b></p>
            <p>Choose your favorite Web language:</p>

            <form>
                <input type="radio" id="html" name="fav_language" value="HTML">
                <label for="html">HTML</label><br>
                <input type="radio" id="css" name="fav_language" value="CSS">
                <label for="css">CSS</label><br>
                <input type="radio" id="javascript" name="fav_language" value="JavaScript">
                <label for="javascript">JavaScript</label>
            </form>
            <hr>
            <h1>Caixa de seleção de tipo de entrada</h1>
            <p><code>&lt;input type="checkbox"&gt;</code>define uma caixa de seleção .</p>
            <p>As caixas de seleção permitem que um usuário selecione ZERO ou MAIS opções de um número limitado de
                opções.</p>
            <h3>Exemplo:</h3>
            <hr>
            <pre><code>
    &lt;form&gt;
      &lt;input type="checkbox" id="vehicle1" name="vehicle1" value="Bike"&gt;
      &lt;label for="vehicle1"&gt; I have a bike&lt;/label&gt;&lt;br&gt;
      &lt;input type="checkbox" id="vehicle2" name="vehicle2" value="Car"&gt;
      &lt;label for="vehicle2"&gt; I have a car&lt;/label&gt;&lt;br&gt;
      &lt;input type="checkbox" id="vehicle3" name="vehicle3" value="Boat"&gt;
      &lt;label for="vehicle3"&gt; I have a boat&lt;/label&gt;
    &lt;/form&gt;
    </code></pre>
            <hr>
            <p><b>Ficando assim:</b></p>
            <form>
                <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
                <label for="vehicle1"> I have a bike</label><br>
                <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
                <label for="vehicle2"> I have a car</label><br>
                <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
                <label for="vehicle3"> I have a boat</label>
            </form>
            <hr>
            <h1>Botão de tipo de entrada</h1>
            <p><code>&lt;input type = "button"&gt;</code> Define um botão:</p>
            <hr>
            <pre><code>
    &lt;input type="button" onclick="alert('Hello World!')" value="Click Me!"&gt;
    </code></pre>
            <hr>
            <p><b>Ficando assim:</b></p>
            <input type="button" onclick="alert('Hello World!')" value="Click Me!">
            <hr>
            <h1>Data do tipo de entrada</h1>
            <p>O <code>&lt;input type = "date"&gt;</code>é usado para campos de entrada que devem conter uma data.</p>
            <p>Dependendo do suporte do navegador, um seletor de data pode aparecer no campo de entrada.</p>
            <h3>Exemplo:</h3>
            <hr>
            <pre><code>
    &lt;form&gt;
      &lt;label for="birthday"&gt;Birthday:&lt;/label&gt;
      &lt;input type="date" id="birthday" name="birthday"&gt;
    &lt;/form&gt;
    </code></pre>
            <hr>
            <p><b>Ficando assim:</b></p>
            <form>
                <label for="birthday">Birthday:</label>
                <input type="date" id="birthday" name="birthday">
            </form>
            <hr>

            <h1>Tipo de entrada Datahora-local</h1>
            <p>Especifica <code>&lt;input type="datetime-local"&gt;</code>um campo de entrada de data e hora, sem fuso
                horário.</p>
            <p>Dependendo do suporte do navegador, um seletor de data pode aparecer no campo de entrada.</p>
            <h3>Exemplo:</h3>
            <hr>
            <pre><code>
    &lt;form&gt;
      &lt;label for="birthdaytime"&gt;Birthday (date and time):&lt;/label&gt;
      &lt;input type="datetime-local" id="birthdaytime" name="birthdaytime"&gt;
    &lt;/form&gt;
    </code></pre>
            <hr>
            <p><b>Ficando assim:</b></p>
            <form>
                <label for="birthdaytime">Birthday (date and time):</label>
                <input type="datetime-local" id="birthdaytime" name="birthdaytime">
            </form>
            <hr>
            <h1>E-mail do tipo de entrada</h1>
            <p>O <code>&lt;input type="email"&gt;</code>é usado para campos de entrada que devem conter um endereço de
                e-mail.
            </p>
            <p>Dependendo do suporte do navegador, o endereço de e-mail pode ser validado automaticamente quando
                enviado.</p>
            <p>Alguns smartphones reconhecem o tipo de e-mail e adicionam “.com” ao teclado para corresponder à entrada
                do e-mail.</p>
            <hr>
            <h3>Exemplo:</h3>
            <hr>
            <pre><code>
    &lt;form&gt;
      &lt;label for="email"&gt;Enter your email:&lt;/label&gt;
      &lt;input type="email" id="email" name="email"&gt;
    &lt;/form&gt;
    </code></pre>
            <hr>
            <p><b>Ficando assim:</b></p>
            <form>
                <label for="email">Enter your email:</label>
                <input type="email" id="email" name="email">
            </form>

    </div>
    <div class="content">

        <h1>HTML Canvas Graphics</h1>
        <p>O elemento HTML <code>&lt;canvas&gt;</code>é usado para desenhar gráficos em uma página da web.</p>
        <hr>
        <h2>O que é um elemento canvas em html?</h2>
        <p>O elemento HTML <code>&lt;canvas&gt;</code>é usado para desenhar gráficos dinamicamente, via JavaScript</p>
        <p>O <code>&lt;canvas&gt;</code> apenas um contêiner para gráficos. Você deve usar JavaScript para realmente
            desenhar os gráficos.</p>
        <p>O Canvas possui vários métodos para desenhar caminhos, caixas, círculos, texto e adicionar imagens.</p>
        <p>Canvas é compatível com todos os principais navegadores.

        </p>
        <h3>Exemplo:</h3>
        <canvas id="myCanvas" width="200" height="100" style="border:1px solid #d3d3d3;">
            Your browser does not support the HTML canvas tag.</canvas>

        <script>
            var c = document.getElementById("myCanvas");
            var ctx = c.getContext("2d");
            ctx.beginPath();
            ctx.arc(95, 50, 40, 0, 2 * Math.PI);
            ctx.stroke();
        </script>
        <hr>
        <P><b>Sendo assim o codigo:</b></P>
        <pre><code>
        &lt;canvas id="myCanvas" width="200" height="100" style="border:1px solid #d3d3d3;"&gt;
        Your browser does not support the HTML canvas tag.
        &lt;/canvas&gt;
        
        &lt;script&gt;
        var c = document.getElementById("myCanvas");
        var ctx = c.getContext("2d");
        ctx.beginPath();
        ctx.arc(95,50,40,0,2*Math.PI);
        ctx.stroke();
        &lt;/script&gt;
        </code></pre>
        <hr>
    </div>
    <div class="content">
        <h1>HTML SVG Graphics</h1>
        <p>SVG define gráficos baseados em vetores em XML , que podem ser incorporados diretamente em páginas HTML.</p>
        <p>Os gráficos SVG são escaláveis ​​e não perdem qualidade se forem ampliados ou redimensionados:</p>
        <p>SVG é compatível com todos os principais navegadores.</p>
        <p>O que é SVG?</p>
        <ul>
            <li>SVG significa gráficos vetoriais escaláveis</li>
            <li>SVG é usado para definir gráficos baseados em vetores para a Web</li>
            <li>SVG define gráficos em formato XML</li>
            <li>Cada elemento e atributo em arquivos SVG pode ser animado</li>
            <li>SVG é uma recomendação do W3C</li>
            <li>SVG integra-se com outros padrões, como CSS, DOM, XSL e JavaScript</li>

        </ul>
        <h2>O elemento &lt;svg&gt;</h2>
        <p>O elemento HTML <code>&lt;svg&gt;</code>é um contêiner para gráficos SVG.</p>
        <p>SVG possui vários métodos para desenhar caminhos, retângulos, círculos, polígonos, texto e muito mais.</p>
        <hr>
        <h3>Exemplo:</h3>
        <svg width="300" height="200">
            <polygon points="100,10 40,198 190,78 10,78 160,198"
                style="fill:lime;stroke:purple;stroke-width:5;fill-rule:evenodd;" />
            Sorry, your browser does not support inline SVG.
        </svg>
        <hr>
        <p><b>Sendo assim o codigo:</b></p>
        <pre><code>
    &lt;svg width="300" height="200"&gt;
      &lt;polygon points="100,10 40,198 190,78 10,78 160,198"
      style="fill:lime;stroke:purple;stroke-width:5;fill-rule:evenodd;" /&gt;
    Sorry, your browser does not support inline SVG.
    &lt;/svg&gt;
    </code></pre>
        <hr>
    </div>
    <div class="content">
        <h1>Midia html</h1>
        <p>Multimídia na web é som, música, vídeos, filmes e animações.</p>
        <h2>O que é multimídia?</h2>
        <p>A multimídia vem em muitos formatos diferentes. Pode ser quase tudo que você pode ouvir ou ver, como imagens,
            músicas, sons, vídeos, discos, filmes, animações e muito mais.</p>
        <p>As páginas da Web geralmente contêm elementos multimídia de diferentes tipos e formatos.</p>
        <h2>Suporte ao navegador</h2>
        <p>Os primeiros navegadores tinham suporte apenas para texto, limitado a uma única fonte em uma única cor.</p>
        <p>Mais tarde vieram os navegadores com suporte para cores, fontes, imagens e multimídia!</p>
        <h2>Formatos multimídia</h2>
        <p>lementos multimídia (como áudio ou vídeo) são armazenados em arquivos de mídia.</p>
        <p>A maneira mais comum de descobrir o tipo de um arquivo é observar a extensão do arquivo.</p>
        <p>Os arquivos multimídia possuem formatos e extensões diferentes como: .wav, .mp3, .mp4, .mpg, .wmv e .avi.</p>

    </div>
    <div class="content">
        <h1>Vídeo HTML</h1>
        <p>O elemento HTML <code>&lt;video&gt;</code>é usado para mostrar um vídeo em uma página da web.</p>
        <h3>Exemplo:</h3>
        <video width="400" controls>
            <source src="mov_bbb.mp4" type="video/mp4">
            <source src="mov_bbb.ogg" type="video/ogg">
            Your browser does not support HTML video.
        </video>
        <hr>
        <p><b>Sendo assim o codigo:</b></p>
        <pre><code>
    &lt;video width="400" controls&gt;
      &lt;source src="mov_bbb.mp4" type="video/mp4"&gt;
      &lt;source src="mov_bbb.ogg" type="video/ogg"&gt;
      Your browser does not support HTML video.
    &lt;/video&gt;
    </code></pre>
        <hr>
        <h1>Áudio HTML</h1>
        <p>O elemento HTML <code>&lt;audio&gt;</code>é usado para reproduzir um arquivo de áudio em uma página da web.
        </p>
        <hr>
        <h2>O elemento HTML &lt;audio&gt;</h2>
        <p>Para reproduzir um arquivo de áudio em HTML, use o elemento <code>&lt;audio&gt;</code></p>
        <h3>Exemplo:</h3>
        <hr>
        <audio controls>
            <source src="horse.ogg" type="audio/ogg">
            <source src="horse.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        <hr>
        <p><b>Sendo assim o codigo:</b></p>
        <pre><code>
    &lt;audio controls&gt;
      &lt;source src="horse.ogg" type="audio/ogg"&gt;
      &lt;source src="horse.mp3" type="audio/mpeg"&gt;
    Your browser does not support the audio element.
    &lt;/audio&gt;
    </code></pre>
        <hr>
        <h2>Áudio HTML - Como funciona</h2>
        <p>O elemento <code>controls</code> adiciona controles de áudio, como reproduzir, pausar e volume.</p>
        <p>O elemento <code>&lt;source&gt;</code> permite que você especifique arquivos de áudio alternativos que o
            navegador pode escolher. O navegador usará o primeiro formato reconhecido.</p>
        <p>O texto entre as tags <code>&lt;audio&gt;</code>e <code>&lt;/audio&gt;</code>só será exibido em navegadores
            que não suportam o elemento <code>7lt
        audio&gt;
    </code></p>





    </div>
    <div class="content">

        <h1>API de arrastar e soltar HTML</h1>
        <hr>
        <p>Em HTML, qualquer elemento pode ser arrastado e solto.</p>
        <hr>
        <h2>Arrastar e soltar</h2>
        <p>Arrastar e soltar é um recurso muito comum. É quando você “pega” um objeto e o arrasta para um local
            diferente.</p>
        <h3>Exemplo de arrastar e soltar:</h3>
        <p>O exemplo abaixo é um exemplo simples de arrastar e soltar:</p>
        <script>
            function allowDrop(ev) {
                ev.preventDefault();
            }

            function drag(ev) {
                ev.dataTransfer.setData("text", ev.target.id);
            }

            function drop(ev) {
                ev.preventDefault();
                var data = ev.dataTransfer.getData("text");
                ev.target.appendChild(document.getElementById(data));
            }
        </script>
        </head>

        <body>

            <p>Drag the W3Schools image into the rectangle:</p>

            <div id="Roberto" ondrop="drop(event)" ondragover="allowDrop(event)"></div>
            <br>
            <img id="drag1" src="img_logo.gif" draggable="true" ondragstart="drag(event)" width="336" height="69">
            <hr>
            <p><b>Sendo assim o codigo:</b></p>
            <pre><code>
        &lt;style&gt;
        #div1 {
          width: 350px;
          height: 70px;
          padding: 10px;
          border: 1px solid #aaaaaa;
        }
        &lt;/style&gt;
        &lt;script&gt;
        function allowDrop(ev) {
          ev.preventDefault();
        }
        
        function drag(ev) {
          ev.dataTransfer.setData("text", ev.target.id);
        }
        
        function drop(ev) {
          ev.preventDefault();
          var data = ev.dataTransfer.getData("text");
          ev.target.appendChild(document.getElementById(data));
        }
        &lt;/script&gt;
        &lt;p&gt;Drag the W3Schools image into the rectangle:&lt;/p&gt;
        &lt;div id="div1" ondrop="drop(event)" ondragover="allowDrop(event)"&gt;&lt;/div&gt;
        &lt;br&gt;
        &lt;img id="drag1" src="img_logo.gif" draggable="true" ondragstart="drag(event)" width="336" height
        
<hr>
Pode parecer complicado, mas vamos examinar todas as diferentes partes de um evento de arrastar e soltar.

<h3>Tornar um elemento arrastável</h3>
<p>Primeiro de tudo: para tornar um elemento arrastável, defina o draggablea tributo como verdadeiro:</p>
<p><span class="exemplo"> <code>&lt;img draggable= "true"&gt;</code></span></p>
<h2>O que arrastar - ondragstart e setData()</h2>
<p>Em seguida, especifique o que deve acontecer quando o elemento for arrastado.</p>
<p>No exemplo acima, o <code> ondragstart</code> atributo chama uma função, drag(event), que especifica quais dados
    serão arrastados.</p>
<p>O <code>dataTransfer.setData()</code>método define o tipo de dados e o valor dos dados arrastados:</p>
<pre><code>
    &lt;script&gt;
    function drag(ev) {
      ev.dataTransfer.setData("text", ev.target.id);
    }
    &lt;/script&gt;
    </code></pre>
<p>Neste caso, o tipo de dados é “texto” e o valor é o id do elemento arrastável (“arrastar1”).</p>
<hr>
<h2>Onde largar - ondragover</h2>
<p>O <code>ondragover</code> evento especifica onde os dados arrastados podem ser descartados.</p>

<p>Por padrão, dados/elementos não podem ser descartados em outros elementos. Para permitir uma queda,
    devemos evitar o tratamento padrão do elemento.</p>
<p>sso é feito chamando o método event.preventDefault() do evento ondragover:</p>
<p><code>event.preventDefault() </code></p>
<h2>Faça o Drop - ondrop</h2>
    <p>Quando os dados arrastados são descartados, ocorre um evento de descarte.</p>
    <p>No exemplo acima, o atributo ondrop chama uma função, drop(event).</p>


    </div>

</body>

</html>
\```

