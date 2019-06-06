## 项目
### 强力Django+杀手级Xadmin打造上线标准的在线教育平台

#### virtualenv使用笔记
```
1.安装
pip install virtualenv

2.创建虚拟环境
virtualenv env //对于python2.7,该虚拟环境env必须在英文目录路径下
virtualenv venv -p python2 //选择python2
virtualenv venv -p python3 //选择python3
//参数--no-site-packages的作用是不把系统python环境中的所有第三方包复制过来，这样就得到了一个“干净”的python运行环境
virtualenv --no-site-packanges venv

3.windows10下激活虚拟环境
cd env/Scripts
activate.bat //激活虚拟环境
pip list //查看当前虚拟环境安装的库

4.windows10下退出虚拟环境
deactivate.bat
```

#### virtualenvwrapper使用笔记
```
1.在windosw10环境下,安装
pip install virtualenvwrapper-win

2.创建虚拟环境
mkvirtualenv env //创建后自动激活虚拟环境

3.windows10下退出虚拟环境
deactivate

4.查看当前有多少虚拟环境
workon
workon env  //选择进入env的虚拟环境
```

#### git上传笔记或代码的命令
```
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/chengmengbao/Django_pro.git
git push -u origin master
//以上命令后，则输入账号密码
```


# 已看完第二章