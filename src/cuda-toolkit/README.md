
# NVIDIA CUDA Compiler and Tools (cuda-toolkit)

Installs shared libraries, compiler (nvcc) and command-line tools for NVIDIA CUDA.

## Example Usage

```json
"features": {
    "ghcr.io/brokencuph/devcontainer-features/cuda-toolkit:1": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| installCudnn | Additionally install CUDA Deep Neural Network (cuDNN) shared library | boolean | false |
| installNvtx | Additionally install NVIDIA Tools Extension (NVTX) | boolean | false |
| installCommandLineTools | Additionally install CUDA command-line tools | boolean | false |
| cudaVersion | Version of CUDA to install | string | 11.8 |
| cudnnVersion | Version of cuDNN to install | string | 8.6.0.163 |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/brokencuph/devcontainer-features/blob/main/src/cuda-toolkit/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
