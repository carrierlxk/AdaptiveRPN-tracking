### CFRP

This is the code of our IEEE CSVT paper: 'Adaptive Region Proposal with Channel Regularization for Robust Object Tracking'.
We expliot region proposal from object detection to address object re-detection and scale estimation issue in object tracking.

##

![](../master/framework1_1.png)

## Startup
1.Setup matconvet (recompile it if it is not comptiable with your machine) http://www.vlfeat.org/matconvnet/

2.Download the VGG-19 model "imagenet-vgg-verydeep-19.mat" http://www.vlfeat.org/matconvnet/pretrained/

3.Download Egdebox toolkit:https://github.com/pdollar/toolbox

4.Run "run_tracker_demo.m"


### Citation
If you find the code and dataset useful in your research, please consider citing:

@article{lu2019adaptive,
  title={Adaptive Region Proposal with Channel Regularization for Robust Object Tracking},
  
  author={Lu, Xiankai and Ma, Chao and Ni, Bingbing and Yang, Xiaokang},
  
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  
  year={2019},
  
  publisher={IEEE}
}
