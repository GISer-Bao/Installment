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
conda create -n pytorch python=3.8
conda activate pytorch
conda install pytorch==1.11.0 torchvision==0.12.0 torchaudio==0.11.0 cudatoolkit=10.2 -c pytorch
conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=10.2 -c pytorch
```
```
GPU version:
conda create -n pytorch python=3.8
conda activate pytorch
pip3 install -i https://pypi.tuna.tsinghua.edu.cn/simple torch===1.6.0 torchvision===0.7.0 -f https://download.pytorch.org/whl/torch_stable.html
```


## **reference**

```
https://pytorch.org/get-started/previous-versions/
https://blog.csdn.net/weixin_42838061/article/details/113107234
https://blog.csdn.net/uuhhy/article/details/124638448
```
