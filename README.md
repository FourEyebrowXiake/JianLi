# 简历
应聘职位：前端开发工程师
## 个人信息
林锦，男，2018年本科毕业生，就读于厦门大学嘉庚学院（二本）计算机与科学技术专业。

| 手机 | email |
| ---- | ---- |
| 18859693867 | fourfishxiake@gmail.com|

| github | 个人博客 |
| ---- | ---- |
|[https://github.com/FourEyebrowXiake](https://github.com/FourEyebrowXiake)|[http://foureyebrowxiake.github.io/](http://foureyebrowxiake.github.io/)|

### 能力简述
- 语言：
	- 了解HTML：知道常用的meta和标签语义化的目的。

	- 了解CSS:熟悉Flexbox。知道transform的变化只会影响Composite,而margin-left的改变会影响Layout、Paint和Composite。

	- 熟悉Javascript:看过《EloquentJavaScript》和《Javascript编程精粹》。看书期间，有坚持做[习题](https://github.com/FourEyebrowXiake/Eloquent-JavaScript-Exercise)和写[博客](http://foureyebrowxiake.github.io/)。

	- 了解Java：写过一个完整的Android应用：[Hot Movie](https://github.com/FourEyebrowXiake/HotMovie)。
- 框架： 熟悉React和Redux。当前的博客就是用react写的。在egghead.io上听完了redux作者的基础课和一部分高级课，了解redux运转的整个过程。

- 工具： 开发中常用 git 、webpack，atom 和Android studio。
- 有不错的自学能力：阅读经典书籍，写博客。课外积极的在course、Udemy，和Udacity上学习。

## 项目经历
### 个人博客
[http://foureyebrowxiake.github.io/](http://foureyebrowxiake.github.io/)
[https://github.com/FourEyebrowXiake/MyNewBlog](https://github.com/FourEyebrowXiake/MyNewBlog)
- 情景: 学了React，一直想找个东西练练手。无意间发现了Gatsby，这个静态博客生成器。它真的非常的快，而且很容易上手。你可以在里面写redux，像平常一样，也可以直接使用Graphql获取数据，再传给组件。因为它不在客户端使用redux，而在"npm run build"和"Gatsby develop"的时候使用。

- 动作: 我用react构建了四个基本页面。组件在页面间复用，以减少代码量。用Gatsby提供的 插件加载文件并创建节点，接着将Markdown文件渲染成网页。用Graphql查询数据，并把数据传给组件。期间多次遇到
Forced reflow。其中有一次是因为react-lazyload查找元素,才引起重排。
- 结果：现在，已经把博客发到github page上了。页面切换流畅，博客的基本功能正常。正在使用Lighthouse审查应用的质量，力求拿到满分。

### REST API
[https://github.com/FourEyebrowXiake/REST-API](https://github.com/FourEyebrowXiake/REST-API)
- 情景：实践 Node.js 和Mongodb等知识，构建一个博客的 REST API。
- 动作：使用 Express 搭建 REST API，配合Mongodb存储数据。最后，把项目部署到阿里云上。地址是“47.94.252.67”。
- 结果：完成了基本功能，如修改评论、投票，上传问题等。并通过增加一组HTTP首部字段，允许服务器声明哪些源站有权限访问哪些资源，来筛选跨域请求。

### HotMovie 安卓应用
[https://github.com/FourEyebrowXiake/HotMovie](https://github.com/FourEyebrowXiake/HotMovie)
- 情景：开发一款有实用型的Android应用。App的内容会实时更新，有平板布局，保证数据持久化和网络的集中调用。此外App界面也力求美观。
- 动作：应用由我一人开发，历经三个版本。第一个版本只是简单地使用retrofit抓取数据，并显示。第二个版本使用content provider存储数据，并添加了额外的小功能。最后个版本，添加了平板布局，保证数据的实时更新。
- 结果：应用支持离线可用。数据能动态更新。界面运行流程，所用网络调用，数据库读写都不在UI线程进行。
