# CSS_Grid_na_prática
 
# grid

- Bidmensional
- Divisão de toda a página em linhas e colunas
- Colocar elementos onde quiser nessa divisão

---
# Grid ou Flexbox

- grid: Duas dimensões (Colunas e linhas)
- Flexbox : Uma dimensão (ou coluna ou linha) 
- uma completa o trabalho da outra
- Verificar quais navegadores ainda não estão aceitando o grid 

---
## Propriedades

Vamos separar em 2 grupos:
`container` e `item(s)` 
---
### Container

- display:grid;/*Inicia o grid*/
- grid-template-columns;/*fatia as colunas, falando quantas colunas o grid possui*/
- grid-template-rows;/*quantas linhas*/
- grid-gap /*fala sobre espaçamento*/
  -grid-row-gap
  -grid-column-gap
-grid-template-areas;/*delimita areas*/

... e masi 4 propriedades e **alinhamento**

---
## item(S)

-grid-column
    -grid-column-start
    -grid-column-end
-grid-row
    -grid-row-start
    -grid-row-end
-grid-area

... e masi 2 propriedades e **alinhamento**


---
# Grid: Alinhamento

-Existem 6 propriedades para alinhamento:
`justify-content`
`aling-content`
`justify-items`
`align-items`
`justify-self`
`align-self`

-Vamos separá-los em 2 grupos
`justify` e `align`
`content`, `items` e `self`

## Justify e Align

--Sabendo que o grid é bidimensional, nós temos o eixo x e o y.

    O **eixo x** é o posicionamento horizontal, da esquerda para a direita.
    o **eixo y** é o posicionamento vertical, de cima para baixo 

---

## Content, Items e Self

Juntando o `justify`, `align`, com esses elementos: `content`, `items` e `self`; nós observamos nossas propriedades

---

## Content

`justify-content` e `aling-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid


o uso dessas propriedades são raras, pois só é aplicado caso o grid seja menor que a area definida (por exemplo, quando usamos em px o tamanho do, poderemos terminar com um grid pequeno, para o tamanho da area do grid)

Podemos usar **7 valores**;
1. start 
2. end
3. center
4. steatch
5. space-between
6. space-around
7. space evenly


---

### items

`justify-items` e `aling-items` vai permitir alinhar os items do nosso grid, em qualquer espaço disponivel, na cèlula que ele habitar.

Podemos usar **4 valores**;
1. start 
2. end
3. center
4. steatch

---

### Self

`justify-self` e `align-self` vai nos permitir alinhar o item em si.

faz a mesma coisa do `justify-items` e `align-items`, porém, aplicado diretamente no item de um grid 