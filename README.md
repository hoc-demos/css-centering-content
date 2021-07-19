# CSS Centering Content

## Width, Margins
This works when you know the width of the content.

```css
body {
  margin-left:auto;
  margin-right:auto;
  width:300px;
} 
```

## Flex, Align Center Vertical/Horizontal
This is a bit easier because you don't need to
set the width.

```css
body {
  display:flex;
  flex-direction:column;
  justify-content: center;
  align-items: center;
}
```