# IDS_Plant_disease
## Run instructions:
1) Upload to cloud
2) Suffer with local installation
3) For those who brave enough to mess around with tensorflow locally, **abandon every hope, all you who enter**
```
docker pull tensorflow/tensorflow:latest-gpu-jupyter
docker run -it --gpus all --rm -p 8888:8888 -v /home/.../project:/tf/notebooks/ tensorflow/tensorflow:latest-gpu-jupyter
```
> assuming CUDA is installed
