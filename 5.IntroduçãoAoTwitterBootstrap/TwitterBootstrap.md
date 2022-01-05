# Twitter Bootstrap
- É o framework para html, css e javascript mais famoso, serve para o desenvolvimento de projetos responsivos;
- Consiste de códigos pré-prontos para design;
- Planejar a versão mobile antes ou depois da versão desktop?
    Recomenda-se planejar para mobile primeiro, porém, é uma escolha tanto quando pessoal.

## Sistema de grades no bootstrap

<img src = exemplo-de-grid-e-colunas-bootstrap.jpg width = 400px height= 250px>

```html
<header class = "container"> (1*)
    <nav class = "row"> (2*) /*linha que "guardará as colunas"*/

        <div class = "col-lg-4">Coluna 1</div>
        <div class = "col-lg-4">Coluna 2</div>
        <div class = "col-lg-4">Coluna 3</div>

    </nav>
</header>
``` 
1. 1*: deve conter uma classe conteiner ou conteiner-fluid:

    conteiner: tem largura fixa pré-determinada que ainda é responsivo com base na largura do navegador;
    conteiner-fluid: estende o layout e toda a largura do navegador e fornece preenchimento  consistente em torno de sua grade e outros conteúdos;
2. 2*: cria grupos horizontas de colunas, o que significa que as colunas colapsam e interagem umas com as outras como um grupo, mas independentes de colunas de outras linhas.

obs. as tags header e nav podem ser divs, porém recomenda-se essas para dar mais sentido semanticamente à leitura do código.

### Classe de colunas

sintaxe:
    col-tamanho da tela(3*)-span(4* divisão)

3. 3*:pode ser lg(largo), md(médio), consultar página do bootstrap para verificar as larguras exatas que correspondem a essas medidas;
4. 4*: de acordo com a grid de 12 colunas

Exemplo(execute em sua máquina para visualizar):
[exemplo](exemplo.html)

