# WuFan - 悟饭
#### A Scalable and Accurate Tool for Android App Clone Detection.

We have published a paper named "WuKong: A Scalable and Accurate Two-Phase Approach to Android App Clone Detection" in [ISSTA 2015](http://issta2015.cs.uoregon.edu). This paper presents WuKong, a new accurate and scalable approach to detect Android app clones. Our proposed techniques include a novel clustering-based approach to detect third-party libraries among Android apps efficiently and accurately without prior knowledge, which introduces significant benefits compared to previously used whitelist approaches. We also introduce a two-phase approach to detect app clones, which combines the scalability of coarse- grained detection and the accuracy of fine-grained detection mechanisms. Experiments on over 100,000 Android apps show that WuKong is able to detect app clones within several hours of comparison, with no false positives found in our evaluation.

However, the approach achieved in that paper is not easy for use. The input of that approach is thousands of Android apps, and the output is which app is re-packaged with anothor app. So, we create this simple tool for clone detection. All we need to do is input two app and then it will give you the similarity of the two apps.

Sample:
![sample](https://github.com/pkumza/WuFan/raw/master/sample.jpg)