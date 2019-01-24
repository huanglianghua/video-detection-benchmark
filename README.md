# Video Object Detection on ILSVRC VID Dataset

## Video Detector Benchmark

Evaluation results on ILSVRC VID validation set. All entries are ordered by the mAP scores.

|     Methods     |   mAP(%)   |  Runtime(ms/fps)  |   Venue   |
|:---------------:|:----------:|:-----------------:|:---------:|
| STMN (ResNet-101) | __80.5__ | 75 ms             | ECCV'18   |
| MANet + SeqNMS  | 80.3       | -                 | ECCV'18   |
| ST-Lattice (denser) | 79.6   | 20 fps            | CVPR'18   |
| ST-Lattice (sparser) | 79.0  | __62 fps__        | CVPR'18   |
| D & T (τ=1)     | 79.8       | 5.3 fps           | ICCV'17   |
| D & T (τ=10)    | 78.6       | 53 fps            | ICCV'17   |
| THPVOD          | 78.6       | 13 fps            | CVPR'18   |
| MANet           | 78.1       | 202 ms            | ECCV'18   |
| FGFA            | 76.5       | 733 ms            | ICCV'17   |
| D (& T loss)    | 75.8       | -                 | ICCV'17   |
| D (R-FCN)       | 74.2       | -                 | ICCV'17   |
| TCNN            | 73.8       | -                 | TCSVR'17  |
| R-FCN           | 73.6       | -                 | NIPS'16   |
| DFF             | 72.8       | -                 | CVPR'17   |
| TPN-LSTM        | 68.4       | 2.1 fps           | CVPR'17   |
| STMN (VGG-16)   | 61.7       | -                 | ECCV'18   |


## Video Object Detection/Segmentation

### ECCV 2018

