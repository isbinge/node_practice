**_ project rules _**

## 开发

安装依赖：
    $ yarn

开发是的环境变量及一些开发环境配置不硬编码在代码中，每个人在项目根目录中新建一个不提交到 Git 的`.env`文件，进行本地配置，在开发服务器运行时时读取。

    API_SERVER=http://12.23.34.45 #开发环境 API 服务器地址
    PORT=9000 #本地开发服务器端口，可选
