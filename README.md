# GAN-jittor
## Brief Introduction
This is the code completed by team from Nanjing Uniersity(NJU) for [Jittor AI Competition](https://www.educoder.net/competitions/index/Jittor-3) warm-up. The Conditional GAN (Conditional generative adversarial Nets) model is mainly trained on the digital image dataset MNIST by inputting a random vector Z and additional auxiliary information Y (such as category label),and generates an image of a specific phone number.


## Environments
* Python >= 3.7 
* jittor == 1.3.4.12
* imageio == 2.9.0
* imageio-ffmpeg == 0.4.3
* matplotlib == 3.3.0
* configargparse == 1.3
* tensorboard == 1.14.0
* tqdm == 4.46.0
* opencv-python == 4.2.0.34

[Anaconda](https://www.anaconda.com/distribution/) is recommended to create a conda environment by running
 ```
 conda create -n gan-jittor python=3.7
 conda activate gan-jittor
 pip install -r requirements.txt
 ```

## Training
* By running 
```
python CGAN.py
```
 to train the model, and the following results will be obtained.

<p align="center">
    <img src="https://github.com/haiyangBai/jittor-nju_coder-jittor_Gan/blob/master/result.png" width="500",height="500">
</p>

## Thanks
This project refers to the following materials and projects, thank the author for sharing!
* https://cg.cs.tsinghua.edu.cn/jittor/tutorial/2020-5-13-22-47-cgan/
* https://github.com/Jittor/gan-jittor/blob/master/models/cgan/cgan.py
* https://github.com/arturml/mnist-cgan/blob/master/mnist-cgan.ipynb
