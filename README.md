[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/samuelli/progress-bar)

# \<progress-bar\>

Vanilla indeterminate progress bar built with no other dependencies that is smaller than 1KB.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="progress-bar.html">
    <style is="custom-style">
      progress-bar {
        margin: 16px;
        width: calc(100% - 32px);
      }

      progress-bar.salmon {
        --progress-bar-color: salmon;
        height: 10px;
      }

      progress-bar.fast {
        --progress-bar-duration: 500ms;
        --progress-bar-delay: 500ms;
        --progress-bar-color: #009688;
        height: 4px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<progress-bar></progress-bar>
<progress-bar class="salmon"></progress-bar>
<progress-bar class="fast"></progress-bar>
```