1、数据集的准备，数据集的格式如下，将数据集放入以下两个文件夹

  * 1、VOCdevkit/VOC2007/Annotations 文件夹，主要用于存放图片文件标注的.xml文件
  
  * 2、VOCdevkit/VOC2007/JPEGImages存放了所有训练照片

2、运行VOCdevkit/VOC2007/voc2yolo4.py 程序，修改xmlfilepath和saveBasePath路径

    最终将得到VOCdevkit/VOC2007/ImageSets/Main 里面各种训练、验证、测试图片名称的txt文件
  
3、运行根目录下的voc_annotation.py，运行前需要将classes改成你自己的classes
   
    此时会生成对应的2007_train.txt，每一行对应其图片位置及其真实框的位置
    







    
    

