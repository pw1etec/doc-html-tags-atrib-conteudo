# Explicação Teórica sobre HTML

Este repositório contém a explicação teórica sobre o **HTML** (Hypertext Markup Language), incluindo a estrutura mínima de um documento HTML, o uso de **tags**, **atributos** e **conteúdo**.

## Estrutura Mínima de um Documento HTML

Um documento HTML básico começa com uma declaração de tipo de documento (DOCTYPE) e é composto pelas seguintes partes principais:

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título da Página</title>
  </head>
  <body>
    <h1>Bem-vindo ao HTML</h1>
    <p>Este é um exemplo de documento HTML mínimo.</p>
  </body>
</html>
```

### Explicação:

1. `<!DOCTYPE html>`: Declaração do tipo de documento, informando ao navegador que o conteúdo está escrito em HTML5.
2. `<html lang="pt-br">`: Elemento raiz do HTML, com o atributo `lang` indicando o idioma da página (português brasileiro).
3. `<head>`: Contém metadados sobre o documento, como o charset e o título da página.
4. `<meta charset="UTF-8">`: Define a codificação de caracteres como UTF-8, garantindo a compatibilidade com caracteres especiais.
5. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Torna a página responsiva em dispositivos móveis.
6. `<title>`: Define o título da página, exibido na aba do navegador.
7. `<body>`: Contém o conteúdo visível da página, como textos, imagens e links.

---

## 🔤 **Tags HTML mais comuns para iniciantes**

### ✍️ **Conteúdo e texto**

| Tag             | Uso                        | Exemplo                           |
| --------------- | -------------------------- | --------------------------------- |
| `<h1>` a `<h6>` | Títulos e subtítulos       | `<h1>Título</h1>`                 |
| `<p>`           | Parágrafo de texto         | `<p>Texto aqui.</p>`              |
| `<br>`          | Quebra de linha            | `Primeira linha<br>Segunda linha` |
| `<hr>`          | Linha horizontal/divisória | `<hr>`                            |

---

### 📌 **Listas**

| Tag    | Uso                    | Exemplo                  |
| ------ | ---------------------- | ------------------------ |
| `<ul>` | Lista **não ordenada** | `<ul><li>Item</li></ul>` |
| `<ol>` | Lista **ordenada**     | `<ol><li>Item</li></ol>` |
| `<li>` | Item da lista          | `<li>Elemento</li>`      |

---

### 🔗 **Links e mídia**

| Tag       | Uso               | Exemplo                                     |
| --------- | ----------------- | ------------------------------------------- |
| `<a>`     | Link (âncora)     | `<a href="https://...">Clique</a>`          |
| `<img>`   | Imagem            | `<img src="logo.png" alt="Logo">`           |
| `<video>` | Vídeo incorporado | `<video controls src="video.mp4"></video>`  |
| `<audio>` | Áudio incorporado | `<audio controls src="musica.mp3"></audio>` |

---

### 🧱 **Organização de layout**

| Tag         | Uso                                | Exemplo                                   |
| ----------- | ---------------------------------- | ----------------------------------------- |
| `<div>`     | Container genérico                 | `<div>Conteúdo</div>`                     |
| `<span>`    | Container inline (dentro do texto) | `<span style="color:red">vermelho</span>` |
| `<section>` | Seção de conteúdo                  | `<section><h2>Blog</h2></section>`        |
| `<article>` | Conteúdo independente (como post)  | `<article>...</article>`                  |
| `<header>`  | Cabeçalho da página ou seção       | `<header>Menu</header>`                   |
| `<footer>`  | Rodapé da página                   | `<footer>© 2025</footer>`                 |
| `<nav>`     | Navegação (menu)                   | `<nav><a href="#">Home</a></nav>`         |
| `<main>`    | Conteúdo principal da página       | `<main>Principal</main>`                  |

---

### 📋 **Formulários (básico)**

| Tag                     | Uso                  | Exemplo                                   |
| ----------------------- | -------------------- | ----------------------------------------- |
| `<form>`                | Formulário           | `<form action="">...</form>`              |
| `<input>`               | Campo de entrada     | `<input type="text">`                     |
| `<label>`               | Rótulo para campo    | `<label for="nome">Nome</label>`          |
| `<textarea>`            | Campo de texto maior | `<textarea></textarea>`                   |
| `<button>`              | Botão de ação        | `<button>Enviar</button>`                 |
| `<select>` / `<option>` | Menu suspenso        | `<select><option>Opção</option></select>` |

---


Exemplo de uso de tags:

```html
<h1>Este é um título principal</h1>
<p>Este é um parágrafo de texto explicativo.</p>
<a href="https://www.exemplo.com">Clique aqui para visitar o site</a>
```

## Atributos HTML

Os **atributos** são usados dentro das tags para fornecer informações adicionais sobre um elemento. Alguns atributos comuns são:

- `href`: Usado em links (`<a href="url">`).
- `src`: Usado para especificar o caminho de uma imagem (`<img src="imagem.jpg">`).
- `alt`: Descrição alternativa de uma imagem (importante para acessibilidade).
- `id`: Identificador único para um elemento.
- `class`: Classe usada para agrupar elementos com características semelhantes.
- `style`: Definição de estilos diretamente na tag.

Exemplo de uso de atributos:

```html
<a href="https://www.exemplo.com" target="_blank">Clique para abrir em uma nova aba</a>
<img src="imagem.jpg" alt="Descrição da imagem" />
<div id="container" class="conteudo"></div>
```

## Conteúdo HTML

O conteúdo de um documento HTML é tudo o que é colocado entre as tags de abertura e fechamento. Ele pode incluir texto, imagens, links, vídeos e outros tipos de mídia, além de elementos de estruturação e formatação.

Exemplo de conteúdo:

```html
<p>Este é um parágrafo de texto.</p>
<a href="https://www.exemplo.com">Visite o site</a>
<img src="imagem.jpg" alt="Imagem exemplo">
```

## Conclusão

Este guia básico sobre HTML fornece a fundação necessária para entender como os documentos HTML são estruturados, como as tags e atributos funcionam e como podemos criar conteúdo web interativo e acessível. A partir daqui, você pode começar a explorar mais sobre HTML e seus recursos para criar páginas mais complexas.

---

> **Nota**: HTML é uma linguagem de marcação, o que significa que sua principal função é estruturar o conteúdo da página. Para adicionar estilos e interatividade, você precisará aprender sobre CSS e JavaScript.

