# YukariFans_MkDocs

#### 介绍

<!-- **以下是 Gitee 平台说明，您可以替换此简介**
Gitee 是 OSCHINA 推出的基于 Git 的代码托管平台（同时支持 SVN）。专为开发者提供稳定、高效、安全的云端软件开发协作平台
无论是个人、团队、或是企业，都能够用 Gitee 实现代码托管、项目管理、协作开发。企业项目请看 [https://gitee.com/enterprises](https://gitee.com/enterprises) -->
泛VOICEROID工具导航站

~~因为是节雨竹的仓库所以就不写俏皮话了&emsp;--DE~~

~~这种事情随便啦~~

<br/>

#### 软件架构

使用MkDocs方便地将多个Markdown文件生成静态网页。
使用的主题是MkDocs-Material, [英文参考文档](https://squidfunk.github.io/mkdocs-material/) (中文的太旧了)。

##### 使用的插件的作用说明

插件的作用全写在mkdocs.yml配置文件里了

<br/>

#### 安装教程

1.  安装Python3.9
2.  使用<code>pip install -r requirements.txt</code>安装Python依赖库

> 其中 jieba库 是为了让搜索功能支持中文的进行分词的库，具体使用参考https://zhuanlan.zhihu.com/p/411854801


* 如果电脑中已经安装了不同版本的Python, 或想方便地从零开始安装Python, 推荐用Miniconda/Conda进行Python版本管理。
  * 参考[Miniconda安装及使用--小白上路](https://zhuanlan.zhihu.com/p/133494097)
  * 创建需要的环境：`conda create -n name_of_this_environment python=3.9.5 `
  * [Miniconda的常用指令](https://zhuanlan.zhihu.com/p/386906874)


<br/>

#### 使用说明

##### 如何在本地查看页面

1.  进入<code>YukariFans_Mkdocs/YukariFans</code>目录（<code>mkdocs.yml</code>同级目录）
2.  使用<code>mkdocs serve</code>启动本地服务器
3.  通过浏览器访问给出的地址（默认<code>http://127.0.0.1:8000/</code>）

##### 如何将页面上传

1.  进入<code>YukariFans_Mkdocs/YukariFans</code>目录（<code>mkdocs.yml</code>同级目录）
2.  使用`mkdocs gh-deploy
`来上传文档到gitee-page中

<!-- #### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
-->