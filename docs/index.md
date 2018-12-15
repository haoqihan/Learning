# mkdocs 的基本使用
- 第一步:下载 pip install mkdocs
- 第二步:创建项目:mkdocs new 项目名
- 第三步:cd 项目名
- 第四步:启动项目:mkdocs serve

# 更换主题
- 进入mkdocs.yml里添加 theme: readthedocs可以修改主题

# 放入github上
- 进入settings里
- 到pages下source选择gh-pages branch
- 注释:这里是建立在你把项目放入github里了,你还需要建立一个gh-pages分支,专门存放mkdocs生成的html代码

# 快速提交github
- mkdocs gh-deploy :这是生成一个site文件并把它推送到仓库



