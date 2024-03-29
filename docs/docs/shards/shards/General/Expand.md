---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# Expand

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | [`Any`](../../types/#any) |
| `<output>` || | | [`[Any]`](../../types/#seq) |
| `Size` |  | The expansion size. | `10` | [`Int`](../../types/#int) |
| `Wire` |  | The wire to spawn and try to run many times concurrently. | `None` | [`None`](../../types/#none)[`Wire`](../../types/#wire)[`[Shard]`](../../types/#seq) |
| `Policy` |  | The execution policy in terms of wires success. | `WaitUntil.AllSuccess` | [`WaitUntil`](../../../enums/WaitUntil) |
| `Threads` |  | The number of cpu threads to use. | `1` | [`Int`](../../types/#int) |

</div>



## Examples

=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/General/Expand/Expand.shs"
  ```

  ```
  --8<-- "samples/shards/General/Expand/Expand.shs.log"
  ```
&nbsp;
--8<-- "includes/license.md"

