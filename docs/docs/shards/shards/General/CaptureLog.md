---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# CaptureLog

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | [`None`](../../types/#none) |
| `<output>` || | | [`[String]`](../../types/#seq) |
| `Size` |  | The maximum number of logs to retain. | `8` | [`Int`](../../types/#int) |
| `MinLevel` |  | The minimum level of logs to capture. | `debug` | [`String`](../../types/#string) |
| `Pattern` |  | The pattern used to format the logs. | `%^[%l]%$ [%Y-%m-%d %T.%e] [T-%t] [%s::%#] %v` | [`String`](../../types/#string) |
| `Suspend` |  | TODO. | `false` | [`Bool`](../../types/#bool) |

</div>



## Examples

=== "Code"

  ```x86asm linenums="1"
  --8<-- "samples/shards/General/CaptureLog/1.shs"
  ```

  ```
  --8<-- "samples/shards/General/CaptureLog/1.shs.log"
  ```
&nbsp;
--8<-- "includes/license.md"

