---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# UI.Variable

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | [`Any`](../../types/#any) |
| `<output>` || | | [`Any`](../../types/#any) |
| `Variable` |  | The variable that holds the value. | `None` | [`&Any`](../../types/#contextvar) |
| `Labeled` |  | If the name of the variable should be visible as a label. | `false` | [`Bool`](../../types/#bool) |

</div>



## Examples

=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/UI/Variable/1.shs"
  ```

  ```
  --8<-- "samples/shards/UI/Variable/1.shs.log"
  ```
&nbsp;
--8<-- "includes/license.md"

