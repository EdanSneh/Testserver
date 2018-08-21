# Component Lifecycle

2. mount component
3. Updating
4. unmount component


## Mounting stage
Methods called when method inserted into DOM:
- constructor()
- getDervedStateFromProps()
- render()
- componentDidMount()
- ~~Depricated: componentWillMount()~~

## Updating Lifecycle
Methods called when updating
- getDerivedStateFromProps()
- shouldComponentUpdate()
- render()
- getSnapshotBeforeUpdate()
    - Good for saving information
- componentDidUpdate()
- ~~Depricated: componentWillReceiveProps() componentWillUpdate()~~