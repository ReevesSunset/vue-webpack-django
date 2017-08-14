# vue + webpack + django

> 参考:https://zhuanlan.zhihu.com/p/25080236

## Build Setup

``` bash
# 第一步: 进入到vue-blog文件夹下,运行如下命令
npm install

# 第二步: 安装完成后,运行如下命令进行构建,python启动后的页面依赖于构建后的文件
npm run build

# 第三步: 后退到python_system下,运行如下命令启动python的server
python manage.py runserver

# 第四步: 如下路径为vue项目的index.html
http://127.0.0.1:8000/demo/
```