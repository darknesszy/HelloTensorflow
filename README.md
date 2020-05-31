# Overview

# Libraries

## Base libraries used
* tensorflow
* matplotlib
* numpy
* notebook

# Useful Resources

The following NVIDIA® software must be installed on your system:

* NVIDIA® GPU drivers —CUDA 10.1 requires 418.x or higher.
* CUDA® Toolkit —TensorFlow supports CUDA 10.1 (TensorFlow >= 2.1.0) - https://developer.nvidia.com/cuda-toolkit-archive
* cuDNN SDK (>= 7.6) - https://developer.nvidia.com/cudnn
* (Optional) TensorRT 6.0 to improve latency and throughput for inference on some models. - https://docs.nvidia.com/deeplearning/tensorrt/install-guide/index.html


## Known Issue
**Could not load dynamic library 'cudart64_101.dll'** - Symlink cudart64_102.dll as cudart64_101.dll

https://github.com/tensorflow/tensorflow/issues/38194