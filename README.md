# yolov5-ncnn-base-android

个人基于YOLOv5的目标检测

参考1：https://github.com/nihui/ncnn-android-yolov5

参考2：https://github.com/Tencent/ncnn

## 如何构建onnx

- [x] 请参考 [onnx2ncnn.ipynb](onnx2ncnn.ipynb) 

- [x] 或直接步入

  [colab]: https://colab.research.google.com/drive/1e2tDu9o1H6lK7ZDXcRVSPWARu2xGfsQI?usp=sharing

## 如何使用
### 第一步

- [x] 去网站下载ncnn-android-vulkan.zip【https://github.com/Tencent/ncnn/releases】

### 第二步
- [x] 将ncnn-android-vulkan.zip 解压到 app/src/main/jni 下

- [x] 或在 app/src/main/jni/CMakeLists.txt 配置文件中修改你的 ncnn 文件夹的路径

### 第三步
- [x] Build！

### 注意：你可能会遇到一些build问题

- [x] 需要您确保您的安卓环境可以成功build apk

- [x] 需要您确保 Android Studio 为最新版本

