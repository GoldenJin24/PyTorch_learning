# PyTorch_learning
 PyTorch基础知识学习，BERT相关使用

- clone来自https://github.com/lansinuote/Simple_PyTorch2
- 视频教程来自https://www.bilibili.com/video/BV17X4y1H7dK/?spm_id_from=333.999.0.0&vd_source=2d43a2b523bdc656d5ec18e5231d85c3
- 关注b站蓝斯诺特 喵😘

# 环境配置
- 推荐miniconda，大小更小，安装更简洁
- pip和conda 安装包的区别和联系
    - conda安装比较慢，即使换源之后因为存在对包进行兼容性排查所有很慢，但是很稳，安装了之后不会因为奇奇怪怪的版本问题导致旧的包不行。
    - pip安装很快，但是存在安装新的包把旧的包的版本依赖关系打乱导致不能使用的问题。
    - 具体使用哪一个都可以（因为是新创建的环境，二者都很舒服）
    - 一会用conda，一会用pip这样的习惯不好。除非确实是死活安装不上包，那样推荐重新建立一个新的环境好了。（重装解决100%的问题）
    - pip，conda换源可以查看我之前的https://github.com/GoldenJin24/The-basic-operation-of-a-new-computer
- torch torchvision torchaudio，有官方的命令行，需要根据具体配置选择即可
https://pytorch.org/get-started/locally/
- huggingface中的transformers，datasets包安装
```
#安装Huggingface
pip install datasets==2.13.0
pip install transformers==4.30.2
```
- 安装jupyter notebook，当然用自己喜欢的IDE都可以，vscode之类的，一般安装了拓展都支持jupyter notebook格式。
# 入门，实战
见jupyter notebook文件