# Pesquisa
## ↪CSS
### Aula de 06-03-2020

### O que é o CSS?
  CSS (ou Folha de Estilo em Cascata) é o código que você utiliza para definir a apresentação (aparência) em páginas da internet que adotam para o seu desenvolvimento linguagens de marcação (como XML, HTML e XHTML). Basicamente é ele que insere o estilo de um documento HTML, descrevendo como os elementos HTML devem ser exibidos.O CSS não é realmente uma linguagem de programação como também não é uma linguagem de marcação.

### Como o CSS pode ser aplicado?
  Mantém tanto a função de estruturar o conteúdo quanto de apresentá-lo para o usuário final. Foi desenvolvido para habilitar a separação do conteúdo e formato de um documento (na linguagem de formatação utilizada) de sua apresentação, incluindo elementos como cores, formatos de fontes e layout. Esta separação proporcionou uma maior flexibilidade e controle na especificação de como as características serão exibidas, permitiu um compartilhamento de formato e reduziu a repetição no conteúdo estrutural de uma página.

### Os Seletores CSS
 O Seletor indica o elemento que será estilizado e foram otimizados para serem usados com as linguagens de marcação HTML e XML. 
 Seletor de ID ► Seleciona o elemento na página com o ID específicado. Em uma determinada página HTML, você só tem permissão para um elemento por ID (e claro, um ID por elemento).
 Seletor de classe ►Seleciona o(s) elemento(s) na página com a classe específicada (várias instâncias de classe podem aparecer em uma página).
Seletor de atributo	► Seleciona o(s) elemento(s) na página com o atributo especificado.

### Como inserir o código CSS?
  Existem três maneiras de inserir o CSS e aplicar as mudanças visuais nas páginas web:
  ►Externa - um arquivo externo CSS (ex: 'estilos.css') que reúne as regras para várias páginas. Esta é a opção mais recomendada para sites com várias páginas pela facilidade de organização e manutenção. Dessa forma também é necessário incluir um elemento <link> para indicar onde está o arquivo de folha de estilos CSS. Nessa forma também é possível usar vários arquivos de folhas de estilos, o que adiciona mais um nível de organização do código.
ex:

<head>
<link rel="stylesheet" type="text/css" href="style.css" />
</   head>
  
  ►Interna - as regras CSS ficam no próprio documento HTML, dentro do elemento <style>. Este método geralmente é usado para sites com poucas páginas ou para determinar regras específicas de uma página.
ex:
  
<head>
<style type="text/css">
p {color:white; font-size: 10px;}
.center {display: block; margin: 0 auto;}
#button-go, #button-back {border: solid 1px black;}
</style>
</   head>
  
  ►Inline - a regra CSS é usada como um atributo de um elemento HTML – o atributo style. Esta forma não é muito recomendada pela dificuldade de organização e manutenção das regras CSS por elemento.
ex:


<body style="background-color:black;">

<h1 style="color:white;padding:30px;">Hostinger Tutorials< / h1>
<p style="color:white;">Something usefull here.< / p>


#### </   head> (Retirar os espaçõs para a utilização do código)
  
### Framework's
   Sendo um facilitador no desenvolvimento de diversas aplicações, sem dúvida, sua utilização poupa tempo e custos para quem utiliza, pois de forma mais básica, são templates que provém diversas funções que podem ser utilizadas em qualquer projeto e com o resultado bem bacana. Traz consigo diversas séries de classes e funções predefinidas que na hora do desenvolvimento torna-se agregadores de otimização de projetos, seja eles em aplicativos, sistemas ou interface.
   ►Bootstrap - desenvolvido pelo Twitter, que traz consigo características bem definidas de inicialização rápida, ou seja, possuem estilos predefinidos (prontos). Com a utilização do Bootstrap é possível a criação de sites responsivos, que são aqueles que se adaptam ao tamanho da tela que estará sendo utilizada pelo usuário. Seus modelos utilizam de uma mesma característica onde, além da harmonia na criação de projetos, possui um design padrão de arredondamento de bordas, conforme as figuras abaixo.
   ►Purecss - bastante simples, é mantido pelo Yahoo! inc. que contém um conjunto componentes CSS responsivos que você pode utilizar em qualquer projeto. O arquivo .min do Pure possui apenas 4.5KB, muito menor que o arquivo do Bootstrap por exemplo, além de possuir links para servidores CDN.
   ►Foundation - completamente personalizável, possui como forte característica sua responsividade, sem a necessidade de adicionar classes, facilitando assim a criação de sites, aplicativos e muito mais. Possui design mais profissional, com cores bem definidas e formatos de componentes mais quadrados, como podemos observar na imagem abaixo, que difere bastante dos componentes já apresentados acima.
   
