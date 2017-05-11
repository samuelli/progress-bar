[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/samuelli/progress-bar)

# \<progress-bar\>

`progress-bar` is a vanilla indeterminate progress bar with no dependencies that is smaller than 2KB.

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
        --progress-bar-duration: 1s;
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

## Finish gracefully
Use the `disable` attribute to let the progress bar finish gracefully instead of abruptly.


## API reference

Disable the progress element using the `hidden` attribute.

Custom property                                  | Description                                 | Default
-------------------------------------------------|---------------------------------------------|--------------
`--progress-bar-color      `                     | Color of the progress bar                   | `#37A0CE`
`--progress-bar-duration`                        | Duration of the animation                   | `2s`
`--progress-bar-delay`                           | Delay before the animation begins           | `0s`
