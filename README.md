It's a test project for python

打包方法：

python setup.py bdist_egg
之后将整个目录打包:
python setup.py sdist
在dist目录下生成tar.gz文件
发给调用方


安装和使用SDK：

解压，进入主目录下
python setup.py install 安装
再执行
pip install dist/pytest-0.3.tar.gz

查看
Lib\site-packages目录下有没有pytest目录，无则要创建
import pytest 在python程序中，调用安装好的pytest包
