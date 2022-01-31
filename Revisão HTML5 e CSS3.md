## REVISÃO DO CURSO DE INTRODUÇÃO A CRIAÇÃO DE WEBSITES COM HTML5 E CSS3


### HTML 5

* O primeiro tópico abordado foi em relação ao uso do HTML5 para a criação de páginas web, essa ferramenta possibilita a criação de páginas estáticas porém com o uso de uma nova semantica, diferente das versões anteriores onde se utilizava apenas a tag <div>. Nesse formato criado em 2014 foram adicionados várias tags com a intenção de melhorar a divisão e entendimento do código escrito, evitando dificuldades com inumeras tags repetidas, como era o caso das divs. cabe lembrar que o HTML é o responsávél por dar forma a estrutura da página, tendo assim uma formatação padrão, sem mudança de estilos, porém pode ser inserido textos, imagens, links, videos e demais conteúdos, deixando o trabalho de estilo com o CSS.

* A estrutura básica do html5 é formada da seguinte maneira:

<<!DOCTYPE html>>                      || Código utilizado para indicar o uso do HTML5
<html>                                 || Tag que simboliza a abertura do código HTML  
<header>                               || Tag para abertura do cabeçalho 

* Nele deverá ser adicionado as funcionalidades iniciais da página para a interpretação do navegador, como por exemplo a logo que aparecerá na aba do site ou o nome da página, além dos links a outros arquivos como as folhas de estilos e scripts;
* A tag header poderá ser utilizada em outros containers também como no body, section, article, footer e outros, dessa forma o mesmo não se limita apenas a cabeçalho principal do html.

</header>                              || Tag para fechamento do cabeçalho

<body>                                 || Tag para abertura do corpo

* Neste container é onde efetivamente esta a estrutura do corpo da página, contendo as section, article,headers e footer, além de outras funcionalidades

</body>                                || Tag para fechamento do corpo


</html>                                || Tag que simboliza o fechamento do código HTML


### CSS3

* Já o CSS é o responsávél por deixar a página mais bonita e amigavél através do uso de estilos, é com ele que podemos inserir cores, bordas e alinhamnetos entre outras possiveis alterações para tornar a página mais bonita. Para executar o cógo css, poder ser feito diretamente na estrutura HTML como um atributo a uma tag, ou pode ser criado um arquivo externo contendo toda a folha de estilo de cada tag como o desenvolvedor preferir.

segue abaixo um exemplo de código css:

#cabecalho_principal {                                       
    background-color: rgb(50, 126, 189);
    border-bottom: 10px solid rgb(5, 46, 100) ;
}

.imagens{
    border: 2px solid black;
    margin: 5px;
}

* Os primeiro exemplo de código altera as propriedades do backgroud e da borda inferior da tag com id cabecalho _principal, já o segundo altera as propriedades da borda e margem da classe imagens.

* Com essas duas ferramentas já é possivél criar páginas estáticas completas, todavia para uma maior interatividade será necessário a adição de mais ferramentas. 