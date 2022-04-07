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