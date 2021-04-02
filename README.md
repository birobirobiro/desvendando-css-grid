## CSS GRID

## GRID

- Bidimensional
- Divisão de toda a página em linhas e colunas
- Coloar elementos onde quiser nessa divisão de

---

## GRID OU FLEXBOX

- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou coluna ou linha)
- Um complementa o trabalho do outro
- Verificar quais navegadores ainda não estão aceitando o Grid

---

## PROPRIEDADES

Vamos separar em 2 grupos:
`container` e `items(s)`

### CONTAINER

- display: grid;
- grid-template-columns;
- grid-template-rows;
- grid-gap
  - grid-row-gap;
  - grid-column-gap;
- grid-template-areas;

... e mais 4 propriedades e **alinhamentos**

### ITEMS(s)

- grid-column
  - grid-column-start
  - grid-column-end
- grid-row
  - grid-row-start
  - grid-row-end
- grid-area

... e mais 2 propriedades de **alinhamentos**

## GRID ALINHAMENTO

Existem 6 propriedades para alinhamentos:
1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

Vamos separá-los em 2 grupos:
1. `justify` e `align`
2. `content`, `items` e `self`


---

## Justify e Align

Sabend que o grid é bidimensional, nós temos o eixo **X** e **Y**

O eixo **X** é o posicionalmento horizontal, da esquerda para a direita

O eixo **Y** é o posicionalmento vertical, de cima para baixo

---

## Content, Items e self

Juntando o `justify`, ou `align`, com esses elementos: `content`, `items` e `self`; Nós observamos nossas propriedades.

---

### Content

`justify-content` e `align-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

O uso dessas propriedades são raras, pois só é aplicado caso o grid seja menor que a área definida.
(Por exemplo, quando usamos em px o tamanho do grid, poderemos terminar com um grid pequeno, para o temanho da área total do grid.)

Podemos usar **7 valores**
1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. space-evenly

--- 

### Items

`justify-items` e `align-items` vai permitir alinhar os items do nosso grid, em qualquer espaço disponível, na cédula em que ele habitar.

Podemos usar **4 valores**
1. start
2. end
3. center
4. stretch

---

### Self

`justify-self` e `align-self` vai nos permitir alinhar o item em si.

Faz a mesma coisa que o `justify-items` e `align-items`, porém, aplicado diretamente no item de um grid.

--- 

### Link para estudos:

* [Rocketseat - Youtube](https://youtu.be/HN1UjzRSdBk)
