# Tutorial Markdown

Comandos aprendidos durante a aula de Markdown.

## Comentário

Semelhante aos comentários em linguagens de programação, coloque o texto desejado entre "<>". <br>

< Comentario > Mas lembre-se do espaçamento. Abra o arquivo para edição para visualizar.

<Comentario Exemplo>
<Comentario>

## Headers

Semelhantes aos headers vistos em HTML, porém basta colocar a quantidade de "#" referente ao tamanho para definir, quanto mais "#" menor fica.

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Dividers

Use "---" ou "***"

---


***

## Enfâse

*Coloque entre asteríscos para dar enfâse*

## Strong

**Coloque entre dois asteriscos**

## Itálico

_Coloque entre dois underscores/underlines_

## Quebra de linha

Coloque "br" entre < > <br> <br> <br> <br> <br>
Pode colocar vários caso necessário.
 
## Lista ordenada

1. Item 1
2. Item 2
3. Item 3
   1. Item 3.1
   2. Item 3.2
4. Item 4

Basta colocar "Número." antes do item, usando espaçamento de TAB para fazer os sub-itens

## Lista não ordenada

- Item 1
- Item 2
* Item 3
  * Item 3.1
  * Item 3.2
* Item 4

Basta colocar um asterisco ou traço ( - ) e um espaço, usando espaçamento de TAB para fazer sub-itens

## Lista com checkbox

- [ ] Item 1
- [X] Item 2 
- [ ] Item 3
  - [ ] Item 3.1
  - [X] Item 3.2
- [x] Item 4

---

1. [x] Item 1
2. [ ] Item 2
3. [x] Item 3

Crie uma lista, ordenada ou não, e coloque [ ] antes dos itens, daí basta preencher com X

## Citação

> Citação 
> > Citação aninhada

Coloque o sinal >, caso queira aninhar repita-o >>.

## Inline code

`git add .` <br>
`git commit -m "Criação de Branch e registro de aula Markdown`

Coloque a linha entre entre dois `

## Code block

```solidity
contract HelloWorld {
    string public message = "Hello World!";

    function helloWorld() public view returns (string memory) {
        return message;
    }
}
```

Coloque o bloco de código entre dois **```**, dependendo da plataforma que está renderizando o markdown, caso coloque o nome da linguagem após as três crases terá um efeito de syntax highlight, neste exemplo é um código solidity.

## Tabelas

| Nome | Data |
| ----- | ---------- |
| Teste | 23/04/2024 |
| ABCDE | 22/04/2024 |

## Links

[Link para o github](https://github.com/)

Coloque o texto entre [] e logo depois coloque o link entre ()

## Imagem

Coloque o texto dentro de ![], e depois () com o caminho/link. Neste caso é uma imagem local, mas não precisa ser necessariamente.

![Logo do github local](./imagens/github-logo.png)

## Funcionalidade do Github

Ao enviar um arquivo Markdown para o github, é possível colocarmos emojis, mas lembre-se que isso é uma característica da plataforma e não necessariamente do Markdown em si. <br>
Exemplos: :smiley: :blush: :star_struck: