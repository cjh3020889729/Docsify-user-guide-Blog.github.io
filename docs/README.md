<center><font size=64>Docsify Tutorial</font><small>0.1</small></center>

> 一个简单的docsify文档上手教程(学习笔记)

- 一、安装Docsify
  - [安装Node.js](./zh-cn/安装Node_js): `docsify`所依赖的安装环境
    - Update Date: _2022.1.19_
  - [npm下载docsify](./zh-cn/npm下载docsify): 通过`npm`下载`docsify`工具
    - Update Date: _2022.1.19_

* 二、快速构建First Doc
  * [初始化构建](./zh-cn/初始化构建): 构建一个最基本的`doc`结构
    * Update Date: _2022.1.20_
  * [解析index.html](./zh-cn/解析html "Docsify Tutorial"): 介绍index.html的基本使用/功能
    * Update Date: _2022.1.20_
  * [解析README.md](./zh-cn/解析README "Docsify Tutorial"): 编写第一个文档页面
    * Update Date: _2022.1.20_
  * [添加侧边栏](./zh-cn/添加侧边栏): 为`doc`添加`侧边栏`，便捷浏览整个文档
    * Update Date: _2022.1.22_
  * [完善侧边栏内容](./zh-cn/完善侧边栏内容 "Docsify Tutorial"): 添加多个文档页面，丰富文档内容
    * Update Date: _2022.1.22_
  * [添加导航栏](./zh-cn/添加导航栏): 为`doc`添加`导航栏`，快速浏览常用内容
    * Update Date: _2022.1.22_
  * [导航栏里的链接](./zh-cn/导航栏里的链接 "Docsify Tutorial"): 导航栏跳转外部链接
    * Update Date: _2022.1.22_
  * [添加文档封面](./zh-cn/添加文档封面  "Docsify Tutorial"): 将在显示`README.md`首先显示封面作为文档入口页面
    * Update Date: _2022.1.22_
  * [实现一个文档](./zh-cn/实现一个文档  "Docsify Tutorial"): 实现第一个文档，基本配置到内容填充
* 三、添加常用插件
  * [字数统计](./zh-cn/字数统计   "Docsify Tutorial"): 统计当前页面(md)所含`字数`以及`大概阅读时间`
    * Update Date: _2022.1.20_
  * [代码高亮](./zh-cn/代码高亮   "Docsify Tutorial"): 针对`不同语言代码`进行高亮，方便语法阅读
    * Update Date: _2022.1.20_
  * [代码复制](./zh-cn/代码复制   "Docsify Tutorial"): 支持复制`文本代码格式`，方便复制粘贴代码内容
    * Update Date: _2022.1.20_
  * [支持Mermaiid](./zh-cn/支持Mermaid   "Docsify Tutorial"): 支持`Markdown`中的`Mermaid`绘图插件
    * Update Date: _2022.1.20_
* 四、进阶小技巧
  * [tab选择查看](./zh-cn/tab选择查看   "Docsify Tutorial"): 根据需要选择合适的内容查看
  * [details收纳展示](./zh-cn/details收纳展示   "Docsify Tutorial"): 根据需要展开内容

- 五、部署应用
  - [Github-Pages文档部署](./zh-cn/Pages文档部署   "Docsify Tutorial"): 将本地文档部署到互联网，方便实时浏览



> 如果有文档撰写问题，可以浏览右上角的`文档撰写资料`哦~



```mermaid
flowchart TB
	subgraph Answer
	    direction LR
        subgraph Question
            direction TB
            id1[有一些使用问题/阅读问题]
        end

        subgraph Ask
            direction TB
            id2([可以联系我])
        end

        subgraph Link
            direction TB
            id3[1.微信: cjh3020889729]
            id4[2.QQ: 3020889729]
            id5[3.在仓库提issue]
            
            id3 <--> id4
            id4 <--> id5
        end
    
        Question --> Ask
        Ask --> Link
    end

```



