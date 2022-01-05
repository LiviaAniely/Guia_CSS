# Consultas de Mídia/Media Queries
- Permite ajustar o site para diferentes tipos de telas, de acordo com os diferentes dispositivos;
- Geralmente, tratamos de dimensão de largura da tela, mas também podemos usar outras características.
- Sintaxe:

```css
@media (tipo de mídia) (recurso de mída/feature media){

    regras css
}
```

Recursos de mídia mais comuns:
- max-width = largura máxima
- min-width = largura mínima
- orientation(orientação da tela):portrait(retrato)/landscape(paisagem)
Tipos de mídia:
- screen = tela
- print= usada para imprimir uma página

- Tanto recursos quanto tipos de mídia são opcionais, você pode usar apenas um deles que é válido

- Também é possível usar operadores lógicos para unir recursos de mídia:
1. E: and
2. OU: ,
3. NÃO: not

Ex.

```css
@media screen (min-width:800px){
    ...
}

@media(min-width:801px) and (max-width:1000px){

}
```

obs: os intervalos são fechados, assim se min-width:800px, então o 800px está incluso.

Exemplo(execute em sua máquina para visualizar, teste diminuir a tela para ver a diferença):
[exemplo](exemplo.html)