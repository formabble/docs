---
authors: Formabble & contributors
license: CC-BY-SA-4.0
---


# GFX.glTF

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | [`[Float4]`](../../types/#seq)[`{transform: [Float4] None: Any}`](../../types/#table) |
| `<output>` || | | [`GFX.Drawable`](../../types/#gfx.drawable) |
| `Path` |  | The path to load the model from | `None` | [`None`](../../types/#none)[`String`](../../types/#string)[`&String`](../../types/#contextvar) |
| `Bytes` |  | The bytes to load the model from | `None` | [`None`](../../types/#none)[`Bytes`](../../types/#bytes)[`&Bytes`](../../types/#contextvar) |
| `Copy` |  | Reference to another glTF model to copy | `None` | [`None`](../../types/#none)[`&GFX.Drawable`](../../types/#contextvar) |
| `Params` |  | Shader parameters for this drawable | `None` | [`None`](../../types/#none)[`{GFX.Texture2D GFX.TextureCube [Float4] Float4 Float3 Float2 Float Int Int2 Int3 Int4 &(GFX.Texture2D GFX.TextureCube [Float4] Float4 Float3 Float2 Float Int Int2 Int3 Int4)}`](../../types/#table)[`&{GFX.Texture2D GFX.TextureCube [Float4] Float4 Float3 Float2 Float Int Int2 Int3 Int4 &(GFX.Texture2D GFX.TextureCube [Float4] Float4 Float3 Float2 Float Int Int2 Int3 Int4)}`](../../types/#contextvar) |
| `Features` |  | Features to attach to this drawable | `None` | [`None`](../../types/#none)[`[GFX.Feature]`](../../types/#seq)[`&[GFX.Feature]`](../../types/#contextvar) |
| `AnimationController` |  | The animation controller | `None` | [`Shard`](../../types/#object)[`[Shard]`](../../types/#seq)[`None`](../../types/#none) |

</div>



## Details

--8<-- "details/shards/GFX/glTF.md"


--8<-- "includes/license.md"

