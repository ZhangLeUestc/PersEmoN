# PersEmoN: A Deep Network for Joint Analysis of Apparent Personality, Emotion and Their Relationship
Training prototxt for the paper ``PersEmoN: A Deep Network for Joint Analysis of Apparent Personality, Emotion and Their Relationship" in IEEE Transactions on Affective Computing.

![image](https://github.com/ZhangLeUestc/PersEmoN/blob/master/img/system.jpg)

We use the MTCNN to first detect and align the faces. The source coude of MTCNN could be found at:

https://github.com/kpzhang93/MTCNN_face_detection_alignment

We used two customized layers which may not be included in the official caffe.

Please get the source code of Videodata layer from the TSN Repository:

https://github.com/yjxiong/temporal-segment-networks



As for the ``DomainConfusionInnerProduct" layer, we get the code from the following paper:

Tzeng, Eric, et al. "Simultaneous deep transfer across domains and tasks." Proceedings of the IEEE International Conference on Computer Vision. 2015.

As the original code for the above paper is not well-maintained, we provide the source code of ``DomainConfusionInnerProduct" layer in this repository.

Please cite the related work if you use this repository in your research work:

@article{zhang2019persemon,
  title={PersEmoN: A deep network for joint analysis of apparent personality, emotion and their relationship},
  author={Zhang, Le and Peng, Songyou and Winkler, Stefan},
  journal={IEEE Transactions on Affective Computing},
  year={2019},
  publisher={IEEE}
}


