# Getting Started React

## React Element
- Smallest building block of React apps
- JS objects cheap to create
- Components are composed of elements

## React Component
```js
class App extends Component {}
```
+ A component returns a set of React elements that should appear on the screen

+ Allows spliting of UI into independent, reusable pieces (objectify UI)

+ Component accepts inputs

+ **User-defined components must always start with captial letter**
  + tags with lowercase are treated as DOM tags

## Rendering to the DOM
index.js
```js
ReactDOM.render(<App />, document.getElementByID('root'));
```
index.html
```html
<div id="root"></div>
```
