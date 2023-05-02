**CSS** (**_Cascading Style Sheets_ ou Folhas de Estilo em Cascata)** é uma linguagem de estilo usada para descrever a apresentação de um documento escrito em HTML  ou XML. O CSS descreve como elementos são mostrados na tela, no papel, na fala ou em outras mídias.

## CSS Inline

No CSS inline o estilo deve ser aplicado individualmente pra cada tag HTML, como no exemplo abaixo:
```css
<h2 style="background-color: orange;"> Teste de título estilizado </h2>
```

Sendo sua estrutura composta pelo  `style="(propriedadeCSS):(valor);"`
## CSS Interno

No CSS interno, é preciso utilikzar a tag `<style>` dentro do escopo da tag `<head>` do HTML.
Como no trecho de código abaixo:

```html
...
<head>
	<style>
	h2 {
		background-color: orange;
	}
	</style>
</head>
...
```

A vantagem do interno em relação ao inline, é que agora, o estilo foi aplicado para todas as tags `<h2>` do código,, o que economiza tempo em um código extenso.