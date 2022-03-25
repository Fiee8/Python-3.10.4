Unix & Linux 平台安装 Python3:
以下为在 Unix & Linux 平台上安装 Python 的简单步骤：
打开 WEB 浏览器访问 https://www.python.org/downloads/source/
选择适用于 Unix/Linux 的源码压缩包。
下载及解压压缩包 Python-3.x.x.tgz，3.x.x 为你下载的对应版本号。
如果你需要自定义一些选项修改 Modules/Setup
以 Python3.6.1 版本为例：
# tar -zxvf Python-3.10.4.tgz
# cd Python-3.10.4
# ./configure
# make && make install
检查 Python3 是否正常可用：
# python3 -V
Python 3.10.4
