# Scale Match for Tiny Person Detection

------------------------
[[paper]](http://openaccess.thecvf.com/content_WACV_2020/papers/Yu_Scale_Match_for_Tiny_Person_Detection_WACV_2020_paper.pdf) [[ECCVW]](https://rlq-tod.github.io/challenge1.html)
[[challenge]](https://competitions.codalab.org/competitions/24551)
[[ECCVW sumarry]](https://arxiv.org/abs/2009.07506)
 
## `The annotaions of test set have released aready !!!` [Baidu Yun, password:pmcq](https://pan.baidu.com/s/1kkugS6y2vT4IrmEV_2wtmQ) and [Google Driver](https://drive.google.com/open?id=1KrH9uEC9q4RdKJz-k34Q6v5hRewU5HOw)

## TODO list
1. add a tutorial that how to train on TinyPerson with scale match on COCO
2. add a tutorial that how to train on other dataset
3. add a tutorial that how to train a strong baseline for competetion

## TinyPerson Dataset

The dataset will be used to for ECCV2020 workshop [RLQ-TOD'20 @ ECCV](https://rlq-tod.github.io/challenge1.html), [TOD challenge](https://competitions.codalab.org/competitions/24551)

#### Download link:
[Official Site](http://vision.ucas.ac.cn/resource.asp): recomended, download may faster<br/>
[Baidu Pan](https://pan.baidu.com/s/1kkugS6y2vT4IrmEV_2wtmQ)   password: pmcq<br/>
[Google Driver](https://drive.google.com/open?id=1KrH9uEC9q4RdKJz-k34Q6v5hRewU5HOw)<br/>

For more details about TinyPerson dataset, please see [Dataset](dataset/).

![](figure/annotation_rule.jpg)

## Tiny Benchmark
The benchmark is based on [maskrcnn_benchmark](https://github.com/facebookresearch/maskrcnn-benchmark) and [citypersons code](https://bitbucket.org/shanshanzhang/citypersons/src/default/evaluation/).

For more details about the benchmark, please see [Tiny Benchmark](tiny_benchmark/).

## Scale Match

![](figure/scale_match.jpg)

## Citation

If you use the code and benchmark in your research, please cite:
```
@inproceedings{yu2020scale,
  title={Scale Match for Tiny Person Detection},
  author={Yu, Xuehui and Gong, Yuqi and Jiang, Nan and Ye, Qixiang and Han, Zhenjun},
  booktitle={The IEEE Winter Conference on Applications of Computer Vision},
  pages={1257--1265},
  year={2020}
}
```
And if the ECCVW challenge sumarry do some help for your research, please cite:
```
@article{yu2020the,
  title={The 1st Tiny Object Detection Challenge:Methods and Results},
  {Yu, Xuehui and Han, Zhenjun and Gong, Yuqi and Jiang, Nan and Zhao, Jian and Ye, Qixiang and Chen, Jie and Feng, Yuan and Zhang, Bin and Wang, Xiaodi and Xin, Ying and others},
  journal={arXiv preprint arXiv:2009.07506},
  year={2020}
}
```

