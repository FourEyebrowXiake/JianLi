# 简历
应聘职位：前端开发工程师
## 个人信息
林锦，男，1995年生，2018年本科毕业生，就读于厦门大学嘉庚学院,计算机与科学技术专业。
- 手机：18859693867
- Email: fourfishxiake@gmail.com
- Blog: [http://foureyebrowxiake.github.io/](http://foureyebrowxiake.github.io/)
- Github: [https://github.com/FourEyebrowXiake](https://github.com/FourEyebrowXiake)
- 知乎重度用户：[四条眉毛](https://www.zhihu.com/people/fish-86-23/activities)

#### 能力简述
- 语言：
	- 熟悉HTML：知道HTML中常用的meta，理解标签语义化和HTML的渲染解析过程。
	- 熟悉CSS：能实现组件的具体样式和常见布局，熟悉scss语法和知道css-module的原理。
	- 熟悉Javascript: 看过《EloquentJavaScript》和《Javascript编程精粹》。看书期间，有坚持做[习题](https://github.com/FourEyebrowXiake/Eloquent-JavaScript-Exercise)和写[博客](http://foureyebrowxiake.github.io/)。 知道JS闭包的底层运行机制和了解函数式编程。

	- 了解Java：独立完成过一个完整的Android应用：[Hot Movie](https://github.com/FourEyebrowXiake/HotMovie)。
- 框架： 熟悉React，当前的博客就是用react写的。在egghead.io上听完了redux作者的基础课，并且看完了redux官方文档的高级部分，了解redux的整个运转过程。

- 工具： 开发中常用 git 、webpack、atom和Android studio。

- 有不错的自学能力：阅读经典书籍，写博客。课外积极的在course，Udacity上学习。现在正在学习斯坦福的cs142:web application，来完善自己的知识体系。

## 项目经历
#### [个人博客](foureyebrowxiake.github.io)（[https://github.com/FourEyebrowXiake/MyNewBlog](https://github.com/FourEyebrowXiake/MyNewBlog)）
- 情景: 为了实践React的知识，准备写一个静态博客练手。使用静态博客生成器Gatsby来搭建博客，省去配置webpack的麻烦。你可以在里面写redux和react，像平常一样，还可以直接使用Graphql获取数据，再传给组件。

- 动作: 我用react构建了四个基本页面。组件在页面间复用，以减少代码量。用Gatsby提供的插件加载文件，接着将Markdown文件渲染成网页。用graphql查询数据，并把数据传给组件。期间多次遇到
Forced reflow。其中有一次是因为react-lazyload查找元素太过耗时,才引起重排。
- 结果：现在，已经把博客发到github page上了。页面切换流畅，博客的基本功能正常。

#### REST API（[https://github.com/FourEyebrowXiake/REST-API](https://github.com/FourEyebrowXiake/REST-API)）
- 情景：实践 Node.js 和Mongodb等知识，构建一个博客的 REST API。
- 动作：使用 Express 搭建 REST API，配合Mongodb存储数据。最后，把项目部署到阿里云上。地址是“47.94.252.67”,API详情请见[Github](https://github.com/FourEyebrowXiake/REST-API)。
- 结果：完成了基本功能，如修改评论、投票，上传问题等。并通过增加一组HTTP首部字段，允许服务器声明哪些源站有权限访问哪些资源，来筛选跨域请求。

#### HotMovie 安卓应用（[https://github.com/FourEyebrowXiake/HotMovie](https://github.com/FourEyebrowXiake/HotMovie)）
- 情景：开发一款有实用型的Android应用。App的内容会实时更新，有平板布局，保证数据持久化和网络的集中调用。此外，App界面也力求美观。
- 动作：应用由我一人开发，历经三个版本。第一个版本只是简单地使用retrofit抓取数据，并显示。第二个版本使用content provider存储数据，并添加了额外的小功能。最后个版本，添加了平板布局，并保证数据的实时更新。
- 结果：APP支持离线可用。数据能动态更新。界面运行流程，所用网络调用，数据库读写都不在UI线程进行。
