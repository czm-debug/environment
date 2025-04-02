###安装anaconda 时需要配置系统环境变量
D:\anaconda
D:\anaconda\Scripts\
D:\anaconda\Library\bin
D:\anaconda\Library\usr\bin
D:\anaconda\Library\mingw-w64\bin

###cmd中修改镜像
###修改镜像
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --show channels

conda create --name PDF python=3.10

###不适用conda创建环境的指令windows

python -m venv venv    #创建虚拟环境
venv\Scripts\activate     #激活虚拟环境   windows系统下
python --version    ##验证环境是否激活
###linux系统下创建环境指令
source venv/bin/activate    ###linux系统下
