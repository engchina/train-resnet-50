# Train resnet-50

## Preparation

```
conda create -n train-resnet-50 python=3.10 -y
conda activate train-resnet-50
```

```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
conda install -y -c "nvidia/label/cuda-12.1.0" cuda-runtime
```

```
pip install -r requirements.txt
```

```
git clone https://www.modelscope.cn/datasets/tany0699/carBrands50.git
```