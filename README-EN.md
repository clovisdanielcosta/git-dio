
<h1 align="center">
Course Introduction to Git And GitHub
</h1>
<p>
Este repositório foi criado para efeito de estudo nos seguintes cursos ofertados gratuitamente pela <b>Digital Innovation One</b>:
<b>

- :white_check_mark: Introdução ao Git e Controle de Versões.
- :white_check_mark: Introdução ao GitHub e comandos para trabalhar em equipe. 
- :white_check_mark: Criando um repositório para seus projetos inovadores.

</b>

<p align="center">
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#books-conhecimento">Conhecimentos adquiridos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#small_orange_diamond-contribuindo">Contribuindo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#small_orange_diamond-agradecimentos">Agradecimentos</a>
</p>

## :rocket: Tecnologias

Nesse projeto foram usadas as seguintes tecnologias:

- [Git](https://git-scm.com/)
- [GitHub](https://github.com/)
- [GitBash](https://gitforwindows.org/)

## :memo: Requisitos

- Familiaridade como o uso do prompt de comando.
- Instalação do Git Bash em caso de uso no Windows.
- Criação de conta no GitHub.

## :books: Conhecimento

Foram adquiridos novos conhecimentos neste projeto, entre eles:
</b>

- Linus Torvalds, pai do Linux, também foi o criador do Git.
- Git não é a mesma coisa que GitHub.
- Sensacional: como editar mais facilmente o README.md dos reposítórios no GitHub.
- Como colocar trechos de código no README.md.

</b>

## :small_orange_diamond: Contribuindo

Repassando um pouco do aprendizado.

### 1. Git não é GitHub

Dito de modo simples:

- Git é um gerenciador de versões do projeto.
- GitHub é um repositório onde estas versões e alterações do projeto são armazenadas. Foi adquirido pela Microsoft, o que dá o respaldo de uma grande companhia para garantir a confiabilidade do serviço. 

### 2. Editando mais facilmente o README.md

- Para editar mais facilmente o README.md do projeto pode se usar online o MD Editor no site:

[https://pandao.github.io/editor.md/en.html](https://pandao.github.io/editor.md/en.html)

### 3. Colocando Emojis no README.md

Para adicionar Emojis no README.md para dar um toque especial pode-se usar o site:

[https://www.webfx.com/tools/emoji-cheat-sheet/](https://www.webfx.com/tools/emoji-cheat-sheet/)

Para inserir o emoji no README.md basta clicar no emoji desejado no site e colar no editor. 
Por exemplo, se quiser adicionar o emoji de foguete comumente usado do GitHub para se referir ao uso de tecnologias, digite a linha abaixo no editor onde está alterando o README.md:

````markdown
 :rocket: Tecnologias
````
O resultado será:

 :rocket: Tecnologias

### 4. Colocando trecho de código no README.md

Exemplo de como colocar um trecho de código em JavaScript no README.md:

```javascript
```javascript
  // Função para recolher o menu quando clicar na página sem escolher nenhuma opção
  $(document).on('click', function(event){
    var $clickedOn = $(event.target),
    $collapsableItems = $('.collapse'),
    isToggleButton = ($clickedOn.closest('.navbar-toggle').length == 1),
    isLink = ($clickedOn.closest('#navToggle').length == 1),
    isOutsideNavbar = ($clickedOn.parents('.navbar').length == 0);
    
    if( (!isToggleButton && isLink) || isOutsideNavbar ) {
      $collapsableItems.each(function(){
        $(this).collapse('hide');
      });
    }
  });
  ...
```

O resultado será:


```javascript
  // Função para recolher o menu quando clicar na página sem escolher nenhuma opção
  $(document).on('click', function(event){
    var $clickedOn = $(event.target),
    $collapsableItems = $('.collapse'),
    isToggleButton = ($clickedOn.closest('.navbar-toggle').length == 1),
    isLink = ($clickedOn.closest('#navToggle').length == 1),
    isOutsideNavbar = ($clickedOn.parents('.navbar').length == 0);
    
    if( (!isToggleButton && isLink) || isOutsideNavbar ) {
      $collapsableItems.each(function(){
        $(this).collapse('hide');
      });
    }
  });
```

## :small_orange_diamond: Agradecimentos

Quero agradecer imensamente aos listados abaixo pelas contribuições para o meu aprendizado sobre este tema, quer tenham sido em cursos ou em vídeos postados no Youtube. Parabéns pelo trabalho de vocês. O efeito que vocês têm causado na comunidade é realmente significativo e sinceramente apreciado. 

- Digital Innovation One
- Carlos Levir
- Rocketseat

Muito obrigado!:clap::clap:
