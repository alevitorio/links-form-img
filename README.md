# 🌐 Desenvolvimento Web - Teoria

Este documento contém conceitos fundamentais sobre elementos essenciais da Web, abordando texto, hyperlinks, imagens, vetores SVG, conteúdos embutidos, tabelas e formulários.

## 📝 Texto e Hyperlinks

O HTML permite estruturar o conteúdo textual de uma página com diversas tags:

- **`<p>`**: 📝 Define um parágrafo, usado para estruturar blocos de texto.
- **`<h1>` - `<h6>`**: 🏷️ Definem títulos de diferentes níveis, sendo `<h1>` o mais importante e `<h6>` o menos importante.
- **`<strong>`** e **`<em>`**: 🔠 Destacam textos em negrito e itálico, respectivamente, para dar ênfase.
- **`<a href="URL">`**: 🔗 Cria um hyperlink para outra página ou recurso externo.

Exemplo de um hyperlink:

```html
<a href="https://www.example.com">Visite o site</a>
```

## 🖼️ Imagens, Vetores SVG e Outros Conteúdos Embutidos

As imagens e outros recursos multimídia são essenciais para a Web:

- **`<img>`**: 🖼️ Insere imagens na página, podendo incluir atributos como `alt` para acessibilidade.
- **`<svg>`**: 📐 Define gráficos vetoriais escaláveis que não perdem qualidade ao serem redimensionados.
- **`<iframe>`**: 🎥 Embute conteúdos de outras páginas, como vídeos do YouTube ou mapas interativos.

Exemplo de imagem:

```html
<img src="imagem.jpg" alt="Descrição da imagem">
```

Exemplo de SVG:

```html
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
</svg>
```

## 📊 Tabelas

As tabelas são usadas para exibir dados tabulares de maneira organizada:

- **`<table>`**: 📋 Define uma tabela.
- **`<tr>`**: ➡️ Define uma linha dentro da tabela.
- **`<th>`**: 🔠 Define uma célula de cabeçalho, geralmente usada para indicar títulos das colunas.
- **`<td>`**: 📦 Define uma célula de dados dentro de uma linha.

Exemplo de tabela:

```html
<table border="1">
  <tr>
    <th>Nome</th>
    <th>Idade</th>
  </tr>
  <tr>
    <td>Ana</td>
    <td>25</td>
  </tr>
</table>
```

## 📝 Formulários

Os formulários permitem a interação do usuário com a página, permitindo entradas de dados:

- **`<form>`**: 📝 Define um formulário que agrupa campos de entrada.
- **`<input>`**: 📌 Define um campo de entrada de diversos tipos (texto, senha, email, etc.).
- **`<textarea>`**: ✍️ Define uma área de texto maior para inserção de múltiplas linhas.
- **`<button>`**: 🔘 Cria um botão para submissão do formulário.
- **`<fieldset>`**: 📦 Agrupa elementos relacionados dentro do formulário.
- **`<legend>`**: 🏷️ Define um título descritivo para um `<fieldset>`.

Exemplo de formulário com `<fieldset>` e `<legend>`:

```html
<form action="submit.php" method="post">
  <fieldset>
    <legend>Informações Pessoais</legend>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome">
    
    <label for="email">E-mail:</label>
    <input type="email" id="email" name="email">
  </fieldset>
  <button type="submit">Enviar</button>
</form>
```

---

Este material serve como base teórica para as aulas de Desenvolvimento Web. Pratique implementando esses conceitos em seus próprios projetos! 🚀

