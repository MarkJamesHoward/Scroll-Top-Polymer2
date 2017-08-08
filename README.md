# ScrollTop

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/scrolltop/markjameshoward/scroll-top)

Overview
Once the page scrolls past a defined position the scroll top button will appear. 
Clicking the button will move the page back to the top.

## Demo
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="scroll-top.html">
  </template>
</custom-element-demo>
```
-->
```html
<scroll-top>Scroll to Top<scroll-top>
```

## Example

<scroll-top activateWhen="200">
  Back to Top!
</scroll-top>

### Properties

activateWhen: specifies the Y value in pixels that the user must scroll before the ScrollTop button will appear

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--scroll-top-background-color` | The paper-toast background-color | `#323232` |
| `--scroll-top-color` | The paper-toast color | `#f1f1f1` |


## License

MIT
