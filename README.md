# Ganimation
# Trying to replicate and fine tune original paper: [ [Paper]](https://rdcu.be/bPuaJ) 

## Prerequisites
- Install PyTorch (version 0.3.1), Torch Vision and dependencies from http://pytorch.org

## Data Preparation
- PreProcess/
Conversion from video to images, and creation of AU - image mapping pkl file.

The code requires a directory containing the following files:
- `imgs`: folder with all images
- `aus_openface.pkl`: dictionary containing the images action units.
- `train_ids.csv`: file containing the image names used to train.
- `test_ids.csv`: file containing the image names used to test.

An example of this directory is shown in `sample_dataset/`.

## Run
vscode/launch.json


## Reference
- original author
```
@article{Pumarola_ijcv2019,
    title={GANimation: One-Shot Anatomically Consistent Facial Animation},
    author={A. Pumarola and A. Agudo and A.M. Martinez and A. Sanfeliu and F. Moreno-Noguer},
    booktitle={International Journal of Computer Vision (IJCV)},
    year={2019}
}
```
