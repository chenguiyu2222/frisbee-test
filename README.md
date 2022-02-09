# frisbee-test
记录一下第一次用Dash和Heroku发布应用遇到的坑吧，纯小白完全无任务web开发经验
主要根据教程dash的官方教程https://dash.plotly.com/deployment
1.windows系统命令行激活虚拟环境用的是    .\venv\Scripts\activate
2.一定生成教程中的app.py,.gitignore,Procfile,requirements.txt 这几个文件，这很重要，虽然不懂这几个文件是干嘛的
3.要用if __name__ == '__main__':来调用程序，有两处__name__ 。这里遇到过一次坑，虽然也是没搞懂原理
除去这几个坑就可以发布到heroku上了。
