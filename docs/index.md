# mkdocs 的基本使用

- 下载      pip install mkdocs
- 创建项目  mkdocs new 项目名
- cd 项目名
- 启动项目:mkdocs serve


## 更换主题
- 进入mkdocs.yml里添加 theme: readthedocs可以修改主题

## 放入github上
- 进入settings里
- 到pages下source选择gh-pages branch
- 注释:这里是建立在你把项目放入github里了,你还需要建立一个gh-pages分支,专门存放mkdocs生成的html代码

## 快速提交github
- mkdocs gh-deploy :这是生成一个site文件并把它推送到仓库

## mkdocs的基本信息
- site_name：站点的名称 比如我们的是这么设置的：
- pages: 导航页面
- theme: 站点主题
- docs_dir: Markdown文档目录
- site_dir: 生成的静态网页目录
- dev_addr: 本地调试的监听地址和端口
- markdown_extensions: 一些扩展功能








