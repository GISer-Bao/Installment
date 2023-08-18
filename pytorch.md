# Install pytorch (based anaconda)

## **step 1. install CUDA and cuDNN**
```
Version:
CUDA==10.2
cuDNN==8.0.2
```
```
Download:
CUDA：https://developer.nvidia.com/cuda-toolkit-archive
cuDNN：https://developer.nvidia.com/cudnn

Reference：
https://blog.csdn.net/weixin_42838061/article/details/113107234
https://blog.csdn.net/uuhhy/article/details/124638448
```

## **step 2. install pytorch**

```
CPU version:
conda create -n pytorch python=3.9
conda activate pytorch
pip install torch==1.10.1+cpu torchvision==0.11.2+cpu torchaudio==0.10.1 -f https://download.pytorch.org/whl/cpu/torch_stable.html
```
```
GPU version:
conda create -n pytorch python=3.9
conda activate pytorch
conda install pytorch==1.10.1 torchvision==0.11.2 torchaudio==0.10.1 cudatoolkit=10.2 -c pytorch
or
pip install torch==1.10.1+cu102 torchvision==0.11.2 torchaudio==0.10.1 -f https://download.pytorch.org/whl/cu102/torch_stable.html
```

## **step 3. install spyder**

```
conda install spyder
```

## **reference**

```
https://pytorch.org/get-started/previous-versions/
https://blog.csdn.net/weixin_42838061/article/details/113107234
https://blog.csdn.net/uuhhy/article/details/124638448
```
