this is for v2 master sdk

cuda11.7:https://developer.download.nvidia.com/compute/cuda/11.7.0/local_installers/cuda-repo-ubuntu1804-11-7-local_11.7.0-515.43.04-1_amd64.deb

cudnn8.5.0:https://developer.nvidia.com/compute/cudnn/secure/8.5.0/local_installers/11.7/cudnn-linux-x86_64-8.5.0.96_cuda11-archive.tar.xz ;并删除其中的*_v8.h文件

cub1.15.0:https://github.com/NVIDIA/cub/releases/tag/1.15.0 ，拷贝其中的cub文件夹到thrust/system/cuda/detail下，删除其中的cmake文件夹

cuda11.8:https://developer.download.nvidia.com/compute/cuda/11.8.0/local_installers/cuda_11.8.0_520.61.05_linux.run ;拷贝其中的cuda_fp8.h*
