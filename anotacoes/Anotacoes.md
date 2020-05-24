# Flexbox Layout

## Flex Container

  ### Display

    - Os elementos ficam em linha;
    - Ocupa somente o espaço do seu contéudo.

  ### Flex-direction

    - Controla a direção dos elementos flex no container (row, row-reverse, column, column-reverse);
    - O padrão é os elementos ficarem em linha (row).

  ### Flex-wrap

    - Controla a quebra de linha dos elementos flex no container (nowrap, wrap, wrap-reverse);
    - O padrão é os elementos não quebrarem a linha (nowrap).

  ### Flex-flow

    - Atalho para o flex-direction e flex-wrap.

  ### Justify-content

    - Controla o alinhamento dos elementos flex do eixo horizontal (flex-start, flex-end, center, space-around, space-between);
    - O padrão é os elementos ficaram alinhados a esquerda (flex-start).

  ### align-items

    - Controla o alinhamento dos elementos flex do eixo vertical (stretch, flex-start, flex-end, center, baseline);
    - O padrão é os elementos ficaram esticados ocupando o tamanho do elemento de maior contéudo (stretch).

  ### Align-content

    - Controla o alinhamento das linhas do container no eixo vertical(stretch, flex-start, flex-end, center, space-around, space-between);
    - A propriedade só funciona caso contenha mais de uma linha;
  - O padrão é os elementos ficaram esticados igualmente (stretch).

  ### Observações

    - Quando a direção é em coluna, "justify-content" muda para a vertical e "align-items" para a horizontal;
    - Quando se define ma direção para uma linha ou coluna reversa, start e end também são reversos.

## Flex Container

  ### Flex-grow

    - Define a habilidade de um elemento flex individual crescer;
    - O padrão o valor é "0";

  ### Flex-basic

    - Define o comprimento de um elemento flex individual;
    - O padrão é o valor "auto";
    - Pode-se receber qualquer unidades css;
    - Possui um compartamento parecido com o "min-width".

  ### Flex-shrink

    - Define a habilidade de um elemento flex individual diminuir em relação aos restantes;
    - O padrão é o valor "1".

  ### Flex

    - Atalho para o flex-grow, flex-shrink e flex-basic.
    - O "flex: 1", define o "flex-grow: 1, flex-shrink: 1 e flex-basis: 0;

  ### Order

    - Controla a ordenação do elemento flex individual, do menor para o maior;
    - O padrão é o valor 0;
    - Pode-se receber valores inteiros positivos e negativos.

  ### Align-self

    - Aceita os mesmos valores que a propriedade "align-items";
    - Se aplica ao elemento flex individual;
    - Por ser específico, possua maior especificidade do que a propriedade "align-items".

  ### Observações

    - É recomendado utilizar a propriedade "flex", em vez de definir as propriedades individuas;
    - A propeidade "justify-content" não funciona em items com flex-grow definido.
    - As propriedades "float, clear e vertical-align" não têm efeito em flex-items.


## Materiais de Apoio

  - [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [Flexbox MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
  - [Flexblox W3C](https://www.w3schools.com/csS/css3_flexbox.asp)
  - [Flexbox guia completo - Origamid](https://origamid.com/projetos/flexbox-guia-completo/)
  - [CSS FlexBox: Um Guia Visual - Alura](https://www.alura.com.br/artigos/css-guia-do-flexbox)
  - [Flexbox Froggy](https://flexboxfroggy.com/)
  - [Flexbugs - Github](https://github.com/philipwalton/flexbugs)