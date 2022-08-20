# yolov7-obb
yolov7（和yolov5）的旋转检测，包含cls,kfiou,kid,mkiou,riou,r-ciou,r-diou,代码等明年毕业答辩后公开

yolov5的backbone包含convnext,swin-v1,swin-v2,cswin,（swin-v1-adapt,swin-v2-adapt,cswin-adapt，冻结骨干网络权重，仅仅训练分支的adapt-mlp,效果不好）
data数据集的测试集：使用yolov5m+convnext_tiny_rciou,官网datav1.5,obb测试效果达到74.08；
![image](https://user-images.githubusercontent.com/87272337/185733645-71d6ce7a-8f39-408a-b6ce-f43987359af1.png)

yolov7+obb正在测试
