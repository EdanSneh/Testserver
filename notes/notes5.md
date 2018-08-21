# State and Props

## State

### declaration
declared within constructor in format
```js
this.state = {
    example: null
}
```

### modification
Use the setState() method
```js
this.setState({
    example: "zero"
})
```

## Props

- Attributes are passed into a component as a single object
- cannot modify props within the component
- available as "props"

Props are passed in line parameters into div
```js
<Menu dishes={this.state.dishes} />
```

## Handling Events
Pass functiona as the event handler
Use camelCase to specify events
```js
<Card onClick={() => this.onDishSelect(dish)}>
```

## Lists sand Keys
Lists are handled similar to JS
```js
const menu = this.props.dishes.map((dish) =>{
    return(
        <div key = {dish.id}>
        <h1>{dish.name}</h1>
    );
})
```

- **Important: Each element within an array requires a key**