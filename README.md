# Projeto Open Source: HTML Básico

Este projeto tem como objetivo ensinar e explorar os fundamentos do **HTML (HyperText Markup Language)**, a linguagem utilizada para estruturar páginas na web. Ele organiza o conteúdo por meio de **tags**, que indicam ao navegador como cada parte deve ser exibida.

## Estrutura do HTML

Um documento HTML começa com a tag `<html>`, que envolve todo o conteúdo da página. Dentro dela, temos duas partes principais:

- `<head>`: contém informações que não aparecem diretamente para o usuário, como o título da página (`<title>`), links para estilos (CSS) e scripts (JavaScript).
- `<body>`: guarda todo o conteúdo visível, como textos, imagens e links.

## Principais Tags

`<h1>` até `<h6>`: títulos e subtítulos, do maior ao menor.  
`<p>`: define parágrafos de texto.  
`<a>`: cria links para outras páginas ou sites.  
`<img>`: insere imagens, usando atributos como `src` (caminho da imagem) e `alt` (descrição).  
`<ul>` e `<ol>`: listas não ordenadas (com marcadores) e ordenadas (numeradas), acompanhadas de `<li>` para cada item.  
`<div>`: divisão de conteúdo em blocos.  
`<span>`: usado para destacar ou estilizar trechos específicos dentro de um texto.  

## Exemplo de Página HTML

```html
<!DOCTYPE html>
<html>
<head>
  <title>Projeto Open Source</title>
</head>
<body>
  <h1>Bem-vindo ao Projeto!</h1>
  <p>Este é um exemplo de página HTML.</p>
  <a href="https://github.com">Visite o GitHub</a>
</body>
</html>


----

# Projeto Open Source: CSS Básico

Este projeto tem como objetivo ensinar e explorar os fundamentos do **CSS (Cascading Style Sheets)**, a linguagem utilizada para estilizar páginas na web. Enquanto o HTML organiza o conteúdo, o CSS é responsável por definir a aparência visual, como cores, fontes, espaçamento e layout.

## Estrutura do CSS

O CSS pode ser aplicado de três formas principais:

- **Inline**: diretamente dentro da tag HTML, usando o atributo `style`.  
  Exemplo: `<p style="color:blue;">Texto azul</p>`

- **Interno**: dentro da tag `<style>` no cabeçalho (`<head>`) do documento HTML.  
  Exemplo:
  ```html
  <style>
    p { color: blue; }
  </style>
  ```

- **Externo**: em um arquivo separado (`.css`), vinculado ao HTML com a tag `<link>`.  
  Exemplo:
  ```html
  <link rel="stylesheet" href="style.css">
  ```

## Principais Propriedades do CSS

- `color`: define a cor do texto.  
- `background-color`: define a cor de fundo de um elemento.  
- `font-size`: controla o tamanho da fonte.  
- `font-family`: escolhe o tipo de fonte.  
- `margin`: espaço externo ao redor do elemento.  
- `padding`: espaço interno entre o conteúdo e a borda do elemento.  
- `border`: define bordas (espessura, estilo e cor).  
- `width` e `height`: controlam largura e altura.  
- `display`: define como o elemento será exibido (ex.: `block`, `inline`, `flex`).  
- `position`: controla o posicionamento (`static`, `relative`, `absolute`, `fixed`).  

## Exemplo de CSS aplicado

```html
<!DOCTYPE html>
<html>
<head>
  <title>Projeto CSS</title>
  <style>
    body {
      background-color: #f0f0f0;
      font-family: Arial, sans-serif;
    }
    h1 {
      color: darkblue;
      text-align: center;
    }
    p {
      color: gray;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <h1>Bem-vindo ao Projeto CSS!</h1>
  <p>Este é um exemplo de estilização com CSS.</p>
</body>
</html>
```

## Como colaborar

Além de abrir *Issues* e enviar *Pull Requests*, você pode contribuir criando exemplos práticos de HTML e CSS.  

### Exemplos sugeridos

- Criar uma página simples em HTML com títulos, parágrafos e imagens.  
- Usar CSS para mudar cores, fontes e alinhar elementos.  
- Experimentar com listas (`<ul>` e `<ol>`) e aplicar estilos diferentes.  
- Criar um layout básico usando `div` e propriedades como `margin`, `padding` e `border`.  
- Testar estilizações com `hover` em links (`a:hover`) para mostrar interatividade.  

---

👉 Assim, cada colaborador pode criar e enviar seus próprios exemplos de HTML e CSS, enriquecendo o repositório com práticas reais.






