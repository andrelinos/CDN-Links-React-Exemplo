# Exemplo de como usar o CDN Link do React

## Links CDN usados 
 - <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
 - <script crossorigin src="https://unpkg.com/react@16/umd/react.production.min.js"></script>
 - <script crossorigin src="https://unpkg.com/react-dom@16/umd/react-dom.production.min.js"></script>
  
## Exemplo de código JAVASCRIPT 
```js
const element = <h1>Hello World</h1>

ReactDOM.render(element, document.getElementById('root'));
```

## Exemplo de código HTML 
```html
<div id="root"></div>

<!-- Chamada do arquivo -->
<script src="./app.js" type='text/babel'></script>
```

## Exemplo babeljs 
```js
  <div id="output"></div>
  <!-- Load Babel -->
  <!-- v6 <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script> -->
  <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  <!-- Your custom script here -->
  <script type="text/babel">
  const getMessage = () => "Hello World";
  document.getElementById('output').innerHTML = getMessage();
  </script>
```

## Links 
- CDN Links [CDN Links](https://pt-br.reactjs.org/docs/cdn-links.html)
- Babel [CDN Links](https://babeljs.io/setup#installation)