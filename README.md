# GAN-jittor

This is the [Jittor AI Competition](https://www.educoder.net/competitions/index/Jittor-3) warm-up. The Conditional GAN (Conditional generative adversarial Nets) model is mainly trained on the digital image dataset MNIST by inputting a random vector Z and additional auxiliary information Y (such as category label),and generates an image of a specific phone number.

## Environments
* Python>=3.7 (installation via [anaconda](https://www.anaconda.com/distribution/) is recommended, use `conda create -n gan-jittor python=3.7` to create a conda environment and activate it by `conda activate gan-jittor`)
* Python libraries
    * Install core requirements by `pip install -r requirements.txt`

## Training
* By running `python CGAN.py` to train the model, and the following results will be obtained.

<p align="center">
    <img src="https://github.com/haiyangBai/jittor-nju_coder-jittor_Gan/blob/master/result.png" width="500",height="500">
</p>


