# c89marui
c89frame
````
|--app(开发者写代码的地方)
|   |--home(前台模块 前台就是用户能看到的东西 用来储存主要是为访客服务，向他们展示商品)
|   |   |--controller(储存控制器类  控制器是整个网站的逻辑实现主体，是最核心部分 控制器是一个类方法)
|   |   |--view(文档视图模型部分)
|--houdunwang(框架的核心内容 分装的类)
|   |--core(控制器)
|   |--model(数据模型 分装的类)
|   |--view(视图 )
|--public(入口、静态资源)
|   |--static(用来储存静态资源  可以被所有实例对象所共享的资源（使用访问）)
|   |--view(公共模板文件)
|--system
|   |--config(配置目录)
|   |--model(数据模型目录  演示模型文件，定义一一对应的数据模型)
