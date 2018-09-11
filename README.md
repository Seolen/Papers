# Papers
the significant papers 

## Summer


### Basic DNN 

+ [Generative Adversarial Nets](https://arxiv.org/pdf/1406.2661v1.pdf)

### Basic Semantic Segmentation

+ [a Fixed-Point Model for Strucured Labeling](http://proceedings.mlr.press/v28/li13b.pdf )

  * Fixed-Point Model *

+ A Fixed-Point Model for Pancreas Segmentation in Abdominal CT Scans

+ [Recurrent Saliency Transformation Network: Incorporating Multi-Stage Visual Cues for Small Organ Segmentation](http://www.cs.jhu.edu/~alanlab/Pubs18/yu2018recurrent.pdf)

  * Joint Optimization, Saliency Transformation *

---
## Autumn

### Basic Weakly Supervised Learning

+ [A brief introduction to weakly supervised learning](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/nsr18.pdf)
* incomplete supervision,  inexact supervision, ; inaccurate supervision *

+ [Semi-Supervised Learning by Disagreement](http://cs.nju.edu.cn/lim/publications/kais10.pdf)

### Weak Supervised Segmentation

#### Bounding Box

+ [Pseudo Mask Augmented Object Detection](https://arxiv.org/pdf/1803.05858.pdf)

* only superviesed by bounding box annotation, recursively estimate the pseudo gt object masks, enhance the detection work with top-down segmentation feedbacks *

+ [BoxSup: Exploiting Bounding Boxes to Supervise Convolutional Networks for Semantic Segmentation](https://arxiv.org/pdf/1503.01640.pdf)  (2015 ICCV)

* significant work, iterate between automatically generating region proposals and training convolutional networks *

+ [Simple Does It: Weakly Supervised Instance and Semantic Segmentation](http://openaccess.thecvf.com/content_cvpr_2017/papers/Khoreva_Simple_Does_It_CVPR_2017_paper.pdf)  (CVPR 2017)

* carefully designing the input labels from given bounding boxes *

+ [Learning to Segment Every Thing](https://arxiv.org/pdf/1711.10370.pdf)

* On COCO Dataset, (past) 80 classes -> 3000 classes, Mask RCNN + transfer learning approach,  partially supervised training paradigm *

+ [Revisiting Dilated Convolution: A Simple Approach for Weakly- and SemiSupervised Semantic Segmentation](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0812.pdf)

* dilated convolution for extracting context info, image-level supervision -> high-quality dense object localization, classification network + multi-dilated convolutional blocks *




# Auxiliary Material

+ [The Expectation Maximization Algorithm](https://www.cs.utah.edu/~piyush/teaching/EM_algorithm.pdf)
+ [Multiscale Combinatorial Grouping](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/mcg/resources/MCG_CVPR2014.pdf) 

* MCG for region proposals *
