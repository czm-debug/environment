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


  
###安装node js   https://blog.csdn.net/yy1715713348/article/details/142741619?ops_request_misc=&request_id=&biz_id=102&utm_term=node%20js%20%E4%B8%8B%E8%BD%BD&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-1-142741619.142^v102^pc_search_result_base6&spm=1018.2226.3001.4187
