---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# UI.FloatSlider

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | [`None`](../../types/#none) |
| `<output>` ||The value produced. | | [`Float`](../../types/#float) |
| `Label` |  | The text label for this widget. | `None` | [`String`](../../types/#string)[`None`](../../types/#none) |
| `Style` |  | The text style. | `None` | [`{Any}`](../../types/#table)[`&{Any}`](../../types/#contextvar) |
| `Variable` |  | The variable that holds the input value. | `None` | [`Float`](../../types/#float)[`&Float`](../../types/#contextvar) |
| `Min` |  | The minimum value. | `None` | [`Float`](../../types/#float)[`&Float`](../../types/#contextvar) |
| `Max` |  | The maximum value. | `None` | [`Float`](../../types/#float)[`&Float`](../../types/#contextvar) |

</div>

A numeric slider.

## Examples

=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/UI/FloatSlider/1.shs"
  ```

  ```
  --8<-- "samples/shards/UI/FloatSlider/1.shs.log"
  ```
&nbsp;
--8<-- "includes/license.md"

