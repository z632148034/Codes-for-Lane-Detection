# Codes-for-Lane-Detection
Codes for the CNN-based lane detection models. (expected release date: 2018.11.20)

## Timeline

I will release the torch code in 2018.11.20. Tensorflow and pytorch version of the model will be released thereafter.

## Content

* [Prerequisites](#Prerequisites)
* [Models](#Models)
  * [SCNN (Tensorflow)](#SCNN (Tensorflow, on-going))
  * [SCNN (Pytorch)](#SCNN (Pytorch, on-going))
* [Others](#Others)
  * [Citation](#Citation)
  * [Acknowledgement](#Acknowledgement)
  * [Contact](#Contact)

## Prerequisites
- [Torch](http://torch.ch/docs/getting-started.html)
- [Tensorflow](https://www.tensorflow.org/)
- [Pytorch](https://pytorch.org/)

## Models

### SCNN (Tensorflow, on-going)

Progress:
- [x] Define network architecture
- [x] Load pre-trained weights
- [x] Define dataloader (data augmentation [on-going])
- [x] Testing
- [x] Training
- [x] validation
- [ ] using multiple GPUs
- [ ] clean the codes and make them reproducible

Notes:

Please go to the [Tensorflow-SCNN](https://github.com/cardwing/Codes-for-Lane-Detection/tree/master/Tensorflow-SCNN) repo to see detailed instructions. 

### SCNN (Pytorch, on-going)

Progress:
- [ ] Define network architecture (VGG-16 + message passing)
- [ ] Load pre-trained weights
- [ ] Define dataloader (load images and labels + data augmentation)
- [ ] Testing (generate probability maps + smoothing)
- [ ] Training
- [ ] validation
- [ ] using multiple GPUs
- [ ] clean the codes and make them reproducible

## Others

### Citation

If you use the codes, please cite the following publications:

``` 
@inproceedings{pan2018SCNN,  
  author = {Xingang Pan, Jianping Shi, Ping Luo, Xiaogang Wang, and Xiaoou Tang},  
  title = {Spatial As Deep: Spatial CNN for Traffic Scene Understanding},  
  booktitle = {AAAI Conference on Artificial Intelligence (AAAI)},  
  month = {February},  
  year = {2018}  
}
```
Our paper working on lane detection will be available soon!

### Acknowledgement
This repo is built upon [SCNN](https://github.com/XingangPan/SCNN) and [LaneNet](https://github.com/MaybeShewill-CV/lanenet-lane-detection)

### Contact
If you have any problems in reproducing the results, just raise an issue in this repo.
