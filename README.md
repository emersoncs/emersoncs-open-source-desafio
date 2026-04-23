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

Assim, cada colaborador pode criar e enviar seus próprios exemplos de HTML e CSS, enriquecendo o repositório com práticas reais.

## ⚠️ Importante sobre o Web Editor (github.dev)

Este projeto está sendo desenvolvido diretamente no **web editor do GitHub** (`github.dev`), que é uma versão simplificada do VS Code no navegador.

- ✅ Permite criar, editar e excluir arquivos.
- ✅ Permite fazer commits e sincronizar com o repositório.
- ❌ **Não possui terminal integrado** (não é possível rodar comandos `git`, `npm`, `python`, etc).
- ❌ Não é possível executar scripts diretamente dentro do editor.

👉 Se precisar rodar comandos de terminal, existem duas alternativas:
1. Usar **GitHub Codespaces**, que abre um ambiente completo com terminal.
2. Clonar o repositório na sua máquina e usar o terminal local.

Para este projeto, todo o trabalho será feito **diretamente no GitHub**, sem Codespaces e sem terminal local.

## ⚙️ Usando o Web Editor do GitHub (github.dev)

Este projeto está sendo desenvolvido diretamente no **web editor do GitHub** (`github.dev`), que é uma versão simplificada do VS Code no navegador.

### O que dá para fazer
- ✅ Criar, editar e excluir arquivos e pastas.
- ✅ Visualizar mudanças nos arquivos.
- ✅ Realizar **commits diretamente pelo Source Control** (ícone de ramificação na barra lateral esquerda).
- ✅ Sincronizar alterações com o repositório no GitHub.

### O que significam os marcadores
- **A** → *Added*: arquivo novo criado, mas ainda não commitado.
- **M** → *Modified*: arquivo existente que foi alterado.
- **D** → *Deleted*: arquivo marcado para exclusão.

### Como realizar um commit no web editor
1. Clique no ícone de **Source Control** na barra lateral esquerda.  
2. Selecione os arquivos modificados (ex.: `style.css` com o marcador **A**).  
3. Clique em **Stage Changes** para preparar os arquivos.  
4. Escreva uma mensagem de commit clara, por exemplo:  
5. Clique em **Commit**.  
6. Clique em **Sync Changes** para enviar ao GitHub.

👉 Assim, não é necessário sair do web editor para fazer commits. Todo o fluxo pode ser feito dentro do próprio editor.

## 📂 Estrutura de Pastas

Para manter a organização do projeto, cada pasta criada deve conter **apenas dois arquivos principais**:

- Um arquivo **HTML** (responsável pela estrutura e conteúdo da página).
- Um arquivo **CSS** (responsável pela formatação e estilo da página).

### Exemplo:
exemplo(x)/ = x representará o número da pasta seguindo a sequência em ordem crescente (2,3,4,etc.)

│── exemplo(x).html
│── style.css


⚠️ Importante:
- O arquivo HTML deve estar **linkado ao CSS** usando a tag `<link>` dentro do `<head>`.
- Não devem existir múltiplos arquivos HTML ou CSS dentro da mesma pasta.  
- Cada pasta representa um exemplo independente, com seu próprio HTML e CSS.

## Visualizando HTML + CSS criados no Web Editor

O **web editor do GitHub (github.dev)** permite criar e editar arquivos, mas **não possui terminal integrado** e **não executa HTML/CSS diretamente**. Para ver a estilização aplicada, é necessário abrir o arquivo HTML em um navegador.

### Como visualizar
Existem três formas principais:

1. **Baixar o repositório**
   - Clique em **Code → Download ZIP** no GitHub.
   - Extraia o arquivo no seu computador.
   - Dê dois cliques em `exemplo1.html` → ele abre no navegador e carrega o `style.css`.

2. **Clonar com Git**
   - Se tiver Git instalado, rode:
     ```bash
     git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
     ```
   - Entre na pasta e abra o `exemplo1.html` no navegador.

3. **Publicar com GitHub Pages**
   - Vá em **Settings → Pages** no repositório.
   - Configure a branch `main` e a pasta `/root` ou `/docs`.
   - O GitHub gera um link público (ex.: `https://seuusuario.github.io/seurepositorio/exemplos/exemplo1.html`).
   - Acesse esse link no navegador para ver o HTML estilizado.

⚠️ Importante:
- Cada pasta criada deve conter **apenas um arquivo HTML e um CSS**.  
- O HTML deve estar **linkado ao CSS** usando:
  ```html
  <link rel="stylesheet" href="style.css">

## Visualizando HTML + CSS criados no Web Editor

O **web editor do GitHub (github.dev)** permite criar e editar arquivos, mas **não possui terminal integrado** e **não executa HTML/CSS diretamente**. Para ver a estilização aplicada, é necessário abrir o arquivo HTML em um navegador.

### Como visualizar
Existem três formas principais:

1. **Baixar o repositório**
   - Clique em **Code → Download ZIP** no GitHub.
   - Extraia o arquivo no seu computador.
   - Dê dois cliques em `exemplo1.html` → ele abre no navegador e carrega o `style.css`.

2. **Clonar com Git**
   - Se tiver Git instalado, rode:
     ```bash
     git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
     ```
   - Entre na pasta e abra o `exemplo1.html` no navegador.

3. **Publicar com GitHub Pages**
   - Vá em **Settings → Pages** no repositório.
   - Configure a branch `main` e a pasta `/root` ou `/docs`.
   - O GitHub gera um link público (ex.: `https://seuusuario.github.io/seurepositorio/exemplos/exemplo1.html`).
   - Acesse esse link no navegador para ver o HTML estilizado.

⚠️ Importante:
- Cada pasta criada deve conter **apenas um arquivo HTML e um CSS**.  
- O HTML deve estar **linkado ao CSS** usando:
  ```html
  <link rel="stylesheet" href="style.css">
