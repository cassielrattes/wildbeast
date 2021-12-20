# CSS GRID-LAYOUT - [ORIGAMID](https://www.origamid.com/)

> # GRID CONTAINER
>
> O Grid Container é a tag que envolve os itens GRID, ao indicar display: grid, essa tag passa a ser um Grid Container.

<br/>

- **[display:](https://codepen.io/origamid/pen/NgzWBo)** Define o elemento como um grid container.

- **[grid-template-columns:](https://codepen.io/origamid/pen/ZyRYQp)** Define o número total de colunas que serão criadas no grid.

- **[grid-template-rows:](https://codepen.io/origamid/pen/gRKpow)** Define a quantidade de linhas no grid.

- **[grid-template-areas:](https://codepen.io/origamid/pen/owyjxz)** Define áreas específicas no grid. O ponto (.) pode ser utilizado para criar áreas vazias.

- **[grid-template:](https://codepen.io/origamid/pen/NgzGOJ)** Atalho para definir grid-template-columns, grid-template-rows e grid-template-areas.

- **[gap:](https://codepen.io/origamid/pen/ZyRQLB)** Define o gap (gutter) entre os elementos do grid.

- **[grid-auto-columns:](https://codepen.io/origamid/pen/RgJrLv)** Define o tamanho das colunas do grid implicito (gerado automaticamente, quando algum elemento é posicionado em uma coluna que não foi definida).

- **[grid-auto-rows:](https://codepen.io/origamid/pen/mwKPYR)** Define o tamanho das linhas do grid implicito (gerado automaticamente, quando algum elemento é posicionado em uma linha que não foi definida).

- **[grid-auto-flow:](https://codepen.io/origamid/pen/LLrZpN)** Define o fluxo dos itens no grid. Se eles vão automaticamente gerar novas linhas ou colunas.

- **[grid:](https://codepen.io/origamid/pen/RgJRLL)** Atalho geral para definir o grid: grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns e grid-auto-flow

- **[justify-content:](https://codepen.io/origamid/pen/OgERge)** Justifica os itens do grid em relação ao eixo x (horizontal).

- **[align-content:](https://codepen.io/origamid/pen/NgzRmr)** Alinhas os itens do grid em relação ao eixo y (vertical).

- **[justify-items:](https://codepen.io/origamid/pen/XgYNgx)** Justifica o conteúdo dos itens do grid em relação ao eixo x (horizontal). Justifica em relação a célula.

- **[align-items:](https://codepen.io/origamid/pen/vZryMX)** Alinha o conteúdo dos itens do grid em relação ao eixo y (vertical). Alinha em relação a célula.

<br/>

> # GRID ITEM
>
> Os Grid Itens são os filhos do Grid Container. Um grid item pode ser explicito ou implicito. Explicito é quanto você define ele explicitamente no container e implicito é quanto ele é criado automaticamente para preencher o conteúdo no grid.

<br/>

- **[grid-column:](https://codepen.io/origamid/pen/JJZVNr)** Define quais colunas serão ocupadas pelo grid item. É possível definir uma linha de início e final, assim o item irá ocupar múltiplas colunas.

- **[grid-row:](https://codepen.io/origamid/pen/dRKBKv)** Define quais linhas serão ocupadas pelo grid item. Atenção aqui, pois essa linha é referente a row. Porém as chamadas grid lines que por tradução também significam linhas do grid, são diferentes. Uma row (linha), possui sempre 2 grid lines (linhas do grid), uma no início dela e uma no final dela.

- **[grid-area:](https://codepen.io/origamid/pen/eRKwaN)** Define a área do item do grid. É um atalho para grid-row-start, grid-column-start, grid-row-end, grid-column-end. O z-index pode ser utilizado para manipular a posição no eixo Z do item. Ou seja, se um item for posicionado em cima de outro, o z-index controla qual vêm na frente.

- **[justify-self:](https://codepen.io/origamid/pen/yXqBJo)** Justifica o item do grid em relação ao eixo x (horizontal). Justifica em relação a célula.

- **[align-self:](https://codepen.io/origamid/pen/EXpYKR)** Justifica o item do grid em relação ao eixo y (vertical). Justifica em relação a célula.
