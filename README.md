# LineSegmentDetector17
基于C+CPP+OPENCV4.0实现，以C为主，OPENCV向下兼容3.0

V1.0 完成了基本算法的实现以及基础动画的实现
V1.1 完成了算法的优化， 将多个定长数组用动态数组实现，极大地减小了内存空间，将原算法的伪排序使用快速排序实现，优化了高斯降采样时计算高斯核的算法，改进后一张图仅需计算一次高斯核，按梯度排序进行区域增长时忽略低于100的值（从1024到1），因为大梯度的区域基本一次就能完成增长，所以将区域增长次数从大于等于2次改到1次
V1.2 完成了Degree图的动画，修正了UsedMap的动画，以及增加了梯度排名和区域内像素点显示
