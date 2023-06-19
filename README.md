# Get started CSS

![GitHub repo size](https://img.shields.io/github/repo-size/alexandrekatsuura/get-started-css?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/alexandrekatsuura/get-started-css?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/alexandrekatsuura/get-started-css?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/alexandrekatsuura/get-started-css?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/alexandrekatsuura/get-started-css?style=for-the-badge)

[get-started-html]: https://github.com/alexandrekatsuura/get-started-html

## Descrição
> CSS é uma linguagem de estilo utilizada para controlar a aparência e o layout dos elementos em um documento HTML

## Pré-requisitos
Antes de começar, verifique se você atendeu aos seguintes requisitos:
* Conhecimento básico em HTML [get-started-html][get-started-html] **|** 

## Conceitos importantes
### Seletores
> Os seletores CSS são usados para selecionar elementos HTML aos quais você deseja aplicar estilos.

### Propriedades e valores
> As propriedades CSS são usadas para definir os estilos que você deseja aplicar a um elemento selecionado. Cada propriedade tem um valor associado que define como o estilo deve ser aplicado.

### Box model
> O modelo de caixa é um conceito fundamental no CSS que descreve como os elementos HTML são renderizados como caixas retangulares.

### Posicionamento
> O posicionamento no CSS determina como os elementos são dispostos em relação a outros elementos na página.

### Layout
> O CSS oferece várias técnicas de layout para controlar o posicionamento e a organização dos elementos em uma página.

### Responsividade
> O design responsivo é a prática de criar layouts que se adaptam a diferentes tamanhos de tela e dispositivos.

### Transições e animações
> O CSS permite animar elementos e aplicar transições suaves entre diferentes estados.

## Modo de utilização
* Incorporando CSS em um arquivo HTML
* Usando um atributo style diretamente em um elemento HTML
* Usando um arquivo separado .css

## Exemplo incorporando CSS em um arquivo HTML
```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <title>Exemplo incorporando css</title>
    <style>
        /* Regras CSS aqui */
        h1 {
            color: blue;
            font-size: 24px;
        }
        
        p {
            color: red;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <h1>Título</h1>
    <p>Parágrafo de exemplo.</p>
</body>
</html>
```

## Exemplo usando um atributo style diretamente em um elemento HTML
```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <title>Style em elemento</title>
</head>
<body>
    <h1 style="color: blue; font-size: 24px;">Título</h1>
    <p style="color: red; font-size: 16px;">Parágrafo de exemplo.</p>
</body>
</html>
```

## Exemplo usando um arquivo separado .css
* .css
```
/* estilos.css */

/* Estilizando o título */
h1 {
    color: blue;
    font-size: 24px;
}

/* Estilizando parágrafos */
p {
    color: red;
    font-size: 16px;
}
```

* .html
```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <title>Arquivo separado .css</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <h1>Título</h1>
    <p>Parágrafo de exemplo.</p>
</body>
</html>
```

## Exemplo seletores (elemento)
> Aplica em todos os elementos `<p>`
```
p {
    color: blue;
    font-size: 16px;
}
```

## Exemplo seletores (classe)
> Aplica em todos elementos que possuem a classe `div-yellow`
```
.div-yellow {
    background-color: yellow;
    height: 200px;
    width: 200px;
}
```

## Exemplo seletores (ID)
> Aplica no elemento que possui o id `container-id`
```
#container-id {
    background-color: red;
    width: 200px;
    height: 200px;
}
```

## Exemplo seletores (descendente)
> Aplica no elemento `<p>` dentro de um elemento `<div>`
```
div p {
    font-size: 16px;
}
```

## Exemplo seletores (atributo)
> Aplica em todos os links com `href` igual a "https://www.exemplo.com"
```
a[href="https://www.exemplo.com"] {
    color: green;
}
```

## Exemplo seletores (pseudo-classe)
> Aplica quando um link `<a>` é hovered (mouse sobre ele)
```
a:hover {
    text-decoration: underline;
}
```

## Exemplo propriedades e valores (color)
> Aplica cor de texto do elemento como azul
```
h1 {
    color: blue;
}
```

## Exemplo propriedades e valores (font-size)
> Aplica tamanho de texto do elemento como 16px
```
p {
    font-size: 16px;
}
```

## Exemplo propriedades e valores (background-color)
> Aplica cor de fundo como amarelo
```
div {
    background-color: yellow;
}
```

## Exemplo propriedades e valores (width)
> Aplica a largura do elemento como 300px
```
img {
    width: 300px;
}
```

## Exemplo propriedades e valores (margin)
> Aplica margem de 10px
```
p {
    margin: 10px;
}
```

## Exemplo propriedades e valores (padding)
> Aplica um preenchimento interno de 20px
```
div {
    padding: 20px;
}
```

## Exemplo propriedades e valores (border)
> Aplica uma borda solida de 1px
```
div {
    border: 1px solid black;
}
```

## Exemplo box model (width e height)
> Aplica largura 200px e altura 150px
```
div {
    width: 200px;
    height: 150px;
}
```

## Exemplo box model (padding e background-color)
> Aplica preenchimento interno de 20px e cor de fundo cinza claro
```
div {
    padding: 20px;
    background-color: lightgray;
}
```

## Exemplo box model (border)
> Aplica borda preta de 1px solida
```
div {
    border: 1px solid black;
}
```

## Exemplo box model (margin)
> Aplica margen de 10px
```
div {
    margin: 10px;
}
```

## Exemplo box model (box-sizing)
> Faz com que seja considerado a borda no cálculo da largura e altura, em vez de ser adicionado aos valores especificados para width e height
```
div {
    box-sizing: border-box;
}
```




