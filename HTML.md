
HTML significa HyperText Markup Language (Linguagem de Marcação de Hipertexto). Ele é usado no front-end e dá a estrutura para a página da Web que você pode estilizar usando CSS e tornar interativo usando JavaScript.  


![Estrutura base de HTML](https://sigarra.up.pt/up/pt/web_gessi_docs.download_file?p_name=F1029677100/36.jpg)

## Elementos, Tags e Atributos HTML

#### `<!DOCTYPE>` 
É uma "informação" para o navegador sobre qual tipo de documento esperar.
Todos os documentos HTML devem começar com uma declaração `<!DOCTYPE html>`

#### `<head>`
O elemento é um contêiner para metadados (dados sobre outros dados).
Metadados são dados sobre o documento HTML. Os metadados não são exibidos.
Os metadados normalmente definem o título `<title>` do documento, o conjunto de caracteres, os estilos, os scripts, e outras meta-informações.

#### `<body>`
A tag define o corpo do documento.
Contém todo o conteúdo de um documento HTML, como títulos, parágrafos, imagens, hiperlinks, tabelas, listas, etc.

#### `<html>`
Representa a raiz de um documento HTML.
É o contêiner para todos os outros elementos HTML (exceto o DOCTYPE)
**Nota:** Você deve sempre incluir o atributo `lang` dentro da tag, para declarar o idioma da página da Web.

#### `<h1>`–`<h6>`
Representam seis níveis de título de seção. 
`<h1>` é o nível de seção mais alto e `<h6>` é o mais baixo.

#### `<p>`
Representa um parágrafo. Em mídias visuais, parágrafos são representados como blocos indentados de texto com a primeira letra avançada e separados por linhas em branco. Já em HTML, parágrafos são usados para agrupar conteúdos relacionados de qualquer tipo, como imagens e campos de um formulário.

#### `<ul>` 
(ou _elemento_ _HTML de Lista desordenada_) representa uma lista de itens sem ordem rígida, isto é, uma coleção de itens que não trazem uma ordenação numérica e as suas posições, nessa lista, são irrelevantes. Caracteristicamente, os itens em uma lista desordenada são exibidos com um marcador que pode ter várias formas, como um ponto, um círculo, ou um quadrado. O tipo de marcador não é definido na descrição HTML da página, mas na CSS associada, utilizando a propriedade `list-style-type`.


#### `<meta>` 
Essas tags sempre vão dentro do elemento `<head>`, e são normalmente usados para especificar o conjunto de caracteres, a descrição da página, palavras-chave, autor do documento e configurações do visor.

Atributo |  Valor  |  Descrição
:---------:|:---------:|------------
charset  | character_set| Especifica a codificação de caracteres para o documento HTML
content | text| Especifica o valor associado ao atributo http-equiv ou name
http-equiv | content-security-policy<br>content-type<br>default-style<br>refresh| Especifica as ações do browser, com efeitos equivalente quando são utilizadas diretamente na tag HTTP do cabeçalho 
name| application-name<br>author<br>description<br>generator<br>keywords<br>viewport| Especifica um nome para o metadado

##### Exemplos:

**Defina palavras-chave para os motores de busca:**
```html
<meta name="keywords" content="HTML, CSS, JavaScript">
```

**Defina uma descrição da sua página da Web:**

```html
<meta name="description" content="Free Web tutorials for HTML and CSS">
```

**Defina o autor de uma página:**

```html
<meta name="author" content="John Doe">
```

**Configurando o visor para que seu site tenha uma boa aparência em todos os dispositivos:**

``` html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

#### Adicionando comentários:

Um comentário pode ser usado para esconder um trecho do código...

``` html
<!-- Isso é um comentário -->
```

#### Adicionando links externos:

``` html
<a href="seulink.com" target="blank">Descrição do link</a>
```

#### Adicionando links internos:

``` html
<a href="/caminho-do-arquivo">Descrição do link</a>
```

## Documentação

[HTML: Linguagem de Marcação de Hipertexto | MDN (mozilla.org)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
