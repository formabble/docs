---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# UI.Float3Slider

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value is ignored. | | [`None`](../../types/#none) |
| `<output>` ||The value produced. | | [`Float3`](../../types/#float3) |
| `Label` |  | The label for this widget. | `None` | [`String`](../../types/#string)[`None`](../../types/#none) |
| `Style` |  | The text style. | `None` | [`{Any}`](../../types/#table)[`&{Any}`](../../types/#contextvar) |
| `Variable` |  | The variable that holds the input value. | `None` | [`Float3`](../../types/#float3)[`&Float3`](../../types/#contextvar) |
| `Min` |  | The minimum value. | `None` | [`Float3`](../../types/#float3)[`&Float3`](../../types/#contextvar) |
| `Max` |  | The maximum value. | `None` | [`Float3`](../../types/#float3)[`&Float3`](../../types/#contextvar) |

</div>

A numeric slider.

## Examples

=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/UI/Float3Slider/1.shs"
  ```

  ```
  --8<-- "samples/shards/UI/Float3Slider/1.shs.log"
  ```
&nbsp;
--8<-- "includes/license.md"

