# Cores

## Tokens fixos

-   primary
-   secondary
-   tertiary
-   basePrimary
-   baseSecondary
-   baseTertiary
-   systemError
-   systemSuccess
-   systemWarning
-   background
-   surface
    > Cores base são as variações entre preto e branco (Exemplo: Primary=Branco, Seondary=Cinza, Tertiary=Preto).

## Variação de cores

Light/Dark ou Escala de cores

1. Light/Dark é uma forma mais simples e direta
    - Ex: primaryLight, primaryDark
2. Escala de cores dá mais opções porem mais trabalho no inicio para definir o design system
    - Ex: primary10, primary20, primary30, ...
    - Cor base é 50 e existem variações para mais e para menos.
3. Prefixo **on** para cores que vão acima de outra
    - ex: background > onBackground
    - ex: primaryDark > onPrimaryDark
4. É importante usar as cores para a sua função (não é algo obrigatório, mas é bom evitar criar exceções para manter a coesão no design) por exemplo usar o token background para o background e o surface para coisas que ficam na superfície do background.

# Tipografia

## Tokens fixos

-   h1, h2, h3, h4 e h5
-   subtitle
-   body
-   button
-   label
-   ...

> A ideia é cada style ter seu tamanho, height e peso. Serem reutilizados e sem ficar variando os valores anteriormente mencionados.

> O design pode precisar, de variações com font family diferente. Nesses casos vamos tratar com um estilo especial. Podemos dar um nome para ele que faça sentido com o seu uso, por exemplo: tvShowTitle, é um titulo com uma fonte especial utilizado apenas nos títulos de um programa na tela de programa.

## Variações

1. Vamos criar duas opções para variar o tamanho de um text style: large ou small. Large para uma versão maior do texto e small para uma versão menor.
    - Ex: bodySmall, body e bodyLarge
2. Usaremos o preso da fonte como sufixo para especificar o preso da fonte.
    - bodyLarge, bodyLargeBold

## Links úteis

-   https://www.figma.com/design/pttxPv5STpQ8RT3ml5hwDa/Mobile-Design-System-Starter-2.0--Community-?node-id=1710-1325&p=f&t=xAuCHu7km14NQBxP-0
-   https://www.youtube.com/watch?v=HNJmWKndUA4
