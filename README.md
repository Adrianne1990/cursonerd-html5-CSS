# cursonerd-html5-CSS
# cursonerd-html5-CSS

<br>

## Aula 10 - Tags Header, Footer, Nav, Section, Main, Div

Nesta aula vamos trabalhar com as tags...

<br>

### 1) body

Representa o conteúdo de um documento HTML.

- É permitido apenas um '<body>' por documento.

Exemplo:

'''html
<body>
   <!-- conteúdo do meu documento -->
</body>
'''

<br>

### 2) header (cabeçalho)

Representa um grupo de suporte introdutório ou navegacional.
- Pode conter alguns elementos de cabeçalho como logo, título, navegação, campo de busca, etc.

Exemplo:

'''html
<header>
  <h1>Curso Html e Css3 - 2022</h1>
</header>
'''

<br>

### 3) footer (rodapé)

Representa um rodapé para sua seção de conteúdo.
- Normalmente um rodapé contém informações sobre o autor do documento;

Exemplo:

'''html
<footer>
  <p>Copyright ₢ 2022. Desenvolvido por Adrianne.</p>
</footer>
'''

<br>

### 4) nav

Representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação.

-nem todos os links de um documento devem estar dentro de um elemento <nav>, o qual é destinado apenas para grupos importantes de links de navegação.

-um documento pode ter vários elementos <nav>, por exemplo, um para navegação no site e outro paranavegação dentro da página.

-normalmente o elemento <footer> contém uma lista de links que não precisam estar em uma <nav>.
section: representa uma seção genérica contida em um documento HTML.

Exemplo:

<nav>
  <ul>
    <li><a href="#">Sobre nós</a></li>
    <li><a href="#">Serviço</a></li>
    <li><a href="#">Contato</a></li>
  </ul>
</nav>

### 5) section

Representa uma seção genérica contida em um documento HTML

-cada <section> deve ser identificado, geralmente incluindo um elemento de cabeçalho <h1>,<h2>...<h6>

Exemplo:

<section>
  <h1>Curso de Html5 e Css3 - 2020</h2>
  <p>Neste curso vamos aprender muita coisa juntos e desenvolver projetos bem legais.</p>
</section>

### 6) main

 O elemento <main> define o coteúdo principal dentro do <body> em seu documento ou aplicação.

-Deve ser único na página, ou seja, apenas um <main> por documento;

-Dentro do elemento <main> não deverão ser incluidas seções da página que sejam comuns a todo site ou aplicação, tais como mecanismo de navegação, informações de copyright, logotipo e campos de busca (a não ser, é claro, caso a função principal do documento seja fazer algum tipo de busca).

Exemplo:
<main>
  <h1>Curso html5 e Css3 - 2022</h1>
  <p>Neste curso vamos aprender muita muita coisa juntos e desenvolver projetos bem legais.</p>

  <section>
    <h2>Sobre o html5</h2>
    <p>Linguagem utilizada para marcar os nossos documentos html.</p>
  </section>

  <section>
    <h2>Sobre o Css3</h2>
    <p>Linguagem utilizada para estilizar os nossos documentos html.</p>
  </section>
</main>


### 7) div

O elemento de divisão HTML <div> é um container genérico para conteúdo, que de certa forma não representa nada.
Ele pode ser utilizado para agrupar elementos para fins de estilos (usando 'class' ou 'id').

Exemplo:

<div>
  <p>Um conteúdo qualquer.......</p>
</div>
