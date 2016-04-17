## Trilha Como aprender Javascript Corretamente! – JavaScript.is (Sexy)

`Aprenda Javascript Corretamente (para NÃO programadores javascript e programadores de primeira viagem)`

- Duração: 6 a 8 semanas

Tópicos nesse post:

- Recursos para esse curso
- Semanas 1 e 2: `Introdução`, `Tipos de dados`, `expressões` e `operadores`
- Semanas 3 e 4: `Objetos`, `vetores`, `funçoes`, `DOM`, `jQuery`
- Seu primeiro projeto: Questionário Dinâmico
- Semanas 5 e 6: Expressões Regulares, Eventos do Objeto Window, jQuery
- Semanas 7 e 8: Classes, Herança, mais HTML5
- Continue melhorando
- Palavras de encorajamento

## Recursos para este curso

- Inscreva-se com uma conta em Codeacademy. Esta é uma plataforma online para aprender a programar: você escreve um código neste website, diretamente do seu browser. (Também é um serviço grátis).

- Posts no JavaScriptIsSexy Blog: Objects, Closures, Variable Scope and Hoisting, Functions, e outros.

### Semana 1 e 2 (Introdução, Tipos de dados, Expressões e Operadores)

1. Se você ainda não sabe HTML e CSS muito bem, complete os “Fundamentos Web” no site Codecademy.

2. Leia o Prefácio e os capítulos 1 e 2 de Javascript: The Definitie Guide.

3. Muito Importante: Cada exemplo de código que você encontrar no livro, escreva-o, teste e experimente o código nos browsers Firefox e Chrome. Ou use o JSFiddle. Não use o Safari. Eu recomendo o Firefox – adicione o Firebug add on para firefox e use isso para testar e debugar seu código. O console do browser é a área do browser onde você poderá escrever e rodar o código javascript.

JSFiddle é uma aplicação web que permite a você escrever e testar seu código online, como no seu browser. Você pode testar todo tipo de código, incluindo uma combinação de HTML, CSS e Javascript (e jQuery).

4. Trabalhe através da seção Introdução ao Javascript na JavaScript Track em Codecademy.

5. Leia os capítulos 3 e 4 de JavaScript: The Definitive Guide.Você pode pular a seção “Bitwise Operators”; dificilmente você irá usar isso na sua carreira JavaScript.

E novamente, assegure-se de parar e escrever os códigos exemplos no seu browser (ou JSFiddle) e experimentar – mude algumas variáveis e saboreie um pouco do código.

6. Leia o capítulo 5 de JavaScript: The Definitive Guide.

7. Trabalhe nas seções de 2 a 5 de JavaScript Track no Codecademy.

### Semanas 3 e 4 (Objetos, Vetores, Funções, DOM, jQuery)

