# Posicionamento Relativo e Absoluto dos Elementos

## Posicionamento Estático
- Diz respeito ao fluxo normal do documento;
- Se tentarmos aplicar algum posicionamento, este será apenas ignorado;
- Por padrão, todo elemento está posicionado estaticamente.

## Posicionamento Relativo
- O elemento é posicionado em relação à sua posição original no documento;
- O elemento não é tirado do fluxo normal do documento;
Ex.
```css
p{
    position:relative;
    top:50px;
    left:50px;
}
```

- Importante frizar que quando usamos essas referências de posições "top/bottom/left/right", não estamos dizendo para onde ir, mas sim a distância em relação à posição original do elemento. Assim, no exemplo acima, o elemento será posicionado à 50px do topo em relação aonde ele estava(ou seja, ele irá para baixo) e à 50px da esquerda em relação aonde ele estava(ou seja, ele irá para a direita).

Exemplo(execute em sua máquina para visualizar):
[exemplo](exemplo-posicionamento-relativo.html)

## Posicionamento Absoluto
- Todo elemento com posicionamento absoluto irá usar como referência o último elemento não absoluto(ou seja, o último relativo): por padrão, a tag html tem posicionamento relativo;
- O elemento é tirado do fluxo do documento;

Ex.
```css
p{
    position:absolute;
    top:50px;
    left:50px;
}
```
- Da mesma forma que na relativa, entendemos que o elemento se posiciona à 50px do topo do elemento relativo mais próximo e à 50px da esquerda do elemento relativo mais próximo.

Exemplo(execute em sua máquina para visualizar):
[exemplo](exemplo-posicionamento-absoluto.html)