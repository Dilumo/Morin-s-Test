# Morin's test
Um simples jogo de tabuleiro, um grande desafio. Vença o ultimo teste e se torne um Elementalista.


# Introdução

  Esse jogo pertence a uma serie de jogos de uma página, que tem como objetivo render mais conhecimento básico a mim e facilitar a entrada/volta de pessoas com menos tempo ou interesse para jogos mais complexos.

# Indice

  - [Documentação](#documentação)
      - [Highconcept](#highconcept)
      - [Enredo](#enredo)
      - [Gameplay](#gameplay)
          - [Regras](#regras) 
          - [Elementos](#elementos)
          - [Efeitos](#efeitos)
  - [Interface](#interface)
  - [Ideias](#ideias)
  - [Meios](#meios)


---
<a name="documentação"></a>
# Documentação
Informações sobre o jogo são encontradas aqui, mas por se tratar de um projeto já feito, algumas informações como o Cronograma não são demosntrados aqui.

<a name="highconcept"></a>
##  Highconcept
  Um jogo de tabuleiro com um sistema de progressão randômica, onde você desafia um adversário para uma batalha de elementos.       
<a name="enredo"></a>                      
## Enredo
Você um aprendiz de elementarista que após passar por vários testes, se encontra no teste final, o Teste de Morin, uma batalha entre aprendizes de varias cordas para provar seu valor. Agora cabe a você desafiar seu adversario em um plano espectral, entre as correntes mais puras de poder elemental e provar ali seu valor.

<a name="gameplay"></a>
## Gameplay 

Com o auxílio de *dois dados* o jogador usa um para marcar seu personagem e outro para definir seus movimentos no tabuleiro.

<a name="regras"></a>
##  Regras: 

- Jogador começa do quadrado Início.
- Jogador roda um dado para andar:
    - 2 Esquerda 3 Direita 4 cima 5 baixo
    - 1  escolhe entre esquerda e direita
    - 6  escolhe entre cima e baixo
- Ao passar sobre um poder você escolhe entre, Manter (até 2), Lançar e Defender.
- Você começa com dez pontos de vida.
- O jogo termina quando um dos dois participantes chegar a zero de vida.
- Vence aquele que tiver vida ao final da partida.
- Ao chegar na linha do meio do tabuleiro, reinicia do ponto de início, com o adicional de +1 de poder, que vale para defesa e ataque. A terceira vez que passar pela linha do meio você começa com 2 cargas de um escudo que anula todos os danos. 
  
<a name="elementos"></a>
## Elementos

- ![Water](https://github.com/Dilumo/Morin-s-test/blob/master/Documents/Assets/Water.png?raw=true "Water") <br> 
**Water:** O elemento "Água" que é mais forte que o fogo e mais fraco que a eletricidade.
- ![Fire](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Fire.png?raw=true "Fire") <br> 
**Fire:** O elemento "Fogo" que é mais forte que a natureza e mais fraco que a água.
- ![Nature](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Nature.png?raw=true "Nature") <br> 
**Nature:** O elemento "Natureza" que é mais forte que eletricidade e mais fraco que fogo.
- ![Electricity](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Electricity.png?raw=true "Electricity") <br> 
**Electricity:** O elemento "Eletricidade" que é mais forte que água e mais fraco que natureza.

<a name="efeitos"></a>
## Efeitos:

- ![Life](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Life.png?raw=true "Life") <br> 
**Life:** Jogador recupera um ponto de vida ao passar por cima dele.
- ![Damage](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Damage.png?raw=true "Damage") <br> 
**Damage:** Jogador perde um de vida ao passar por ele.

<a name="interface"></a>
# Interface
>![Explicação da interface](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Interface.png?raw=true "Explicação da interface") <br> 
 > **Fonte:** Acervo pessoal.

<a name="ideias"></a>
# Ideias
Entre as ideias para uma extensão do jogo, temos a ideia de colocar cartas de ação, que serião compradas com o valor de dois elementos mantidos, onde para serem postas em jogo, o jogador deveria manter elementos em expecifico. 

<a name="meios"></a>
# Meios
Usei as dependências da minha casa para produzir esse jogo.
- Inkscape
- Visual Studio Code
- GitHub