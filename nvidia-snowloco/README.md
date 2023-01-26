# `nvidia-snowloco`

PKGBUILD for a merged NVIDIA driver using [snowman's](https://github.com/VGPU-Community-Drivers/vGPU-Unlock-patcher) and [PolloLoco's](https://gitlab.com/polloloco/vgpu-proxmox) patches.

This package should increase performance over the [`nvidia-snowman`](../nvidia-snowman/) package as it will not spoof the host card as a Quadro, instead just allowing vGPU checks to pass and run.

Patches are also included to disable transcoding limits using the NVIDIA Video Codec SDK (read: NvENC) and to enable NvFBC usage.

Report bugs with this PKGBUILD in issues.
Other bugs need to be tested without this PKGBUILD; use the merged and patched driver created from the patcher manually to rule out anything being caused by this package.

Thanks to krys in the Discord for figuring out that this combination of patches works.

[GPU Unlocking Discord server](https://discord.com/invite/qh6dvPtxvb)
