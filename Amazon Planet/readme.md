# Planet: Understanding the Amazon from Space

## Problem Statement

Use satellite data to track the human footprint in the Amazon rainforest

Every minute, the world loses an area of forest the size of 48 football fields. And deforestation in the Amazon Basin accounts for the largest share, contributing to reduced biodiversity, habitat loss, climate change, and other devastating effects. But better data about the location of deforestation and human encroachment on forests can help governments and local stakeholders respond more quickly and effectively.

[Planet](https://www.planet.com/company/careers/), designer and builder of the world’s largest constellation of Earth-imaging satellites, will soon be collecting daily imagery of the entire land surface of the earth at 3-5 meter resolution. While considerable research has been devoted to tracking changes in forests, it typically depends on coarse-resolution imagery from Landsat (30 meter pixels) or MODIS (250 meter pixels). This limits its effectiveness in areas where small-scale deforestation or forest degradation dominate.

Furthermore, these existing methods generally cannot differentiate between human causes of forest loss and natural causes. Higher resolution imagery has already been shown to be exceptionally good at this, but robust methods have not yet been developed for Planet imagery.

In this competition, Planet and its Brazilian partner  [SCCON](http://www.sccon.com.br/)  are challenging Kagglers to label satellite image chips with atmospheric conditions and various classes of land cover/land use. Resulting algorithms will help the global community better understand where, how, and why deforestation happens all over the world - and ultimately how to respond.

Competition Link: https://www.kaggle.com/c/planet-understanding-the-amazon-from-space

## My Solution

I used 9 CNN models, including several custom models, resnet50, vgg19 and Xception. I've also tried both pretained vgg19 with finetuning at the last layer and retrain vgg19 from scratch. Finally, I use average voting from these 9 models to make the final prediction.

You can checkout one of the model at [Custom Augment.ipynb](https://github.com/jincongho/Competitive-Machine-Learning/tree/master/Amazon%20Planet/Layer_1/custom/2.%20Single%2BDeep%2BAugment.ipynb).

## Performance

I was ranked 300 out of 938 teams (top 32%). 

![Image of Ranking](https://github.com/jincongho/Competitive-Machine-Learning/raw/master/Amazon%20Planet/rank.png)