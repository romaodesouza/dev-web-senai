# Desenvolvedor Web - Front-End | SENAI/SC

Este repositório contém as soluções para os desafios do curso de Desenvolvedor Web, focado no módulo de Front-End, oferecido pelo [SENAI/SC](https://cursos.sesisenai.org.br/), para o programa [Entra21](https://www.entra21.com.br/).

## Como Utilizar o Repositório

Na estrutura principal deste repositório, estão organizadas as pastas [desafio-1](/desafio-1/), [desafio-2](/desafio-2/) e [desafio-3](/desafio-3/), cada uma contendo arquivos como index.html, style.css e script.js. Esses arquivos demonstram a aplicação prática dos conceitos abordados no curso.

Na seção de [Exemplos](#exemplos), você encontrará a demonstração prática dos conceitos abordados em cada desafio.

## Desafios

1. **Desafio 1:** Desenvolver o Front-End do site utilizando a linguagem de marcação HTML5.

2. **Desafio 2:** Criar um Front-End responsivo para o site utilizando o framework CSS3 - Bootstrap.

3. **Desafio 3:** Aplicar a linguagem de programação JavaScript para implementar eventos no código HTML, aprimorando a interatividade do site.

## Desafio 1: Explorando a Estrutura HTML

Este desafio abrange a estrutura de documentos HTML, formatação, etiquetas para links, listas numeradas e não numeradas, tabelas, formulários, imagens, áudio e vídeo.

### Estrutura HTML

A estrutura básica do HTML segue o formato:

```html
<!DOCTYPE html>
<html>
	<head>
		<!-- Conteúdo do Head -->
	</head>
	<body>
		<!-- Conteúdo do Body -->
	</body>
</html>
```

Comentários podem ser adicionados ao código desta maneira:

```html
<!-- Meu Comentário -->
```

Uma estrutura mais completa, que costumo utilizar em meus projetos, é exemplificada abaixo:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <!-- Meu CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Conteúdo do Body -->

    <!-- Meu script.js -->
    <script src="script.js"></script>
</body>
</html>
```

### Formatação de Textos e Títulos em HTML

Nesta tabela, são apresentadas diversas tags HTML destinadas à formatação de textos e títulos em páginas web. Aqui estão breves descrições para cada uma delas:

- `<h1>` a `<h6>`: Essas tags são utilizadas para definir títulos de diferentes níveis, indo do título principal `<h1>` ao menos importante `<h6>`. São essenciais para estruturar e hierarquizar o conteúdo de uma página.

- `<p>`: A tag `<p>` é usada para envolver parágrafos de texto, permitindo uma organização clara e estruturada do conteúdo textual em uma página HTML.

- `<b>`, `<i>`, `<u>`, `<em>`: Estas tags são usadas para aplicar estilos específicos ao texto. `<b>` para negrito, `<i>` para itálico, `<u>` para sublinhado, e `<em>` para ênfase, proporcionando variedade e ênfase visual ao conteúdo textual.

- `<br>`: A tag `<br>` é utilizada para criar uma quebra de linha, forçando o conteúdo subsequente a aparecer em uma nova linha, útil para separar visualmente elementos em uma página.

- `<hr>`: Essa tag é empregada para criar uma linha horizontal, frequentemente utilizada para separar seções distintas em uma página. No exemplo, são adicionados estilos extras para personalizar a aparência da linha.

- `<strong>`: Similar à tag `<b>`, `<strong>` é utilizada para enfatizar o texto como forte ou importante, geralmente resultando em negrito. Ambas são empregadas para destacar determinados trechos de texto.

Cada exemplo é acompanhado pelo código HTML correspondente, mostrando como cada tag é implementada, e pelo resultado visual que a marcação produziria em uma página web. Essas tags desempenham um papel crucial na estruturação, estilo e apresentação de textos em documentos HTML.

#### Exemplos de Uso

| Tag       | Código                                                                                      | Resultado                                |
| --------- | ------------------------------------------------------------------------------------------- | ---------------------------------------- |
| `<h1>`    | `<h1>h1 é o título principal</h1>`                                                          | <h1>h1 é o título principal</h1>         |
| `<h2>`    | `<h2>h2 é subtítulo de h1</h2>`                                                             | <h2>h2 é subtítulo de h1</h2>            |
| `<h3>`    | `<h3>h3 é subtítulo de h2</h3>`                                                             | <h3>h3 é subtítulo de h2</h3>            |
| `<h4>`    | `<h4>h4 é subtítulo de h3</h4>`                                                             | <h4>h4 é subtítulo de h3</h4>            |
| `<h5>`    | `<h5>h5 é subtítulo de h4</h5>`                                                             | <h5>h5 é subtítulo de h4</h5>            |
| `<h6>`    | `<h6>h6 é subtítulo de h5</h6>`                                                             | <h6>h6 é subtítulo de h5</h6>            |
| `<p>`     | `<p>Texto</p>`                                                                              | Texto                                    |
| `<b>`     | `<b>Negrito</b>`                                                                            | **Negrito**                              |
| `<i>`     | `<i>Itálico</i>`                                                                            | *Itálico*                                |
| `<u>`     | `<u>Sublinhado</u>`                                                                         | <u>Sublinhado</u>                        |
| `<em>`    | `<em>Com ênfase</em>`                                                                       | _Com ênfase_                             |
| `<br>`    | `<br>` Quebra-de-linha                                                                      | <br>Quebra-de-linha                      |
| `<hr>`    | `<hr style="width:50%;height:3px;background-color:red">` cria uma linha                     | <hr style="width:50%;height:3px;background-color:red">|
| `<strong>`| `<strong>Strong</strong>`                                                                   | **Strong**                               |


### Etiquetas Para Links

### Listas Numeradas e Não Numeradas

### Tabelas

### Formulários

### Imagens

### Áudio

### Vídeo
