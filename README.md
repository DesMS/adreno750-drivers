# Adreno 750 drivers for FEX

Only install `mesa-vulkan-kgsl_24.1.0-devel-20240422_amd64.deb` in your amd64 guest fs, and install all others in your arm64 guest fs.

Note:

You HAVE to set `MESA_VK_WSI_DEBUG` to `sw` (`export MESA_VK_WSI_DEBUG=sw`) and `TU_DEBUG` to `noconform` (`export TU_DEBUG=noconform`).

These drivers only work in a proot environment
