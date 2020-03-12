# shape-dividers
SVG shape divider collection for websites

## React Component

### Props

```js
{
  shape: string, // The name of the shape.
  height?: int|string,
  color?: string, // fill color
  flipX?: bool,
  flipY?: bool
}
```

### Example

```js
class MyComponent extends React.Component {
  render(){
    return (
      <div>
        <ShapeDivider shape="curve-asymmetrical-opacity" height={200} color="#abcdef" flipX />
      </div>
    );
  }
}
```
