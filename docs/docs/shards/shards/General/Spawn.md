---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# Spawn

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | [`Any`](../../types/#any) |
| `<output>` || | | [`Wire`](../../types/#wire) |
| `Wire` |  | The wire to spawn and try to run many times concurrently. | `None` | [`None`](../../types/#none)[`Wire`](../../types/#wire)[`[Shard]`](../../types/#seq) |

</div>



## Examples

=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/General/Spawn/Spawn.shs"
  ```

  ```
  --8<-- "samples/shards/General/Spawn/Spawn.shs.log"
  ```
&nbsp;
--8<-- "includes/license.md"

