# Parallel-Programming using CUDA and Julia-GPU packages

This repository contains implementation of various parallel algorithms using ```CUDA``` and Julia's native support for ```CUDA```.

The [CUDAnative.jl](https://github.com/JuliaGPU/CUDAnative.jl) package adds native GPU programming capabilities to the Julia programming language. Used together with the [CUDAdrv.jl](https://github.com/JuliaGPU/CUDAdrv.jl) or [CUDArt.jl](https://github.com/JuliaAttic/CUDArt.jl) and [CuArrays.jl](https://github.com/JuliaGPU/CuArrays.jl) package for interfacing with the CUDA driver and runtime libraries, respectively, users can now do CUDA development in Julia without an external language or compiler.

## Installation
```Google Colab``` already has CUDA-10 pre-installed but doesn't have all the necessary drivers. Create a new notebook, set the hardware accelerator to GPU, and run all the cells in [this notebook](https://colab.research.google.com/drive/1588h5niCYwlobietNpmQOouM0chW21mu) (thanks to [@jekbradbury](https://github.com/jekbradbury) who found this solution) to install julia and the necessary drivers for the session on colab (don't forget to set the hardware accelerator to GPU, it can be found under the "Change runtime type" option in the "Runtime" menu). The output of the last cell must include ```Cuda compilation tools, release 10.0, V10.0.130```.

After that, open a new notebook in the same session and upload [this notebook](https://colab.research.google.com/drive/1588h5niCYwlobietNpmQOouM0chW21mu). This notebook will be your julia notebook where you write the code (similar to a python notebook but it's a julia notebook).

To use this julia notebook after the session has ended (or everytime you open colab), you'll need to open the installation notebook and run the cell which has instructions for installing julia (the 2nd cell) and then open the julia notebook. Also, it is necessary to keep both the notebooks open in the same session.
