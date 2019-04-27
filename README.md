# POINTS
	1.不要在github desktop打开gh-pages分支（没有更改的必要，该分支仅用于生成网页）
	2.写博文后只需要以下操作：在本地使用hexo d提交，然后使用girhub desktop同步（写明更新的博文名称）
	3.master分支的public文件夹即为hexo提交给gh-pages分支的文件
	4.同步theme文件时，要删除.git/.gitignore文件才能成功
	5.atom编辑器中黄色表示未提交的改变，灰色为忽略提交的文件

# 不需要提交的文件
	.deploy_git 应该为hexo的发布插件 hexo g-------------------不会改变
	.git        github控制版本的文件       -------------------自动改变
	node_modules应该为安装hexo时下载node.js插件----------------不会改变

# 草稿与文章
	草稿相当于隐藏的文章
	https://blog.csdn.net/wizardforcel/article/details/40684575

# 主题使用方法详解
	1.
	2.Next
	https://theme-next.iissnan.com/getting-started.html
	3.archer主题的安装及配置方法
	https://github.com/fi3ework/hexo-theme-archer
	4.怎么把Hexo网站备份到GitHub上
	https://www.asroads.com/2018/08/10/other/%E6%80%8E%E4%B9%88%E6%8A%8AHexo%E7%BD%91%E7%AB%99%E5%A4%87%E4%BB%BD%E5%88%B0GitHub%E4%B8%8A/
