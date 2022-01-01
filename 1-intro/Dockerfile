# 将image文件继承与官方的3.7版本的python
FROM python:3.7
# 将当前目录下的所有文件（除了 .dockerignore排除的路径），都靠拷贝进image文件的/app目录
COPY . /app
# 指定接下来的工作路径为/app
WORKDIR /app
# 在/app目录下，运行python文件
CMD python3 hello.py

