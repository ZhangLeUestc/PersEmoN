# PersEmoN: A Deep Network for Joint Analysis of Apparent Personality, Emotion and Their Relationship

This repository contains the training prototxt for our papers: 

[PersEmoN: A Deep Network for Joint Analysis of Apparent Personality, Emotion and Their Relationship.](https://arxiv.org/abs/1811.08657)  
[*Le Zhang*](https://zhangleuestc.github.io/), [*Songyou Peng*](https://pengsongyou.github.io/), [*Stefan Winkler*](https://stefan.winkler.site/)  
IEEE Transactions on Affective Computing, 2019.

and 

[Give Me One Portrait Image, I Will Tell You Your Emotion and Personality.](https://pengsongyou.github.io/files/mm18_personality_paper.pdf)  
[*Songyou Peng*](https://pengsongyou.github.io/), [*Le Zhang*](https://zhangleuestc.github.io/), [*Stefan Winkler*](https://stefan.winkler.site/), [*Marianne Winslett*](http://winslett.cs.illinois.edu/)  
ACM Multimedia, 2019, Demo.

![image](https://github.com/ZhangLeUestc/PersEmoN/blob/master/img/system.jpg)

## Requirements
- [MTCNN](https://github.com/kpzhang93/MTCNN_face_detection_alignment)  
We use the MTCNN to first detect and align the faces. We used two customized layers which may not be included in the official caffe.
- [TSN](https://github.com/yjxiong/temporal-segment-networks)  
Used in Videodata layer.

Also, For the ``DomainConfusionInnerProduct" layer, we get the code from the following paper: ["Simultaneous Deep Transfer Across Domains and Tasks."](https://people.eecs.berkeley.edu/~jhoffman/papers/Tzeng_ICCV2015.pdf), ICCV, 2015. 

As the original code for the above paper is not well-maintained, we provide the source code of ``DomainConfusionInnerProduct" layer in this repository.

## Citations
Please cite the following papers if you use this repository in your research work:
```sh
@article{zhang2019persemon,
  title={PersEmoN: A Deep Network for Joint Analysis of Apparent Personality, Emotion and Their Relationship},
  author={Zhang, Le and Peng, Songyou and Winkler, Stefan},
  journal={IEEE Transactions on Affective Computing},
  year={2019},
  publisher={IEEE}
}
```
and
```sh
@inproceedings{peng2018mm,
 title = {Give Me One Portrait Image, I Will Tell You Your Emotion and Personality},
 author =  {Peng, Songyou and Zhang, Le and Winkler, Stefan},
 booktitle = {ACM International Conference on Multimedia (ACM MM)},
 year = {2018},
}
```

Contact **Le Zhang** [:envelope:](mailto:zhangleuestc@gmail.com) for questions, comments and reporting bugs.



