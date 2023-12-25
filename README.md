# 这是一个关于使用resnet18训练小狗分类模型，并使用GUI客户端方便操作的练习项目
项目内容包括：
- Data_Resize.ipynb:用于处理数据集图片，将数据集图片重新设置大小并保存在新的目录中，数据集来自斯坦福小狗分类图片。
- dict.ipynb：用于获取标签和数字索引的对应字典
- model_resnet18.ipynb：使用Pytorch定义的resnet18模型
- Train_Test.ipynb：在数据集上训练模型，并保存最好效果的模型参数。这一块需要注意，数据增广的重要性，在数据集量偏小的情况下，数据增广尤为重要。此处也有自定义数据集的一些使用实践。
- GUI：使用交互式客户端来实现简便的识别分类操作，主要是打开图片，进行分类，显示分类结果。
![Uploading 图片.png…]()
