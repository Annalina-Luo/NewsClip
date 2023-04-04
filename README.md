![Python 3.6](https://img.shields.io/badge/python-3.9-green.svg)
![Packagist](https://img.shields.io/badge/Pytorch-2.0.0-red.svg)

# NewsClip

## Prerequisites
- Python 3
- CPU or NVIDIA GPU + CUDA CuDNN

## Installation

- Clone this repo:
```bash
git clone https://github.com/UIC-ESLAS/DiGAN-pytorch
cd NewsClip
```

- For pip users, please type the command `pip install -r requirements.txt`.
- For Conda users, you can create a new Conda environment using `conda env create -f environment.yml`.



<!-- ## Dataset Preparation
- Download the datasets using the following script. Please cite their paper if you use the data. (e.r. horse2zebra)
Try twice if it fails the first time!
```bash
bash ./datasets/download_dataset.sh horse2zebra
```
- You can also build your datasets followed the structure in `./datasets/{name}/`
- Get segmented results(condition) for training images:
```bash
python segmented_prepro.py --dataroot ./datasets/horse2zebra 
``` -->
<!-- ## Training/Testing
- Download a dataset using the previous script (e.g., horse2zebra).
 
- Train a model:
```bash
python train.py --dataroot ./datasets/horse2zebra --name horse2zebra
```
- To continue training, append `--continue_train --epoch_count xxx` on the command line.
- To view training results and loss plots, run `python -m visdom.server` and click the URL http://localhost:8097.
- To log training progress and test images to W&B dashboard, set the `--use_wandb` flag with train and test script
- To see more intermediate results, check out `./checkpoints/horse2zebra/web/index.html`.
 
- Test the model:
```
python test.py --dataroot ./datasets/horse2zebra --name horse2zebra
```
- The test results will be saved to a html file here: `./results/horse2zebra/latest_test/index.html`. -->

<!-- ## Apply a pre-trained model
- The pretrained model is saved at `./checkpoints/{name}_pretrained/latest_net_G.pth`. 
- To test the model, you also need to download the horse2zebra dataset:
```bash
bash ./datasets/download_dataset.sh horse2zebra
```
- Then generate the results using
```bash
python test.py --dataroot datasets/horse2zebra
```
-The results will be saved at `./results/`. Use `--results_dir {directory_path_to_save_result}` to specify the results directory. -->
