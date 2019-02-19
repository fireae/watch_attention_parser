# Watch-Attend-and-Parse-tensorflow-version

![pic1](./misc/WAP-Decoder.png)
![pic2](./misc/WAP-Dense.png)

This project is a tensorflow implementation of the DenseNet model provided by [jianshu's Github](https://github.com/JianshuZhang/WAP). 

Mainly based on his two papers:

[Watch, attend and parse: An end-to-end neural network based approach to handwritten mathematical expression recognition](https://www.sciencedirect.com/science/article/pii/S0031320317302376)

[Multi-Scale Attention with Dense Encoder for Handwritten Mathematical Expression Recognition](https://arxiv.org/abs/1801.03530).

In [jianshu's model](https://github.com/JianshuZhang/WAP/tree/master/DenseNet), the codes are in Theano, then I convert the codes into tensorflow version and the performance is comparative with jianshu's [best model](https://github.com/JianshuZhang/WAP/tree/master/DenseNet/models) provided in his github. The performance of the codes can achieve 44%-45% ExpRate on single Tesla K80 GPU. The final results reported in jianshu's papers are obtained after five models ensembling. And the performance reported on single model is almost 
the same as ours as jianshu stated in his github [issues](https://github.com/JianshuZhang/WAP/issues/7)


# Requirements

  - Tensorflow v1.6
  - Python 3
  - cuda 9.0 [optional]
  - cudnn 7 [optional]


# Usage

```sh
python model-single-GPU.py  --batch_size=4
```

# Validation on offline-test.pkl

![pic3](./misc/WAP-Train.png)


# Tips to run the codes

If OOM Error occurs, please set batch_size to 4 or 2

# wap

#### Description
{**When you're done, you can delete the content in this README and update the file with details for others getting started with your repository**}

#### Software Architecture
Software architecture description

#### Installation

1. xxxx
2. xxxx
3. xxxx

#### Instructions

1. xxxx
2. xxxx
3. xxxx

#### Contribution

1. Fork the repository
2. Create Feat_xxx branch
3. Commit your code
4. Create Pull Request


#### Gitee Feature

1. You can use Readme\_XXX.md to support different languages, such as Readme\_en.md, Readme\_zh.md
2. Gitee blog [blog.gitee.com](https://blog.gitee.com)
3. Explore open source project [https://gitee.com/explore](https://gitee.com/explore)
4. The most valuable open source project [GVP](https://gitee.com/gvp)
5. The manual of Gitee [https://gitee.com/help](https://gitee.com/help)
6. The most popular members  [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)

