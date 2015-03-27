# digitcsuforpython

数字中南电信网络Python登陆脚本


### 使用前提

您本地需安装python环境

### 登陆

首次登陆时，进入到csu.py所在目录，运行：
    
    python ./csu.py login

会提示输入用户名,然后提示输入密码，注意，密码输入时是不显示的，在输入后直接回车即可。
登陆完成后，会在当前目录生成config.ini文件，这是用户的信息文件，密码已加密处理，但仍不要泄露。

以后登陆时只需运行`python ./csu.py login`而无需再输入密码。

### 下线

进入到csu.py所在目录，运行：
    
    python ./csu.py logout

### 问题

如果发现无法登陆，可以尝试删除`config.ini`文件后重新尝试登陆。


