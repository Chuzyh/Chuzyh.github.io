# 研一Fall


第一个学期有三门课：
* Mathematical Computation I: Matrix Computation Course
* Modern Applied Optimization
* Inverse Problems and Data Assimilation: A Machine Learning Approach

# Matrix Computation
这个课是计算数学轨必选，感觉和国内上的数值代数比较像，稍微更难一点，还多了点编程内容，不过用python都能搞定 ~~c++写本科的数值分析和微分方程数值解大作业容易导致熬夜伤身体~~
期中考挺简单，期末考突然变难了（也可能我没认真复习），作业也没有太离谱的题（但要是能给个标准答案就更好了），总体而言感觉还是门不错的课。

# Modern Applied Optimization 
和上一门一样都是Lim教授的课。之前本科的好几个老师都推荐我选一门优化的课，但我好像一直时间冲突没选上，来硕士弥补一下遗憾（逃 整体课程内容偏简单，一开始讲了一些牛顿法之类的东西，然后开始一堆求导，求二阶导，黑塞矩阵blabla，最后到了一堆迭代法了之后又给了一堆公式糊脸，并来不及深入讲解。总之就是感觉听完之后内容从脑子上划过没有留下太多痕迹。最后的作业要求从头开始自己写几个优化器，这个工作量就有点大，如果复用之前几次的代码或许会好一点，如果学期开始提一嘴我可能写前几个作业就把代码维护好一点了（


# Inverse Problems and Data Assimilation: A Machine Learning Approach
开学前并没有看过这个课，但orientation的时候有人问了一句，后来还有人来问要不要一起学，感觉反问题还挺有意思的就给教授发了个邮件选上了。

理论上这个课是给上个反问题那个课本的人上的，不过直接从后面散度和评分方法之类的东西讲感觉也挺有意思的，可以自学前面的课本。

给分按照三个Project和一个pre，开学就布置并给出ddl，工作量有点大应该不太能短时间内赶出来，或许可以用于治疗拖延症（

第一个Project有点滥竽充数，很快就做完了，但我的结果似乎一直不收敛，似乎和其他人不太一样，可能是Prior没选好。

第二三个就很有意思了，可以作为对书上寥寥带过的几个细节（集合卡尔曼滤波的截断和inflation等）很好的实践注释。做完之后有点想去看看有没有关于这部分内容的理论分析但没找到，鸽了。

Pre就比较随意了，我讲了讲写Project遇到问题时候读的论文里的一个2ensemble 卡尔曼滤波器，在project上的效果并没有用inflation那么好，但从实践上可以通过增加rms error，降低rms spread，起到一点点效果。

总之是一个感觉学到了很多的课程，如果我英文好一点或许能和教授同学多聊一点什么，明年一定要学好口语（立下flag）

最后进行一个自己的代码的开源。

[Inverse Problem repository](https://github.com/Chuzyh/Inverse-Problem-and-Data-Assimilation)
