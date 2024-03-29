---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# Math.Mean

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A sequence of floating point numbers. | | [`[Float]`](../../types/#seq) |
| `<output>` ||The calculated mean. | | [`Float`](../../types/#float) |
| `Kind` |  | The kind of Pythagorean means. | `Mean.Arithmetic` | [`Mean`](../../../enums/Mean) |

</div>

Calculates the mean of a sequence of floating point numbers.

## Examples

=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/Math/Mean/Mean.shs"
  ```

  ```
  --8<-- "samples/shards/Math/Mean/Mean.shs.log"
  ```
&nbsp;
--8<-- "includes/license.md"

