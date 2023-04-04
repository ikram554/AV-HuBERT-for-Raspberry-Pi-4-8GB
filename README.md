# AV-HuBERT (Audio-Visual Hidden Unit BERT)
[Learning Audio-Visual Speech Representation by Masked Multimodal Cluster Prediction](https://arxiv.org/abs/2201.02184)

[Robust Self-Supervised Audio-Visual Speech Recognition](https://arxiv.org/abs/2201.01763)

![lip-reading](assets/lipreading.gif)

## Introduction
AV-HuBERT is a self-supervised representation learning framework for audio-visual speech. It achieves state-of-the-art results in lip reading, ASR and audio-visual speech recognition on the LRS3 audio-visual speech benchmark.

If you find AV-HuBERT useful in your research, please use the following BibTeX entry for citation.
```BibTeX
@article{shi2022avhubert,
    author  = {Bowen Shi and Wei-Ning Hsu and Kushal Lakhotia and Abdelrahman Mohamed},
    title = {Learning Audio-Visual Speech Representation by Masked Multimodal Cluster Prediction},
    journal = {arXiv preprint arXiv:2201.02184}
    year = {2022}
}

@article{shi2022avsr,
    author  = {Bowen Shi and Wei-Ning Hsu and Abdelrahman Mohamed},
    title = {Robust Self-Supervised Audio-Visual Speech Recognition},
    journal = {arXiv preprint arXiv:2201.01763}
    year = {2022}
}
```

## License

AV-HuBERT LICENSE AGREEMENT

This License Agreement (as may be amended in accordance with this License
Agreement, “License”), between you (“Licensee” or “you”) and Meta Platforms,
Inc. (“Meta” or “we”) applies to your use of any computer program, algorithm,
source code, object code, or software that is made available by Meta under this
License (“Software”) and any specifications, manuals, documentation, and other
written information provided by Meta related to the Software (“Documentation”).

By using the Software, you agree to the terms of [this
License](https://github.com/facebookresearch/av_hubert/blob/main/LICENSE). If
you do not agree to this License, then you do not have any rights to use the
Software or Documentation (collectively, the “Software Products”), and you must
immediately cease using the Software Products.

## Pre-trained and fine-tuned models

Please find the checkpoints [here](http://facebookresearch.github.io/av_hubert)

## Demo
Run our lip-reading demo using Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bNXkfpHiVHzXQH8WjGhzQ-fsDxolpUjD)

## Installation
First, create a virtual environment and activate it:
```
sudo apt install python3-venv
python3 -m venv my-project-env
source my-project-env/bin/activate
```
Then, install jupyter-notebook:
```
pip install jupyter
jupyter notebook
```
Now open **avhubert_vsr.ipynb**, to execute the code cells in Jupyter Notebook, click on the cell with code in it, then press "Shift+Enter" on your keyboard. This will run the code in that cell.
