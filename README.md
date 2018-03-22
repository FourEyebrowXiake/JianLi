# [简历](https://github.com/FourEyebrowXiake/JianLi/blob/master/README.md)

应聘职位：前端开发工程师

## 个人信息

林锦，男，1995 年生，2018 年本科毕业生，就读于厦门大学嘉庚学院,计算机与科学技术专业。

* 手机：18859693867
* Email: fourfishxiake@gmail.com
* Blog: [https://foureyebrowxiake.github.io/](https://foureyebrowxiake.github.io/)
* Github: [https://github.com/FourEyebrowXiake](https://github.com/FourEyebrowXiake)

#### 能力简述

- 语言：

  - 熟悉 HTML：知道 HTML 中常用的 meta，理解标签语义化和 HTML 的渲染解析过程。

  - 熟悉 CSS：能实现组件的具体样式和常见布局，熟悉 sass。

  - 熟悉 Javascript: 看过《EloquentJavaScript》，《Javascript 编程精粹》和《你不知道的 javascript 上》。看书期间，有坚持做[习题](https://github.com/FourEyebrowXiake/Eloquent-JavaScript-Exercise)和写[博客](http://foureyebrowxiake.github.io/)。
  - 了解java：独立完成过一个android应用：[HotMovie](https://github.com/FourEyebrowXiake/HotMovie)

- 框架： 熟悉 React，当前的博客就是用 react 写的。在 egghead.io 上听完了 redux 作者的基础课，并有 redux 的实际开发经验。
- 工具： 开发中常用 git 、webpack、vscode 和 Android studio。
- 有不错的自学能力：阅读经典书籍，写博客，参加 coursera，Udacity 等在线课程

## 项目经历

#### Readable ([https://github.com/FourEyebrowXiake/Readable](https://github.com/FourEyebrowXiake/Readable))

* 情景：为了加深对 redux 的了解，采用 react 和 redux 构建一个小型社区类网站的前端。网站的文章和评论要能编辑、排序，删除和创建。发挥单页面应用的优点，提高网站的响应速度。

* 动作： 
	1. 按功能组织代码文件，并确定各个模块的边界。
	2. 设计 state 树。保证一个模块只控制一个 state。使用范式化的数据结构存储 state 数据，并保证 state 树形结构扁平。 
	3. 设计 action 的构造函数和 reducer。 
	4. 开始构建实际应用。期间使用了 redux Devtool 等辅助工具来提高开发效率。

* 结果：项目顺利完成。期间实践了不少 redux 的新特性，使代码更加简洁。尝试了新版的 react-route，get 到了新技能，如通过 url 控制组件內状态。当然，还有不少不足。如没有考虑 React 组件的性能优化，正借助 React perf 来进行优化，并使用 reselect 提供数据获取性能。

#### [个人博客](https://foureyebrowxiake.github.io/)（[https://github.com/FourEyebrowXiake/MyNewBlog](https://github.com/FourEyebrowXiake/MyNewBlog)）

* 情景: 为了实践 React 的知识，准备写一个静态博客练手。使用静态博客生成器 Gatsby 来搭建博客，省去配置 webpack 的麻烦。你可以在里面写 redux 和 react，像平常一样，还可以直接使用 Graphql 获取数据，再传给组件。

* 动作: 我用 react 构建了四个基本页面。组件在页面间复用，以减少代码量。用 Gatsby 提供的插件加载文件，接着将 Markdown 文件渲染成网页。用 graphql 查询数据，并把数据传给组件。期间遇到几次
  Forced reflow，其中有一次是因为 react-lazyload 查找元素太过耗时,才引起重排。
* 结果：现在，已经把博客发到 github page 上了。页面切换流畅，博客的基本功能正常。

#### REST API（[https://github.com/FourEyebrowXiake/REST-API](https://github.com/FourEyebrowXiake/REST-API)）

* 情景：实践 Node.js 和 Mongodb 等知识，构建一个博客的 REST API。

* 动作：使用 Express 搭建 REST API，配合 Mongodb 存储数据。API 详情请见[here](https://github.com/FourEyebrowXiake/REST-API)。
* 结果：完成了基本功能，如修改评论、投票，上传问题等。并通过增加一组 HTTP 首部字段，允许服务器声明哪些源站有权限访问哪些资源，来筛选跨域请求。
