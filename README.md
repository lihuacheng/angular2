
<h3 style="color:red;">angular2 项目整合</h3>
<hr stye="height:1px;color:block;">

#步骤1. 设置开发环境

    在开始工作之前，我们必须设置好开发环境。

    如果你的机器上还没有Node.js®和npm，请先安装它们。

    请先在终端/控制台窗口中运行命令 node -v 和 npm -v， 来验证一下你正在运行 node 6.9.x 和 npm 3.x.x 以上的版本。 更老的版本可能会出现错误，更新的版本则没问题。
    然后全局安装 Angular CLI 。

    #npm install -g @angular/cli
#步骤2. 创建新项目

    打开终端窗口。

    运行下列命令来生成一个新项目以及应用的骨架代码：

    #ng new my-app
    
    请耐心等待。 创建新项目需要花费很多时间，大多数时候都是在安装那些npm包。
#步骤3. 启动开发服务器

    进入项目目录，并启动服务器。

    #cd my-app
    
    #ng serve --open
    
    ng serve命令会启动开发服务器，监听文件变化，并在修改这些文件时重新构建此应用。

使用--open（或-o）参数可以自动打开浏览器并访问http://localhost:4200/。

本应用会用一条消息来跟你打招呼：

The app works!
