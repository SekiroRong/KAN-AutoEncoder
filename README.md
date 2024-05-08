# KAE:KAN-AutoEncoder
This repo is heavily based on [Blealtan's implement of KAN](https://github.com/Blealtan/efficient-kan). The original implementation of KAN is available [here](https://github.com/KindXiaoming/pykan).

## Motivation
Intuitively, KAN seems a natural representation of 1-dimensional signals, especialy of audio signals which can be decomposed into sinusoidal signals.
Thus, this repo is created to investigate the potential of KAN to represent the sinusoidal signals.

## How to use
Here I create two Juypter notebooks, one for [KAN-based AutoEncoder](https://github.com/SekiroRong/KAN-AutoEncoder/blob/main/KAE.ipynb) and another for [MLP-based AutoEncoder](https://github.com/SekiroRong/KAN-AutoEncoder/blob/main/MAE.ipynb).
My toy example shows that KAN is way better than MLP in representing sinusoidal signals, which may indicate the great potential of KAN to be the new baseline of AutoEncoder.

## Interesting Findings
![recon_signal.jpg](assests/recon_signal.jpg)
![mix_signal.jpg](assests/mix_signal.jpg)
