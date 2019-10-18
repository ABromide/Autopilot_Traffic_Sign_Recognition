# Autopilot_TrafficSignRecognition
自动驾驶---交通指示牌的识别，基于keras，支持GPU加速。Traffic Sign Recognition code in keras, runs on GPU.

这是一个小型的神经网络项目，期望网络能够识别不同的交通指示牌。这个项目以卷积神经网络为基础，使用keras编写网络，支持GPU加速。

科目一里有一项任务就是学习交通指示牌，认指示牌是考取驾照的基础，同时也是实现自动驾驶的基础。

生活中我们常常会看到各种各样的交通指示牌：<br>
<p align="center">
	<img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1571415059674&di=4c2ed31c630b0f77fba0a1104191b833&imgtype=0&src=http%3A%2F%2Fimg.99114.com%2Fgroup10%2FM00%2F8C%2FFA%2FrBADsloysIaAcuagAAEHm0XhzdE515.jpg" alt="Sample"  width="250">
</p>

这个项目的数据集里搜集了43种不同交通指示牌共39209张彩色图片，您可以在[这里](https://pan.baidu.com/s/1ql2YNPQ7pNqOeNEYWupQwA&shfl=sharepset)获取，提取码：7yu6。您也可以访问该数据集的[原网址](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset)。

您可以通过运行help_func.py来查看数据集中的图片，以及每种图片所占的百分比：<br>
<p align="center">
	<img src="https://github.com/LeeWise9/Img_repositories/blob/master/%E6%8C%87%E7%A4%BA%E7%89%8C1.png?raw=true" alt="Sample"  width="350">
</p>
<p align="center">
	<img src="https://github.com/LeeWise9/Img_repositories/blob/master/%E6%8C%87%E7%A4%BA%E7%89%8C2.png?raw=true" alt="Sample"  width="350">
</p>
