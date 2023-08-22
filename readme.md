# VOC图像分割标签制作方法
## 运行labelme对目标进行标注
#### 这里生成的文件是json格式，通过json格式文件和jpg文件保存在同一个目录中，如果没有labelme需要进行安装
```
pip install labelme
```

## 获取json文件的类别名信息，并将类别存入classes.names中
```
python get_classes_name.py
```

## 生成voc格式分割数据
```
python labelme2voc.py
```


