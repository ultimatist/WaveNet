# WaveNet

WaveNet is a powerful new predictive technique that uses multiple Deep Learning (DL) strategies from Computer Vision (CV) and Audio Signal Processing models and applies them to longitudinal (time-series) data. It was created by researchers at London-based artificial intelligence firm [DeepMind](https://deepmind.com), and currently powers [Google Assistant voices](https://assistant.google.com).

We'll explore WaveNet and how it works, but first dive into data prep, current high-performance models (as a baseline, Facebook Prophet), and then compare results!

## Setup:

>run this full line in bash, as one line:

`conda create -n wavenet python=3.7 pandas numpy seaborn matplotlib jupyter keras`

>then install Facebook Prophet:

`source activate wavenet; conda install -c conda-forge fbprophet`
