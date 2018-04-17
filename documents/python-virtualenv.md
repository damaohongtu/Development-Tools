# virtualenv
`同一台机器上可能需要使用不同的python版本，如不同的第三方软件需要不同版本的python支持，或者当前用户根据自己的需要需要搭建相关的python开发环境，（如该用户需要搭建自己的tensorflow环境）`
## ubuntu下virtualenv建立和使用
```
$ pip3 install virtualenv
$ mkdir myproject
cd myproject/
#创建一个独立的Python运行环境，命名为venv
$ virtualenv --no-site-packages venv
#有了venv这个Python环境，可以用source进入该环境
$ source venv/bin/activate
# 关闭当前virtualenv
$ deactivate
```
