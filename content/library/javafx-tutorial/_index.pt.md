---
layout: article
title: "Tutorial JavaFX 8 (Português)"
date: 2014-09-10
updated: 2014-11-06
slug: javafx-tutorial/pt
github: https://github.com/marcojakob/code.makery.ch/edit/master/collections/library/javafx-tutorial-pt.md
description: "Este Tutorial em sete partes orienta a criação, programação e a implantação de um aplicativo de endereços usando JavaFX."
image: /assets/library/javafx-tutorial/addressapp.png
published: true
prettify: true
comments: false
sidebars:
- header: "Artigos nesta serie"
  body:
  - text: "Introdução"
    link: /library/javafx-tutorial/pt/
    paging: Intro
    active: true
  - text: "Parte 1: Scene Builder"
    link: /library/javafx-tutorial/pt/part1/
    paging: 1
  - text: "Parte 2: Modelo e TableView"
    link: /library/javafx-tutorial/pt/part2/
    paging: 2
  - text: "Parte 3: Interagindo com o usuário"
    link: /library/javafx-tutorial/pt/part3/
    paging: 3
  - text: "Parte 4: Estilos usando CSS"
    link: /library/javafx-tutorial/pt/part4/
    paging: 4
  - text: "Parte 5: Salvando dados como XML"
    link: /library/javafx-tutorial/pt/part5/
    paging: 5
  - text: "Parte 6: Gráficos de Estatistica"
    link: /library/javafx-tutorial/pt/part6/
    paging: 6
  - text: "Parte 7: Implantação"
    link: /library/javafx-tutorial/pt/part7/
    paging: 7
languages: 
  header: Linguagens
  collection: library
  item: javafx-tutorial
  part: 
  active: pt
---

Em 2012 eu criei um tutorial muito detalhado [JavaFX 2 tutorial series](/library/javafx-2-tutorial/) para meus alunos. Muitas pessoas ao redor do mundo leram o tutorial e derem um feedback possitivo. Então eu decidi ** rescrever o tutorial de JavaFX 2 para JavaFX 8** (Leia sobre o que mudou em [Atualização para JavaFX 8 - Quais as novidades](/blog/update-to-javafx-8-whats-new/)).

Este Tutorial em sete partes orienta a criação, programação e a implantação de um aplicativo de endereços. No fim nossa aplicação ficará como a da imagem:

![Screenshot AddressApp](/assets/library/javafx-tutorial/addressapp.png)


## Oque você aprenderá

* Criar e executar um projeto JavaFX
* Usar o Scene Builder para criar a interface com o usuário
* Estruturar uma aplicação usando o padrão MVC (Modelo Visão Controle)
* Usar `ObservableLists` para atualizar automaticamente a interface do usuário
* Usar `TableView`e mostar as informações ao selecionar uma linha
* Criar uma caixa de dialogo popup para editar as informações das pessoas
* Validar a entrada do usuário
* Personalizar um aplicativo JavaFX usando CSS
* Persistir dados usando XML
* Armazenar o ultimo arquivo aberto nas preferencias do usuário
* Criar gráfico JavaFX com estatísticas
* Implementar um aplicativo JavaFX como um pacote nativo

**São muitas coisas!** Assim, depois que você completar esta serie de tutoriais você estará pronto para criar aplicativos sofisticados com JavaFX.


## Como usar este tutorial

Há duas maneira de usar este tutorial:
* **Aprendizagem:** Crie seu própio projeto JavaFX do zero.
* **Modo rapido:** Importe o código fonte de uma parte do tutorial para sua IDE (é um projeto Eclipse, mas você pode usar outras IDEs como o NetBeans com algumas modificações). E depois ler o tutorial para entender o código.

Espero que você se divirta! Começe com [Parte 1: Scene Builder](/library/javafx-tutorial/pt/part1/).


<div class="alert alert-success">
  <strong><i class="fa fa-trophy"></i> Atribuição:</strong> Contribuiram para a tradução deste tutorial:
  <ul>
    <li><a href="https://github.com/JulioDinis" class="alert-link">JulioDinis</a></li> 
    <li><a href="https://github.com/RegiusK" class="alert-link">Régius Andrei Kachimareck</a></li>
    <li><a href="https://github.com/Shura16" class="alert-link">João Antônio Cabral</a></li>
    <li><a href="https://github.com/alexaleluia12" class="alert-link">Alex Aleluia</a></li>
  </ul>
  Muito obrigado!
</div>
