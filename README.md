

安装环境说明：

拉取代码后，使用 npm install 安装依赖包
有部分依赖包需要跨域下载，会导致失败。 

但我们可以使用淘宝镜像下载，无需跨域
全局安装：npm install -g cnpm --registry=http://registry.npm.taobao.org

安装淘宝镜像后，以后下载将npm改为cnpm

在目录文件夹Shift+右键， 打开命令行， 输入 cnpm install 进行依赖包安装

安装完毕后，在目录文件夹打开命令行
运行 npm run build 和 npm run dev

最后在浏览器中打开
http://localhost:8080/app/index/index.html