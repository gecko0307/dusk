# Dusk
The goal of this project is to create a tool that generates WebGPU binding for D using a specification file as an input. Currently it uses [dawn.json](https://dawn.googlesource.com/dawn/+/refs/heads/main/dawn.json) from [Dawn](https://dawn.googlesource.com/dawn). Dusk will be compatible with [bindbc-wgpu](https://github.com/gecko0307/bindbc-wgpu) and eventually will be used to automate its maintainance.

Dusk is not finished yet, at this stage it generates only `types.d` module and supports only struct and enum declarations.
