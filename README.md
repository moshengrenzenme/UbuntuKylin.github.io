# ukui-wiki
本项目为ukui-wiki，欢迎各位同事添加内容

## 添加规则
本wiki使用hexo框架搭建，使用githubpages发布，故创建了两个分支，源代码存放于hexo分支，网页存放于master分支。项目默认位于hexo分支。新增文章在source/_posts目录下，该目录下的文章会根据路径产生相应的分级，文章请使用markdown编写，图片请采用外链的模式。请注意:

- 由于我司没有规范的github管理，大家都拥有项目权限，所以请各位务必以先fork再pr的模式来贡献项目。**不要直接往项目里提交代码！！！！不要直接往项目里提交代码！！！！不要直接往项目里提交代码！！！！**

- 请各位每次进行提交前务必先执行git pull命令，第一次将项目clone到本地时需要在项目目录执行npm install。

- 每次新增文章请使用hexo new + 文章名的形式，再将其放置到相应目录。

- 提交到网页需要执行命令`hexo d -g`，请不要使用该命令，该命令由且仅由项目管理员在审核内容结束后从主项目来执行。各位修改请在本地执行`hexo g`，`hexo s`来测试。

- 请各位仅对hexo分支进行修改，并在每次提交前执行`hexo clean`命令。
