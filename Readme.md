# UNIT/Style_Transfer Models

## Example
``` markdown
## Model名称
- 项目github地址: xxx.xxx.xxx
- 项目本地路径: xxx/xxx/xxx
- output路径: xxx/xxx/xxx
- 训练数据集本地路径: xxx/xxx/xxx
- 训练时长: training_time
- fid值: xxx.xxx
- Model训练小结本地路径(方便他人重复实验): xxx/xxx/xxx
```
## Semantic Segmentation on MIT ADE20K dataset in PyTorch
- 项目github地址:https://github.com/CSAILVision/semantic-segmentation-pytorch
- 项目本地路径: /home/undergrats/han/semantic-segmentation-pytorch
- 使用方法 ./demo_test.sh your_path_to_image 
- output路径 /home/undergrats/han/semantic-segmentation-pytorch


## UNIT

- 项目github地址: [https://github.com/mingyuliutw/UNIT](https://github.com/mingyuliutw/UNIT)
- 项目本地路径: /home/sway007/UNIT-local
- 训练数据集本地路径:
  - /home/sway007/UNIT-local/udacity_datasets
  - /home/sway007/img-sources
- 训练时长: **todo**
- fid值: **todo**
- Model训练小结本地路径: **todo**

## CycleGAN

- 项目github地址:  [https://github.com/hardikbansal/CycleGAN](https://github.com/hardikbansal/CycleGAN)
- 项目本地路径: `/home/undergrats/ywCHENG/CycleGAN`
- 训练数据集本地路径: `/home/undergrats/ywCHENG/Oxford_*.zip
- 训练时长: about 24 h (Since the best images appear during the training process, the epoch will be changed to the best number in the following)
- fid值: **todo**
- Model训练小结本地路径: ` /home/undergrats/ywCHENG/Report.md` along with all the output obtained during Cheng Yiwei's work in `/home/undergrats/ywCHENG/CycleGAN/output/imgs`.

## deep-photo-styletransfer

- 项目github地址: [https://github.com/luanfujun/deep-photo-styletransfer](https://github.com/luanfujun/deep-photo-styletransfer)
- 项目本地路径: /home/sway007/git-repos/deep-photo-styletransfer
- 训练数据集本地路径: **todo**
- 训练时长: **todo**
- fid值: **todo**
- Model训练小结本地路径: **todo**

## AdaIN-style

- 项目github地址: 

- 项目本地路径: /home/sway007/git-repos/style-transfer/AdaIN-style

- 训练数据集本地路径: content_dir(/home/sway007/datasets/unamed_dataset)  style_dir(/home/sway007/datasets/Images_Oxford_Sun/snow_1)

- output路径: /home/sway007/git-repos/style-transfer/AdaIN-style/custom_output

- 训练时长: 
    ```bash
    real	2349m46.212s
    user	3782m18.764s
    sys	554m26.476s
    ```

- fid值: TODO

- Model训练小结本地路径(方便他人重复实验): exp-reports/AdaIN-style.md

## FastPhotoStyle

TIPs: This model uses CSAILVision in itself, there's no need to generate more segmentation images from outside.

And you'd better resize two inputs to the same width and height to prevent possible `ValueError`.

- 项目github地址: [https://github.com/NVIDIA/FastPhotoStyle](https://github.com/NVIDIA/FastPhotoStyle)

- 项目本地路径: /home/undergrats/ywCHENG/FastPhotoStyle
- 训练数据集本地路径: Pre-trained model
- output路径:/home/undergrats/ywCHENG/FastPhotoStyle/results
- Model训练小结本地路径: /home/undergrats/ywCHENG/FastPhotoStyle/Guidance_from_CHENG.md

-----------------------

# Metrics

## Steering Angle Difference

- **self-driving model** (预测steering angle)
    - 实验代码地址: 
        - baseline model: [baseline model](https://github.com/dolaameng/udacity-SDC-baseline)
        - cg23: [cg23](https://github.com/udacity/self-driving-car/tree/master/steering-models/community-models/cg23)
        - pretrained models: [pretrained model evaluation](https://github.com/udacity/self-driving-car/tree/master/steering-models/evaluation)
    - 代码本地路径: 
        - baseline model: /home/sway007/git-repos/udacity-SDC-baselien-master
        - pretrained models: /home/sway007/git-repos/steer-angle-evaluation
    - 实验总结本地路径: [self-driving model summary](https://docs.google.com/document/d/1koSxoUU7QjgYpHRdOcLGRNhlKUnOZWE1EMcpufwrH-M/edit?usp=sharing)
  
- **udacity-driving-reader** (生成路况图片图片标记数据)
    - 实验代码地址: [https://github.com/rwightman/udacity-driving-reader](https://github.com/rwightman/udacity-driving-reader)
    - 代码本地路径: /home/sway007/git-repos/udacity-driving-reader
    - 实验总结本地路径: **todo**

## Fréchet Inception Distance

- 实验代码地址: [github](https://github.com/mseitzer/pytorch-fid)
- 代码本地路径: /home/sway007/git-repos/pytorch_inception_score
- 实验总结本地地址: **todo**

## UNIT/Style_Transfer Model训练时长

## TODOs
