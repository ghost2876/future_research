# 未来一些研究方向

## Speech Recognition 语音识别
只看了看知乎https://www.zhihu.com/question/20398418 主要使用DNN神经网络+HTK库（比较老，TensorFlow后来也有新的库但没试过） 需要大量语料和已标注的数据。

## 使用C/C++实现ML
That's why scikit-learn is pretty faster than our models implemented in Python. 毕竟Python是Interpreted Language解释型语言，运行时需要二次翻译，跟Java一样，而C/C++是Compiled Language，运行时几乎可以直接跑。但是Python上面的库和包比较多，所以一般公司都是用Python作整体框架和PoC，等model顺利通过验证后用C/C++实现，并用Python来调接口。

## CUDA
见对应子文件夹。