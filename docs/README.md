Dear ImGui - Meson Build
=====

## Supported versions
- Docking
- v1.89.9-docking

  
The `v1.89.9-docking` version is identical to the version `v1.89.9-docking` from the forked ImGui project but with a `meson.build` and `meson_options.txt` file for building with meson.

The fork of this version (1.89.9-docking) was created specifically as its the highest version of `Imgui` that is compatible with https://github.com/StudioCherno/Walnut/tree/3b8e414fdecfc6c8b58816106fe8d912bd172e31 which is/was the master branch at the time of writing.

Imgui v1.90 removed and updated a few methods [such as ImGui_ImplVulkan_CreateFontsTexture](https://github.com/ocornut/imgui/releases/tag/v1.90) which broke compatibility with TheCherno's Walnut app.

