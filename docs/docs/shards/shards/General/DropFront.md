---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# DropFront

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | [`Any`](../../types/#any) |
| `<output>` ||The input to this shard is passed through as its output. | | [`Any`](../../types/#any) |
| `Name` |  | The name of the variable. | `` | [`String`](../../types/#string)[`&Any`](../../types/#contextvar) |
| `Key` |  | The key of the value to read from the table (parameter applicable only if the target variable is a table). | `None` | [`String`](../../types/#string)[`&String`](../../types/#contextvar)[`None`](../../types/#none) |
| `Global` |  | If the variable is available to all of the wires in the same mesh. | `false` | [`Bool`](../../types/#bool) |

</div>

Drops the first element of the sequence variable passed in the `:Name` parameter. Works only on sequences.

## Details

--8<-- "details/shards/General/DropFront.md"


## Examples

=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/General/DropFront/DropFront.shs"
  ```

  ```
  --8<-- "samples/shards/General/DropFront/DropFront.shs.log"
  ```
&nbsp;
--8<-- "includes/license.md"

