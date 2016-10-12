

安装环境说明：

拉取代码后，使用 npm install 安装依赖包
如提示错误 npm 3+ 则需要升级npm版本，打开cmd， npm -v 查看版本，低于3的需要升级版本，输入npm install -g @npm3

升级完毕后，在目录文件夹Shift+右键， 打开命令行， 输入 npm install 进行依赖包安装

安装完毕后，在目录文件夹打开命令行
运行 npm run build 进行打包，文件输出目录为output

运行 npm run dev 进行开发（开发只需要运行 npm run dev）

最后在浏览器中打开以下链接，进行开发
http://localhost:8080/app/index/index.html