后端

# 使用MySQL数据库，请执行以下命令安装项目依赖环境
pip3 install -r requirements.txt

# 配置环境
在.env.dev文件中配置开发环境的数据库和redis，并修改配置文件为自己数据库和redis的相关配置

# 运行sql文件
1.新建数据库ruoyi-fastapi
2.如果使用的是MySQL数据库，使用命令或数据库连接工具运行sql文件夹下的ruoyi-fastapi.sql；

# 运行后端
python3 app.py --env=dev
