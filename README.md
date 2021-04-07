# Awesome Image Harmonization  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, datasets, and relevant links pertaining to image harmonization.

## Contributing

Contributions are welcome.  If you wish to contribute, feel free to send a pull request. If you have suggestions for new sections to be included, please raise an issue and discuss before sending a pull request.

## Table of Contents
+ [Papers](#Papers)
+ [Datasets](#Datasets)
+ [Other Resources](#Other-resources)


## Papers

#### Supervised deep learning methods
+ Wenyan Cong, Li Niu, Jianfu Zhang,  Jing Liang, Liqing Zhang: "*BargainNet: Background-Guided Domain Translation for Image Harmonization.*" ICME (2021) [[pdf]](https://arxiv.org/pdf/2009.09169.pdf) [[code]](https://github.com/bcmi/BargainNet).
+ Konstantin Sofiiuk, Polina Popenova, Anton Konushin: "*Foreground-aware Semantic Representations for Image Harmonization.*" WACV (2021) [[pdf]](https://openaccess.thecvf.com/content/WACV2021/papers/Sofiiuk_Foreground-Aware_Semantic_Representations_for_Image_Harmonization_WACV_2021_paper.pdf) [[code]](https://github.com/saic-vul/image_harmonization)

+ Guoqing Hao, Satoshi Iizuka, Kazuhiro Fukui: "*Image Harmonization with Attention-based Deep Feature Modulation*." BMVC (2020) [[pdf]](https://www.bmvc2020-conference.com/assets/papers/0121.pdf) [[code]](https://github.com/Dominoer/bmvc2020_image_harmonization)
+ Wenyan Cong, Jianfu Zhang, Li Niu, Liu Liu, Zhixin Ling, Weiyuan Li, Liqing Zhang: "*DoveNet: Deep Image Harmonization via Domain Verification.*" CVPR (2020) [[pdf]](https://arxiv.org/pdf/1911.13239.pdf) [[code]](https://github.com/bcmi/Image_Harmonization_Datasets/tree/master/DoveNet).
+ Xiaodong Cun, Chi-Man Pun: "*Improving the Harmony of the Composite Image by Spatial-Separated Attention Module.*" IEEE Trans. Image Process. 29: 4759-4771 (2020) [[pdf]](https://arxiv.org/pdf/1907.06406.pdf) [[code]](https://github.com/vinthony/s2am)
+ Yi-Hsuan Tsai, Xiaohui Shen, Zhe Lin, Kalyan Sunkavalli, Xin Lu, Ming-Hsuan Yang: "*Deep Image Harmonization.*" CVPR (2017) [[pdf]](https://arxiv.org/pdf/1703.00069.pdf) [[code]](https://github.com/wasidennis/DeepHarmonization)

#### Unsupervised deep learning methods
+ Anand Bhattad, David A. Forsyth: "*Cut-and-Paste Neural Rendering.*" arXiv preprint arXiv: 2010.05907 (2020) [[pdf]](https://arxiv.org/pdf/2010.05907.pdf)
+ Fangneng Zhan, Shijian Lu, Changgong Zhang, Feiying Ma, Xuansong Xie:"*Adversarial Image Composition with Auxiliary Illumination.*"  ACCV (2020) [[pdf]](https://arxiv.org/pdf/2009.08255.pdf)
+ Bor-Chun Chen, Andrew Kae: "*Toward Realistic Image Compositing With Adversarial Learning.*" CVPR (2019) [[pdf]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Toward_Realistic_Image_Compositing_With_Adversarial_Learning_CVPR_2019_paper.pdf)

#### Traditional methods
+ Shuangbing Song, Fan Zhong, Xueying Qin, Changhe Tu: "*Illumination Harmonization with Gray Mean Scale.*" Advances in Computer Graphics. CGI (2020) [[pdf]]()
+ Jun-Yan Zhu, Philipp Krähenbühl, Eli Shechtman, Alexei A. Efros:  "*Learning a Discriminative Model for the Perception of Realism in Composite Images.*" ICCV (2015) [[pdf]](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Zhu_Learning_a_Discriminative_ICCV_2015_paper.pdf) [[code]](https://github.com/junyanz/RealismCNN)
+ Su Xue, Aseem Agarwala, Julie Dorsey, Holly E. Rushmeier:
"*Understanding and improving the realism of image composites.*" ACM Trans. Graph. 31(4): 84:1-84:10 (2012) [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.365.5306&rep=rep1&type=pdf)
+ Kalyan Sunkavalli, Micah K. Johnson, Wojciech Matusik, Hanspeter Pfister: "*Multi-scale image harmonization.*" ACM Trans. Graph. 29, 4 (2010) [[pdf]](http://www.kalyans.org/research/2012/Harmonization_SIG10.pdf)
+ Jue Wang, Maneesh Agrawala, Michael F. Cohen. 2007: "*Soft scissors: an interactive tool for realtime high quality matting.*" ACM Trans. Graph. 26, 3 (2007) [[pdf]](http://vis.berkeley.edu/papers/softscissors/softscissors-SIG07.pdf)
+ Jean-François Lalonde, Alexei A. Efros: "*Using Color Compatibility for Assessing Image Realism.*" ICCV (2007) [[pdf]](https://ieeexplore.ieee.org/document/4409107) [[code]](https://github.com/jflalonde/colorRealism)
+ Daniel Cohen-Or, Olga Sorkine, Ran Gal, Tommer Leyvand, Ying-Qing Xu: "*2006. Color harmonization.*" ACM Trans. Graph. 25, 3 (2006) [[pdf]](https://igl.ethz.ch/projects/color-harmonization/harmonization.pdf)
+ Jiaya Jia, Jian Sun, Chi-Keung Tang, Heung-Yeung Shum: "*Drag-and-drop pasting.*" ACM Trans. Graph. 25, 3 (2006) [[pdf]](http://jiaya.me/archive/all_project_webpages/ddp/drag-and-drop_pasting.html)
+ Patrick Pérez, Michel Gangnet, Andrew Blake: "*Poisson image editing.*" *ACM Trans. Graph.* 22, 3 (2003) [[pdf]](https://www.cs.jhu.edu/~misha/Fall07/Papers/Perez03.pdf)

## Datasets
+ **iHarmony4:**  It contains four subdatasets: HCOCO, HAdobe5k,	HFlickr, Hday2night, with a total of 73,146 pairs of unharmonized images and harmonized images. [[link]](https://github.com/bcmi/Image_Harmonization_Datasets)
+ **GMSDataset**: It contains 183 images with image resolution of 1940*1440. It consists of 16 different objects and for each object, one source image and 11 target images in different background scenes and illumination conditions are captured. [[paper]]() [[link]](https://pan.baidu.com/s/141bLd3kjw8I4L7vUhYiEnQ) (access code: ekn2)
+ **RHHarmony**: A rendered image harmonization dataset, which contains 15000 ground-truth rendered images and has the potential to generate 135000 composite rendered images. [[link]](https://github.com/bcmi/Rendered_Image_Harmonization_Datasets)


## Other resources



