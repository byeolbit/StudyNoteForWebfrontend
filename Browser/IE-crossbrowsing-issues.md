# IE cross browsing issues

### Flex-box
Fix for flex items that following parent's height.
<br>
```
min-height: 1px;
```

### content-fit
fallback for content-fit
<br>
```css
float: left;
clear: left;
```

### CSS color value
Use rgba instead of hex
```
background-color: #00000080 // not acceptable in IE
background-color: rgba(0, 0, 0, 0.5) // acceptable in IE
```