1. Leia meu post [Objetos Javascript em detalhe](http://javascriptissexy.com/javascript-objects-in-detail/).

Ou leia o capítulo 6 de Javascript: The Definitive Guide.

Qualquer um dos 2 são bons, embora o texto do livro entre em maiores detalhes: os detalhes extra você pode pular com confiança, se você ler e compreender corretamente meu post.

2. Leia os capítulos 7 e 8 de Javascript: The Definitive Guide.

3. Neste momento, você deve gastar bastante tempo escrevendo código em seu console do browser e testando as declarações if-else, loops for, arrays, funções, objetos e mais. É extremamente importante que você saiba (e continue praticando) como programar independentemente (sem ajuda do Codecademy) em seu browser. Quando você voltar para o Codecademy, você não precisará de nenhuma ajuda ou dica. Cada tarefa já será fácil para você.

Se você ainda está tendo dificuldades com Codecademy, volte ao seu browser e continue tentando. É ai que você vai aprender mais. Isto é o análogo ao Lebron James aprimorando suas habilidades nas ruas (nas quadras de basquete do seu bairro), ou ao Bill Gates trabalhando em seu porão.

Há um enorme valor em você mexer e aprender pouco a pouco por conta própria. Você tem que perceber o valor dessa estratégia, e também abraçar e acreditar que isso vai dar certo!

Há uma falsa sensação de sucesso quando se usa o Codecademy. O maior problema com Codecademy é que as dicas e o pequeno fragmento de código o ajuda tanto que você tem a falsa sensação de sucesso quando você avança nos exercícios facilmente. Você não sabia disso ainda, mas muito do que você está fazendo não é por si próprio.

Agora, Codecademy continua sendo de grande ajuda para se aprender como programar, particularmente na maneira em que o orienta através do processo de desenvolvimento de pequenos projetos e pequenas aplicações de construções de código básicas como if, for, funções e variáveis.

4. Volte ao Codecademy e complete o Javascript track trabalhando nas seções 6, 7 e 8 (Estrutura de Dados até Objetos 2).

5. Enquanto você estiver em Codecademy, faça os 5 pequenos projetos básicos na seção Projects. Depois disso, você estará livre do Codecademy. E isso é bom pois quanto mais você trabalhar por sua conta, mais rápido irá ser seu aprendizado e melhor você estará preparado para começar a programar sozinho.

6. Leia os capítulos 13, 15, 16 e 19 de Javascript: The Definitive Guide.

O que Codecademy trata sobre jQuery é insuficiente. Siga esse curso de jQuery – é grátis: [Try JQuery](http://try.jquery.com/)

E você pode ler o capítulo 19 de Javascript: The Definite Guide, se você tiver o livro, para mais sobre jQuery.

7. Trabalhe através de todo o curso em [Try JQuery](http://try.jquery.com/)

## Seu Primeiro Projeto – Um Questinário Dinâmico #

Nesse momento, você já aprendeu o suficiente para construir uma sólida aplicação. Não prossiga nada além disso até você conseguir construir com sucesso essa aplicação que descrevi abaixo. Se você estiver com dificuldades, faça perguntas no Stack Overflow e releia as seções do livro para entender corretamente os conceitos.

Você irá construir uma aplicação de questionário javascript (você vai usar html e css também) que funcionará da seguinte forma:

- Este é um simples questionário com botões de escolha do tipo radio, que vai mostrar ao usuário sua pontuação na competição.

- O questionário poderá ter quaisquer quantidades de questões e escolhas.

- Compute a pontuação do usuário e mostre a pontuação final na última página. Na última página deverá aparecer somente a pontuação, então remova a última pergunta.

- Use um array para armazenar todas as questões. Cada pergunta, juntamente com suas alternativas e respostas corretas, deverão ser armazenadas em um objeto. O array de questões deverá ser parecido com isso:

`Somente uma pergunta está nesse array, mas você vai adicionar todas as perguntas.`

  <code>
  	var todasPerguntas = [{
  	  pergunta: “Quem é o primeiro ministro do Reino Unido?”, 
      escolhas: [“David Cameron”, “Gordon Brown”, “Winston Churchill”, “Tony Blair”], 
      respostaCorreta:0
    }];
  </code>

- Dinamicamente (com document.getElementById ou jQuery) adicione a próxima pergunta e remova a atual da tela, quando o usuári clicar no botão “Próximo”. O botão “próximo” vai ser somente o botão para navegar neste questionário.

- Você pode comentar no Stack Overflow. Provavelmente você terá uma resposta rápida e precisa no Stack Overflow.

### Semanas 5 e 6 (Expressões Regulares, Window Object, Eventos e jQuery)

1. Leia os capítulos 10, 14, 17 e 20 de Javascript: The Definitive Guide.

2. Lembre-se de manter-se escrevendo todos os exemplos de códigos no console do Firefox e ajustar cada pedaço de código para experimentá-lo e assim realmente entender como ele funciona e porque funciona.

3. Neste ponto, você deve estar muito confortável com o javascript, provavelmente se sentindo como um jedi. Você ainda não é jedi, e deve continuar usando seus novos conhecimentos e habilidades sempre que possível para continuar aprendendo e melhorando.

4. Melhore sua aplicação de questionário anterior:

- Adicione uma validação “client-side” (no lado do usuário): tenha certeza que o usuário respondeu cada pergunta antes de continuar para a próxima.
- Adicione um botão “Voltar” para permitir que o usuário volte e mude sua resposta. O usuário pode voltar até a primeira questão. Para as questões que o usuário já tiver respondido, certifique-se de mostrar o botão “radio” selecionado, então o usuário não será forçado a responder a questão novamente, pois ela já foi concluída.
- Use jQuery para adicionar uma animação (“fade out” para a pergunta atual e “fade in” para a próxima pergunta).
- Teste o questionário no IE8 e 9 (Internet Explorer 8 e 9), e conserte todos os erros. Isso irá lhe dar um bom trabalho ; )
- Armazene as perguntas do questionário em um arquivo JSON externo.
- Adicione uma autenticação de usuário: permita o login de usuários, e salve suas informações de login no “local storage” (armazenador do navegador em HTML5).
- Use “cookies” para lembrar o usuário, e mostre uma mensagem “Bem vindo, Primeiro Nome” quando o usuário retornar ao questionário.

### Semana 7 e se necessária 8 (Classes, Herança, mais HTML5)

1. Leia os capítulos 9, 18, 21 e 22 de Javascript the Definitive Guide

Ou leia meu post no blog, [POO em Javascript: O que você PRECISA de saber](http://javascriptissexy.com/oop-in-javascript-what-you-need-to-know/) 

NOTA: A leitura nesta seção do livro é a mais técnica que você vai encontrar neste roteiro inteiro. Cabe a você escolher se vai ler tudo isso. Você deve pelo menos aprender Padrões “Prototype”, “Factory” e Herança de Protótipos. Você não tem que saber todos os outros padrões.

2. Melhore seu questionário ainda mais:

- Use o [Twitter Bootstrap](http://getbootstrap.com/2.3.2/) para todo o layout da página, incluindo os elementos de questionário para fazê-lo aparentar mais profissional. E como um bônus adicional, use os componentes da interface de abas do Twitter Bootstrap e apresente 4 questionários diferentes, um em cada aba.

- Aprenda [Handlebars.js](http://javascriptissexy.com/handlebars-js-tutorial-learn-everything-about-handlebars-js-javascript-templating/) e adicione o modelo de Handlebars.js ao questionário. Você não deve ter nada de HTML no seu código javascript. Seu questionário está ficando mais avançado pouco a pouco.

- Pegue a pontuação de todos os usuários que responderam o questionário e mostre a pontuação de cada um no rank geral com todas as pontuações.

3. Mais tarde (após você aprender Backbone.js e Node.js), você irá usar essas duas tecnologias para refazer seu questionário e tornar este mesmo questionário em um sofisticado, “single-page”, aplicativo web moderno, feito com os últimos frameworks. E você irá guardar as credenciais de autenticação do usuário e sua pontuação em um banco de dados MongoDB.

4. Próximo: Decida um projeto pessoal para construir, e começe a trabalhar no projeto imediatamente (enquanto tudo está fresco na sua mente). Use Javascript Definitive Guide (ou Professional Javascript for Web Developers), como referência se você estiver “emperrado”. E claro seja um membro ativo em Stack Overflow: pergunte e responda questões para os outros programadores.

## Continue Melhorando

1. [Aprenda Backbone.js corretamente](http://javascriptissexy.com/learn-backbone-js-completely/)

2. [Aprenda Javascript Intermediário e Avançado](http://javascriptissexy.com/learn-intermediate-and-advanced-javascript/)

3. [Aprenda Node.js corretamente e com confiança](http://javascriptissexy.com/learn-node-js-completely-and-with-confidence/)

## Palavras de Encorajamento

Tudo de bom para seus estudos. Nunca desista! Quando você estiver lutando e se sentindo um idiota (você pode, de vez em quando), sempre lembre-se que alguns (talvez a maioria) dos outros novos e experientes programadores em torno do mundo, provavelmente estarão sentindo a mesma coisa.

É difícil no começo quando você está aprendendo a “codar” (programar) pela primeira vez, especialmente se você já passou da adolescência. Adolescentes não tem medo e nada a perder, e muito tempo para <del>jogar fora</del> usar em qualquer coisa que estiverem apaixonados. Então os desafios podem parecer somente pequenos obstáculos para eles.

Mas depois da sua adolescência, você quer resultados rápidos pois não tem mais tempo para perder com assuntos aparentemente triviais. Mas é ai que você tem que ir fundo e não ficar frustado. Apenas continue na tarefa até que você descubra o erro, por uma recompensa que vale a pena esperar até que você triunfe no fim – programação é divertido e lucrativo.

A alegria e o intenso prazer que se tem ao construir uma aplicação é um sentimento incrível que deve ser experimentado para ser entendido. Mais satisfatório, entretanto, é o amadurecimento que você sente ao ter atingido as habilidades e conhecimentos para construir aplicações do zero.

Chegará o momento em que você perceberá que toda dificuldade que enfrentou valeu a pena, porque você se tornou um programador e você sabe que seu futuro é brilhante como desenvolvedor javascript. Assim como os milhares e milhares antes de você: Você sobreviveu aos bugs, você não desistiu, e você triunfou em encontrar várias desculpas para desistir.

#### Referências

- [Artigo original EN](http://javascriptissexy.com/how-to-learn-javascript-properly/)
- [Artigo traduzido](https://codeinbrasil.wordpress.com/2013/04/28/como-aprender-javascript-corretamente-javascript-is-sexy/)
- [JSFiddle](https://jsfiddle.net/)
- [Codecademy](https://www.codecademy.com/)
- [Stack Overflow](http://stackoverflow.com/)
- [Javascript is Sexy](http://javascriptissexy.com/)

#### Material Apoio

- [MDN - Mozilla Developer Network](https://developer.mozilla.org/en-US/Learn/JavaScript)
- [Material de apoio aos grupos](https://github.com/training-center/study-groups/blob/master/material-de-apoio.md)

#### Livros
- [Download] [The Definitive Guide for Download](http://jonathanlima.com.br/The%20Definitive%20Guide.pdf.zip)
- [Eloquente Javascript](https://github.com/braziljs/eloquente-javascript)
- [Download] [Código Limpo](http://jonathanlima.com.br/Codigo%20Limpo%20-%20Completo%20PT.pdf)
