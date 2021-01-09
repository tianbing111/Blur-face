# 人脸模糊处理
### 对输入的图片（含有人脸）进行模糊或者像素化处理，可以直接在IDE运行，不需要输入脚本参数
### 本项目可以对任何格式的图片进行批处理并且将结果保存到指定文件夹中
### 项目文件结构
    Blur and anonymize faces
    ├── examples
    │   ├── 11.jpg
    │   ├── 22.png
    │   ├── 33.png
    ├── face_detector
    │   ├── deploy.prototxt
    │   └── res10_300x300_ssd_iter_140000.caffemodel
    ├── result
    │   ├── 11_result.jpg
    │   ├── 22_result.png
    │   ├── 33_result.png
    ├── pyimagesearch
    │   ├── __init__.py
    │   └── face_blurring.py
    ├── blur_face.py
    └── blur_face_video.py
### blur_face.py实现对图片的批处理
### blur_face_video.py实现对视频流的处理

#### 参考文献：https://www.pyimagesearch.com/author/adrian/

## 🐱‍🏍实验结果
<img src="https://raw.githubusercontent.com/tianbing111/Blur-face/main/result/11.jpgresult.png"/>
<img src="https://raw.githubusercontent.com/tianbing111/Blur-face/main/result/33.jpgresult.png"/>
