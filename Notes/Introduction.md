# 什么是Machine Learning

 - Looking for function from data（从很多数据中找到解决问题的方法）
 - Machine Learning 的框架分为 Model(A set of function), Training Data, Goodness of function
## 机器学习一共分为三个步骤
1. Define a set of function（找到一组方法）
2. goodness of function（拥有评估function的评估方法）
3. pick the best function（找到一个最好的function）
## 学习路径
 - Supervised Learning：有 Input 和 Output，Output 的 label 通常要人工来评测是否是正确的
     - Regression （回归）
         - 输出通常是一个数值
         - 如：给定历史的PM2.5的值，来预测明天上午的PM2.5的值
     - Classification （分类）
         - Binary Classification: yes or no
         - Multi-class-Classification: class1, class2 ...
         - Linear Model
         - Non-Linear Model：Deep Learning, SVM, Desicion Tree, K-NN
 - Semi-Supervised Learning
     - 有少部分 labelled 的猫狗图片，和大部分 unlabelled 的猫狗图片，这部分 unlabelled 的猫狗图片，也会对机器的学习有帮助
 - Transfer Learning
     - 有 labelled 的猫狗图片，和一堆不相干的其他内容的图片，需要机器自己来识别是不是猫狗
 - Unsupervised Learning
     - 学习的时候，只给机器一大堆的数据，不输出内容，也就是不给标签化。比如：给机器训练庞大的新闻内容，机器是否能给出认识这些词语
 - Structured Learning
     - 语音识别，机器翻译，人脸识别
 - Reinforcement Learning
     - Reinforcement Learning 通过评价来学习（不断试错，找到更好的方法）
     - Supervised Learning 通过人工指导来学习
     - Alpha Go 一开始用的是Supervised Learning，后来用的是Reinforcement Learning