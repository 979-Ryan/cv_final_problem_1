# cv_final_problem_1

# Links
model 链接：https://pan.baidu.com/s/1vdpZaFbkbr5ByotzKBRErw?pwd=rl80

videos 链接：https://pan.baidu.com/s/1D8xmpxwcW48x-_BIF1En_Q?pwd=wkr8

# Usage
将model下载并存放至Model文件夹中，将需要进行语义分割的视频存放至Video文件夹中（默认命名为sample.mp4）

使用基于MobilenetV2的Deeplab V3+进行测试：将Driving_Scene_Segmentation.py中的ModelPath修改为"Model/deeplab_model1.tar.gz"

使用基于Xception65的Deeplab V3+进行测试：将Driving_Scene_Segmentation.py中的ModelPath修改为"Model/deeplab_model2.tar.gz"

完成上述工作后，直接运行Driving_Scene_Segmentation.py即可进行测试。