* __MANet__: Shiyao Wang, Yucong Zhou, Junjie Yan, Zhidong Deng. "Fully Motion-Aware Network for Video Object Detection." ECCV 2018.
  [[pdf](http://openaccess.thecvf.com/content_ECCV_2018/papers/Shiyao_Wang_Fully_Motion-Aware_Network_ECCV_2018_paper.pdf)]
  [[code](https://github.com/wangshy31/MANet_for_Video_Object_Detection)]

* __STMN__: Fanyi Xiao, Yong Jae Lee. "Video Object Detection with an Aligned Spatial-Temporal Memory." ECCV 2018.
  [[pdf](http://openaccess.thecvf.com/content_ECCV_2018/papers/Fanyi_Xiao_Object_Detection_with_ECCV_2018_paper.pdf)]
  [[project](http://fanyix.cs.ucdavis.edu/project/stmn/project.html)]
  [[code](https://github.com/fanyix/STMN)]

### CVPR 2018

* __TAFM__: Mason Liu, Menglong Zhu. "Mobile Video Object Detection With Temporally-Aware Feature Maps." CVPR 2018.
  [[pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Mobile_Video_Object_CVPR_2018_paper.pdf)]

* __THPVOD__: Xizhou Zhu, Jifeng Dai, Lu Yuan, Yichen Wei. "Towards High Performance Video Object Detection." CVPR 2018.
  [[pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhu_Towards_High_Performance_CVPR_2018_paper.pdf)]

* __ST-Lattice__: Kai Chen, Jiaqi Wang, Shuo Yang, Xingcheng Zhang, Yuanjun Xiong, Chen Change Loy, Dahua Lin. "Optimizing Video Object Detection via a Scale-Time Lattice." CVPR 2018.
  [[pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Optimizing_Video_Object_CVPR_2018_paper.pdf)]
  [[project](http://mmlab.ie.cuhk.edu.hk/projects/ST-Lattice/)]
  [[code](https://github.com/hellock/scale-time-lattice)]

### ICCV 2017

* __FGFA__: Xizhou Zhu, Yujie Wang, Jifeng Dai, Lu Yuan, Yichen Wei. "Flow-Guided Feature Aggregation for Video Object Detection." ICCV 2017.
  [[pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_Flow-Guided_Feature_Aggregation_ICCV_2017_paper.pdf)]
  [[video](https://www.youtube.com/watch?v=R2h3DbTPvVg&feature=youtu.be)]
  [[code](https://github.com/msracver/Flow-Guided-Feature-Aggregation)]

* __TD-Graph LSTM__: Yuan Yuan, Xiaodan Liang, Xiaolong Wang, Dit-Yan Yeung, Abhinav Gupta. "Temporal Dynamic Graph LSTM for Action-Driven Video Object Detection." ICCV 2017.
  [[pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Yuan_Temporal_Dynamic_Graph_ICCV_2017_paper.pdf)]
  [[supp](http://openaccess.thecvf.com/content_ICCV_2017/supplemental/Yuan_Temporal_Dynamic_Graph_ICCV_2017_supplemental.pdf)]

* __a\_LSTM__: Yongyi Lu, Cewu Lu, Chi-Keung Tang. "Online Video Object Detection Using Association LSTM." ICCV 2017.
  [[pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Lu__Online_Video_ICCV_2017_paper.pdf)]

* __ULFV__: Ioana Croitoru, Simion-Vlad Bogolin, Marius Leordeanu. "Unsupervised Learning From Video to Detect Foreground Objects in Single Images." ICCV 2017.
  [[pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Croitoru_Unsupervised_Learning_From_ICCV_2017_paper.pdf)]

* __D & T__: Christoph Feichtenhofer, Axel Pinz and Andrew Zisserman. "Detect to Track and Track to Detect." ICCV 2017.
  [[pdf](https://www.robots.ox.ac.uk/~vgg/publications/2017/Feichtenhofer17/feichtenhofer17.pdf)]
  [[code](https://github.com/feichtenhofer/detect-track)]

### CVPR 2017

* __VPNs__: Varun Jampani, Raghudeep Gadde, Peter V. Gehler. "Video Propagation Networks." CVPR 2017.
  [[pdf](http://openaccess.thecvf.com/content_cvpr_2017/papers/Jampani_Video_Propagation_Networks_CVPR_2017_paper.pdf)]
  [[supp](http://openaccess.thecvf.com/content_cvpr_2017/supplemental/Jampani_Video_Propagation_Networks_2017_CVPR_supplemental.pdf)]

* __FCN-LSTM__: Huazhe Xu, Yang Gao, Fisher Yu, Trevor Darrell. "End-To-End Learning of Driving Models From Large-Scale Video Datasets." CVPR 2017.
  [[pdf](http://openaccess.thecvf.com/content_cvpr_2017/papers/Xu_End-To-End_Learning_of_CVPR_2017_paper.pdf)]

* __TPN-LSTM__: Kang Kai, Li Hongsheng, Xiao Tong, et al. "Object Detection in Videos with Tubelet Proposal Networks." CVPR 2017.
  [[pdf](https://arxiv.org/pdf/1702.06355)]

### BMVC 2017

* __OnAVOS__: Paul Voigtlaender, Bastian Leibe. "Online Adaptation of Convolutional Neural Networks for Video Object Segmentation." BMVC 2017, Oral.
  [[project](https://www.vision.rwth-aachen.de/page/OnAVOS)]
  [[pdf](https://arxiv.org/abs/1706.09364)]

### ECCV 2016

* Hanul Kim, Chang-Su Kim. "CDT: Cooperative Detection and Tracking for Tracing Multiple Objects in Video Sequences."
  [[pdf](http://www.eccv2016.org/files/posters/P-4A-31.pdf)]

* Koteswar Jerripothula, Jianfei Cai, Junsong Yuan. "CATS: Co-saliency Activated Tracklet Selection for Video Co-localization."
  [[pdf](http://www.eccv2016.org/files/posters/P-4A-44.pdf)]

### CVPR 2016

* __CPC__: Yao Lu, Xue Bai, Linda Shapiro, Jue Wang. "Coherent Parametric Contours for Interactive Video Object Segmentation."
  [[pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Lu_Coherent_Parametric_Contours_CVPR_2016_paper.pdf)]

* __TrackAndSeg__: Fanyi Xiao, Yong Jae Lee. "Track and Segment: An Iterative Unsupervised Approach for Video Object Proposals."
  [[pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Xiao_Track_and_Segment_CVPR_2016_paper.pdf)]

* __TCN__: Kai Kang, Wanli Ouyang, Hongsheng Li, Xiaogang Wang. "Object Detection From Video Tubelets With Convolutional Neural Networks."
  [[project](https://github.com/myfavouritekk/vdetlib)]
  [[pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Kang_Object_Detection_From_CVPR_2016_paper.pdf)]

### ArXiv 2016

* __SeqNMS__: Wei Han, Pooya Khorrami, Tom Le Paine, et al. "Seq-NMS for Video Object Detection." ArXiv 2016.
  [[pdf](https://arxiv.org/abs/1602.08465)]

### ICCV 2015

* __UnsupVideo__: Suha Kwak, Minsu Cho, Ivan Laptev, Jean Ponce, Cordelia Schmid. "Unsupervised Object Discovery and Tracking in Video Collections."
  [[pdf](http://openaccess.thecvf.com/content_iccv_2015/papers/Kwak_Unsupervised_Object_Discovery_ICCV_2015_paper.pdf)]

* __UnsupParse__: Ozan Sener, Amir R. Zamir, Silvio Savarese, Ashutosh Saxena. "Unsupervised Semantic Parsing of Video Collections."
  [[pdf](http://openaccess.thecvf.com/content_iccv_2015/papers/Sener_Unsupervised_Semantic_Parsing_ICCV_2015_paper.pdf)]

### ArXiv

* Tuan-Hung Vu, Anton Osokin, Ivan Laptev. "Tube-CNN: Modeling temporal evolution of appearance for object detection in video."
  [[pdf](https://arxiv.org/pdf/1812.02619)]

* Shiyao Wang, Hongchao Lu, Pavel Dmitriev, Zhidong Deng. "Fast Object Detection in Compressed Video."
  [[pdf](https://arxiv.org/pdf/1811.11057)]

* Hao Luo, Wenxuan Xie, Xinggang Wang, Wenjun Zeng. "Detect or Track: Towards Cost-Effective Video Object Detection/Tracking."
  [[pdf](https://arxiv.org/pdf/1811.05340)]

* Vít Růžička, Franz Franchetti. "Fast and accurate object detection in high resolution 4K and 8K video using GPUs."
  [[pdf](https://arxiv.org/pdf/1810.10551)]
