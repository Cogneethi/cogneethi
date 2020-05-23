---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/texture_3_1.jpg
excerpt: >
  Machine Learning Tutorials.<br />
---

Hi, I am Nikhil, a Machine Learning Engineer. I am currently Freelancing.
Know more [about me](/about).

I am in the process of getting a deeper understanding on Machine Learning.
I have created video tutorials on topics related to Machine Learning.
The first one is on [Object Detection](https://www.youtube.com/playlist?list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S){:target="_blank"}. There are more than 1000 subscirbers currently. I will be creating more during my spare time.

There are many tutorials online that cover topics more broadly. For example, they might teach you CNNs, RNNs, GANs, RL etc. I would consider these to be the *meta concepts* or the basic building blocks with which you can build higher level stuff. These tutorials are already good and there is no point repeating them.

My intention is to pick a domain and cover all the important topics in that domain. Irrespective of what *meta concept* they might be using.

## 1. Evolution of Object Detection Networks
Topic on Object Detection.

**You can find the detailed video tutorials on  [YouTube](https://www.youtube.com/playlist?list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S){:target="_blank"}.**
{: .notice--info}

**A brief version of this tutorial is available as a blog [here](/evodn/object_detection_intro/){:target="_blank"}.**
{: .notice--primary}

In this course, I have covered some of the important papers in this field like:
* **Dalal & Triggs Detector, which uses Histogram of Oriented Gradients (HOG)**
* *Deformable Parts Model (DPM)*
* *Corner Detection & SIFT, intuitions*
* **Overfeat**
* *Selective Search*
* *Edge Boxes*
* *Bag of Visual Words (BoW)*
* *Spatial Pyramid Matching*
* **Spatial Pyramid Pooling Network (SPPNet)**
* **RCNN**
* **FAST RCNN**
* **Faster RCNN**

In the above list, the ones that are in **bold**, are covered in detail. The ones that are in *italic*, I have given just enough info, to either make it easy to understand the subsequent topics or to provide some additional context. If time permits, I might also cover RFCN, SSD, YOLO.

I have covered **Faster RCNN** in detail, including a **demo** of outputs at different points of the network. I have also shown a **short code walkthrough** of the Network Architecture of Faster RCNN.

Also, note that, I have concentrated more on the **concepts and intuitions**, rather than *math or code*. So, before you start, you can decide if this kind of content suits you.

Last but not the least, I have also included some additional materials in case you are new to this field. These include:
* Evaluating ML models, where you will learn about
  * Precision, Recall & F1 Scores
  * F1 Scores vs Accuracy
  * True Positive (TP), False Positive (FP), True Negative (TN), False Negative (FN)
  * Sensitivity, Specificity, False Positive Rate, True Positive Rate
  * Precision-Recall Curves
  * Receiver Operating Characteristic Curves
* Calculating the above measures for Object Detection
  * Intersection over Union (IoU)
  * Calculating TP, FP, TN, FN using IoU
  * Average Precision
  * 11-Point Interpolatiion & All Point Interpolation
  * Mean Average Precision
* CNN Basics
  * Here, I will give a short intro to Convolutional Neural Networks. I have only covered the intuitions without going into details.

In case, you are familiar with the above topics, feel free to skip them and take up the rest of the course.

### Prerequisites
In this course, I did not go into the basics of Machine Learning. I assume that you already are aware of the basic concepts.

But, in case, you are new to ML, don't worry. What I have done is to give you just enough overview about ML, so that you can continue to the course on Object Detection, without any issues.

If you are interested in the basics of Machine Learning, you can go through these:

[Michael Nielsen's Tutorial: (recommended)](http://neuralnetworksanddeeplearning.com/chap1.html){:target="_blank"}

[Andrew Ng's ML playlist: (recommended)](https://www.youtube.com/playlist?list=PLkDaE6sCZn6Ec-XTbcX1uRg2_u4xOEky0){:target="_blank"}

[Stanford Univ's Notes: (recommended)](http://cs231n.github.io/neural-networks-1/){:target="_blank"}

[NPTEL Deep Learning - part 1 (recommended, very under-rated)](https://www.youtube.com/playlist?list=PLyqSpQzTE6M9gCgajvQbc68Hk_JKGBAYT){:target="_blank"}

[NPTEL Deep Learning - part 2 (recommended)](https://www.youtube.com/playlist?list=PLyqSpQzTE6M-_1jAqrFCsgCcuTYm_2urp){:target="_blank"}

[Good short intro: (optional)](https://www.youtube.com/watch?v=FmpDIaiMIeA){:target="_blank"}

[Long intro with TensorFlow & MNIST: (optional)](https://www.youtube.com/watch?v=vq2nnJ4g6N0){:target="_blank"}

## Future Plans
My next target is to cover other papers on Object Detection like Yolo, SSD, RFCN, RetinaNet etc.
Then I will cover a. Segmentation, b. Action Recognition etc.

But as I said, I can continue creating, only if there is considerable [support](/donate) to this line of teaching.

**I grossly underestimated the amount of time it would take to create video courses.** I initially thought, it would just take 1 or 1.5 months, but actually I ended up taking more than 6 months, full-time. Off course, next time it would take less, since I have already learnt few things from my mistakes and the foundation is set. Nevertheless, I realised, Video/Audio recording is not for the faint hearted!
