# Getting Started React

## React Element
- Smallest building block of React apps
- JS objects cheap to create
- Components are composed of elements

## React Component
```js
class App extends Component {}
```

## Rendering to the DOM
index.js
```js
ReactDOM.render(<App />, document.getElementByID('root'));
```
index.html
```html
<div id="root"></div>
```
