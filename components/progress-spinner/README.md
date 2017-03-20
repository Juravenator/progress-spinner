# progress-spinner
a material design inspired spinner for Polymer 2 that also supports progress indication

_[Demo and API Docs](https://juravenator.github.io/progress-spinner/components/progress-spinner/)_

## Usage

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-loader.js"></script>
    <link rel="import" href="progress-spinner.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<!-- an indeterminate spinner -->
<progress-spinner active></progress-spinner>

<!-- a pink indeterminate spinner -->
<style>
  progress-spinner[pink] {
    --spinner-color: pink;
  }
</style>
<progress-spinner active pink progress=0></progress-spinner>

<!-- a spinner displaying 70% progress -->
<progress-spinner active progress=.7></progress-spinner>
```

## Styling
The following custom properties are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--spinner-color` | Color or the spinner | `--primary-color`, `#2196F3`
