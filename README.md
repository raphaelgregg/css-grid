# CSS GRID

## GRID
- Bimensional
- Divisão de toda a pagina em linhas e colunas
- Colocar elementos onde quiser nessa divisão

## GRID OU FLEX
- GRID: Duas dimensões (colunas e linhas)
- FLexbox: Uma dimenção ( ou coluna ou linha)
- Um complementa o trabalho do outro
- Verificar quias navegadores ainda não estão aceitando Grid
  
## PROPRIEDADES
Vamos separar em 2 grupos
`container` e `item(s)`

### CONTAINER
- display: grid;
- grid-template-column;
- grid-template-rows;
- grid-gap;
  - grid-row-gap
  - grid-column-gap
  - grid-template-areas;

... e mais 4 propriedades e **alinhamentos**

### ITEM(s)
- grid-column
  - grid-column-start
  - grid-column-end
- grid-row
  - grid-row-start
  - grid-row-end
- grid-area

... e mais 2 propriedades de **alinhamentos**

## Grid: Alinhamento

Existem 6 propriedades para alinhamento:
`justify-content`
`align-content`
`justify-items`
`align-items`
`justify-self`
`align-self`

Dois grupos
1. `justify` e `align`
2. `content`  `items` e `self`

### Justify e Align

sabendo que o grid é bidimensional, nós temos o eixo x e o y.

O **eixo x** é o posicionamento horizontal, da esquerda para a direita.
O **eixo y** é o posicionamento vertical, da cima para baixo.

### Content, Items e Self

Juntando o `justify`, ou `align`, com esses elementos: `content`  `items` e `self`; nós observamos nossas propriedades

### Content

`justify-content` e `align-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

O uso dessas, propriedades são raras, pois só é aplicado caso o grid seja menor que a area definida. (Por exemplo, quando usamos em px o tamanho do grid, poderemos terminar com um grid pequeno, para o tamanho da aréa do grid)

Podemos usar **7 valores**
1. start
2. end
3. center
4. strech
5. space-between
6. space-around
7. space-evenly

### Items

`justify-items` e `align-items` nos permite alinhar os items do nosso grid, em qualquer espaço disponível, na célula que ele habitar.

Podemos usar **4 valores**
1. start
2. end
3. center
4. stretch


### Self

`justify-self` e `align-self` vai nos permitir alinhar o item em si.

Faz a mesma coisa que o `justify-items` e `align-items`, porém, aplicado diertamento no item de um grid.