---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# Msg

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | [`Any`](../../types/#any) |
| `<output>` || | | [`Any`](../../types/#any) |
| `Message` |  | The message to display on the user's screen or console. | `` | [`String`](../../types/#string) |
| `Level` |  | The level of logging. | `LogLevel.Info` | [`LogLevel`](../../../enums/LogLevel) |

</div>

Displays the passed message string or the passed variable's value to the user via standard output.

## Details

--8<-- "details/shards/General/Msg.md"


## Examples

=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/General/Msg/2.shs"
  ```

  ```
  --8<-- "samples/shards/General/Msg/2.shs.log"
  ```
&nbsp;
=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/General/Msg/1.shs"
  ```

  ```
  --8<-- "samples/shards/General/Msg/1.shs.log"
  ```
&nbsp;
--8<-- "includes/license.md"

