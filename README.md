# SEIDNet
we propose SEIDNet equipped with the generative Status Estimation and Information Decoupling for rain removal.

<img align="center" src="./Architecture/train.png" swidth="750">

## Requirements

- python 3.7.11
- pytorch 1.8.0
- CUDA Version 11.4
- opencv-python 4.4.0.44
- scikit-image 0.17.2

## Datasets
Single image rain removal
- Rain100L-old_version https://github.com/nnUyi/DerainZoo/blob/master/DerainDatasets.md
- Rain100H-old_version https://github.com/nnUyi/DerainZoo/blob/master/DerainDatasets.md
- Rain1400 https://xueyangfu.github.io/projects/cvpr2017.html
- SPA https://stevewongv.github.io/derain-project.html
- Rain13k https://github.com/swz30/MPRNet

Single image snow removal
- Snow100K https://goo.gl/BrRc3U

Single image haze removal
- ITS&OTS https://sites.google.com/site/boyilics/website-builder/reside

Single image shadow removal
- ISTD Dataset https://drive.google.com/file/d/1I0qw-65KBA6np8vIZzO6oeiOvcDBttAY/view



## Pretrained models

Coming soon

## Train

```
sh train_SEIDNet.sh
```

## Test

```
sh test_SEIDNet.sh
```

## Results

<details><summary>Single image rain removal</summary>
<p>
<img align="center" src="./results/derain.png" swidth="750">

<img align="center" src="./results/rain13k.png" swidth="750">
</p>
</details>


<details><summary>Single image snow removal</summary>
<p>
<img align="center" src="./results/desnow.png" swidth="750">
</p>
</details>

<details><summary>Single image haze removal</summary>
<p>
Single image haze removal
<img align="center" src="./results/dehaze.png" swidth="750">
</p>
</details>

<details><summary>Single image shadow removal</summary>
<p>
Single image shadow removal
<img align="center" src="./results/deshadow.png" swidth="750">
</p>
</details>


## Bibtex


